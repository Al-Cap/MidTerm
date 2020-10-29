# Video Game Sales

<p align="center">
   <img src=https://github.com/Al-Cap/MidTerm/blob/main/images/videogames-1-e1522270884482.jpg />
<div align="center">
   <figcaption></figcaption>
</div>
</p>


## Overview

Video game sales have been increasing every since they were first released. Sales are increasing even more in the last few years with better hardware and graphic being available and inproving respectively. The increase of sales also comes an increase in reviews for any game that comes out. Reviews on a game vary depending on game, genre, and various other factors as well. Furthermore, reviews from critics can and have effected game sales and releases of many game. A pattern can sometimes been seen depending on the game, platform, and developer in comparison the the scores critics give it can effect sales.

## Goals

The goal of this project is to determine whether there is an actual comparison between the sales of games and the critic score assigned to them and how that effect the sales.

## Motivation & Background

Buy a game is sometimes difficult if one is sure of what to get. This is simialar to buying a car or house but usually not as exspensive as those. In the same realm, review and comments on such things help in deciding on what to get. One does not want to buy a game and then find out that the game is not good or too difficult for it to be played.

## Table of Content
<pre>
Report           : <a href=https://github.com/Al-Cap/MidTerm/blob/main/report.ipynb>Main</a>
Data             : <a href=https://github.com/Al-Cap/MidTerm/blob/main/data>Data Source</a>
Graphs           : <a href=https://github.com/Al-Cap/MidTerm/blob/main/graphs>Modals</a>
Pictures           : <a href=https://github.com/Al-Cap/MidTerm/blob/main/images>Iamges</a>
</pre>

## ReadME Navigation

[Data](https://github.com/Al-Cap/MidTerm#data) - 
[Modeling](https://github.com/Al-Cap/MidTerm#modeling) - 
[Results](https://github.com/Al-Cap/MidTerm#results) - 
[Future](https://github.com/Al-Cap/MidTerm#future) - 
[Project Info](https://github.com/Al-Cap/MidTerm#project-info)

## Data

Data retrieved from [kaggle.com](https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings). Initial data was modified a bit to be able to use properly. In addition, only data pertaining to North American Sales and Critic Score was use from the data. 


## Modeling

Initial plot of North American Sales and Critic Scores

![scatter.jpg](https://github.com/Al-Cap/Video-Game-Sales-Analysis/blob/main/graphs/scatter_plot.jpg)

Slop represented with the red line.

![linefit.jpg](https://github.com/Al-Cap/Video-Game-Sales-Analysis/blob/main/graphs/linefit_plot.jpg)

Residual and Predition values with linear regression.

![regression.jpg](https://github.com/Al-Cap/Video-Game-Sales-Analysis/blob/main/graphs/regression_plot.jpg)

## Results

 The results were shown that there was some correlation between sales and critic score with some outliers in the correlation. Even if scores were low sales were sometimes higher than expected.
 
## Future

Continouing this project, one could include user score in addition to critic score to determine how sales relate to them. The data can also be used to compare sales from other places as well. Anoter way is to compare sales to the platform used to play games on or the developer as well.

<p align="center">
   <img src=https://github.com/Al-Cap/MidTerm/blob/main/images/index-6-1579289540.jpg />
<div align="center">
   <figcaption></figcaption>
</div>
</p>


## Project Info
<pre>
Contributor  : <a href=https://github.com/Al-Cap>Alexander Caporale</a>
</pre>

<pre>
Languages    : Python
Tools/IDE    : Anaconda, Jupyter Notebook
Libraries    : pandas, matplotlib, numpy, csv, scipy, sklearn, statsmodels
</pre>

<pre>
Duration     : October 2020
Last Update  : 10.29.2020
</pre>
