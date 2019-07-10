---
layout: markdown.hbs

title: Getting started
slug: starting
lead: How to start a team towards level 2 proficiency
proprietary: true
contributors:
 - name: Arlo Belshee
   username: arlobelshee
   gravitar_id: 6995191364b77794684fbf3a3d6dacd7
---

# Context

We are assuming a software organization:

* of 50-150 individuals,
* with legacy code (roughly 1MLoC / developer, roughly 500 known open bugs / developer),
* with hierarchical reporting structures,
* where work is executed by individuals according to specialized skills,
* who make product decisions based on the Highest Paid Person's Opinion (HiPPO),
* under competitive pressures that prevent them from stopping or even significantly slowing production in order to fix things that they know are broken.

Who wants to be an organization:

* of the same 50-150 individuals,
* who release at will,
* who use build-measure-learn from Lean Startup to make product decisions,
* who get a little better each day and fix each problem as it arises,
* with much higher productivity,
* and enjoy work.

This is a typical transformation. It requires changes in process, tooling, skill, culture, expectation, and structures. These changes need to be synchronized across time and teams so that they support each other.

This page describes the base recipe we customize to make it happen. The recipe is described chronologically, starting about a month before the official start date.

> Note:what we don't do is at least as important as what we do. Customization usually alters how we do the things we do and may add some context-specific actions, but it does not include removing things from the "do not do" section. Doing these things, especially early in the process, tends to bog down a transformation.

# Week -4

First we get the right people in place to support the transformation to come. We also prepare the managers to shift from managers to servant leaders.

## Do

**Pick the right change unit.** Pick a set of people who share responsibility for some outcome and own that from the perspective of the rest of the organization. A product team is a good example. The technical people involved in a product is not a good example (some people required for success are not in the group). Neither is a set of people who contribute to multiple businesses, even if they all report to the same manager.

The right change unit has a name. That name is obvious. It is probably known by your customers.

**Designate champions for the transformation.** Fundamentally, champions are any people that have effective veto power in your organization. When a new thing shows up, everyone in the room first looks to someone to see whether that person is nodding or shaking their head. That person is a champion. Typically you will find (and need) champions from every role and every level of the hierarchy.

Champions must meet several criteria:

1. Be trusted by the group to veto bad ideas.
2. Volunteer. Have enthusiastic involvement&mdash;even if only to protect themselves/their team from a bad transformation.
3. Be supported by whomever assigns them work. They will need to do less of their regular work in order to do work as champions.

Additionally, the set of all champions must meet several criteria:

1. Everyone in the organization must see at least one champion who he trusts to tell him new ways to work. This generally requires a champion who has the same role and level in the organization.
2. If the champions group makes a decision then it is made. Decisions are not subject to review or veto&mdash;anyone who could veto is a champion.
3. Have a group identity.

**Check whether top managers want to become servant leaders.** Clarify what this role shift means. Clarify that it means they will no longer made decisions or even have much influence into the decisions that are made. Clarify that it means they can no longer punish or reward people for making good or poor decisions&mdash;only reward a culture of taking appropriate risks, knowing they might succeed or fail. Are existing managers enthusiastic about this prospect?

## Do not do

**Try to change a unit of over 150 people as one unit.** If the obvious names are for groups larger than this size, then find well-named subgroups that make sense. Different change groups can still coordinate their products, but change is easiest if the change boundary does not exceed 150 people.

**Leave out resistors.** These are your champions of important advantages of the current system. You need to maintain or enhance those advantages and these champions are the ones with the perspective to do that.

**Do change management.** People don't like to be managed. They really don't like to have their expectations managed. Instead, we are picking a set of people who will figure out what to do, how to help it happen, and how to let everyone see it happening as it does.

**Decide, centrally, what will happen.** We are changing culture from one that highlights a small number of brains as "exceptional" to one that takes advantage of all the brains in the organization. Accomplishing this requires that we actually use all of those brains&mdash;especially when they get different results than the few brains that used to make all the decisions.

**Ask everyone who should be champions.** The group is poor at making group decisions right now. They are skilled at using authority. So use authority to quickly identify the right people. Do ask people from each part of the organization who the right people are; people are often obvious choices to one segment and invisible to another.

**Continue if managers expect to retain authority.** People with status will retain status, but authority will become a much less appropriate method of making decisions. Current managers will lose their authority; they will have to seek consensus&mdash;just like everyone else always has&mdash; if they want their opinions to influence decisions. If managers aren't enthusiastic about this prospect, stop the transition. The new culture requires decentralization of power.

# Week -2

The champions align strategic intent. This determines the transformation plan. Champions understand the approach; they know why they will do certain things and can explain that when asked.

## Do

**Discuss intentional culture, decision-making methods, and shared strategic intent.** These are core ideas that probably do not exist in the prior culture. All champions need to be up on those ideas before we start making plans.

**Performance chain analysis + six boxes.** Decide what outcome we are going to change, understand the systems at play, and determine the system changes that will get us there. Agree on behavior influencers we are changing and why.

Time box the performance chain analysis to 90 minutes. Have 100% of the champions in the room. Have a facilitator who is familiar with the technique. If you can't get to agreement in 90 minutes, then you are not yet ready for change. You have some systemic problem that will prevent transformation at this time. **Stop**, fix that, and then try again.

## Do not do

**Decide, centrally, what will happen.** We are changing culture from one that highlights a small number of brains as "exceptional" to one that takes advantage of all the brains in the organization. Accomplishing this requires that we actually use all of those brains&mdash;especially when they get different results than the few brains that used to make all the decisions.

**Try anything without enthusiasm by 100% of the champions.** If you can't get full consensus then you don't yet understand your business problem or context well enough. You won't come up with changes that actually improve things universally. And champions are people with veto power (by definition). If you try to go against even one champion, others in the organization will see the same problems and reject the change.

**Badger champions into agreement.** The problem isn't that champions disagree. The problem is that some aspect of the system will be hurt by the current proposal. One champion is the voice of that part of the system and sees the problem everyone else is missing. Use this information to find a better proposal.

# Week -1

Prepare the kickoff. Technical champions learn key micro-skills.

## Do

**Focus on launch day. Champs design a launch.**

**Ensure technical champs know how to do key skills.** These skills are:

1. Facilitate a mob.
2. Refactor, using tools, to introduce names (key 6 refactorings).
3. Write a mini-spec, designed to be read, in a unit testing framework (using fluent assertions).
4. Understand the sequence of developing good names (J.B. Rainsburger's blog post).

## Do not do

**Managers take over.** The culture of having anyone other than management own change is weak. It requires strong reinforcement this week. Err on the side of manager non-involvement if you can't have managers participate as supporting characters.

# Day 1

Clearly indicate that change is happening and supported at all levels. Align strategic intent throughout organization. Institute structural changes that enable continuous improvement.

## Do

**Put the individual contributor champs front and center.** Everyone else explicitly indicate support for what the teams and IC champs decide to do. highlight the importance of the business problem and some of the sacrifices you are willing to make to solve it.


## Do not do

**Any presentation by the manager or a consultant.** The champions decided what to do. They know why they decided those things. They need to present the information to the organization. Managers are champions and have an equal role. However, historically managers have probably had a superior role. So they will have to intentionally take a lesser role in order to establish balance.

# Week 1

Teams start changing themselves. Start reading code by using tool-driven refactoring to introduce names. Reduces cost to implement stories that involve changing legacy code, while also reducing defects in that code. Teams create learning environments by sharing work.

## Do

## Do not do

# Week 2

Teams deal with the pain that comes from starting to share work. Teams master changing themselves. Start extracting specs from legacy code. Whole team improves understanding of what the product actually does.

## Do

## Do not do

# Week 3

Teams use testability to drive context-neutral coding. Code size starts to reduce as a side-effect of normal working. Team learns

## Do

## Do not do

# Month 2

## Do

## Do not do

# Important future moments

## Do

## Do not do
