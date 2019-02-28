# EECS 201 HW 6
uniqname:  patelpri

## Question 1
``` 1
Putting a carrot in front of a term means it will sort the list with the term in the beginning only.
```

## Question 2
``` 2
Dollar sign at the end sorts the list with the term at the end.
```

## Question 3
``` 3
Period fills in any letter or character in the grep'd term. So "..th" would give a result from "10th" to "with".
```

## Question 4
``` 4
grep -c '^...$' cracklib-small
```

## Question 5
``` 5
grep -c ^[a-zA-Z][a-zA-Z][a-zA-Z]$ cracklib-small
```

## Question 6
``` 6
The command counts the amount of vowels (a, i, e, o, u) in cracklib-small, then lists them with number of reoccurences of each vowel in alphabetical order.
```

## Question 7
``` 7

```

## Question 8
``` 8
answer_to_Q8_here
```

## Question 9
``` 9
The command will search for terms do not have space and * right next to each other. So nothing with " *"
```

## Question 10
``` 10
git grep does not search in untracked files, unless told to do so.
```

## Question 11
``` 11
Yes git grep does search new files that have been staged but not commited. I added hw6.md and created a testing.md file and staged them, ran git grep and it searched those both of the files.
```
