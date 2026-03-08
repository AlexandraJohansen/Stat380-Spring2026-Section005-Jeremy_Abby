---
title: "Activity #2: Applying Linear Regression Algorithms"
subtitle: "Group 10: Jeremy, Abi, Max"
author: "Abby Sine"
date: 02-22-2026
output: 
  html_document:
    toc: true
---

You and your team have been hired by the Nittany Valley Insurance Company to provide insight into how much an arbitrary health insurance policy might cost the company. You’ve been provided a data collection available for download: [Activity #2 Insurance Policy Data](https://psu.instructure.com/courses/2451788/files/189213964/download?download_frd=1) (note: clicking the link will initiate a download).

Within this data collection you’ll find information pertaining to:

-   The age of the primary beneficiary (in years)
-   The sex of the primary beneficiary
-   The body mass index of the primary beneficiary (kg/m\^2)
-   The number of children/dependents of the primary beneficiary
-   Whether the primary beneficiary is a smoker
-   Which of four US geographical regions the primary beneficiary lives in
-   The month in which the claim occurred
-   The number of claims made by the primary beneficiary in the prior fiscal year
-   The total charges billed to the policy (in US dollars)

# 1 Goal

Your goal is to build a predictive model for the charges based upon the available data using algorithms associated with linear regression.

# 2 Reporting

Your team will need to build a report that demonstrates that you’ve:

1.  Have investigated the data as fully as possible to help you build your understanding of the data.
    -   Possible Artifact: A description of the data that incorporates visualizations, descriptive/incisive statistics, and narrative text describing the data (i.e., EDA)
2.  The generation of at least two candidate models.
    -   Possible Artifact: Professional looking discussion of the candidate models and the process by which you arrived at them. All decisions should be documented and justified.
3.  Interpretations of Model Coefficients and Intercept
    -   Possible Artifact: Discussion of the candidate/final model
4.  Evaluation/Validation of the Candidate and Final Model(s)
    -   Possible Artifact: Build as complete of a body of evidence both for and against your candidate/final model.
5.  Final recommendation to the Nittany Valley Insurance Company.
    -   Possible Artifact: A paragraph to summarize your recommended model and key findings.

Your team should work together in as collaborative a manner as possible and be prepared to have create a single report. **All of your work should be documented and reproducible.**

## 2.1 What to Submit

Each group will need to submit the following:

1.  A typed report prepared using Quarto and knitted to PDF.
    -   DO NOT create PDFs by saving/printing an HTML file to PDF. Make sure your QMD file is appropriately setup to create a PDF.
2.  All group members need to be listed in the report twice.
    -   The first place is in the author line (via the YAML header). The second place is at the end where this is a detailed list of who did what in the report (Author Contributions/Responsibilities).
3.  The report needs to have a coherent structure.
4.  There should be no terminal output in the report.
    -   That is, anything that would be typically printed to the console when you run a command should not appear. For example, `summary(myModel)` prints to the console and should not appear. However, the information from this call is important and should be included. You just need to format the information. See the Linear Regression Guide for how. (Note: This guide is not meant to be an example of what your report should look like.)
5.  The Code Appendix (at the end of the report) should be the only place that raw code appears in your report.
6.  The report should address the prompt given (see the stated goal above).
7.  The report should mix data visualizations (plots, graphs, tables), values of statistics (descriptive, incisive, inferential–as applicable), and narrative text.
    -   The use of other kinds of images and figures is up to you. Such elements should serve to support and enhance your report, not just be decoration.

You do ***not*** need to worry about conducting any type of literature review or include references. You are welcome to do so but there are no points off for not doing this.

## 2.2 Example Coherent Structure

Here is **one** possible coherent structuring that you might wish to use for your report. I’ve set this up as a document outline.

I.  Introduction/Background
II. Data Exploration
III. Modeling
IV. Methods/Strategies
V.  Results
    I.  Initial Results
    II. Interpretations
    III. Model Evaluation
    IV. Refinements
VI. Final Recommendations
VII. Author Contributions/Responsibilities
VIII. Code Appendix

Using Section Headers in your document is a great way to help convey a coherent structure and organization.

There are many other ways in which you can organize your document as well as create a coherent structure to your analysis. Feel free to find one that works for your group.

## 2.3 A Final Check

When your team believes that you have reached your final model and you have finished making your body of evaluation/validation evidence, contact Abby and she will provide you with an additional check to run. This final check should be added into your results/evidence portion of your report.
