+++
categories = ["tech"]
date = "2017-05-20T21:10:18-05:00"
description = ""
tags = [
  "devops",
  "infrastructure"
]
title = "Declarative is the new black"
draft = true

+++
[learning-javascript]: https://hackernoon.com/how-it-feels-to-learn-javascript-in-2016-d3a717dd577f "How it feels to learn JavaScript in 2016"

I'm consistently amazed at the number of _devops_ tools coming out in the
infrastructure space. Almost every week, I find something new and shiny vying
for my attention as a platform engineer. It's not quite the level of thrash
that the Javascript community simultaneously
[instigates and endures][learning-javascript], but still certainly enough to
give you the feeling there's got to be a lot of noise and hype here as well.

I want to pass along a bit of wisdom I've picked up in the last couple years
about tools that provision infrastructure.

<!-- more -->

### _Reach for declarative tools and systems first_

Why is the declarative paradigm  so important when working with
infrastructure? Simple. Thinking declaratively is a higher-level way to reason
about the resources we manage. Working declaratively means we can describe the
_desired state_ of a resource, and let the tool decide what imperative steps
must be taken to bring the resource into the state you've described.


Here's the deal:

#### Imperative means:

* Do something
* Do another thing
* Now do this other thing

The imperative model provides ultimate power and
current state of whatever resource it's interacting with.
Not every tool does.


