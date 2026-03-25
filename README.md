# 🎵 Spotify Power BI Dashboard  
**Interactive Music Analytics | Artist Insights | Track Trends**

<img width="1536" height="1024" alt="Spotify music analytics dashboard__endoftext__" src="https://github.com/user-attachments/assets/af20c9ba-6bcd-4b06-91bd-e2b284f4d87e" />


<p align="center">
  <img src="https://img.shields.io/badge/PowerBI-Data%20Analytics-F2C811?logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen" />
  <img src="https://img.shields.io/badge/Visualization-Interactive-blue" />
  <img src="https://img.shields.io/badge/Dataset-Spotify-orange?logo=spotify" />
</p>

---

## 📌 Project Overview  
This project presents an **interactive Spotify Analytics Dashboard** built using **Power BI**, providing insights into song popularity, artist performance, audio features, and listening trends.  

The dashboard allows users to:  
- 🎧 Explore top songs & artists  
- 🔍 Analyze track features (energy, tempo, danceability, etc.)  
- 📈 Compare popularity vs. audio attributes  
- 📊 View trends using intuitive charts  

---

## 📁 Repository Structure

```
📂 Spotify-PowerBI-Dashboard
│── README.md
│── Spotify_Dashboard.pbix
│── 📂 assets
│     ├── dashboard_cover.png
│     ├── dashboard_overview.png
│     ├── top_artists.png
│     ├── audio_features.png
│     ├── popularity_trends.png
│── 📂 data
│     ├── spotify_raw_data.csv
│     ├── spotify_cleaned_data.csv
│── 📂 imagges
      ├── background image
      ├── spotify logo
```

---

## 🚀 Features

### **🎵 1. Overview Dashboard**
- Total tracks analyzed  
- Total artists  
- Popularity distribution  
- Top genres  


### **🌟 2. Top Artists & Tracks**
- Most streamed artists  
- Highest popularity tracks  
- Heatmap of artist contribution  

### **🎚️ 3. Audio Feature Analysis**
- Tempo  
- Danceability  
- Energy  
- Loudness  
- Valence  

### **📊 4. Popularity vs Audio Attributes**
- Scatterplots  
- Trend lines  
- Correlation insights  

---

## 🗂️ Dataset Information
- Source: Spotify track dataset  
- Includes:  
  - `track_name`, `artist_name`, `popularity`  
  - Audio metrics (energy, acoustics, danceability, speechiness)  
  - Duration, release year, etc.

For more details → Check `docs/data_dictionary.md`

---

## 🛠️ Tools Used
- **Power BI Desktop**  
- **Power Query** (Data Cleaning)  
- **DAX** (Measures & Calculations)  
- **Spotify Dataset (CSV)**  

---

## 📸 Screenshots  
(Add your exported dashboard images in /assets folder)

### 🔹 **Dashboard Overview**
<img width="1146" height="644" alt="Dashboard overview" src="https://github.com/user-attachments/assets/bbf7d820-0c53-40bf-aea4-ec2aca228095" />

### 🔹 **Top Artists & Songs**
<img width="359" height="211" alt="Artist analysis" src="https://github.com/user-attachments/assets/df4cc322-ba53-46aa-998c-9c58555b41fa" />

<img width="349" height="188" alt="Track Insight" src="https://github.com/user-attachments/assets/d01ce26a-6772-4c17-925c-d433d72f65fa" />

### 🔹 **Audio Features Breakdown**

<img width="380" height="240" alt="Track by key" src="https://github.com/user-attachments/assets/2e481b95-b3eb-406f-9723-2660d8ec3bb9" />

### 🔹 **Popularity Trends**
<img width="1134" height="286" alt="Streams by release Year" src="https://github.com/user-attachments/assets/1b619ca9-b8cf-4d22-86c2-bbe9b7ef244a" />


---

## ▶️ Getting Started

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/Spotify-PowerBI-Dashboard.git
```

### **2. Open the Project**
- Open **Spotify_Dashboard.pbix** in Power BI Desktop.

### **3. Load Data**
- Ensure all CSV files inside `/data` folder are correctly mapped.

---

## 🧮 Measures Used (DAX Samples)

```DAX
Total Tracks = COUNTROWS(spotify_data)

Average Popularity = AVERAGE(spotify_data[popularity])

Energy vs Popularity = CORREL(spotify_data[energy], spotify_data[popularity])
```

---

## 📑 Documentation  
| Document | Description |
|---------|-------------|
| `data_dictionary.md` | Field-level dataset description |
| `transformations.md` | All cleaning + Power Query steps |

---

## 🤝 Contributing
Contributions are welcome!  
Feel free to submit issues or pull requests.

---

## ⭐ Show Support  
If you like this project, give it a **⭐ star** on GitHub!
