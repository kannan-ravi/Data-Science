# Analysis for Suicides in India form 2001 to 2012
## Introduction

Suicide is the most common reason for death in India. Every year the suicide rate is increasing dramatically. So analyzing suicide in India is an interesting and knowledgable one.

We have a dataset from *Kaggle*, from the range of 2001 to 2012 for every 28 states and every 7 union territories. And *Telangana* becomes a state in India in 2014 so we don't have the data for *Telangana.*

This dataset contains *237,519 rows* and *7 columns*:
* **State** - Contains the name of each State and Union Territory in India
* **Year** - Contains every year from 2001 to 2012
* **Type Code** - It contains the value that explains the what the Type is like if Type explains about the causes for suicide, Type code contain Causes heading
* **Type** - This column contain, why the people die, what are their educational qualification, about their social status, and professional profile
* **Gender** - This column contains values about their gender Male or Female
* **Age Group** - This column contain values about their age
* **Total** - This column contains, the total value of how many people suicide.

We are going to analyze this dataset to understand what was going on there, why people decide to end their life, what are the reasons, and many more. In a nutshell, we are going to understand this data from very top to bottom using Python

For understanding the data, we are going to use some of the libraries or frameworks or modules whatever you want to name it.

* **opendatasets** - opendatasets is the tool to download the Kaggle dataset from the website with one click
* **NumPy** - NumPy is used for numerical computing in the dataset
* **Pandas** - Pandas is the most popular tool for analyzing the Tabular Data and Pandas was built on NumPy
* **Matplotlib** - Matplotlib the basic tool to visualize the database, This can be useful for basic plotting
* **Seaborn** - Seaborn is the advanced tool for visualizing the data with easy steps, Seaborn is built on Matplotlib

