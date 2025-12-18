# Data Cleaning in Python

## Why Clean Data?
Raw data often contains errors, missing values, or inconsistencies. Cleaning ensures accuracy and reliability.

## Common Issues
- Missing values (`NaN`)
- Duplicates
- Incorrect data types
- Outliers

## Techniques
- `df.dropna()` → remove missing values
- `df.fillna(value)` → replace missing values
- `df.drop_duplicates()` → remove duplicates
- `df.astype(type)` → convert data types

## Best Practices
- Always check with `df.info()` before cleaning.
- Document every cleaning step.
- Keep a copy of raw data for reference.
