# NYC Public Safety Data App

### *Advanced Computing Final Project*

> **Project Summary**  
> An interactive Streamlit application designed to explore patterns in New York City public safety and police misconduct data through clear, data-driven visualizations.

---

## Quick Overview

**Course:** Advanced Computing  
**Project Type:** Interactive Data Application  
**Tools Used:** Python, Streamlit, Pandas, BigQuery, Plotly, GitHub, GitHub Actions  
**Live App:** [Police Misconduct Analysis in New York City](https://fuzzy-potato-kmst2vvnvebesjvs2b9kyh.streamlit.app/)

---

## Project Overview

For our **Advanced Computing final project**, my team built an interactive Streamlit application to analyze public safety and police misconduct data in New York City. The project integrates multiple public datasets related to NYPD complaints, civilian allegations, and officer-level records, and transforms them into a more accessible, interactive dashboard.

Rather than presenting the data only through static charts or tables, we wanted to create a tool that allows users to **interactively explore important patterns** in the data. Our project focused on three main questions:

- **Are misconduct complaints concentrated among a small group of officers?**
- **How do complaint patterns differ across officer groups?**
- **Are precinct-level complaint patterns associated with broader public safety conditions?**

The goal of the app was not only to support analysis, but also to improve **clarity, accessibility, and usability** for both technical and non-technical audiences.

---

## My Role

In this project, I mainly contributed to the **data processing workflow, cloud database integration, and visualization development**.

### My main contributions included:

- **Data cleaning and preparation**  
  I helped organize and process public datasets, standardize variables, and prepare the data for analysis.

- **BigQuery-based data workflow**  
  One of my key contributions was helping move the project from direct API-based data loading to a **BigQuery-based pipeline**, which improved both speed and stability.

- **Analytical metric construction**  
  I supported the logic for aggregating officer-level and group-level complaint patterns, including measures such as **complaint concentration**, **substantiation rates**, and **group comparison metrics**.

- **Visualization design**  
  I worked on charts that communicate findings more clearly, including concentration analysis and group comparison visuals.

- **App structure and usability**  
  I also contributed to organizing the app around clear research questions so that users could navigate the dashboard more intuitively.

---

## Tools and Methods

| Category | Details |
|---------|---------|
| **Programming** | Python |
| **App Framework** | Streamlit |
| **Data Processing** | Pandas |
| **Database** | Google BigQuery |
| **Visualization** | Plotly / interactive charts |
| **Version Control** | Git & GitHub |
| **Deployment / Workflow** | GitHub Actions, Streamlit Cloud |

In this project, we combined **data engineering, analytical thinking, and dashboard design**. We used Pandas for data cleaning and aggregation, BigQuery for more efficient querying, and Streamlit for building the application interface.

Because the datasets were relatively large, app performance became an important concern. Loading everything directly through APIs made the app slower and less reliable. To improve the user experience, we adopted several strategies:

- **Using BigQuery instead of direct API pulls**
- **Applying caching in Streamlit**
- **Pre-aggregating data where appropriate**
- **Reducing unnecessary data load in the interface**

These technical improvements helped make the dashboard faster and more practical as a public-facing application.

---

## Key Features

The final app includes several main features:

### 1. Complaint Concentration Analysis
We used tools such as the **Lorenz curve** and **Gini-style analysis** to examine whether complaints are concentrated among a relatively small number of officers.

### 2. Group Comparison
The app compares complaint burden and substantiation intensity across different officer groups, helping users identify meaningful differences.

### 3. Interactive Visualizations
Users can interact with charts and explore patterns by category, which makes the findings easier to interpret.

### 4. Research Question-Based Structure
Instead of displaying isolated charts, the app is organized around clear analytical questions, giving the project a stronger narrative structure.

### 5. Public-Facing Dashboard Design
The project was developed as a live application, which means usability, page structure, and clarity were important parts of the work.

---

## Screenshots

Below are screenshots of the application in case the live version becomes unavailable.

### Homepage
![Homepage](screenshot1.png)

### Complaint Concentration Analysis
![Complaint concentration analysis](screenshot2.png)

### Group Comparison Visualization
![Group comparison visualization](screenshot3.png)

---

## Challenges and What I Learned

This project taught me that building a data product is different from simply completing a data analysis in a notebook.

One important lesson was that **good analysis alone is not enough**. If the app is slow, difficult to navigate, or visually unclear, users may not fully understand the value of the work. Through this project, I gained a better understanding of how **backend data decisions directly affect frontend user experience**.

I also learned more about how to turn a technical workflow into a **user-friendly analytical tool**. In addition to working with data cleaning and cloud-based querying, I had to think about how to structure the content, how to make the charts more interpretable, and how to make the app feel coherent across different pages.

Finally, this project strengthened my experience in **team-based technical collaboration**. We needed to divide responsibilities, review each other’s work, and make sure the final product was both technically sound and visually consistent.

---

## Reflection

Overall, this project helped me strengthen my skills in:

- **data cleaning and transformation**
- **interactive dashboard development**
- **BigQuery-based data workflows**
- **performance optimization**
- **communicating analytical findings through visualization**

More importantly, it showed me how data analysis can become more impactful when it is presented through an interactive, well-structured, and user-centered application.

---

## Final Takeaway

> This project was a valuable experience in combining **data analysis**, **technical implementation**, and **visual communication** into a single public-facing product. It helped me better understand how to build data tools that are not only analytically rigorous, but also accessible and useful to others.
