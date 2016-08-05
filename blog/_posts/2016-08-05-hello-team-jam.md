---
title: Hello World from Team JaM!
layout: post
created_at: Mon Aug 05 2016
permalink: blog/2016-08-05-hello-team-jam
current: blog
author: Jeena Lee and Malisa Smith
categories:
- student-posts
---

<!-- jeena -->
### Who are we?
![team picture]()

<!-- jeena -->
### Meet our team!

**Jeena**:
![jeena]()


<!-- malisa -->
**Malisa**:
![malisa]()

<!-- malisa -->
### What are Rust and Servo?

[Rust](https://doc.rust-lang.org/book/README.html) is a systems-level programming language that was created in 2010 by an employee at Mozilla. It is a compiled language (creating usable code is slow, but runtime is fast), it is memory safe (pointers will only point to things that exist), and it is designed for concurrency and parallelism on multiple cores. You might consider using it for projects where you would otherwise write C++ code.
![servo-doge]()
[Servo](https://servo.org/) is also Mozilla's experimental baby. It is a parallel browser engine, and it is written in Rust! We are working on Servo this summer.

...what is a browser engine anyway? To generalize, a browser engine takes a URL and displays the document that corresponds to it. Every web browser has one. For example, Firefox's current browser engine is called Gecko and is written in C++. Mozilla's long-term plan is to replace bits of Gecko with bits of Servo. You can read more about browser engines [here](https://en.wikipedia.org/wiki/Web_browser_engine#Technical_operation).

<!-- malisa -->
### Our Project
![fetch](/img/blog/2016/team-jam-make-fetch-happen.jpg)
Within the vast codebase that is Servo, our task is to implement the Fetch API. The Fetch API sends an HTTP Request, [similar to XMLHttpRequest](https://developers.google.com/web/updates/2015/03/introduction-to-fetch). We are writing the Fetch API in Rust and connecting it to the JavaScript task.

Sending an HTTP Request via the Fetch API involves a request and a response. Our task is follow the class templates for Request, Response, Headers, and Fetch, which are specified by the [WHATWG standards for the Fetch API](https://fetch.spec.whatwg.org/). We're lucky to have very specific instructions and goals for our project. ;)

### What have we achieved so far?

So far we have implemented the Headers API and the Request API. We started out pair programming (which really revealed some of the differences in the way we think and approach programming), but then moved onto independent tasks. One cool thing is that because our code is so dependent on the rest of Servo and the WHATWG specifications, over the past month we have had to modify non-Fetch-specific Servo code to add additional functionality that our code depends on, and we've also filed issues with WHATWG where the Fetch spec requires clarification. This has kind of added to our experience to make us realize "hey, what we're doing actually affects the rest of the world, and we're in it for real!"

Probably even more exciting is the influence that this project has had on **us**.
- The Rust and Servo communities are both really awesome, and since starting to work with them, our standards for human interaction have gotten higher. ;P
- Coming into this project, we had no experience with low-level languages. We were both used to writing lots of one-off scripts in Python. Working with Rust has really forced us to think about what's going on in [the stack and the heap](https://doc.rust-lang.org/book/the-stack-and-the-heap.html), and what happens in memory when you create or copy an object. It is fRUSTrating but rewarding.
    - We're still struggling with concepts like ownership, lifetimes, and the interplay between Rust and JavaScript. #endofsummergoals!
- On a related note, working on such a big project with such an unfamiliar codebase and lots of collaborators is a very valuable experience. Good documentation and collaboration etiquette is appreciated by everybody.
- Plus this is the first time we've even learned what a web browser engine is!

<!-- together -->
### What tips do we want to share?

<!-- together -->
### What will we do next for the project?
**Front-end**
- Voting

**Back-end**
- Login

Visit our [blog](https://rgsoc-jam.github.io/) for the daily updates and in-depth discussions (coming soon)!
