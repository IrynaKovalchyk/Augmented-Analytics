# Augmented Analytics
Breaking down Augmented Analytics(AA) methodology on example of the data cleaning process. To get yourself familiar with main concept, you can read [dyvenia blog](https://dyvenia.com/blog/augmented-analytics)  or check out some of the [Useful-links](https://github.com/IrynaKovalchyk/Augmented-Analytics#useful-links).

To make yourself more familiar with the topic, before going into exercises and/or modifying code on the notebooks, check out the summary up [presentation](https://github.com/IrynaKovalchyk/Augmented-Analytics/blob/main/Augmented%20analysis.pdf)

There are 3 notebooks that you can manipulate and work with. They're different, also, it'd be needed to approach them differently. All of them start with a brief description and plan of what is going to be done to each notebook.
1. [Custom methods notebook](https://github.com/IrynaKovalchyk/Augmented-Analytics/blob/main/custom.ipynb) has a lot of potential for changes, modification, and improvement. The main idea of it was to create an example of the AA approach on the various level of coding, starting from standard Python functions, following up with the ideologically ML approaches, and at the end with actual one-liners for ML methods. 
2. The notebook based on [Autoclean](https://github.com/IrynaKovalchyk/Augmented-Analytics/blob/main/Autoclean.ipynb) library is a playground for approaching the same data as in [Custom methods notebook](https://github.com/IrynaKovalchyk/Augmented-Analytics/blob/main/custom.ipynb) with the help of it. Showing use cases of its methods in the AA approach.
3. The [DataClean](https://github.com/IrynaKovalchyk/Augmented-Analytics/blob/main/DataClean.ipynb) notebook is based on the same called library with the same aim as the [Autoclean notebook](https://github.com/IrynaKovalchyk/Augmented-Analytics/blob/main/Autoclean.ipynb) 


## Exercises 

Exercises will be rated on 0-7 scale, where each number represents:
| Scale | Description                                                                               |
|-------|-------------------------------------------------------------------------------------------|
| 0     | Never used                                                                                |
| 1     | Used limited times _I can copy and paste, but not create by myself_                       |
| 2     | Basic understanding _I can complete very simple use cases/ adapt others work to my needs_ |
| 3     | Used on basic level as part of role _I can create basic end-to-end by myself_             |
| 4     | Used regularly in medium complexity _I can work comfortably and support beginners_        |
| 5     | Used for advanced cases on a daily basis                                                  |
| 6     | Able to teach                                                                             |
| 7     | Mastered, able to teach and coach                                                         |

**0-2 Scale.** </br>
  1. Read the  [dyvenia blog article on AA ](https://dyvenia.com/blog/augmented-analytics) </br>
  2. Get yourself familiar with some of the materials from [Useful-links](https://github.com/IrynaKovalchyk/Augmented-Analytics#useful-links). </br>
  3. Clone the [repo](https://github.com/IrynaKovalchyk/Augmented-Analytics)</br>
  4. Run code of the notebook as well as get familiar with main strategies, which were used there </br>

**3-4 Scale.**</br>
  1. Clone the [repo](https://github.com/IrynaKovalchyk/Augmented-Analytics)</br>
  2. Run code of the notebook as well as get familiar with main strategies, which were used there </br>
  3. Check out the data source and chalnge to it 
  4. Descover more ML methods, for instance you can check them out at the [The top 10 ML algorithms you should know](https://medium.com/@techynilesh/the-top-10-machine-learning-algorithms-you-should-know-7c97222e08d2)
  5. Try out [.loc() and .iloc() functions](https://sparkbyexamples.com/pandas/pandas-difference-between-loc-vs-iloc-in-dataframe/) to deal with missing data
  6. Build dictionary based on 'neighbourhood', 'neighbourhood group', then try to find correlation between 'price' and 'neighbourhood'
  7. How to handell missing data in 'host_identity_verified' ? For instance, make one more lable for missing data 
  8. Handdel data types, special symbols

**5-6 Scale.**</br>
  1. Whata categories will be influenced by 'instant_bookable' ? What about 'cancellation_policy'
  2. Transform 'last review' to the date type. What is the fresiest and the oldies review ? How it will correlate with the 'number of reviews'
  3. Handdel missing data in 'last review', 'number of reviews'. Hint: sometimes in a way to normalization some of the data might be droped, however it's not a case all the time 
  4. Get insides from 'number of reviews',	'last review',	'reviews per month',	'review rate number'
  5. Try to use Linear Regression for cleaning some data  
  6. Try to use Logistic Regression for cleaning some data 
  7. Comper what worrks better on the data set Linear Regression or Logistic Regression


**7 Scale.**</br>
  1. Implement best paracies of code
  2. Geo data. Handelling 'lat','long' missing data by useing API 
  3. Use NLP to parth key words from 'house_rules'
  4. What is the most common key word and the most rare one ?
  5. Is it possible to handell 'house_rules' by usige of the most common/rare key words ?
  6. Clusterize data set 
  7. Try to use  Decision Trees and Support Vectors
  
## Guidelines 
To kick off start working with [Custom methods notebook](https://github.com/IrynaKovalchyk/Augmented-Analytics/blob/main/custom.ipynb) in a way to explore the data set and a main ideas standing by it. To improve your data cleaning skils try one by one tasks and hints given at the [Exercises](https://github.com/IrynaKovalchyk/Augmented-Analytics#exercises) section. Try out libraries used in the [Autoclean](https://github.com/IrynaKovalchyk/Augmented-Analytics/blob/main/Autoclean.ipynb) and [DataClean](https://github.com/IrynaKovalchyk/Augmented-Analytics/blob/main/DataClean.ipynb) notebooks to explore more opportunities for cleaning data in AA way.

## Useful links 
### Videos:
1. <a href="https://www.youtube.com/watch?v=kyFrQRPGpAM" target="_blank">How AA Enhances Decision-Making</a>
2. <a href="https://www.youtube.com/watch?v=ascreEpm33A&t=0s" target="_blank">How AA Tools Will Change The Way We Work</a>
### Articles
1. <a href="https://www.gartner.com/en/documents/3773164" target="_blank">Gartner definition of AA</a> 
2. <a href="https://cedar.princeton.edu/sites/g/files/toruqf1076/files/media/gartner_bi_comparison_2018.pdf" target="_blank">Gartner paper: BI Platforms</a> 
3. <a href="https://www.adverity.com/augmented-analytics" target="_blank">Overview on AA. How it can transform your marketing</a>
4. <a href="https://www.qlik.com/us/augmented-analytics" target="_blank">Qlik: What is AA?</a>
5. <a href="https://www.sap.com/insights/what-is-augmented-analytics.html"  target="_blank">SAP: Intro to the AA</a>
6. <a href="https://powerbi.microsoft.com/en-us/what-is-augmented-data-preparation/" target="_blank">PowerBi: What is augmented data preparation?</a>
7. <a href="https://powerbi.microsoft.com/en-us/augmented-analytics/ " target="_blank">PowerBi: What is AA? Overview</a>
8. <a href="https://datrixgroup.com/en/augmented-analytics/"  target="_blank">datrix: Overview on AA</a>
9. <a href="https://sisudata.com/blog/augmented-analytics-use-cases-and-examples" target="_blank"> Sisy: AA use cases and examples </a>
10. <a href="https://www.selecthub.com/business-analytics/augmented-analytics-guide/" target="_blank">Starter`s guide for AA </a>
11. <a href="https://analyticsindiamag.com/a-primer-to-augmented-analytics-for-the-beginners/" target="_blank">AA for the beginners</a>
12. <a href="https://www.smarten.com/blog/what-is-augmented-data-preparation-and-why-is-it-important/" target="_blank">What Is Augmented Data Preparation And Why Is It Important?</a>
13. <a href="https://www.mdpi.com/1424-8220/22/20/8071"  target="_blank">Research paper: "Augmented Analytics Driven by AI: A Digital Transformation beyond Business Intelligence" by Noorah A. Alghamdi, Heyam H. Al-Baity </a>
14.  <a href="https://www.researchgate.net/publication/347442365_BIG_DATA_AUGMENTED_ANALYTICS" target="_blank">Research paper: "BIG DATA & AUGMENTED ANALYTICS" by Girish Madhav Akurathi</a>
15. <a href="https://www.freecodecamp.org/news/what-is-augmented-analytics-definition-example/" target="_blank">AA: Definition and Example of Use Cases </a>
16. <a href="https://unscrambl.com/blog/7-augmented-intelligence-examples-and-industry-use-cases/" target="_blank"> 7 examples and use cases for AA</a>
17. <a href="https://www.allerin.com/blog/what-if-we-told-you-that-augmented-reality-had-been-a-part-of-human-life-for-a-long-time-surprised-dont-be-with-emerging-technologies-ar-has-improved-a-lot-and-so-has-its-uses-augmented"  target="_blank">Real-world applications of Augmented Reality</a>

