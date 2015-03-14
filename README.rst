========================
ABOUT THE LATEX TEMPLATE
========================

This is the readme file for the sample template .tex to present a master thesis at the UPF inf A4 format.
It was based on the UPF template for PhD thesis.

The .tex file contains some sample chapters to illustrate how it works.


One side, two sides
-------------------

For bette printing, you can change the document class to twoside like this:

\documentclass[12pt, a4paper, twoside]{upf_thesis}



The file tesi-upf.cls
---------------------

The file **tesi-upf.cls** is a modification of the *book style* with the following changes:
    1. Cover redesign (with the \maketitle instruction).
    	- It is prepared for mentioning two supervisors. If you don't have two, please delete lines referencing *second_supervisor* on upf_thesis.cls and thesis.tex
    2. Chapter names in capital letters.
    3. Redefinition of cleardoublepage so blank pages have no numeration.


Bibliography
------------

To test it, it incorporates a small bibliographic database: **tesi_upf_bib.bib**. You can generate your own using **Mendeley**.

To efficiently use bibliographic references, it is recommended to use the program **BibTeX**:
    1. Write *\bibliographystyle{plain}* on the preamble.
    2. Where you want the references list to appear, write *\bibliography{tesi_upf_bib}* (or your references file name).

IMPORTANT: if you are using **texmaker**, go to textmaker > preferences > quickbuild and select the second option (PdfLaTeX + Bib(lat)ex + PdfLaTeX (x2) + View Pdf)


Tables
------

It incorporates a figure and a tabular on the sample chapter, to test that the indexes are working properly.


The index
---------

Add to your preamble *\usepackage{makeidx}* and *\makeindex*, and the command *\printindex* where we want the references to appear.
To create an index entry use: \index{Lamport}

When you compile your .tex file, it generates a .idx file.
Then, to generate the index, execute from the command line *makeindex thesis* (it will generate thesis.ind file).



============================
Evaluation guidelines (MIIS)
============================

http://www.upf.edu/iis/information/thesis/guidelines.html

The master thesis project is evaluated by a committee constituted by three members: the MIIS coordinator, the thesis supervisor and another teacher of the master. This evaluation takes into account the tutoring sessions, the oral presentation and the written report.


Oral presentation
-----------------

Students present the status of their master project work in front of the evaluation committee at the end of the academic year. This presentation does not require to have finished the actual thesis report. Prior to the oral presentation, the student has to submit a draft of the thesis as a PDF file to the supervisor and to the evaluation committee.

Oral presentations will take 20 minutes plus 10 minutes of questions from the evaluation committee. **Oral presentations will be scheduled during the last week of June.**


Thesis report
-------------

There will be one single deadline for the submission of the thesis report. **The deadline is September 2nd.**

Prior to this deadline, the student has to submit the final version of the thesis as a PDF files to the supervisor and to the evaluation committee. Accordingly, the student and supervisor have to arrange that the supervisor has enough time to read and assess the final thesis text before the deadline.

After the submission, the MIIS commission will assess all documents and contact again the members of the evaluation committee to finalize the evaluation report and determine the final grade for the student. To facilitate the work of all parties involved we encourage that reports finished before the deadline are sent to the MIIS commission as soon as possible.


Formatting of the report
------------------------

As for the format of the written thesis (Font size, line spacing, margins, Section numbering etc) we propose that the students follow the A4 template provided by the Universitat Pompeu Fabra for Phd-theses (http://www.upf.edu/bibtic/en/guiesiajudes/eines/tesis/dina4.html#template). The MIIS board does not have any preference on the word processor and will accept documents written with any word processor, such as for example LaTex. As for the different parts of the thesis we also refer to the university guidelines for PhD-theses (cover page, abstract, table of contents, etc.). However, in contrast to these PhD-guidelines the Master thesis should have no prologue, and the abstract should be in English only. The length of the abstract can be up to 500-600 words.


Length and structure of the report
----------------------------------

The actual report can be structured according to Introduction, Methods, Results, Discussion. However, this is not mandatory. Different overall organizations of the report can be used, if necessary. As a general guideline we would like to indicate that a Master report is not supposed to reach the comprehensiveness of a PhD thesis. An adequate length of the thesis is between 20-40 pages (This page count assumes the format referred to above. This count includes the text, figures, figure captions, tables but excludes cover pages, abstract, acknowledgements, table of contents, references and also excludes technical appendices, such as for example programming source codes). The number of 20-40 pages is regarded as a guideline: If a student wants to write 50 pages instead, that is discouraged but perfectly tolerated. A longer report will not result in a lower grade. However, a report should have neither 5 nor 150 pages.

A **typical structure** of the final report of the thesis would be the following (CESIM):

    - Abstract
    - Keywords
    - Introduction
        - Problem statement
        - State of the art
    - Methods
        - Design & Development criteria and strategies
        - Experimental design and set-up
        - Procedures used to obtain data and results
    - Results
        - Key results obtained in the study
    - Discussion & Conclusion
        - How did the results address the problem defined
        - What are the problems faced by the study
        - Validity of the results
        - Relevance with respect to state of the art
        - Future steps


Schedule (CESIM)
----------------

The schedule associated to the steps followed in a master thesis are approximately as follows:

    - First days of October: Open house sessions from all the research groups related to our master
    - Mid-October: List of project proposals i published. Students start to talk to supervisors and groups
    - End of October: Students chose projects (their 5 top in preference)
    - Mid November: Projects are assigned to students. Students start their master thesis project
    - Start of January: Students deliver their state of the art
    - Start of March: Students make their mid-way presentations before an assessment board. Students receive feedback on their progress and suggestions to improve and succesfully finalise.
    - April: Students should have done their experimental work
    - May: Students perform their statistical analysis and evaluations.
    - June: Students correct any misalignments or extra needs. They start writing their master thesis report.
    - First week of July: Students deliver their final master thesis report and make their defence before an evaluation board to get their final grade.


Example Theses (CESIM)
----------------------

http://www.upf.edu/csim/information/thesis/


Thesis supervisors
------------------

http://www.upf.edu/iis/information/thesis/supervisors.html





