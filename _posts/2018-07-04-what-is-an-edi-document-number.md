---
layout: post
current: post
cover: /assets/images/edi.jpg
navigation: true
title: What Is An EDI Document Number?
date: 2018-07-04T09:00:00.000Z
tags:
  - edi
class: post-template
author: roger
---

EDI is a standard approach to sharing information between companies. Most companies in North America follow the X12 standard, which uses numbers to represent documents. Every kind of business document you can imagine have a number that corresponds with that type.

When you are sharing documents, partners will ask to share particular document numbers back and forth. If you are new to EDI, this might not be obvious at first. Various excellent resources exist that help map the document numbers to the kind of document you are sharing.

[Click here for a link to the official list of documents and the corresponding document number](https://en.wikipedia.org/wiki/X12_Document_List).

There are hundreds of potential documents that could be shared but those dealing with suppliers and retailers selling consumer products usually only deal with a half dozen or so. Occasionally you will see weird partner-specific ones but it’s mostly just a few core documents.

Let’s talk about how each document actually works. It’s one thing to provide a lookup, but that doesn’t necessarily explain why you might need one document or another in the course of business. So we’ll explain where each one fits in using a narrative approach.

You just got hired as the Operations Manager at Convictional Wholesale, Inc. Your company trades in various goods destined for major retailers all over North America. A huge retailer, named after a particularly long river in Brazil, says they want to buy stuff from you wholesale. This is exciting, but first you need to be EDI compliant.

Sidebar: that’s right, you have to be EDI compliant from day one even though you won’t necessarily get a purchase order right away or get paid for a long time.

The retailer says they want to be able to send you orders (850). When you get an order, you will need to review it and confirm whether you are comfortable with the terms and items it contains. If you are, just let them know (855) so they will know to expect it from you. Sometimes they’ll realize they messed up and need to make a change, so they’ll send you a change request (860). If you are okay with the changes they are making, you can confirm it again (865).

Once you are ready to ship the order, the retailer asks that you let them know in advanced so they can be ready on their end. So you send an advanced ship notice (856) to let them know the shipment is on the way. Now that you have shipped the goods, you need to get paid. So you have to send the retailer an invoice with details about what was shipped (810). At that point the retailer can confirm they received what you sent and pay the invoice (eventually).

To make sure you are both on the same page, the retailer also asks to share some information on an ongoing basis. The retailer wants updates on stock levels (846) so they know not to over promote or sell your product without stocking up first. And finally, the retailer requests that you let them know a document makes it to you any time you receive one (997), and they will do the same in return so you can confirm information is getting where it needs to go.

You’ll notice this is a pretty standard exchange of information between two trading partners. The key thing to keep in mind is that most steps described above are completely automated. Other than reviewing the orders as they come in for accuracy (always make sure pricing matches up with your prices -- the retailer pays whatever it says on the EDI documents, not necessarily what you agreed to) most of the work described is done automatically by computers.

In order to facilitate sharing this information, you will need to have systems on your side that contain each type of record involved in the information sharing. Further, you will need a way to share information back and forth with the retailer in an automated way, without dropping messages and ensuring that the documents reach their destination in the retailer’s system. Sometimes this is called a VAN (value-added network, like an internet service provider but for EDI document sharing) and sometimes you can do this yourself through your existing systems.

Next time you are asked to share a particular document number, it is generally safe to assume that your partner wants to trade using the X12 format. You can use the link above to lookup which documents they are referring to, and make sure you are in a position to support them. There are many aspects of EDI that are not particularly transparent or intuitive, but that’s why we are making it part of our mission to shine a light on the black box that can be using EDI.

If you have any questions about this post or your partners require something you don’t understand, get in touch with us and we can explore whether our platform can help.
