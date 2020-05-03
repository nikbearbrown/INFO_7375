# INFO 7375   
INFO 7375 - Special Topics in Artificial Intelligence Engineering Computational Skepticism   

In this seminar we do research in Computational Skepticism, that is, building systems to answer the question "Why Should I Trust an Algorithms Predictions?”   

As a group, students and any collaborators will be writing a book called "Computational Skepticism." Small groups of students will collaborate on writing a chapter. Two students have already started on their chapter on model interpretability, so you can see what the beginnings of this process looks like here [https://maheshwarappa-a.gitbook.io/ads/](https://maheshwarappa-a.gitbook.io/ads/)  

Once completed the Computational Skepticism book will be available for free online and published with an ISBN through the Banataba project through a publishing site such as https://www.Blurb.com.


_What is Computational Skepticism?_   
 
Evidence, as broadly construed, is anything presented in support or opposition of an assertion. Creating an automated skepticism pipeline is intended to do three things: 1) accumulate as much evidence for an assertion or question as it can in an automated way, 2) store and search that data and 3) present and visualize that data in an understandable manner.

There are many forms of evidence in machine learning, all of which are active areas of research. The goal of Computational Skepticism is to automate the best practices in all of these areas of research into a single, intuitive framework. The forms of automated evidence gathering to be studied include: data quality and completeness, bias and fairness ,  AutoML, model interpretability, causal inference, counterfactual models, deep learning pipelines (AutoDL), time-series pipelines (AutoTS), feature engineering pipelines  AutoFE), autovisualization (AutoViz), reinforcement learning pipelines (AutoRL), evidence knowledge graphs (EKG) and many more.



_Course Description_    

‘Trust but verify,’ is a proverb that should be a mantra for the age of artificial intelligence. Despite their widespread adoption, machine learning models remain mostly black boxes. In spite of this, many who use machine learning to make critical predictions in domains such as finance, telecommunication, healthcare, and many other domains don’t fully understand how machine learning models make their predictions.

In this research, seminar we do research in Computational Skepticism, that is, building systems to answer the question "Why Should I Trust AI?”.   Computational Skepticism a process of obtaining knowledge through automating systematic doubt and continual testing. The word Skepticism comes from the Greek skeptomai, or to search for alternative possibilities.  

As engineering research, the focus is building systems that can be used to transform untrustworthy models into a trustworthy ones. To accomplish this there are a number of
component subprojects using techniques from probability, deep learning, reinforcement learning, machine learning, and data visualization. Students are expected to pick a single subproject within the first two weeks. All students should have a strong programming background. The sub-projects typically require some knowledge of either probability, deep learning, reinforcement learning, machine learning or data visualization. The approval of a student’s choice of subproject will depend on the student's interest and background. The current list of projects and associated code is kept at the INFO 7375 GitHub https://github.com/nikbearbrown/INFO_7375   

Students present their research every two to three weeks.  


_Research Seminar Courses_   

This course is a Research Seminar that is intended to guide students through the conceptualization, planning, and execution of a major original project in Artificial Intelligence, Machine Learning, Data Visualization or Reinforcement Learning. 

The goals of the Research Seminar are:

1. To provide students with additional training in research design, research methods, and effective writing;     
2. To guide students through the process of conducting original research and analysis, leading to the production of substantial, professional-quality papers. This course also helps students recognize common research mistakes and biases, while learning more about what constitutes strong research; and     
3. To help students develop their abilities to constructively critique and contribute to the work of others.    
 

_Course Prerequisites_

Students only can enroll through the approval of the instructor. Students must have either 1) done successful research previously with Professor Nik Bear Brown, or 2) will be given a challenge to assess the student's ability and desire to do research.


_Course Schedule_    


This is a seminar class. The literature is read and presented every week. Students present their research every two to three weeks. The beginning of each week will introduce new theory. The focus for Summer 2020 is parts one through four below.  Advanced students have the option of working on any of the parts below.

Companies that have applications and research related to Computational Skepticism will be invited from time to time. 

*Part 0  Assertions and Questions*     
A preface to the course discusses how to formulate questions and assertions.

*Part I  Data*   
The first part discusses understanding data quality, bias, and predictive value so that automated pipelines can be built that assess the quality of a dataset and its appropriateness to answer an assertion. Feature engineering is also discussed. Technqiues include descriptive statsitics, data auditing, exploratory data analysis (EDA), resampling methods.

*Part II  Bias and Fairness*  
Discrimination is the unequal treatment of individuals or groups. While algorithms are blind, unintentional unfairness often creeps into the decisions they suggest, particularly in "black box" models. This part discusses how bias can be introduced into the machine learning pipeline, what it means for a decision to be fair, and methods to remove bias and ensure fairness.

*Part III  Models* 
The third part discusses building automated pipelines that build models to answer an assertion, evaluating the best models for a given purpose and selecting the most appropriate parsimonious models. The focus is on Automated machine learning (AutoML) is the process of automating the process of feature selection, algorithm selection, hyperparameter optimization, metric selection and creating stacked ensembles.
Technqiues include feature selection, algorithm selection, hyperparameter optimization, metric selection and stacked ensembles.
The base algorithms included are Distributed Random Forest (DRF), Extremely Randomized Trees (XRT), Generalized Linear Model (GLM), Generalized Additive Model (GAM), Gradient Boosting Machine (GBM), XGBoost, and Simple Deep Learning (MLP Neural Networks)

*Part IV  Model Interpretability*  
The fourth part discusses building automated pipelines that allow a human to understand the logic and process that a model uses to answer an assertion. This is model interpretability which refers to how easy it is for humans to understand the processes a model uses to arrive at its outcomes.
Technqiues include individual conditional expectation (ICE), leave-one-covariance (LOCO), local feature importance, partial dependency plots, tree-based feature importance, standardized coefficient importance, accumulated local effects (ALE) plots and Shapley values. .
The output of a model interpretability pipeline is as follows:
A Model Schematic Diagram that visualizes all of he steps that each model uses to arrive at its outcomes.
Plots that show the outcome of model interpretability algorithms such as feature importance. partial dependency plots, etc.
A Feature Knowledge Graph with compares illustrates feature importance and interrelationships.
A Data Sensitivity Graph which exposes the effect of adding noise the data on the robustness of a model and the sensitity of individual features.

_Advanced Topics_   
Advanced Topics (These topics will not be presented as part of a structured lecture but advanced students are encouraged to present the literature in the student presentations related to their research topic). I  will be looking for experts in these areas of research. The presentations by experts won’t necessarily follow any particular order but be scheduled according to the external researchers schedules.
  
*Part V  Causal Inference*        
The fifth part is causal inference, in the conext of builing automated pipeline for understanding causation. Causal inference is the process of drawing a conclusion about a causal connection based on the conditions of the occurrence of an effect. The main difference between causal inference and inference of association is that the former analyzes the response of the effect variable when the cause is changed.  In this part we discuss causal methods as compared to traditional statistical methods.

*Part VI  Counterfactual Models*  
The sixth part discusses building automated pipelines that build counterfactual simulations and use causal methods to ask “what if” questions. Technqiues include causal inference, agent-based modeling and reinforcement learning.

*Part VII  Deep Learning Pipeline (AutoDL)*  
The seventh part is an extension of AutoML discussed in part two to use more soptisticated deep learning models like CNNs, RNNs, Gauge-equivariant convolutional neural networks (Gauge CNNs) or other deep learning models.

*Part VIII  Time-Series Pipeline (AutoTS)*  
The eigth part is an extension of AutoML discussed in part two to use time series models like ARIMA, VARMA, RNNs, fbProphet, etc. 

*Part IX  Feature Engineering Pipeline (AutoFE)*  
The ninth part is an extension of AutoML for automated feature extraction.

*Part X  Autovisualization (AutoVIZ)*  
The tenth part is the integration of machine learning and data visualization to automatically rank and generate relevant plots for a data set.

*Part XI  Reinforcement Learning Pipeline (AutoRL)*  
The eleventh part discusses building automated pipelines that answer optimization questions.  The model behind reinforcement learning presupposes one has some form of signal, such as the state of a game board, or the sensors attached to a self-driving car. The central problem that reinforcement learning is intended to solve what is the optimal action to take, given a signal and some objective or reward. For example, what move to make to do well in a game, or what actions to take to not crash a car and get to some destination within any rules of the road.
The AutoRL project is to build automated pipelines for reinforcement learning.

*Part XII  Evidence Knowledge Graphs (EKG)*  
The twelth part discusses building Knowledge Graphs. A Knowledge Graph is a network database using information gathered from a variety of sources to present information on a topic or thing and its relations with other things.
For example, a knowledge graph could not only collect facts about an algorithm such as its hyperparameters as one would get in documentation but the distribution of hyperparameter values extracted from its data sources.
It can so "similar" algorithms and which algorithms are used for particular problems. Google used its Knowledge Graph for answering "roughly one-third" of the 100 billion monthly searches Google processed in May 2016. 
Knowledge Graphs allow for the addition of "wisdom of the crowds" based evidence into a skeptical framework. Look at the references of the GitHub page under the topics Knowledge Graphs and Collective Intelligence for more information.




_INFO 7375 - Computational Skepticism Schedule_  

*Week of May 4*  

(Tuesday, May 5) Cinco de Mayo   
Note: Given the course is online, you will have to supply your own tacos on Taco Tuesdays.   

What is Computational Skepticism?  

What is the course about? Go over the syllabus.    
The main point - you will contribute to writing a chapter in a book on Computational Skepticism should you choose to stay in the course.  

What Static Site Generators (see https://www.staticgen.com) will we use? I'm thinking of using GitBook, Jekyll, or Github pages.  

Two students (Abhishek Maheshwarappa and Kartik Kumar) have already started on their chapter on model interpretability [https://maheshwarappa-a.gitbook.io/ads/](https://maheshwarappa-a.gitbook.io/ads/)

We will discuss and critique the chapter.



Show and Tell #1 (Thursday, May 7) (Counts towards participation grade)

Bring in a review article discussing one of the following subjects: data quality and completeness, bias and fairness, AutoML, model interpretability, causal inference, counterfactual models, deep learning pipeline (AutoDL), time-series pipeline ( AutoTS), feature engineering pipeline (AutoFE), autoVisualization ( AutoViz), reinforcement learning pipeline (AutoRL), or evidence knowledge graphs (EKG).    

For example, this article discusses bias and fairness [https://www.borealisai.com/en/blog/tutorial1-bias-and-fairness-ai/ ](https://www.borealisai.com/en/blog/tutorial1-bias-and-fairness-ai/)    

Present the article to the group in 10 minutes.  










