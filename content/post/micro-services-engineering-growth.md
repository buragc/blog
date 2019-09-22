+++
title = "Micro Services for engineering growth"
description = "A positive side effect of working with micro-services"
showcomments = true
date="2017-06-15"
tags = ["engineering", "services"]
+++

# Organizational impact of micro-service architecture

Using micro-services in your engineering organization is where the hype has been at for the past few years. As others like [Martin Fowler have pointed out](https://martinfowler.com/bliki/MicroservicePrerequisites.html) , building a micro-services architecture based on the hype is probably a bad idea as a true micro-services architecture comes with a whole set of new challenges that probably is not worth it for a good chunk of use cases.

Since the technical comparison of monoliths and micro services has been done several times ([here](https://medium.freecodecamp.org/rest-in-peace-to-microservices-or-not-6d097b6c8279) and  [here](https://stackoverflow.com/questions/33041733/microservices-vs-monolithic-architecture)) I will not go into whether or not you should pick a micro services architecture. Instead, I want to focus on what happens to your engineering team communication, responsibilities and overall impact on your engineering organization if you were to pick a micro-services architecture.

## Team driven vs. standardized architecture

One of the big decisions an engineering organization makes as they go micro services route is to decide whether or not all micro-services will look the same or if teams will be given the freedom to use the tools, languages and architecture that makes sense for them. 

I am all for experimenting and picking a good fit for team and the engineering organization based on the makeup of the engineering team. As such, I have preferred giving teams the freedom to choose their own implementation strategy as long as the overall ecosystem adhered to a few key rules that impacted ease of communication between services, log collection/analysis and monitoring. 

## Decentralized decisioning

By giving teams the ability to pick and choose what they think is best for their use case, engineering organizations essentially start pushing technical decisioning from a centralized model to a more distributed one where decisions are made at the edges. 

The first thing that this does is to spark more architectural discussions, debates and designs within your team. This creates an opportunity (and a good challenge) for engineers to start communicating their ideas to other engineers more effectively and helps them develop their verbal and written communication skils.

## Making experience years count

If you end up with teams that are autonomous in their design and architecture decisions your engineers will probably end up making some unproven assumptions but as long as these are incremental, small micro-services that are released to production in a controlled way as part of A/B tests, your engineers will quickly start getting feedback in the form of hard-data points about their assumptions, architectural decisions and implementation choices. 

Compared to a monolithic architecture where junior engineers are expected to incrementally introduce new functionality by replicating existing behaviors, micro-services give them the ability to quickly learn based on real-world feedback. 

As a result, the experience your engineers start gaining actually will mean something because they are constantly learning new things and forming their views on good engineering based on real world evidence rather than executing a cookie cutter approach over and over for years.

![Experience](http://memeguy.com/photos/images/applying-to-entry-level-jobs-that-require-years-experience-62749.jpg "Experience")

## It's not all rainbows and unicorns
All this sounds great and at this point you may be wondering why would any organization not choose to go with micro-services if it has all these positive impacts on engineers. 

The answer is in the numbers; as your organization scales the number of services from a handful to a few dozen, discovery, documentation, deprecation, tracing and overall coordination among teams require the creation of a well oiled machine. 

Setting up the necessary systems, processes and encouraging the desired positive team behavior is no small feat. As such, a concious effort needs to be made to understand the needs of teams, find solutions that work internally and then learn from these experiments to improve. 

I would even argue that **if you cannot afford to dedicate the time/engineering management capacity to restructure your organization, create efficient communication paths and introduce systematic improvements you probably should not roll out a micro-services architecture**. Simply because, if not tended to, it would be dice roll to expect to reap the benefits I highlighted above.