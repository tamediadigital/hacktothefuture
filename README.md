---
layout: page
title: How to Add Your Hack to this Website
permalink: /add-your-hack/
---

Here's how to add your hack project to this website...

### The Quick Version

1. Fork the project on github - head to [https://github.com/tamediadigital/hacktothefuture](https://github.com/tamediadigital/hacktothefuture) and hit the "Fork" button top right
2. After you fork, `git clone` the forked project from your own account (or whereever you forked to) to your local machine
3. Add a file to the `_hacks/` sub-directory containing your project - see `_hacks/example.markdown` for a template. You can use standard [markdown for formatting](https://www.markdownguide.org/cheat-sheet/).
4. Optionally test the looks good locally with jekyll:
- `bundle exec jekyll serve --config _config.yml,_config_dev.yml`
5. `git add`, `git commit` and `git push` your changes to your forked repo
6. Open a pull request request back to the main repo using the "Contribute" button
7. Bug harry.fuecks on Slack to merge the changes
8. Check that the results look right at [https://tamediadigital.github.io/hacktothefuture/](https://tamediadigital.github.io/hacktothefuture/)

### More Details

The generated using [jekyll](https://jekyllrb.com/) - a static website generator, written in Ruby. Jekyll is supported by [Github Pages](https://pages.github.com/), so whenever changes are made to [this repository](https://github.com/tamediadigital/hacktothefuture), github automatically runs them through jekyll to generate [this site](https://tamediadigital.github.io/hacktothefuture/).

#### Formatting Pages

Pages with the `.md` or `.markdown` are handled by jekyll as being formatted with [markdown](https://www.markdownguide.org/cheat-sheet/).

You can also format pages using HTML by giving them the `.html` extension and take advantage of using the [Liquid template language](https://jekyllrb.com/docs/liquid/).

In either case, if you're adding a hack project, import is you put this at the top of the page (whether HTML or markdown);

```
---
layout: hack
title: Name of your project
---
```

...and add it to the `_hacks` sub-directy.

#### Running jekyll locally

If you have the code cloned locally, you can generate the site and view it locally using jekyll - follow the installation instructions up to step 2 [here](https://jekyllrb.com/docs/) then run jekyll locally with;

```
bundle exec jekyll serve --config _config.yml,_config_dev.yml
```

You will now be able to view the site on [http://localhost:4000/](http://localhost:4000/). Be warned that there are differences in paths locally vs. on the live website - see the `url` and `baseurl` config options in `_config.yml` vs. `_config_dev.yml`
