# Airbnb_Analysis_Project_2022
<p align="center">
  <img src="https://hotel.oxu.vn/wp-content/uploads/2018/08/airbnb.jpg" />
</p>

<a name="readme-top"></a>

## 📔TABLE OF CONTENTS 
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#project-objectives">Project Objectives</a></li>
    <li><a href="#process">Process</a></li>
    <li><a href="#special-implementation">Special Implementation</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#built-with">Built With</a></li>    
    <li><a href="#contributor">Contributor</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgments</a></li>
  </ol>
</details>


## 🏨Introduction

In the purpose of helping entrepreneurs gain more knowledge about what they are going to do, this project will analyze an AirBnB service in Los Angeles - one of the most luxurious cities in the world to clarify how they can succeed here. The data would contain the neighborhood, location, price and reviews of accommodations that cooperate with AirBnB in Los Angeles.

By the end of this project, entrepreneurs will get the full insights of Los Angeles’s AirBnB service, including the distribution of accommodation along with the cost, the benefit and the ideal price for each type in order to achieve the best for their start-ups.

<p align="center">
  <img src="https://rickalbertonline.com/wp-content/uploads/2018/06/2018_04_Lamerica-Homes_3112-Corda-Dr._Los-Angeles_CA-12-2.jpg" />
</p>

## 🎯Project Objectives

💘The project is aimed to answer these questions below:
-	Which type of accommodation is the most popular in Los Angeles?
-	Is there any correlation between room type, bath type and price of accommodation?
-	How can businesses raise customer satisfaction and property value?
-	What services should entrepreneurs prepare for their accommodations in the future?
-	At what cost will clients be satisfied given the facilities of the accommodations?

<br>

💘By observing the insights of this dataset, entrepreneurs will be able to:
-	Observe the insights of this dataset, including the most popular price range as well as the amount of bookings by customers.
-	Forecast the suitable position and price for new accommodations in order to prepare and invest in it.
-	Build a recommendation system for start-ups using customers’ reviews.

## ⚙Process
-	Data gathering

-	Data preprocessing

-	Data visualizing

-	Data analyzing

-	Data modeling

## ✍️Special Implementation

- Using fuzzywuzzy.process.extract to find similar type of property and replace them with right format

<p align="center">
  <img src="https://user-images.githubusercontent.com/89919775/224375725-9b97e15c-d860-4603-a22c-20830d91d6bf.png"><br/>
</p>

- Using pandas_profiling


<p align="center">
  <img src="https://user-images.githubusercontent.com/89919775/224373306-638e4e68-a558-480c-9974-f76a2b045698.png" width=800 ><br/>
</p>

- Using folium to draw map 

<p align="center">
  <img src="https://user-images.githubusercontent.com/89919775/224379362-8e353dd1-3233-4edb-abab-4a64daeefb29.gif"><br/>
  <i>Position of villa on the map</i>
</p>

Extract feature importance from Random Forest Regressor

<p align="center">
  <img src="https://user-images.githubusercontent.com/89919775/224381761-91aae040-1654-4175-a0e9-b3d6334dabea.png" ><br/>
</p>

- Applying Association Rules
<p align="center">
  <img src="https://user-images.githubusercontent.com/89919775/224382170-de7f933f-0352-42e2-a887-b1f1403d1994.png" ><br/>
</p>

## 🏆Results

💘The project has already fulfill the task above:

👉 A clear picture of Airbnb has been illustrate along with significant insight. 

👉 The model developed to forecast the appropriate pricing for new Airbnbs based on their condition

👉 Association rules also applied to determine the ideal combination of amenities.

<br>

💘This project also finds out uncovered elements that are essential to the success of the accommodation through targeted analytics, including:

-	The wide range of price is affected by the wide range of accommodation types and minimum night. The same for other attributes.

-	The combination of expensive room type and luxury property does not necessarily result in high value of accommodation, but it depends on the suitability between them.

-	The more money customers pay for the accommodation, the higher level of satisfactory standards they require.

-	Both property and room types have separate suitable locations to work well.

-	Although there are correlations between the price and other attributes, there are some critical rules that help distinguish them.

- Only if number of reviews are trivial, do the price of rental worsen customer satisfaction



## 🏗️Built with

- ![Python Router](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)

- ![image](https://img.shields.io/badge/Apache_Spark-FFFFFF?style=for-the-badge&logo=apachespark&logoColor=#E35A16)

- ![Folium](https://a11ybadges.com/badge?logo=folium)

- ![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)

- ![Scipy](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)

<!-- See more badge: https://github.com/Ileriayo/markdown-badges
  https://github.com/alexandresanlim/Badges4-README.md-Profile/blob/master/README.md#-database--->

- MLxtend

- fuzzywuzzy

- pandas_profiling 3.2.0

## 👋Contributing

<a href="https://github.com/thijnhdawjng">
  <img src="https://contrib.rocks/image?repo=Louis3797/awesome-readme-template" />
</a>

## 📞Contact

<a href="https://www.facebook.com/profile.php?id=100013569134053">
  <img src="https://raw.githubusercontent.com/gauravghongde/social-icons/master/SVG/Color/Facebook.svg" />
</a>    
&nbsp; &nbsp; &nbsp;

<a href="https://www.linkedin.com/in/duy-tr%E1%BA%A7n-a6b8541b7/">
  <img src="https://github.com/gauravghongde/social-icons/blob/master/SVG/Color/LinkedIN.svg" />
</a>
&nbsp; &nbsp; &nbsp;

<a href="mailto:tranbaoduy654772@gmail.com">
  <img src="https://github.com/gauravghongde/social-icons/blob/master/SVG/Color/Gmail.svg" />
</a>



## 📖Acknowledgements
[Pandas Profiling](https://towardsdatascience.com/pandas-profiling-easy-exploratory-data-analysis-in-python-65d6d0e23650)

[Polynomial Regression](https://www.w3schools.com/python/python_ml_polynomial_regression.asp)

[FPgrowth](https://hands-on.cloud/implementation-of-fp-growth-algorithm-using-python/)

[Hyperparamer tunning in pyspark](https://spark.apache.org/docs/latest/ml-tuning.html)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
