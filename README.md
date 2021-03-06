# Matplotlib Homework - The Power of Plots

## Background

What good is data without a good plot to tell the story?

So, let's take what you've learned about Python Matplotlib and apply it to a real-world situation and dataset:

![Laboratory](Images/Laboratory.jpg)

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Obersvations & Insights

My observations of this study are as follows:

* Most statisticians agree that the minimum sample size to get any kind of meaningful result is 100. In the case of this study, we had exactly 100.

* Both Capomulin and Ramicane seemed neck-and-neck in terms of affectiveness; both these drugs Final Tumor Size was near identical, however it is worth noting
  that the Starting Tumor Size for each respective was not. We would need an identical Starting Tumor Size to be asbolutely sure of affectiveness.

* An R-square of 0.84 suggests that their is compelling evidence that mouse weight correlates strongly vs. the Average Tumor Size.

* Continuing the treatment of mice (who's drug were Capomulin and Ramicance) would help determine whether these respective drugs could totally eradicate the tumors, or whether tumor shrinkagw plateaus, before the tumor is completely 'cured.