---
layout: post
title: "Building My Blog: The Journey from Zero to Jekyll"
date: 2024-09-16
categories: [blog, Jekyll, GitHub, web development]
---

# Building My Blog: The Journey from Zero to Jekyll

### Date: 2024-09-16  
### Categories: [blog, Jekyll, GitHub, web development]

---

## Introduction

Welcome to my first blog post! After many side projects, I finally decided to build a blog to document and share my work on electronics, woodworking, hacking, art, and more. I chose to use **Jekyll**—a static site generator—and host it on **GitHub Pages** for easy maintenance and full control over customization. This post will walk you through my journey of setting up the blog, from the initial idea to the final implementation.

## The Motivation

I wanted a space to consolidate all my projects and ideas in one place, a digital workshop where I can share what I build, create, and learn. I also wanted the flexibility to categorize my posts—whether they relate to electronics, woodworking, or hacking—and give visitors a simple way to explore those categories.

I didn’t want to rely on a complex Content Management System (CMS) like WordPress. Instead, I wanted a lightweight, static site that I could fully control. This led me to **Jekyll**, a powerful tool that integrates perfectly with **GitHub Pages** for hosting.

## Setting Up Jekyll

I started by installing **Jekyll** on my local machine. Jekyll makes it easy to generate a static site using simple **Markdown** files for content and **HTML/CSS** for design. With just a few commands, I had a basic blog structure ready to go:

```bash
gem install jekyll bundler
jekyll new my_blog
cd my_blog
bundle exec jekyll serve
