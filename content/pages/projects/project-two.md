---
type: ProjectLayout
title: Creating a reddit chatbot using reddit data and Google api
colors: colors-a
date: '2025-03-29'
client: own project
description: >-
  gathered reddit data using reddit api and praw library. and done some
  sentiment analysis and eda. finally created a ask me anything chatbot with
  google gemini api
featuredImage:
  type: ImageBlock
  url: /images/bg1.jpg
  altText: altText of the image
  caption: Caption of the image
  elementId: ''
media:
  type: ImageBlock
  url: /images/artificial-intelligenceai-chat-bot-concept-scaled.jpg
  altText: altText of the image
  caption: Caption of the image
  elementId: ''
---
This project was inspired by a YouTube tutorial from Thu Vu, a data scientist based in the Netherlands. She originally built the chatbot using the ChatGPT API, but I decided to take the idea further in my own way.

I started by pulling Reddit data using the Reddit API with the `praw` library. I collected posts and comments from three subreddits: **datascience**, **artificial**, and **machinelearning**. The data was saved into two files: `DS_ML_AI_POSTS.csv` and `Comments.csv`.

I used the **Datalore** platform for analysis — it's packed with useful features and worked great for this kind of project. For EDA, I explored the number of posts per year in each subreddit using bar graphs, and visualized trending topics over time with **word clouds**.

Then I moved on to **sentiment and emotion analysis** using predefined models. For example, when I input a word like *ChatGPT*, the system would search through the comments and return sentiment results, which I displayed using graphs.

The final part was building the chatbot. Initially, I tried using the ChatGPT API, but it didn’t work as the free credits had expired. That’s when I started researching alternatives. I explored **local models** and finally settled on using the **Google Gemini Flash API**. After updating the codebase and switching from OpenAI to Google’s API, I managed to get the chatbot running successfully. It took a bit longer because I wasn’t chunking the data and was using a free-tier API — but I made it work.

I wrapped everything up by generating a report directly within Datalore. Through this project, I learned a ton about working with APIs, NLP techniques like word clouds and sentiment analysis, and the practical use of **LlamaIndex** and **LLMs**, both online and locally.

Here is the link for the[ jupyter notebook](https://github.com/hariharan3103/Reddit-EDA-and-Chatbot) that i coded. (Please change the api with your api, if you are using it)

And direct link for the [Datalore report](https://datalore.jetbrains.com/report/static/GNioAFYu8e593vRQh3dQmz/NhBDkDofLP6PZrLkdmx5kE) that i created. (Sorry i can't put it in the intereactive mode)
