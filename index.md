---
person: Sneha
hobby: Reading
country: India
layout: templates
---

# symmetrical-meme
## Demo Repo for Docs-as-Code

# Introduction
Hi, I am {{page.person}}, my hobby is {{page.hobby}} and I am from {{page.country}}.


# What is **Markdown** and What is the _usage_ of it?
1. Its easy to use and fast to learn.
1. It converts to HTML easily.
1. It is convenient for users.


# What the are the benifits of using Github in writing documents? 
- Track changes in your code.
- It is an open source project, which means, everyone can contribute.
- It is integrated with Static Site Generator like [Jekyll](https://jekyllrb.com/).


# Data

{% for item in site.data.Sneha %}
- {{item.name}}, {{item.year}}, {{item.place}}
{% endfor %}
