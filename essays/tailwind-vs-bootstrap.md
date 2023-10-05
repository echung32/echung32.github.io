---
layout: essay
type: essay
title: "Tailwind vs Bootstrap"
# All dates must be YYYY-MM-DD format!
date: 2023-10-04
published: true
labels:
  - Software Engineering
  - Learning
  - TailwindCSS
  - Bootstrap
---

<img width="100%" class="rounded py-4" src="../img/tailwind-vs-bootstrap/banner.jpg">

User Interface (UI) frameworks are extremely useful tools to quickly design web applications. Many disagree with the format of writing all your style in HTML instead of using CSS files, but from my point of view, this makes the format of the website more easy to interpret at a glance. I don’t have to switch between two files and look at what classes the HTML file is using, then check the CSS file for what that class actually does. This, coincidentally, is the reason why I am finding myself to dislike using Bootstrap as a UI framework. I have used Bootstrap in the past, but have since switched to Tailwind as my framework of choice after I started playing around with development in React and developed a [URL Shortener for HACC 2022](https://echung32.github.io/projects/url-shortener.html).

## Problem with Bootstrap

My main problem with Bootstrap is that there is a lot of “information hiding” at play. Take, for example, a `.container` class in Bootstrap. This should simply do one thing: set the `max-width` of my `div` so that my content fits in various screen sizes. Instead, it sets the `max-width`, but also automatically adds padding and margins to my container, which I may not want. In this case, my only choice is to use write my own, or overwrite `.container`, and in that case why am I even using a UI framework? This functionality is also not immediately obvious on the [Bootstrap documentation](https://getbootstrap.com/docs/5.2/layout/containers/). On the other hand, [Tailwind’s documentation](https://tailwindcss.com/docs/container) clearly shows what the setting a div to a `.container` actually does. Sure, it’s a lot more verbose and requires more writing since not everything is done for you, but you get to have finer control over how much margin or padding to add, or at what breakpoint should margin and padding be added. 

## Learning Curve

I think that it doesn’t take too long to get used to a new framework and switching wasn’t too bad, since a majority of the classes that you primarily need to use are flexboxes, paddings and margins, and a handful of others. And, in cases where you want an accordion or some specialized thing, then you can refer to the extensive documentation that most popular libraries include, and/or existing articles from other people who talk through how to get it done. All in all, as a software developer, using CSS frameworks is definitely beneficial to me and helps speed up the development process.
