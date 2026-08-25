# Cybersecurity Learning Journal

## 2026-08-25 — SQLi-Labs Less-27

**Topic:** UNION-based SQL Injection / Blacklist Bypass

### Learned
- User input was directly inserted into an SQL query.
- The blacklist was case-sensitive.
- Mixed-case `UNION` / `SELECT` bypassed the blacklist.
- `%09` provided tab whitespace that wasn't filtered.
- The `users` table has 3 columns.
- UNION allowed controlled values to appear in the application's output.
- `database()` revealedthe `security` database.
- `information_schema` provides database metadata such as tables and columns.

### Main lesson
Understand how the application processes input instead of memorizing payloads.

**Status:** Completed 
