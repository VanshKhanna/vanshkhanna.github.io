---
layout: post
title: "Disrupting the Arena (B2B Saas)"
date: 2025-07-01
categories: [software]
author: "Vansh"
---

> the more things change, the more they stay the same - Jon Bon Jovi 

B2B Saas is maybe the oldest profession out there. The pimp tracking his girls in the wild west was really just doing b2b saas with human as a controller. You scoff, but almost every succesfull YC startup was once a precocious founder with an excel sheet (see: vanta).

But modern business software runs on computers and boils down to 3 components:
- **UI**
- **Controller**
- **Memory**

**UI** is how your user interacts with the product. Maybe it’s clicking, maybe it’s typing, maybe it’s something else. Chat is the latest trend, unlocked by LLMs. Before LLMs, Apple unlocked colorful UIs with the mouse. The internet, somewhere in the middle, brought about JavaScript, web2, and new ways to interact with your software that was now running 1000s of miles away.

**Controller** is what routes input and determines what to do. This is what everyone calls “business logic.” Every SF-style software company, it starts with the MVP and evolves into a complicated beast of microservices, data pipelines, and more. But really, it’s just a router: take user input, do some compute, return a response. You can break the controller into a router and the core business logic, but that’s just semantics.

**Memory** is what aids the UI and controller—and in my opinion, how every business actually makes money. Recording preferences, automating work, tracking events…whatever. A software product without some kind of memory/storage to track some function of user input will never make money. Maybe you’re not tracking direct user input, but you have to track something. Even old-school Google -famously a read-only, profitable consumer product- indexed the web for you. Memory is how you make money.

Lot of debate and contention around the relevance of B2B saas software with the imminent arrival of AGI/ASI/SSI/etc. But beneath the surface, it is still `Memory[f_controller(UI)]`, except each one has since evolved.

A low fidelity MVP today would replace UI with chat. I am constantly amazed at how forgiving users are of an LLM backed chat and on the other hand how restless and critical they are while using a specially crafted UI.

Next, with function calling, you can replace your entire business logic with an o3 llm. Oh, is it unsafe? Non determinstic? Buggy? Well, so is your code and the LLM is usually much better than you are. You can keep fighting it, but all software is headed this way. The LLM might be testing and creating a plan for another engine to execute, but the routing and descision making for how to do what the user requested will be quickly handed over to an LLM. Not because it's better but because it can do everything right out of the box, while your pre-llm competition is still in a `trifecta` meeting between a PM, a designer, and a lead engineer trying to figure out if it's worth the resources.

Which leaves us with memory/storage/the data. Like always, that's what it will come down to. But it's not easy to get someone to pay you money and also give you their data. Saas sales is art at it's best, but on an average it's hoodwinking with extra steps. It's tricky contracts, huge egos and uncomfortable age-gap conference after- parties in Vegas.

The product, usually built for a lowly analyst, is sold to a CIO/CTO/CEO who's never gonna touch it.

**Where does B2B saas, *the arena where boys become men*, go from here?** Wherever it wants really. It's easier than ever to create software but selling it is just as hard as it ever was. Not harder. But still pretty hard. Your moat then might come from how well you are able to prompt your LLM for that niche vertical that everyone else has also identified but are unwilling to solve.

Happy Building!