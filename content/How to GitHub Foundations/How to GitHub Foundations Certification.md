---
title: How to GitHub Actions
draft: false
tags:
  - example-tag
---

> **How to use this template :**

> Use this template to create and present your team with a software architecture proposal. You can easily share this page with your team [ via 🔗 Secret Link.](https://support.craft.do/hc/en-us/articles/4413266374673-Sharing-Documents)

---

# Introduction

I have challenged myself to take prepare and take the GitHub Foundations exam in 36 hours! (Not that I don't have other things to do haha)

But let's get in to it:

- Step 1 - Book the exam to motivate yourself to study.
- Step 2 - Write a blog to procrastinate.
- Step 3 - Read the study [guide](https://assets.ctfassets.net/wfutmusr1t3h/1kmMx7AwI4qH8yIZgOmQlP/79e6ff1dfdee589d84a24dd763b1eef7/github-foundations-exam-study-guide__1_.pdf)
- Step 4 - Learning Path [here](https://learn.microsoft.com/en-us/collections/o1njfe825p602p)
- Step 5 - YouTube Tutorial [here](https://www.youtube.com/watch?v=Jdc0i7RcBv8&t=30038s)

# Theory of operation

Create an architecture diagram describing the proposed solution

![Paginated Full Sync.jpeg](https://res.craft.do/user/full/bfc7e208-6889-acda-34d3-41fecaa071c1/doc/5DCFE626-E381-4772-A55C-056C6B3E05F4/bb9f92ea-8820-2e82-1319-b9b9b597e762/Paginated%20Full%20Sync.jpeg)

Spell Out the Details of the proposed architecture

- ::component 1:: does X
- which impacts ::component 2::
- ::component 3:: does Y
- ::component4:: finishes work off

# Code Level Examples

Demonstrate the proposed changes with code wherever needed

```json
>> Request

{
   "support": [ "ver_1" ],
   "data": { }
}
```

Demonstrate the proposed changes with code wherever needed

```json
<< Response

{
   "data": { ... },
   "continuation_token": "<token1>"
}
```

Demonstrate the proposed changes with code wherever needed

```json
>> Request

{
   "continuation_token": "token1"
}
```

Demonstrate the proposed changes with code wherever needed

```json
<< Response

{
   "data": { ... },
   "sync_token": "<sync token>"
}
```

# FAQ

#### Question 1

> Answer to Question 1

#### Question 2

> Answer to Question 2

