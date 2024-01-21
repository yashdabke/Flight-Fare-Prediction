# Flight Fare Prediction

This repository contains the code and documentation for a machine learning project aimed at predicting flight fares based on various factors. The project focuses on providing users with insights into potential flight costs, helping them make informed decisions when planning their trips.
We explore a dataset containing flight information and perform data preprocessing, exploratory data analysis (EDA), feature engineering, and model building using the RandomForestRegressor algorithm. The goal is to create a reliable model that can accurately predict flight ticket prices for various routes and airlines.

## Problem Statement

Travelling by air has become a common practice, and flight ticket prices are subject to fluctuations based on factors such as flight timing, destination, and duration. This project aims to predict flight fares using a provided dataset, enabling users to estimate costs before planning their journeys.

## Approach

The project follows standard machine learning tasks, including data exploration, data cleaning, feature engineering, model building, and model testing. Various machine learning algorithms are employed to determine the best fit for the given problem.

## Dataset

The dataset used for this project is available [here](Dataset). It includes relevant information for training and testing the machine learning model.

## Code

The code is organized in a modular fashion to ensure readability, testability, and maintainability. It adheres to Python coding standards as outlined in [PEP-0008](https://www.python.org/dev/peps/pep-0008/). The codebase is maintained on GitHub, and the repository is public for transparency.

### Code Structure

- `src/`: Contains the source code for the machine learning model.
- `tests/`: Includes test cases to ensure the functionality of the code.
- `notebooks/`: Jupyter notebooks for data exploration and analysis.

### Workflow and Execution

For detailed instructions on running the project, refer to the [Workflow and Execution document](workflow_execution.md).

## Database

The project utilizes a Cassandra database, and the dataset is hosted on [Astra](https://astra.dev/ineuron).

## Cloud

The solution can be hosted on any cloud platform such as AWS, Azure, or GCP. The choice of the cloud provider is based on individual preferences and requirements.

## API Details or User Interface

The solution can be accessed either through an API or a user interface for model testing. The flexibility of choice allows users to interact with the system in a way that suits their needs.

## Logging

The Python logging library is used to capture and document every action performed by the code. Logging ensures transparency and aids in debugging.

## Ops Pipeline

The project incorporates AI ops pipeline tools such as DVC, MLflow, and Jenkins to enhance project delivery efficiency.

## Deployment

The machine learning model can be deployed on cloud platforms, edge devices, or locally, depending on the system design. Justifications for the chosen deployment approach are provided in the documentation.

## Solutions Design

Complete solution design strategies are documented in both High-Level Design (HLD) and Low-Level Design (LLD) documents.

## System Architecture

The wireframe document and architecture document outline the system architecture, providing insights into how different components interact.

## Latency for Model Response

Response time measurements for the model are conducted to assess its efficiency for a given dataset input.

## Optimization of Solutions

The project is optimized at the code and architecture levels. Test cases are included to validate the effectiveness of the optimizations.

## Author 
Yash Santosh Dabke
Email: yash11usa@gmail.com
GitHub: https://github.com/yashdabke
