# Netflix Analysis with Amazon QuickSight

This project demonstrates how to use **Amazon QuickSight**, a cloud-based business intelligence tool, to perform interactive data visualization and analysis on the Netflix Titles dataset from Kaggle.

## 🔍 Overview

In this project, I analyzed Netflix's content library by visualizing key attributes such as:

- Release Year
- Content Type (Movies vs. TV Shows)
- Genre Categories
- Date Added to Netflix

The final product is an interactive **Amazon QuickSight Dashboard** that helps identify content trends and distribution patterns.

## 🧠 Key Insights

- A large spike in content was noticed in certain years, revealing uneven distribution across release years.
- Most content was added to Netflix between 2017 and 2020.
- Visualizations highlight genre popularity and release patterns over time.

## ⏱️ Project Duration

- Approximately **2.5 hours** from setup to visualization and dashboard publishing.

## 🧰 Tools & Services Used

- **Amazon S3** – For storing the dataset and `manifest.json` file.
- **Amazon QuickSight** – For creating visual dashboards.
- **Dataset** – [Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## 📁 Steps to Reproduce

### 1. Upload Files to S3
- Files uploaded:
  - `netflix_titles.csv`
  - `manifest.json`
- `manifest.json` was modified to include the correct S3 path:  
  `s3://nextwork-quicksight-project-sidh/netflix_titles.csv`

### 2. Create QuickSight Account
- Signed up with AWS details and selected **Standard Edition**.
- Quick setup with free tier.

### 3. Connect Dataset to QuickSight
- Go to **Datasets** → **New Dataset** → **S3**.
- Use `manifest.json` to define dataset path, format, and permissions.

### 4. Create Visualizations
- Logged into QuickSight → **New Analysis**.
- Selected dataset → Dragged `release_year` for donut chart.
- Used **bar charts**, **tables**, and **filters** for enhanced clarity.

### 5. Dashboard Setup
- Combined visuals into a dashboard.
- Added descriptive titles.
- Exported dashboard as PDF for sharing.

## 📷 Sample Visualizations

- **Donut Chart** – Titles by Release Year
- **Bar Graph** – Titles by Genre
- **Table View** – Recently Added Titles
- **Filter** – Focus on top 20 release years

## 📌 Author

**Siddhesh Pallor**  
*NextWork Student*  
Email: sidhesh2508@gmail.com

## 🌐 Useful Links

- [Amazon QuickSight](https://aws.amazon.com/quicksight/)
- [Kaggle Dataset - Netflix](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- [NextWork Community](https://community.nextwork.org)

