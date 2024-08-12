# Team AstroPioneers: Analyzing the Velocity Distribution of Small Asteroids

### Descripton of Research:

> This project investigates the relationship between the size and velocity of asteroids within our solar system. Our central hypothesis posits that smaller asteroids exhibit greater velocities compared to their larger counterparts. To explore this hypothesis, we analyzed a comprehensive dataset of asteroid observations, focusing on key attributes such as size, velocity, and orbital parameters.

### Objectives:

1. **Hypothesis Testing:** To examine whether smaller asteroids indeed have higher velocities than larger ones, as hypothesized.
2. **Data Visualization:** To develop a suite of visualizations that effectively represent the distribution of asteroid attributes and reveal patterns or correlations between size and velocity.

### Methodology:

1. **Data Collection:** We utilized a robust dataset containing attributes of numerous asteroids, including their sizes, velocities, and orbital characteristics. This dataset was sourced from kaggle.com, a reliable astronomical dataset and research source.

2. **Data Preparation:** The dataset was cleaned and preprocessed to ensure accuracy and consistency. This involved handling missing values, normalizing measurements, and categorizing data into relevant groups.

3. **Visualization Techniques:** A variety of visualization methods were employed to analyze and interpret the data. This included scatter plots to depict the relationship between asteroid size and velocity, histograms to show the distribution of velocities across different size ranges, and correlation heatmaps to identify potential patterns or anomalies.

4. **Statistical Analysis:** We applied statistical tests to quantify the relationship between asteroid size and velocity.

### Results:

The visualizations and statistical analyses provided clear insights into the relationship between asteroid size and velocity. Our findings supported the hypothesis that smaller asteroids tend to have higher velocities compared to larger ones. This was evident from the scatter and attribute correlation plots showing a trend where smaller asteroids clustered at higher velocity ranges.

### Conclusion:

The project successfully validated the hypothesis that smaller asteroids possess greater velocities. The comprehensive data visualization approach facilitated a deeper understanding of the attributes and interactions within the asteroid dataset, leading to valuable conclusions about their dynamic behaviors. These insights contribute to the broader field of asteroid research and may have implications for future studies on asteroid dynamics and their impact on space exploration.

---

## Table of Contents

- [Terminology](#terminology)
- [Screenshots](#screenshots)
- [Workshop Details and Progress](#workshop-details-and-progress)
- [Project Artifacts](#project-artifacts)
- [Research Questions](#research-questions)
- [Hypothesis](#hypothesis)
- [Our Observations](#our-observations)
- [URL Links](#url-links)
- [Research Project Team](#research-project-team)
- [Citations](#citations)
- [Issues](#issues)
- [Feedback](#feedback)
- [Acknowledgments](#acknowledgments)

---

## Terminology

- **Open Science**: A movement to make scientific research, data, and dissemination accessible to all. It encompasses four key components:

  - **Open Data**: Data that is freely available for anyone to use, modify, and share.
  - **Open Code**: Source code that is made available to the public, allowing others to use, modify, and distribute it.
  - **Open Source**: Software for which the original source code is made freely available and may be redistributed and modified.
  - **Open Results**: The outcomes of research, including publications and data, that are freely accessible to the public.

- **FAIR Principles**: Guidelines that ensure that research data is:
  - **Findable**: Data should be easy to find by both humans and computers, with metadata that clearly describes the data.
  - **Accessible**: Data should be retrievable by authorized users, using standardized protocols.
  - **Interoperable**: Data should be compatible with other datasets and tools, allowing for integration and analysis across various platforms.
  - **Reusable**: Data should be well-documented and licensed for reuse, allowing others to replicate or build upon the research.

---

## Screenshots:

![Asteroids on the way to Earth](/Group-Projects/Asteroid%20Project/images/asteroids.jpg) _Screenshot 1
(Asteroids on the way to Earth)_

---

## Workshop Details and Progress

### Day 1: Defining Scope and Data Discovery

On the first day of our workshop at NASA, we started by gathering resources and defining the scope of our research. Our focus is on NASA's Nearest Earth Objects (1910-2024). During our initial exploration, we found a relevant dataset on Kaggle, which we plan to explore and work with in the coming days. Over the next week, we will examine various datasets and code repositories to evaluate their compliance with Open Science and FAIR Principles. Further updates and detailed observations will be added as the project progresses.

### Day 2: Preparing Questions and Hypotheses

On the second day of our workshop, we focused on preparing the right questions to guide our research. These questions will help us delve deeper into the data and extract meaningful insights. Here are the questions we developed:

- On average, how many asteroids are hazardous to Earth?
- What is the average miss distance of asteroids?
- What is the size distribution of asteroids?
- How far/close are asteroids from Earth?
- How many asteroids are considered harmful?
- What is the ratio between harmful and non-harmful asteroids?
- What are the statistical measures for each attribute/field/column?
- Do bigger (size) asteroids move faster than smaller ones?

We also formulated a hypothesis to test:

- **Hypothesis**: Asteroids with smaller diameters have greater velocity.

To support our research, we created functions to calculate key metrics:

- A function to find the average diameter of asteroids.
- A function to find the average velocity of asteroids.

These foundational steps will guide us as we dive deeper into the analysis of NASA's asteroid data in the coming days.

### Day 3: Validating Our Hypothesis

On Day 3 of our NASA workshop, we focused on testing our hypothesis: **Do smaller asteroids move faster than larger ones?** With the right questions in mind, we utilized Python and Pandas to build functions that allowed us to analyze our asteroid data in detail.

**Key Steps**:

- **Data Analysis:** We developed Python functions to extract and analyze key metrics.
- **Visualization:** We created a diagram to visualize the relationship between asteroid size and velocity.
- **Findings:** The analysis confirmed our hypothesis—smaller asteroids tend to move faster than larger ones.

Dr. Antonio's guidance was instrumental in refining our approach and ensuring the accuracy of our findings.

### Day 4: Preparing for the Final Presentation

On Day 4, having proven our hypothesis that smaller asteroids tend to move faster than larger ones, we shifted our focus towards preparing for the final presentation. This presentation will showcase all aspects of our project, including detailed explanations of our research, the methodologies employed, and the key learnings we gathered throughout the NASA TOPS workshop. The presentation will be delivered using PowerPoint, highlighting both our analytical process and the broader significance of our findings.

### Day 5: Presentation Day

On the final day of the workshop, we presented our project to the professors from National Louis University and the NASA TOPS team. Each team member took part in the presentation:

- **Alina and Jasmin**: Presented the PowerPoint slides, explaining the project description, research questions, and hypothesis.
- **Jordi**: Discussed the dataset, including how we sourced the data, verified its accuracy, and assessed the credibility of the authors and sources.
- **Alex**: Detailed the coding aspects, including the Python, R, and Pandas functions used in our analysis, and demonstrated how we validated our hypothesis with the results shown in our charts.

After the presentation, we were awarded certificates for successfully completing the NASA TOPS workshop and received badges from the NASA team.

---

## Project Artifacts:

- `AsteroidData.ipynb` - Initial data exploration, focusing on data cleaning and basic analysis.
- `AsteroidData2.ipynb` - In-depth analysis with visualizations of asteroid size and velocity.
- `Visualization_of_AsteroidData.ipynb` - In-depth analysis with visualizations of the full dataset.
- `Visualization_of_AsteroidData_version_2_0.ipynb` - In-depth analysis with visualizations of the full dataset.

---

## Research Questions:

1. On average, how many asteroids are hazardous to Earth?
2. What is the average miss distance of asteroids?
3. What is the size distribution of asteroids?
4. How far/close are asteroids from Earth?
5. How many asteroids are considered harmful?
6. What is the ratio between harmful and non-harmful asteroids?
7. What are the statistical measures for each attribute/field/column?
8. Do bigger (size) asteroids move faster than smaller ones?

---

## Hypothesis:

> Asteroids with smaller diameters have greater velocity.

---

## Our Observations:

- **Smaller Asteroids' Velocity**: Our analysis confirmed that smaller asteroids move faster than larger ones, supporting our hypothesis. The data shows a clear trend of higher velocities for smaller asteroids.
- **Hazardous Asteroids**: The data reveals that most asteroids are non-hazardous, with hazardous ones being relatively few. This is illustrated by our diagram, which shows a predominance of non-hazardous asteroids.
- **Miss Distance Patterns**: Faster asteroids generally have greater miss distances from Earth. Our data indicates that high-velocity asteroids are less likely to come close to our planet.

Each observation was derived from the analysis conducted through Python and Pandas, with significant guidance from Dr. Antonio.

---

## URL Links:

- **Powerpoint**: [Powerpoint](https://docs.google.com/presentation/d/1r9Vi_z3EddbH_eHS5Gd_BBTkE0VKa03nxBB9hihftqc/edit#slide=id.g10eb5cd01b8_0_24)
- **Excel Sheet Data**: [Project Dataset](https://docs.google.com/spreadsheets/d/1Q_QM-YqW9yW4P4PteW9sOijVi2MwfEhaOKOLoTSNZLk/edit?usp=sharing)
- **Project Description**: [Nearest Earth Objects Project Description](https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024)

---

## Research Project Team:

- Dr. Antonio Tovar - Project Advisor - ORCID: 0000-0002-4585-2122 - [GitHub](https://github.com/antoniotovargh)
- Alex Smagin - Project Team Member - ORCID: 0009-0007-6588-1565 - [GitHub](https://github.com/Alexandrbig1)
- Alina Zholdubaeva - Project Team Member - ORCID: 0009-0009-3548-1151 - [GitHub](https://github.com/Alinka8)
- Jasmin Duishebaeva - Project Team Member - ORCID: 0009-0005-6258-0447
- Jordi Rodriguez - Project Team Member - ORCID: 0009-0004-1036-3187 - [GitHub](https://github.com/JR224-jpg)

---

## Citations:

- [Scientific Method](https://en.wikipedia.org/wiki/Near-Earth_object)
- [NASA Modules for Open Science](https://openscience101.org/about)
- [NASA FAIR Principles](https://www.earthdata.nasa.gov/learn/articles/making-earth-science-data-fair#:~:text=NASA%20is%20working%20to%20ensure,FAIR)
- [FAIR Assessment](https://www.f-uji.net/index.php)

---

## Issues

If you encounter any issues, bugs, or have suggestions for improvement, please feel free to [open an issue](https://github.com/CSIS-NLU/Open-Science-101/issues) on our GitHub repository. We encourage you to report any discrepancies in data, functionality issues with our code, or anything else that could help us improve the quality of our project. Your feedback is invaluable in helping us refine our work.

---

## Feedback

We greatly value feedback from the community and project stakeholders. If you have any insights, suggestions, or comments that could help enhance our project, please reach out to us. You can provide feedback by:

- **Opening an issue** on our GitHub repository.
- **Contacting a team member** directly through GitHub.
- **Submitting a pull request** with suggested improvements or corrections.

Your contributions help us to ensure the accuracy, relevance, and impact of our research.

---

## Acknowledgments

We would like to extend our heartfelt thanks to all the National Louis University professors who guided us throughout this workshop. We greatly appreciate their knowledge, experience, and the invaluable advice they shared with us:

- PhD Antonio Tovar
- PhD Abdullah Alshboul
- PhD Toni Holden-McGee
- PhD Phuong Thai-Garcia
- PhD Ian Moncrief
- PhD Robyn Moncrief

We are also deeply grateful to NASA TOPS Open-Science Workshop for this incredible opportunity. Their influence on students, developers, programmers, and coders through this initiative is invaluable.

Special thanks to our project team — Alex Smagin, Jordi Rodriguez, Jasmin Duishebaeva, and Alina Zholdubaeva — for making this experience remarkable. We also appreciate Akshay Mestry for his support and advice throughout our project.

Lastly, we thank National Louis University at Wheeling for providing the space that made this workshop possible.

---
