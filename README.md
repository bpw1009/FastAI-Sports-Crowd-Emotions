# FastAI-Sports-Crowd-Emotions
This is a proof of concept for using image data to detect sports crowd emotions


I have recently started working through the Practical Deep Learning for Coders course developed by fastai. Fastai is an organization as well as a python library built on top of pytorch. Fastai was developed in large part by Jeremy Howard, President and Chief Scientist at Kaggle.

This project is an adaptation of the example tutorial from the first chapter from the Practical Deep Learning course. The original tutorial created a deep learning classifier to identify bird photos vs forest photos. The course encourages learners to adapt the tutorial for novel purposes, so that is what I did in this notebook.

I decided to adapt the classifier to detect happy vs. angry sports crowds.

I got the idea for this sort of classifier several months before starting this course--in June of 2022. While visiting San Francisco, I went to a Giant's game with my sister's family. At the game, my brother-in-law asked me what are some potential applications of data science in sports. I wanted to think of some applications aside from the obvious goal of using player analytics to maximize performance. Aside from player analytics, there are many opportunities to optimize the business and marketing of sports using data. It's obvious that sports exist for entertainment... If fans did not show up to games or watch on TV, there would be no major league sports. What are some ways to maximize fan enjoyment?

Along those lines, I started thinking about what an MLB organization could do help make sure fans are enjoying the games. At another point that day, my brother-in-law mentioned that the music being played at the stadium heavily favored music from certain decades. He noticed a lot of 80's music being played at the game. My brother-in-law deducted that there is some sort of demographic analysis that influences their playlist choices--that the songs are chosen based on what the team's marketing department knows about the makeup of the crowd.

I thought his assessment seemed likely, however, there might be a more direct way to tell if the crowd enjoys the songs. An image classifier could be trained to recognize the emotion of a crowd. The model could be trained to recognize when a crowd seems to be happy/having fun, when a crowd is bored, when a crowd is angry, etc.

That's why I decided to try to build a proof of concept model that could detect the emotion of sports crowd images.
