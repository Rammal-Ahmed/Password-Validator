# 🔐 Password Validator

A small command-line program written in Python that checks whether a password is strong enough, and tells you what to fix if it isn't.

I built this while practicing loops, conditions and string handling as part of my Python learning journey.

## What it checks

A password is accepted only when it:

- is at least **8 characters** long
- contains **letters**
- contains at least one **number**
- contains the **@** sign

If something is missing, the program points out exactly what to add.

## How to run

Make sure Python 3 is installed, then:

```bash
git clone https://github.com/Rammal-Ahmed/password-validator-python.git
cd password-validator-python
python password_validator.py
```

## Example

```
==============================
      PASSWORD VALIDATOR
==============================
Enter a password:
hello@123

Password Accepted

==============================
   SEE YOU IN NEXT REPOS...!
==============================
```

If something is missing:

```
Enter a password:
hello123

Please add an @ sign to your password
```

## What I practiced

- Looping through a string character by character
- Using boolean flags to track conditions
- Writing clear `if / elif / else` logic
- Giving the user helpful, readable feedback

## Possible improvements

- Show every missing requirement at once instead of one at a time
- Allow more special characters, not just `@`
- Let the user retry until the password is accepted

## About me

**Rammal Ahmed**

**AI & Data Science Enthusiast** | **Microsoft Dynamics 365 CRM Developer** | **Power Platform** | **UI/UX Designer** | **Graphic Designer & Illustrator**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rammal-ahmed-58184b325)
[![GitHub](https://img.shields.io/badge/GitHub-Rammal--Ahmed-181717?style=flat&logo=github)](https://github.com/Rammal-Ahmed)

<div align="center">

⭐ If you found this useful, consider giving it a star ⭐

**I truly value your feedback and welcome any suggestions for improvement**

**Always open to fresh perspectives, constructive feedback, and new ideas**


## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Project Status:** Completed

</div>
