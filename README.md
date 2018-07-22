# Password lists.

- default router credentials
- Password spraying

More passwords lists: https://github.com/danielmiessler/SecLists/tree/master/Passwords 

### CWE - 521 : Weak Password Requirements

The product does not require that users should have strong passwords, which makes it easier for attackers to compromise user accounts.An authentication mechanism is only as strong as its credentials. For this reason, it is important to require users to have strong passwords. Lack of password complexity significantly reduces the search space when trying to guess user's passwords, making brute-force attacks easier.

```
For more information, see: http://cwe.mitre.org/data/definitions/521.html
```