---
title: "SAAB Internship"
excerpt: "An overview of my time at SAAB as an intern."
date: 2024-09-15
header:
  image: /assets/images/navyfleet.png
  teaser: /assets/images/Updated_SAAB_Logo.png
toc : true
toc_label: "Table of Contents"
sidebar:
  - title: "Role"
    text: "Machine Learning Software Engineer Intern"
  - title: "Responsibilities"
    text: "Helping in the devlopment of projects TSUNOMI, ETA ETD IRAD, and ReflexAI"
---

# Introduction 

As a Machine Learning Software Engineer Intern at SAAB I was tasked with helping the team with the development of three projects. TSUNOMI, ETA ETD IRAD, and ReflexAI. TSUNOMI was a collaboration with ONR to build a multimodal sensor fusion system for the US Navy. ETA/ETD IRAD was a project to create a machine learning model that would help improve the predection times that the FAA uses currently to predict the arrival and departure times of aircrafts. ReflexAI was a project to create a machine learning model that would help autonomly control a boat that has changing dynamics such as weight, hull integrety, and engine power.

# TSUNOMI Summer 2024

During my second internship at SAAB, I took on complex challenges in computer vision and synthetic data generation for autonomous systems. My objective was to develop a synthetic data generation pipeline for training and testing object detection models. I also worked on developing a computer vision algorithm for detecting and tracking objects in real-time. Building relastic models using Cesium and utalizing Unreal engine to have relastic graphics.

## Computer Vision System Development

I developed a robust camera vision system focused on object tracking and real-time location data processing. The system was designed to maintain consistent tracking accuracy across varying environmental conditions and object velocities. I implemented advanced computer vision algorithms and optimized the processing pipeline to ensure minimal latency in location data updates.

## YOLO Model Training Enhancement

I designed an automated image pipeline that significantly improved the YOLO (You Only Look Once) model training process. The pipeline automatically generated bounding boxes around objects of interest, streamlining the data preparation phase. This automation reduced manual labeling time and improved model training efficiency.

## Unreal Engine Integration

One of my key contributions was implementing a camera calibration pipeline within Unreal Engine. This calibration system enhanced the accuracy of synthetic data collection by ensuring proper alignment between virtual and real-world camera parameters. I created photo-realistic environments that closely mimicked real-world conditions, enabling more effective AI model training through synthetic data.

## Cross-Functional Leadership

Beyond technical development, I led cross-functional team meetings with university research collaborators. These meetings focused on sharing knowledge, aligning development goals, and ensuring our innovations could be effectively integrated into broader research initiatives.

# TSUNOMI Summer 2023

On the TSUNOMI I worked on three different main objectives. Building a simulated enviorment that would allow us to gather traning data for our tracking algorithm, building a Kafka broker to allow for seemless data communication between sensors and the tracking algorithm, and finally building an acoustic sensor measurment model.

## Simulated Enviorment

To build a simulated enviroment I used the open source software stone-soup. Stone Soup is a software project to provide the target tracking and state estimation community with a framework for the development and testing of tracking and state estimation algorithms. To setup our enviroment I followed the tutorial for a 2D model getting that working as a proof of concept. This allowed us to test and valiadate if the data recived can be used to train and test our tracking algorithm. After that I worked on a 3D model that would allow us to test our tracking algorithm in a more realistic enviroment. Getting this setup was the crucial first step in our project as it allowed us to gather data to train and test our tracking algorithm.

## Kafka Broker

To setup a Kafka broker I used the open source software Apache Kafka. Apache Kafka is a distributed streaming platform. What this means is that it allows for data to be sent and recieved from multiple sources. This was crucial for our project as we had multiple sensors that needed to send data to our tracking algorithm. The Kafka broker allowed us to do this with ease. I was able to setup a Kafka broker on a local machine and then have the sensors send data to the broker. Then the tracking algorithm would recieve the data from the broker. This allowed for a seemless data transfer between the sensors and the tracking algorithm. I utalized docker to setup the Kafka broker and the sensors. This allowed for a quick and easy deployment on any machine.

## Acoustic Sensor Measurment Model

Devloping an acoustic sensor measurment model was an intresting challenge to tackle as it focused more on the math behind simulating sensors as compared to coding. I first utalized the data that I recived from the simulation and with a decent amount of linear algebra using covraince matrixes and gaussian distrubations I would add relastic noise to the data. This allowed us to have a more realistic data set to train and test our tracking algorithm. Next step was to add the speed of sound delay to the sensor. While I was working on this task I was not able to complete it as my internship ended. However I was able to get a decent amount of work done on it and I am confident that I would have been able to complete it if I had more time.

# ETA/ETD IRAD

On the ETA/ETD IRAD I worked on two main objectives. Building a data pipeline that would allow us to gather weather data along flight paths and storing it on a data base. Then I worked on building a machine learning model that would predict the arrival and departure times of aircrafts.

## Weather API

To gather weather data I used the open source software Open-Metro. Open-Metro is an online service that provides weather data, including current weather data, forecasts, and historical data to the developers of web services and mobile applications. I used the API to gather weather data along flight paths. I was able to get the data in a JSON format and then I used python to parse the data and store it in a database. This allowed us to have a large data set to train and test our machine learning model.

## Machine Learning Model

To build a machine learning model I used the open source software Tensorflow. Tensorflow is an end-to-end open source platform for machine learning. I used Tensorflow to build a machine learning model that would predict the arrival and departure times of aircrafts. I used the data that I gathered from the weather API and the data that the FAA uses to predict the arrival and departure times of aircrafts. I was able to build a model that was able to predict the arrival and departure times of aircrafts with a 90% accuracy. This was a great accomplishment as it showed that machine learning can be used to improve the current system that the FAA uses to predict the arrival and departure times of aircrafts.

# ReflexAI

I was pretty busy during my internship so I was not able to help as much on this project as I wanted. But I was still able to experince how my team does a demo presentation to DARPA to showcase how much work was completed and that we were on track to finish the product on the deadline. This was a great learning experince as I was able to see how a demo presentation is done and what is expected from the team.

# Key Technologies Used

Computer Vision: YOLO, OpenCV
Game Engine: Unreal Engine
Programming: Python, C++
Development Tools: Git, Docker
Team Collaboration: JIRA, Confluence

# Impact 

The systems I developed contributed to SAAB's autonomous systems capabilities, particularly in object detection and tracking. The synthetic data generation pipeline continues to be used for training and testing computer vision models, reducing the need for extensive real-world data collection.