---
title       : Data and Visualizations in R
description : Basic navigation in R, common functions, indexing, help, etc.

--- type:NormalExercise lang:r xp:100 skills:1 key:17b7ba7439
## Simple Operations
In the following exercise you will learn how R can be used as the greatest calculator of all time!  

*** =instructions
- Add 45 and 32
- Subtract 32 from 45
- Multiply 32 and 45
- Divide 32 by 8
- Find the square root of 49
- Raise 32 to power of 3


*** =hint

Type the mathematical operations in the console and choose "Submit Answer".

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}

```

*** =solution
```{r}
45 + 32
45 - 32
32 * 45
32 / 8
sqrt(49)
32 ^ 3
```

*** =sct
```{r}
test_output_contains("77", incorrect_msg = "Try again")
test_output_contains("13", incorrect_msg = "Try again")
test_output_contains("1440", incorrect_msg = "Try again")
test_output_contains("4", incorrect_msg = "Try again")
test_output_contains("7", incorrect_msg = "Try again")
test_output_contains("32768", incorrect_msg = "Try again")


test_error()

success_msg("Good work!")
```
