---
layout: essay
type: essay
title: "Asking smart questions"
# All dates must be YYYY-MM-DD format!
date: 2023-09-05
published: true
labels:
  - Software Engineering
  - Learning
---

<img width="100%" class="rounded py-4" src="../img/asking-smart-questions/stackoverflow.png">

Asking questions online is intimidating. In Eric Raymond’s [*How To Ask Questions The Smart Way*](http://www.catb.org/esr/faqs/smart-questions.html), he mentions some important things you should do before you ask for help on websites like StackOverflow. His advice really boils down to *showing* that you’ve tried everything before asking. If you’ve already tried searching Google, or trying to read the manual, or asked your friends, and you still haven’t found an answer, then you should *prepare* to ask a question online. Make sure you outline specifically what you’re trying to do and document everything that you’ve tried.

[I saw a thread on Reddit](https://www.reddit.com/r/learnpython/comments/jyz6xd/does_anyone_else_dread_asking_questions_on/), discussing how asking questions on StackOverflow seems to be dreadful. The original poster feels intimidated when he asks questions on StackOverflow, since he feels like he gets “trolled and shut down by people who are really advanced developers.” A reply from a user was, roughly, that the nature of StackOverflow was to be designed that way for good reason. 

> “In my experience people are rather responsive towards questions that show effort, and often by going through that effort I find that I never needed to post a question in the first place, as I found the solution myself.”

So, again, the most important thing is showing that you’ve actually tried to put in effort into solving your problem. And most of the time, you’ll be able to find the answer you’re looking for.

Knowing this, let’s look at an example of a “bad” question.

## Bad Question
This post, titled [“Doesn't show me the correct output”](https://stackoverflow.com/questions/45595797/doesnt-show-me-the-correct-output), is a perfect example of a bad question. It’s not bad in the sense that the post is lacking information – the user provided the source code, a screenshot of the program running, and wrote the output that he expected.

What *is* bad, however, is the fact that the user clearly didn’t do any research before posting their question. It’s evident in the timestamps: the question was posted on August 9th, at 16:12. Only 18 minutes later, at 16:30 on the same day, the user responded to their question stating that they “some how found the answer”. No extra explanation provided, and didn’t mark the question as answered. On August 17th, someone made a reply to the question, but it was effectively a waste of time since they had answered their own question in the same hour.

## Good Question
Let’s see what a good question looks like. This post is titled [“getKey in FoundationDB returns unexpected result”](https://stackoverflow.com/questions/53284066/getkey-in-foundationdb-returns-unexpected-result). What is good about this post is that the author clearly states what they’re trying to do in the first sentence of their question, and goes through a couple example scenarios (with code) to help explain their dilemma. Moreover, they commented their code and explained where the issues are appearing, and what the errors are. This clearly shows that they had done their own testing with different cases. Finally, at the end, they ask what they should do, now that the reader has context of what their issue is. In a day, they were able to get a response that broke down what the issues were.

## My Experiences
I’m not a complete stranger to asking questions online. I’ve even asked one or two questions on StackOverflow before. It was definitely scary to post my question at first as I spent literal hours trying to contemplate how to clearly word my question and made sure I showed that I really did try to solve the problem by myself before asking.

Yet, asking smart questions is important, but it’s not the only solution.

The thing I realized is that, you sometimes don’t need to post to find the answer. As I’m writing out my question and tracing back my steps, trying to collect the things that I’ve tried, I can end up just “finding” the issue right then and there. If you don’t “see” it yet, I found it also helpful to take a step back away from the computer for a couple minutes. Let yourself tackle the problem with a clear mind.
