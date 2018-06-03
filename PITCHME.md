# ASP.NET Zero

The Right Framework At The Right Time

Nico de Wet

![Thorgil](http://www.thorgil.com/thorgil.png)

---

## Software Delivery Quicksand

> 1. Loose wet sand that yields easily to pressure and sucks in anything resting on or falling into it.
> 2. A bad or dangerous situation from which it is hard to escape.

---

## The Metaphor and ASP.NET Zero

- Useful metaphor
- ASP.NET Zero *may* help in some situations

---

## The Art of Manliness

- [How to Escape Quicksand: An Illustrated Guide](https://www.artofmanliness.com/articles/how-to-escape-quicksand-an-illustrated-guide/)
- Step 1 is knowing you are in it

---

## W. Edwards Deming

> Doing your best is not enough, you have to know what to do, then
> do your best

---

## Hypothetical Scenario

- Greenfield product scenario
- Either large enterprise or startup
- Need to prove innovative product in market and make money

---

## Hypothetical Scenario

- Two pizza (i.e. colocated) team
- [Some form of agile SDLC](https://youtu.be/l1wKO3rID9g)

--- 

## Quicksand Symptoms

- Low velocity, far too long from concept to delivery
- Pivoting makes velocity worse, hard to do
- Team rotation

--- 

## Quicksand Symptoms

- Team remains in storming phase
- Low trust

--- 

## Some Hypothetical Causes

- [Probably many](https://svpg.com/top-10-reasons-for-slow-velocity/)
- We'll focus on subset of software engineering concerns

---

## Engineering Team Concern: Type of Experience

- Too much established business engineering experience
- Don't write hundreds of SPA unit tests

---

## Lean Enterprise Fundamentals

- Lean Enterprise: How High Performance Organizations Innovate At Scale

> There are no awards for elegance of software design or automated test coverage
> in an MVP - the more skeletal, the better, provided we can gather the
> information we need.

---

## Lean Enterprise Caveat

- Waterfall works when copying a proven idea
- Re-use existing software to move fast

---

## Hotel Booking Example

- Most profitable production prototype I've written.
- Adapted 2007 [JBoss Seam Hotel Booking example](https://access.redhat.com/documentation/en-US/JBoss_Enterprise_Web_Platform/5/html/Seam_Reference_Guide/booking.html).
- Never mastered entire stack.

---

## Engineering Team Concern: Adaptability

- Some engineers are good for a [v1 (prototype) build](https://queue.acm.org/detail.cfm?id=2841311)
- Some engineers are good for a v2 build
- Some can adapt to both, some can't

---

## Engineering Team Concern: Rotation

- Cannot predict rotation at start

---

## Engineering Team Concern: Rotation

- Can react to rotation
- Can control *cognitive load* on team
- Can control *cognitive load* on maintainers

---

## Engineering Team Concern: Rotation

- *Can* control scope
- *Can* press reset button
- *Can* move to the norming-performing stages

---

## Kathy Sierra

- [Making Badass Developers](https://youtu.be/FKTxC9pl-WM)
- Going from A to C
- The effect of high quality teaching
- [Core Spring Training](https://pivotal.io/training/courses/core-spring-training)

---

## Robert C. Martin

- [Expecting Professionalism](https://youtu.be/NsNC47mdi4E) 
- Clean, framework free code.
- **"We will not ship shit."**
- No going back from green light development.

---

## Engineering Team Concern: Pragmatic Programmers

- [The Pragmatic Programmer: From Journeyman to Master, 1999](https://www.amazon.com/Pragmatic-Programmer-Journeyman-Master/dp/020161622X)
- "Tip 1: Care About Your Craft"
- "Tip 5: Be a Catalyst for Change"
- "Tip 8: Invest Regularly in Your Knowledge Portfolio"
- Languages to Learn ...

---

## Hypothetical Stack Before Reset

- Serverless Architectures on AWS
- Lambdas, API Gateway, AWS SDKs
- Node.js, Javascript, Typescript
- SPA (React, Redux, Thunks, Custom CSS)
- Serverless Framework

---

## Architecture Stack After Reset

- [ASP.NET Zero](https://aspnetzero.com/)
- ASP.NET Core MVC and jQuery
- Two docker containers (highly portable, limited lock-in)
- [Simple pure AWS CD pipeline](https://github.com/awslabs/ecs-refarch-continuous-deployment)

---

## Key Framework SDLC Benefits

- UI *constrained* by existing patterns
- SPA complexity deferred
- SOFEA (service oriented front end architecture)
- Developers can focus on service layers

---

## CD Pipeline Notes

- Relatively speaking, simple, however ...
- "AWS certified" still required
- [blog](https://aws.amazon.com/blogs/compute/set-up-a-continuous-delivery-pipeline-for-containers-using-aws-codepipeline-and-amazon-ecs/)
- [tut](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-cd-pipeline.html)

--- 

## AWS CodeBuild (buildspec.yml)

---

## ASP.NET Zero Core MVC and jQuery

---