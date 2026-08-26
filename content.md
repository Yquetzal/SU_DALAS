# Lectures: Overview, Schedule and Teachers

* 14/09 - Intro + data collection(RC)
* 21/09 - EDA + Dash(RC)
* 28/09 - BD1 (CC)
* 05/10 - BD2 + Storytelling (CC)
* 12/10 - Clustering(RC)
* 19/10 - Dimensionality Reduction(RC)
* 02/11 - ML Protocol-1(CBM)
* 09/11 - ML Protocol-2(CBM) 
* 16/11 - Interpretability - Bias (RC)
* 23/11 - From lab to Production - MLops(OS)

---------------
# TME

## TME: Groups and Teachers
| Group | Day | Time | Teacher(s) |
|--------|------|----------|----------------|
| **G1** | Monday | 8:30–12:45 | Clara |
| **G2** | Wednesday | 8:30–12:45 | Rémy |
| **G3** | Thursday | 8:30–12:45 | Zakariae |
| **G4** | Thursday | 13:45–18:00 | Camélia (20 h) + Zakariae (20 h) |


## TME: General Organization

Each TME session is split into two parts:
* The first 2 hours are devoted to a guided exercise.
* The last 2 hours are devoted to the project.

The timing is relatively flexible: you may spend more or less time on each part, but do not neglect the first one. There is no evaluation for the guided exercise. There are intermediate deliverables for the project, detailed in the project section.

## TME guided part: Objectives

The objectives of the guided part of the TME are to:
* Present concrete examples of the topics introduced in the lectures.
* Provide example code to help you get started.
* Let you experiment with simple datasets to become familiar with the concepts.

The objective is **not** to teach you how to code a particular solution. There are many ways to solve the same problem, and you are free to implement your solution however you like, including using AI or taking inspiration from existing code. The important part is **understanding** what you are doing and **finding efficient ways** to achieve your goal. For instance, learning how to read the documentation of an API or a library is often more valuable than knowing how to write a particular pandas transformation.

## TME guided part: contents
* Week 1 - Data collection (scraping, APIs), missing data, outliers
* Week 2 - EDA + Dash
* Week 3 - BD1
* Week 4 - BD2
* Week 5 - Clustering
* Week 6 - Dimensionality Reduction
* Week 7 - ML Protocol-1
* Week 8- ML Protocol-2
* Week 9 - Interpretability - Bias
* Week 10 - PROJET
-------

# Project

The project is carried out in groups of 2 or 3 students. You are free to choose your group.

The objective of the project is to:
1. choose a dataset,
2. formulate one or several questions related to this dataset,
3. try to answer them.

Each part is important.

### The dataset

You have to build your own dataset. There are two main possibilities:

* The first is to use APIs and/or web scraping to build your own dataset from one or several accessible sources. Usually, this means more than simply collecting a single table from Wikipedia: you should collect multiple items and combine them into a single dataset.

* The second is to use an existing dataset. This is allowed **only if** the dataset:
  1) contains real-world data (i.e., it is not synthetically generated), and
  2) is complex enough to require meaningful preprocessing and analysis.

  For instance, a dataset with 300 observations and 5 variables is too simple. In contrast, a complete dump of the OpenFoodFacts database, a large collection of Spotify playlists, or daily temperature records across Europe over ten years would all represent sufficiently challenging datasets.

  In all of these cases, enriching the dataset with information from other sources is not only allowed but encouraged. For example, for the temperature dataset, you could collect additional information about cities such as their geographical coordinates, altitude, precipitation, average cloud cover, or any other variables that you think may be relevant.

### The question(s)

You have to choose one or several questions about the real world, rather than questions about the dataset itself.

Examples of appropriate questions include:

* Where is climate change the strongest?
* Who is the most likely next President of France?
* What are the main factors driving used car prices?

Examples of questions that are **not** appropriate include:

* What clusters of cities can be found in a climate change dataset? (blindly applying methods to a dataset)
* Which method gives the best predictions for used car prices? (blindly comparing methods)

Think about the process this way:

1. Think of a question that interests you.
2. Search for data suitable for answering that question.
3. Apply the tools presented in the course to answer it.

### FAQ

**_What if I don't know whether I will be able to find the data needed to answer my question?_**

First, make a quick check that such data exist. If they do, see the next question.

**_What if I later realize that 1) I do not have the appropriate data, or 2) the problem is too complex to solve with the methods learned in class?_**

That is not a problem. You will **not** be evaluated on whether you successfully answer your question. You will be evaluated on your ability to apply the data analysis process presented in the course: understanding your data and its limitations, preparing it correctly, applying appropriate methods, interpreting the results, etc.

You may end up answering only part of your question, or concluding that additional information would be required to answer it completely. That can still be a successful project, provided that you reached this conclusion by correctly applying the tools presented in class to the best dataset you were able to collect.

**_I don't know yet what we will learn during the course, so I don't know what questions I will be able to answer._**

That is true, but it is not a problem (see the previous point). If, during the semester, you realize that the methods presented in class are better suited to answering a related question, you are free to refine or slightly modify your research question while keeping the same overall objective.

### Deliverables

* **05/10 (10%)**: Research question and dataset (preliminary version; both may be updated later)
* **02/11 (25%)**: Dashboard for exploratory data analysis
* **30/11 (65%)**: Final report

#### Deliverable 1

The first deliverable consists of a two-page report containing:

1. the research question(s),
2. a quantitative description of the collected dataset, together with a description of the data collection process.

It should include information such as the number of observations, the variables collected, their meaning, and any relevant preprocessing already performed.

#### Deliverable 2

The second deliverable is a dashboard for exploring your dataset.

To make it easy to share and fast to use, it may focus on a subset of the data or on a transformed summary of the original dataset. The teacher should be able to run the dashboard easily.

The dashboard should **not** simply display default visualizations (e.g., distributions of every variable, default clustering, or default dimensionality reduction). Instead, the proposed visualizations should be tailored to your dataset (for example, using maps for geographical data, or choosing clustering and dimensionality reduction parameters that produce meaningful and readable results).

The dashboard does not yet need to answer your research question, but it should make the dataset easy to explore and understand.

#### Deliverable 3

A visual report.

The report should contain **at most 2,000 words** and **at most 12 pages, including figures**. It may be provided either as a PDF document or as an interactive HTML page (which prints in approximately less than 12 pages).

The objective is to produce a clear, professional-looking, data-driven investigation that is pleasant to read.

You may take inspiration from the following examples:

* [peak population](https://ourworldindata.org/which-countries-have-already-passed-peak-population-and-when-will-the-rest-do-so)
* [climate change and agriculture](https://ourworldindata.org/will-climate-change-affect-crop-yields-future)
* [student population in the UK](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/livebirths/articles/howhasthestudentpopulationchanged/2016-09-20)

Additionally, you must provide:

1. all the code used to generate the elements included in the visual report;
2. a technical report describing aspects that are not discussed in the visual report, such as data preparation, implementation details, parameter choices, and other technical decisions.

The final grade for this deliverable will be the average of two components:

1. the quality of the final report (report itself, figures, research question, choice and correct application of methods, interpretation of results, quality of the data, etc.);
2. an overall evaluation of the work carried out during the semester, based on weekly discussions with the teacher, the quality of the code produced, and your involvement in the project sessions.

**Students who do not attend the project sessions may therefore receive a grade of zero for the second component, even if they submit an excellent final report.**

----
# Note on AI Tools

You are free to use AI tools, both during the TME sessions and for the project. AI tools are very effective at coding and can often remove the need to know the details of how to use a particular library, how to produce a nice-looking plot, etc.

However, keep the following points in mind:

* **AI tools will only do what you ask them to do.** You therefore need to know what is possible in order to ask the right questions. For example, if you ask for a plot but do not know that it can be made interactive, the AI will probably generate a static plot. It might also produce long and complex code using `matplotlib` directly when the same result could be obtained in a few lines with `seaborn`.

* **AI writes the code, but YOU are responsible for everything it does.** In a data mining pipeline, many decisions can affect the results, and you **MUST BE AWARE** of these decisions. For instance, if you ask an AI to implement a classification pipeline, it may make many arbitrary choices, such as:
  - the fraction of the dataset used for training and testing;
  - the transformations applied to each variable;
  - how variables are interpreted (e.g., an integer column may actually encode categorical values, but the AI may incorrectly treat it as numerical);
  - the objective function;
  - the parameters of the chosen method (e.g., XGBoost has many parameters controlling regularization, the number and depth of trees, the objective function, etc.);
  - the number of repetitions of the experiment.
  - etc.

  You must understand these choices and know what is happening in your code.

  Note: This requirement may be less important for some types of code, such as generating the front end of a website or adjusting the appearance of a plot, where the quality of the result can often be assessed simply by looking at it. In a data mining pipeline, however, it is generally impossible to assess the validity of the analysis from the final output alone.

* **AI-generated code is often unnecessarily long and complex, which makes it difficult to understand and maintain.** I strongly recommend using these tools to generate or improve individual functions and small pieces of code step by step, rather than asking them to produce an entire analysis pipeline autonomously. Reading, debugging, and modifying a large amount of AI-generated code afterwards can be very difficult. Demonstrating that you have a good knowledge of what your code is doing will be part of the evaluation.


--------

# Syllabus of the classes (work in progress)

## Intro + data collection
* Presentation of class content, evaluation, etc.
* Data Science, Data Mining, Machine Learning: What, Why, How ?
* Data collection: scrapping
* Data collection: API
* Project Présentation
* AI and Data Mining - AI and the class

## EDA
* Why EDA
* Types of data
* Dataframes
* Preprocessing
* Plots
* Missing data + imputation
* Outlier detection

## BD1

## BD2

## Dimensionality Reduction
* PCA
* FCA
* nonlinear transformations
* interpretation

## Clustering 
* what is it
* k-means
* Gaussian Mixture
* DBSCAN - HDBSCAN

## ML Protocol 1


## ML Protocol 2

## Interpretability - Bias
* Direct interpretation
* Post-hoc interpretation
* LIME-SHAP
* LLM Bias

## From lab to production (Olivier Schwander)
### Content

* **Evaluation in production:** continuous monitoring, attack detection, and bias detection.
* **Methods:** a brief introduction to foundation models and zero-/few-shot learning, and why fine-tuning can often be avoided whereas evaluation remains essential.
* **Tools:** MLOps with MLflow and Docker.
