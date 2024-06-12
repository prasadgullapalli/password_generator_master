# Password-Generator: Java Console Application

## Introduction

I developed this project during the Winter Break of my second year after completing the Object-Oriented Effective Java Programming course. My goal was to practice my Java skills by building an interesting project. The idea for a random password generator came to me while explaining to my father the importance of strong passwords for his social media accounts. A week later, the project was completed.

Additionally, I incorporated a password strength checker to evaluate the robustness of the generated passwords. Although I was pleased with the outcome, I realized the application wasn't user-friendly for those unfamiliar with its functionality. As a result, I created a GUI version, which is available in the Password-Services repository.

## Functionalities

### 1. Generating a Password

The application guides the user through the following steps to create a password:

1. **User Preferences:** 
   - The user answers "Yes" or "No" to questions about including uppercase letters, lowercase letters, numbers, or symbols in the password.

2. **Password Length:**
   - The user specifies the desired length of the password.

3. **Password Alphabet Creation:**
   - Based on the user's preferences, a password alphabet is generated, consisting of the selected characters.

4. **Random Password Generation:**
   - Random characters from the password alphabet are selected and combined to form a completely random string that meets the user's criteria.

5. **Display Password:**
   - The randomly generated password is displayed on the console.

### 2. Checking a Password's Strength

The strength checker evaluates the password based on the following criteria:

- Inclusion of uppercase letters.
- Inclusion of lowercase letters.
- Inclusion of numbers.
- Inclusion of symbols.
- Password length of 8 or more characters (minimum for a decent password).
- Password length of 16 or more characters (minimum for a good password).

These criteria are used to calculate a score, which determines the strength message (weak/medium/good/great) displayed to the user.

### 3. Displaying Useful Information

This minor feature provides the user with information on password security practices, such as:

- Avoiding the reuse of passwords.
- Avoiding character repetition, keyboard patterns, dictionary words, and letter or number sequences.

---

By incorporating these functionalities, the application aims to help users create strong, secure passwords and understand the importance of password security.
