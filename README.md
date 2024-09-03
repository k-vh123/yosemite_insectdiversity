# Yosemite National Park Native Insect Biodiversity Analysis

![California Sister Butterfly in Yosemite (Adelpha californica)](https://media.istockphoto.com/id/539461046/photo/california-sister-butterfly-yosemite-national-park.webp?a=1&b=1&s=612x612&w=0&k=20&c=OyCqcTqTQBMfjP8VClSi5ERJWmDWkKTF-AyloWae4zY= "California Sister Butterfly in Yosemite (Adelpha californica)")

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Analysis Components](#analysis-components)
  - [Python Analysis](#python-analysis)
  - [Tableau Visualizations](#tableau-visualizations)
- [Key Findings](#key-findings)
- [Sustainability Perspective](#sustainability-perspective)
  - [Conservation Relevance](#conservation-relevance)
  - [Business Relevance](#business-relevance)
  - [Technological Relevance](#technological-relevance)
- [Future Directions](#future-directions)
- [Acknowledgments and Data Citation](#acknowledgments-and-data-citation)

## Project Overview
This project analyzes insect biodiversity data collected from Yosemite National Park between 2014 and 2024. Using a combination of Python data analysis in the Jupyter extension of Visual Studio Code and Tableau visualizations, I explored patterns in insect observations, focusing on species diversity, seasonal trends, and the most frequently observed species. Data was restricted to research-grade observations of native species only.

## Data Source
The data was sourced from iNaturalist, a citizen science project and online social network of naturalists, citizen scientists, and biologists. It contains research-quality observations of insects in Yosemite National Park.

## Analysis Components

### Python Analysis
- Species richness calculation
  
  <img width="789" alt="python1 1" src="https://github.com/user-attachments/assets/d0dc3a4e-cb5c-471f-990d-4e1775d13dc3">

  <img width="790" alt="python1 2" src="https://github.com/user-attachments/assets/265ad1f2-1732-4e66-b0ed-1ba68c325c18">
  
- Identification of most common species
  
  <img width="789" alt="python2" src="https://github.com/user-attachments/assets/2d031fdb-aef3-4fc0-a633-d9fd054e544b">

- Temporal trends in observations

  <img width="795" alt="python3" src="https://github.com/user-attachments/assets/ef6eca64-6f1f-497b-bcc7-f6a126e31a36">

- Seasonal patterns analysis

  <img width="791" alt="python4" src="https://github.com/user-attachments/assets/2fd45516-f381-4211-ab90-b34536bcac1e">
  
- Order and family distribution

  <img width="790" alt="python5" src="https://github.com/user-attachments/assets/b11f389d-8add-43f7-a225-f3274d4c35d2">

  <img width="789" alt="python6" src="https://github.com/user-attachments/assets/33eecfb6-bbfa-4929-ae8b-04f6f89581be">
  
- Species accumulation curve

  <img width="789" alt="python7" src="https://github.com/user-attachments/assets/41a011f1-c1f8-4234-bd00-0503a0910546">
  
### Tableau Visualizations

 **Top Three Most Frequently Observed Insect Species (2014-2024)**
  - Line chart showing monthly observation counts for California Sister, Pale Swallowtail, and Convergent Lady Beetle
  - Reveals clear seasonal patterns and differences in abundance between species

  <img width="941" alt="tableau1" src="https://github.com/user-attachments/assets/4a69474a-826e-4e12-9899-4e64a4f92b85"><br /> <br /> 

    
**Top Five Most Frequently Observed Insect Orders in June (2014-2024)**
  - Bubble chart displaying the relative abundance of insect orders
  - Highlights the dominance of Lepidoptera in June observations

  <img width="909" alt="tableau2" src="https://github.com/user-attachments/assets/07a889c0-dcb0-4e36-a2b5-c57d5d07a5c7"><br /> <br /> 
  


## Key Findings

Species Richness: The dataset contains 365 unique species, indicating a high native biodiversity in Yosemite National Park.

Most Common Species: California Sister, Pale Swallowtail, and Convergent Lady Beetle are the most frequently observed insects in the park.

  ![pyviz1](https://github.com/user-attachments/assets/85d25546-7161-4078-b051-ad99aac9ca7d)


Observations Over Time: There is a general trend of increasing observations from 2014 to 2024, with peaks in recent years.

  ![pyviz2](https://github.com/user-attachments/assets/82c84cee-2d9c-431d-8a40-3f89e365bc83)


Seasonal Patterns: Insect activity peaks in July, with the lowest activity in January.

  ![pyviz3](https://github.com/user-attachments/assets/e1330f5c-b727-4bdd-8e6c-ea5b1fdd276d)


Order Distribution: Lepidoptera (butterflies and moths) is the most represented insect order in the park.

  ![pyviz4](https://github.com/user-attachments/assets/28144b71-c6c7-4a62-9ef5-5e21e2442240)

  <img width="335" alt="pyviz4 1" src="https://github.com/user-attachments/assets/fbd27ad6-a445-48c1-9400-6a6159a3fc47">


Family Distribution: Nymphalidae (brush-footed butterflies) is the most observed insect family.

  ![pyviz5](https://github.com/user-attachments/assets/c602d7fa-69b8-452d-8523-533aff0a8014)

Species Accumulation: The curve does not show clear signs of plateauing, suggesting that more species are likely to be discovered with increased sampling effort.

  ![pyviz6](https://github.com/user-attachments/assets/a4e11db3-b370-490f-92e6-17b306439100)


## Sustainability Perspective

### Conservation Relevance:
- The species richness data can be used as a baseline for future biodiversity assessments in Yosemite.
- Seasonal patterns can inform conservation efforts, focusing protection measures during peak activity periods.
- The species accumulation curve can guide sampling efforts, indicating that more intensive surveys could reveal additional species.

### Business Relevance:
- Ecotourism companies can use seasonal data to plan insect-focused tours during peak activity months, especially July and August.
- The most common species information can be used in developing educational materials and guidebooks, featuring butterflies prominently.
- Seasonal patterns can inform staffing decisions for park-related businesses, with increased staffing needed during summer months.

### Technological Relevance:
- The dataset can be used to develop and test machine learning models for species identification and population trend predictions, particularly for Lepidoptera.
- Seasonal and temporal data can be integrated into park management apps to provide real-time information to visitors about likely insect sightings.
- The correlation analysis could be extended to develop more sophisticated predictive models for insect activity, potentially incorporating climate data.

This analysis provides valuable insights into the native insect biodiversity of Yosemite National Park, which can be used to inform conservation strategies, enhance visitor experiences, and develop technological solutions for biodiversity monitoring and prediction.

## Future Directions
- Incorporate weather and climate data to analyze correlations with insect activity.
- Expand the analysis to include rare species and their conservation needs.
- Develop a machine learning model to predict future trends in insect populations based on this historical data.

## Acknowledgments and Data Citation
Data for this project was sourced from iNaturalist. I thank the community of observers and identifiers who contributed to this dataset.

iNaturalist. (2024). Native insect observations from Yosemite National Park, CA. 
Retrieved September 1, 2024 from https://www.inaturalist.org/
Accessed through GBIF.org on September 1, 2024.



---

This project underscores the importance of long-term ecological monitoring and the value of citizen science in understanding and preserving biodiversity. By leveraging technology and data analysis, we can gain crucial insights into the health of our ecosystems and inform sustainable management practices for protected areas like Yosemite National Park.
