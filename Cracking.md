## Password Cracking

### Common password weaknesses:

- Short passwords creating **low entropy**
- **Common words/phrases** found easily in wordlists
- Use of **personal information**
- **Reuse** across accounts
- **Predictable patterns** like "qwerty" or "123456"

### Brute-Force Attacks

Brute-force attacks leverage **raw system resources over poorly implemented password systems.**

### Dictionary Attacks

Dictionary attacks exploit the tendency of users to use **memorable words and phrases**. [SecLists](https://github.com/danielmiessler/SecLists/) maintains a popular library of **wordlists.**

### Hybrid Attacks

Hybrid attacks exploit user complacency in adhering to password-change policies. A dictionary attack can be adapted to resemble a brute-force attack by **appending numbers, special characters, or successive years to each word in a list.**

### Credential Stuffing

Credential stuffing exploits password reuse by **trying breached passwords from other services.** This can lead to obtaining keys-to-the-castle if a personal email is compromised.
