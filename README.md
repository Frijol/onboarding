# Onboarding

Thoughts &amp; approaches to onboarding in the context of large code-based projects.

**What's here so far?** Thoughts and some generalized useful information for people new to contributing to open source projects.

[Read this as a Gitbook](https://frijol.gitbooks.io/open-source-onboarding/content/) | [See on Github](https://github.com/Frijol/onboarding)

## Why?
Onboarding is hard.

* It's hard at big companies (where new recruits often spend the first couple of weeks in long and minimally effective meetings).
* It's hard at small companies (where maybe nobody has time to help the newbie because of shipping deadlines and there aren't good procedures or docs yet).
* It's hard at non-company open source projects (where project maintainers are typically people you've never met, might not be able to identify, and might or might not be open to helping newbies– and conversely, where project maintainers have no way to gauge whether a given new contributor is interested in mentorship, or maintainers might just not be able to prioritize mentorship)

But you have to onboard for just about every project. Somehow, new people have to be brought up to speed.

How can we do this effectively and efficiently?

## What's the situation?

* People being onboarded might have a specific purpose (learning? specific feature/bug?)
* People being onboarded have an unknown level of skill
* Project maintainers have varying levels of time/interest/skill in mentorship
* Project may have a lot of complexity & change often

## What can we draw from?

* Onboarding is a process of teaching and learning. It's a very specific subject, but general teaching principles can be applied
* Code as craft: mentorship/apprenticeship type scenarios seem like a good fit because (a) code reviews/pull requests explicitly encourage this type of interaction and (b) code projects tend to be byzantine messes of files, so it really really helps to have someone show you around/help you find stuff when you're new/explain why it's structured in that way, if possible
* Interactive learning: because most projects have many open issues, there is likely some project that a newcomer can be assigned to in order to get familiar with the project (but they will likely need help navigating the project)

## Examples/application

### Finding issues to work on
* [yourfirstPR](https://yourfirstpr.github.io/) and similar labels/movements help people find the more-accessible first issues to tackle within a given project
* [Servo Starters](https://starters.servo.org/) has a nice getting-started page based around issue-finding
* [Node Todo](http://nodetodo.org/) is a guide to help people make first contributions to Node core
* Node and other projects have not just a "beginner friendly" label but also a "mentor available" label. "Beginner friendly" should typically mean that the issue is well-defined and gives enough supporting information that someone brand new to the project should know where to start looking. Node elevates "beginner friendly" issues that are still untackled after a few weeks to "mentor available"– assumption is that if you flag an issue "mentor available", you become the mentor

### Mentorship
* RailsGirls Summer of Code (and similar) creates an explicit mentorship environment within open source projects
* Formalized processes: Tessel Project defines a "team member" as someone who is capable of bringing someone new into the project. Nominees from the contributor base are assigned a mentor who is assigned at least two week-apart video calls
