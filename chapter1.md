---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

Define vector (1,3,4) and store it to variable a. Calculate a^2 and store it to variable b.

`@instructions`


`@hint`


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}

```

`@solution`
```{r}
a <- c(1,3,4)
b <- a^2
```

`@sct`
```{r}
check_error()
success_msg("Well done!", praise = FALSE)
```
