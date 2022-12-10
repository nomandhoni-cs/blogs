---
coverImageAlt: Sat Naing Portfolio website & Blog
coverImageWidth: "1200"
coverImageHeight: "700"
datetime: 2022-03-25T16:55:12.000+00:00
tags:
  - NextJS
  - TailwindCSS
  - HeadlessCMS
  - Blog
author: Sat Naing
type: article
coverImage: https://res.cloudinary.com/noezectz/image/upload/v1653050141/SatNaing/blog_at_cafe_ei1wf4.jpg
title: How Do I Develop My Portfolio Website & Blog
description:
  My experience about developing my first portfolio website and a blog
  using NextJS and a headless CMS.
excerpt:
  My journey about planning, designing and developing my very first portfolio
  website and my personal blog. Thoughts about my motivation for this project and
  experiences.
slug: how-do-i-develop-my-portfolio-and-blog
featured: true
category: How Do I
language: English
---

My experience about developing my first portfolio website and a blog using NextJS and a headless CMS.

## Motivation

I've been always thinking about launching my own website with my custom domain name (**satnaing.dev**) since my college student life. But that never happened until this project. I've done several projects and works about web application development but I didn't make an effort to do this.

So, "what about blog?" you may ask. Yeah, blog also has been in my project list for some time. I always wanted to make a blog project using some of the latest technologies. However, I've been busy with my works and other projects so that blog project has never been started.

In these days, I tend to develop my own projects with the focus in good quality rather than quantity. After the project is done, I usually put a proper readme file in the Github repo. But Github repo readme is only suitable for technical aspects (this is just my thought). I want to write down my experiences and challenges. Thus, I decided to make my own blog. Plus, at this point, I have decent experiences and confidence to develop this project.

## Tech Stack

For the front-end, I wanted to use [React](https://reactjs.org/ "React Official Website"). But React alone is not good enough for SEO; and I did have to consider many factors like routing, image optimization etc. So, I chose [NextJS](https://nextjs.org/ "NextJS Official Website") as my main front-end stack. And of course TypeScript for type checking. (It's said that you'll love TypeScript when you're used to it 😉)

For styling, I use [TailwindCSS](https://tailwindcss.com/ "Tailwind CSS Official Website"). This is because I love developer experience that Tailwind gives and it has a lot of flexibilities compared to other component UI libraries like MUI or React Bootstrap.

All contents of this project reside within the GitHub repository. All my blog posts (including this one) are written in Markdown file format since I'm very used to with this. But to write Markdown along with its frontmatter effortlessly, I use [Forestry](https://forestry.io/ "Forestry Official Website") headless CMS. It is a git-based CMS that can serve Markdown and other contents. Because of this, I can write my contents either using Markdown or wysiwyg editor. Besides, writing frontmatters with this is a breeze.

Images and assets are uploaded and stored in [Cloudinary](https://cloudinary.com/ "Cloudinary Official Website"). I connect Cloudinary via Forestry and manage them directly in the dashboard.

In conclusion, these are the tech stack I've used for this project.

- Front-end: NextJS (TypeScript)
- Styling: TailwindCSS
- Animations: GSAP
- CMS: Forestry Headless CMS
- Deployment: Vercel
