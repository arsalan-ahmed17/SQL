# CS50 2024 - SQL Problem Sets

[![CS50](https://img.shields.io/badge/CS50-Harvard_University-02569B?style=flat&logo=edx&logoColor=white)](https://cs50.harvard.edu/x/2024/)

Repository containing my solutions for **CS50's Introduction to Computer Science 2024** SQL problem sets. These exercises helped me master fundamental SQL concepts while solving real-world style data challenges.

## 🧩 Problem Sets Included

### 1. Songs
**Task:** Analyze a music database containing songs from 2018\
**Skills demonstrated:**
- Basic `SELECT` queries
- Filtering with `WHERE`
- Sorting with `ORDER BY`
- Using `LIKE` for pattern matching

```sql
SELECT name FROM songs WHERE duration_ms > 240000 AND energy > 0.8;
```

### 2. Movies
**Task:** Explore a movie database with Oscar-winning films\
**Skills demonstrated:**
- Table joins (`INNER JOIN`)
- Aggregation with `COUNT()` and `GROUP BY`
- Subqueries
- Handling NULL values

```sql
SELECT title, rating FROM movies WHERE year = 2012 
ORDER BY rating DESC LIMIT 5;
```

### 3. Fiftyville Mystery (Forensic SQL)
**Task:** Solve a fictional theft mystery using SQL queries\
**Skills demonstrated:**
- Complex multi-table joins
- Timestamp analysis
- Transactional queries
- Advanced filtering

## 🛠️ Technologies Used
- **SQL** (SQLite flavor)
- CS50 IDE
- VS Code + SQLite Extension

## 📂 How to Use
1. Clone repo:
   ```bash
   git clone https://github.com/yourusername/cs50-sql-solutions.git
   ```
2. Use with CS50's databases:
   - Download problem set databases from [CS50 2024 Materials](https://cs50.harvard.edu/x/2024/)
3. Run queries in:
   - CS50 IDE
   - DB Browser for SQLite
   - VS Code with SQLite extension

## ⚠️ Academic Note
These solutions are provided for **educational reference only**. CS50 students should attempt problems independently before reviewing solutions to maximize learning
