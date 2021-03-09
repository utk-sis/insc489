# INSC 489 - 21Spring - Project Proposal

# General Project Instructions and Requirements

Please read [final project instructions](https://github.com/utk-sis/insc489-21Spring/blob/main/project/final-project-instructions.md).

# Submission

Submit your project proposal as a [markdown document](https://guides.github.com/features/mastering-markdown/) (recommended) or a pdf to the GitHub repo for your project by Mar 17, Wed, 11:59pm. The file name should be "proposal.md/pdf"

GitHub invitation: https://classroom.github.com/a/-tRvZPwb

You will use the repo to submit all of your project deliverables.

# Project Proposal Requirements

1. Project Title
2. Overview
3. Description of the data
4. Usage scenario & tasks

The narrative of your proposal should be precise and brief. No more than 1,000 words.

## Section 2: Overview

A few sentences that describe what problem your visualization is tackling and how. You may choose to tell an interactive data-driven story intended to be consumed by the general public. The theme of your visualization can draw from any topic, including current affairs, history, natural disasters, and research findings from the sciences and humanities. State the intended audience. Be brief and clear.

Example:

> Missed medical appointments cost the healthcare system a lot of money and affects the quality of care. If we could understand what factors lead to missed appointments it may be possible to reduce their frequency. To address this challenge, I propose building a data visualization that allows health care administrators to visually explore a dataset of missed appointments. My app will use show the distribution of factors contributing to appointment show/no show and allow users to explore different aspects of this data by filtering and re-ordering on different variables in order to compare factors that contribute to absence.

## Section 3: Description of the data

You can choose any public open dataset. You may find one of these resources useful:

- [Kaggle Datasets](https://www.kaggle.com/datasets)
- [Goolge Dataset Search](https://datasetsearch.research.google.com/)
- [Data is Plural](https://tinyletter.com/data-is-plural/letters/data-is-plural-2021-03-03-edition)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)

The dataset should be complex and challenging enough to an interesting final project.

To ensure everyone has different project dataset, please **list your dataset on this Canvas page** :

[https://utk.instructure.com/courses/121275/pages/data-selection](https://utk.instructure.com/courses/121275/pages/data-selection) 

(You can edit this page by clicking Edit button on the page.)

In your report, briefly describe the dataset and the attributes that you will visualize. Provide a link to your data sources. Include the cardinality of the entire dataset (total number of items), the types of the attributes, and the cardinality for categorical attributes or the range for quantitative/ordered attributes.

Please note, if your dataset has many more than 20 attributes and you plan to visualize them all, then you may provide a high level descriptor of groups of attributes, for example say the dataset contains demographic attributes instead of describing every single variable.

Example:

> I will be visualizing a dataset of approximately 300,000 missed patient appointments. Each appointment has 15 associated attributes that describe the patient who made the appointment (PatientID [categorical, 300K levels], Gender [categorical, 2 levels], Age [ordered, 0-105]), the health status of the patient (Hypertension, Diabetes, Alcohol intake, physical disabilities [all categorical & binary]), information about the appointment itself (appointment ID [categorical, 300K levels], appointment date [ordered, 1/1/2010- 12/31/2016]), whether the patient showed up (status [categorical & binary]), and if a text message was sent to the patient about the appointment (SMSsent [categorical & binary]). Using this data I will also derive a new variable, which is the predicted probability that a patient will show up for their appointment (ProbShow [quantitative, 0.0-1.0]).

In the above example, specific attribute names are indicated in the parenthesis. The example also differentiates attributes that come with the dataset (i.e. Age) from new attributes that you might derive for your visualizations (i.e ProbShow) - you should make a similar distinction in your write-up.

## Section 4: Usage scenarios & tasks

The purpose of the usage scenario is to get you to think about how someone else might use the web application you're going to design, and to think about those needs before you start hacking. Usage scenarios are typically written in a narrative style and include the specific context of usage, tasks associated with that usage context, and a hypothetical walkthrough of how the user would accomplish those tasks with your visualization. If you are using a Kaggle dataset, you may use their "Overview (inspiration)" to create your usage scenario, or you may come up with your own inspiration.

Example usage scenario with tasks (tasks are indicated in brackets, i.e. [task]):

> Mary is a policy maker with the Canadian Ministry of Health and she wants to understand what factors lead to missed appointments in order to devise an intervention that improves attendance numbers. She wants to be able to [explore] a dataset in order to [compare] the effect of different variables on absenteeism and [identify] the most relevant variables around which to frame her intervention policy. When Mary logs on to the "Missed Appointments app", she will see an overview of all the available variables in her dataset, according to the number of people that did or did not show up to their medical appointment. She can filter out variables for head-to-head comparisons, and/or rank order patients according to their predicted probability of missing an appointment. When she does so, Mary may notice that "physical disability" appears to be a strong predictor missing appointments, and in fact patients with a physical disability also have the largest number of missed appointments. She hypothesizes that patients with a physical disability could be having a hard time finding transportation to their appointments, and decides she needs to conduct a follow-on study since transportation information is not captured in her current dataset.

Note that in the above example, "physical disability" being an important variable is fictional - you don't need to conduct an analysis of your data to figure out what is important or not, you just need to imagine what someone could find, and how they may use this information.