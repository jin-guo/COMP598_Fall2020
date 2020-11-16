#Assignment 3: Security and Privacy

## Overview
In this assignment, you are going to use threat modeling techniques to identify the most important threats to your case study system (the same system in your Assignment 1 and 2 reports) and to understand their impact on the product users. Consider this analysis happens during the early stage of product development. Note the objective is not to build a comprehensive threat model, but to analyze the threats that are most relevant to the ML components.

## Tasks and Questions:

**Task1:**

Build the [data flow diagrams (DFDs)](https://en.wikipedia.org/wiki/Data-flow_diagram) for the system/subsystem that are relevant to the user stories you created in Assignment 2 [15]. DFD is one of the common first steps for threat modeling. Since this activity happens at the early stage of the system design, the diagram doesn't need to be very detailed. The granularity of the diagram only needs to be sufficient for the analysis of Privacy and Integrity related threats of your ML components. You can reference the Section of **Explain and Explore** from [this link](https://martinfowler.com/articles/agile-threat-modelling.html) for the concrete steps of building a lo-fi DFD. Provide a short decription of your diagram and explain how it satisfy the user stories you created in Assignment 2 [5].

**Task2:**

Get familiar with the [Security Cards](http://securitycards.cs.washington.edu/assets/security-cards-deck.pdf), including all four dimensions. 

Sort the cards within each dimension in the order of relevance to the DFD from Task1, following this order: Human Impact cards, then the Adversary’s Motivations cards, then the Adversary’s Resources card, and then the Adversary’s Methods cards. During the sorting, please consider each dimension independently and sort the cards within that dimension in the order of how relevant and risky it is for the system.

If you have other considerations that are not included in the current suits, please add them in as customized cards and sort them together with the existing cards. 

Questions [60]:
1. **Question 2.1:** What are the top three ranked cards in the dimension of Human Impact, and why do you choose them? Explain the relevance of each card and link the discussion to the persona you created in Assignment 2 [15].
2. **Question 2.2:** What are the top three ranked cards in the dimension of Adversary’s Motivations, and why do you choose them? Explain the relevance of each card, provide examples of issues and actions of the adversaries [15].
3. **Question 2.3:** What are the top three ranked cards in the dimension of Adversary’s Resources, and why do you choose them? Explain the relevance of each card, provide examples of adversary's expertise and contributors [15].
4. **Question 2.4:** What are the top three ranked cards in the dimension of Adversary’s Methods, and why do you choose them? Explain the relevance of each card, provide examples of their attack methods, the outcome of the attacks, and potential defenses to their attack[15]. 

**Task3:**

Choose two cards from your list in Question 2.1-2.4 that come from different dimensions. For each card, find a news article from within the last year that related to that card. Describe:

1. The news event [6];
2. How the news event is an example of the ideas on the card. For instance, if the event is an attack, explain the attacker's motivation, what resources and/or methods the attacker used, or how the attack impacted human beings. [14].

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

