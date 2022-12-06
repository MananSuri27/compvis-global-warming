# compvis-global-warming

Developed as a part of lab assessment for COCSC17- Machine Learning.

## Task
Given a dataset, think of an ML application and develop a prototype of the same.



## Application:
Based on changes detected in satellite data, we want to predict the mean average temperature for a region. This analysis over different regions and across years of data will be helpful in analyzing global warming and predicting future trends.

## Model Architecture:

![Model Architecture](https://cdn.discordapp.com/attachments/891317274936483871/1049830648199794788/lab_project.png)


The model is developed on PyTorch.

We have used dummy data to train the model and check the code for now.

## Dataset
Gateway to Indian Earth Observatory

Bhuvan is a geoportal developed by ISRO which has open-source geo-spacial data and allows users access to IRS (Remote Sensing) images.

Platform:
![](https://cdn.discordapp.com/attachments/891317274936483871/1049830409778757632/image.png)

It has a wide variety of data on different domains mapped across India. Some of the domains include:
- Infrastructure: Roads, railways, settlements
- Hydrological Boundaries: Basin, sub-basin, water bodies
- Agriculture: Vegetation, land use, irrigation, ground water
- Population analytics

The data is sourced from different satellites including:
![](https://cdn.discordapp.com/attachments/891317274936483871/1049830440489467945/image.png)

We will be working with a specific subset of maps:
- Albedo Map:
Albedo maps represent the amount of sunlight reflected from the earth’s surface. They are used to study cloud presence and snow as they are highly absorbent and highly reflective, respectively.

- Altitude Map:
Represents the altitude of a region

- Precipitation Map:
A precipitation map represents the amount of rainfall, and precipitation in every area.

The given data is available across years.

