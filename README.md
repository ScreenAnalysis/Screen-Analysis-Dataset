# Screen Analysis Dataset

## Overview
This repository contains the dataset used in our study to build and validate a machine learning model for analyzing user screen. The dataset is stored across two folders: DataXL3 and studentdata2, as described below.

### Dataset Details

1. **DataXL3 Folder**  
   The `DataXL3` folder contains three categories of data:

   - **Students in Lab**  
     - Collected using an automated screenshot collection script, which captured a screenshot every 10 seconds while students worked in a controlled lab environment.  
     - The data includes 198 sessions from 27 participants (aged 18-25), all of whom met the DSM-5 criteria for ADHD.  
     - Participants completed an average of 7.4 sessions each, with a maximum of 12 sessions of 50 minutes each.

   - **Authors in Lab**  
     - To balance the dataset, we collected non-focused screenshots by performing activities like browsing, gaming, and using social media.  
     - The dataset includes 3,000 off-task screenshots, captured using the same automated script.

   - **Authors in Lab**  
     - To cover the subtle difference between on-task and off-task video content, we collected 342 screenshots of educational videos from YouTube.  
     - These include lectures, educational content, and edutainment videos.

2. **studentdata2 Folder**  
   The `studentdata2` folder contains the **Students in Wild** dataset:
   
   - **Students in Wild**  
     - This dataset includes 462 screenshots collected directly from students using their own computers in their own settings.  
     - The screenshots include both on-task and off-task activities, providing real-world validation for our model.  
     - To ensure diversity and accurate labeling, students were requested to include educational YouTube videos in their screenshots.  
     - A total of 15 students contributed to this dataset by providing about 20 on-task and 10 off-task labeled screenshots each.

### Data Summary
Below is a summary table of the dataset with the distribution of on-task and off-task screenshots:

| Source                                 | All   | On-Task | Off-Task |
|----------------------------------------|-------|---------|----------|
| Students in lab                        | 11,191| 9,178   | 2,013    |
| Authors, off-task in lab               | 3,000 | 0       | 3,000    |
| Authors, on-task videos, in lab        | 342   | 342     | 0        |
| Students in wild (real-world)          | 462   | 312     | 150      |
| **Grand Total**                        | 14,995| 9,820   | 5,175    |

_Fig. 3. Summary of the dataset distribution across different sources._



