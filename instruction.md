# STAT 151A Final Group Project*

Fall 2025

The goal of the final project is to apply what you've learned in this course to conduct a statistical analysis. It should be an in-depth regression analysis of a question that interests your group. This question may come from one of your other courses, your research interests, your future career interests, etc.

You will work in groups of three to complete the project. It consists of three primary deliverableless:

- Project proposal (3% of course grade): due Friday November 14 at 11:59 PM PST.  
- Final project report (20% of course grade): due Friday, December 19 at 11:59 AM PST.  
- Self-evaluation (1% of course grade): due Friday, December 19 at 11:59 PM PST.

# 1 Data

It is best to start with the question of interest and find relevant data second. As you're looking for data, keep in mind your regression analysis must be done in R. Once you find a data set, you should make sure you are able to load it into R, especially if it is in a format we haven't used in class before. If you're having trouble loading your data set into R, ask for help as soon as possible, so you can make any necessary adjustments before the project proposal is due.

In order for you to have the greatest chance of success with this project it is important that you choose a manageable dataset. This means that the data should be readily accessible and large enough that multiple main effects and interactions can be explored for your model. As such, your dataset must have at least 100 observations and at least 10 variables (exceptions can be made but you must speak with me first). The data set should include both quantitative and categorical variables.

Please do not reuse datasets used in examples/homework/labs in class.

# 2 Data resources

- Duke University provides a guide to finding datasets for projects like this, with links to several possible data sources.  
- Google Dataset Search allows you to explore 25 million datasets from various sources using search filters.  
- The fivethirtyeight package in R contains 128 datasets on topics including politics, sports analytics, and popular culture.  
- TidyTuesday publishes a new dataset every week, as well as a list of links to data portals from news organizations.

- The UC Irvine Machine Learning Repository provides 557 datasets and a searchable interface.  
- Kaggle maintains a large collection of datasets published by users.

If you identify other interesting data sources you are strongly encouraged to share them with your classmates on Ed.

# 3 Detailed timeline and deliverables

- Tuesday October 13: project groups formed. You may propose your own groups of exactly three through this date by signing up here. You are encouraged to use Ed to share your project ideas and form groups. Forming your own group is optional. If you do not wish to find your own group or have difficulty forming one, you may request to be placed in a group by course staff. You can do this by entering your name on the online form here. Additional groups will be formed at random from those who submit their names using the form.  
- Friday November 14: project proposals due 11:59 PM. The proposal is a draft of the introduction section of your project as well as a regression analysis plan and evidence that you can load the needed data into R. The proposal should be no more than 3 pages (excluding appendices). Please submit only one document per group to Gradescope, tagging all group members.

You will receive written feedback on this proposal from the professor or the GSI. After writing the initial proposal, if you do not think your group will work together well this is the best time to come to me because I can reassign people and form new groups. After this point, it will be difficult to change the project members.

- Friday December 19: final project due 11:59 AM. The purpose of the report is for you to demonstrate your ability to ask meaningful questions and answer them with the results from regression analysis, and your proficiency in using R and in interpreting and presenting results. Focus on methods that help you begin to answer your research questions. You do not have to apply every statistical procedure we learned. Also pay attention to your presentation. Neatness, coherency, and clarity will count.

At a minimum, your report should have the following sections: an introduction, a section describing your final regression model, a discussion section outlining conclusions drawn from the model and limitations of the analysis, a conclusion summarizing the main findings in answer to the research question, an additional work section describing other models and diagnostics you tried, and a references section listing the sources you used. The first four sections should be no more than 3 pages in total, and the "additional work" section should be no more than 5.

At the end of your report, you should include a code appendix containing all the R code used to conduct your analysis. You may either append the entire .Rmd source, or extract the code chunks and present them separately. The code appendix will not count toward the page limit. Please submit only one document per group to Gradescope, tagging all group members.

- Friday December 19: self-evaluation due 11:59 PM. Each member of the group must individually submit a description of how the work was distributed throughout the project. You should be specific about how you decided to organize the work and what each group member contributed. These reports do not need to be formal, and should only be 1-2 paragraphs.

# 4 Assessment

The proposal and final report will be graded holistically. Below we provide the rubrics used to do this grading; for each assignment, each part of the rubric receives an equal weight in the grade. In addition,

if the end-of-project self-evaluations show highly disproportionate distribution of effort among members within a group, grades may be adjusted to reflect this.

# Proposal rubric:

- Research question and data: Is a research question chosen and clearly defined? Is the question challenging, interesting, and specific? Is a specific dataset identified that is relevant for this question, and can the group load it successfully in R in a usable form?  
- Choice of analysis: Is the model and analysis chosen relevant to the research question? Does it make effective use of the data in hand? Is a clear plan given for making modeling choices and assessing assumptions, with attention to the broader scientific context?  
- Clarity and concision: Is the report organized logically with a clear structure? Are individual steps in the analysis explained clearly? Is writing concise and grammatically correct? Are length and formatting requirements observed?

# Final report rubric:

- Choice of analysis: Is an appropriate research question chosen and clearly defined? Is the model and analysis chosen relevant to the research question? Does it make effective use of the data in hand? Are modeling choices and assumptions properly justified with reference either to the data itself (e.g. through diagnostics or exploratory data analysis) or to the broader scientific context?  
- Interpretation and evaluation: Is model output interpreted correctly? Are conclusions justified by specific results from the analysis? Are weaknesses of the approach and alternate explanations or methodologies considered and discussed?  
- Computations: Are computations and calculations performed correctly? Are they documented clearly but concisely? Is code (in code appendix) complete and well-structured, using appropriate naming, formatting, and syntax?  
- Visual presentation: Do plots and figures convey important information that contributes to the central arguments of the report? Are plots and figures labeled appropriately and referred to effectively in the text?  
- Clarity and concision: Is the report organized logically with a clear structure? Are individual steps in the analysis explained clearly? Do conclusions drawn from the data analysis respond meaningfully to the research question? Is writing concise and grammatically correct? Are length and formatting requirements observed?