---
layout: post
title:  "Bluesky Business Model - Risk Factors"
date:   2025-05-20 01:00:00 -0400
categories: updates
---

This is a working document + open letter meant primarily to discuss with *Why* from the Bluesky team, but I'm publishing it in the open to make sure anyone who is participating in the broader conversations can see what exactly I am and am not trying to say.

If you're in a hurry or don't want or need background info, scroll down to **"Specific Points of Concern"** and you should be able to get right to the heart of my argument.

I may edit it as I'm having conversations and will mark sections that have been revised + extended when I do.

## What I'm not trying to say...

To calibrate, let's get some of the strawmen that people seem to keep throwing up out of the way. (Why and I have already discussed all these over DM so this is more for others who might be reading)

- I'm not trying to suggest Bluesky run without revenue. Quite the opposite in fact... I think the team is much later to the game than they ought to be on that, and critically undercapitalized. It's actually existential that they find a business model, and fast, not just in theory but rolled out and bringing money in the door.

- I'm not trying to suggest that ad revenue is *inherently* wrong, for many types of businesses. I'm not even trying to suggest that it's wrong in many cases for third party builders + authors on Bluesky. Many valid cases for running ads and sponsorships in various forms, and the UX doesn't need to be bad or unwelcome to the audience.

- I'm not suggesting that I think that the Bluesky team operates from bad will or has hidden intentions -- I accept at face value and my experience tells me from what I've seen that this team very much wants to have atproto outlast them.

- I'm not trying to suggest that I have any meaningful leverage in announcing that I'm leaving Bluesky, nor am I trying to suggest that such a move would be permanent.

- I'm not trying to advocate for *full decentralization* in the way that Mastodon/ActivityPub adherants have done, nor am I trying to suggest that I believe Mastodon has a sustainable business model that scales to world scale.

- I'm not trying to say that ad revenue is inherently a bad idea for Bluesky as a company -- it is only that they currently occupy the role as the sole network operator for a ubiquitous global communication network. If there was enough viable microblogging going on atop atproto that you could pull Bluesky out of the ecosystem and still have the remaining providers retain comparable levels of network effects, then it doesn't matter what Bluesky's position on ad revenue is.

## What I am trying to call attention to and urge caution over...

**The short story is this: Ubiquitous networks (i.e. places that are meant to serve "everyone" and allow connections between everyone) are fundamentally different forms of businesses than almost every other type of business that exists in the world.**

The ways you can avoid unintended emergent outcomes in most other forms of businesses do not apply to ubiquitous networks. Nearly every other form of business can at least define who their intended customer is, even if the goal is to scale as much as possible.

By contrast, ubiquitous networks are meant to provide a universal *capability* of some sort, agnostic to any particular purpose. Because the actors themselves don't have anything in common (at scale) beyond a shared desire to make use of that capability, the applications, impact on the world, and the mental models people have of ubiquitous networks are primarily *emergent* rather than designed for in a predictable way.

As a result of this, they have *unique threat patterns* that can lead to network collapse or capture which you won't find in most other forms of business. In particular, they are extremely sensitive to even small governance and funding model changes, and are prone to extreme oscillations and chaotic behavior that tend to accelerate the larger and more valuable the network gets.

---

> For some background theory, see [Ubiquitous Connectivity with Nudging](https://melconway.com/Home/pdf/UbiquitousConnectivity.pdf) a paper published by Mel Conway last year. The core principle from it is "THINK NETWORKS FIRST, ACTORS SECOND", and is about how humans tend to misunderstand network effects and how a lot of our biggest problems arise from that. Mel coined "Conway's Law" half a century ago,and I regard him as one of the deepest thinkers on human behavior at scale that has ever lived.
>
> But that's a very, very abstract article, so I don't know that folks will have time to tease out the key details. I'll focus on practical concerns through the rest of this note with that in mind.

---

## Specific points of concern

I'd ask you to conditionally accept the idea that at least at this very moment *Bluesky is a ubiquitous network* which intends to serve all people and scale connections infinitely, and so therefore has this strange shape that we don't see in most other kinds of businesses.

And assuming that's a frame we can work within, I'd assert that even if the *purpose* of Bluesky PBC is to lead to the development of an open protocol that will outlive both the Bluesky company and the app... that for practical purposes Bluesky is currently a *platform business* and will be constrained by that until the protocol truly can stand on its own legs.

Then the design challenge is to **allow Bluesky to survive long enough in a way that incentives line up to facilitate the bootstrapping of the protocol to a point where it no longer requires Bluesky to be a "good actor" to sustain itself**.

With that challenge in mind, here's the list of concerns I see with any business model dependent on ad revenue. If I've framed it wrong, let me know and I'll reanalyze and retract or revise anything I got wrong.

- Any monetization lever you provide for any actor in the system becomes available to all, unless you want to be in the business of becoming a media company that editorializes things. In other words, while you can restrict certain behaviors globally, you can't locally tune rules to be very opinionated about restricting or boosting particular types of commercial activities... or you'd run into major conflicts of interest that would interfere with being an equitable steward of a *generic* protocol.

- Therefore, if you want to maintain a level of operational independence which allows you to faithfully retain the stewardship role over atproto, you need to design monetization levers that are *ergodic* in nature. In other words, ones in which the average outcome for the population as a whole mirror the average odds of success for an individual. Otherwise, even without ill intent, you will kick off a "natural selection" like process in which whoever is best suited to benefit from whatever systems you put in place get richer at the cost of others getting poorer, which would land you in the same place as the prior example of becoming a media company. Which would be an excellent platform play potentially, but bad for building a protocol.

- Consider this from the lens of the specific example of "Feed operators accept sponsorships for paid placement using payments facilitated by Bluesky, the payments are peer to peer but Bluesky gets a cut for providing an easy payment mechanism" -- this sounds like a content + actor agnostic model on the surface and there are no immediate surface level ethical concerns about it. But consider this when you dig in...

  - To make this work at scale you'd need to make feeds far more visible and far more sticky for the "everyday" Bluesky visitor. It's hard to imagine a way to do that which doesn't put a thumb on the scale one way or the other, and the natural incentive would be to elevate that which brings in more revenue or has revenue generating potential. In other words, elevating placement based on engagement + conversion rate for sponsored posts. If you remain neutral you will struggle to bring in the revenue required, if you allow money to determine placement you become an adtech business.

  - If you do not cap the total amount that can be earned from a feed operator / spent by a sponsor/advertiser in a set period of time, you will end up getting a distribution of outcomes where the median performance is nowhere near the average, i.e. something that's very much non-ergodic in nature. So the end result is that one way or another you will end up with a handful of "Whales" that control a large portion of the overall revenue pool. If this contributes to opex rather than profits for Bluesky, and you can't afford to lose those accounts, then a strong influence will exist that will constrain any design decisions Bluesky makes... including and especially things that benefit the protocol more than the platform.

  - If you do not put quality control measures in place for feed operators / sponsors, you will kick off a gold rush of people trying to monetize through ads and sponsorships, which will increase the odds that the average Bluesky visitor's experience will degrade, even if they have the ability to opt out by choosing which feeds to subscribe to. But those who aren't already very sophisticated in the use of social media tooling aren't necessarily going to act with agency in response to this, and so their response is more likely to be "you promised that Bluesky wouldn't run ads and now there are ads everywhere and that sucks" or they'd just passively accept the intrusion. This will also be ripe for engagement farming, slop, and bait and switch tactics.

  - When signal degrades in a network, and monetization forces are at work, the natural trend is consolidation. People either find the little corners that work for them, or they leave, or they subscribe to things that they don't appreciate the business model behind but endure the discomfort to get at the "content" -- don't think about this from a lens of customer experience but instead from a revenue stream perspective, where the pool actually *shrinks* or after an initial gold rush period at least slows substantially while a narrowing pool of successful operators grab a bigger and bigger piece of a shrinking (or at least slower growing) pie.

In light of all of the above, what I see is more and more design cycles and threat mitigation efforts being spent on tuning the influence that ad revenue has on the platform, and unless opex shrinks over time rather than going up, a need to keep chasing growth and making tough choices about how to balance quality control without editorializing and becoming a media company.

So the cost of maintaining the revenue stream would go up over time, rather than down, and essentially would become a flywheel running in reverse. This will in turn impede the work on other forms of revenue streams, increasing dependence, and then in turn creating a spiral where the independence of the protocol is both out of alignment with the business model of the platform and the platform itself is chasing growth at all costs simply to pay for the increased complexity that comes along with this way of making money.

Look at other platforms and see if you see signs that they've ever had a different trajectory.

## Risk Mitigation Strategies + Silver Linings

- I've said it many times but I do believe subscriptions are a good starting point. I don't think they work as a standalone revenue stream, especially not at first, and it'd be important to not gate core features behind a paywall. But for someone like me who up until this point was going "all in" on Bluesky as a way for people to discover my own works, I'd pay $50-$100/month gladly if it would meaningfully even defer the introduction of ad revenue as a stream, or at least serve as a counterweight against it enough to cover a significant portion of opex across all subscriptions.

- If you can somehow seed a generic payment mechanism into Bluesky, I'd gladly pay a cut of a "Buy Now" button for my own stuff to Bluesky and use it if others I followed were using it. Essentially weaving in something like Gumroad / Venmo would be incredibly powerful *but only if it was sufficiently heterogeneous to avoid paid placement taking the lionshare*

- If you make public commitments that are verifiable to metered growths and caps, that'd go a long way too. For example, things that get more expensive the bigger they get to discourage rapid growth hacking as a defacto model / giant buys from giant companies would go a long way. Or straight up caps that let people earn only up to a certain point that'd guarantee that no one actor can exert too much influence over the overall revenue stream, then you'd be doing something that at least would be more of a "two way door" than a "one way door" in that those values could be tuned to ensure that the overall system stays healthy enough, long enough, to get atproto to a stable point of real operation independence.

- If you set up a trust of some sort and either dumped a multi-year grant into it or committed to a rather hefty percentage share of Bluesky revenue and then appointed a managing director for an independent atproto development team... or did this split at the peer to peer level where some money goes to Bluesky directly while others go into this earmarked fund, then you'd have a counterweight in place that meant that revenue growth would always mean further investment in the protocol *by design* and this would create a balancing force.

- If you stood up enough other forms of revenue inflows that *aren't* oriented around content placement / discovery but instead around utility + convenience, and those worked well enough that any ad revenue contributed only to profit and not to opex, you'd have a lower risk profile. For example, I had heard of things like partnerships for people to be able to set up a custom domain + self verify where Bluesky would recommend a preferred DNS provider in exchange for a referal fee. This to me seems fine because it's just a value add and doesn't meaningfully get in the way of an average customer's experience or lock anyone else out.

To sum up... I want you all to succeed. But you don't need to be evil to miss out on the potential for emergent network effects to create the "rich get richer" phenomena. And if you really want a world without Ceasers, then you need to devise a system that is the digital equivalent of building farmer's markets and main streets.

Tilt the incentives in that direction for long enough, and you'll achieve the goal you set out for with atproto, and then it doesn't really matter what happens to Bluesky after that.

Hope this helps and happy to talk more.

**PS: Will revisit my intent to depart Bluesky if/when official comms clarifying the business model are put out. Not a big deal if that doesn't happen and clearly I am just a small drop of water in an ocean size bucket, but want to express a willingness to trust again if I feel I can back this org on principle, which I felt I could do very strongly until the other day.**
