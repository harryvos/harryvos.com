---
title: 2024-W41 week note. New job and a tech conference
description: I started a new job, working on a product that helps tugboat crews reduce their emissions. I went to a tech conference.
date: 2024-10-13
image: /img/harry-vos-tugboat.webp
tags:
- post
- Week notes
layout: layouts/post.njk
canonical: "https://www.harryvos.com/posts/2024-w41-week-note/"
---

## New job

After getting laid off earlier this year from my first job in Denmark, I’m the [Newman](https://www.youtube.com/watch?v=1PE7Tf-0eXE) in the office. Sorry, I could not resist linking to that classic from Channel 4’s PhoneShop 😍

I’m working on a product that [helps tugboat crews reduce their emissions](https://www.rivieramm.com/news-content-hub/news-content-hub/behavioural-change-cuts-fuel-and-emissions-81316) by showing them where they could reduce their speed. It’s fascinating. Some of my highlights so far include:

- triaging a bug over the phone with a crew member on the River Thames in London
- usability testing some iterated designs with a crew member on the River Tees in Middlesborough
- a conversation in a retrospective about improving communication within our team

![Harry Vos in front of a tugboat. Smiling, with a blue sky behind the boat.](/img/harry-vos-tugboat.webp "Harry Vos and a tugboat")

I even got a tour of a tugboat, where the crew made me feel very welcome 😊

I quickly noticed how passionate my colleagues are about tugboats and towage. At first, I was interested because I would be working on a product that reduces greenhouse gas emissions. Now, I’m finding myself geeking out about tugboats. I think a lot of that comes down to the passion and pride rubbing off on me. It certainly helps me as I learn about the domain. Topics I might previously have thought would be a bit boring, but necessary, are intriguing when I learn about them from colleagues.

I think the app our team has built is brilliant and my first instinct is to want to share it very loudly on all our internal channels. But, I’m also conscious of how we, as a company, must prioritise communication about safety. Towage is risky work. Just two years ago, two crew members lost their lives at work. To respect the risks our crews can face, I’m relearning how to communicate. I don’t want to distract from more important messages. So basically the opposite of the “stop everything and look at my shiny thing” LinkedIn grifters.

We’re facing some tricky technical decisions. I think it’s a situation where we’re probably better off breaking some agreed architectural principles. But, I still feel so new that it’s hard for me to form strong opinions on certain things. So I’m listening a lot to my colleagues. If we do end up building something that on the surface looks weird, I want us to ensure we document it. Why did we build it that way? Why did we break from the wider architecture? Teams read code around 10x more than writing code. So it’s important to make it understandable for our future selves, especially the weird parts.

## Django Day Copenhagen 2024

Last week, as part of my quest to contribute more to technical discussions, I went to [Django Day Copenhagen 2024](https://2024.djangoday.dk/). I found the talks pretty accessible to me as someone who has a less technical background, which I was grateful for.

Learning about domain-driven design gave me a new perspective on the technical decisions I mentioned earlier. Where are we better off using default concepts that come with each part of our tech stack? Where are we better off defining concepts to model our business domain? And to what extent?

There were a few talks that touched on the challenges of creating and maintaining maps in web apps. It gave me an understanding of how difficult maps can be. So I left wanting to know how our team implemented our map of tugboat and ship movements all over the world.

[Rosamund Mather](https://www.rosamund.dev/about) shared her brilliant side project, [named after women](https://named-after-women.berlin/). It shows streets named after women in Berlin, along with short biographies. It started as a way for her to go for new walks during lockdowns and try new things in Python and Django. She said it was a mix of her passion and telling people about it that drove her to release her side project to the public 👏🏻 I particularly liked how she built in three metrics to track her progress, % published of all Berlin streets named after women, % published with photos and % drafted.

## Next

At work, I’ll be getting into product discovery mode, learning about our users. I’ll work with our team to form a more opinionated roadmap and backlog.

Over the summer holidays, I’ve slipped a bit on learning Rust (a programming language). I feel quite rusty 🤦🏻‍♂️ One or two colleagues might want to learn too. Perhaps we’ll club together.

[Reply on LinkedIn](https://www.linkedin.com/in/harryjvos/)

[Reply on Mastodon](https://mastodon.social/@vosageroll)