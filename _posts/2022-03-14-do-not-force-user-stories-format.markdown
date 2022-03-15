---
layout: post
title:  "Do not force the user story format"
date:   2022-03-03 17:17:01 -0800
categories: post ebuzz
---

_The goal of user stories is not to write better requirements_ 

---
Recently a teammate reached me because he was struggling trying to write a _user story_, he basically had to prioritize a package dependency update for all their team services because the security team found some vulnerabilities, he had the services to be updated and the vulnerabilities identified written in the CoA. He just was not sure of the _user story_ he asked my advice and showed me a couple of drafts, these are the two I remember:

- _AS a customer I WANT my software to be protected against vulnerabilities found in report SO I CAN keep working without security issues._
- _AS customer I WANT the service a,b,c,d to be remedited againts vulnerabilities found in CVE-XXXX_

None of them resonated with him, because the "user" will never ask that, he said. He asked me how I would write them.

I told him I would not even bother writting in the format,the format is supposed to help us drive a conversation, for this case I would simply writte the ask in plan english in the ticket, add the details of the vulnerabilities to be addressed as part of the CoA and when presenting to the team **tell** the team about the ask and importance of doing it, something like this:

>_"Our security team found in a code scanning these vulnerabilities (list of vulnerabilities) in this package which are critical and could put our applications in danger, in the JIRA ticket I have listed the services and vulnerabilities, also attached the report for you to take a look if you have any questions."_

Then, if there are any details that came up from conversation add them to the ticket description. 

"Don't go crazy because of the format man, there is nothing wrong if you don't follow preescribed formats out there" I replied.


# Focus on telling stories, not writting user stories with "correct" formats
The goal of user stories is to have **shared understanding** with your team about a problem that needs to be solved, to initiate a **conversation** you don't need to force a format to do that.

The format is supposed to help you and very useful in some scenarios to  keep stories simple, but if it does not feel right and there is better way to express an problem or ask don't force it. 






