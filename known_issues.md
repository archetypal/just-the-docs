# Known Issues

## Liquid Exception: Liquid error (line 50): comparison of Array with Array failed in /_layouts/default.html

This occurs when the title of a page is a number value and there is no _data/nav.yml:

```markdown
---
title: 404
---

# Page not found

The page you requested could not be found. Try using the navigation or search.

```

