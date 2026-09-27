---
date: "2026-09-27T09:00:00+01:00"
draft: false
summary: A practical 12-step framework for turning ambiguous business
  requests into clearly scoped data analytics projects.
tags:
- project scoping
- business understanding
title: Can We Scope Ambiguous Business Requests?
---

Most analytics and machine learning projects start with a problem. But
in my experience working as a data analyst and data scientist, the
problem we are given is rarely as clear as we would like.

Over the course of my career, I've found that some of the best analysts
and data scientists aren't necessarily the people who jump into the data
fastest. They're the people who are good at **scoping the problem
first**.

I've experimented with several approaches to doing this, including
frameworks such as CoNVO and the 4Ws. They gave me useful starting
points, but I often found gaps. I would begin a project only to realise
that an important question hadn't been answered, which meant going back
to stakeholders for clarification.

There's nothing inherently wrong with that. Scope changes, new
information emerges, and revisiting stakeholders is a normal part of an
analytics project. But I wanted a more systematic way of thinking
through a request upfront---one that would help me uncover more of the
unknowns before getting deep into the analysis.

Over time, I arrived at a **12-step framework for scoping analytics
projects**. I've also turned it into a template that I use to structure
projects before beginning the analysis.

I use a separate framework for machine learning projects, which I'll
share another time. For now, this one is specifically designed for
analytics.

## My 12-Step Analytics Scoping Framework

### 1. Define the problem

Start with the business problem---not the data.

What is actually happening? What prompted the request? Why does the
business believe analysis is needed?

The goal here is to turn an ambiguous request such as *"Can you analyse
why sales are down?"* into a clearly defined problem that everyone
agrees on.

### 2. Identify the objective

Once the problem is understood, define what the analysis is expected to
achieve.

What should we know at the end that we don't know now? More importantly,
**what decision will this analysis help someone make?**

This distinction matters. An interesting analysis isn't necessarily a
useful analysis.

### 3. Identify the stakeholders

Who requested the analysis? Who will use the results? Who owns the
relevant business process? And who has the context or knowledge needed
to interpret the data correctly?

The person requesting an analysis isn't always the person making the
final decision.

Understanding the wider group of stakeholders can also help uncover
different expectations before the project begins.

### 4. Define the key questions

Break the broader business problem into specific questions that can
actually be answered with data.

For example, *"Why are sales falling?"* could become:

-   When did the decline begin?
-   Is it concentrated in particular products, regions or customer
    segments?
-   Is the decline driven by fewer customers, fewer purchases or lower
    order values?
-   Are there seasonal or historical patterns that could explain the
    change?

These questions begin to create the bridge between the business problem
and the analysis.

### 5. Determine the data requirements

Now ask what information is required to answer those questions.

This includes the variables needed, level of granularity, relevant time
period, data sources and any additional dimensions required for
comparison.

The important distinction is that the **questions should determine the
data requirements**, rather than allowing whatever data happens to be
available to determine the questions.

### 6. Assess data availability and quality

Required data and available data aren't always the same thing.

Does the data actually exist? Can you access it? Is the required history
available? Are important fields missing? Are definitions consistent
across systems?

Discovering these limitations early can completely change the scope of a
project.

It may also reveal that some of the original questions cannot be
answered reliably with the data currently available. That's something
worth knowing before the analysis begins.

### 7. Define the scope and boundaries

Explicitly state what the analysis will---and will not---cover.

This might include particular dates, markets, products, customer groups,
business units or channels.

Clear boundaries help prevent a seemingly straightforward analysis from
quietly expanding into several different projects.

They also create a shared understanding between the analyst and
stakeholders about what should be expected from the work.

### 8. Choose the analytical approach

Only after understanding the problem, questions and available data
should you decide how to analyse it.

Depending on the problem, this might involve descriptive analysis,
segmentation, trend analysis, statistical testing, forecasting or
modelling.

The technique should follow the question---not the other way around.

Starting with a preferred technique and then searching for somewhere to
use it can easily lead to analysis that is technically interesting but
doesn't address the original business problem.

### 9. Define success criteria

What does a successful analysis look like?

Success shouldn't simply mean *"the dashboard was delivered"* or *"the
analysis was completed."*

Ask whether the work answered the original questions, provided
sufficient evidence and enabled the stakeholder to make the intended
decision.

Having this conversation upfront gives both the analyst and stakeholder
a clearer idea of what the project is working towards.

### 10. Identify constraints and risks

Every project operates within constraints.

These could include deadlines, limited resources, privacy requirements,
incomplete data, assumptions, technical dependencies or reliance on
other teams.

Making these explicit early helps stakeholders understand what the
analysis can realistically deliver.

It also allows potential risks to be addressed before they become
blockers halfway through the project.

### 11. Define the deliverables

Agree on what will actually be produced.

Does the stakeholder need a dashboard? A presentation? A written report?
A dataset? Recommendations? Or perhaps simply an answer to a specific
question?

A technically impressive dashboard isn't useful if the stakeholder
needed three numbers for a decision on Friday.

The format of the deliverable should ultimately reflect how the analysis
will be consumed and used.

### 12. Create the project plan

Finally, turn the scope into a plan.

Define the major tasks, owners, dependencies, milestones and
timeline---from obtaining the data through analysis, validation and
communicating the results.

At this point, an ambiguous business request should have become
something much more concrete: **a clearly defined analytical project.**

## Scoping Doesn't Mean the Scope Won't Change

One thing I've learned is that good scoping doesn't eliminate
uncertainty.

You will still discover things in the data that change your
understanding of the problem. Stakeholders will provide new information.
Assumptions will turn out to be wrong. Questions will evolve.

That's normal.

The purpose of a framework isn't to prevent you from ever going back to
a stakeholder. It's to make those conversations more productive and
reduce the number of avoidable unknowns you carry into the analysis.

For me, these 12 steps provide a structured way to move from:

**ambiguous request → defined problem → analytical questions → data →
analysis → decision.**

And that means I spend less time asking *"What exactly are we trying to
do?"* halfway through a project---and more time answering the questions
that actually matter.

## What's Next?

A framework is useful, but the real test is how well it works when
you're faced with an actual business request---especially one that isn't
clearly defined.

In the next article, I'll take you through a practical example, starting
with an ambiguous business request and working through each of the 12
steps to turn it into a clearly scoped analytics project.

The aim is to show not just **what questions to ask**, but **how the
answers shape the direction of the analysis before we even touch the
data**.

See you in the next one.
