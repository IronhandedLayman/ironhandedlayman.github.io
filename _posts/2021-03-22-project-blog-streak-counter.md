---
layout: post
title: Project blog-streak-counter kickoff
date: 2021-03-22 10:21 -0400
categories: project kickoff
tags: blog-streak-counter
---
 

I was very vague about my project last night. This I feel is okay; vagueness in definition will work when the team of people working on it lives inside of a single brain. (I have a post I willstart to prepare about the topology of processing that will look at this very topic.) But now after sleeping on it I will document some of the things I want for this project:

* I want three counters, two of which you see on the main page:
  * Duration since the last post
  * Maximum number of days of consecutive posting
  * Current streak of consecutive posting

Also I know that this first project is just set up so that I can get my project structure in place and get used to PPBL and blogging. This shouldn't be that hard. I just want to have a little bit of code that calcuates the streaks when I build my posts with Jekyll (naturally will have to be in Ruby, a language that I have little practical experience in outside of Vagrant confiugations) and have the time since last post be calculated in Javascript (because that will change more dynamically). Since my JS is a bit stronger, I started with the JS portion first.

So, let me tell you about the first rabbit hole I went down. :)

I looked for a good date library to use that is lightweight enough for my page and was going to use Moment since I used it in the past. Then I learned that Moment was deprecated due to its size, and that I should use a slimmer library instead. One suggestion is [Luxon](https://moment.github.io/luxon/index.html) written by one of Moment's maintainers. I will go with that for now. It is hard sometimes to keep track of the changes in another domain, since the alternatives need to call attention to themselves when the original solution is sought after. In some ways it reminds me of the [COMEFROM pragma in INTERCAL](https://en.wikipedia.org/wiki/COMEFROM) and the problems it introduces. This train of thought is branching philosophical so I will put that into another side post. Anyway Luxon seems to be pretty easy to use, so I can add that immediately. I will add that with this post's commit.

Well, as this part has been written later, I ran out of time today. Will add it tomorrow. I made some progress today that I feel okay about pushing up.

The other part will have to embed itself in Jekyll somehow, or use Ruby in some way. At any rate, I will need to do some research.
