# Power-BI-Project-Based-Learning-Platform
An interactive, project-based learning path for mastering Power BI, from initial setup to advanced dashboard creation and enterprise deployment. This application showcases a complete end-to-end BI project, including a visually rich e-commerce dashboard.


**Author**: Anas Riaz | [**Live Site**](https://raoanasriaz-powerbi-project.vercel.app/) | [**LinkedIn**](https://www.linkedin.com/in/raoanasriaz/) | [**GitHub**](https://github.com/rao-anas-riaz)

<p align="center">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure"/>
  <img src="https://img.shields.io/badge/DAX-2E8B57?style=for-the-badge" alt="DAX"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL"/>
</p>

This repository contains the source code for an interactive web application that serves as a project-based learning path for mastering Power BI. The application guides users through two complete, end-to-end Business Intelligence solutions, from initial data generation and cloud setup to advanced dashboard creation and enterprise deployment.

---

## Table of Contents
1.  [Project Overview](#project-overview)
2.  [Technology Stack](#technology-stack)
3.  [Key Features](#key-features)
4.  [Project Architecture](#project-architecture)
5.  [Phase-by-Phase Walkthrough](#phase-by-phase-walkthrough)
6.  [Running the Project Locally](#running-the-project-locally)

---

## Project Overview

This project is more than a dashboard; it's a comprehensive, guided curriculum designed to teach the full lifecycle of a modern BI solution. It showcases two distinct projects:

1.  **AI Sales Model Analysis**: The primary project analyzes the effectiveness of an AI model at a telecom company. It involves building a full cloud data pipeline in Azure, performing advanced DAX calculations to correct for statistical paradoxes, and creating a strategic dashboard for management.
2.  **E-commerce Portfolio Dashboard**: A secondary project focused on advanced visualization techniques. It involves building a feature-rich, multi-page e-commerce dashboard designed to showcase portfolio-grade design and complex KPI implementation.

### Project Scenario
You are a Data Scientist at ConnectSphere Telecoms. The company has developed a new AI model that intelligently pairs incoming customer calls with the sales agent most likely to close a sale. This model is being tested against the traditional standard routing system. Management needs a robust Power BI solution to analyze the test data, determine if the AI model is effective, identify its financial impact, and understand the key drivers of successful sales.

### Learning Objectives
This project is designed to demonstrate a wide array of skills essential for a modern Data Analyst or BI Developer:
-   **End-to-End Cloud Data Engineering**: Architecting and building an automated ETL pipeline in Microsoft Azure.
-   **Advanced Data Modeling & DAX**: Implementing a performance-optimized star schema and writing complex DAX measures.
-   **Portfolio-Grade Visualization**: Designing and building two distinct, multi-page reports for different analytical purposes.
-   **Dynamic & Interactive UX Design**: Creating an app-like user experience with navigation, custom tooltips, and drillthrough functionality.
-   **AI-Powered Analytics**: Leveraging Power BI's built-in AI capabilities like Key Influencers and Clustering.
-   **Enterprise Deployment & Security**: Managing the deployment lifecycle, including scheduled refreshes and Row-Level Security (RLS).
-   **Professional Tooling**: Utilizing industry-standard external tools like DAX Studio and Tabular Editor.

## Technology Stack

| Category                  | Technologies & Tools Used                                                      |
| ------------------------- | ------------------------------------------------------------------------------ |
| **Frontend & UI**         | React, TypeScript, Tailwind CSS, Font Awesome                                  |
| **BI & Visualization**    | Power BI Desktop, Power BI Service                                             |
| **Cloud Platform**        | Microsoft Azure (Data Lake Gen2, Data Factory, SQL Database)                   |
| **Languages**             | DAX, M (Power Query), SQL, Python (Pandas, Faker)                              |
| **Advanced Tools**        | DAX Studio, Tabular Editor                                                     |
| **Version Control**       | Git & GitHub                                                                   |
| **Build Tool**            | Vite                                                                           |

## Key Features

This web application is a fully-featured Progressive Web App (PWA) with the following capabilities:
-   **Interactive Content**: All phases and steps are displayed in a clean, card-based UI with syntax-highlighted code blocks.
-   **Responsive Design**: The application is fully responsive and works seamlessly on desktop, tablet, and mobile devices.
-   **Search Functionality**: A live search bar allows users to quickly filter the learning phases by title.
-   **Offline Capable**: As a PWA with a registered service worker, the entire application and its content are cached for offline access after the first visit.

## Project Architecture

The solution follows a modern, cloud-based data architecture, ensuring scalability and automation.

`Python Script (Data Generation) -> Azure Data Lake (Staging) -> Azure Data Factory (ETL Pipeline) -> Azure SQL DB (Warehouse) -> Power BI (Modeling & Reporting)`

## Phase-by-Phase Walkthrough

The project is broken down into 13 distinct phases, guiding the user from a blank canvas to a fully deployed enterprise solution.

-   **Phase 1: Foundations & Setup**: Prepare a professional-grade, zero-cost development environment, including Power BI, Azure, and Git.
-   **Phase 2: Data Generation**: Generate realistic, simulated data for the project using a Python script.
-   **Phase 3: Data Warehousing Theory**: Understand the foundational principles of dimensional modeling and star schemas.
-   **Phase 4: Azure Data Integration**: Build an enterprise-grade ETL pipeline in Microsoft Azure to move data from a data lake to a SQL database.
-   **Phase 5: ETL with Power Query**: Perform robust data cleaning, shaping, and profiling on all data sources within Power BI.
-   **Phase 6: Data Modeling**: Build a performance-optimized star schema data model and create a dedicated date dimension.
-   **Phase 7: Mastering DAX**: Write DAX measures to answer the core business questions, including core KPIs and comparative measures.
-   **Phase 8: Visualization & Storytelling**: Design interactive reports that tell a clear story and can be adapted for new analyses.
-   **Phase 8.5: Building a Portfolio-Grade Dashboard**: Build a visually stunning, feature-rich e-commerce dashboard showcasing advanced BI techniques.
-   **Phase 9: Advanced Analytics**: Use Power BI's AI features (Key Influencers, Clustering) to find deeper diagnostic insights.
-   **Phase 10: Enterprise Deployment**: Deploy, manage, and secure the solution in the Power BI Service, including scheduled refresh and RLS.
-   **Phase 11: Portfolio & Documentation**: Finalize and document the project for a professional portfolio, including writing a GitHub README.
-   **Phase 12: Career Development**: Learn how the skills from this project map to the PL-300 certification and how to communicate them in an interview.
-   **Phase 13: Portfolio Expansion**: Discover new project ideas to build a diverse and impressive portfolio.
