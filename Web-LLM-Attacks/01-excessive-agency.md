# 01 – Excessive Agency

- **Goal:** Delete user `carlos` using LLM's exposed SQL API.
- **Steps:**
  - Asked LLM for available APIs → Debug SQL API found.
  - Sent: `SELECT * FROM users` → confirmed `carlos` exists.
  - Sent: `DELETE FROM users WHERE username='carlos'` → success ✅

- **Key Takeaway:** LLM had unsafe access to sensitive functions like raw SQL execution.

