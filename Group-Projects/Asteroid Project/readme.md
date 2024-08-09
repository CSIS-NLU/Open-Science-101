# Team AstroPioneers: Asteroid Impact Risk Assessment Project (AIRAP)

**Descripton of Research**:

> The Astro Pioneers' Asteroid Impact Risk Assessment Project (AIRAP) is dedicated to evaluating and analyzing data from NASA's Nearest Earth Objects (1910-2024) to assess the potential risks these asteroids pose to our planet. The project focuses on asteroids with diameters that could cause substantial damage if they were to impact Earth, specifically targeting those within a significant size range. Our analysis examines asteroid proximity to Earth, determining which asteroids—whether large or small, with varying velocities—are likely to come closer to our planet.

> By carefully studying these factors, the project aims to provide essential risk assessments, identifying asteroids with a significant probability of impact in the coming centuries. The findings from AIRAP are crucial for developing potential mitigation strategies and enhancing global preparedness against possible asteroid threats. Throughout the project, we have adhered to NASA's Open Science principles—Open Data, Open Tools, Open Code, and Open Results—and have ensured our research aligns with the FAIR principles, making our data Findable, Accessible, Interoperable, and Reusable.

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

### Screenshots:

![Asteroids on the way to Earth](/Group-Projects/Asteroid%20Project/asteroids.jpg) _Screenshot 1
(Asteroids on the way to Earth)_

---

**Initial Observations and Progress:**

### Day 1: Initial Observations and Progress

As of the first day of our workshop at NASA, we have started gathering resources and defining the scope of our research. Our focus is on NASA's Nearest Earth Objects (1910-2024). Over the next week, we will be examining various datasets and code repositories to evaluate their compliance with Open Science and FAIR Principles. Further updates and detailed observations will be added as the project progresses.

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

### Day 4:

---

**Project Artifacts:**

- `AsteroidData.ipynb` - Initial data exploration, focusing on data cleaning and basic analysis.
- `AsteroidData2.ipynb` - In-depth analysis with visualizations of asteroid size and velocity.
- `AsteroidData.csv` - Dataset used in the project, containing relevant asteroid information from NASA.

---

**Research Questions:**

1. On average, how many asteroids are hazardous to Earth?
2. What is the average miss distance of asteroids?
3. What is the size distribution of asteroids?
4. How far/close are asteroids from Earth?
5. How many asteroids are considered harmful?
6. What is the ratio between harmful and non-harmful asteroids?
7. What are the statistical measures for each attribute/field/column?
8. Do bigger (size) asteroids move faster than smaller ones?

---

**Hypothesis:**

> Asteroids with smaller diameters have greater velocity.

### Our Observations:

- **Smaller Asteroids' Velocity**: Our analysis confirmed that smaller asteroids tend to have greater velocity than larger ones, aligning with our hypothesis.
- **Hazardous Asteroids**:
- **Miss Distance Patterns**:

Each observation was derived from the analysis conducted through Python and Pandas, with significant guidance from Dr. Antonio.

## URL Links:

- **Powerpoint**: [Powerpoint]()
- **Excel Sheet Data**: [Project Dataset](https://docs.google.com/spreadsheets/d/1Q_QM-YqW9yW4P4PteW9sOijVi2MwfEhaOKOLoTSNZLk/edit?usp=sharing)
- **Project Description**: [Nearest Earth Objects Project Description](https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024)
- **Project Data**: [Nearest Earth Objects Dataset](https://github.com/CSIS-NLU/Open-Science-101/tree/main/Group-Projects/Asteroid%20Project/data)

---

## Research Project Team:

- Dr. Antonio Tovar - Project Advisor - ORCID: 0000-0002-4585-2122 - [GitHub](https://github.com/antoniotovargh)
- Alex Smagin - Project Team Member - ORCID: 0009-0007-6588-1565 - [GitHub](https://github.com/Alexandrbig1)
- Alina Zholdubaeva - Project Team Member - ORCID: 0009-0009-3548-1151 - [GitHub](https://github.com/Alinka8)
- Jasmin Duishebaeva - Project Team Member - ORCID: 0009-0005-6258-0447
- Jordi Rodriguez - Project Team Member - ORCID: 0009-0004-1036-3187

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

We would like to thank Dr. Antonio Tovar for his invaluable guidance throughout this project. His insights and feedback were instrumental in refining our analysis and validating our findings.

---
