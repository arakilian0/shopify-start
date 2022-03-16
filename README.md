# shopify-start
This is all that's needed to start developing your own Shopify Theme.
## Files
1.<span> </span>`layout/theme.liquid`<br>
```html
<html>
<head>
    {{ content_for_header }}
    <title>{{ shop.name }} - {{ page_title }}</title>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title>untitled</title>
</head>

<body>
    {{ content_for_layout }}
</body>
</html>
```

2.<span> </span>`templates/index.liquid`
```html
<-- start building... -->
```
