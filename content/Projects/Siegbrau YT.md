---
title: "Siegbrau YT (YouTube Dislike Calculator)"
date: 2019-03-26T08:47:11+01:00
publishdate: 2019-03-26T08:47:11+01:00
---

## Context
This is a project initiated in conjunction with a dear friend, in an attempt to estimate the total number of dislikes associated with a given YouTube video (following YT's elimination of the dislike button). Siegbrau is a direct reference to Dark Souls, but is a cool name and little else. 

## Method & Scope
Update 1 - This project is created in Python. Initially, I created a small desktop app that essentially performs a crude version of sentiment analysis on a given video's comment section. Using [VADER](https://github.com/cjhutto/vaderSentiment), a sentiment analysis framework geared towards social media content, we assess the positivity of a given Youtube video's comment section. 

The program calls on the Google API to retrieve comment data, up to a limit defined by the user themself. The interactive app is a simple tkinter box.

Update 2 - This project will continue with the analysis and framework decision-making given a great dataset retrieved of YouTube videos and their dislikes. This historical data will be used to develop a model to further refine this project. 

## Project Links
- [GitHub Repo (App & Dependecies)](https://github.com/pennatia/Siegbrau_YT)