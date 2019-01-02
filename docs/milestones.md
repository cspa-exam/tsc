# Milestones Per Term

In order to release a new version every three months, this approximate schedule is proposed:

## Week 1 (January 1 - January 5)
**Onboarding**

Member introductions and onboarding.  Familiarize with current CSPA offering -- current exam formats and content, CMS tools and systems, and current challenges.

## Weeks 2-3 (January 6 - February 19)
**Exam Classes and Formats**

Discuss if the current [exam classes](./schema/ExamClass.md) are suitable for the industry.  Should we focus on a single exam class?  Or break down individual subject-based tests?  Is the duration and types of questions the right ones?  What about topic coverage?

We can also think outside of the box -- e.g. microassessments over a long period of time via mobile app, or assessing a team instead of individual?

If CSPA's exam platform does not support certain methods of assessment, new features can be requested.  The only hard requirement is that the assessment method needs to be standardized (unbiased), scalable to deploy, and can be administered at a reasonable per-unit cost.

Milestone: Determine any changes to exam classes, via voting.

## Weeks 4-5 (January 20 - February 2)
**Topic Coverage**

Once the exam classes have been determined, we need to determine what [topics](./docs/schema/Topic.md) should be covered.  This should be informed by the exam class's assessment goal and target audience.

If applicable, we may break down into subgroups -- one per exam class.  Members can participate in multiple subgroups.

Milestone: Determine the list of topics that should be covered for each exam class, including at what difficulty and level of expertise.  Also done via voting.

## Week 6+ (February 3 - March 31)
**Compiling Questions**

Once the topic coverage is determined, search the existing question bank for any suitable questions, and write new [questions](./docs/schema/Question.md).  Questions should be tagged with the proper topics and difficulty level.  Once sufficient questions are created, put them together into an [exam](./docs/schema/Exam.md).

If CSPA's exam platform does not support certain question types, languages, or environments, new features can be requested.  Respective examples: multi-part questions that increase in difficulty, Java support, and virtual machine/EC2 instance access for each test taker.

TODO: CSPA will open up exam compilation abilities to the question CMS soon.  This will allow TSC members to create new draft exams with the correct set of questions.

Milestone: A new draft [Exam](./docs/schema/Exam.md) should be ready to go.

## All Weeks
**Scoring Algorithm**

Throughout the term, we should keep in mind how these assessments should be scored.  Our scientific advisor will be instrumental here.  The predominant statistic model is [Item Response Theory](https://en.wikipedia.org/wiki/Item_response_theory).  We'll review and discuss the appropriate models and possible innovations.

Milestone: Determine changes, if any, to scoring algorithms, both at the ExamClass level and Question level.
