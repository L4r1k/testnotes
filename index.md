---
layout: default
title: Home
nav_order: 1
description: "Home Page"
permalink: /
---

# Home

| Test 1 | Test 2 |
| :- | :- |
| Test val 1 | Test val 2 |

```json
{
	"test_key": "test_val"
}
```

<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

<script> const toggleDarkMode = document.querySelector('.js-toggle-dark-mode') const cssFile = document.querySelector('[rel="stylesheet"]') const originalCssRef = cssFile.getAttribute('href') const darkModeCssRef = originalCssRef.replace('just-the-docs.css', 'dark-mode-preview.css') addEvent(toggleDarkMode, 'click', function(){ if (cssFile.getAttribute('href') === originalCssRef) { cssFile.setAttribute('href', darkModeCssRef) } else { cssFile.setAttribute('href', originalCssRef) } }) </script>