---
title: Home
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# Focus on writing good documentation
{: .fs-9 }

The Archetypal fork of Just the Docs gives your documentation a jumpstart with a responsive Jekyll theme that is easily customizable and hosted on GitHub Pages.
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/archetypal/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Getting started

This fork is specialized for GitHub Pages to utilize [GitHub Metadata](https://jekyll.github.io/github-metadata/) exposed through [site.github](https://jekyll.github.io/github-metadata/site.github/).

### Dependencies

Just the Docs is built for [Jekyll](https://jekyllrb.com), a static site generator. View the [quick start guide](https://jekyllrb.com/docs/) for more information. Just the Docs requires no special plugins and can run on GitHub Pages' standard Jekyll compiler. The [Jekyll SEO Tag plugin](https://github.com/jekyll/jekyll-seo-tag) is included by default (no need to run any special installation) to inject SEO and open graph metadata on docs pages. For information on how to configure SEO and open graph metadata visit the [Jekyll SEO Tag usage guide](https://jekyll.github.io/jekyll-seo-tag/usage/).

### Quick start: Use as a GitHub Pages remote theme

1. Enable [GitHub Pages](https://pages.github.com/) for your organization or project site.
2. Add Just the Docs to your `_config.yml` as a [remote theme](https://github.com/benbalter/jekyll-remote-theme)
```yaml
remote_theme: archetypal/just-the-docs@v0.5.2
```
<small>You must have GitHub Pages enabled on your repo, one or more Markdown files, and a `_config.yml` file.</small>

### Configure Just the Docs

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

## Metadata

Site metadata available (not page specific):
```javascript
{{ site | jsonify }}
```

Site pages metadata available:
```javascript
{{ site.pages | jsonify }}
```


Page metadata available:
```javascript
{{ page | jsonify }}
```

---

## About the project

Just the Docs is &copy; 2017-{{ "now" | date: "%Y" }} by [Patrick Marsceill](http://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/pmarsceill/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/pmarsceill/just-the-docs/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.
