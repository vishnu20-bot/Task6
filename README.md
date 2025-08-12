# Task6

 Understand what makes a password strong and test it against password strength tools

 # 🔐 Password Strength Testing Report

## Objective
Understand what makes a password strong and test different passwords using online strength checkers.

## Tools Used
- [PasswordMeter.com](https://passwordmeter.com)
- [How Secure Is My Password?](https://howsecureismypassword.net)

---

## 1. What Makes a Password Strong
A good password is:
- **Long:** At least 12–16 characters
- **Complex:** Mix of uppercase, lowercase, numbers, and symbols
- **Unpredictable:** Avoid dictionary words or personal info
- **Unique:** Different for every account



## 2. Test Results

| Password Tested     | Length | Complexity | PasswordMeter Score | Estimated Crack Time* |
|---------------------|--------|------------|----------------------|-----------------------|
| `password123`       | 11     | Low        | 12%                  | < 1 second            |
| `Summer2024`        | 10     | Medium     | 42%                  | 2 minutes             |
| `T!m3toFly_2025`    | 13     | High       | 88%                  | 40 years              |
| `V3!n^4bQ7$kLz@2`   | 15     | Very High  | 100%                 | Millions of years     |

\* Crack time estimates from howsecureismypassword.net.



## 3. Observations:

- Adding numbers, symbols, and mixed case increases security.
- Longer passwords are harder to crack.
- Simple or common passwords fail immediately in strength tests.
- Using personal information makes passwords predictable.


## 4. Advanced Observations:
1. **Length exponentially increases cracking difficulty** — doubling length can multiply crack time thousands of times.
2. **Entropy is key** — high entropy = unpredictability.
3. Passwords found in public breaches are unsafe **no matter their complexity**.
4. Passphrases (e.g., `Yellow$Train!Galaxy27`) can be both **memorable and secure**.



## 5. Recommendations
- Minimum length: **16 characters** for high-security accounts.
- Use **all four character types** (upper, lower, numbers, symbols).
- Avoid reuse — each service should have its own unique password.
- Check passwords against breach databases before use.
- Implement **Multi-Factor Authentication (MFA)** to mitigate password compromise.
  
# 6. Conclusion
A strong password is **Long + Complex + Random + Unique**.  
For better security:
- Use a password manager to store complex passwords.
- Use passphrases for easy recall (e.g., `Blue!River8Cloud#Sun`).
- Enable Multi-Factor Authentication (MFA) for important accounts.


