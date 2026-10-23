# 🏏 Cricbuzz LiveStats: Real-Time Cricket Insights & SQL Analytics

[**Live Demo App**](https://cricbuzz-livestats.streamlit.app/)

An interactive, multi-page cricket analytics dashboard built using **Python, SQLite, Pandas, and Streamlit**. The application allows users to explore cricket match information, player records, scorecards, SQL queries, database operations, and visualizations.

## Features

- 🏏 Cricket match information and available score data
- 🗄️ SQLite database integration
- 📊 Multi-page Streamlit dashboard
- 👥 Player and match information
- 🔍 SQL query interface with beginner, intermediate, and advanced questions
- ✍️ CRUD operations: Create, Read, Update, and Delete records
- 📈 Data visualizations and analytics overview
- 📝 Custom SQL query execution
- 📤 Data exploration and analysis

## Tech Stack

- **Python** — application logic
- **Streamlit** — interactive web dashboard
- **SQLite** — database management
- **SQL** — querying and analyzing cricket data
- **Pandas** — data manipulation and tabular results
- **Requests** — API requests, where configured

## Project Structure

```text
Cricket_Insights/
├── Streamlit_app.py
├── requirements.txt
├── README.md
├── cricket.db
├── query_db.py
├── utils/
│   ├── path_setup.py
│   └── db_connection.py
└── pages/
    ├── 1_Home.py
    ├── 2_Matches.py
    ├── 3_Players.py
    ├── 4_Scores.py
    ├── 5_CRUD.py
    ├── 6_Matches_CRUD.py
    ├── 7_Scores_CRUD.py
    ├── 8_SQL_Queries.py
    ├── 9_Visualizations.py
    └── 10_Analytics_Overview.py
```

## Getting Started

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Cricket_Insights
```

### 2. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 3. Run the application

```bash
python -m streamlit run Streamlit_app.py
```

Open the local URL displayed in the terminal, usually `http://localhost:8501`.

## Application Modules

- **Home:** Project introduction and navigation.
- **Matches:** Explore available cricket match records.
- **Players:** View player information.
- **Scores:** Explore available score records.
- **SQL Queries:** Execute predefined and custom SQL queries.
- **CRUD Operations:** Manage player records.
- **Matches CRUD:** Manage match records.
- **Scores CRUD:** Manage score records.
- **Visualizations:** Explore cricket data through charts.
- **Analytics Overview:** Review available analytics and summaries.

## SQL Analytics

The SQL interface organizes 25 practice questions into three levels:

- **Beginner:** Basic filtering, grouping, sorting, and aggregate functions.
- **Intermediate:** Multi-table analysis and more advanced query patterns.
- **Advanced:** Cricket performance analysis and analytical query examples.

The implemented queries operate on the available database schema and sample data. The completeness of each advanced analytical calculation depends on its implementation and available data.

## Future Enhancements

- Integrate and validate a live cricket data API.
- Expand player and match statistics.
- Improve advanced SQL analytics.
- Add more interactive visualizations.
- Enhance deployment and database management.

## Use Cases

- Sports data exploration
- Cricket performance analysis
- SQL learning and practice
- Database management demonstrations
- Data analytics portfolio projects

## Author

**Bhagyashri Patil**

Computer Engineering | Python • SQL • Streamlit • Data Analytics

---

*This project demonstrates cricket data exploration, SQL querying, database operations, and interactive visualization using Python and Streamlit.*