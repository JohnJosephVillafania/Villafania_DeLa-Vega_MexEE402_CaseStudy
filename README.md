# MexEE 402: Data Preprocessing Case Study

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## Members

| Name | Student Number | Section |
|---|---|---|
| Villafania, John Joseph| 22-03102|MEXE-4103 |
| De La Vega, Wincy | 22-03102|MEXE-4103 |

## Notebook links

| Chapter | Villafania, John Joseph | DeLa Vega, Wincy|
|---|---|---|
| Ch1_2_3 | [Ch1_2_3_Villafania_DeLa Vega](https://colab.research.google.com/drive/1tm_Myp5_0fCUcHYmF5ctf-7Rvn10UXLX?usp=drive_link) | [link]() |
| Ch4 | [Ch4_Villafania_DeLa Vega](https://colab.research.google.com/drive/1yQWjCi5YbevDfX7wirgD8sZ-esXaM_gm?usp=drive_link) | [link]() |
| Ch5 | [Ch5_Villafania_DeLa Vega](https://colab.research.google.com/drive/1qfbPhtMaFq0baRtYH_cmH-3yI7hEvi2H?usp=drive_link) | [link]() |
| Ch6 | [link]() | (https://colab.research.google.com/drive/183K6aYaUs_dveQ27C5JiO9L6m9lb9vUG#scrollTo=xw-ulSLhnqbd) |
| Ch7 | [link]() | (https://colab.research.google.com/drive/1mJO1qrH2w9SYjA-TQhIUeF3nJ3vFqK8n#scrollTo=BqyCrcWOwGRZ) |
| Ch8 | [link]() | (https://colab.research.google.com/drive/14KXqovNIiOHcwa0oW5ZjkXPdz6tL0zdV#scrollTo=lLq58yLJw8jx) |
| Ch9 | [link]() | (https://colab.research.google.com/drive/1MOw_ygW3VIgCDclmLpRFZlzoDhgDHKea#scrollTo=yrCa6D0Z2vuX) |

## What we learned

<h1 align="center">
<b>CHAPTER 1_2_3</b>
</h1> 

 Ch1_2_3 taught us that data preprocessing is an important step in making raw data useful and reliable because real-world data can contain missing, inconsistent, or unnecessary information. We learned that cleaning and organizing data before analysis can improve the quality of results and make patterns easier to understand. What surprised us most was how missing or messy data can greatly affect the accuracy of the final analysis or model, even before any machine learning is done.

<h1 align="center">
<b>CHAPTER 4</b>
</h1> 

 Chapter 4 demonstrated that feature engineering helps turn simple raw data into more useful information that can reveal patterns and relationships. We learned that combining or transforming features can give a clearer understanding of the data, while encoding allows categorical information to be used properly. What surprised us most was that the way we represent data, such as using one-hot or ordinal encoding, can affect how a model understands the information.
 
<h1 align="center">
<b>CHAPTER 5</b>
</h1>    

Chapter 5 showed that scaling and normalization help make different features fair and comparable by putting their values on a similar scale. We learned that features with larger numbers can affect a model more, even when they are not necessarily more important. What surprised us most was that scaling is not always required because its importance depends on the data and the machine learning algorithm being used.

 <h1 align="center">
<b>CHAPTER 6</b>
</h1>

This chapter explains that outliers are values that differ greatly from most of the data and can affect the accuracy of analysis and results. It introduces the Z-score and IQR methods for detecting outliers, along with techniques such as capping and flooring, log transformation, and removal to manage them. What is surprising is that even one extreme value can influence the results and lead to incorrect conclusions. However, outliers should be carefully examined before removing them because they may contain important information.

<h1 align="center">
<b>CHAPTER 7</b>
</h1>

Chapter 7 explains how feature selection helps identify the most useful variables for building accurate predictive models. It discusses correlation, which measures the relationship between variables, and the three main feature selection methods: filter, wrapper, and embedded methods. What is surprising is that using too many features does not always improve a model because irrelevant information can reduce its performance. This chapter highlights the importance of choosing the right features to make data analysis more efficient and reliable.

<h1 align="center">
<b>CHAPTER 8</b>
</h1>

This chapter discusses how a preprocessing pipeline organizes and automates data preparation before it is used in machine learning. It covers the use of tools such as SimpleImputer to fill missing values, StandardScaler to standardize numerical data. What is surprising is that automating these steps can reduce errors, save time, and ensure consistent results when processing new data. This chapter highlights how pipelines make data preparation easier, more organized, and more reliable.

<h1 align="center">
<b>CHAPTER 9</b>
</h1>

 This chapter covers cleaning missing values, transforming numerical data, removing unnecessary features, grouping ages into categories, and converting categorical data into numerical form. What is surprising is that preparing a dataset involves more than simply fixing errors because each feature may require a different preprocessing technique. This chapter emphasizes the importance of checking data quality after preprocessing to ensure that the dataset is organized, consistent, and ready for further analysis.
 
## Errors we found

List any mistake you found in the original notebooks, and the correct version.
There are real ones in there. Finding them earns points.



## Note on AI tools

Say whether you used an AI tool, and what for. This is not a penalty.
Hiding it is.

We used AI tools to understand data scaling, specifically focusing on how StandardScaler impacts a feature's mean and standard deviation to prevent large numbers from dominating a model.  In addition, We relied on AI assistance to analyze  why was the Rank column dropped from the dataset and why it acts as noise in a dataset.

## References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
Any other page or article you used.
