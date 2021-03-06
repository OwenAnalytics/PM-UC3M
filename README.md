<!-- README.md is generated from README.Rmd. Please edit that file -->
Notes for *Predictive Modeling*
===============================

[![Travis-CI Build Status](https://travis-ci.org/egarpor/PM-UC3M.svg?branch=master)](https://travis-ci.org/egarpor/PM-UC3M) [![License](https://img.shields.io/badge/license-CC_BY--NC--SA_4.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Course overview
---------------

These are the notes for *Predictive Modeling* for the course 2017/2018. The subject is part of the [MSc in Big Data Analytics](https://www.uc3m.es/ss/Satellite/Postgrado/en/Detalle/Estudio_C/1371210340413/1371219633369/Master_in_Big_Data_Analytics) from [Carlos III University of Madrid](http://www.uc3m.es/).

The notes are available at <https://bookdown.org/egarpor/PM-UC3M>.

The course is designed to have, roughly, **one lesson and one lab for each main topic** in the syllabus. The schedule is tight due to time constraints, which will inevitably make the treatment of certain methods a little superficial compared with what it would be the *optimal*. Nevertheless, the course will hopefully give you a great panoramic view of different available methods for predictive modeling.

Here is a broad view of the **syllabus**:

1.  [Introduction](https://bookdown.org/egarpor/PM-UC3M/intro.html) (first lesson)
2.  [Linear models I](https://bookdown.org/egarpor/PM-UC3M/lm-i.html) (first/second lesson)
3.  [Linear models II](https://bookdown.org/egarpor/PM-UC3M/lm-ii.html) (second/third lesson)
4.  [Linear models III](https://bookdown.org/egarpor/PM-UC3M/lm-iii.html) (third/fourth lesson)
5.  [Generalized linear models](https://bookdown.org/egarpor/PM-UC3M/glm.html) (fifth lesson)
6.  [Nonparametric regression](https://bookdown.org/egarpor/PM-UC3M/npreg.html) (sixth lesson)

<!-- 7.  [Generalized additive models](https://bookdown.org/egarpor/PM-UC3M/gam.html) (seventh lesson -- skipped) -->
The **office hours** are **Thursdays from 19:15 to 20:15**, at the classroom in which the lab took place. Make use of them!

**Questions and comments** during lectures are mostly welcome! So just go ahead and fire. Especially if these are clarifications, comments or alternative perspectives that may help the rest of the class.

Course evaluation
-----------------

Evaluation is done by means of **two group projects**, to be done in groups of 3 (preferable) or 2 students, plus a presentation of one randomly-selected report. The final grade (in the scale 0-10) is:

    min(0.70 * reports_grade + 0.30 * individual_presentation_grade, 10)

The `individual_presentation_grade` is in the scale 0-10. The `reports_grade` (in the scale 0-12) is the weighted grade of the two reports about the following topics:

1.  Linear models I, II, and III (weight: 60%; **deadline: 2017/12/21**).
2.  Generalized linear models **or** Nonparametric regression (weight: 40%; **deadline: 2018/01/25**).

Deadlines are subjected to minor changes due to the course development.

### Group projects

#### Groups

It is up to you to form the groups based on your grade expectations, affinity, complementary skills, etc. Take into account that all the students in a group will be graded evenly for the `reports_grade`.

Communicate the group compositions by filling this [Google Sheet](https://docs.google.com/a/uc3m.es/spreadsheets/d/10zWtuhpAEtfZs7tuL9wEPdGsLVVYT-MKDLudvuhEFCA/edit?usp=sharing) (you need to log in with your UC3M account). An example: if students A, B, and C form the group number `4` in the second project, add a `4` to the the rows of A, B, and C in the `Project II` column. Keep the same numbers in both columns if the composition of the group does not change. Under extraordinary circumstances to be communicated in advance to the professor, it is possible to switch group members from project to project. Be advised that this might have undesirable consequences if you do so: you might have to present two different randomly-chosen group reports.

#### Report structure

The report must analyze a real dataset of your choice using the statistical methodology that we have seen in the lessons and labs. The purpose is to demonstrate that you understand and know how to apply and interpret the studied statistical techniques in a real-case scenario. Simulation studies (*i.e.*, analysis of artificially generated data) are also allowed if they are meant to illustrate interesting features or insights of the methods. The data analyzed does not have to be necessarily 'Big Data' and you may use the same dataset for different reports (if that makes sense).

Compulsory format guidelines:

-   Structure: title, authors, abstract, first section, second section and so on. Do not use a cover.
-   Font size: 11 points.
-   Font type: any sensible choice (`Comic Sans` is not).
-   Margins: any sensible choice. `Rmd` defaults works quite well.
-   Spacing: single space, single column.
-   Length: **10 pages at most**. This includes tables, graphics, code, equations, appendices, etc. Everything must fit in 10 pages. Want extra space? You can buy it at `-1.00` points per extra page! ;)
-   Style: be concise, specific, and insightful. Make a clever use of the space.
-   Code: do not include *all* the code in the report. Instead of, just add the parts you want to highlight (or that you believe are particularly interesting) and describe what the code is doing, but provide it for reproducibility. A great way of doing this is to create an `R Markdown` document and omit the lengthy code chunks, providing the `.pdf` and `.Rmd` outputs.

Mandatory report structure:

1.  **Abstract**. Provide a concise summary of the project. It must not exceed 250 words.
2.  **Introduction**. State what is the problem to be studied. Provide some context, the question(s) that you want to address, a motivation of its importance, references, etc. Must not be *very* extensive.
3.  **Methods**. Describe in detail the methods you are going to use, showing that you know what you are writing about. For example, you can include: background, useful interpretations, connections with other methods, alternative expositions, discussions, remarks, etc. if you wish, you can describe generally the method and then focus in exploring in more detail one particular feature that you use for the analysis. Optionally, go beyond what was taught in the lessons by considering extensions, improvements or better (in certain sense) implementations.
4.  **Statistical analysis**. Apply the statistical methods to the real data. Justify their adequacy to the data studied. Obtain analyses, in the form of summaries and plots. Provide a discussion about the outputs, interpret them and obtain insights about the data. These last points tend to be skipped and are very important!
5.  **Conclusions**. Summary of what was addressed in the project and of the most important conclusions. Takeaway messages. The conclusions are not required to be spectacular, but *fair and honest* in terms of what you have discovered.
6.  **References**. Refer to the sources of information that you have employed (for the data, for information on the data, for the methodology, for the statistical analyses, etc).

#### Report grading

The report grading will be performed according to the following breakdown:

-   **Method description** (4.5 points). In general, graded according to the evidence you show about the knowledge of the methods. For example, method descriptions in your own words that are accurate, detailed, and present your own insights are positively received.
-   **Statistical analysis** (3.5 points). Graded according to the adequacy of the method to the data, the quantity and quality of the analysis provided, and, very importantly, the interpretation and the insights obtained from the statistical analyses.
-   **Presentation** of the report (2 points). This involves the readability, the conciseness, the correct usage of English, and the overall presentation quality (`R Markdown` is preferred!). Code documentation (comment what the code is doing!), reproducibility, and clarity are also evaluated.
-   **Excellence** (2 bonus points). Awarded for creativity of the analysis, originality of the problem studied and/or of the data acquisition process, use of advanced statistical tools, use of points briefly covered in lessons/labs, use of extensions of the methods, description of advanced insights of the methods, completeness of the report, use of advanced presentation tools, etc. Only awarded if the sum of regular points is above 7.5.

#### Report hand in

Upload **one** report per group, in the form of a `.pdf`, to the `Turnitin` task associated to that report in AulaGlobal. Upload only a `.pdf`, not other file, so this can be checked for originality. **Also**, send **one** email per group to <edgarcia@est-econ.uc3m.es> with the subject "PM - Report X - Group Y" (replace X and Y as convenience) and write the group members in the body of the email. Attach the report (in `.pdf`) and all relevant scripts (e.g., `.Rmd` and `.R`) in a single `.zip` file. Be sure to ensure easy reproducibility of analysis (e.g., include the data you employed or the pertinent `.RData`).

**Deadlines**: the deadlines finish at **23:59** and the list of days can be seen above. Recall that the last deadline, the 25th of January at 23:59, is quite close to the presentation day, the 30th of January.

Need extra time? Buy it at expenses of a penalization in your grade: `-0.04` points per extra hour! ;) But only until the **25th of January**, reports received after that date will not be graded. The maximum grade according to the hours past the deadline is given in the graph below.

![](penalization-1.png)

### Project presentations

The **30th of January, from 09:00 to 21:00 in room 0.B.08**, each group must present one of the two projects. The project to be presented is randomly selected. On the 25th of January, a list with the selected reports and presentation schedule will be made public, so you know at which time you have to present. Restrictions, if any, must be communicated and justified in advance. The presentation will determine the `individual_presentation_grade`.

The evaluation will be carried out as follows:

-   Each group must present one report. Strict presentation policy: **all students must present for 5 minutes**. This is a 15-minutes or 10-minutes limit for the whole presentation, depending on the group size. Tailor your presentation to that time limit and break it evenly among the group members.
-   All group members must be present in the presentation. Failure to be at the presentation results in `individual_presentation_grade <- 0`.
-   The **presentation must follow tightly the report contents**. You just need to explain properly what you did in the group project without adding new material. Take this into account when preparing the reports.
-   In the presentation, you may want to highlight your main (personal or group) contributions and show your understanding of the methods.
-   **Questions may be asked during and after the presentation of each student.** Questions may be about the theory, implementation, or other matters related with the report. You are assumed to know and be able to defend all these topics. Together with the presentation, the accurateness, conciseness, and detail in the answers will determine the **grade**.

### Academic fraud

Evidences of academic fraud will have serious consequences, such as a zero grade for the whole group and the reporting of the fraud detection to the pertinent academic authorities. Academic fraud includes (but is not limited to) plagiarism, use of sources without proper credit, project outsourcing, and the use of external tutoring not mentioned explicitly.

Contributions
-------------

Contributions, reporting of typos, and feedback on the notes are very welcome. Either send an email to <edgarcia@est-econ.uc3m.es> or (preferably) fork the repository, make your changes and open a pull request. Give me a reason for writing your name in a list of contributors!

License
-------

All material in this repository is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
