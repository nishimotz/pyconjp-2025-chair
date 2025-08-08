---
lang: en
title: How do you write a < b < c in Python? - PyCon JP 2025
layout: default
permalink: /python-comparison-operators-en.html
---

## Answer: a < b < c

I'm Nishimotz, Chair of [PyCon JP 2025](https://2025.pycon.jp/).

Previously, I wrote this article: [https://note.com/24motz/n/n15b9cc1de0ae](https://note.com/24motz/n/n15b9cc1de0ae)

After that, I got curious and asked AI, and learned that languages with syntax that can simultaneously exchange (multiple assignment) multiple variable values in one line like Python's "a, b = b, a" exist in other languages too.
So languages like Ruby, JavaScript, Perl were mentioned.
That's right.
Indeed, it's not a feature unique to Python.

So how about this?

**a < b < c**

This is the symbol you often see in math textbooks meaning "a is less than b, and b is less than c," right?

**In Python, you can use this mathematical symbol as-is!**

## What does it mean that mathematical symbols can be used directly?

For example, suppose you want to check "whether a test score is higher than 50 points and lower than 80 points."
In many other programming languages, you'd often write it like this:

score > 50 **and** score < 80

But in Python, you can write it more simply, **just like in mathematics**:

```python
score = 60

if 50 < score < 80:
    print("Good score!")
```

No extra symbols, and it increases from left to right, making it very readable.

## Learn more "awesome things" about Python at PyCon JP 2025!

Learning Python at school is a **wonderful first step** into the world of programming.
And PyCon JP 2025 is a place for you, having taken that first step, to explore Python's charms even deeper.

Where other programming languages write:
a < b and b < c
or
a < b && b < c

Python writes:
a < b < c

Why not experience at PyCon JP how such things actually arise from Python's "language design itself" and how they're used in actual professional settings?
Please come discover the "more awesome!" parts of Python that school doesn't teach you.

PyCon JP 2025 will be **held in Hiroshima at the end of September 2025**.
Why don't you come to Hiroshima to experience this "Python magic"?

## PyCon JP 2025 is recruiting speakers and sponsors!

PyCon JP 2025 will be held at **Hiroshima International Conference Center** on September 26-28, 2025.
The last day is development sprints. [https://note.com/24motz/n/n4f6801257221](https://note.com/24motz/n/n4f6801257221)

**This is the first time PyCon JP is held outside Tokyo**, and we're currently recruiting speakers (proposals).
The deadline is June 29.
Don't think it's still far away! It'll be here in a flash!

This year, **posters and community posters have the same deadline**, so please be careful!

[https://pretalx.com/pycon-jp-2025/cfp](https://pretalx.com/pycon-jp-2025/cfp)
[https://pyconjp.blogspot.com/2025/05/pyconjp-2025-call-for-proposals.html](https://pyconjp.blogspot.com/2025/05/pyconjp-2025-call-for-proposals.html)

**We're also recruiting sponsors.
Please support us to realize the PyCon JP we want to create.**

If you have any questions, please feel free to contact us at the inquiry address listed in the materials!

[https://pyconjp.blogspot.com/2025/06/pyconjp2025-sponsorship-result-ja.html](https://pyconjp.blogspot.com/2025/06/pyconjp2025-sponsorship-result-ja.html)
[https://note.com/24motz/n/n8828bcad687a](https://note.com/24motz/n/n8828bcad687a)