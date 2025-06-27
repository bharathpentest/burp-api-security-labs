# Summary: Burp Suite API Security Labs

## Key Takeaways

- Modern APIs expose more attack surface than classic web apps.
- Server-side validation and hidden parameters are often misused.
- Simple characters like `&`, `%23`, `=` can break logic.
- Mass assignment and object injection are critical API risks.
- Tools like Intruder, Repeater, and Param Miner are essential for testing APIs.

---

## Topics Completed

- API Recon: How to locate APIs with minimal clues
- API Documentation: Reverse-engineering client-side JS and Swagger
- Endpoint Interaction: Sending custom requests and altering behavior
- Hidden Parameters: Discovering undocumented functionality
- Mass Assignment: Manipulating JSON to escalate privileges
- SSPP (Server-Side Parameter Pollution): Injecting internal parameters

---

## Learning Approach

I used Burp Suite’s browser and tools to manually inspect requests, modify headers, fuzz parameters, and identify logic flaws.

