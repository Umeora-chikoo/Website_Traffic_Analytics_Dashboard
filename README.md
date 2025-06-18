# Website-Traffic-Analytics-Dashboard

## Project-Overview:

This repository features a Power BI Dashboard for an E-commerce platform, showing how sessions, bounce rate, and page views vary across different dimensions such as devices, sources, campaigns, and regions. These insights help plan digital marketing strategies to boost revenue.

## Goal:

The lack of insights regarding customer engagement on this e-commerce platform across various devices, sources, campaigns, and regions has led to inefficient advertisement expenditures by the owner without achieving the desired outcomes. This analytical dashboard offers detailed insights into website traffic, enabling the owner to refine their advertising strategy with data driven decisions for enhanced visibility and increased revenue.

## Key Metrics:

1.	**Session**: Time spent on website, from initial click till final interaction.	
3.	**Bounce Sessions**: Single page sessions having session duration of 0 seconds.
5.	**Page views per session**: Count of website pages viewed during a single session
6.	**Source types**: From Where Website Traffic Comes from (Social,Email,Referral,Organic)
7.	**Campaign**: Efforts to promote the content products
8.	**Bounce Rate**: Bounced Sessions / Total Session

## Tech Stack:

The dashboard was built using the following tools and technologies:

•	**Power BI Desktop** – Main data visualization platform used for report creation.

•	**MySQL** – For Data Capture

•	**Power Query** – Data shaping, data modelling and preparing the data

•	**DAX(Data Analysis Expression)** – Custom DAX measures for  Total_number_of_sessions, Average_session, Bounce_Rate, Total_Page_Views, Total_Session_Duration.

•	**File format** - .pbix for development and .png for dashboard previews.

## Visualization

![](https://github.com/Umeora-chikoo/Website_Traffic_Analytics_Dashboard/commit/f00983db66ea8c23e43985c9c87c09e874cbf5b9#diff-b9e0680d230b38a3c84cc37f9cd5e98e4035ae3f9b4389a7ef53a3769195fb63)
## Business Requirements & Analysis:

### WEBSITE TRAFFIC BY SOURCES AND DEVICES
 * **Bounce Rate by Device Type**:  
Bounce Rate is highest for Desktop around 11.54 % where as it is lowest for Other at around 8.51 %

* **Bounce Rate by Content Segment**:  
Bounce Rate is highest when user is searching Personal Content and lowest when user is searching Gaming Content

* **Bounce Rate by Website Traffic Source**:  
Bounce Rate is highest when traffic is coming after a specific Referral Program whereas it is lowest for Organic Website Traffic

* **Session Duration and Page Views –( Device Type)**:  
For Tablet , total and average session duration along with that Page views are good whereas for Mobile these parameters are not good

* **Total Session Duration and Page Views – (Traffic Source)**:  
Total and Average Session duration are good when website traffic is coming organically whereas it is worst when traffic is coming from referral.

### WEBSITE TRAFFIC TREND OVER TIME
* **Total Session Duration-Trend for Device types**:  
For tablet overall trend for session duration is improving while it is stable for Desktop , Mobile and Other devices . Trend is somewhat deteriorating for Laptop device

* **Total Session Duration – Trend for website traffic sources**:  
Session duration for organic traffic and traffic originating from social media is good whereas it is bad for Referral and Paid traffic. For Email and Other traffic sources there is no trend as such

* **Bounce Rate - Monthly Trend**:  
Bounce Rate is highest for April Month which needs to be explored wheres it is lowest for July Month. 

* **Bounce Rate - Daily Trend**:  
Bounce Rate is highest on Sunday which is worrisome sign also there is specific trend in which bounce rate keep on increasing from Monday till Thursday .

### WEBSITE TRAFFIC GEOGRAPHICAL ANALYSIS
* **Total Page Views – (Region)**:  
Maximum Pages were viewed in Southern Region whereas minimum number of pages were viewed in Eastern Region 

* **Total Session Duration –(Region)**:   
Session Duration was highest for Southern Region and minimum for Easteren Region

* **Bounce Rate - (Region)**:   
Bounce Rate is also highest for Southern Region whereas it is lowest for Eastern Region

* **Total Session Duration (Top 5 cities)**:  
 Total Session Duration is highest for Chennai City whereas it is lowest for Lucknow city

* **Bounce Rate (Top 5 cities)**:  
 Bounce Rate is lowest for Delhi city whereas highest for Chennai city

* **Total Page Views (Top 5 cities)**:  
 Total Pageviews were highest in Chennai city and lowest for Delhi city 

* Total Number of Sessions(Top 5 cities):  
 Total Sessions count is highest for Chennai City whereas it is lowest for Lucknow city

## Conclusion:
•	**Bounce Rate**: The bounce rate is highest for desktop users (11.54%) and lowest for "Other" devices (8.51%). Personal content has the most bounce rate while gaming content sees the least. Organic traffic results in the lowest bounce rate compared to referral traffic, which is highest.

•	**Session Duration and Page Views**: Tablets show strong session duration and page views, whereas mobile devices perform poorly. Organic traffic outperforms referral traffic in terms of session duration and page views.

•	**Trends Over Time**: Session duration for tablets is improving. Bounce rates peak in April and Sundays, and there’s a pattern of bounce rates increasing from Monday to Thursday. Analyse parameters reducing July's bounce rate.

•	**Geographical Insights**: Southern regions excel in page views and session duration but also have the highest bounce rate. Chennai leads among cities in session duration, page views, and total sessions, while Delhi has the lowest bounce rate.

## Recommendations✨✨:
Based on the analysis, here are the recommendations:
1. **Optimize Traffic Sources:** Focus on enhancing organic traffic, as it consistently shows better performance in terms of session duration and bounce rate compared to referral traffic. Strategies could include improving SEO efforts and creating engaging, keyword-rich content.
2. **Improve Mobile Engagement:** Since mobile devices show weaker performance in session duration and page views, explore ways to enhance the mobile user experience. This can include faster load times, responsive design, and mobile-friendly navigation.
3. **Address High Bounce Rates:** Investigate the factors contributing to higher bounce rates in specific regions, such as the Southern region and referral traffic sources. Consider revising content to align better with audience expectations in these areas.
4. **Target Successful Trends:** Build upon the positive trends observed in tablet usage and the geographic success of the Southern regions. For instance, allocate more resources toward optimizing content for tablets and tailoring campaigns to Southern audiences.
5. **Leverage Regional Strengths:** Strengthen engagement strategies for high-performing cities like Chennai, which leads in total sessions, page views, and session duration, and use insights from its success to improve performance in cities like Lucknow.
These targeted actions will help enhance overall website performance and user engagement across devices, regions, and traffic sources.

Connect with me on socials📱💻➡️;  
LinkedIn-www.linkedin.com/in/chikodili-anagu-  
Github- https://github.com/Umeora-chikoo







