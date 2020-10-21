# Assignment 2: Approach Understanding User Need and Design

## Overview

One of the biggest challenges for building any product to develop empathy for the end users of the product and meet their needs at various levels. It is particularly important when the product you are building contains learning components that might exhibit unexpected behaviors and a substantial long-term impact on the users. In this assignment, you will build on the investigation of your first assignment report and focus on how to identify the user groups for the system you have chosen and how to address two design concerns for that system (i.e. level of control and feedback loop).


## Tasks and Questions

**Task1:**
Creating [personas](https://www.interaction-design.org/literature/article/personas-why-and-how-you-should-use-them) can help you understand the user requirements and to design the user experience to best fit the needs of particular user communities. In this task, please first identify the direct and indirect user classes for your target system and create the persona for the favored user class (or one of the favored user classes).

Questions [65]:

1. **Question 1.1:** Explain who are the different user classes of your target system [10] and why they should be favored, disfavored, or ignored during the product development [5].
2. **Question 1.2:** Create the persona for your target system that is similar to [this example](https://s3.amazonaws.com/media.nngroup.com/media/editor/2015/01/19/examplepersona.png), and describe the process you follow to design the persona [15]. Justify the design of the personas by lightweight [user research](https://www.interaction-design.org/literature/topics/user-research) (e.g. interviews) [10]. Remember that your persona doesn’t need to document every aspect of the imaginary individual. Rather, it should focus on only the characteristics that impact the feature design related to the machine learning component (e.g. personalized content recommendation of movie streaming service).
3. **Question 1.3:** Using the persona as an instrument, write a list of [user stories](https://learning.oreilly.com/library/view/agile-software-requirements/9780321685438/ch06.html) (relevant to the machine learning components) following this format [10]: 
`As a <role>, I want <activity> so that <values for the role>. `
and the corresponding acceptance tests [15]. Make sure your acceptance tests are verifiable. You might want to complete this question together with Question 2.2 and reference the BIS book: Chapter 15.

**Task 2:**
In this task, you will consider how to approach designing an intelligent system addressing two primary concerns: user control and feedback loop. 

Based on the context of the problem, the users might expect to have a higher level of control. For example, when AI is used in a high-stake situation, the users might want the option to be in full control before they build sufficient trust in the system. Another example is when the recommendation was not relevant to the users' preferences that have been evolved. It is therefore important to map how much control the users need across different interactions with the product.

One other essential design task for building the intelligent system is to design the feedback loop that can be integrated to improve the learning component. It includes designing mechanisms to collect implicit feedbacks (e.g. telemetry data about how users are interacting with the system) and explicit feedbacks(e.g. app reviews, user surveys). As a designer, you need to balance the benefit of collecting the feedback and potential risk or additional effort imposed on the users.



Questions [35]:
1. **Question 2.1:** Consider all the user stories you have identified in Question 1.3, described the level of user control needed (i.e. low, medium, high, and unsure) for concrete context. Justify why you assign a certain level of control for each case using the persona you designed and other evidence [15].
2. **Question 2.2:**
Design and describe the feedback loop for the intelligent feature you have been focusing on since Question 1.3. Particularly, include the following information in your description for each feedback mechanism [20]. Again, considering using persona and other evidence you can gather to examine the benefit and risks for the user.
* Concrete feedback mechanism
* Type of feedback (i.e. implicit or explicit, qualitative or quantitative)
* Timing and frequency for collecting the feedback
* Usage of the feedback
* User benefit of giving feedback
* Timing for users receiving the benefit (e.g. immediate, next deployment, unknown)
* Any perceived risks for the user





## Grading

This assignment is worth 100 points. The grading includes two phases:

**Peer Editor (25 points):**
Everyone will read one submission of your classmates after the initial submission. The editor's role is to provide concrete **compliments, suggestions, and/or corrections** on the submission (directly on the PDF) considering the following grading criteria:
- each question is completely answered;
- the answer to the question is clear and effective;
- the discussion is supported either by evidence or reasonable speculation. 

You will be graded on how well you **serve as an editor**, in particular, to what extent your comments/suggestions are clear and constructive, not the length of the comments. 


**Submission Grade (75 points):**
After you receive the peer editor's comments, please revise your submission, and submit the revised version to MyCourse. We will grade this version using the same criteria during peer editing. The percentage of the grade for each question/subquestions is listed after the sentence in [XX]. 

