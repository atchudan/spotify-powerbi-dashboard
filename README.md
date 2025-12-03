# 🎧 Spotify Global Music Analysis (2009–2025) — Power BI Dashboard
This project analyzes the Spotify Global Music Dataset (2009–2025) using Power BI, uncovering insights on track trends, artist performance, genre popularity, and music evolution over the years.
The dashboard includes data cleaning, transformation, modeling, and multi-page storytelling.

# 📌 Project Overview
This Power BI dashboard provides a complete analysis of Spotify music data across 8,582 tracks and 2,548 artists.

- It answers questions like:
- How has music production changed over time?
- Which artists and genres are the most influential?
- What drives track popularity?
- How do followers, popularity, and genres connect?
- Which trends have shaped the music industry in the last 15+ years?

# 🛠️ Tech Stack

| Tool            | Purpose                                  |
| --------------- | ---------------------------------------- |
| **Power BI**    | Dashboard visuals, DAX, storytelling     |
| **Power Query** | Data cleaning & transformation           |
| **DAX**         | KPIs, custom measures, analytical logic  |
| **GitHub**      | Documentation & project hosting          |
| **Dataset**     | Spotify Global Music Dataset (2009–2025) |

# 🧹 Data Preparation (Power Query)
**Key transformations:**

- Trimmed & cleaned text fields
- Corrected data types
- Parsed album release dates
- Extracted Year, Month, and Month Name
- Converted track duration to minutes/seconds
- Split multi-genre strings into rows
- Removed null/blank genres (visual-level only)
- Ensured unique track counts using DISTINCTCOUNT

# 📈 Key Insights
- Music production has exploded after 2010
- Pop remains the most produced genre
- Explicit tracks make up ~25% of all releases
- Popularity peaks appear in the late 70s, 80s, and 2010s
- High followers ≠ high popularity
- Genre and artist behavior varies significantly

# 📊 Dashboard Pages
### 1️⃣ Executive Summary
Provides a high-level view of the dataset with KPIs:

- Total Tracks
- Total Artists
- Average Track Popularity
- Average Artist Followers
- % Explicit Tracks
- Visuals include:
- Track Popularity Trend (by year)
- Tracks Released Over Time
- Genre Distribution
- Explicit vs Non-Explicit Split

### 2️⃣ Artist Insights
Focuses on artist-level analytics:

- Top Artists by Average Popularity
- Followers vs Popularity (scatter analysis)
- Artist Performance Table
- Genre distribution per artist
- Key insights:
- Artist popularity does not always match follower count
- Some emerging artists outperform major names
- Genre-specialist artists stand out clearly

### 3️⃣ Track Analysis
Dive into track-level patterns:

- Cumulative Unique Tracks Over Time
- Top Track Durations by Genre
- Searchable Track Table (popularity, genre, year)
- Key observations:
- Track releases rise sharply after 2010
- Certain genres consistently produce longer tracks
- Popularity varies widely across decades

### 4️⃣ Artist–Genre Analysis
Shows the relationship between artists and genres:

- Tracks per Artist (genre-based)
- Avg Track Popularity by Genre
- Artist Slicer with integrated search

Insights:

- Many artists work across multiple genres
- Some niche genres show very high popularity scores

# 📂 Repository Structure
spotify-powerbi-dashboard/
│
├── Spotify_Dashboard.pbix
├── README.md
│
└── screenshots/
     ├── executive_summary.png
     ├── artist_insights.png
     ├── track_analysis.png
     └── artist_genres.png


# 🚀 How to Use the Dashboard
1. Download the .pbix file
2. Open it in Power BI Desktop
3. Explore the visuals using slicers:
   -Artist
   -Genre
   -Year
   -Explicit
4. Switch pages using the bottom tabs

# 🤝 Feedback & Contributions
Feel free to open issues, suggest improvements, or fork the repository.
Feedback is always welcome!

# 📬 Connect With Me
LinkedIn: (https://www.linkedin.com/in/atchudan-sreeram-609b46169/)
Email: atchudan1998@gmail.com
