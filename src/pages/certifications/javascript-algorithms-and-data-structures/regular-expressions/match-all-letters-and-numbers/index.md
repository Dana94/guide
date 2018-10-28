---
title: Match All Letters and Numbers
---

## Match All Letters and Numbers

Use the shorthand character class `\w` to count the number of alphanumeric characters in various quotes and strings.

## Hint 1:

Be sure to include the `g` flag. You won't need the `i` flag here (but it's fine if you do) since `\w` covers both lower and uppercase letters. 


## Spoiler Alert - Solution Ahead!

## Solution:

```javascript
let quoteSample = "The five boxing wizards jump quickly.";
let alphabetRegexV2 = /\w/g;
let result = quoteSample.match(alphabetRegexV2).length;
```



