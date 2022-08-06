---
title: Instructions for updating this website
layout: page
---

---
## Getting started

This website is organized as a bunch of simple text files in “markdown” format — a lightweight standard for formatting text.
You can easily edit any of the pages online, and the website will be updated usually within a minute.
All changes are tracked automatically, so you can't mess up — it is always possible to undo changes.


### 1. Get a github account

If you need to edit this website, the first thing to do is to [get an account on github](https://github.com/signup).
This is the platform that hosts and serves the web pages.

### 2. Ask to be added as a collaborator

Once you have an account, ask [Oscar](https://github.com/onierstrasz) to add you as a collaborator to the Canada Club website project.
This will let you edit and change pages.

---
## Editing pages

To edit a page, just click on the “edit” icon, modify the text, and commit your changes.

### 1. Edit the file

At the bottom of each page atthe far right there is a “pencil” icon that will allow you edit the page.

![edit link](images/instructions-edit-link.jpg)

Just click on the icon to edit the page directly in the web browser.

![edit page](images/instructions-edit-page.jpg)

### 2. Commit your changes

When you're done, go to the bottom of the page, write a short description of the change you made, and click on the “Commit changes” button.

![commit changes](images/instructions-commit-changes.jpg)

That's it!
Usually within 30 seconds you can see your change on the actual website.

---
## About markdown

Markdown is pretty simple — it's intended to be.
To edit the pages, you probably only need to know a couple of things.
The header defines the title of the page.
You can change this if you like.
You shouldn't change the layout, however.

```
  ---
  title: Canada Club Berne
  layout: home
  ---
```

Headings start with a hash.
Add more hashes to increase the sub-heading level.

```
  # About us
```

If you want to make a link to another page, use the format `[DESCRIPTION](URL)`.

For example:

```
  [our FAQ](faq)
```

will generate an internal link to [our FAQ](faq), while


```
  [the Canada Club github profile](https://github.com/canadaclub)
```

generates an external link to [the Canada Club github profile](https://github.com/canadaclub).

That's probably enough to get started.
If you want to learn more about markdown and how to use it, have a look at [this cheatsheet](https://itopaloglu83.github.io/Jekyll-Markdown-Cheat-Sheet/).
