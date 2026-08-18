# Natas Level 3 ➔ Level 4

- **Target URL:** `http://natas3.natas.labs.overthewire.org`
- **Vulnerability:** Information Disclosure via `robots.txt` / Insecure Directory Listing

### Execution & Solution
1. Authenticated to Level 3 in Firefox using credentials `natas3:K3OJrSRHzjxq3paUQuwozY4MNvmNFyhI`.
2. Inspected the HTML source code (`Ctrl + U`) and noticed the comment indicating search engines are blocked: `<!-- No more information leaks!! Not even Google will find it this time... -->`.
3. Navigated directly to `http://natas3.natas.labs.overthewire.org/robots.txt` and discovered the hidden path `Disallow: /s3cr3t/`.
4. Visited `http://natas3.natas.labs.overthewire.org/s3cr3t/users.txt` to extract the password for **natas4**.

### Retrieved Password for Natas4
`JDrPnuZAKyl6MkiqQGFiddrqpvgOASth`

### Proof Screenshot
![Level 3 Proof](./proof.png)
