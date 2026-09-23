# 📊 Meta Ad Performance Dashboard – Power BI

An interactive **Meta Ads Performance Dashboard** built using **Microsoft Power BI** to analyze advertising campaigns, user engagement, ad performance, audience demographics, and marketing KPIs.

The dashboard helps understand how different campaigns and advertisements perform across platforms such as **Facebook and Instagram**.

---

## 🚀 Project Overview

The main objective of this project is to transform raw Meta advertising data into meaningful business insights using **Power BI**.

The dashboard provides an interactive view of:

- 📈 Ad impressions
- 🖱️ Clicks
- ❤️ Likes
- 💬 Comments
- 🔄 Shares
- 🛒 Purchases / Conversions
- 👥 User demographics
- 🎯 Target audience
- 📢 Campaign performance
- 💰 Campaign budget
- 📊 Engagement and conversion metrics

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel / CSV**
- **Data Modeling**
- **Data Visualization**

---

## 📂 Dataset

The project uses four main datasets:

### 1. Users

Contains information about users and their demographics.

Important columns:

- `user_id`
- `user_gender`
- `user_age`
- `age_group`
- `country`
- `location`
- `interests`

### 2. Ads

Contains information about advertisements.

Important columns:

- `ad_id`
- `campaign_id`
- `ad_platform`
- `ad_type`
- `target_gender`
- `target_age_group`
- `target_interests`

### 3. Campaigns

Contains campaign-level information.

Important columns:

- `campaign_id`
- `name`
- `start_date`
- `end_date`
- `duration_days`
- `total_budget`

### 4. Ad Events

Contains user interactions with advertisements.

Events include activities such as:

- Impressions
- Clicks
- Likes
- Comments
- Shares
- Purchases / Conversions

---

## 🗂️ Data Model

The Power BI data model connects the datasets using their respective IDs.

```text
Users
  │
  │ user_id
  ▼
Ad Events
  │
  │ ad_id
  ▼
Ads
  │
  │ campaign_id
  ▼
Campaigns
