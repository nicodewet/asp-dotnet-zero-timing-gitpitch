# ASP.NET Zero

The Right Framework At The Right Time

Nico de Wet

![Thorgil](http://www.thorgil.com/thorgil.png)

---

## Software Delivery Quicksand

> 1. Loose wet sand that yields easily to pressure and sucks in anything resting on or falling into it.
> 2. A bad or dangerous situation from which it is hard to escape.

---

## Quicksand and ASP.NET Zero

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

- Team remains in [storming phase](https://en.wikipedia.org/wiki/Tuckman%27s_stages_of_group_development)
- Low trust

Note:
Remember to mention Bruce Tuckman as professor of psychology who first proposed
the forming-storming-norming-performing model of group development.

--- 

## Some Hypothetical Causes

- [Probably many](https://svpg.com/top-10-reasons-for-slow-velocity/)
- We'll focus on subset of software engineering concerns

---

## Engineering Advisor Concern: Incompetence

- MCSEs instead of CS degrees during [dot-com bubble (~ 1997 - 2001)](https://en.wikipedia.org/wiki/Dot-com_bubble).
- At the end of 2010s beware of cloud certifications and "certified cloud consultants". Cloud bubble.
- Many IT advisors, including architects, still out there from Dot-com bubble days that didn't even bother with MCSE.

Note:

Worth noting to the audience that I did recently do the AWS Solutions Architect certification, but it not
all I've got by any means.

Worth noting the effect on team morale in cases where sponsors choose to use the advise of incompetent,
unqualified, inexperienced IT consultants, of which there are many.

---

## Engineering Industry Concern

- No regulation or controls whatsoever
- No practitioner licensing (e.g. doctors, nurses, civil engineers)
- No engineering code compliance or mandatory inspections
- Public generally has no recourse

> A cottage industry.

Dr. Paul Chapman

Note:

HTML programming scam on my mother. Countless projects started with
no hope of finishing or succeeding, but sponsors parted with funds.

---

## Engineering Team Concern: Culture

- "Startup" culture problems
- Maturity and pedigree (A players won't play with Z players)

Note:
Remember to mention that in terms of maturity it is important that employees
understand the levers that drive the business given the stage it is in. Being
financially savvy and business savvy is important. It's important for leaders
to clearly communicate what behaviours will drive success.

Also remember to mention that efficiency matters in a startup and that some
individuals may expect "startup" behaviour such as arriving late to meetings
and playing foosball where as this won't work for others or generally 
causing friction.

Remember to mention that we can change the culture. Not overnight, but in time.

---

## Lean Enterprise Fundamentals

- Lean Enterprise: How High Performance Organizations Innovate At Scale

> There are no awards for elegance of software design or automated test coverage
> in an MVP - the more skeletal, the better, provided we can gather the
> information we need.

---

## Lean Enterprise Caveat

- Waterfall works when perfecting a proven idea or well understood domain
- Re-use existing software to move fast

Note:

Using the word perfecting in the sense that if you come second you are not copying.
Its easier since you can observe the incumbent and enhance a business model with
software.

Could mention the ISP domain in with open source software such as freeradius and
dd-wrt.

---

## Hotel Booking Example

- Most profitable production prototype I've written.
- Adapted 2007 [JBoss Seam Hotel Booking example](https://access.redhat.com/documentation/en-US/JBoss_Enterprise_Web_Platform/5/html/Seam_Reference_Guide/booking.html).

---

## Engineering Team Concern: Adaptability

- Some engineers are good for a [v1 (prototype) build](https://queue.acm.org/detail.cfm?id=2841311).
- Some engineers are good for a v2 build.
- Some can adapt to both, some can't.
- Some environments cannot support a v1/v2 development process.  

Note:

Remember to refer to the referenced article as "Lean Software Development- Building and Shipping Two Versions" by
Kate Matsudaira in which she talks about catering to developer's strengths while still meeting team objectives.
The process is called the v1/v2 development process.

Remember to mention that some engineers may not be able to ever accept working on v1 with its associated style
even though that is what is required in a given situation. Clearly this will be a problem when trying to get
a prototype (v1) out because you may never get it out (risk of overengineering and so on).

Mention that the contract of the v1/v2 development process cannot be broken. If engineers feel they may be
forced to break the contract they should not follow a v1/v2 development process.

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
- *Can* press reset button (or **stop**)
- *Can* move to the [norming-performing](https://en.wikipedia.org/wiki/Tuckman%27s_stages_of_group_development) stages

Note:

The stop option in some cases comes down to ethics and professional conduct
i.e. ethically and professionally correct to recommend. See the
[ACM Code of Ethics and Professional Conduct](https://www.acm.org/about-acm/acm-code-of-ethics-and-professional-conduct).
Ultimately this option should be discussed with sponsors.

---

## Kathy Sierra

- [Making Badass Developers](https://youtu.be/FKTxC9pl-WM).
- Going from A to C.
- The effect of high quality teaching (and code).
- [Core Spring Training](https://pivotal.io/training/courses/core-spring-training).

---

## Robert C. Martin

- [Expecting Professionalism](https://youtu.be/BSaAMQVq01E) 
- Clean, framework free code.
- **"We will not ship shit."**
- No going back from green light development.

Note:

Encourage audience to look at the notes summary of [Expecting Professionalism](https://youtu.be/BSaAMQVq01E):

Expecting Professionalism - Robert C. Martin
1. We Will Not Ship Shit
2. We Will Always Be Ready (deployable after each dev't cycle)
3. Stable Productivity (same speed a year ahead / not slowed by bad code)
4. Inexpensive Adaptability (easy to change the code/software)
5. Continuous Improvement (of code, design, system over time)
6. Fearless Competence (use test-driven development)
7. Extreme Quality (why do we need a bug-tracking system?)
8. We Will Not Dump On QA (they should find no defects; it should be front-end test-design and trying to break the system)
9. Nothing Fragile
10. We Cover For Each Other (ensure someone on your team can cover for you)
11. Honest Estimates (give expected time and window of best/worst cases)
12. You Were Hired to Say "No" (To Unrealistic Deadlines)
13. Continuous Aggressive Learning (surf the wave of software popularity; 10-15h/wk extra)
14. Mentoring (# of programmers doubles every 5yrs = 1/2 group has under 5yrs exp. = perpetual inexperience)

Might be worth mentioning the [ACM Code of Ethics and Professional Conduct](https://www.acm.org/about-acm/acm-code-of-ethics-and-professional-conduct) does exist.

---

## Engineering Team Concern: Pragmatic Programmers

- [The Pragmatic Programmer: From Journeyman to Master, 1999](https://www.amazon.com/Pragmatic-Programmer-Journeyman-Master/dp/020161622X)
- "Tip 1: Care About Your Craft"
- "Tip 5: Be a Catalyst for Change"
- "Tip 8: Invest Regularly in Your Knowledge Portfolio"
- Languages to Learn ...

Note:

Here I want to mention that pragmatic programmers would be required when
say changing an entire stack. Trust and buy-in required.

--- 

## Ward Cunningham: Debt Metaphor Misunderstanding

- Poorly written code is **not** technical debt.
- Poorly written infrastructure-as-code (serverless architecturing) is also **not** technical debt.

> I'm never in favour of writing code poorly but I am in favour of writing code that reflects your current
> understanding of a problem even if that understanding is partial. The ability to pay back debt and make
> the debt metaphor work for your advantage depends upon on you writing code that is clean enough to be able
> to refactor as you come to understand your problem.

[Ward Cunningham, 14 Feb 2009](https://youtu.be/pqeJFYwnkjE)

Note:

"Repay that loan by refactoring the program to reflect your experience as you acquired it. Bloggers have explained the metaphor
and confused it with the idea that you could write code poorly with the intention of doing a good job later and thinking that
that is the primary source of debt."

Introduce [Ward Cunningham](https://en.wikipedia.org/wiki/Ward_Cunningham).

---

## Reset Decision

- Reset means start construction from scratch
- May entail architectural changes and likely to entail voluntary team changes
- Pragmatic programmers may be required
- No team *wants* to fail, elevated professionalism and sometimes saying "no" paramount

Note:

Remind the audience to watch Robert C. Martin's talk and follow the [Expecting Professionalism](https://youtu.be/BSaAMQVq01E) rules.

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

Note:

Worth mentioning pragmatic programmer requirement again here. Engineers will go from
Javascript to C# as main language.

---

## Monolith

- Better to have a successful monolith than a failed nanoservices architecture
- Splitting up a **well built** monolith a good problem to have
- Never forget conways law & value to the end user

---

## Monolith First

> It may be hard to scale a poorly designed but successful software system,
> but that's still a better place to be than its inverse.

[Martin Fowler](https://martinfowler.com/bliki/MonolithFirst.html).

---

## Key Framework SDLC Benefits

- UI *constrained* by existing patterns
- SPA complexity deferred
- SOFEA (service oriented front end architecture)
- Developers can focus on service layers & use a debugger

Note: Worth noting that UI constraints could help mitigate the effects of a
broken SDLC such as a cargo cult engineering process.

---

## CD Pipeline Notes

- Relatively speaking, simple, however ...
- "AWS certified" still required
- [reference blog](https://aws.amazon.com/blogs/compute/set-up-a-continuous-delivery-pipeline-for-containers-using-aws-codepipeline-and-amazon-ecs/)
- [reference tut](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-cd-pipeline.html)

Note:

On the "AWS certified" front. Not every team member will become "AWS certified" and so
will break the "13. Continuous Aggressive Learning" rule
from [Expecting Professionalism](https://youtu.be/BSaAMQVq01E).

---

## AWS ECS CD Reference Architecture

![AWS ECS CD Reference Architecture](images/aws_ecs_reference_cd_architecture.png)

--- 

## AWS CodeBuild (buildspec.yml)

---

## ASP.NET Zero Features

- Multi-tenancy
- Organization Units, Roles, Users, Languages
- Internationalization
- RAD tooling
- **Lots of quality sample code and tests**

---

## JHipster Features

- Awareness, as pragmatic programmers

---

## ASP.NET Zero Core MVC and jQuery

---

## Backlog Bits

- Many to Many with EF Core 2
- Speed up build and test run
- Visual Studio for Mac
- Broke the "We Cover For Each Other" rule when building pipeline

Note:

Remind audience that the rule comes from [Expecting Professionalism](https://youtu.be/BSaAMQVq01E).

---