# -Follower-Growth-Visualization-Basic-App
_____________________________________________________________________________
https://github.com/user-attachments/assets/07528b2c-72f2-434e-907a-501db570c92d
_____________________________________________________________________________

Follower Growth Visualization App
This app visualizes social media follower data using PySide2 and QtCharts. It provides interactive charts to track follower trends, influencer performance, and engagement metrics.

Features:
Line Charts: Displays follower growth over time.
Bar Charts: Compares follower counts or engagement metrics.
Combined Charts: Shows category-based metrics with trend lines.
Technologies:
PySide2: For GUI components.
QtCharts: For rendering charts.

## Description of main.py
### create_line_chart():
 Generates a line chart to display follower growth over time with dates on the X-axis and follower counts on the Y-axis. Data points are connected by lines to show trends.
### create_bar_chart():
Creates a bar chart to compare data across different influencers or time periods.
### create_combined_chart():
Produces a combined bar and line chart for comparative and trend analysis.
## Usage:
### Install dependencies:
```
pip3.9 install PySide2
```
### Run the app:

```
python main.py
```
## Notice:
Currently, the values in this project are static. However, future updates will introduce features allowing dynamic data input directly from social media accounts. This will include automatic fetching and updating of follower metrics.

Upcoming Features:

Dynamic Data Fetching: Automatically retrieve and update follower data from linked accounts.
Automated Video Generation: Generate specific types of videos and publish them without human intervention.
Hands-Free Video Publishing: Schedule and post videos automatically to social media platforms.
Stay tuned for these enhancements!
