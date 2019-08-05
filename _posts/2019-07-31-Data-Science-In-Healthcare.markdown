---
layout: post
title:  "Challenges of implementing AI within Healthcare"
description: Reasons why healthcare is behind in the AI revolution
date:   2019-08-01 21:03:36 +0530
categories: Healthcare
tags: AI
permalink: pretty
---

Today I came across a highly relevant talk on Open Source Data Centre (OSDC), which I will link in the references below. The speaker was talking about the challenges of implementing AI in the healthcare and biotechnology space. It is interesting to note that other industries, such as finance and insurance have already been implementing AI / data science and analytics in their workflow for almost 2 decades. There is an obvious benefit having an edge over a competitor in those industries, which is earning more money!

These are the challenges that will face those who try to incorporate AI into Healthcare:
1. Industry niche & unique characteristics
2. Lack of traditional data scientists
3. Scaling costs
4. Difficulty in medical text classification

### 1 - Industry niche & unique characteristics
The healthcare industry is one of the most compliant industries, which isn't surprising when they are dealing with people's lives! There exists numerous reporting schemes and a complex organization structure in most hospitals. And to add to the difficulty, this varies according to the location, size and workforce within the hospital / surgery. Not all types of specialties exist in all hospitals, and mind you each specialty has it's own quirks. I would be pretty certain that department working with robotic surgery will vary greatly from another dealing with glandular conditions. Breaking AI into each specialty will bring its challenges - and companies will need to look into not just making algorithms but a clinically applicable and robust product.

Accuracy matters, in fact in a doctors office - one test result may essentially change the life of an individual. In contrast, artificial intelligence applications such as music playlist recommender systems have a bigger leeway in 'guestimating' a playlist for a user based on his or her past history. If the system does get it wrong, the user may still continue using the same provider in hopes that it gets better with more personal data collected. In the worst case scenario, the user will discontinue the service. Here is where accuracy matters, in that any system in healthcare requires a highly accurate prediction model that is 95-99%. There isn't much room for 'guestimating' when one is dealing with lives. There is a huge ethical implication in designing an AI system in this field.

Measurement of results. This is again reflected easily in finance, where being 'smarter' means getting more money. In the healthcare industry, how we measure results is 'varied' to say the least. Which do we focus on - patient satisfaction, running costs, efficiency of bed use? Public systems are not profit focused, instead they look to deliver as much with a set budget. AI companies will need to target their focus to bring about a "clinically significant impact".

### 2 - Lack of traditional data scientists
Healthcare organizations can run easily without data scientists. Even if you do find them, I believe that they form only a handful of individuals. Most public organizations may not even have any data scientists in their team. I think this trend is slowly changing as organizations find value in utilizing their data. Slow adoption means that companies thinking of getting into this space still have room to move in, which is a great opportunity!

### 3 - Scaling costs
After seeing how simple it is for NVDIA or OpenAI to come up with models that can recognize basically any food type or animal species - I wonder why we do not bring this technology into healthcare. Turns out there is a scaling issue with medical images and getting the right training data for the model. To start recognizing cancers from scans, you will need to 'teach' the AI what is normal and what is not. This is called data labelling. It is estimated that to get a decent training dataset of 20,000 CT scans will cost $500,000 to $1M just to get the manpower to correctly label these medical images. One will require a highly trained individual called the radiologist to go through the images and annotate them correctly. It's not a simple and labelling 'hot dog' or 'not hot dog'.

Size is an issue too. Medical imaging usually studies a part of the body intricately. To do this requires a large amount of images to be taken. For example, a cardiac CT will usually take up 18,000 images and up to 36GB of data for one patient. Just doing 4 scans a day, on the weekdays for a year will be taking up a space of 30TB. It is estimated that in 2014 and in the US alone, medical imaging data takes up 100 peta-bytes of storage! (That is a quadrillion btyes, or 16 digits long!)

### 4 - Medical text classification and extraction
The medical language is a highly efficient way of communicating, where each word in a medical report will carry some value and meaning. Take for example: "From the latest PET-CT of this patient, we now have evidence that the lobulated hepatic lesion which is abutting the diaphragm is deemed to be of malignant nature and requires immediate surgical intervention." That is a mouthful of words - and I'm sure training a usual linguistic AI model isn't going to be so straightforward in this space.

Understanding how each word interacts also will be something to look into. Training a computer to understand and recognize the word "glucose" will not be enough, as it will mean differently in different context. For example, "urine glucose" vs "gestational glucose levels".

These are the few challenges that will be faced by companies trying to incorporate AI into healthcare. In my next post, I will be talking about what recent developments and what sort of data is available in the healthcare space. So do look out for that!


Source:
* Michael Segala, Phd - SFL Scientific https://www.youtube.com/watch?v=eTvcEUKmpWo
* Shourya Sarcar, GE Healthcare - https://www.slideshare.net/sarcar/data-explosion-in-medical-imaging
