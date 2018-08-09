# Liberation: Issue 1

In this issue, we will introduce some free, open source, and easy-to-use digital tools that most radicals don't talk about, as well as how (and why) to use them. Liberation(1) focuses on introducing tools that require little to no deep skill or familiarity with which to get started, which nonetheless provide powerful organizing abilities to both individuals and groups.

# Contents

1. [Introduction](#introduction)
1. [Communication forms](#communication-forms)
1. [Synchronous communication](#synchronous-communication)
1. [Messaging](#messaging) 
    1. [Signal Private Messenger: A deeper dive](#signal-private-messenge)
    1. [What is Signal Private Messenger?](#what-is-signal-private-messenger)
     1. [How to get Signal Private Messenger](#how-to-get-signal-private-messenger)
    1. [Using Jabber with OMEMO](#using-jabber-with-omemo)
1. [Asynchronous communications](#asynchronous-communications)
    1. [Using a Sandstorm.io grain to host a subscribable calendar](#using-a-sandstormio-grain-to-host-a-subscribable-calendar)
    1. [What are, and how to use, ICS feeds](#what-are-and-how-to-use-ics-feeds)
1. [Organizing](#organizing)
    1. [Getting started with GitHub](#getting-started-with-github)
    1. [Getting started with Crabgrass](#getting-started-with-crabgrass)
    1. [Back to Sandstorm apps](#back-to-sandstorm-apps)

# Introduction

The Western narrative of what it means to be a technologist has sadly never exactly been a holistic one, only ever enjoying a few brief moments of real magic throughout its history. The narrative has also become strangely backwards; hung by its ankles, perhaps to make the reality of what it means to have technical power harder to realize.

The Tech Industry, and technologists informed by it, will want you to believe that being a technologist means writing code, and creating new software. This, however, is a bad starting place, for the main reason that knowing how to build something does not necessarily mean you know how to use the thing effectively. But moreover, a great number of needs have been anticipated by many people throughout the last decades, and many people who have already seasoned their programming skills have created free and open source software that you can pick up and use right now.

Learning how to use software effectively used to be the starting point for technologists, and it is the opinion of this book that that is where everyone should start, if for no other reason (though there are plenty of other reasons we will come to) than to become familiar with the incredible landscape of what already exists.

Another word of advice: it is easy for groups who do not know enough to make meaningful distinctions to talk endlessly without ever trying anything. Never let endless rhetoric distract or intimidate you from just picking up and trying things out.

At the very least, pick up the following and give them a shot; we'll provide you with some reasons why we like these tools. The fundamental principles introduced here will be built upon throughout this series.

# Communication Forms

One of the most important distinctions that needs to be made immediately is the difference between synchronous and asynchronous communication.

This distinction was once elegantly summarized as the difference between being on the same or different "clocks." In other words, whether or not the events in a sequence, like a conversation, follow immediately one after the other. When you're talking to someone in person, for example, this is a method of synchronous communication. We do not normally say one thing to a friend, to have that friend then walk away from us for a few hours and then return and pick up the conversation immediately where it was left off. This may happen occasionally, but it is not how we normally have conversations. Note, too, that even in this special case, when the conversation is returned to, someone needs to remind the other where they left off.

With asynchronous communication, all involved are on different clocks. This means that each person can get the same information in the same way, but at different times. Another way to think about this difference is to think about synchronous communication as a web, in which communication transmits from one point to another, and one action is dependent on another prior action.

Whereas asynchronous communication is more like a watering hole. There are no connecting threads, and everyone comes and goes as they please. If there ate changes, those changes are discovered at different times.

One thing that easily differentiates synchronous and asynchronous communications is that synchronous communications are ad-hoc and rarely written down _in a templatized way._

A primary and easy distinction between these two methods is whether or not the communication was _recorded_, usually meaning _written down_. In synchronous methods, one does not necessarily need to write anything down, whereas asynchronous communication depends upon its being written down; otherwise there would be no way to have conversations without being in the same place at the same time, and if you don't do that, it is the view of this book that _you cannot organize meaningfully._ Period. Hence why it is so important to make this distinction right off the bat.

Synchronous communication is of course just as vital. Nothing develops or grows without synchronous communication.

The point here is, you need both forms absolutely. However, especially in radical circles, it's asynchronous communication that is terribly undervalued, and without a fundamental change in that, no meaningful organizing can happen. Another thing that also happens, which we will address shortly, is that whatever asynchronous communication is being done should be _thoroughly detailed_, so that no follow up questions are needed and time does not go by waiting for an opportunity to have synchronous communication.

Sometimes, we meet hybrid forms of communication, such as texting.

Texting is an example of a form of synchronous communication done in an asynchronous medium. It is synchronous as is defined by its sequential manner and ad hoc nature – one response logically follows another – but it is written down, such that anyone may come back to it later to review it.

However, when reflecting on the use of a tool in an organizing context, consider how it would be to a text or chat log as your main body of reference. It would be extremely inefficient, time consuming, and frustrating. If someone had to scroll through hours of text messages just to find one date and time, it would be an infuriating way to go about things. Even if you have decided to have a dedicated chat room or thread in which only date and time information was recorded, you would doom that potentially malleable information to a static form, thereby neglecting the very most important aspect of digital tools: the magic lies not so much in _what_ is written, as much as in _how_ it is written.

Writing, in a digital context, is invaluably flexible. Its main characteristic, which is so often forgotten or never exposed, is how infinitely a single written thing can expand, bend, and shapeshift. If this power of elasticity can be understood and mastered, then tremendous possibilities for self-empowerment become apparent.

Shapeshifting is the business we are in here, and this is the main principle of this entire work.

Now, we will review some tools that deal with synchronous communication, and go over why this book believes they are good ones.

# Synchronous communication

## Messaging

When we talk about messaging, there are a few things we should clarify. When we say "messaging," what we actually mean is a form of communication that is:

* Synchronous: More often than not, when we use text messaging, we are expecting a response in not too long. At the very least, everyone is on the same "clock."

* Ad-hoc: Messaging services in the way we mean them refers to something that is "ad-hoc," meaning on the fly and for a specific purpose that arises at the moment. Because of this, it is more conversational than infrastructural.

### Considerations

* Security: This is of course the first issue that arises in the context of radical organizing. How safe is it for you to use the tool you've chosen? How easy would it be for someone to compromise? What is your threat model and how does your tool fit into that model? How easy would it be for someone to misuse the tool? What does the worst case scenario look like in the case of compromise if using this tool? And so on and so forth. When it comes to these questions, there are a few measurable aspects that we can look at.

    * Encryption: This comes up a lot when discussing any kind of digital tool. Is the transmission and content of the message encrypted? What does this mean?

    * Authentication: Where encryption is about securing the content and method of transportation, authentication is about securing the _source_ of the transmission. How do you know the source was not tampered with, changed, or intercepted on its way to you? How can you be sure that the person you think you're talking to is who they say they are?

    * Storage: Where are the messages being stored? Who in total has access to them? Can you trust every point at which the message traverses from origin to destination?

* Ease of use: Is the tool easy to use?

## Using Signal…effectively

  >  :construction: TK-TODO Fit the below into the structure of the above. Address each issue outlined above below.

If you're anywhere near radical circles, you've almost definitely heard about [Signal Private Messenger](https://signal.org), and are maybe already using it. If you felt comfortable enough to ask the person who told you to download an app you've never heard of and use it exclusively for messaging why you would do such a thing, you might have heard something along the lines of, "something, something, end-to-end encrypted." Oh, and maybe something about a private... security... number? Or something...?

Let's demystify the world of Signal, explain why it's actually a good idea to use, address some of the common fears about using it, and explain the vital importance of Signal Safety Numbers.

### What is Signal Private Messenger?

> :construction: TK-TODO

### How to get Signal Private Messenger

> :construction: TK-TODO

## Using Jabber with OMEMO
> :construction: TK-TODO

# Calendars

> :construction: TK-TODO Add a description re: using digital calendars.

## Using a Sandstorm.io grain to host a subscribable calendar
> :construction: TK-TODO

## What are, and how to use, ICS feeds
> :construction: TK-TODO

# Organizing
> :construction: TK-TODO Add a description re: organizing spaces.

## Getting started with GitHub
> :construction: TK-TODO

## Getting started with Crabgrass
> :construction: TK-TODO

> :construction: TK-TODO Determine what other tools to add, and add their guides.
