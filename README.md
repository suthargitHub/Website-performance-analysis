# 🌐 Website Performance Analysis

This project analyzes user engagement data on a website to identify patterns in user behavior, session performance, and channel effectiveness. Using Python, we process a structured dataset exported from analytics tools, clean and transform the data, and visualize key metrics that impact site performance.

---

## 📁 Dataset Overview

The dataset consists of **3,183 records** with the following performance metrics:

| Column Name                             | Description |
|-----------------------------------------|-------------|
| `Session primary channel group`         | Source/channel of the session (e.g., Direct, Organic Social) |
| `Date + hour (YYYYMMDDHH)`              | Timestamp of the session (date and hour) |
| `Users`                                 | Number of users for the session group |
| `Sessions`                              | Total sessions recorded |
| `Engaged sessions`                      | Sessions with user interaction |
| `Average engagement time per session`   | Time spent per session (in seconds) |
| `Engaged sessions per user`             | Ratio of engaged sessions to users |
| `Events per session`                    | Number of events triggered per session |
| `Engagement rate`                       | Percentage of engaged sessions |
| `Event count`                           | Total number of events triggered |

---

## 🔧 Project Workflow

### 1. Data Cleaning
- Rename columns
- Convert date strings to datetime format
- Handle missing values and type conversions
- Normalize numeric formats

### 2. Exploratory Data Analysis (EDA)
- Analyze trends in user activity over time
- Compare engagement metrics across traffic sources
- Visualize session behavior patterns
- Identify peak engagement hours

### 3. Visualization
- Correlation heatmaps
- Time-series plots of session metrics
- Bar plots comparing engagement rates per channel
- Boxplots for distribution analysis

---

## 📊 Tools & Technologies

- **Python**
- `Pandas` - for data manipulation
- `NumPy` - for numerical computation
- `Matplotlib` & `Seaborn` - for data visualization

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn
