
# Organization

This document describes how files and directories are organzied in this repository.

*Legend:*

* `!` technical files typically not edited by user contributor
* `~` a file visible on the Github website, not the chalcid website

*Manifest:*

* ! `_config.yml` - The Jekyll configuration for this website 
* `_diversity/` - Each file becomes an individual taxon page.
* `_education/` - Each file becomes a card on the Education section
* `_education/pages/` - Each file is a page leading from a card in the Outreach section, or another page here.
* ! `_includes/` - Each file is a repeated section in the website. This is a technical section
* `_outreach/` - Each file becomes a card in the Outreach section
* `_outreach/pages` - Each file is a page leading from a card in the Outreach section, or another page here.
* ! `_sass` - CSS styling rules for the wepage
* ! `404.html` - The webpages that users get when they reach a broken link.
* `assets/` - CSS files.  Our binary (image, pdf, etc.)  assets are stored in the TaxonWorks chalcid project or on other servers.
* ! `CNAME` - A Github configuration file. DO NOT MODIFY.
* !~ `CODE_OF_CONDUCT.md` - The code of conduct for contributers to this project.
* ~ `CONTRIBUTING.md` - The code of conduct for contributers to this project.
* ! `doc/` - The generated website.  DO NOT MODIFY DIRECTLY.  This is produced by Jekyll.
* ! `Gemfile` and `Gemfile.lock` - Ruby dependencies
* !~ `LICENSE.md` - The license for this website.
* ! `node_modules` - Javascript for the site
* ~ `README.md` - Intoductory file that user sees at the Github repository under these files 
* ! `script/` - Build script. DO NOT MODIFY.
* `site/` - HTML templates for specific parts of the website.  Cards, and pages are rendered inside these templates
* ! `yarn.lock` - Javascript metadata. DO NOT MODIFY.

* Summary:*

Content contributed by users ends up in one of:

* `_diversity/`
* `_education/`
* `_outreach/`
* `site/` 

_All files in these directories are canditates for changes directly from Github._

