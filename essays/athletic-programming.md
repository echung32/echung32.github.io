---
layout: essay
type: essay
title: "Athletic Programming with Javascript"
# All dates must be YYYY-MM-DD format!
date: 2023-08-29
published: true
labels:
  - Software Engineering
  - Learning
  - Javascript
---

<img width="100%" class="rounded py-4" src="../img/athletic-programming/javascript-logo-banner.jpg">

## FreeCodeCamp

I’ve been using Javascript long before ICS 314, a course about software engineering concepts and technologies, but it still reigns as my favorite language to quickly develop simple programs. If I want to get something done quickly, I’d use Javascript. Compared to other languages like Java, there is no need to worry about types, and there is no need to write a bunch of boilerplate code to get a simple main() function to run. Javascript can be used either for functional programming (like Python), or object-oriented programming (like Java), which makes it highly flexible.

After going through and completing the freecodecamp course, I realized that I was already familiar with most of the content, including the ES6 portion, but it was nice to receive a refresher about some features and functions of Javascript. I think that it’s important to reinforce your knowledge about even the basics, since there can be things that you didn’t know about or simply forgot about.

## Javascript Downfalls

I think that, from a software engineering perspective, Javascript is certainly not a bad language. However, I’ve personally forbidden myself from ever using Javascript for larger projects. An untyped language is great to get things done quickly, but can likewise quickly grow to become a maintainer’s nightmare. I’ve interned at a company which developed their framework around Javascript, and the hassle of figuring out the expected structure of the data, or the random and inconsistent types being passed into functions, can cause immense frustration. It’s even worse when a function takes an object instead, with absolutely no documentation of what that object takes. It takes time to search through existing code and piece together what it expects. JSDocs were created as a simple way to type your code, but at that point, why not just use a typed language instead? I’ve since been using Typescript since it’s almost identical to Javascript, and has made maintaining code far simpler for not only me, but for others who work with me.

## Athletic Software Engineering

Moving on, this class also heavily incorporates athletic software engineering. I feel that athletic software engineering is quite interesting and motivates me to explore the various ways to solve a problem. While the practice WODs (Workout of the Day) are not too complicated in nature, they encourage me to quickly think of a solution to the problem. It’s fun to see how fast I can beat the time and inspires me to seek implementations that can reduce my time further.

For example, the previous workout called for us to implement a method, `isUnique`, which accepts an array as a parameter and checks whether all elements of the array are unique.

My first implementation pushed all elements into the array with an object and looked like this:

```js
function isUnique(arr) {
  const obj = {};
  for (int i = 0; i < arr.length; i++) {
    obj[arr[i]] = 0;
  }
  return arr.length === Object.keys(obj).length;
}
```

After a couple of iterations, I discovered that I could completely implement this function using a single line and, because why not, use an anonymous function.

```js
const isUnique = (arr) => new Set(arr).size === arr.length;
```

Of course, in the pursuit of seemingly shorter code, we shouldn’t forget to consider the efficiency nor readability of these implementations. Shorter is not always better, and sometimes developers may intentionally write more verbose code that is easily understood. I think that a developer would be able to identify how my first implementation works far quicker than the second, since developers generally work more with objects than Sets.

Regardless, my primary goal doing these WODs is to explore the many different ways to implement a solution. It can be challenging, and can be quite stressful at times, but has overall been a great experience. I think this method of athletic software engineering works for me, since my competitive nature seeks out different solutions in search of faster time, and it helps reinforce existing knowledge and expands my exposure to various problems.
