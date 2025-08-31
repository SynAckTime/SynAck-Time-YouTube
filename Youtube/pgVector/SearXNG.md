## SearXNG Tips

```
API URL = https://searchurl.com/search?q=
```

### Edit Settings.yml

Be sure to add json to this setting in order to allow n8n the ability to search.

```
  # remove format to deny access, use lower case.
  # formats: [html, csv, json, rss]
  formats:
    - html
    - json
```
