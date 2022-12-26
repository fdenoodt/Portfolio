# Portfolio
Hi there!

I am Fabian Denoodt, a Masters student in computer science with a degree in Applied Informatics. Here you can take a look at the projects I have worked on during my studies.  If you are interested in my profile, please visit my LinkedIn page: [Fabian Denoodt | LinkedIn](https://www.linkedin.com/in/fabian-denoodt/). 

Thank you for visiting!



## [2022] Computational Creative system - Pokémon Creator

For a computational creativity assignment, I generated fake Pokémon images using the open source text-to-image model ruDALLE. I fine-tuned the model on images of a specific Pokémon type and also used the pretrained weights to generate outlines of Pokémon sketches. To create the names for the Pokémon, I used a linear regressor trained on a dataset of all Pokémon names. The creative system took a few input words and combined the best combination of syllables to generate a list of potential names. The linear regressor then ranked the generated names and selected the most plausible option.

For more details, please take a look at the [paper](./pokemon_character_design.pdf).

<img src="https://scontent-bru2-1.xx.fbcdn.net/v/t1.15752-9/282383800_554874483021026_1003824832411503408_n.png?_nc_cat=105&ccb=1-7&_nc_sid=ae9488&_nc_ohc=nj8MyDDyfr8AX-iqIdy&_nc_ht=scontent-bru2-1.xx&oh=03_AdTD5X3j_fI3ECJsZIjH_GrKR3ky_oSGhJJumGy7C1fUNg&oe=63D118C1" alt="No description available." style="zoom: 67%;" />

<img src="assets/image-20221226162855553.png" alt="image-20221226162855553" style="zoom:67%;" />



## [2022] Statistical Foundations of Machine Learning - SVM research project

For a school project, I was tasked with analysing three research questions. One of the questions I focused on involved comparing the capability of different kernels in support vector classification on non-linearly separable data. Specifically, I compared the performance of linear, polynomial, and radial basis function (RBF) kernels when applied to a synthetic two-dimensional dataset. It was an interesting project that allowed me to explore the abilities of different kernels in support vector classification and to gain a deeper understanding of how they can be used to solve complex classification tasks.

<img src="assets/image-20221226154655480.png" alt="image-20221226154655480" style="zoom:67%;" />

Github: [WardGauderis/SFML (github.com)](https://github.com/WardGauderis/SFML)



## [2022] Actual Trends in Artificial intelligence- Wine temperature prediction

I contributed to a research project for company QelviQ where the goal was to predict the optimal temperature for wine bottles based on their labels. The project was divided into three main modules: a computer vision module to extract text from the bottle labels, a data interpretation module that transformed the raw text into meaningful knowledge, and a temperature prediction module that used this information to predict the exact temperature. I worked on the data interpretation module, which involved extracting features such as the bottle name, year, wine name, and the regions of the included ingredients.

QelviQ is available via the following link: [QelviQ stylish device regulate serving temperature your wine perfectly – QelviQ Euro](https://eu.qelviq.com/)

<video src="assets/Video_Qelviq.mp4"></video>



## [2021] Machine Learning regression - Appliances prediction

I completed a machine learning project where I used regression techniques to predict the energy consumption of appliances in a house. I experimented with different regression models such as `linear regression`, `decision trees`, `boosting regression`, and `support vector regression`. I also went through the full machine learning pipeline, including data visualization, data preprocessing, cross-validation for time series data, feature engineering, and model training with parameter tuning. Overall, it was a valuable experience in applying various machine learning techniques to a real-world problem.



## [2020-2021] Computer science bridging program

A one year program that prepares students to start a masters program in computer science. The program consists of the core courses from the original three year bachelors program.



Included math courses:

- Calculus and linear algebra
- Discrete mathematics
- Probability and statistics
- Scientific mathematics

Included computer science courses:

- Structure of computer programs
- Interpretation of computer programs
- Algorithms and data structures 1
- Algorithms and data structures 2
- Logic and formal systems
- Automata and computability



## [2020] Image recognition alarm
Because waking up can be hard, I made a smart alarm to help me out. The alarm contains a camera that is pointed at my bed and detects when I sleep. When it is time to wake up, the alarm continues to play music while I stay in bed. Only when I walk out of bed, the alarm will stop. The alarm consists of a Raspberry pi, a camera and speakers. The frontend is developed in `Angular`.

The Artificial Neural Network consists of a convolutional neural network developed in `python` using the `Keras` library.  

Github: [oBoii/alarm (github.com)](https://github.com/oBoii/alarm)

![image-20221226150245847](assets/image-20221226150245847.png)

![Image of the alarm](https://raw.githubusercontent.com/oBoii/alarm/master/readme/image-20200822155035922.png)



## [2020] 4 month internship as data scientist in the Netherlands
I worked as an intern for the Data Analytics team of Achmea. Data scientists have previously developed an image recognition model. My job was to extend their current solution so that other employees can develop their own machine learning models. (Similar to AutoML). The developed product includes a web application, which users can easily enter data and then train a model. In addition, several evaluation techniques have been implemented to assess the models. When a model does not perform satisfactorily, the application generates advice in one key sentence so that the end user can improve the model.

Grade: 16/20

Technologies:

- Data Science: Python, TensorFlow, Keras, YOLOv3
- Software development: Angular, .NET CORE, Azure Services



## [2019] Student job - Angular Developer
As front end developer for enterprise Organi, I helped the team adding an extra module to their existing program, which is currently being used by their customers.

<img src="https://i.gyazo.com/ab7222350747b64bc41392d4d72aac73.png" alt="Image of the alarm" style="zoom:50%;" />

### Technologies: 
* JavaScript
* Angular
* RxJS

### Links:
* Organi: https://www.organi.be/en
* Result: https://imgur.com/a/Yoyt5c5



## [2019] School Project - TaskZone
A team project, with the objective of enhancing the communication/planning of teams.  
The application contains a chat service, similar to LinkedIn where you can send messages to a person/group.
The person receiving the message will then see 3 suggestions he can reply to that sentence.
![TaskZone](https://i.imgur.com/K6PezTP.png)
### Technologies: 
* C# (MVVM, Entity Framework)
* Python
* T-SQL



## [2019] Hackathon - WhatTheHack
2 day Hackathon, our objective was for awkward students to be able to make friends more easily.  
This we attempted to achieve by building a website, similar to Omegle but where the person gets matched with other students from the same school.  
If the conversation goes well they can add eachother as connection or if things go really well... even friends.

### Links:
Github: https://github.com/oBoii/WhatTheHack-Hackathon

## [2018] Student job - Open Summer of Code
Project called "HealthStory", the objective was to make health related data more accessible.
![HealthStory image](http://ofabian.be/cv/map/healthstory.png)
### Technologies: 
* JavaScript 
* React

## [2018] School project - World of Pong
Hybrid smartphone application, mark zones as 'Silent' / 'Loud'.
While in the zone, the phone will go into the preferred mode.

### Technologies: 
* NodeJS 
* Socket.IO
* JavaScript
* Cordova

### Links:
Video: https://www.youtube.com/watch?v=THXR1ZnCKiM

## [2018] A Silent Place - School project
Native android application, mark zones as 'Silent' / 'Loud'.  
When positioned in the zone, the phone will switch into the preferred mode.
![A silent place image](https://i.gyazo.com/99fd3405a5940747237c79991dd4c051.png)

### Technologies: 
* Kotlin
* Firebase

### Links:
Google Play: https://play.google.com/store/apps/details?id=be.ofabian.asilentplace

## [2018] UNO - School project
The game can be played solo against against bots.  
It can also be downloaded from my website to serve as an app for your phone.
![UNO image](http://ofabian.be/cv/map/uno.png)

### Links:
Demo: https://ofabian.be/UNOv6

## [2017-2019] Management System - AMC Genk
Started as highschool project but is now being used profesionally by AMC-Genk + supported.  
Administration of:
Users, Reservations, Pictures / albums, Newsfeed, Sponsors / Advertisements
[AMC Genk image](http://ofabian.be/cv/map/amc.png)
#### Technologies: 
* JavaScript
* PHP
* Bootstrap

## [2017] Website - School project
Disability-friendly Website without use of frameworks.

### Links:
* Website: http://ofabian.be/website_marc/

## [2017] Calendar - Home project
"I didn't feel like using Google's Calendar, so I built my own."

Project made for fun to fill in some time during my 3 month summer vacation.

## [2017] Static website - Traductions Marquant
A static website that shows information about the company (Bootstrap).

### Links:
* Website: http://luc-marquant.be

## [2017] Internship - Horeca Technology Solutions
IT-Support helpdesk for 2 weeks.  
Company specialised in offering IT solutions in hotel and catering industry.

### Links:
* Website: https://be.placedigger.com/horeca-technology-solutions-hts174251099.html
