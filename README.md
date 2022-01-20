# Catalog Service

[![Overall](https://img.shields.io/endpoint?style=flat&url=https%3A%2F%2Fopslevel-jason.ngrok.io%2Fapi%2Fservice_level%2FduqgjOnsAjJk3cR1HapTmsMXsVRM470WfotJ6QMY5JU)](https://opslevel-jason.ngrok.io/services/catalog_service/maturity-report)

Usage
Workflow to publish a new post
Under posts/ , create a new Markdown file similar to the one below:

title: Some Title
author: Some Author
date: 01-01-1971
---
The first paragraph (which will be used as excerpt.)

And some other contents. With an image below:

![dr.watson](assets/img/dr_watson.jpg)
Optional: Run python main.py local to see if the result is what you want.

Optional: Name the Markdown file ignore-sample.md to be ignored by the site generator.

Run python main.py github .

There is no Step 3.

Workflow to create a new static page
