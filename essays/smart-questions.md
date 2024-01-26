---
layout: essay
type: essay
title: "No Dumb Questions, Only... Not Smart Questions?"
# All dates must be YYYY-MM-DD format!
date: 2024-01-25
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/dumb-questions.png">

## There are no dumb questions, only… not smart questions?

At times in the article, it seems like the author had been very personally offended by the stupid questions he sees get posted to forums, but his rants are relatable and do a good job conveying why those questions were not smart. If every question were to follow his guidelines, it would certainly lead to better dialog. If somebody has done no searching or trial-and-error of their own and asks an ambiguous question, why would someone else want to spend time on their problem if it looks like they haven’t either. 

Those answering would have a more favorable gauge of the effort put in if they could see that the person asking had actually searched the documentation or tried different things themselves. Including that in the original post would help eliminate questions that they have about the original question, show what hasn’t worked, or maybe reveal that it’s just a tiny, easy fix. And if the asker is specific about what it is they’re trying to accomplish, it will further help those answering focus their help in that direction.

## A dumb question is forgotten

An example of a question that is not smart is this post, simply titled "[Logging function calls to a library](https://stackoverflow.com/questions/77881461/logging-function-calls-to-a-library)". The summary might as well be the entire post, but to try and summarize further, the OP is tracing a randomly occurring bug in his C++ program and is trying to figure out if his external library calls are the source. He asks if there is a way to log functions to the library without having to alter source code. His program is complex and multi-threaded, and all function calls to the library have specific prefixes. 

About the only two guidelines he didn’t break with his question was using clear grammar and spelling, and not marking the question as urgent. Otherwise, there is no indication that he searched documentation or for previously asked questions. There was nothing specific in his very open-ended post, not even which library or what the “bug” is. He doesn’t list what he’s tried or include any snippets of code. Amazingly, someone took the time to reply to him with several different things he can try. The most helpful though, was advising him it’d be much easier to help if he described the problem in the post.

## A smart question helps others

In contrast, I found this post to be an example of a smart question, very thoroughly titled "[How to fix "FATAL ERROR: Ineffective mark-compacts near heap limit Allocation failed - JavaScript heap out of memory" error](https://stackoverflow.com/questions/55613789/how-to-fix-fatal-error-ineffective-mark-compacts-near-heap-limit-allocation-fa)". The OP is trying to deploy a React.js application to Heroku but while compiling assets, the build fails and produces the error. He includes the large snippet of output that displays exactly what is being compiled, more details on the error, and the notification that the precompiling and push failed. He then includes snippets of the various methods he tried, along with links to prior search results, and the code in his package.json file.

While he didn’t hit all of the guidelines and the question could have been smarter (there were actually no questions, just a series of statements that implied a question), he provided enough detail and proof that he did his homework. In turn, his post was highly upvoted and he received many replies with suggestions of what he can do to fix it. Unfortunately, he didn’t receive his first reply until two months after the post, but a few of the replies have gone on to be solutions for others having the same issue, even four years later. Him posting his question smartly has helped many other developers in their search for a solution to their own similar problems.
