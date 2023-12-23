---
layout: page
title: Class Reviews
permalink: /reviews
---

I have fun writing reviews for classes, and I write them as if I was presenting a lecture on the material because it really helps me study. I can't
promise any of these to be 100% accurate, so **always** trust your textbook / professor more, but I do try my best, and since they're what I
personally use for exam prep, I have high motivation to make them as correct as possible. If you find any errors, I'm always happy to fix them, just
shoot me an email at <a class="u-email" href="mailto:{{site.email}}">{{ site.email }}</a>

{% assign schoolPosts = site.posts | where: "category", "reviews" %}

{% include postList.html posts=schoolPosts searchTag='ecen248' title='ECEN 248' %}

In addition to that, I also have <a href="{{site.url}}/assets/ecen248/LatchesToFlipFlops.pdf" download>this PDF</a>, which is my handwritten notes talking about basic synchronous elements, from Latches to Flip-Flops

{% include postList.html posts=schoolPosts searchTag='ecen214' title='ECEN 214' %}

In addition, I also have <a href="{{site.url}}/assets/ecen214/Unit1.pdf" download>this PDF</a>, which is my handwritten notes covering all of unit 1,
from basic quantities up to thevenin circuits. This has an *inaccuracy*: When discussing kirchhoff's laws, I said that both have
to do with the law of Conservation of Energy. That is incorrect. Kirchoff's Voltage Law is Conservation of Energy, but Kirchoff's Current law is
Conservation of Charge

{% include postList.html posts=schoolPosts searchTag='math311' title='MATH 311' %}

My one review only covers the multivariable portion of the class. If you are trying to study the linear algebra portion, I **highly** recommend
<a href="https://www.3blue1brown.com/topics/linear-algebra"> this </a> (free) course by 3 blue 1 brown. Like my review, it is completely focused on
building the *intuition* behind the math, rather than throwing formulas and theorems in your face. It's what I used, and I found success in the course
with it.
