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
| Groupe | Jour | Horaire | Enseignant(s) |
|--------|------|----------|----------------|
| **G1** | Monday | 8:30–12:45 | Clara |
| **G2** | Wednesday | 8:30–12:45 | Rémy |
| **G3** | Thursday | 8:30–12:45 | Zakariae |
| **G4** | Thursday | 13:45–18:00 | Camélia (20 h) + Zakariae (20 h) |


## TME: General Organization
Each TME class is split in two parts: 
* The first 2 hours are devoted to a guided exercise
* The last 2 hours are devoted to the project.

The timing is relatively flexible, you can spend more or less time on each of the two parts, but do not neglect the first part. There is no evaluation on the first part. There are intermediate delivarable for the projects, detailed in the project section

## TME: Objectives
The objective of the guided part of the TME is to :
* Present concrete examples of the topics introduced in the lectures
* Provide example codes to get started
* Let you experiment on some simple data, to get familiar with the concepts

The objectives is NOT to teach you how to code some particular solutions. There are many ways to code the solution to a same problem and you are free to do it the way you want, including using AI or taking inspiration from existing code. The important part is  **understanding** what you are doing, and **finding efficient ways** to do what you want to do. For instance, learning how to read the documentation (of an API, of a library) is often more important than to know how to write some particular pandas transformation.

-------

# Project

The project is done in groups of 2 or 3 students. You can choose your groups freely. 

The objective of the project is to 1)choose a dataset, 2)ask one or a few questions relative to this dataset, and 3)try to answer it. Each part is important:

### The dataset
You have to build your own dataset. There are two main possibilities: 
* The first one is to use APIs and/or scrapping to build your own dataset from an accessible source. Usually it will not be just collecting one table from wikipedia, but rather collecting multiple several items and grouping them in a single database.
* The second one is to use an already existing dataset. This is allowed ONLY if the dataset 1)corresponds to real data, i.e., not a synthetically generated dataset 2)is complex enough to require preprocessing and analysis. For instance, a dataset with 300 observations and 5 variables is too simple. A complete dump of a large database such as the one from openfoodfacts, a large collection of playlists from spotify, or complete records of temperatures from europe, daily during 10 years, will represent a sufficient challenge to analyze. In each of these case, enriching the dataset from other sources is not only allowed, but encouraged. For instance, in the temperature dataset, you can search for additionnal information about cities such as their geographical positions, altitude, precipitations, avergage cloud covers, or any other information that you think can be relevant.

### The question(s)
You have to choose one or a few questions that are general questions about the world, and not specific to a dataset. For instance, examples of correct questions are:
* Where is climate change the strongest?
* Who is the most probable next president of France?
* What are the main factors driving the price of used cars?
etc.

Examples of questions that are not adapted are:
* What are the clusters of cities found on a dataset of climate change? (blindly applying methods to a dataset)
* What method gives the best result to predict used car prices? (blindly applying methods to a dataset)

Think of the process in that way:
1)Think about a question that interst you
2)Search for the data adapted to answer that question
3)Apply the various tools presented in the class to answer your question with your data

### FAQ
* _What if I don't know if I will find the correct data to answer my question?_
First make a quick check that some data exist. If yes, see answer to the next question
* _What if the question I asked is too difficult and I later realise that 1)I do not have the appropriate data, or 2)The problem is too complex to solve with the methods I learned in the class_
That is not a problem. You will not be evaluated on the correctness of the answer to your question. You will be evaluated on your capacity to apply the Data Analysis process described in the course: understand your data, its limits, prepare it correctly, apply adapted methods, interpret the results, etc. You might end-up answering only part of the question, or concluding that you need an additional information you do not have access to in order to answer your questions. But that can be a successful result, if you learned this by applying successfully the tools presented in the class to the best dataset you could collect in the time you had.
* _I don't know yet what we will learn in the class so I don't know yet what answer I will be able to answer_
That is true, but it is not a problem, see previous point. If you realize that the tools are more adapated to answer a related question, you can adapt your question, keeping the same idea.

### Deliverables
* 05/10 (10%): Question and Dataset (can be preliminary, i.e., can be udpated later)
* 02/11 (30%): EDA, Data description
* 30/11 (60%): Final Report

#### Deliverable 1
The first deliverable is composed of a 2 page report, containing 1)The question(s) the group will investigate, 2)The quantitative description of the dataset collected, with the description of the methods used to collect it. It will contain information such as the number of observations, the descriptions of the variables, etc.

#### Deliverable 2
The second deliverable will be a dashboard allowing to explore your dataset. In order to be easy to share and fast to use, it can be focused on a subset of the complete data, or on a transformed summary of your original data. The teacher should be able to run the dashboard easily. The dashboard must not be a simple collection of by-default visualization (e.g., distribution of each variable, default clustering and dimensionality reduction, etc.). The exploration and visualisation it proposes must be tailored to the dataset (e.g., a map for geographical data, choice of parameters that give relevant and readable results for a clustering/dimansionality reduction, etc.).
The dashboard does not have to be useful to answer the question yet, but it should be efficient to explore and understand the dataset.

#### Deliverable 3
The final report. It should contain a maximum of 2000 words, and a maximum of 12 pages including figures. It can be a PDF or an interactive HTML page. The obejctive is to have a clear, professional looking, data-based investigation of your question, that is easy to read. You can take inspirations from the following examples: [peak population](https://ourworldindata.org/which-countries-have-already-passed-peak-population-and-when-will-the-rest-do-so), [climate change and agriculture](https://ourworldindata.org/will-climate-change-affect-crop-yields-future)

----

# Note on AI tools
You are free, for the TME and for the project, to use AI tools. AI tools are very efficient at coding and often avoid the need to know the details of how to use a particular library, how to make a nice looking plot, etc.
However, be careful of the following:
* AI tools will only do what you ask. So you need to know what is possible to do or not to do in order to ask the right questions. Example, if you ask a plot and you do not know that it is possible to make it interactive, the AI will generate a static plot. It might also use a long and complex code using directly matplotlib instead of doing it in a few lines using the seaborn library.
* AI writes the code, but YOU are the person responsible for everything it writes. In a datamining pipeline, many decisions affect the results, and you MUST BE AWARE of these decisions. For instance, if you ask the AI to code a classification on some data, it will take many arbitrary decisions in the process, such as the fraction of the dataset used in train/test, the data transformation of each variable, that might or might not be documented (e.g., the AI cannot know that an integer column encode categorical variables, and thus treat it as numerical, a major error), the objective function, the parameter of the method used (e.g., in xgboosts, there are many parameters controlling regularization, number and size of the default trees, objective functions, etc.), number of repetitions of the experiments, etc. You MUST be aware of all these elements. You must know what is in your code. (It can be different for some other code productions such as generating the front-end of a website or a plot, where the result can be judge by simply looking at it. But in a datamining pipeline, it is impossible to judge the quality of the result by looking only at the result.) 
* AI generated code is often long and complex, thus difficult to maintain. I strongly recommend to use these tools to generate individual functions, step by step, rather to trust them on a full process. Later modifications and reading of long code written by AI in autonomy is often very difficult


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

## Dimensionality Reduction
* PCA
* FCA
* nonlinear transformations
* interpretation

## Storytelling  (?)
* What and Why ?
* Advanced Plots
* Dash

## Clustering 
* what is it
* k-means
* Gaussian Mixture
* DBSCAN - HDBSCAN

## ANOVA (?)
* Why ANOVA
* How does it work

## ML Protocol 1


## ML Protocol 2

## Interpretability
* Direct interpretation
* Post-hoc interpretation
* LIME-SHAP

## BIAS (?)
* LLM Bias

## From lab to production (Olivier Schwander)
### Contenu:
* Évaluation pour la production: monitoring continu, détection des attaques attaques et biais
* Méthodes: quelques mots sur les modèles de fondation et zero/few-shots
 et sur le fait qu'on peut souvent éviter un nouveau train mais pas une
 évaluation
* Outils: mlops avec mlflow, docker
