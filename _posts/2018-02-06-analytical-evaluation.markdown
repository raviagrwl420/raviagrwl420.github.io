---
layout: post
title:  "Analytical Evaluation Methods in HCI"
date:   2018-02-06 09:00:00 -0700
categories: hci
---
## Introduction

Usability inspection methods such as heuristic evaluation are often used as cost-effective alternatives to empirical user studies as a part of the iterative design process for finding usability issues in a user interface. These methods are not meant to replace usability testing altogether but are typically used early in the design cycle to uncover key design issues before the eventual usability tests are conducted. Here we discuss heuristic evaluation and how it compares to another actively used usability inspection method known as cognitive walkthrough.

### Heuristic Evaluation

Introduced by Nielsen and Molich, heuristic evaluation involves having a small set of usability experts evaluate a user interface and judge its compliance with recognized usability principles known as the heuristics<sup>1</sup>. The heuristics, originally developed by Nielsen and Molich, and later revised by Nielsen, include 10 broad design principles that must be followed for effective user interface design. 

As a part of heuristic evaluation, the usability experts refer to the design principles being violated when identifying the usability problems, the severity of each problem and where it exists. Evaluation by a single individual is unlikely to identify all the usability problems in an interface hence in order to be more effective Nielsen recommends using three to five evaluators. To ensure independent and unbiased evaluations, each evaluator carries out the evaluation individually and the results are aggregated at the end of the evaluations.

### Cognitive Walkthrough

The cognitive walkthrough is a technique for evaluating the design of a user interface for its ease of "exploratory learning," i.e. first time use without formal training<sup>2</sup>. The prerequisites for the cognitive walkthrough include the determination of likely users, representative tasks and the actions to be taken during each task. Then for each representative task, the walkthrough process involves examining each individual step in the correct action sequence to identify whether the user will select each of the correct actions along the sequence path. At each individual step, the evaluators need to consider the four criteria namely the user's goal, the accessibility of the correct control, the quality of the match between the control's label and the goal, and the feedback provided after the control is acted on.

The cognitive walkthrough method does not rely on usability experts and can be performed by the system's designers in the early stages of the design, before empirical user study is possible. Unlike empirical user study, it does not require a fully functional prototype, or the involvement of the user. Cognitive walkthrough helps the designers to take on a potential user's perspective thus helping them identify some of the issues that might arise in the interaction with the system.

### Comparison of Heuristic Evaluation and Cognitive Walkthrough

In the study conducted by Hollingsed and Novick<sup>3</sup>, heuristic evaluation and the cognitive walkthrough were found to be the most actively used and researched usability inspection techniques. Both heuristic evaluation and cognitive walkthrough can be considered as faster and cheaper alternatives to empirical usability testing but are not intended to fully substitute it. They are useful as they can be implemented in the early stages of the development cycle and provide a discussion forum for interface changes.

Heuristic evaluation relies heavily on the evaluators' expertise for an effective evaluation of a user interface. Cognitive walkthrough on the other hand is found to be easily learnable and usable by novices although they may find it difficult to apply the method early in the design process and to choose the task scenarios. A study found that heuristic evaluation is likely to find more problems than cognitive walkthrough but only for expert evaluators. System designers and non-experts were able to find the same number of problems with both heuristic evaluation and cognitive walkthrough. A disadvantage of heuristic evaluation is that you need several evaluation experts whereas in some cases it may be difficult to obtain even one.

One major difference is that, where heuristic evaluation focuses on the overall interface of the system, cognitive walkthrough is useful for predicting problems on the representative tasks performed on the system. Also with heuristic evaluation, each evaluator must carry out the evaluation individually to ensure independent and unbiased evaluations. Cognitive walkthrough though originally intended to be performed individually was later revised to address some of its limitations like repetitive form filling by using small groups instead of individual evaluators.

Another concern with the heuristic evaluation is the cost. Most issues identified by heuristic evaluation in the studies conducted were minor, only a few of the severe issues were identified. There is also a possibility of false alarms, i.e. issues that may never bother the user in actual use. Cognitive walkthrough may provide a better cost to benefit ratio as compared to heuristic evaluation as it is cheaper. However, a criticism of the cognitive walkthrough is that it does not provide any guidelines about what makes an action clearly available and what types of actions are considered by a broad range of users.

### Conclusion

Here we discuss and compare heuristic evaluation and cognitive walkthrough, the most widely used usability inspection methods. While the choice of one or the other must be based on practical considerations one can also combine multiple inspection methods in the same project to obtain better coverage of usability issues. Even though the usability inspection methods rely on expert evaluators to be effective, their strengths are that they can be useful for rapid iteration early in the design cycle. Usability inspection methods however, cannot fully substitute the empirical user testing which is much required before the public release of any system.

#### References
1. Nielsen, Jakob. "Heuristic evaluation." Usability inspection methods 17.1 (1994): 25-62.
2. Rieman, John, Marita Franzke, and David Redmiles. Usability evaluation with the cognitive walkthrough. Conference Human factors in computing systems. ACM, 1995.
3. Hollingsed, Tasha, and David G. Novick. Usability inspection methods after 15 years of research and practice. Proc ACM Design of communication (2007).