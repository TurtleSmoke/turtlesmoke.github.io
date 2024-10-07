---
title: LeetCode
author: TurtleSmoke
avatar: "/me/pp.jpg"
cover: img.jpg
images:
  - img.jpg
categories:
  - projects
tags:
  - problems
  - programming
---

LeetCode is famous for its coding problems. I really like solving problems, so I had to try it out, and somehow I've
been doing the daily challenges for a while now.

<!--more-->

<div class="tldr">
  <strong>Too Long, Didn't Read!</strong>
  <p>
    I love problem-solving, and LeetCode is a great playground to keep my skills sharp. Because like any good programmer,
    I'd rather waste 10 hours automating a 5-minute task, I created a tool to generate the problems, the testsuite, and
    push to LeetCode. It's been working for some months now, and I can't see myself doing the problems without it.
    Now, I simply open my IDE, run "generate", solve the problem, and "publish" it back. Curious about my solutions or
    the tool? Check out the source code on <a href="https://github.com/TurtleSmoke/LeetCode">GitHub</a>!
  </p>
</div>

---

> [LeetCode](https://leetcode.com/) is a website that provides a series of coding problems.

My LeetCode journey began over four years ago, on April 2, 2020, during my first year of engineering school.
I was just starting to learn C# at the time, and I wanted to try out some problems to see if I could solve them.

My first submission? A glorious "Compile Error":

![First submission](compile_error.png)

At least I was consistent: my instinct to code at 2 a.m. was already strong back then—a true mark of a programmer,
right?

Of course, my second submission was much better - no more "Compile Error", but a "Runtime Error"... Classic
out-of-bounds... But hey, third time's a charm, and I finally got my first... "Wrong Answer"!

Persistence paid off, as always. After yet *another* "Runtime Error" (because why bother checking your code when the
machine can do it for you?), I finally got the coveted "Accepted"!

While still in the mood, I did a second problem, this time in C. I didn't learn about pointers back then, so
at 3am and after a few rounds of "Compile Error" I just gave up, went to bed, and as they say, sleep on it.
The next day, I solved it in a few minutes.

I took a long break from LeetCode, but in December 2023, during Advent of Code, I rediscovered my love for solving
programming puzzles. And so, I decide to give LeetCode another try, and I've been tackling the daily challenges ever
since.

After having a blast automating problem generation for Advent of Code, I figured, why not do the same for LeetCode? So,
I built a script that generates the problem template, sets up a test suite, and pushes my solution back to LeetCode.

Building this tool wasn’t as simple as I expected, though. LeetCode had made their API private, so I had to
reverse-engineer their GraphQL queries. This involved a lot of console inspecting and clicking everywhere to figure out
what was going on. But eventually, I built something solid that’s been working for months.

Now, solving LeetCode problems is as simple as opening my IDE, running my "generate" command, coding up the solution,
and hitting "publish." I can’t imagine going back to the manual way of doing it, even if it’s just a few clicks.

Curious about the tool or want to see my LeetCode solutions? You can find everything on my
[GitHub](https://github.com/TurtleSmoke/LeetCode).
