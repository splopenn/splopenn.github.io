---
layout: post
title:  "Dive into DITA"
date:   2025-06-04 12:00:00 -0400
categories: technical-writing
---
DITA. It's a [sunglasses brand](https://dita.com/), but it's also an [architecture for representing documentation](https://en.wikipedia.org/wiki/Darwin_Information_Typing_Architecture). More than that, it's something I understand as a concept, but haven't had any chances to use. So, I thought I'd jump in.

Today is just Chapter 1. More like the introduction, really. I brushed up on the basics of DITA with a [YouTube video](https://www.youtube.com/watch?v=-Y4qslKhmOY) and the [Wikipedia article](https://en.wikipedia.org/wiki/Darwin_Information_Typing_Architecture). But I really want to get my hands dirty — and dirty they got.

I decided to install the [DITA Open Toolkit](https://www.dita-ot.org/). I have *some* experience with command line, so I figured, why not? Well...

The [documentation](https://www.dita-ot.org/dev/), while great (I'd expect nothing less), is geared towards people with a *little* more experience than I have. I downloaded DITA-OT and unzipped it (in the right place), easy-peasy. But then...

> Ensure that you have a Java Runtime Environment (JRE) or Java Development Kit (JDK).

Haha. Okay. I can do that. This only took one Google search, but I got it sorted.

Next up...

> Add the absolute path for the bin folder of the DITA-OT installation directory to the PATH environment variable.

Yeah, sure, *let me just do that.* 

To figure this one out, I:

- Read the [Wikpedia article](https://en.wikipedia.org/wiki/PATH_(variable)) they linked. (Okay, I skimmed it, so what?)
- Watched a [YouTube video](https://www.youtube.com/watch?v=Ao_Jvk1J5i0).
- Asked ChatGPT for help. (Didn't help.)
- Paced.
- Returned to the YouTube video — and, **got it**.

It wasn't actually that hard. I just freak myself out when I mess around with Terminal. But, hey, nothing seems to be broken.

...and a note on that. I just returned from a 30 minute break to figure out why `dita --version` was *no longer working*. But don't worry. ChatGPT and I figured it out. Back in action.

The most beautiful thing I've seen today? Easy.

`~ % dita --version`
`DITA-OT version 4.3.1`

Stay tuned. I'll post when I mess something else up.