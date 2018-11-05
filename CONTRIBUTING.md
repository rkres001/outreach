
# Contributing

This document covers the "technical" approach to updating this website. There are many ways of doing this, but in general they follow two approaches, 1) editing the files directly on Github or 2) editing the files on your local machine.

## Using Github

This approach is useful when you:

* ave a Github account
* want to modify existing content

It is possible to use the Github website to edit the files, and therefor content of the website.  

## Developing locally

This approach is useful when you:

* are familiar with the basics of git
* want to add new files
* want to test the outcome of your modifications on your local machine by viewing the changes as a website there

### Oveview

We use Git to store files, [Jekyll](https://jekyllrb.com/) to build the website, and [Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/) to style the website. Content is marked up (simple layouts, italic, bold, sections, etc.) using HTML or [Markdown](https://guides.github.com/features/mastering-markdown/). The website is served using [Github pages](https://pages.github.com/) There are many tutorials for all of these technologies, a web search for `Jekyll tutorial` for example will find you a better explanation of the core basics than we can provide here.  

These are the general steps:

* Configure your machine with the necessary tools 
* Modify the website
* Submit the changes as a pull request

#### Configure your machine

Assumes you have Ruby, bundler, and Git installed.

```  
git clone git@github.com:chalcid/outreach.git
cd outreach
bundle install
```

#### Modify the website

* Become familiar with the [organization of this repository](ORGANIZATION.md)

#### Running the website locally

See instructions [Jekyll](https://jekyllrb.com/). 

```
bundle exec jekyll serve
```

In your browser goto http://127.0.0.1:4000/. 

When the Jekyll server is running then editing any file automatically triggers a rebuild of the site.

#### Submit the changes

Commit and push your changes using Git. 

There are many tutorials around for how to do this, e.g. [1](https://try.github.io/levels/1/challenges/1), [2](https://help.github.com/articles/git-and-github-learning-resources/).

# Learn more

You're almost certainly somewhere where a wonderful [SoftwareCarpentry](https://software-carpentry.org/) course is available, it will be more than enough for your needs here. 
