wwe# **Building a Power BI Report for Waggle**

Project 2 of Udacity's [Data Analysis and Visualization with Microsoft Power BI Nanodegree Program](https://www.udacity.com/course/data-analysis-and-visualization-with-power-BI-nanodegree)
in **Creating Visualizations with Power BI** course.

## Project Description:
Waggle is a startup that makes smart devices for pets. Recently, they has been thrilled by the success of their new Lapdog device, a fitness collar that lets owners track their dog’s steps, alerts them when it’s time for a walk, and even repels fleas! Reviews have been fantastic, sales are growing, and—best of all—the product really works! 

The product team distributed 1,000 Lapcat prototypes for field testing. Now, after months of data collection, we have been tasked with delivering a boardroom-ready Power BI report that tells the story of how the Lapcat data compares to findings from the dog collar Lapdog devices to either help convince the CEO that Lapcat is the next big thing or a costly mistake to be avoided.

Below is a quick demonestration about the project components.

### Data Model:
A snapshot of the data model is provided below and can be found on `Waggle-Data-Model.png.jpg
` on this repo.

![Waggle Data Model](https://github.com/Abdelazizmakkawi1/SEVEN-SAGES-TEA-COMPANY-SSTC-DATA-MODELING-PROJECT/blob/master/02-Building-Power-BI-Report-for-Waggle/Theme%20and%20sources/Waggle-Data-Model.png.jpg)


### Report Requirements:
- The CEO is curious about the following questions:
  - Did the average daily steps increase for cats wearing the device as they did for dogs?
  - Were owners of Lapcat devices as satisfied with the product as Lapdog owners?
- The Chief Marketing Officer would like the report to be “on-brand” by including only colors from the Waggle color palette, the Waggle logo, and other approved company logos and icons.

![Waggle color palette](https://github.com/Abdelazizmakkawi1/SEVEN-SAGES-TEA-COMPANY-SSTC-DATA-MODELING-PROJECT/blob/master/02-Building-Power-BI-Report-for-Waggle/Theme%20and%20sources/Waggle-color-palette.png)


- The product team trusts us to incorporate other visuals and insights as we see fit but is most interested in comparisons between the dogs and cats using Waggle devices as well as any information about the families who own the pets. They would also like slicers to help them filter and explore on their own.
- The report should include: 
  - at least five slicers on each page with at least one example of a drop-down slicer, at least one example of a slider slicer, at least one example of a hierarchy slicer, at least one example of a slicer with “Select All” enabled, and one example of a slicer with the search box enabled.
  - at least two bookmark features. One must allow users to dynamically swap one visual out with a different one and another must reset all applied filters on the page.
  - buttons that help users navigate the report tabs. they must respond when users hover over them by changing color or size

The report is to include 3 tabs
- The first page should highlight the CEO’s business questions, specifically calling out the differences in average step count and average user rating between Lapdog and Lapcat devices.
- The second page should focus on insights related to pets using the device.
- The third page should focus on insights related to the families that own the pets.


### Report Tab 1:
To address the CEO’s questions 
- 1 visualization was ploted to highlight the difference between average daily steps over time recorded on Lapdog devices vs. Lapcat devices displaying the trend over time by year and month and with the using of button 2020 you can have a detailed look at its trend.
- 1 visualization highlighted the difference between the customer ratings for Lapdog devices vs. Lapcat devices.
- 2 visualization highlighted the difference between the customer recommendations for Lapdog devices vs. Lapcat devices.


![Waggle Report Tab 1](https://github.com/Abdelazizmakkawi1/SEVEN-SAGES-TEA-COMPANY-SSTC-DATA-MODELING-PROJECT/blob/master/02-Building-Power-BI-Report-for-Waggle/Theme%20and%20sources/Waggle-Tab1.jpg)

___

### Report Tab 2:
To drive insights from the `pets` dataset, the second tab included:
- A visualization that shows the `breed` distribution of cats and dogs.
- 2 visualiza`tion that highlighted both `gender` and `age` distributions along the dataset with `pet type` as hue. 


![Waggle Report Tab 2](https://github.com/xShaimaa/Udacity-Data-Analysis-and-Viz-with-Microsoft-Power-BI/blob/master/02-Building-Power-BI-Report-for-Waggle/Waggle-dashboard/Waggle-tab2.jfif)

___

### Report Tab 3:
To drive insights from the `family` dataset, the third tab included:
- A table that shows important family data.
- A card that shows the count of total pets on the dataset, and has 2 bookmark buttons to show only cat or dog counts.
- A visualization that shows the relation between `house hold income` and `number of owned pets` along the dataset with `pet type` as hue. 


![Waggle Report Tab 3](https://github.com/xShaimaa/Udacity-Data-Analysis-and-Viz-with-Microsoft-Power-BI/blob/master/02-Building-Power-BI-Report-for-Waggle/Waggle-dashboard/Waggle-tab3.jfif)

___
