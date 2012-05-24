---
layout: post
title: "Test First?"
date: 2012-05-24 10:36
comments: true
categories: [TDD, TFD, testing, software development]
---
Why in the world would you want to write tests for your code before you even start writing your code? Why would I want to write tests at all? I can just write my code, implement it myself and test it in the browser. After all, that's how the end user will experience it, so shouldn't that be how I develop it? Plus, writing tests would be like writing twice as much code so I would decrease my productivity.
<!-- more -->
That seems like a pretty solid argument against testing in software development. Except there are some assumptions in that line of logic that don't present themselves until well into the development process. The first and most important assumption is that I will be able to write the best version of the code right away. Further I am assuming my code will be correct from the start.

As a somewhat experienced developer (I suppose I am still the new kid on the development team ☺), I know that these assumptions are rarely true. In fact, there is probably a correlation between the size of the code and how wrong I will be after my first iteration. Believe it or not, testing first helps mitigate some of that.

## But why test at all?

![Testing First](/images/test.jpg)

But first, why would we want to write tests first? Or at all? The idea behind testing is to write a test for some functionality or feature. You write it before you even write your first line of code. At this point, if you run your test it will fail. Here is the key though, a failing test is a good thing! A failing test tells you what to do next. Once you have a failing test, you write just enough code to make the test pass. Then you look at your code and see if it can be more efficient, this is called refactoring. You continue this process of writing new, failing tests and writing the code to make them pass, all the while making sure your new code does not break your existing tests. If they do, you know exactly what you did to turn a passing test into a failing test, and you again know exactly what to do next. This method of programming actually saves you time and frustration. You don't have to go over your entire code base to find a hidden bug that is throwing your code off. You have written tests in small, manageable chunks and can easily tell when and where things go wrong.

Testing does force you to write more code. There is no way around that. But, I would suggest that the test code is just as valuable as the actual feature you have coded. A side effect of your tests is that your code becomes easier to read. The tests have guided the functionality and start to guide its documentation as well. A well written test suite is one of the most valuable pieces of code you can write, especially for developers who will look at your code in the future.

So, how do you feel about writing tests for your software?

