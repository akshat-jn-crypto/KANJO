# Kanjo

People are only a click away from obtaining vast amounts of data. With information comes people's opinions, and with that comes people's positive and negative perspectives on a subject. This can lead to bullying and the spread of hateful remarks about someone or something.
Therefore, Kanjo is a an attempt to help our cops to maintain a safe cyberspace across various social media platforms startng with Twitter. This script can tell you the sentiments of people regarding to any events happening in the world by analyzing 1000s of tweets related to that event. It will search for tweets about any topic and analyze each tweet to see how positive or negative it's emotion is.

This project was built as a part of the Hackmanthan 2022 which was the first ever hackathon organized by chattisgarh Police in collaboration with IIIT (Naya Raipur) where Participants had to take up one of the five challenges/tracks, namely:-
- BlockChain 
- Integration of CCTV data
- speech emotion recognization on live calls while creating events/Identification of system generated spoof calls landing at dial 112 control room
- Sentiment Analysis of Social Media Posts
- Crime Data Analysis.

This project was made in an attempt to take on the 4th challenge of researching and thinking about the algorithms that may be used to analyse sentiments and emotions of different type of topics over twitter.

**Motivation:** 

While today's world has become fast paced and hectic where it is easier than ever to hide behind the mask of anonymity. Therefore, we require a solution that must be able to classify the sentiments that are expressed on different social media platoforms. It should be able to accurately identify when the tone of the posts becomes inflammatory and hateful.

**Solved Problem:**

This application aims to offer a quick and easy way to analyse 1000s of tweets on a certian topic/ place or person and determine the most popular sentiment and emotion shown towards it.

**Watch Demo** :  [Demo](https://youtu.be/KQGjfpfWfI0)

## Table Of Contents

- [Features](#features)
- [Installation](#installation)
- [Tech Stack](#tech-stack)
- [Challenges Faced](#challenges-faced)
- [Demo](#demo)
- [Support & Contact](#support-and-contact)


## Features

- Scraping all the tweets related to specific topic
- Categorizing tweets of a topic under Positive, Negetive or Neutral sentiments.
- Categorizing a specific topic under love, happiness, worry or hate
- Importing Live tweets
- Typing your own tweet to analyse it.
- Compatible with Phones, Laptops, Ipads and Tablets


## Installation

To use this project execute the following scripts

1. Login from your Twitter account and goto Twitter Apps. 
2. Create a new app (How to create twitter app) and goto Keys and access tokens and copy Consumer Key, Consumer Secret, Access Token and Access Token Secret. We will need them later.

1. Initialise Your Git Terminal
```bash
  git init
```
2. Clone this Repository
```bash
  git clone <repo link>
```

3. Move into the Directory
```bash
  cd Project_name
```
4. Open The Repository with your code editor,  it is recommended you use Visual Studio Code.
```bash
  code .
```
5. Install all nessecary Libraries (List of libraries to be installed)


6. Run the following command:

```bash
  python ./manage.py runserver
```  

## Tech Stack

In spite of all the smart devices that exist today in the world, one thing that is common is - web and internet browsers. I selected my application to be a web application so that a large number of users are able to use it with ease and connect together

**Client:** HTML, CSS, SASS , JavaScript

**Server:** Python, Django, Twitter app API, sqlite

**Libraries:** numpy, tweepy, textblob, pandas

The design of this application is simple yet responsive keeping in mind for it to work on different types of devices to solve a a real life problem 

## Challenges Faced

*"Errors are a stepping stones to develop good applications"*

During the development process I faced the following challenges:-

- Kaavya & Saloni: Working with SASS and its variables for the 1st time 
- Saloni: Using Twitter API for the first time
- Akshat: We working with Django for the 1st time therefore errors came up frequently which were solved by taking hep of various online communities and websites.

## Demo

[Link to Video Demo](https://www.youtube.com/watch?v=KQGjfpfWfI0)

## Support and Contact

***Paricipant 1:-***

Name: Kaavya Saxena

Email: kaavya1906@gmail.com

College: Indira Gandhi Delhi Technical University for Women

Batch : 2024

***Paricipant 2:-***

Name: Saloni Gupta

Email: officialetc01@gmail.com

College: Indira Gandhi Delhi Technical University for Women

Batch : 2024

***Paricipant 3:-***

Name: Akshat Jain

Email: akshat.jn2002@gmail.com

College: Netaji Subhas University of Technology

Batch : 2024
