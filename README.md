# airbnb-vacation-rental-market-analysis

![Esta es una imagen](/Datos/Imagenes/featured.jpg)

- [Introduction](#introduction)
- [Objectives](#objectives)
- [Project results](#project-results)
- [Project structure](#project-structure)
- [Instructions](#instructions)

## Introduction <a name="introduction"></a>
The client is a Real Estate company that invests in large cities by buying properties to later rent them out as vacation apartments.

The managers have made the decision to invest in Madrid, and are interested in analysing the data that the sector leader AirBnb makes public to try to find the types of properties that have the greatest commercial potential for vacation rental.

As a main deliverable, the management expects to receive the typology (or typologies) of properties that the valuation team should look for among the existing opportunities in the city and the main neighborhoods or geographic areas to focus on.

- [See a technical explanation of the project here.](https://pedrocorma.github.io/project/5realstate/)

## Objectives <a name="objectives"></a>
Analysing available public data sources to find insights that help to understand the characteristics of the market in Madrid city and guide the valuation team’s research work, especially in terms of the main angles: rental prices, occupancy levels and purchase prices.

## Project results  <a name="project-results"></a>
**1. 10 neighborhoods with a high investment potential have been identified**

- There are 10 neighborhoods that a priori can maximize the cost-income ratio.
- They can also be segmented by the type and quality of the property in which we are interested in investing in 4 main groups.
- These are the neighborhoods where to start looking for specific opportunities:
  - Low Investment: Simancas, Ambroz, Marroquina, San Juan Bautista.
  - Medium investment: El Plantio, Valdemarín, Valdefuentes.
  - Medium-high investment: Jerónimos, Fuentela reina.
  - High investment: Recoletos.

**2. It is recommended to search for one-bedroom properties that can accommodate 3 guests.**

- The number of guests that maximizes the purchase price paid is 3.

**3. It is recommended to search for properties in one of the identified neighborhoods that are not necessarily close to points of interest.**

- This properties are expected to have a lower purchase price.
- It appears that proximity to points of interest does not have a particular impact on rental prices.

**4. A new business model based on rentals for specific moments of high sporting interest, especially in the San Blas neighborhood should be explored.**

- It is advisable to look for opportunities in the San Blas neighborhood.
- The relationship between the purchase price and the rental price per night is quite good.
- There are still many rentals that are not exploiting this potential.

## Project structure <a name="project-structure"></a>
- :file_folder: Datos: Project datasets.
  - :file_folder: Imagenes:  Contains project images.
- :file_folder: Notebooks
  - `01_Diseño del proyecto.ipynb`: Notebook compiling the initial design of the project.
  - `02_Analisis de ficheros y preparacion del caso.ipynb`:
  - `03_Creacion del Datamart Analitico.ipynb`: Notebook creating analitic datamart (loading and unifying data, applying data quality processes, ...).
  - `04_Preparacion de datos.ipynb`: Notebook compilling feature engineering processes.
  - `05_Analisis e Insights.ipynb`: Notebook used for the execution of the exploratory data analysis and which collects the business insights found as well as the recommended actionable initiatives.
  - `06_Comunicacion de resultados.ipynb`: Brief executive report for the communication of results using McKinsey's Exhibits methodology.

## Instructions  <a name="instructions"></a>
- Unzip airbnb.rar under 'Datos' folder.
- Remember to update the `project_path` to the path where you have replicated the project.

