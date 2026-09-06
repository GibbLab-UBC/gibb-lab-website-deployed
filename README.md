[![Netlify Status](https://api.netlify.com/api/v1/badges/dcf3d5d0-a4a4-486f-bd9a-64b612392aad/deploy-status)](https://app.netlify.com/sites/brave-bell-c85a34/deploys)

# Research lab website template

This website is built with [Jekyll](https://jekyllrb.com/).
It is derived from the great template provided by the
[Allan Lab](https://www.allanlab.org/aboutwebsite.html), at Leiden University.

## Setup

``` bash
brew install ruby
gem install bundler jekyll
```

Clone this repository, then install the dependencies:

``` bash
bundle install
```

## Run

Run the local webserver with:

``` bash
bundle exec jekyll serve
```

## Contribute

### Add a new member

New members are stored as markdown files under
[_pages/team/_posts](_pages/team/_posts).

Each new member `.md` file must look like this:

``` yaml
---
layout: member
category: alumni/student/role_name
title: Name
image: Name_ProfilePicture.png
role: xx
joined: month YYYY - month YYYY
join_date: YYYY-MM-DD
leave_date: YYYY-MM-DD
description: to_be_fill
---
```

