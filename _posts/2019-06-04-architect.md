---
layout:     post
title:      Being A Software Architect
date:       2019-06-04 17:43:00
summary:    I hope someone could tell me about what the 'Software Architect' should look like and how to play the role before I got into it and sort it out by myself. Maybe it is different for peoples who are playing this role with or without the title, I expect our definition of 'Software Architect' can also be different, that is fine, but, I believe there are something in common worth to be shared here. 
categories: general career architect
---

I hope someone could tell me about what the 'Software Architect' should look like and how to play the role before I got into it and sort it out by myself. Maybe it is different for peoples who are playing this role with or without the title, I expect our definition of 'Software Architect' can also be different, that is fine, but, I believe there are something in common worth to be shared here. 

This is my version of 'Being A Software Architect':

## There will be lot of decision need you to make

It can be something big or small, it is not about saying 'Yes' or 'No', most of the time, you need to think through with the understanding of different aspects of the problem, trying to understand the 'root' cause of it, **put it in the 'big picture' you have** (if not, try to get one, even just a vague one), and see how it will fit with given choices. As always, during the design discussions, I would like to ask, to the myself and team: 'Let's forget about all the constrains for a moment, think about what issues we are talking about, what priority we would like to put on them and what we would like to be in ideal?'. The goal is to set the 'direction' we want to be heading toward, it help us to understand which solution, for short-term or near-term, is aligning better with our long-term direction, **are we making improvement toward to the direction we pictured**.

## Try to put a big picture together for the org/team

**You won't have it at beginning, that is normal**. The points are how to get one, then we can iterate and evolve it along the way. There are always particular sets of problem need you to solve, start to build the list, after you have it, usually, the question need to be answered is **'why they are important which needs to be solved right now?'**. Keep in mind, there are always piles of problem there, big or small, don't be intimidated and get lost by just trying to address them one by one, you may need to **step back a little bit to see the 'big picture' first**, and, time to time, try to find the commonality, patterns and causality in between the problems (it sounds like a debugging process, and, indeed, it is a debugging process), and think about the impact of the problems. In order to make some big changes, **you need to be able to articulate the idea, pitch the solution to the teams**, including the managers and teammates. The ultimate impact would better to **be able to be reflected in the products as business result**, no matter you like or not ,that is the real value you can bring to the employer, don't forget about it (Be useful and meaningful).

## It is a debugging process

The bug is a real complex one, **a compound of the problems**, expecting the fix most likely won't be single line of change. You need to understand the problems, try to get to the 'root cause' of them, then figure out the fix/solution to address them. You may not be able to fix all of them, typically not, since, most of time, **you are doing the trade-offs**, which means, there are always having Pros and Cons, you need to understand both of them for the decision you made, sometime, it is an overwhelming process to evaluate the choices out there, and you may not be able to evaluate all of them, and **you can be wrong at some degree, that is fine**. you need to accept the fact, and refine your design as needed. It is a process, a process to find the root of the problems, step-in and step-out to understand them in different aspects, evaluate the ideas, **take the first step, try something out, get feedback and refine along the way**.

## Your schedule will suck

At certain point, **you won't be able to implement every idea you have**. That just doesn't scale, sooner, you will find you become the bottle-neck, there are so many design review and code review are waiting for you. Remember, keep the team in high velocity is part of the architecture design, in order to scale well, **you need to delegate the work to the teams**, pick most important things to focus on, and expect, unblock the team, make them moved in-parallel is crucial, so, **be prepared to jump in any given issue** which may slow down the team's velocity. There will be random issues come to your way, it can be asking for help, asking for decision, asking for design feedback etc,. So, how to get used to this and still be able to manage your own schedule become a real challenge here. You may find you talk to different kinds of peoples all day long, feel you didn't actually do anything concrete, like fixing a bug or implement a functionality. This is **a quiet tough transition** as someone first time experience it. I feel, even now, still not fully getting used to it.

## Educate the team

As you won't be able to do the review on all designs and changes, there will be something happens in a way not aligning w/ the architecture, big or small. That is another normal here you need to get used to. However, there is something we can do here, which is to **educate the team, get them on the same page on the design principles, trust them, let them to spread the idea and do the review on behave of you**. And, you need to keep doing this to make sure the message get delivered in a proper form. Remember, beside having automated infra in-place to enforce some design principles, there are ones need to be done manually. Someone asked me on how to improve team's design skill, those are my takes:

- There are few efficient ways to help team to learn and share
    - **Design Review**
        - The feature should have design and design review w/ whole team invited as optional, which should talk about the code design beside going through the user scenarios and high level breakdown
        - **Feedback should be taken and resolved properly** just like how we treat the comments on the PR before moving forward
    - **Code Review** (It is a validation of the design in detail)
        - **It takes time to have a helpful review**, plan accordingly not just for feature implementation, but also the time for the review (reviewer and reviewee)
        - Have the mindset to **'be responsible'** when asking for review and doing the review
    - Share the cookbook/channel about the patterns and usage examples
        - We definitely can build the 'cookbook' on the patterns and pitfalls when designing and using the tech stacks, and share with the teams
        - Some sharing session(brownbag/announcement) maybe helpful to **kick off some discussion** and get idea/knowledge spread
- Need some **alignment, emphasis, recognition and encouragement**
    - Emphasize on the usage/purpose of the 'Design Review' and 'Code Review' as tools
    - Spend the effort to build some shared components, documentation, and tool sets should get encouraged and recognized
    - The discussion with constructive feedback should be encouraged
    - And we also need to **be caution about over-design at first place**, some refactor will be necessary as we get more requirements along the way

Design review and code review are important tools to **guide the team to the same direction**, it is also a great way to **share and spread the knowledge across the team**, kick-off discussion, grow the team in design skill. Emphasize the usage and importance of the tools, encourage healthy discussion is always necessary and beneficial.

## Influence w/o authority

As a software architect, I believe, you **need the supports from your manager**, and, as the same important if it is not more, you also **need the support and respect from the teams as well**. I guess top-down enforce approach works for some cases and needed time to time, but, in the end of day, **you need the ones who can agree with you, carry on the idea and make it happen**. 

Most likely, you might be the same as I am, who is an IC('Individual Contributor') without any direct reports, in some companys' setup, the people manager, which can be your peers, is the ones have the power to assign the work items and allocate the resources. In order to trun the idea into real, you need the peoples to work with you. So, beside pitching the idea, you also need to convince the people manager to support it by allocating the resources to it.

It **become tricky when they have different priority & delivery goal** with you, **even harder, if you have different belief on the architecture and design itself**. What you are gonna do here? First, you need to understand the fact here, it will have different goal as yours, for example, teams need to deliver feature x,y,z in the end of A/B/C. You may not be able to get resource you want. It totally make sense, since, as business, you need to deliver something to your end user, **we always easy to picture the short term outcome, but, architecture effort, most of time, looks into the long term benefit**, better support on the products' needs, in terms of improving the team velocity, product quality, and user experiences etc,.

Sometime you may need to leverage the support from your manager to push something forward, but, most of the time, you need to figure it out by yourself. Along the way, those are my take from it: 

- In order to get support w/o authority, you need to be able to pitch the idea in a way relate to the goal others/teams have, in other word, **try to align on the goal, try to put yourself in others' shoes**. It sounds vague, actually, it is vague, because it is not a simple approach I can just summarize as steps here. 
- There is always something you can be helpful to the teams, and **try to be as genuinely helpful as you can**, it is not just to help the teams, even it is part of the effort, **it actually will help you as result to make thing happen**. That is exactly what I positioned myself, trying to be helpful for anyone who needs the help, **this is the process to gain the trust and help when you need it**.
- As developer, I believe **we have some common belief**, not matter you can relate/quantify it to the final business value or not, that keeps us close when pursuing something better and challenging ourself further.


## Summary

Software architect, it is to **structure the system to better serve products' needs** for now and forseeable future, figure out **the way and steps to transform the system from existing one to a more proper one**, it also **helps to form the culture, grow the team and lead them along the way**.
