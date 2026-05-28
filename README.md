# cs50-music-database
A SQL-powered music database querying tool that analyzes songs, artists, and their characteristics.

🎵 The Database
A SQLite database (songs.db) containing data about popular songs including:

Songs - Title, tempo, danceability, energy, key, loudness, and more

Artists - Names and artist IDs

🔍 Queries Implemented
8 SQL queries answering questions like:

Songs with specific danceability - Basic filtering

Songs by specific artists - JOIN operations

Top tempo songs - ORDER BY with LIMIT

Songs with high energy and danceability - Multiple conditions

Songs by year - Date filtering

Songs with low loudness - Numeric comparisons

Songs by multiple artists - IN operator with subqueries

Songs with specific energy range - BETWEEN clause

🛠️ SQL Techniques Used
SELECT with WHERE - Conditional filtering

JOIN (INNER) - Connecting songs to artists

ORDER BY & LIMIT - Sorting and top results

IN & NOT IN - Set membership

BETWEEN - Range filtering

LIKE - Pattern matching for text

📁 Files
1.sql through 8.sql - One query per file

songs.db - SQLite database (provided)
