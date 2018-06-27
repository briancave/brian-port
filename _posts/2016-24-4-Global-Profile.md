---
layout: post
title:  "A Need for a Global Profile"
date:   2016-04-23 12:00:22
---

***Summary:*** Comprehensive usability testing was conducted on MyAccount to evaluate the website before and after the redesign. This would be used to identify usability issues and validate that the UX team met or exceeded our goals for the new design. 

MyAccount is the website that Santander customers use to make payments on their loan, view statements, and adjust their profile information.

Although I saw a significant improvement in usability over the original design some fundamental usability issues remained specifically surrounding how users expected to update their account information or change communication preferences.

Methods
-------

I decided to break usability testing into three main areas for evaluation based on the secondary research and qualitative research collected in the discovery phase: 

+ **Authentication:** *sign up, log in, reset password and recover username*
+ **User Profile:** *change account information and communication preferences*
+ **Payments:**  *submit payments or set up auto draft payments*

I did a evaluation test for each section to establish a baseline, and then an exploratory test for each section once mockups were completed. After the design was further refined and built in a test environment, I performed a comprehensive test that took specific tasks from each section. 

During each session, I would invite designers, developers and stakeholders be present in an observation room to strengthen empathy and to help document any usability issues that were identified. Findings were consolidated into a report and presented with my recommendations.


Results
-------

Here are the goals identified in the test plan document:

>To assess the overall usability of the redesign by:
>
>1. Having users try to complete tasks common to MyAccount users.
>2. Capture Single Ease Question (SEQ) and System Usability Scale Questionnaire (SUS) data.
>3. Compare results to baseline testing to measure impact of the new design.

The comprehensive test revealed that the new design was a drastic improvement over the original design. There were however two tasks indicated a decrease in usability. Test participants were asked to update their mailing address after logging into their account (T3) and update their communication preferences by turning on SMS notifications (T4). 

As you can see in the baseline comparison, these two tasks logged a longer time on task, and increased number of clicks. 

<br>
![baseline comparison table](/images/baseline_comparison.jpg)
<br>

Looking at the task completion chart  we get a better sense of the overall impact.

<br>
![Task completion bar chart](/images/task_completion.jpg)
<br>


Conclusion
----------

I found that the majority of the test participants look for account settings and preferences in the top navigation. The current organization places both the customer address and communication preferences under a link titled “Account Contacts.” If a user has more than one auto loan, they would see a different “Account Contacts” link for every loan in their profile, thus allowing user to potentially have different information saved for their different loans. This organization is unexpected and confused most users. The verbiage of “Account Contacts” is also misleading. 

<img src="/images/account_profile.jpg" alt="account profile" class="imgcenter">

I recommended to:

1. Revise information architecture by separating loan information and profile information to reduce confusion
2. Move account profile and preferences to the top navigation to become a global profile and settings.
3. Revise language to help users distinguish difference between vehicle/loan specific information and global profile and settings. 

I designed an alternative conceptual flow based on the collected feedback.

<br>
![conceptual user flow](/images/user_flow.jpg)
<br>

If a customer had multiple accounts (or loans) they should see a snapshot view. If they only have one account, they see the Account view only. You will notice that loan specific information is organized under Vehicle info, and the profile and preferences is pulled out into the global navigation. 
