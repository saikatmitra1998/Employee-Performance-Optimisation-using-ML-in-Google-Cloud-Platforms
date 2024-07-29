# Maintenance and Service Project Report

## Overview
This repository contains the final report for the project titled "Konzeptionierung und Evaluierung eines Modells zur Bewertung von Big-Data Projekten und deren Ordnungsrahmen" conducted by the Otto-von-Guericke-Universität Magdeburg. The project aims to improve the quality of services at Mobility Worldwide (MWW) by optimizing employee assignments and leveraging learning trajectories.

## Table of Contents
1. [Introduction](#introduction)
2. [ER Diagram](#er-diagram)
3. [Task-1: Visualization of Learning Curves](#task-1-visualization-of-learning-curves)
4. [Task-2: Evaluation of Team Effectiveness](#task-2-evaluation-of-team-effectiveness)
5. [Task-3: Simulation and ML Model](#task-3-simulation-and-ml-model)
6. [System Architecture](#system-architecture)
7. [Conclusion](#conclusion)

## Introduction
Mobility Worldwide, located in Magdeburg, is a globally operating corporation specializing in innovation, production, talent promotion, and services in the mobility domain. The Maintenance & Service (MS) department is responsible for the functioning of physical facilities at client sites. This project aims to enhance service delivery quality by optimizing employee assignments based on historical data analysis.

## ER Diagram
The report includes an Entity-Relationship (ER) diagram that represents the data structure and relationships between service employees, tasks, and clients.

## Task-1: Visualization of Learning Curves
The first task involves visualizing the learning curves of individual employees to show how their efficiency improves over time. Using datasets from MS SAP DWC and tools like BigQuery and Looker Studio, various graphs were created to illustrate this learning process.

- **Query Used**: SQL queries to join datasets and calculate time spent on each task.
- **Visualization Tools**: Google Looker Studio

## Task-2: Evaluation of Team Effectiveness
The second task evaluates the effectiveness of teams, considering factors like distance to client sites and team composition. This involved extracting relevant data, running SQL queries, and visualizing results using Looker Studio.

- **Key Analysis**: Team performance based on average time to complete tasks, impact of distance on performance, and gender-specific team analysis.

## Task-3: Simulation and ML Model
The third task involves developing a machine learning model to predict the best employee or team for new tasks and creating a simulation model using a Flask application.

- **ML Model**: Linear regression model built with BigQuery ML to predict task completion times.
- **Simulation**: Flask application deployed on Google App Engine to generate and assign tasks.

## System Architecture
The project utilizes Google Cloud services including Cloud Storage, BigQuery, and App Engine to manage data, perform analysis, and host applications.

![System Architecture](path_to_architecture_diagram.png)

## Conclusion
The project successfully achieved its objectives by leveraging data analysis and machine learning to optimize employee assignments and improve service delivery quality at MWW. The developed tools and insights will support continuous improvement and help MWW adapt to evolving customer needs.

For more detailed information, refer to the full project report provided in this repository.
