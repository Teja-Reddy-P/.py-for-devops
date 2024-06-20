string-concat.py

str1 = "Hello"
str2 = "World"
result = str1 + " " + str2
print(result)


string-len.py


text = "Python is awesome"
length = len(text)
print("Length of the string:", length)


string-lowercase.py

text = "Python is awesome"
uppercase = text.upper()
lowercase = text.lower()
print("Uppercase:", uppercase)
print("Lowercase:", lowercase)

String-replace.py


text = "Python is awesome"
new_text = text.replace("awesome", "great")
print("Modified text:", new_text)



string-split.py

text = "Python is awesome"
words = text.split()
print("Words:", words)


string-strip.py

text = "   Some spaces around   "
stripped_text = text.strip()
print("Stripped text:", stripped_text)

string-substring.py

text = "Python is awesome"
substring = "is"
if substring in text:
    print(substring, "found in the text")

float.py

    # Float variables
num1 = 5.0
num2 = 2.5

# Basic Arithmetic
result1 = num1 + num2
print("Addition:", result1)

result2 = num1 - num2
print("Subtraction:", result2)

result3 = num1 * num2
print("Multiplication:", result3)

result4 = num1 / num2
print("Division:", result4)

# Rounding
result5 = round(3.14159265359, 2)  # Rounds to 2 decimal places
print("Rounded:", result5)

int.py


# Integer variables
num1 = 10
num2 = 5

# Integer Division
result1 = num1 // num2
print("Integer Division:", result1)

# Modulus (Remainder)
result2 = num1 % num2
print("Modulus (Remainder):", result2)

# Absolute Value
result3 = abs(-7)
print("Absolute Value:", result3)


regex-findall.py


import re

text = "The quick brown fox"
pattern = r"brown"

search = re.search(pattern, text)
if search:
    print("Pattern found:", search.group())
else:
    print("Pattern not found")

regex-match.py


    import re

text = "The quick brown fox"
pattern = r"quick"

match = re.match(pattern, text)
if match:
    print("Match found:", match.group())
else:
    print("No match")

regex-replace.py


import re

text = "The quick brown fox jumps over the lazy brown dog"
pattern = r"brown"

replacement = "red"

new_text = re.sub(pattern, replacement, text)
print("Modified text:", new_text)


regex-search.py


import re

text = "The quick brown fox"
pattern = r"brown"

search = re.search(pattern, text)
if search:
    print("Pattern found:", search.group())
else:
    print("Pattern not found")

regex-split.py


    import re

text = "apple,banana,orange,grape"
pattern = r","

split_result = re.split(pattern, text)
print("Split result:", split_result)
