# Online Gamestore Analytics

Chukwuemeka Okoli <br>
Practicum by Yandex Project 4 - Integrated Project 1 <br>
May 25, 2021 

**Project description** <br>
You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns.

In front of you is data going back to 2016. Let’s imagine that it’s December 2016 and you’re planning a campaign for 2017. The important thing is to get experience working with data. It doesn't really matter whether you're forecasting 2017 sales based on data from 2016 or 2027 sales based on data from 2026. The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.

## Table of contents

<div class="alert alert-block alert-info" style="margin-top: 20px">
    <ol>
        <li><a href="#objectives">Objectives</a></li>
        <li><a href="#data_source">Data Source</a></li>
        <li><a href="#technology_used">Technology Used</a></li>
        <li><a href="#structure_notebook">Structure of Notebook</a></li>
        <li><a href="#executive_summary">Executive Summary</a></li>
        <li><a href="#accomplishments">Accomplishments</a></li>
    </ol>
</div> 
<br>

<div id="objectives">
    <h2>Objectives</h2> 
</div>
The objective of this project is to:

- Identify patterns that determine whether a game succeeds or not.
- Spot potential big winners and plan advertising campaigns.
- Apply Data Analysis to a real-life analytical case study.

<div id="data_source">
    <h2>Data Source</h2> 
</div>

**Description of the data**

The dataset contains the following fields:
- Name
- Platform
- Year_of_Release
- Genre
- NA_sales (North American sales in USD million)
- EU_sales (sales in Europe in USD million)
- JP_sales (sales in Japan in USD million)
- Other_sales (sales in other countries in USD million)
- Critic_Score (maximum of 100)
- User_Score (maximum of 10)
- Rating (ESRB)
Data for 2016 may be incomplete.

<div id="technology_used">
    <h2>Technology Used</h2> 
</div>

<ul>
    <li>Python</li>
    <li>Jupyter Notebook</li>
    <li>Pandas</li>
    <li>Numpy </li>
    <li>Matplotlib</li>
    <li>Seaborn</li>
    <li>Plotly</li>
    <li>Squarify</li>
</ul>

<div id="structure_notebook">
    <h2>Structure of Notebook</h2> 
</div>
<ol>
    <li>Open the data file and study the general information</li>
    <li>Prepare the data</li>
        <ul>
            <li>Replace the column names</li>
            <li>Processing missing values</li>
            <li>Convert Datatypes</li>
            <li>Calculate the total sales</li>
        </ul>
    <li>Analyze the data</li>
        <ul>
            <li>Look at how many games were released in different years</li>
            <li>Look at how sales varied from platform to platform</li>
            <li>Which platforms are leading in sales? Which ones are growing or shrinking? Select several potentially profitable platforms.</li>
            <li>Build a box plot for the global sales of all games, broken down by platform</li>
            <li>Take a look at the general distribution of games by genre</li>
        </ul>
    <li>Create a user profile for each region </li>
    <li>Test the hypothesis</li>
        <ul>
            <li>Test 1 - Average user ratings of the Xbox One and PC platforms are the same</li>
            <li>Test 2 - Average user ratings for the Action and Sports genres are different</li>
        </ul>
    <li>Overall Conclusion</li>
</ol>

<div id="executive_summary">
    <h2>Executive Summary</h2> 
</div>

**Introduction**

**Methods**

**Key Findings**

**Deployment and Application**


**Future Development**


<div id="accomplishments">
    <h2>Accomplishments</h2> 
</div>





