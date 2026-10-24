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

## Git Setup and Cybersecurity Learning

- Reinstalled Git after formatting my laptop.
- Cloned my existing cybersecurity-learning repository from GitHub.
- Verified that my local main branch is synchronized with origin/main.
- Learned the purpose of git status.
- Current focus: strengthening web security fundamentals.

### Git Workflow

1. Edit files.
2. Use git status to inspect changes.
3. Use git add to stage changes.
4. Use git commit to save a snapshot.
5. Use git push to upload commits to GitHub.
