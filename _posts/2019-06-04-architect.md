---
layout:     post
title:      Software Architect
date:       2019-06-04 17:43:00
summary:    Looking back my career, and how I 'accidentally' get into the software architect role, what is my understanding on what it should play as a role, and stuff I learnt along the way.
categories: general career architect
---

For my career path, it should be up to date on my LinkedIn [profile](https://www.linkedin.com/in/knightlinwu/). Everyone has different track to get where it has been for now, for the sake of this post, as a context, let me have a quick summary on my career track so far. 

- 2004 Aug, I was starting as software engineer working on very low level embedded devices, was working on hardware programming by using VHDL on FPGA, boot loader, drivers and OS HAL(hardware abstraction layer) on ARM chip-set for smart TV, smart phone and hand-held devices. 

- 2008 Jan, I joined Microsoft as software engineer, worked cellular stack and web platform (for Windows Phone browser, Microsoft Edge browser), mainly focused on the HTML engine, performance and Browser architectures. 

- 2017 Oct, I joined Microsoft Advertising team, mainly focused on the architecture of its applications across platforms (Web, Desktop and Mobile), until now (June, 2019). Technically, I am the software architect of Microsoft Advertising applications (Advertiser facing).

So, my career path pretty much starts from low level programming, then building application platform and applications. The first time I feel I am starting play as architect role was when I was working on hosting architecture for web platform.

Let's talk about what is software architect, what software architect does.

It is all about the scope, the scope of impact the change, change in the system and code base, change the focus on the engineering team. As our day to day work, there is always some design work get involved in certain scope, which may be a design you will implement it by yourself, or for few developers as a crew, but it not all about amount of people gets involved, their are few difference here:

- The architecture design is serving for the products as the organization which will focus on and ship to end user. So, it is to serve the products' needs as beginning and scope of view when you are making the design decision.
- Since it serve for the product rather than just a set of feature, it need to put the end to end into consideration, including
    - Coding, which programming languages we we will choose for what purpose
    - Debugging, for development, for testing, what hardness we can use, is it efficient enough
    - Testing, how the developer should write test, unit test, component test, integration test, all are serving for its own purpose
    - Integration, 
    - CI, 
    - CD, 
    - Telemetry, 
    - Monitoring, 
    - User support/feedback response
- The choice is base on the status of the engineering team and looking beyond, their existing expertise and assets
- Cost, there is always limited resources, as a business, all the effort should be justified, and delivered as part of product to the end user, in some form. Either more fast to add new feature, improved performance, stability, user experience etc,.
- Plan on how to get to the pictured architecture, the design along the way