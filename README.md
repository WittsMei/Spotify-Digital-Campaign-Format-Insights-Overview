# Spotify-Digital-Campaign-Insights


## The goal of this project is to investigate the performance of Spotify's digital marketing campaigns across all categories to surface recommendations for optimizing marketing budget allocation in future campaigns.

**Spotify, a leading music streaming service, has a vast user base across the globe.** To expand its user base further, Spotify has been running various digital marketing campaigns outside of its app since 2019. These campaigns span multiple platforms, including Email, SEO & SEM, and Social Media, and utilize various categories such as Welcome Series, Display Ads, Sponsored Posts, and more. Each category is designed to target potential users and encourage them to sign up for Spotify's services.

To stay competitive amidst evolving technology and shifting user preferences, Spotify aims to refine its marketing strategy by analyzing how different platforms and types impact user sign-ups and brand awareness. This project will offer insights into campaign effectiveness, aiding in more strategic budget allocation.

As Spotify strategizes its marketing budget for the upcoming year, a newly formed data team has been tasked with evaluating the success of past campaigns. The company’s primary objectives are twofold: 1) to significantly increase the number of new sign-ups, and 2) to enhance Spotify’s brand awareness globally.


## Data Structure

The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as engagement filed by customers and related engagement information.


<img width="600" alt="Screenshot 2024-09-03 at 18 15 56" src="https://github.com/user-attachments/assets/28ceb456-ef88-41c2-a8e0-48ebae539b2e">


## North Star Metrics & Dimensions
- **Click-Through Rate (CTR)**: The percentage of impressions that resulted in clicks.
- **Sign-Up Rate**: The percentage of impressions that lead to sign-ups across different formats and platforms.
- **Cost per Sign-Up**: The total cost divided by the number of sign-ups for each campaign, format, and platform.
- **Category**: Specific campaign formats like Welcome Series, Search Ads, Sponsored Posts, etc.
- **Campaign Type**: Acquisition, Retention, Re-engagement.
- **Time Period**: Year, Month.


## Summary of Insights


### Click-Through Rate (CTR)
- Across campaign categories, Carousel Ads achieved the highest CTR at 5.36%, despite having the lowest impressions. This exceptional performance was primarily driven by the Retention campaign type, which recorded an impressive CTR of 36.02%, significantly surpassing the overall average of 0.88%.
- Although Video Ads generated the highest impressions and sign-ups, they experienced a relatively low CTR of 0.71%. This was largely due to the Upsell, Educational, Retention, and Seasonal campaign types, which posted CTRs ranging from just 0.01% to 0.05%.
- Both Drip Campaigns and Sponsored Posts not only recorded the lowest CTRs but also had the lowest sign-up rates.

### Sign-Up Rate
- Across campaign categories, Carousel Ads and Influencer Partnership campaigns performed 5x and 2x better than the average sign-up rate, with rates of 0.048% and 0.016%, respectively.
- This high sign-up rate for Carousel Ads was attributed to the Retention campaign type, which by far had the highest sign-up rate across all campaign types (0.217%).
- Interestingly, despite having the highest sign-up rate and a relatively low cost per sign-up, Carousel Ads generated the fewest total sign-ups, with only 7,475.

### Cost per Sign-Up
- Across campaign categories, Welcome Series had the highest cost per sign-up at $5.14, coupled with a mediocre sign-up rate of 0.008% and highest sign-ups, compared to an average of $2.07.
- The elevated cost per sign-up for Welcome Series was driven by the Brand Awareness, Re-engagement, and Seasonal campaign types, with costs ranging from $7 to $10.
- Search Ads (Acquisition campaign type) and Display Ads (Content Promotion campaign type) also encountered notably high CACs, at $12.54 and $7.94, respectively. Search Ads in particular had the lowest sign-up rate at 0.005%.
 


## Recommendations & Next Step

- **Carousel Ads**: Given their exceptional performance, especially in the Retention campaign type, where they achieved the highest CTR and Sign-Up Rate, it is recommended to reallocate a portion of the budget from less effective categories—such as Drip Campaigns, Sponsored Posts, Search Ads, and Display Ads (Content Promotion campaign type)—to Carousel Ads. Additionally, consider expanding the use of Carousel Ads to other relevant campaign types, especially those targeting customer retention, to maximize ROI.
  
- **Influencer Partnerships**: With a sign-up rate twice the average, these campaigns should see increased investment, particularly in the Brand Awareness campaign type. Leveraging influencers to amplify Spotify’s reach can further enhance brand perception and drive sign-ups.
  
- **Video Ads**: While Video Ads generate the highest impressions and sign-ups, their low CTR (0.71%) indicates weak engagement. This indicates that although they reach a wide audience, their ability to convert clicks into sign-ups is limited. To address this, focus on Brand Awareness-type and Cross Cell-type (low cost) marketing, and less on Upsell, Educational, and Seasonal campaign typess, which had low signup rate and CTR.
  
- **Welcome Series**: Investigate the cause of high cost per signup ($5.14), particularly within Brand Awareness, Re-engagement, and Seasonal types. Also, consider reallocating part of the budget to more cost-effective campaigns, such as Carousel Ads and Influencer Partnerships.








## Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/witts.jianming.mei/viz/SpofityCampaignFormatDashboard/SpotifyCampaignFormatDashboard). This dashboard enables users to filter by plan, campaign type, and platform, and focuses on trends and values in marketing metrics, signup metrics, and duration metrics.

![Spotify Campaign Format Dashboard](https://github.com/user-attachments/assets/7ef91563-6051-49f8-909c-46f0ce3ecab3)


