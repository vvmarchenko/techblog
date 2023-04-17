---
title: "What is DevOps?"
date: 2023-03-25T13:25:17+02:00
summary: What is DevOps and what's it all about?
description: What is DevOps and what's it all about?
cover:
    image: /postsimg/whatisdevops.png
    relative: true
    alt: What is DevOps and what's it all about?
draft: false
author: "Vladyslav Marchenko"
---

## Introduction

### Hello everyone!👋 I'm pleased to have your attention!

Every day, as I delve deeper into the DevOps methodology, I see more and more discrepancies and misunderstandings about what DevOps is and why it is needed.\
In this article, I will try to share the information that I have learned and found about this issue, and I hope it will be helpful to you.\
So let's get started!🚀

## History of DevOps

### To answer the question "What is DevOps?", let's first understand where this methodology came from:

The DevOps methodology started to coalesce sometime between 2007 and 2008, when IT operations and software development communities raised concerns what they felt was a fatal level of dysfunction in the industry.

They railed against the traditional software development model, which called for those who write code to be organizationally and functionally apart from those who deploy and support that code.

At this very moment, by fortunate circumstances, [Patrick Debois](https://twitter.com/patrickdebois?lang=en) appears.
{{< figure src="/postsimg/patrick.jpeg" >}}

Patrick Debois first suggested the DevOps philosophy in 2007. When consulting as a project manager for the Belgian government ministry's task of data center migrations. Patrick was visibly frustrated with the "walls of separation" and lack of collaboration between the application development teams and infrastructure teams.

In 2008, Patrick learned about the **"Agile Infrastructure"** session hosted by **Andrew Schafer** at the Agile Conference in Toronto. Unfortunately, given the negative predilection around the topic, Patrick was the only one at the session. Nevertheless, they both shared their ideas and seemed to hit it off instantly. They then discussed "Agile Systems Administration" on an online forum. The idea was met with lackluster interest.

In an unrelated turn of events, this idea resurfaced at the 2009 O'Reilly Velocity Conference when two Flickr employees - **John Allspaw** and **Paul Hammond**, gave the fabulous presentation titled, ["10+ Deploys per Day: Dev and Ops Cooperation at Flickr."](https://www.youtube.com/watch?v=LdOe18KhtT4) Allspaw and Hammond role-played conversations between members of development and operations teams during a standard software deployment cycle. In addition, they offered dramatic representation to the finger-pointing that goes along, including "It's not my code, it's your machines!"

While Patrick Debois wasn't at the presentation, he watched the recording. And given the sudden buzz on social media went on to coin the term "DevOps" in the year 2009.

## So what is DevOps?

At its core, **DevOps** is a culture that emphasizes the need for collaboration and communication between software development teams and IT operations.\
The primary goal of DevOps is to enable organizations to deliver software products and services quickly, reliably, and at scale. It involves a combination of tools, practices, and cultural changes to achieve this goal.

{{< figure src="/postsimg/dev-ops-qa.png" >}}

### The goals of DevOps:
- Fast Development Methodologies
- Fast Quality Assurance Methodologies
- Fast Deployment Methodologies
- Faster time to market
- Iteration & Continuous Feedback (strong
and continuous communication between
stakeholders — the end users and
customers, product owners,
development, quality assurance, and
production engineers)

### The benefits of DevOps:
- **Environment Stabilization** (enforces consistency, increase up-time)
- **Shorter Development Cycle** (manage requirements and code-repository)
- **Increased Release Velocity** (continuous build, push-button deployments)
- **Reduced Defects** (regiment processes, automated testing)
- **Process Metrics** (track both time at each stage, and the errors and exceptions)



**Also, I cannot overlook one of the most important practices in DevOps, which is Continuous Integration and Continuous Delivery (CI/CD).**

### Continuous integration and continuous delivery (CI/CD)
{{< figure src="/postsimg/ci-cd.png" >}}

**Continuous Integration (CI)** is the practice used by development teams to automate, merge, and test code. CI helps to catch bugs early in the development cycle, which makes them less expensive to fix. Automated tests execute as part of the CI process to ensure quality. CI systems produce artifacts and feed them to release processes to drive frequent deployments.

**Continuous Delivery (CD)** is a process by which code is built, tested, and deployed to one or more test and production environments. Deploying and testing in multiple environments increases quality. CD systems produce deployable artifacts, including infrastructure and apps. Automated release processes consume these artifacts to release new versions and fixes to existing systems. Systems that monitor and send alerts run continually to drive visibility into the entire CD process.

**Based on the above, I can identify the main steps in DevOps:**

### The Steps of DevOps:
{{< figure src="/postsimg/steps-devops.png" >}}

- **Plan**: task management, schedules
- **Code**: code development and code review, source code management
- **Build**: continuous integration tools, version control tools, build status
- **Test**: continuous testing tools that provide feedback on business risks,
determine performance
- **Package**: artifact repository, application pre-deployment staging
- **Release**: change management, release approvals, release automation
- **Operate**: infrastructure installation, infrastructure changes
(scalability), infrastructure configuration and management,
infrastructure as code tools, capacity planning, capacity & resource
management, security check, service deployment, high availability
(HA), data recovery, log/backup management, database management
- **Monitor**: service performance monitoring, log monitoring, end user
experience, incident management

### What DevOps is NOT
{{< figure src="/postsimg/no.jpg" >}}

**DevOps is NOT a tool:**\
Understandably, this misconception arises from the fact that several tools are used in the DevOps practice. By itself, DevOps is not a tool or even a set of tools. While DevOps does rely heavily on tools to automate the process, it is much more than just that.

**DevOps is NOT a team:**\
Another common misconception while just beginning the DevOps transformation is creating a new team called the DevOps team. A different team is contrary to the principles of DevOps, which intend for the Dev and Ops teams to work more closely with each other. Setting up a new DevOps team is just going to create more silos rather than dissolve them.

**DevOps is NOT a role:**\
Related to the previous point and a rather rampant one, DevOps is technically not an individual role. Saying "DevOps Engineer '' is not justified unless the role single-handedly manages everything technical happening in the organization (an unimaginable thought).

**DevOps is NOT a standardized strategy:**\
Given that there are numerous ways to implement DevOps and an equal number of varied outcomes, a one-size-fits-all approach may not be the best way to address DevOps. Instead, various aspects, including requirements, business objectives, tech stack, and tools, need to be considered while developing a DevOps strategy for the organization.

## Conclusion

***DevOps - Is a culture (methodology) that encompasses many aspects, solutions, and standards, and I believe that it will continue to evolve over the years, possibly changing and restructuring, but I believe that DevOps will remain relevant for many years to come.***

I hope you found this article informative and that I was able to provide some clarity on this topic. There is still much that could be said and explored about DevOps, but I have tried to focus on the main aspects that will spark your interest to further investigate this fascinating world of DevOps.

I leave you with references to the sources where I obtained information and drew ideas from to create this article:
- ***[Learn.Chef.Introduction-to-DevOps](https://learn.chef.io/courses/course-v1:chef+DevOpsTransformation+Perpetual/course/)***
- ***[Atlassian.com.History-of-DevOps](https://www.atlassian.com/devops/what-is-devops/history-of-devops)***
- ***[Gitlab.com.What-is-DevOps](https://about.gitlab.com/topics/devops/)***
- ***[Microsoft.com.What-is-DevOps](https://learn.microsoft.com/en-us/devops/what-is-devops)***


**Thank you for reading, and I wish you success and good luck!** 😌







