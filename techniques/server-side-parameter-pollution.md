# Server-Side Parameter Pollution (SSPP)

## Objective

Bypass frontend restrictions and inject new parameters into server-side logic.

---

## Method

- Used `%26` to inject parameters like: `username=admin%26field=email%23`
- Used `%23` (`#`) to truncate the rest of the query or body
- Brute-forced field names using Burp Intruder and built-in payloads
- Extracted password reset tokens or forced internal state changes

---

## Sample Payloads

```http
username=admin%26field=email%23
username=admin%26field=reset_token%23

