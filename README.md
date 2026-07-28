AI Systems Analysis with SQL

SQL analysis of the AI industry using the EpochAI dataset. Investigates influential organizations, AI system development trends, and key problem areas.

Completed as part of the Codecademy SQL learning path.

Dataset

**Tables:**
- `systems`: AI systems with publication dates, parameters, organization ID, problem ID
- `orgs`: Organizations with names and types
- `problems`: AI problem categories/tasks

Tasks Performed

1. Explored database tables structure
2. Defined project goals
3. Documented database structure
4. Brainstormed analytical ideas
5. Identified most influential organizations (by system count)
6. Filtered by AI system type and organization type
7. Analyzed AI development growth over time
8. Debugged YEAR function for SQLite (used STRFTIME instead)
9. Found top 5 AI problems by organization focus

SQL Concepts Used

* SELECT
* JOIN
* GROUP BY
* COUNT()
* MAX()
* STRFTIME()
* WHERE
* ORDER BY
* LIMIT
* DISTINCT

Files

* ai_systems_queries.sql
* findings.md


```bash
sqlite3 epochdb.db < ai_systems_queries.sql
```
