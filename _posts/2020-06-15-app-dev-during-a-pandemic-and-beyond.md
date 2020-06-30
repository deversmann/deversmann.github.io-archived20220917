---
title: App Dev during a Pandemic and Beyond
categories:
    - observations
tags:
    - it-modernization
    - evolution
    - culture
    - app-dev
    - cloud
---

Let’s set the stage: You’re the manager of an application development team. The size of the team doesn’t really matter, it could be half a dozen or an army. The technologies in your arsenal aren't that important either. Your team could be building Java desktop applications or websites built using more modern technologies like golang or node.js. You could be building applications for other employees at your company, for citizens in your locality or for customers locally or around the world. Suddenly, one day, your entire workforce is ripped from the office to work from home. On top of needing to adjust to new remote working technologies, your employees are dealing with the complexities of homeschooling, social distancing, quarantines, and a whole range of other things that certainly aren't helping productivity. You've begun to fear that the amazing pace at which your team developed is in danger of grinding to a halt. And if that all isn’t bad enough, this situation, this pandemic, this reality, is creating even more complicated work for your team to do.

This is the reality in which many of us find ourselves today. Covid-19 has us dealing with situations that we've never experienced or expected to experience in our lives. Companies and organizations that were staunchly against remote working suddenly have their entire workforce working from home. Applications that were never expected to need to support more than a meager amount of traffic are now seeing 10, 20, 50 times what they were originally designed for. New features and apps are needed now that we never dreamed would exist. What's a development organization to do?

Let's examine a few principles that, when used effectively, can help organizations to deal with situations like today's and many others. In addition, these principles are ones that can help an organization to thrive during normal operations. Some simple steps and ways of doing things can help your development organization succeed and even excel in both good times and bad. 

### Anything-as-a-Service to the Rescue
You’ve heard it all before: Software-as-a-Service, Platform-as-a-Service, Networking-as-a-Service, Storage-as-a-Service, the list goes on and on. But what does that really mean? At its core, it means on demand. My infrastructure can’t support something, but someone else's can. And they’ll sell it to me.  Amazon pioneered this with AWS but today there are myriad choices when it comes to things-as-a-service in technology. What's more, these technologies are well proven, solid and secure. The companies behind these technologies: Amazon, Microsoft, Red Hat, IBM, Google and others, have been doing it for decades now, and it's trusted by companies in the Fortune 500, by the US government and by organizations all over the world. 

In a time like this, these providers are your lifeline to continuing your operations and maintaining scale. Tools exist to enable you to utilize these technologies without needing to affect too much change in your process. The ability to scale out to the cloud is one that is in the grasp of more and more organizations today. 

On top of these always-on data centers, there are modern tools that can help you orchestrate your workloads and scale to support the ever-growing need of your customers. Kubernetes, an open source project originally started by Google, has become the de facto standard orchestrating workloads on-premises and in the cloud. Utilizing Kubernetes, in conjunction with Linux containers, virtually any workload can be maintained, managed and scaled.

That brings us to point number two…

### Cloud Native by Default
Linux containers are one of the key components of modern application development. “But wait”, you say, “Our existing applications aren't developed using containers.” Stay tuned. You're not alone, and you're not left behind. 

A container is simply a way of packaging an application, or part of an application, in a way that makes it portable, and fully self-contained. A container can be distributed amongst many systems without needing a change. In fact, the same container that a developer builds on their local system can make it through testing and QA to user acceptance and eventually to production, without change. It is a technology that is much lighter weight than virtual machines and also much less resource-intensive. It makes better use of the infrastructure hosting it, and it's quicker and easier to scale. 

Due to their scale and light weight, containers are virtually purpose built to support the next technology in our toolkit, microservices.  Microservices are an application architecture pattern where the features and functions of an application are deconstructed down into their smallest constituent parts.  Then these parts are used together to build the application.  Microservices provide many benefits to the application.  First, they enable agile development practices by breaking the application into smaller, more manageable parts.  They also allow the application to scale more efficiently.  By breaking the application into smaller pieces, bottlenecks in the application are compartmentalized into smaller pieces which can be scaled independently of the rest of the application.  Microservices make the application more modular which supports quicker and more efficient feature development.  The largest social applications like Facebook and Twitter use this to roll out new features daily, even hourly.  Finally, microservices encourage reusability between applications as their granularity and generic nature enable them to be used between many different applications.  And this is by no means an exhaustive list of benefits.

Those of you who aren't already using microservices and containers, don’t think I haven't forgotten my promise to you. Containers and microservices are not an all or nothing proposition. Simple modifications to existing monolithic applications can expose Application Programming Interfaces (APIs).  These are programmatic hooks into the application that allow communication with other modules.  APIs are at the heart of microservices and can allow you to start developing new features for your existing application using microservices.  API managers exist to help you maintain your growing catalog of APIs as you migrate to microservices.  Modern architectures do not need to be released with a big bang.  On the contrary, they are practically designed to be implemented piecemeal as necessary or as time and resources allow.

### Security, Don’t Forget Security
During the difficulty and chaos of our current situation, one thing still remains true: Security concerns must not be forgotten. It might be easy to push security to the side when wrapped up in urgent activities, but that tendency must be avoided at all costs.  It’s times like this that lead to mistakes and vulnerabilities that can end up crippling an organization.

The exciting fact is that there are plenty of tools, enabled by containers and microservices architectures, that can make implementing security controls easier and more seamless. APIs and microservices provide connection points for more granular and more thorough security practices.  And if, perish the thought, security vulnerabilities are found, microservices architectures serve to limit the extent of those vulnerabilities and containers provide a mechanism to more quickly remediate them.

### Epilogue
During these chaotic times, it is exceptionally easy to back yourself into a corner and conclude that any significant application development needs to stop.  Don’t give into that tendency. Technologies like Linux containers, tools based on Kubernetes and architectural patterns such as APIs and microservices help to quickly fix existing issues while creating new features in an efficient and secure manner.  It takes little investment, in both effort and finances, to get started.  And it provides a foundation for continued progress toward modernization both during this pandemic and in the future. Don’t allow your app dev teams to freeze up in apprehension.  Use this time to your benefit and start on the path to being a contemporary app dev shop using cutting edge technologies to the benefit of yourselves, your stakeholders and your users.
