# 🌿 NDVI Analysis Project Worksheet  Lehiwa and Makaʻala 

This worksheet will guide you through the process of designing and carrying out an NDVI-based analysis in R. Fill in the prompts for your chosen research question, location, time period, data sources, and methods.  

---

## 1. Framing the Question  

**What environmental or social issue will you explore?**  
Invasive Plant species in Lehua Forest, ROD.
Native ot Non-Native vegitation 
Green = health Lehua 
Black is Dead fungus infected 
Only shows Healhty Green Lehua trees, monitor clusters of healthy trees 
---

**Why is NDVI an appropriate tool for this question?**  
NDVI can be used to track the spread of invasive plants over time by monitoring changes in the vegetation index
As ʻōhiʻa trees sicken and die from ROD, their leaf greenness (chlorophyll content) decreases, and canopy health declines. This change is detectable by NDVI, which would show a corresponding decrease in the vegetation index
---

**Who might find your results meaningful or useful?**  
Department of Forestry and Wildlife
Land and Natural Resource Management 
State legislation for policy and Momney efforts
Local Communites and Non-profit 

---

## 2. Choosing a Place and Time  

**What geographic area will you focus on?**  
Hawaiian Islands 
Before ROD 2000 - During ROD 2008 - Now 2025
---

**What time frame makes sense for your question?**  
(e.g., single date, multiple years, seasonal patterns)  
Multiple Years 

---

**How will you define the scope of your analysis?**  
focus on using time-series satellite data to track and interpret vegetation health changes, and to distinguish ROD-induced mortality from other environmental factors
Differentiate from other disturbances: Isolate the NDVI signature of ROD-related mortality from other causes of vegetation stress, such as drought, fire, deforestation and other invasive species.
---

## 3. Finding Data  

**Where could you get satellite imagery or NDVI data?**  
(https://dlnr.hawaii.gov/hisc/rapid-ohia-death-rod/)
https://earthexplorer.usgs.gov/
https://search.earthdata.nasa.gov/
NOAA website
---

**What resolution and frequency are appropriate?**  
High frequency monitoring

---

**Will you download data manually or use an R package? Which one?**  
*Write your thoughts here:*  

---

## 4. Bringing Data into R  

**What R packages can help you work with spatial data?**  
*Write your thoughts here:*  

---

**How will you handle projections, boundaries, or missing data?**  
*Write your thoughts here:*  

---

**What file formats will you be working with?**  
*Write your thoughts here:*  
Jp2 
shape file 

---

## 5. Calculating NDVI  

**What is the NDVI formula?**  
NDVI = (NIR - Red) / (NIR + Red)

---

**Which spectral bands are needed?**  
For sentinal Near infer red Band 4 and 8
4 and 5 for landsat
---

**How will you apply this formula in R?**  
install and import data
visulize using Terra and ggplot2

---

## 6. Exploring and Visualizing Data  

**How will you summarize NDVI values?**  
(maps, plots, tables)  
combination of maps, plots, and tables to show the spatial patterns, temporal trends, and statistical distribution of vegetation health. This approach helps track the disease's progression, pinpoint affected areas, and identify long-term changes in forest health. 
hotspot, time series, color gradient for NDVI health 
---

**Will you compare locations, beofre and after events, look at seasonal patterns, or study long-term trends?**  
Before and After events
Before 2000 - 2008 Healthy Ohia 2008-2025 Health decline for ROD
pre ROD - current ROD 
---

**How will you make your visualizations clear and interpretable?**  
spatial and temperol analysis 
time-series report

---

## 7. Interpreting Results  

**What patterns or relationships do you expect to see?**  
ROD and NDVI: Expect a negative correlation, where increased ROD presence leads to lower NDVI values, signaling the death and browning of native `ōhiʻa trees. 

---

**How do they relate to your research question?**  
*Write your thoughts here:*  

---

**What uncertainties or data limitations should you acknowledge?**  
*Write your thoughts here:*  

---

## 8. Reflecting on Impact  


**Could your results inform decisions, policies, or further research?**  
*Write your thoughts here:*  

---

**What new questions emerge from your findings?**  
*Write your thoughts here:*  
