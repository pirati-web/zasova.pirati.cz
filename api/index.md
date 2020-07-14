---
layout: blank
---

# [pirati.cz]({{'/' | relative_url}})/api

Přístupné je:

- sitemap: [sitemap.xml]({{'/sitemap.xml' | relative_url}})
- aktuality: [api/posts.json]({{ '/api/posts.json' | relative_url}})
- lidé: [api/people.json]({{'/api/people.json' | relative_url}})
- tags [api/tags.json]({{'/api/tags.json' | relative_url}})
- stručný obsah [ api/search.json]({{'/api/search.json' | relative_url}})

## Přístup

**JavaScript**:

```javascript
$.get('/api/search.json')
    .done(function(data) {
        console.log('Úspěch:');
        console.log(data);
    })
    .fail(function(data) {
        console.log('Error:');
        console.log(data);
    });
});
```

**Python**:

```python
from urllib.request import urlopen
from json import loads

url = 'http://localhost:4000/api/search.json'

response = urlopen(url)
text = response.read().decode("utf-8")
var = loads(text)
```
