**Website User Behavior Analysis**
This mini project aims to analyze user interaction data collected from a website to uncover usage patterns, detect potential usability issues, and make data-driven suggestions.

**Objective**

Analyze logs of user actions on a website.

Identify potential usability or performance problems based on user interaction.

Provide initial findings and thoughts about the nature and structure of the dataset.

**Dataset Description**

Each record in the dataset represents a user event:

EventName: Name of the user event (e.g., page visit, click).

DeviceIDHash: Unique identifier for each user/device.

EventTimestamp: Timestamp of the event in Unix format.

ExpId: Experiment group identifier — 246 and 247 are control groups, while 248 is the experimental group.

**Project Tasks**

Step 1: Load and Explore the Data

Convert Unix timestamps to human-readable datetime format.

Review dataset structure and integrity.

Step 2: Describe the Data

Understand the structure and roles of each column.

Confirm that each row corresponds to a single user interaction.

Step 3: Analyze Unique Device Counts by Experiment Group

Count how many unique users (devices) are in each experiment group.

Note that Group 248 (experimental) has the highest user count.

Step 4: Analyze Visit Counts by Experiment Group

Total number of visits logged by users in each group.

Again, Group 248 shows the most activity.

Step 5: Analyze Visits by Page

Identify which pages receive the most traffic.

The home page is the most visited, which is typical behavior as users start their journey there.

**Preliminary Findings**

The dataset is clean with no missing values.

User distribution across experimental groups is relatively even.

The homepage is the most interacted-with element, suggesting it is either the entry point or where users spend the most time.

**Technologies Used**

Python

Pandas

Matplotlib / Seaborn (for visualization, if used in your code)

Jupyter Notebook
