# 03 - Clustering

## Introduction
This project was made for an assignment in the course Neural Networks, Artificial Intelligence and Big Data at the IMC University of Applied Sciences Krems.

## Goal
The goal of this project was to successfully use K-Means Clustering on two different problems. 

## Tasks

### PART 1: Mobile phone picture
- Take a picture with your smartphone. The picture must contain a piece of paper with your name on it and some type of background (walls, floor, window, etc.). Example in the slides from Lecture 7.
- Resize it to a manageable size (e.g., 256x256) either with R or Py.
- The goal of the homework is to reduce the number of RGB colors by using k-means.
- Pick the k suggested by the elbow mechanism. Try also other k values.
- The report must contain the original pic, the WSS plot (elbow), the final pictures, and your comments.
- (OPTIONAL) Feel free to experiment with multiple pictures to see how the variety of colors impacts k.

### PART 2: Drilling machine
Your company needs to understand the operation of the drilling machine that was just purchased. The sales rep responsible for the purchase knows only that the machine operates in different states, but instructions are in Chinese and the producer does not reply. The engineers take some operational measurements (400 observations of two variables) and ask you to analyze the data to (a) find out the number of states in which the machine operates, and (b) find out the state for each of the 400 observations. The data is stored in drilling.csv. Without labels, you decide to approach the problem with a clustering technique. Try with all techniques learned in the course:

- k-means: Different choices of K --> Elbow --> Choose K --> Final cluster Memberships
- Hierarchical clustering: Different Linkage --> Choose Linkage --> Look Dendrogram --> Choose cut --> Final cluster memberships
- DBscan: Set MinPTS --> Knee --> Set eps --> Find cluster memberships

---

## Assignment Evaluation
###  Possible points for assignment: 10 
Feedback:
In k-means for the drilling you write that k=4 is right, the title says k=4, but the plot shows a k=3.
Punkte
9 / 10

## Report
The report can be found in the file `src/clustering.ipynb`.