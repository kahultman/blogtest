---
date: 2017-03-08
title: "A Shiny App for the Biology Alumni Survey"
author: "Keith Hultman"
bigimg: [{src: "img/feature-image-electrophoresis.jpg"}]
---

I recently built an interactive dashboard for the [Elmhurst Biology Department's alumni survey.](https://keithh.shinyapps.io/SurveyApp/)

### Background

Our biology department at Elmhurst is highly motivated to improve our teaching methods and styles. Currently, we are updating our introductory course curriculum with adding more active learning, standardizing laboratory modules, and developing central themes to introduce students to the field of biology and the scientific method. 

As part of this curriculum revision, we recently reached out to alumni through social media and asked them to evaluate their training here at Elmhurst in light of their current career path. The survey was conducted in collaboration with a Master's program course by a team including Whitney Carey, Priya Devineni, Nicole Kasmer and Alex Severson. Their original report showed that alumni who responded to the survey are generally very happy with EC Biology's curriculum and ability to prepare them for graduate studies and their career. 

Although the original report did an excellent job in examining the responses in aggregate, there was not much analysis of the relationship between the different types of responses. I further analyzed the responses to answer several questions I had about the data. But I also wanted my colleagues to ask their own questions and perhaps they would find something I might miss. I've been wanting to build an R Shiny app, and this was a perfect excuse for it.

[The EC Biology Survey Shiny App](https://keithh.shinyapps.io/SurveyApp/) lets them filter according to different graduation years and career fields and then visualize how those groups rated our curriculum. One surprising result for me was that transfer students seemed to rank our curriculum quite high compared to those who started their education here. This could be because they were comparing our curriculum positively to the school they transfered from. Or, perhaps we are on the right track in updating our introductory courses for our Freshmen and Sophomores, as students who took those courses ranked us lower. The shiny app also uses some text analysis (using the tidytext R package) in order to rank the most common curriculum requests from these groups, which I find to be really useful. 

## Major Curriculum/Program Suggestions by Alumni

The following suggestions were popular with all alumni but especially with alumni who remained in biology and medical fields. 

* Offer, or continue to offer, **advanced human health-related courses** (nutrition, pathology, pharmacology, medical physiology)
* **More career-focused advising**, with a greater emphasis on job opportunities for biology majors outside of advanced degrees.
* Incorporate updated **lab technologies** in lab sciences coursework where possible
* Continue to offer **Bioinformatics** and Biostatistics as an essential skill for the modern biologist

## Minor Curriculum/Program Suggestions

* Invite speakers for biology talks at least once a semester
* Invite Biology and Medical Alumni for honorary award and talks on campus
* Develop a J-term field research based trip
* Encourage a student run journal club (BBB?) with faculty participation
* Add emphasis of epigenetics into (Advanced?) Genetics course


You can check it out [here](https://keithh.shinyapps.io/SurveyApp/) for yourself, and let me know what you think.