---
layout: post
title: Data Visualization Final Project
---

## Introduction



## Data

I choose to use the 2018 Central Park Squirrel Census data from City of New York website. It has a little over 3000 entries in a csv format. There are 31 column fields but some of the key (and funny) ones are the "X" and "Y" (longitude and latitude) coordinates of the squirrel siting, and "Unique Squirrel ID". It also includes information about the squirrel to include "Age" and "Primary Fur Color" and boolean flags describing the action of the squirrel to include "Kuks", "Tail Twitches", and "Runs From".

Apart from having a funny data set to work with, my goals for working with this data set are to see if I can answer some questions that immediately come to mind when looking at this data set. Are there differences in actions from adult and juvenile squirrels? Do different color of squirrels cluster together? Do different colors of squirrels have similar or different activities?

There is already an interactive visualization for this data that is linked at the same website as the data. It is an interactive map that shows the locations of these data points within central park and also their fur color. This visualization is actually pretty good and shows the whole data set, lets you zoom in, and then gives you details when you hover over the mark. The only thing that could be improved is if there was details on the activity of the squirrel siting when hovering over the mark.

## Tasks

### 1. Compare favored activities of adult and juvenile squirrels

- Goal - Explore data to see if there is a difference in adult and juvenile squirrel actions
- Means - Relate age and activity categories
- Characteristics - Ranking most to least common actions (percentage of activities conducted)
- Target Data - Relative reference comparing between age and actions
- Workflow - Take raw data and use the outcomes show differences between adult and juvenile squirrels
- Roles - For a (amateur) squirrel scientist to guide further squirrel research areas

### 2. Compare favored activities of different color of squirrels

- Goal - Explore data to see if there is a difference in cinnamon, gray, and black squirrel actions
- Means - Relate color and activity categories
- Characteristics - Ranking most to least common actions (percentage of activities conducted)
- Target Data - Relative reference comparing between color and actions
- Workflow - Take raw data and use the outcomes show differences between cinnamon, gray, and black squirrels
- Roles - For a (amateur) squirrel scientist to guide further squirrel research areas

### Task 1-2 Design

- Data - 
- Aesthetics
- Scale
- Geometric Objects
- Statistics
- Facets
- Coordinate System

![Hand drawn radar plot](images/radar_hand_drawn.png)

### 3. View distance relationships and clustering of squirrels based on color

- Goal - Explore data to see if there is a clustering of cinnamon, gray, and black squirrels together
- Means - Organize sightings by location and highlight color
- Characteristics - Highest amount of sightings per color in a hexagonal unit
- Target Data - Latitude and longitude of sightings as well as the color of the squirrels
- Workflow - Take raw data and us the outcomes to show if similar colored squirrels tend to stay close together.
- Roles - For a (amateur) squirrel scientist to guide further squirrel research areas

### Task 3 Design

- Data
- Aesthetics
- Scale
- Geometric Objects
- Statistics
- Facets
- Coordinate System

![Hand drawn radar plot](images/hexbin_hand_drawn.png)

## Behavior Visualization

Utilizing the 

![Activity vs Age and Color Radar Plot](images/radar.png)

## Activity Visualization

{% include squirrel_sitings_visualization.html %}

## Evaluation
