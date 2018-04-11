---
layout: post
title:  Sentiment Analysis in Slack
date:   2018-04-10 21:25:00
categories: projects
description: A Slack User Bot for analyzing the sentiment of messages
author: Owen Miller
author-image: https://avatars0.githubusercontent.com/u/31546566?s=400&u=764d99a094f2c8ee578837b5ab629ad55f213d0e&v=4
author-bio: First year Computational Mathematics Major
author-email: euler@csh.rit.edu
author-social:
  github: https://github.com/owencmiller
---
# The Story
Here at Computer Science House we use a group messaging platform called Slack. Slack allows for collaboration with all members of CSH
in the form of channels. Members of our Slack group can join and leave channels at will and post messages within the channels. One day 
I was wondering how to guage the mood of CSH and realized that Slack had all of the information I needed. With the use of the Natural
Language Tool Kit (nltk) and the Slack Client Python API (slackclient) I was able to create a Slack User Bot that guaged the mood
of a particular Slack channel.

# The Project
The Sentiment Analysis tool for Slack is a User Bot that can be added to Slack channels to measure the sentiment within the channel.
Written in Python, the program initially connects to the Slack using the Real-Time Messaging API and waits until a user @'s the bot.
This sends the user's message to the progarm, which then interprets the request and uses the Slack WebAPI to return an analysis of the 
requested information.

