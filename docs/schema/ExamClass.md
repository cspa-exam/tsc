# ExamClass

*CSPA Dev note: This corresponds to the `ExamEnums.CLASS_TYPES` struct and `Exam.class_type` database field (possible values: `core`, `front_end_web`, `back_end_web`, `employer_quiz`).*

An **exam class** is defined by its target test-taker audience, assessment goal, and collection of questions (and indirectly, the format and topic coverage).  We currently have 4 exam classes: Core, Quizzes, Front-End Web, Back-End Web, but mostly focus on Core and Quizzes.  For example:

## Core

This is the main exam we currently administer.  Candidates take this test weeks or months *prior* to applying for a job, without a specific employer in mind.  The assessment results should be highly reusable.

*Target Audience:* Entry-level software engineers (juniors/senior computer science undergraduates, coding school students)  
*Used By:* Employer seeking junior software engineers or interns
*Assessment Goal:* To determine the *career-readiness* of the candidate  
*Format:* 5-6 hours: 50-70 multiple choice questions, 2-5 open coding questions, 3 short answer coding questions  
*Topic Coverage:* programming languages, OS, algorithms, data structure, databases, tools, front-end web, back-end web  

## Quiz

Quizzes are a bit of a special case right now.  They are aimed to be shorter assessments that can be done *during* application process.  Candidates will usually be in the middle of applying to a specific job at a specific employer.  As a result, they are shorter and more specific, but the assessment results are less reusable.

*Target Audience:* Various, job-seeking candidates
*Used By:* Employers hiring software engineers
*Assessment Goal:* Replace the technical phone screen for majority of tech employers
*Format:* 1-2 hours, various question types
*Topic Coverage:* Various

We may want to deprecate the front_end_web and back_end_web and consider them quizzes instead.
