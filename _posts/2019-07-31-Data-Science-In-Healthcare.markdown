---
layout: post
title:  "Challenges of implementing AI within Healthcare"
description: Reasons why healthcare is behind in the AI revolution
date:   2019-08-01 21:03:36 +0530
categories: Healthcare
tags: AI
permalink: pretty
---

In the last decade we have seen much media coverage about the artificial intelligence revolution. The idea of self-driving cars, auto-recommender systems (ie. Netflix), and automatic fraud detection in banking is not a foreign concept to most of us. However, we do not see such coverage in the health industry.
Is healthcare falling behind in the arms race of artificial intelligence and machine learning?

I would like to explore the challenges specific to the industry:
1. Industry niche & unique characteristics
2. Ethical considerations
3. Lack of traditional data scientists
4. Scaling costs
5. Difficulty in medical text classification


### 1 - Industry niche & unique characteristics

The healthcare industry is one of the most compliant among all the other types of industries. This isn't surprising, considering that individual lives are at stake.

Within the industry, there exists numerous reporting schemes and complex organization structures. To add to this conundrum, organization varies according to type of hospital, be it a tertiary center or a secondary one.

Each department within healthcare is also a niche on itself. Robotic surgery will vary greatly from glandular conditions. Bringing AI into each specialty will bring its own set of challenges.

Accuracy matters. In a doctors office - one test result may essentially change the life of an individual. Contrast this with AI applications like a music playlist recommender system for example. It has a bigger leeway for mistakes. If the system does get it wrong, the user isn't physically affected. In the worst case scenario, the user will discontinue the service.

A highly accurate prediction model that is at least 95-99% confident will be essential. There isn't much room for 'guestimating' when one is dealing with lives.

### 2 - Ethical considerations

Who will make the final diagnosis? Can a machine determine if a person has or doesn't have cancer? Where do we draw the line in this ethical dilemma.

Can a machine determine whether a man lives or dies?

Are computer generated synthetic images equal to real world imaging? Can they be used in training further AI applications?

There isn't any consensus yet on these issues, from both professional bodies and the public. It will be something that needs to be ironed out before society can fully embrace AI technology. I think this area is one that is extremely exciting to watch!

### 3 - Lack of traditional data scientists
Healthcare organizations can run easily without data scientists. Even if you do find them, they form only a handful of individuals.

<img src="https://www.kdnuggets.com/images/linkedin-data-scientist-title-649.jpg"></img>

A search on LinkedIn profiles with data scientists title in 2018:
A majority of them are in tech and finance. I don't see anyone in health at all!

### 4 - Scaling costs
It is inspiring that other industries are implementing futuristic technology in their workflow. In the food industry for example, there is automatic weighing and detection of food waste. This can then directly lead to cost saving models.

Turns out there is a scaling issue with medical images it isn't all that easy. There is a significant cost for  data labelling. It is estimated that to get a decent training dataset of 20,000 CT scans will cost USD$500,000 to $1M just to get the manpower to correctly label these medical images. One will require a highly trained individual called the radiologist to go through the images and annotate them correctly.

Size is an issue too. Medical imaging usually studies a part of the body intricately. To do this properly requires a large amount of images to be taken. For example, a cardiac CT will usually take up 18,000 images and up to 36GB of data for one patient. This is another one of the hurdles when developing AI techniques in this space.

### 5 - Medical text classification and extraction
The medical language is a highly efficient way of communicating, where each word in a medical report will carry some value and meaning. Take for example: "From the latest PET-CT of this patient, we now have evidence that the lobulated hepatic lesion which is abutting the diaphragm is deemed to be of malignant nature and requires immediate surgical intervention." That is a mouthful of words - and I'm sure training a usual linguistic AI model isn't going to be so straightforward in this space.

Understanding how each word interacts also will be something to look into. Training a computer to understand and recognize the word "glucose" will not be enough, as it will mean differently in different context. For example, "urine glucose" vs "gestational glucose levels".

These are the few challenges that will be faced by companies trying to incorporate AI into healthcare. In my next post, I will be talking about what recent developments and what sort of data is available in the healthcare space. So do look out for that!


Source:
* Michael Segala, Phd - SFL Scientific https://www.youtube.com/watch?v=eTvcEUKmpWo
* Shourya Sarcar, GE Healthcare - https://www.slideshare.net/sarcar/data-explosion-in-medical-imaging
