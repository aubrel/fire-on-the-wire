# Contributing to Fire on the Wire

FotW hearily accepts contributions! The only thing we ask is that your content be accurate and in line with [our general goals](issues/shared.md#goals). :wink:

Here's how to contribute, if you're so inclined.

## What We Want

* Guides on using existent tools
* Translations of existent texts
* Theoretical writing around relevant concepts

First, choose which [tier (volume)](issues/README.md#issues) your work fits in with best. Tiers are centered around a particular theme, mutually informed by the general level of skill and familiarity with digital tooling that is needed to understand the guide for the tool.

We also have [Addendum issues](issues/addendum), which cover things that are not touched upon by the core tiers, including offense and defense, more expansive theoretical writing, and perhaps specific deep-dives into ideas we haven't even thought of yet. Addendums are like sattelites, and are the most openly free and community driven, where the core tiers serve as a general organizing principle for the main goals of this body of work.

Both the core tiers and the addendums can be contributed to, and contributions to either are always welcome and open; the only difference is that what is included in the core tiers is selected more stringently. It's entirely possible that a contribution originally submitted for consideration in the core literature will make its way into an addendum of its own or as one part of an addendum issue.

### Addendum Topics

See the [addendum](issues/addendum) page for current topics of interest. Other topics may organically emerge by virtue of being suggested through contributions.

# Translate

One way you can help is by translating our texts into a language that you know, but that we do not. We prefer translated texts to be separate files, side-by-side with the initial (i.e., in the same folder). Copy the file you are going to translate with an ISO 639 language code in the file extension. As fluent English speakers, our default language is United States English (`en-US`). Files with no language code are thus expected to match that locale.

For example, to translate the [top-most README](README.md) file into Spanish, copy the file like so:

```sh
cp README.md README.es.md
```

The file `README.es.md` should now be edited so that any English in the document is translated into Spanish.
