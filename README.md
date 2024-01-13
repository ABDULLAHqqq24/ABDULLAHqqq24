- 👋 Hi, I’m @ABDULLAHqqq24
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
ABDULLAHqqq24/ABDULLAHqqq24 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import random

# generate a random number with 16 digits
card_number = random.randrange(10**15, 10**16)

# convert the number into a string
card_number = str(card_number)

# add the first digit (4) to the beginning of the string
card_number = '4' + card_number

# generate a random 3-digit CVV code
cvv = random.randrange(100, 1000)

# convert the CVV code into a string
cvv = str(cvv)

# generate a random expiration date (month and year)
expiration_month = random.randrange(1, 13)
expiration_year = random.randrange(2022, 2032)

# convert the month and year into a string and combine them
expiration_date = str(expiration_month) + '/' + str(expiration_year)

# print out the generated information
print('Credit card number:', card_number)
print('CVV code:', cvv)
print('Expiration date:', expiration_date)
