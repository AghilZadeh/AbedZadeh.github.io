# My Personal Projects
Here is a brief description of few of my personal side projects. If you wanna know more about me take a look at my [LinkedIn](https://www.linkedin.com/in/aghilzadeh/).

***

## Insight into Insight
For a while, I have been interested in knowing more about the [Insight program](http://insightdatascience.com/). If you are also curious about the past projects, pursued by Insight fellows, this project might be insightful for you too!

I have looked at all [INSIGHT DATA SCIENCE FELLOWS](http://insightdatascience.com/fellows) over the past years. Using data scraping by beautifulsoup, I have collected all their projects, found word frequencies and filtered our irrelevant words. Finally, I have come up with the below word-cloud of past Insight projects. 

<div align="center">
<img src="https://user-images.githubusercontent.com/35585082/35773969-b57cdd64-092f-11e8-9a5e-ae76ad567a0e.png" alt="3LSkgv.png" height="270px">
</div>

There are few words that you see at the first glance, like find, new, predicting and recommendation. If you take a closer look you can see the most popular data are video, image and music. Also regarding the places, restaurant and city are more desirable in the projects. Have you ever wondered which corporations are more picked by fellows? Twitter and Zidisha are on top of the list in organizations and incorporations. 

If you want to see more details, you can refer to my [codes](https://github.com/AghilZadeh/Insight_WordCloud)!


***

## Duke Visualization Challenge

Scholars@Duke and The Graduate School of Duke University invited researchers and data scientists to participate in a [visualization challenge](https://rc.duke.edu/scholars-vis-challenge/) to address questions like:

- Can faculty publications and PhD dissertation committees show how disciplines overlap?
- What can the makeup of dissertation committees tell us about trends in research?
- How many Duke faculty cross departmental and school boundaries in their publishing and teaching activities, and can these activities be visualized?
 
My collaborator [Varda](https://github.com/vfaghirh) (at Arizona State University) and I teamed up along with Python, many of its libraries and Gephi to present a poster at the symposium. Our results got lots of attentions, won 3rd place, and appeared on [Duke News](https://researchblog.duke.edu/2018/02/06/duke-scholars-bridge-disciplines-to-tackle-big-questions/).

<div align="center">
<img src="https://vgy.me/3LSkgv.png" alt="3LSkgv.png" height="600px">
</div> 

Our Poster, which I designe using Inkscape, is now in Duke's Library and can be cited. You can see the abstract [here](https://dukespace.lib.duke.edu/dspace/handle/10161/16028).

Let me walk you through the results briefly! Ready?? There are three main parts: Publications, collaborations, and education!
You see some description on the poster. Here I am going to focus on the networks!

In our bigger collaboration network, the nodes represent organization and departments, with the outer circle being the most important ones (largest degree nodes)! Most of these important ones are affiliated with Duke school of Medicine.

On a coarse-grain level, we also have plotted collaboration network of schools. Still school of Medicine and basic sciences rock, but take a closer look and you see how connected law school and school of public policy are! Right? Kind of amazing how collaborative publications are! On the other hand, Divinity school is isolated. It was not like this few hundred years ago, I believe! If you want to explore more do not miss out our [collaborations interactive graph](https://aghilzadeh.github.io/Duke_Collaborations/)! 

In the education graph, we want to show where students go to pick up their graduate level committee members. The inner circle are departments, where students have graduated from 2012 to 2017, and outer circles are faculties affiliations. The edges represent the number of students. Lots of students love faculties from Trinity College of Arts and Sciences. Here basic sciences are connected more than medical sciences or even engineering. If you need to take a closer look try our [education interactive graph](https://aghilzadeh.github.io/Duke_Education/)!

Still need more details? You can always refer to our codes, methods and abstract [files](https://github.com/AghilZadeh/Duke_DataVisualization)!  
