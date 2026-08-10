# Natas Level 1 ➔ Level 2

- **Target URL:** `http://natas1.natas.labs.overthewire.org`
- **Vulnerability:** Client-Side Right-Click Restriction / Source Code Disclosure

### Execution & Solution
1. Authenticated to Level 1 using `natas1:scfWG0qNEIdzqvyfRwEGXyNUfFZkZeQ7`.
2. Observed that right-clicking was blocked on the page via JavaScript (`oncontextmenu`).
3. Bypassed the restriction by opening the page source directly using `Ctrl + U` (or `view-source:` prefix in Firefox).
4. Located the commented password for **natas2**.

### Retrieved Password for Natas2
`vsD0xoXyq3wckCP1ZmTZ7IngIA606odB`

### Proof Screenshot
![Level 1 Proof](./proof.png)
