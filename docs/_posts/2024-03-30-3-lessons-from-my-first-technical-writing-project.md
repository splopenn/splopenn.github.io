---
layout: post
title:  "3 Lessons From My First Technical Writing Project"
date:   2024-03-30 12:00:00 -0400
categories: writing
---
I recently wrote my first set of documentation that wasn’t part of a classroom assignment. It was tough, but I learned a lot. (Much of it by trial and error.)

I wrote the [Staff Catalog](https://docs.evergreen-ils.org/docs/latest/staff_catalog/introduction.html) docs for the [Evergreen Integrated Library System](https://evergreen-ils.org/) as part of the [Documentation Interest Group](https://wiki.evergreen-ils.org/doku.php?id=evergreen-docs:dig). I wrote the code in [AsciiDoc](https://asciidoc.org/) using Visual Studio Code and pushed it to the [GitHub](https://github.com/evergreen-library-system/Evergreen/commit/452a51637d512d0fced31372d31f627c0e21684d). The DIG uses [Antora](https://antora.org/), which is a site generator I am still learning more about.

Here are a few things I learned — I hope it saves you some time!

# Get Feedback Early

This one tip save me hours during this project: ask for feedback early. Since this was my first project, I only wrote one page of documentation before running it by the group. I came prepared with specific questions:
- Are my file references correct?
- Is my alt text acceptable?
- Am I formatting everything correctly?

I made sure to ask  specific questions rather than just asking them to review the files and give me feedback because they’re all busy people and don’t necessarily have the time to closely read the entire file. This saved time on their end and gave me more useful feedback.

I asked these specific questions because they weren’t clearly addressed in our style guide, and they are easy things to fix early, but would be much more difficult to fix later on.

# Check Other Files

Many times in this process I was able to answer my questions by consulting existing docs source files. This was especially helpful for questions of formatting or best practice.

It also showed my team that I respected their time by trying to help myself first.

However, this was not always useful because the docs are not always consistent. Since this is a volunteer-run group with many contributors, it’s hard to make sure everything is always correct. When I couldn’t find answers by referring to other docs or the style guide, I just asked the group. It's always better to ask and learn than to guess and have to spend more time correcting it down the road.

# Refer to the Style Guide Often

One mistake I made was not checking the style guide often enough. A few times, I thought I knew the correct way to format a term or write a file path, but still had some doubt in my mind. I often chose to trust my gut instead of just checking the guide, which led to repeating mistakes and ultimately wasted time.
