# IPL-2024
Power BI Project on IPL 2024

![Screenshot 2024-12-23 175950](https://github.com/user-attachments/assets/2bf1cae1-77b2-4ecb-b93b-cbe88f123067)
![Screenshot 2024-12-23 180009](https://github.com/user-attachments/assets/aeff449b-427e-462f-b48c-6967915e8ea9)
![Screenshot 2024-12-23 180032](https://github.com/user-attachments/assets/d2039504-1a2d-40db-ac57-b8f253820cc4)

# How to Create a Power BI IPL Dashboard with Cricbuzz API Integration:
Creating a Power BI dashboard that visualizes IPL data in real-time can be an exciting way to engage with cricket analytics. In this guide, we’ll walk through setting up Power Query to retrieve data from the Cricbuzz API via RapidAPI, and how to build a dynamic IPL dashboard.

## 1) Getting Started with RapidAPI and Cricbuzz
Before we dive into Power Query, you’ll need to sign up for RapidAPI and subscribe to the Cricbuzz API.
## Step-by-Step Guide to Obtain the API Key:
  
# 1. Sign Up on RapidAPI:
- Visit RapidAPI’s website and sign up for a free account.
- Once registered, log in to your RapidAPI dashboard.
# 2. Search for Cricbuzz API:
- In the RapidAPI dashboard, use the search bar to find the “Cricbuzz” API.
- Select the Cricbuzz API from the search results to access its details page.
# 3. Subscribe to the API:
- On the Cricbuzz API page, click on the “Pricing” tab to choose a subscription plan.
- Start with the free tier if you’re experimenting or have light usage. You can upgrade later if needed.
- Click “Subscribe” to activate the API for your account.
# 4. Access Your API Key:
- Once subscribed, go to the “Endpoints” tab of the Cricbuzz API.
- You’ll see your API key displayed at the top of the page under “X-RapidAPI-Key”.
- Copy this API key, as you’ll need it when setting up your Power Query connections in Power BI.

## 2) Setting Up the API Connection in Power Query
With your API key in hand, you can now set up Power Query in Power BI to retrieve IPL data.

## Series Information API Setup:
This API provides detailed information about the IPL series (Series ID = 7607).
## Live Match Data API Setup:
To visualize live match data, you can set up another API call to fetch real-time information like scorecards.
## Extracting Toss Results:
It pulls the toss result from the live score data, giving you valuable context for the match.

## 3) Building Your IPL Dashboard

Once you’ve set up the API connections, you can start building the dashboard:

- Series Overview: Display stats like the number of matches, teams, top scorers, etc.
- Live Match Updates: Use real-time data to show scores, player performance, and more.
- Toss Insights: Visualize how toss results have influenced the outcomes.

## 4) Data Refresh and Automation
You can schedule data refreshes in Power BI to keep your dashboard up-to-date with live IPL action. This is particularly useful for dashboards that track live match data.

## 5) Conclusion
Integrating Cricbuzz APIs with Power BI is a powerful way to create an interactive, real-time IPL dashboard. This setup allows you to bring cricket data to life, providing insights that are both engaging and informative. Just make sure to manage your API calls effectively and ensure your API key is secure.

Happy dashboarding, and enjoy the IPL season!
















