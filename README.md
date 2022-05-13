## Recommended tags

``` html
<meta charset="utf-8">
<meta http-equiv="x-ua-compatible" content="ie=edge; chrome=1">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">

<title>Page Title</title>
<meta name="description" content="150 words">

<meta http-equiv="Content-Security-Policy" content="default-src 'self'">
<meta name="robots" content="index,follow">

<link rel="shortcut icon" type="image/ico" href="/favicon.ico">
<link rel="canonical" href="http://">

<meta property="og:url" content="http://" />
<meta property="og:type" content="website" />
<meta property="og:title" content="The page title" />
<meta property="og:description" content="" />
<meta property="og:image" content="http://" />

<meta name="twitter:card" content="summary">
<meta name="twitter:site" content="@site_account">

```
## Usage

### Lang attribute
``` html
<html lang="en">
```
Language is included in the opening HTML tag

https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/lang

---

### Title tag
``` html
<title>This is the page title</title>
```
Title tag unique for every page

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title

---

### Description
``` html
<meta name="description" content="150 words">
```
Meta description is what shows up on the search engine results page (SERP)

https://developers.google.com/search/docs/advanced/appearance/snippet

---

### Security
``` html
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">
```
Mitigate and report XSS attacks

https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP

---

### More meta tags
Meta charset important for correct rendering in browsers

Meta robots tag only if you use noindex or nofollow

Meta viewport for responsive design

Meta canonical tag addresses duplicate content issues with multiple pages/URLs

---

### Open graph
``` html
<meta property="og:url" content="http://" />
<meta property="og:type" content="website" />
<meta property="og:title" content="The page title" />
<meta property="og:description" content="" />
<meta property="og:image" content="http://" />
```

https://developers.facebook.com/docs/sharing/webmasters

---

### Twitter
``` html
<meta name="twitter:card" content="summary">
<meta name="twitter:site" content="@site_account">
```

https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/markup

---

https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML


## Testing
* Twitter: https://dev.twitter.com/docs/cards/validation/validator
* Facebook: https://developers.facebook.com/tools/debug
* Google: http://www.google.com/webmasters/tools/richsnippets
* Pinterest: http://developers.pinterest.com/rich_pins/validator/
* Google Structured Data: https://developers.google.com/structured-data/testing-tool/
