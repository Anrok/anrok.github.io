Then OpenAPI Specification is given by `dist.yaml`. Build the static HTML from the OpenAPI Specification using

```
redoc-cli build dist.yaml -o index.html \
--options.theme.rightPanel.backgroundColor=#201A36 \
--options.theme.logo.gutter=20px 
```
