---
layout: home
title: Home
---

# Hello and welcome to haskins.io.

## What is this site
Essentially it's a dumping ground for all my thoughts and ideas. It is powered by Jekyll using an AWS S3 bucket to host
the static site. Why? because I'm too cheap to fork out on dedicated hosting.

## Who am I?
I'm a software engineer that is currently working as an AWS / Azure Systems Engineer.

## What will I find here?
Currently on this site you will find:-
* A Blog, though I'm not very talkative so don't expect a lot from that
* Cloudtrail Viewer. This is an open source project I started almost 5 years ago and is the most popular repository I
have on gitHub
* Ends - This is Apple Watch based application that I'm currently working on.

## Latest Posts
<div>
    {% for post in site.posts %}
        {% if forloop.index < 6 %}
           <h5><a href="{{ post.url }}">{{ post.title }}</a></h5>
        {% endif %}
    {% endfor %}
</div>