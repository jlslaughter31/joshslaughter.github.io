---
layout: post
title: "Incident Response & Log Fundamentals"
---

Over the past several months, I’ve been intentionally building a foundation in cybersecurity with the long-term goal of becoming an ethical hacker and security professional. This site documents that journey, as I thought it would be helpful to show not just what I’m learning, but how I’m thinking through problems and developing practical skill. This post documents my time on TryHackMe's "Incident Response" and "Log Fundamentals" rooms. Welcome in!

---

## Incident Response/Logs Fundamentals

The next step on the roadmap in my cybersecurity journey is learning about Incident Response and Log Fundamentals. I've been working my way through the rooms on TryHackMe. I'm keeping details high-level to avoid spoilers for the millions of people that will for sure read this, and also to stay within platform guidelines.

I'm currently in the Defensive Security section (Cyber Security 101 > Defensive Security) and it's been fun so far! It's been mostly introduction, but it's still cool to kind of see things at work.

The Incident Response room basically covered "What do defenders do when they are attacked?" It started by distinguishing alerts (true vs false positives) from confirmed incidents, then continued with different types of incidents, followed by covering SANS and NIST. We discussed playbooks vs runbooks, and different tools at the defender's disposal to recover.

The Logs Fundamentals room covered the purpose and use of logs, and taught us how to analyze them well. We took a short tour through the Windows Event Viewer and saw the different categories of logs (Security, System, Application, etc) and learned how to filter for what we were looking for.

---

## My Takeaways

1. Incident Response ties in well with the 3 Pillars of Defense. The right people, carrying out the right process, with the right technology is necessary for mitigating damage once an attacker has gained a foothold.
2. Validate alerts quickly before escalating, so you reduce false positives without missing real incidents.
3. Logs are expansive and learning to review them well can be the difference in identifying points of failure and successful aplication of SANS/NIST.

---

## What I'd check first in a real investigation:

1. Time window (when did it start?)
2. Who has been affected?
3. Authentication Activity
4. Network Connections made (unusual destinations or ports)


---

## Defender Insights

- Learn to use logs well and reap the benefits: become a better defender, learn to think like an attacker, and recover well from incidents.
- Logs are evidence and without them we're all guessing
- Filtering logs to weed out the noise is extremely beneficial, probably moreso in larger environments
- Processes (SANS, NIST) matter
- Documentation matters (What did you learn?)

---

## In the Rearview

- Obtained my Network+ Certification (January of 2026)
- Building a functional home lab, including Kali, Windows 11VM, and Windows Server

---

## What’s Next

- Continue learning the basics from TryHackMe.
- Continue working in my home lab
- Continue building towards the Security+

This blog exists to make my growth visible to future employers, myself, and those interested in following along with my journey.

If you’re reviewing this as a hiring manager, thanks for popping in. What you’ll see here is not just study notes, but applied reasoning and documented progress.
