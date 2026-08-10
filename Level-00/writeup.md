# Natas Level 0 ➔ Level 1

- **Target URL:** `http://natas0.natas.labs.overthewire.org`
- **Vulnerability:** HTML Source Code Disclosure

### Execution & Solution
1. Connected to the Natas Level 0 target using `curl` with default credentials (`natas0:natas0`).
2. Inspected the raw HTML source code returned by the server.
3. Located the commented flag containing the password for **natas1**.

```bash
curl -u natas0:natas0 [http://natas0.natas.labs.overthewire.org](http://natas0.natas.labs.overthewire.org)
