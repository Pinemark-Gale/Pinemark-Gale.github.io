---
layout: post
title: Capstone Blog Post 4
author: Gale Proulx
published: true
categories: Capstone
---

With only four weeks until the end of the semester, we are reaching the final leg of preparation for this capstone project. Before that leg ends, we still have a lot of work to do. One constant main concern for this project is getting our research approved by Champlain College's Institutional Review Board (IRB). The paperwork we must fill out is quite extensive and will force our group to accelerate the Professional Writing side of this capstone that does not start until next semester. With the discordance in time frames, it is becoming increasingly harder to get the required work of our first semester work done while adding more work of the upcoming semester. Our hope it that both me and my partner's schedules will line up within the next week so we can have a solid chunk of time to decide on the future of this capstone's parameters surrounding interviews and call for submissions. Since the IRB is not required to approve projects in a specific time frame, this approval process could be a big burden if we do not get it approved before next semester.

Setting aside the paperwork required to get this project approved, the data preparation for this project is getting along nicely. As mentioned in my last blog post, I needed to combine a total of 11 data files successfully. My attempts to combine the initial 11 files have been a success, and I am now attempting to combine all 252 files together. With a little more time, this week I should be able to finish combining all data files, allowing me to continue with the rest of the design process for this project. Although my data gathering will most likely not end at the first stage of this project, the bulk of this work should be done.

While coding a solution for gathering data, I have also been writing the third chapter of my capstone summary. The design process has already been outlined, and most of the software that I will be using has been covered. I did take an initial look into the compatibility of SAS and this dataset, just to see if the program would prove to be useful for creating multiple linear regression models. It turns out that SAS as a program is extremely limited by the lack of efficiency. Combining two data files that are approximately 11,000 rows long took about 26 seconds. Multiple this time by 100 (if I wanted to combine 100 of the 252 files we have), and we are looking at estimated computing times of 2600 seconds or 43 minutes of runtime just to combine datafiles in SAS. While I do realize I will not have to combine these files as I am already making a program to do this process beforehand, I am still worried that SAS is not a program capable of handling larger datasets. For the sake of this project, I might have to use SAS only for small snippets of data and use Python for larger analysis.

Another issue popped up while I started looking ahead at the end of this project's design process. If I wanted to create geographic visualizations of the data, I need to attach longitude and latitudes to all the institutions in this dataset. I only have addresses. Google Maps does have an API I could potentially grab the data from, but their licensing requires that I use a Google Maps to visualize the data. Other services online offer free geocoding but limit the number of requests that a single user can pull per day. I will have to do some more research for a tool that will allow me to pull approximately 11,000 address geolocations.

The rest of the software that will be used in this project has already been mentioned to the best of my ability. The same goes for algorithms. I imagine that my classes next semester (specifically Machine Learning teaching about Neural Networks) will provide additional algorithms that I will want to test, but for now my preliminary analysis will be a good guide.

To guide my data exploration for next semester, I have also created the following research questions:

Do liquor crimes at four-year postsecondary institutions have any effect on sexual violence at those institutions?
Are any types of crimes on four-year postsecondary institutions related to specific geographical regions in the United States?
Do four-year postsecondary institutions have different crime rates than two-year postsecondary institutions?
How has the overall trend in reported crimes for postsecondary institutions changed from 2009 to 2017?
What connections are there, if any, between New England’s postsecondary institutions student demographics and crime rates?

It is my hope that most of my research will be able to tie back to these questions while backing up the statements made by calls for submissions and interviews from the professional writing side. In regards to the rest of Chapter 3, I still am working hard to specify my test plan, criteria and constraints, and other sections that may be needed. A time frame for these sections will be specified soon in the next assignment.
