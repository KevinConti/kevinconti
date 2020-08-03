---
title: CoderNotes Pre-Retrospective 1 - What went well
description: ''
date: 2020-06-04T04:00:00.000+00:00
categories: []
published: false
tags: []

---
The experience of making CoderNotes.io felt a lot like playing a sport after reading a book on it. You quickly realize that even though you know the theory, putting it in practice is a whole other beast.

That said, there are three things I feel I did correctly that I'll be sure to do again in the future. In part 2, I'll write about all the things I feel I did wrong (far more than three!), and how I'm tackling them next time.

## Things that worked... I think.

### 1. The Initial Pivot

![Image that reads "Learning from an online course is tricky"](/forestry/the-problem.jpg "My initial landing page")

I initially made CoderNotes for a different problem. At first, it was a solution for junior developers taking coding courses. It was designed to be a note-taking system that improved retention. I imagined it to have features like:

* Spaced repetition
* Public and private flashcards
* Ability to share "decks" (sets of flashcards)

When I reached out to developers to share the idea, I found that while only some junior developers related to that pain, there was a specific value prop that everyone could get behind:

!["You know you've solved the problem before, but can't remember how](/forestry/problem.png "The pivot's value prop")

When I interviewed people about this pain, I got a lot of affirmative responses. I took this as validation and ran with it, immediately lowering my head into the ground to start working.

Eventually, I created CoderNotes, to solve the pain of finding and retrieving code notes:

![User saying that they experience that pain](/forestry/pain-im-solving.png)

The fact that I made this pivot, that I was able to think somewhat critically about the idea before proceeding, is a big win. It's something a lot of founders get tripped up on, and I'm glad that I was able to avoid going down the first rabbit hole I found.

That being said, I still think I jumped to product creation way too early. But we'll talk about that in part 2 of this post.

### 2. The Tech Stack

I'm really happy with the product itself. CoderNotes.io uses a somewhat unique tech stack, but all the pieces have really come together:

Svelte - Javascript frontend framework

TailwindUI / TailwindCSS - CSS framework and library

Sapper - SRR svelte framework that works as a pass-through backend

Elixir / Phoenix - Backend API

Hasura - RBAC database

For each of these, it was my first time working with them seriously. Thankfully, I don't regret the experience of learning any of them. I had a specific criteria for each of the frameworks I chose, which I think is a more important takeaway than the actual languages I used.

If you're looking for a production-ready framework or language for your product, make sure that it has the following:

* An active community. You WILL get stuck and confused eventually, and you want a place where you can quickly get an answer. I specifically look for if the community has a discord or slack group that was friendly towards beginners, and typically responded to user's questions within 30 minutes.
* Reviews from other users in production. While it's fun to use new and cutting-edge frameworks, you may be risking having to rewrite the code in a new framework if it doesn't support your use case. I almost ran into this issue with Hasura, and I will say that I was disappointed with the developer experience of Sapper (with a few exceptions). 

Also, realize that it takes time to learn something new. If you're already familiar with a good framework (like Ruby), it's probably not worth your time to learn something new, unless you have a specific, clear need for it (such as Phoenix's OTP). Otherwise, stick with what you know.

In that vein, my next project will definitely be using Phoenix again, possibly even the new Phoenix LiveView to keep everything contained in a single language. I've loved the speed of development with Phoenix. 

### 3. Consistency

This final thing I feel I did well with getting the product to launch was the consistency of effort. Since I have a full-time job, it's tough to find time to work on a project like this. I found success in building a habit of waking up at 5AM, and working from around 5:30 - 8 AM. It's only 2.5 hours a day, but it was enough to get the app ready for launch in right around five months. 

Bootstrapping on nights and weekends (or mornings and weekends in my case) is a real struggle. It's not for the faint-hearted. You need to be aware that you'll be making a large sacrifice for an uncertain payoff. You really have to enjoy doing the work if you're going to succeed.

## Conclusion

Overall, I'm pretty happy with my first SaaS attempt. Like I said above, it was a refreshing smack in the face to take everything I've learned from the indie community and struggle to apply it to real life. As has been my experience in every company I've started, the amount I've learned is immense. I'm very excited to take what I've learned forward into the future, as well as to see how CoderNotes.io can grow over time. 

As far as what exactly I've learned, you can take my hard-earned knowledge and save yourself the pain by checking out part two of this post.