# Software Engineering Job Ladder

| band | title |
| --- | --- |
| E0 | Software Engineering Intern |
| E1 | Software Engineer I |
| E2 | Software Engineer II |
| E3 | Software Engineer III |
| E4 | Senior Software Engineer |
| E5 | Principal Software Engineer |

# Components

There are four primary areas that contribute to determining progress through our
levels.

- Technical Ability & Experience
- Communication
- Critical Thinking
- Initiative

## Technical Ability & Experience

How well does the engineer perform the technical skills needed to be successful?
Is the engineer adept at coding, system's design, devops?  How well does the
engineer work within the Software Development Life Cycle?  How much "been there,
done that" does the individual exhibit?

## Communication

How well does the engineer communicate with the team, with other engineers,
with junior staff looking to learn? How well does the engineer communicate
with the greater software engineering community at large?

## Critical Thinking

Is the engineer able to think around difficult problems and derive new methods
of finding a solution?  Can the engineer balance short-term needs with long-term
goals?  Can the engineer "Build to Fail Well"[^fw] instead of focusing on
the "Happy Path"[^hp]?  Can the engineer identify requirements of a
solution?  Is the engineer solely focused on the code or the solution?

## Initiative

How scrappy is the individual?  Do they take ownership?  Do they follow through
to the end or abandon something in favor of the next shiny language or project?

# Descriptions

It is important to keep aware that these are not rigid guidelines but more of an
area of general progress.

## E0: Software Engineering Intern

**Role:** Help the team! Do the stuff that seems menial and basic, but gets you
experience.  Learn!  Follow the 1 hour help-team rule[^htr].

**Typical Project Duration:** 1 day - 2 weeks

**Scope:** within single project

**Anti-patterns:** Ignores the help-team rule. Afraid to try big new things.
Insists on only working on the toughest engineering issues.

**Experience:** ~0-1 years

## E1: Software Engineer I

**Role:** Builds defined features, investigates and fixes bugs, writes
appropriate tests.  Communicates progress, identifies blocking issues.
Find a work-life balance.

**Typical Project Duration:** 3 days - 2 weeks

**Scope:** Within single project

**Anti-patterns:** Poor code quality.  Not self-motivated; needs someone to
tell them what to do next.  More inclined to blame-complain than roll up
sleeves.  General helplessness.  Disregards team process.

**Experience:** ~0-2 years

## E2: Software Engineer II

**Role:** Helps define feature requirements, build larger defined features.
Identifies potential blocking issues during planning phase.  Writes test plans.
Focuses on delivering solution and not just stated features.

**Typical Project Duration:** 2 weeks - 6 weeks

**Scope:** Takes ownership of simpler projects.  Works within team.

**Anti-patterns:** Poor code quality.  Not self-motivated. Still focuses on the
"Happy Path" when developing functionality.

**Experience:** ~1-3 years

## E3: Software Engineer III

**Role:** Owns a functional area.  Breaks large requests down into sub-tasks,
gives higher-level status updates.  Takes operational responsibility.  Sets
measurable goals, and meets them.  Reviews code changes.  Helps interview and
mentor new hires.  Integrates runtime monitoring as part of solution delivery.

**Typical Project Duration:** 2 weeks - 2 months

**Scope:** Functional area owner, drives projects to completion. Works with
business and other stakeholders to deliver solutions.

**Anti-patterns:** Disappears into projects that don't matter to the business.
Fails to identify or communicate big roadblocks.  Us-vs-them attitude.
Continually underestimates timelines.  Doesn't take operational excellence
seriously.  Solutions are typically overengineered and more complicated than
necessary.

**Experience:** ~2-5 years

## E4: Senior Software Engineer

**Role:** Owns the development and rollout for an entire product, or large
project.  Champions process and SDLC.  Writes tech specs and identifies risks
before starting marjor projects.  Sets standard of excellence.  Goes out of
their way to reduce complexity.

**Typical Project Duration:** 3 weeks - 6 months

**Scope:** Works within team on multiple projects.  Works with business and
other stakeholders to deliver solutions.  May work with external partners on
collaborative projects.

**Anti-patterns:** Arrogant jerk.  Suffers from "not invented here".  Ego gets
in the way of delivering solutions and pushing for excellence.  Doesn't
delegate. Suffers burn-out due to always saying "yes".  Lets details slip
through the cracks and does not follow up on commitments.  Fails to raise
awareness of projects at risk or people problems.  Doesn't follow new
technologies or industry trends.

**Experience:** 5+ years

## E5: Principal Software Engineer

**Role:** Owns cross-team shared infrastructure.  Works with organizational
leadership to choose new technologies, and promote culture / process. Has deep
technical expertise in a business-critical area.  Does serious research to
evaluate and test options.  Understands, and communicates, implications and
trade-offs of reliability, scability, operational costs, ease of adoption by
organization, recruiting, etc.

**Typical Project Duration:** 1 month - 1 year

**Scope:** Works throughout organization to drive engineering excellence.

**Anti-patterns:** Over-emphasis on scalability or high availability far beyond
business needs.  Spends too much time chasing the newest shiny technology with
little benefit to business. Doesn't collaborate or ask questions.
Condescending.  Has "pet" agenda.  Constantly in conflict with senior
organizational leadership.

**Experience:** 8+ years


# Notes

## What is the help-team rule?

Help the team before (and by) asking for help.

If you immediately ask for help as you encounter a problem, you're not helping
your team first. Ideally you would chew on a problem for an hour, a day,
whatever is appropriate to the size of the task. You'd research it, do web
searches, dive into code. After some (admittedly nebulous) period of time, you
will ask for help.  If you continue to search in vain, you are no longer helping
yourself or your team by being stuck.

**tl;dr** - If you ask before searching, you're wasting the team's time. If you
stubbornly search too long, you're also wasting the team's time.

## What does it mean to Build to Fail Well vs Build For the Happy Path?

When developing a system for production, planning for a graceful failure (and
subsequent recovery) is vital.

Code that only functions in a perfect world, with a perfect runtime context and
pristine input is said to have been built for the Happy Path.  The Happy Path is
a mythical road that leads to late nights and burnout.

Junior developers (but sometimes senior!) tend to focus on meeting a certain
requirement and fail to consider possible paths that a code function may take
based on dynamic runtime contexts or invalid input.

## Footnotes

[^htr]: help the team before (and by) asking for help

[^fw]: plan for a graceful failure and subsequent recovery

[^hp]: code that only works in a perfect world

## Heavy inspiration for this document

Much of this document was heavily inspired from the following article:

https://blog.usejournal.com/the-software-engineering-job-ladder-4bf70b4c24f3

