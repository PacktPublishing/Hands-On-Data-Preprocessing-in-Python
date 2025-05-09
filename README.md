<p align="center"><a href="https://packt.link/mlsumgh"><img src="https://static.packt-cdn.com/assets/images/ML Summit Banner v3 1200x627.png" alt="Machine Learning Summit 2025"/></a></p>

## Machine Learning Summit 2025
**Bridging Theory and Practice: ML Solutions for Today’s Challenges**

3 days, 20+ experts, and 25+ tech sessions and talks covering critical aspects of:
- **Agentic and Generative AI**
- **Applied Machine Learning in the Real World**
- **ML Engineering and Optimization**

👉 [Book your ticket now >>](https://packt.link/mlsumgh)

---

## Join Our Newsletters 📬

### DataPro  
*The future of AI is unfolding. Don’t fall behind.*

<p><a href="https://landing.packtpub.com/subscribe-datapronewsletter/?link_from_packtlink=yes"><img src="https://static.packt-cdn.com/assets/images/DataPro NL QR Code.png" alt="DataPro QR" width="150"/></a></p>

Stay ahead with [**DataPro**](https://landing.packtpub.com/subscribe-datapronewsletter/?link_from_packtlink=yes), the free weekly newsletter for data scientists, AI/ML researchers, and data engineers.  
From trending tools like **PyTorch**, **scikit-learn**, **XGBoost**, and **BentoML** to hands-on insights on **database optimization** and real-world **ML workflows**, you’ll get what matters, fast.

> Stay sharp with [DataPro](https://landing.packtpub.com/subscribe-datapronewsletter/?link_from_packtlink=yes). Join **115K+ data professionals** who never miss a beat.

---

### BIPro  
*Business runs on data. Make sure yours tells the right story.*

<p><a href="https://landing.packtpub.com/subscribe-bipro-newsletter/?link_from_packtlink=yes"><img src="https://static.packt-cdn.com/assets/images/BIPro NL QR Code.png" alt="BIPro QR" width="150"/></a></p>

[**BIPro**](https://landing.packtpub.com/subscribe-bipro-newsletter/?link_from_packtlink=yes) is your free weekly newsletter for BI professionals, analysts, and data leaders.  
Get practical tips on **dashboarding**, **data visualization**, and **analytics strategy** with tools like **Power BI**, **Tableau**, **Looker**, **SQL**, and **dbt**.

> Get smarter with [BIPro](https://landing.packtpub.com/subscribe-bipro-newsletter/?link_from_packtlink=yes). Trusted by **35K+ BI professionals**, see what you’re missing.




# Hands-On Data Preprocessing in Python

<a href="https://www.packtpub.com/product/hands-on-data-preprocessing-in-python/9781801072137"><img src="https://static.packt-cdn.com/products/9781801072137/cover/smaller" alt="Hands-On Data Preprocessing in Python" height="256px" align="right"></a>

This is the code repository for [Hands-On Data Preprocessing in Python](https://www.packtpub.com/product/hands-on-data-preprocessing-in-python/9781801072137), published by Packt.

**Learn how to effectively prepare data for successful data analytics**

## What is this book about?
Data preprocessing is the first step in data visualization, data analytics, and machine learning, where data is prepared for analytics functions to get the best possible insights. Around 90% of the time spent on data analytics, data visualization, and machine learning projects is dedicated to performing data preprocessing.

This book covers the following exciting features: 
* Use Python to perform analytics functions on your data
* Understand the role of databases and how to effectively pull data from databases
* Perform data preprocessing steps defined by your analytics goals
* Recognize and resolve data integration challenges
* Identify the need for data reduction and execute it

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1801072132) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
from ipywidgets import interact, widgets
interact(plotyear,year=widgets.
IntSlider(min=2010,max=2019,step=1,value=2010))
```

**Following is what you need for this book:**
Junior and senior data analysts, business intelligence professionals, engineering undergraduates, and data enthusiasts looking to perform preprocessing and data cleaning on large amounts of data will find this book useful. Basic programming skills, such as working with variables, conditionals, and loops, along with beginner-level knowledge of Python and simple analytics experience, are assumed.

With the following software and hardware list you can run all code files present in the book (Chapter 1-18).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1  - 18      | Python using the Jupyter Notebook                  | Windows Or Mac OS |


We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781801072137_ColorImages.pdf).


### Related products 
* Learn Amazon SageMaker - Second Edition [[Packt]](https://www.packtpub.com/product/learn-amazon-sagemaker-second-edition/9781801817950) [[Amazon]](https://www.amazon.com/dp/1801817952)

* The Data Science Workshop - Second Edition [[Packt]](https://www.packtpub.com/product/the-data-science-workshop-second-edition/9781800566927) [[Amazon]](https://www.amazon.com/dp/1800566921)

## Errata

**Chapter 5 - page 126:** The code chunk under Chapter 5 Data Visualization, Subsection Example of comparing populations using boxplots (page 126) is misplaced. The correct chunk of code can be found on the dedicated GitHub of the book. Also, this is the correct code:

```
income_possibilities = adult_df.income.unique()
dataForBox_dic= {}
for poss in income_possibilities:
    BM = adult_df.income == poss
    dataForBox_dic[poss] = adult_df[BM]['education-num']
    
plt.boxplot(dataForBox_dic.values(),vert=False)
plt.yticks([1,2],income_possibilities)
plt.show()
```

**Chapter 6 - page 166:** The following code chunk which can be found in Chapter 6, Prediction, Example of applying linear regression to perform regression analysis (page 166) has an error.

```
X = ['P_Football_Performance','P_2SMA']
Y = 'N_Applications'
```

The correct chunk of code:

```
X = ['P_Football_Performance','SMAn2']
Y = 'N_Applications'
```

The code in the GitHub repository is correct.

**Chapter 12 - page 380:** The first sentence in Exercise 5 of Chapter 12 (page 380) should be:

“Recreate Figure 5.23 from Chapter 5, Data Visualization, but instead of using WH Report_preprocessed.csv, integrate the following three files yourself first: WH Report.csv, populations.csv, and Countries.csv.”

Instead of 

“Recreate Figure 5.20 from Chapter 5, Data Visualization, but instead of using WH Report_preprocessed.csv, integrate the following three files yourself first: WH Report.csv, populations.csv, and Countries.csv.”


## Get to Know the Author
**Roy Jafari**
, Ph.D. is an assistant professor of business analytics at the University of Redlands.
Roy has taught and developed college-level courses that cover data cleaning, decision making, data science, machine learning, and optimization.
Roy’s style of teaching is hands-on and he believes the best way to learn is to learn by doing. He uses active learning teaching philosophy and readers will get to experience active learning in this book.
Roy believes that successful data preprocessing only happens when you are equipped with the most efficient tools, have an appropriate understanding of data analytic goals, are aware of data preprocessing steps, and can compare a variety of methods. This belief has shaped the structure of this book.

### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781801072137">https://packt.link/free-ebook/9781801072137 </a> </p>