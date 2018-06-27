---
layout: post
title:  "MyAccount Redesign"
date:   2017-09-19 07:00:22
---

***Summary:*** MyAccount is the website that Santander customers use to make payments on their loan, view statements, and adjust their profile information. In preparation for a major redesign of the website, I was brought in to conduct qualitative research to better understand why some customers were not able to access their account.

Through my research, we were able to identify a major technical issue with the password/username reset process resulting in a potential **$1.6 million/annual cost savings.**

Methods
-------
The company receives most customer feedback through call centers. I conducted contextual inquiries with customer service agents to establish a frequency of customer issues relating to account access. I created a customer journey map for account access calls capturing time on task data to find an average amount of time spent trying to resolve password reset or username recovery issues.

<br>
![customer service representative journey map](/images/CSR_JourneyMap.jpg)
<br>

Like most websites, recovering a username or resetting a password is a task users should be able to complete without needing to make a phone call to customer service. I performed a heuristic evaluation of the current account recovery process to begin forming my hypothesis. I used secondary research sources such as web tracking, server logs, and interactive voice response (IVR) data to validate my hypotheses of root causes. I also did a SUS survey evaluation of the tool customer service agents use to assist customers in resetting their password or recovering their username.

Results
-------

I discovered that agents spent on average **6-18 minutes** to resolve an account access issues. Customers were spending on average **17-28 minutes** on the phone factoring in hold times. Using an average salary and total number of active agents, I calculated that our company was spending approximately **$1.6 million annually** to resolve account access issues that should be mostly preventable. 

One of the most significant findings came from digging into technical server log data. I discovered that if a user keyed in an incorrect response to a security question, they would see the same message as if they had entered a correct response. Without accurate system feedback, many users were expecting to receiving a link to get access to their account that would never come. This forced customers to call Santander to find a resolution.

<br>
<img src="/images/email_sent.jpg" alt="email sent message" class="imgcenter">
<br>

Conclusion
----------

All of the findings were consolidated into a report and presented to a group of stakeholders.  One of the biggest challenges that I faced with this project was calculating an accurate figure of potential annual loss. As a small and nimble UX team inside a big corporation, its critical that we use every opportunity that we have in front of stakeholders to evangelize the user experience practice and our value to the company. With the final presentation of findings, I felt that the best way to relate to the decision makers in the room was to try to speak their language. **I highlighted the major issues with the design, but through the lense of potential for cost savings.** The report contained my recommendations for addressing the design problems and outlined next steps.