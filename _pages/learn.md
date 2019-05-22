---
layout: single
permalink: /learn/
date: 2019-04-14T00:00:00+09:00
---
# CARECOM Nurse Care Activity Recognition Challenge

## Why nurse care activity recognition?
In an aging population, the demand for nurse workers increases to care for elders. Helping nurse workers make their work more efficient, will help increase elder quality of life, as the nurses can focus their efforts on care activities instead of other activities such as documentation.

Activity Recognition can be used for this goal. If we can recognize what activity a nurse is engaged in, we can partially automate documentation process to reduce time spent on this task, monitor care plan compliance to assure that all care activities have been done for each elder, among others.  

## Challenge Goal
The goal of the HASC Nurse Care Activity Recognition Challenge is to recognize nurse activities by means of body movement analysis. Although complex activities can benefit from other types of sensors such as object or environment sensors, in a nursing domain these can be difficult to install. For example, in nursing homes, extra care for not disturbing the residents environment must be considered and the sudden installation of sensors can disturb them. Moreover, some nurses are working as visitor nurses, visiting each patient at their own homes where we have no control of sensors available or environment. For these reasons, the challenge aims at measuring the feasibility of recognizing nursing activities based on body movement.

## Data
The data for the challenge has been collected in a controlled environment for evaluating the feasibility of recognition. Six activities were performed by eight subjects with 5 repetitions per activity. The laboratory emulated a real environment with hospital bed, desk and all instruments used by the nurse.
The activities have been chosen in collaboration with nurses and CARECOM company to make the most important activities.

Four types of sensors have been installed.
Motion capture sensors with 29 markers, accelerometer sensor in the chest, bluetooth based in-door positioning and pressure sensor. 
[See more details about each activity and the sensors](/data_description/).

## Challenge
For the challenge the dataset has been divided in two subsets.
The first subset contains data about 6 subjects and contains all activity labels.
The second subset contains data about the other 2 subjects and is not labeled.
Participants must submit their results of predicted activities on the second dataset using their models.
