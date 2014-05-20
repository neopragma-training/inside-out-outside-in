# Inside-Out and Outside-In Software Design

* Audience: Programmers
* Level: Intermediate to Advanced
* Duration: 60 min.
* Format: Demonstration, hands-on, some lecture
* Methods: Experiential, practicum, group exploration

## Learning Objectives

* Understand concepts, potential benefits, and potential pitfalls of each approach
* Understand how the benefits of each approach mitigate or offset the potential pitfalls of the other
* Understand how to combine the two approaches to maximize the value obtained from each while minimizing the pitfalls
* Gain gut-level insight into the techniques used with each approach through guided hands-on practice

## Abstract

"Outside-In" is a general term that describes any approach to software development in which we specify a significant portion of the technical design in advance, before beginning to write code in earnest. We start by understanding the big picture, and then work our way "inward" toward the details. Coding usually begins with the most fundamental "horizontal" architectural layer of the design and builds from there. "Inside-Out" is a general term that describes any approach to software development in which we begin with a clear definition of the purpose of the proposed software solution but not a comprehensive specification of the technical design. Coding begins with the functionality that has the highest anticipated stakeholder value, slicing "vertically" through all architectural layers even if those layers are left partially complete at first. The technical design emerges gradually as we flesh out the solution bit by bit. The purpose of the workshop is to explore the benefits and pitfalls of these approaches and to see how they can complement one another to mitigate the weaknesses of each.

## Overview

Traditional software development methods rely almost entirely on an outside-in approach. In the most formal cases, this involves so-called Big Design Up Front (BDUF) resulting in a comprehensive Work Breakdown Structure (WBS) comprising Work Packages that have been specified in detail and estimated in terms of hours of effort. Dependencies between the Work Packages are identified, and Critical Path planning methods are used to lay out a project roadmap that includes start and end dates for all the Work Packages. This is often documented in the form of a Gantt chart, and progress is usually tracked using a technique like Earned Value Management (EVM) or a derivative thereof. 

Tracking can be as simple as comparing the percentage of work completed to date with the percentage of work that was expected to be completed per the project plan. The focus of tracking is on performance to plan, and not (directly) on actual value delivered as of the completion date. Stakeholder-defined value is assumed to have been baked into the plan at the beginning.

Lightweight methods to support an outside-in approach have also been devised. Among others, these include Domain Driven Design (Eric Evans), Agile Modeling (Scott Ambler), and Feature Mapping or Story Mapping (Jeff Patton). These techniques are often used to support adaptive software development, although they can be used with traditional software development as well. These lightweight methods blend nicely with inside-out coding techniques to provide a balanced approach to development.

Inside-out design is often used to support adaptive software development. Incomplete but functional increments of the solution provide stakeholders with real information (as opposed to estimates and documentation) to refine their vision of the goal state. In turn, their feedback to the development team helps guide the evolving solution design to meet stakeholder needs. 

In the absence of a WBS, planning is typically based on Rolling Wave, Critical Chain, and Just-in-Time techniques. Tracking is generally based on empiricism rather than on statistical methods, with a focus on steering the work toward stakeholders' evolving vision as it changes through lessons learned in using the early solution increments. Comparing actual and expected percentage complete is not meaningful for adaptive development, as there is no firm definition of 100% at the outset.

Developers taking an inside-out approach apply several key elements of professional practice in concert:

1. Disciplined use of sound software design principles appropriate to the context
2. Interleaving coding and automated testing at a fine-grained level of detail, often using automated test cases to guide or "drive" the production code
3. Frequent peer review
4. Continuous or very frequent integration of code

The inside-out approach is sometimes called "emergent design," because the technical design is not defined in detail up front, but rather emerges in the course of development to support the evolving product vision.

## Agenda and Timings

(needs refinement)

Note: No lecture or explanation prior to the first rehearsed demonstration.

Rehearsed demonstration by a pair of developers in randori format. Very strict inside-out development of "checking account" functionality using the most rigorous and literal interpretation of test-driven development. The demonstration is designed to show how a practical design emerges bit by bit when we use automated unit tests to force the creation of every line of production code. It also highlights the pitfalls of such an approach.

Explanation of what happened in the demonstration. Facilitators guide group discussion to result in a list of the benefits and pitfalls of the inside-out approach. 

Explanation of two ways to guide emergent design that are seen in the demonstration - dive "vertically" into the development of domain entities as they are identified, or mask off the required "new" entities and complete very small, intentionally incomplete, fully-tested subsets of functionality that can be checked in piecemeal. Discuss pros and cons of each. Facilitators guide group discussion to result in a list of the pros and cons of each approach.

Hands-on coding exercise by participants working in pairs. The requirement is that they follow the same very strict regimen as the facilitators demonstrated. Facilitators check on each pair and help them stick to the approach. 

Debrief.

Rehearsed demonstration by a pair of developers in randori format. Strict outside-in design of the same "checking account" functionality to create a detailed model before starting coding. The demonstration is designed to show the benefits of the approach as well as to highlight its pitfalls. 

Explanation of what happened in the demonstration. Facilitators guide group discussion to result in a list of the benefits and pitfalls of the outside-in approach.

Hands-on coding exercise by participants working in pairs. The requirement is that they follow the same very strict regimen as the facilitators demonstrated. Facilitators check on each pair and help them stick to the approach.

Debrief.

Facilitated group discussion of how we can combine the inside-out and outside-in approaches to good effect.

Hands-on coding exercise by participants working in pairs based on a different problem than the earlier one. Pairs use a combination of outside-in and inside-out techniques to develop the solution.

Wrap-up, summary, and Q&A.
