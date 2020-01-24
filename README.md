# Website for BIOL 3272/5272 Spring 2020

**Link for website:** https://biol3272-5272.github.io/biostats2020

This is the Github page for the course website.

## Modifying content for the course

To preview changes locally, install [Jekyll](https://jekyllrb.com/docs/installation/) and run the following from inside the Github repo each time you want to preview your changes:

```bash
bundle exec jekyll serve
```

This will generate a server address that you can paste into your browser to see changes locally before pushing the changes to Github.

All draft markdown files can be stored in `_drafts`. Even if these are pushed to Github, these will not be shown on the website.

**Home page**

To update content, modify the markdown file under `_pages/home-page.md`.

**Syllabus**

To update content, modify the markdown file under `_pages/syllabus.md`.

**Schedule**

To update content, modify the markdown file under `_pages/schedule.md`. Google spreadsheet of the schedule is embedded on the page and gets updated automatically.

**Modules**

These consist of links to all slides and in-class material. Each markdown file contains material for one week of class. For new classes/weeks, add markdown files with the naming scheme `year-month-day-weekXX.md`.

**Assignments**

Links to assignments and Canvas submission links. Each markdown file contains material for one submission. For new submission links, add markdown files with the naming scheme `year-month-day-assignmentXX.md`.

**Additional Resources**

To update content, modify the markdown file under `_pages/resources.md`.

#### Additional documentation for modifying site content

Please see [this reference](https://github.com/academicpages/academicpages.github.io/blob/master/_pages/archive-layout-with-content.md) for a variety of common markup showing how the theme styles them.

#### Adding anchors to headings within .md files (aka smartlinks)

See here for how to do this: https://github.com/fefong/markdown_readme#anchor-links

Or here: https://gist.github.com/rachelhyman/b1f109155c9dafffe618

---

## Helpful instructions for website setup

A Github Pages template for academic websites. This was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

I think I've got things running smoothly and fixed some major bugs, but feel free to file issues or make pull requests if you want to improve the generic template / theme.

### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file.

# Instructions

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right.
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

# Changelog -- bugfixes and enhancements

There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch.

To support this, all changes to the underlying code appear as a closed issue with the tag 'code change' -- get the list [here](https://github.com/academicpages/academicpages.github.io/issues?q=is%3Aclosed%20is%3Aissue%20label%3A%22code%20change%22%20). Each issue thread includes a comment linking to the single commit or a diff across multiple commits, so those with forked repositories can easily identify what they need to patch.
