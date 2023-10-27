# AIEA Website

This is the website for the Association Internationale des Études Arméniennes, created with Jekyll and hosted on Github Pages. The site uses [the Polyglot plugin](https://github.com/untra/polyglot) for internationalization.

Guidelines for maintainers:

- The site is currently set to support English, French and Armenian localization, with English as default.
- New main pages should be produced in this directory, written in [Markdown](https://github.github.com/gfm/), with a header to indicate its title and language. See [membership-en.markdown](membership-en.markdown) / [membership-fr.markdown](membership-fr.markdown) for an example. Translations of the same page should be named identically, except for the language tag at the end of the filename.
- New posts go in [_posts/&lt;language&rt;](_posts), depending on the language in which it is made. We should aim to have everything translated, but if something can't be translated, there still needs to be a post in at least the `en/` folder, whichever language it is written in, so that it will appear on all language versions.
- The site will rebuild automatically when changes are made to any files here.