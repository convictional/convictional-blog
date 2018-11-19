---
layout: post
current: post
cover: /assets/images/translate-api.png
navigation: 'True'
title: Free EDI Translation API
date: '2018-11-19T01:00:00-05:00'
tags: EDI
class: post-template
author: roger
---
As a software developer, you may be asked at some point to translate an EDI document into another format. The challenge is that EDI document translation is often done by proprietary software installed on your computer in a way that is totally opaque to the user. Most EDI users don’t actually translate the documents themselves, their system just comes with those abilities. When we started Convictional, we wondered why an API didn’t exist to help provide this service, the way other APIs provide functionality too complex or specific to justify building in-house.

Today, we’re releasing our EDI translation API for free. Our goal is to make EDI more accessible to modern companies: basically, to make it easier to use for technical users and non-technical ones. When we think about the different things we have done that saved us time working with customers, one of the most useful things we did was to build our own EDI translation engine. We wrote it in a generic way, so you still need to know a little bit about the documents you’re working with. But it saves the developer from headaches like formatting and parsing.

We thought about releasing this functionality as a library but that would make it a lot harder for us to iterate on it based on new fields, document types and other things that people use it for. This way we can understand how it’s being used and attempt to improve it in real-time without breaking the basic contract (EDI documents go in, JSON representations come out). The compute cost is very little compared to the future value to us and our customers of a strong EDI translation API. A version will always be free and in future we’ll offer more usage-based APIs.

To use it, sign up for an account and take a look at the documentation. You can provide the EDI document in X12 format as plain text, and we’ll send back a JSON object with all the fields. It works for any X12 document. If we’ve seen that segment before (there are thousands!) we can either provide it back to you in the raw format, or give you the name of the field to make it easier. You can decide when you make the request whether to get the raw format or cleaned up one. Our hope is that we can use this as a tool to better understand how developers are using EDI.
