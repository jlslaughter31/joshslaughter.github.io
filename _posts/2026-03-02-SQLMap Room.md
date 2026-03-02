---
layout: post
title: "SQL Map Room!"
---

Over the past several months, I’ve been intentionally building a foundation in cybersecurity with the long-term goal of becoming an ethical hacker and security professional. This site documents that journey, as I thought it would be helpful to show not just what I’m learning, but how I’m thinking through problems and developing practical skill. This post documents my time on TryHackMe room "SQLMap: The Basics". Welcome in!

---

## "SQLMap: The Basics" Room Complete!

The next step on the roadmap in my cybersecurity journey is interacting with web applications through SQL injection via SQLMap. I've been working my way through the rooms on TryHackMe. I'm keeping details high-level to avoid spoilers for the millions of people that will for sure read this, and also to stay within platform guidelines.

I'm currently in the Offensive Security Tooling section (Cyber Security 101 > Offensive Security Tooling) which has been challenging, to say the least. It seems like for most of these rooms, there is one underlining concept that makes the whole room click. And so, you'll probably struggle until you understand that concept.

SQLMap automates the detection and exploitation of SQL injection flaws in web applications.

After skimming over the basics of SQL (handled more in-depth in another room), the author of this room did a great job getting to the point of the room: how to exploit web applications with SQLMap.

This room was actually pretty easy compared with some of the more recent rooms I've done. Everything was laid out well, explained well, and it truly felt like a beginner room. It was nice to kind of take a breath, and not have to dive through some of the hoops some of the other rooms present.

Web apps that don’t properly parameterize SQL queries can be vulnerable to SQL injection, and SQLMap can automate testing and exploitation. For this room at least, SQLMap appears to like anything to do with the GET function. For this room, the specific function that was exploited was "cat". Manipulating the URL can lead to unauthorized database queries, which can lead to the untimely release of user details: usernames, passwords, etc. Anything that is stored in the database, I would assume, is vulnerable (depending on permissions and defenses).

---

## What Clicked for Me

- The syntax of the commands, easy to learn and remember
- An appropriate follow-up to the previous SQL Room on TryHackMe
- Understanding databases/tables/records
- How authentication/authorization can still matter even if SQLi exists
- How SQLMap identifies injectable parameters.

---

## In the Rearview

- Obtained my Network+ Certification (January of 2026)
- Building a functional home lab, including Kali, Windows 11VM, and Windows Server

---

## What’s Next

- Continue learning the basics from TryHackMe. Defensive Intro is next. Really excited for this one!
- Continue working in my home lab
- Continue intermittent study of Security+ concepts

This blog exists to make my growth visible to future employers, myself, and those interested in following along with my journey.

If you’re reviewing this as a hiring manager, thanks for popping in. What you’ll see here is not just study notes, but applied reasoning and documented progress.
