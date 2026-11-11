# My First Try (Before AI)

### Step 1: My claims:

## Problems Identified

1. **Missing value:** I noticed that one price is missing. I would keep the row and investigate the missing value.

2. **Duplicate row:** I found a repeated record. I would remove the extra copy after checking it.

3. **Unusual price (9999):** This price looks too high compared to the others. I would flag it for checking.

4. **Price formatting (1,250):** One price contains a comma. I would remove the comma to convert it into a number, then check whether the value is correct.

5. **Incorrect item name:** The item "oil b" looks inconsistent. I would investigate whether it should be "Staple A".

6. **Wrong data type:** Prices are stored as text. I would convert them into numeric values.

## My Cleaning Plan

I would use Python and pandas to check missing values, duplicates, item names and unusual prices. I would avoid changing any suspicious value without proper evidence and compare the data before and after cleaning.
