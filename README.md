# Task 6: Create a Strong Password and Evaluate Its Strength

## Objective
Understand the elements that make a password strong and evaluate it using online password strength checkers.

---

## Tools Used
- [PasswordMeter.com](https://www.passwordmeter.com)
---

## Steps Followed

### Step 1: Create Multiple Passwords
Created 5 different passwords with varying complexity:

| Password                           | Type                            |
|------------------------------------|----------------------------------|
| `password123`                      | Weak – common word + numbers     |
| `password`                         | Weak – common word               |
| `12345678`                         | Weak – numbers                   |
| `Pass@2024`                        | Medium – mix of case + symbol    |
| `!@#%&!*`                          | Strong – symbols                 |
| `R3d$!Sh!ft&*G4l@xy%Pl@n3t2025`    | Extremely strong – passphrase-like |

---

### Step 2: Test Passwords on Strength Tools

Each password was tested on PasswordMeter and Kaspersky:

| Password                           | PasswordMeter Score | Kaspersky Strength     | Time to Crack Estimate     |
|------------------------------------|---------------------|-------------------------|-----------------------------|
| `password123`                      | 25%                 | Very Weak               | < 1 second                  |
| `Pass@2024`                        | 55%                 | Weak                    | Minutes                     |
| `!@#%&!*    `                      | 90%                 | Strong                  | Years                       |
| `R3d$!Sh!ft&*G4l@xy%Pl@n3t2025`    | 100%                | Excellent               | Brute-force impractical     |

---

## What I Learned

### What Makes a Password Strong
- Long (at least 12+ characters)
- Mix of uppercase, lowercase, numbers, and symbols
- Avoid dictionary words or personal info
- Use randomness or passphrases

### Common Mistakes
- Reusing old passwords
- Using names, birthdays, or "123456"
- Short or predictable patterns

---

## Summary of Password Attacks

| Attack Type       | Description |
|-------------------|-------------|
| **Brute Force**   | Tries every possible combination. |
| **Dictionary**    | Uses a list of common words/passwords. |
| **Phishing**      | Tricks users into revealing passwords. |
| **Keylogging**    | Captures typed input to steal credentials. |

---

## What is Multi-Factor Authentication (MFA)?
An extra layer of security beyond just a password, e.g., password + OTP.

---

## How Password Managers Help
- Generate strong, random passwords
- Securely store credentials
- Save time and reduce reuse risks

---

## Tips
- Use **passphrases** (e.g., `Correct$Battery!Staple2025`)
- Don’t reuse passwords across platforms
- Always enable **MFA**
- Use trusted **password managers** like Bitwarden or KeePass
