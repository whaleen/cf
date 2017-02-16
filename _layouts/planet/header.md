---
title: "{{ post_title }}" # => "I Made a Pretty Gem - Planet.rb"
created_at: {{ post_date }}
layout: post
kind: article
author: "{{ author }}"

categories: {{ blog_categories }}
tags: {{ blog_tags }}
source_post_url: {{ post_url }}    # => "http://poteland.com/blog/i-made-a-pretty-gem-planet-dot-rb/"
source_twitter_url: {{ twitter_url }}
source_twitter: {{ twitter }}
source_blog_name: {{ blog_name }}
source_blog_slug: {{ blog_slug }}              # => "this-is-where-i-tell-you-stuff"
source_blog_url: {{ blog_url }}               # => "http://poteland.com/articles"
source_image_url: {{ image_url }}              # => "http://poteland.com/images/site-logo.png"

---


<!--
   {{ post_content }}           # => "I’ve been hurting to write this ever since we had the idea of creating a Planet for Cubox..." (Continued)
   {{ blog_slug }}              # => "this-is-where-i-tell-you-stuff"
   {{ blog_url }}               # => "http://poteland.com/articles"
   {{ image_url }}              # => "http://poteland.com/images/site-logo.png"
