---
title: "{{ post_title }}"
kind: article
created_at: {{ post_date }}
author: "{{ author }}"
categories: {{ blog_categories }}
tags: {{ blog_tags }}
layout: post
link: {{ post_url }}
---

<!--
   {{ post_title }}             # => "I Made a Pretty Gem - Planet.rb"
   {{ post_url }}               # => "http://poteland.com/blog/i-made-a-pretty-gem-planet-dot-rb/"
   {{ post_date }}              # => "2012-04-14 05:17:00 UTC"
   {{ post_content }}           # => "I’ve been hurting to write this ever since we had the idea of creating a Planet for Cubox..." (Continued)
   {{ blog_name }}              # => "This is where I tell you stuff"
   {{ blog_slug }}              # => "this-is-where-i-tell-you-stuff"
   {{ blog_url }}               # => "http://poteland.com/articles"
   {{ blog_categories }}        # => "programming planet"
   {{ blog_tags }}              # => "go ruby jekyll"
   {{ image_url }}              # => "http://poteland.com/images/site-logo.png"
   {{ author }}                 # => "Pablo Astigarraga"
   {{ twitter }}                # => "poteland"
   {{ twitter_url }}            # => "http://twitter.com/poteland" -->
