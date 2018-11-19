---
layout: post
current: post
cover: /assets/images/desk.jpg
navigation: 'True'
title: What EDI Is Not
date: '2018-11-13T12:43:40-04:00'
tags: EDI
class: post-template
author: roger
---
We talk a lot on this blog about what EDI is. It’s a pretty complicated thing, combining technology and standards across a bunch of industries. But EDI as a way to connect with suppliers and sellers of your products has limitations too, and getting scope right matters.

EDI is not a good way to communicate with people. It’s a language that systems use to share information, but it’s basically unreadable for people. That means if either you or the trading partner you are trying to integrate with have to deal with the documents manually outside the context of an integrated system, it will be a real challenge to read them in any meaningful way. 

EDI is not a good way to store information. EDI is stored in files, but those files tend to represent a single document. There isn’t a good way to query information from those documents, they are basically just self-contained records about what’s happening in a business (like an order). Even if you have EDI files, you should be storing them somewhere like a database to query them. Further, it’s good practice to have a secondary way of storing that information beyond the files.

EDI can’t speak to every system. Primarily, it can speak to those that started to deal with integration before the internet. Post-internet, most systems use REST and other kinds of web APIs (application programming interfaces, a post-internet way for systems to share data) for sharing business documents. So EDI is limited primarily to systems that started to be built and put into practice prior to the advent of the internet. Many important systems fall into that category, but there is a generational gap between modern APIs and older ones like EDI.

EDI isn’t good if you have custom requirements or require flexibility. The benefit of a strictly defined standard like EDI is that in theory, lots of companies can be speaking the same language. The flip side is that introducing custom requirements or trying to be flexible about what does and doesn’t go into your EDI documents can be problematic for everyone else. As a result, it can be a real challenge to meet business-specific requirements and still do valid EDI.

We’re trying to make it easier to do things like meet custom requirements, store your business information, speak to any system (not just EDI ones) and share the documents with people. If you can think of other business integration needs that aren’t fit by EDI, we’ll add them here.
