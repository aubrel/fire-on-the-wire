# Contributing to Fire on the Wire

> :construction: TK-TODO

FotW hearily accepts contributions! The only thing we ask is that your content be accurate and in line with [our general goals](issues/shared.md#goals). :wink:

Here's how to contribute, if you're so inclined.

## What We Want

* Guides on using existent tools
* Translations of existent texts
* Theoretical writing around relevant concepts

1. First, choose which tier your work fits in with best. Tiers are centered around a particular theme, mutually informed by the general level of skill and familiarity with digital tooling that is needed to understand the guide for the tool. The tiers are:

    1. [Liberation](issues/1/)
    1. [Autonomization](issues/2/)
    1. [Collectivization](issues/3/)

In addition to these three tiers, we also have [Addendum](issues/addendum) issues, which cover things that are not touched upon by the core tiers, including offense and defense, more expansive theorhetical writing, and perhaps specific deep-dives into ideas we haven't even thought of yet. Addendums are like sattelites, and are the most openly free and community driven, where the core tiers serve as a general organizing principle for the main goals of this body of work.

Both the core tiers and the addendums can be contributed to, and contributions to either are always welcome and open; the only difference is that what is included in the core tiers is selected more strigently. It's entirely possible that a contribution originally submitted for consideration in the core literature will make its way into an addendum of its own or as one part of an addendum issue.

## Core Tier Descriptions

### Liberation

* How to move away from centralized services and towards open source, free ones.
* Necessary Skill Level: Little to none (beginner)
* General ideas:
    * Moving away from centralized services to free and open source alternatives (eg. [OpenStreetMap](https://openstreetmap.org) versus Google Maps).
    * Into to the command line
    * Basic organizational tools (eg. Wikis, secure messaging services, calendars, file sharing and storage)

### Autonomization

* How to enter the world of self-hosting.
* Necessary Skill Level: Medium to high (intermediate)
* General ideas:
    * Assessing the needs for and regarding self-hosted infrastructure based on the successes and habits developed from using free and open source tools (eg. if the organization uses OpenStreetMap a lot and finds that it has needs for using maps a lot in general, how does one utilize and implement maps for the org's own purposes?) 
    * Beginnings of system administration
    * Virtual machines
    * Making decisions about and constructing autonomous infrastructure
    * Handling hardware questions
    * Introductions to more advanced security questions regarding:
          * Encrypted disks
          * Network security
          * Opsec

### Collectivization

* How and when expand self-hosted systems, including both systems that were introduced and explored in the first stages of self-hosting, and expanding to networking infrastructures such as intranets, extranets, and mesh networking.
* Necessary Skill Level: High (advanced)
* General ideas:
    * Assessing the needs for and regarding the expansion of various self-hosted infrastructures based on the successes and habits developed from using those self-hosted infrastructures in the context of the organization (eg. when and how does one organization need to grow to fuse into another? How can education spread from one organization to the next? Or, more internally, how can/should one system talk to another? How does an org judge this and then implement this depending on those judgments?) 
    * More advanced system administration
    * Larger scale automation
    * Handling hardware questions
    * Introductions to more advanced security questions regarding:
          * Encrypted disks
          * Network security
          * Opsec

1. Once you have determined either that your work would best benefit one of the core tiers or would be best suited for an addendum, you can submit files for review.

> :construction: TK-TODO
          
### Addendum Topics

See the [addendum](issues/addendum) page for current topics of interest. Other topics may organically emerge by virtue of being suggested through contributions.


# Translate

One way you can help is by translating our texts into a language that you know, but that we do not. We prefer translated texts to be separate files, side-by-side with the initial (i.e., in the same folder). Copy the file you are going to translate with an ISO 639 language code in the file extension. As fluent English speakers, our default language is United States English (`en-US`). Files with no language code are thus expected to match that locale.

For example, to translate the [top-most README](README.md) file into Spanish, copy the file like so:

```sh
cp README.md README.es.md
```

The file `README.es.md` should now be edited so that any English in the document is translated into Spanish.
