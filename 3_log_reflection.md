# Reflection





\# Assignment 2: The Dirty Ledger

\## Reflection Questions and Answers



\### Question 1: Which of your decisions differed from the AI's?



\*\*Answer:\*\*



Some of my decisions were different from the AI's suggestions. For example, the AI suggested removing rows with missing prices, but I decided to keep them because they still contain useful information.



The AI also suggested replacing unusual prices with other values. I decided to flag prices like 9999 and 1,250 instead of guessing their correct values.



I also kept the original item names so I could check any changes later.



\### Question 2: Which decisions were better supported, and why?



\*\*Answer:\*\*



I think keeping the original data and flagging suspicious values was a better decision because there was no proof of what the correct values should be.



For example, changing 9999 to another number without checking could give incorrect results. Removing a row just because its price is missing could also mean losing useful information.



Removing the exact duplicate was a good decision because the same record appeared twice.



These decisions helped make the data cleaner without changing information unnecessarily.



\### Question 3: What would you have missed if you worked alone without AI?



\*\*Answer:\*\*



Without AI, I might have missed some problems in the dataset. For example, I might not have noticed that the price 1,250 contained a comma, which caused problems when converting the column into numbers.



I also might have missed the duplicate row or the unusual item name "oil b".



AI helped me understand how to check these problems using Python. However, I learned that I should not accept every AI suggestion without checking it first.



\### Question 4: How did you check that the cleaning worked correctly?



\*\*Answer:\*\*



I compared the data before and after cleaning.



The original dataset had 97 rows, and the cleaned dataset had 96 rows because one duplicate was removed.



Before cleaning, there was one missing price. After cleaning, there were three missing or flagged prices because two unusually high prices were also marked for review.



I also checked the item names, duplicate records and price statistics.



This helped me make sure that I did not accidentally remove useful information.



\### Question 5: What did you learn from this assignment?



\*\*Answer:\*\*



I learned that cleaning data is not just about deleting missing values or fixing errors.
