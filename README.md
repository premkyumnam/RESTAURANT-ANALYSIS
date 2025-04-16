<html>
  <body>
    <h1><u>Restaurant_Data_Analysis</u>:Data Analysis Internship Program</h1>
    <h2>Cognifyz Technologies</h2>
<h1>Tools & Technologies:</h1>
In this Data Analysis Internship program, to achieve the goals of geven tasks of the levels, I used the following tools and technologies:<br>

Pandas: For data analysis, cleaning, exploration, and manipulation.<br>
NumPy: For efficient numerical computations.<br>
Matplotlib: For data visualization, including plots, charts, and graphs.<br>
Seaborn: For statistical data visualization, building on Matplotlib.<br>
Counter (Collections): For counting hashable objects, such as frequency analysis.<br>
Jupyter Notebook(IDEs): As the primary environment for data processing and analysis.<br>

These tools enabled me to effectively extract insights and meaning from the data.
#First Task of Level 1
The goal of the first task was to:
1. Identify the top three most common cuisines in the dataset and
2. Calculate the percentage of restaurants serving each of these cuisines.
<h1>Results:</h1>
<p>I identified the top three most common cuisines and calculated the percentage of restaurants serving each:<br>
1. North Indian: 3,960 restaurants (41.50%)<br>
2. Chinese: 2,735 restaurants (28.66%) and <br> 
3. Fast Food: 1,986 restaurants (20.81%)<br>

<h1> Second Task of Level 1</h1>
  The goal of this second task was to:

1. Identify the city with the highest number of restaurants in the dataset
2. Calculate the average rating for restaurants in each city. And
3. Determine the city with the highest average rating.<br>
<h1>Results:</h1>
<p>Finally, I identified the required results of the task2:<br>
1. The city with the highest number of restaurants cin the dataset is <b>New Delhi (5473 restaurants) </b><br>
2. The average rating for restaurants in each city are:<br><br>
<table>
    <thead>
      <tr>
        <th></th>
        <th>City</th>
        <th>Average Rating</th>
      </tr>
    </thead>
    <tbody>
      <tr><td>43</td><td>Faridabad</td><td>1.866932</td></tr>
      <tr><td>88</td><td>Noida</td><td>2.036204</td></tr>
      <tr><td>78</td><td>Mc Millan</td><td>2.400000</td></tr>
      <tr><td>82</td><td>Montville</td><td>2.400000</td></tr>
      <tr><td>87</td><td>New Delhi</td><td>2.438845</td></tr>
      <tr><td>...........</td><td>.........</td><td>........</td></tr>
      <tr><td>75</td><td>Mandaluyong City</td><td>4.625000</td></tr>
      <tr><td>94</td><td>Pasig City</td><td>4.633333</td></tr>
      <tr><td>73</td><td>Makati City</td><td>4.650000</td></tr>
      <tr><td>106</td><td>Quezon City</td><td>4.800000</td></tr>
      <tr><td>56</td><td>Inner City</td><td>4.900000</td></tr>
    </tbody>
  </table>

[140 rows x 2 columns]<br><br>

3. The City with the highest average rating is Inner City (4.90)<br></p>

<h1> Task 3_L#1: PRICE RANGE DISTRIBUTION</h1>
In this project, I analyzed a restaurant dataset to identify the following two key questions:

1. To create the a histogram or bar chart to visualize the distribution of price range among the restaurants.<br> 
2. To calculate the percentage of restaurants in each price range category.<br>
<h1>Results:</h1>
<p> At first, I tried to find out the price range category and arranged them in ascending order: <br>
  <p>The price range are:</p>
  <table>
    <tbody>
      <tr><td>1</td><td>4438</td></tr>
       <tr><td>2</td><td>3113</td></tr>
        <tr><td>3</td><td>1405</td></tr>
         <tr><td>4</td><td>586</td></tr>  
    </tbody>
  </table>
<br>
And then I plotted the bar chart with different colors of the above price range category. Here is the link to view the chart. :<br><br>![image](https://github.com/user-attachments/assets/0086bb7a-cabc-4158-962d-f9efb0cc9208)

  And then I found out the price range distribution> Here is the required reults:<br><br>
  Price Range Distribution:<br>
  <table>
    <tbody> <tr><td></td><td></td></tr>
      <tr><td>1</td><td>Price Range 1: 46.51% of restaurants</td></tr>
       <tr><td>2</td><td>Price Range 2: 32.62% of restaurants </tr>
        <tr><td>3</td><td>Price Range 3: 14.72% of restaurants</td></td></tr>
         <tr><td>4</td><td>Price Range 4: 6.14% of restaurants </td></tr> 
    </tbody>
  </table>
<br<<br>
Thus, I got the required keys of the given two questions of the task3:<br><br> 

 <h1>Task#4_Level#1: ONLINE DELIVERY ANALYSIS</h1>
 <h2>Projec Review: </h2>
In this project, I analyzed a restaurant dataset to identify food trends. The goal of this 4<sup>th</sup> task (Level 1) is to:

1. Determine the percentage of restaurants that offer online delivey. And
2. Compare the average ratings of restaurants with and without online delivery <br>
<h1>Results:</h1>
<p>First,I tried to find out the total number of restaurants by using this code: <br> <em>"total_resutaurants=len(df)"</em><br><br> And then,  I got the total number of restaurants that do not offer online delivery i.e., 7091  and <br>the total number of restaurant that offer online delivery is 2451. <br>And tried to find out the percentage of restaurants that offer and do not offer online delivery.  This is the formula I am applying here: <br><br><br>

  <p>
  $$ \text{Online Delivery Percentage} = \left( \frac{\text{Online Delivery Counts}}{\text{Total No. of Restaurants}} \right) \times 100 $$
</p></br> 
<p>Python code:<br></br>
<em>
  1. online_delivery_percentage = (online_delivery_counts / total_restaurants) * 100</em> </br>
  2. avg_rating_online = df[df["Has Online delivery"] == "Yes"]["Aggregate rating"].mean()</br>
  3. avg_rating_no_online = df[df["Has Online delivery"] == "No"]["Aggregate rating"].mean()</br>
</em>
</p>

  
Finally, I identified the required results of the 4<sup>th</sup> task(level 1):<br><br>

1. The percentage of restaurants that offer online is 25.69 and do not offer online delivery is 74.31 </b><br>
2. The average ratings with online delivery is 3.25 and the average ratings without online delivery is 2.46.<br></br>

This is the formula I am applying Here:
<p>
  $$ \text{Average Rating} = \frac{\text{Sum of all ratings}}{\text{Number of ratings}} $$
</p>

<h2> N.B: For the remaining tasks, you can see in the pdf file I uploaded separately in this repository.</h2>

A huge thanks to Cognifyz Technologies for this amazing learning opportunity! Every step in this journey is helping me grow, and I'm excited for what's next.<br><br>

Explore the full project on LinkedIn and GitHub:<br>
(https://www.linkedin.com/feed/update/urn:li:activity:7316539760322191360/)<br>

<p>I hope this will be very helpful to new learners and students. <br>
And I'd love to hear your thoughts and feedback! <br>
Let's connect and explore more data-driven insights together. <br><br>
Thank you all!

  <b>(YUMNAM PREMKUMAR SINGH)</b>
</p>
</body>
