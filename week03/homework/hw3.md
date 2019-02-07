# EECS 201 HW 4
uniqname: patelpri

## Question 1
``` 1
"ls" used to work before PATH= but it doesn't anymore. "touch" doesn't work either.
```

## Question 2
``` 2
/bin/<command> let you run commands with an empty PATH.
```

## Question 3
``` 3
"/bin/ls"and "/bin/touch" work. Since PATH was set to empty, this is telling terminal where to get the command what directory to execute.
```

## Question 4
``` 4
"$" is used to refer to a variable, to know the value or to refer to a variable. An example would be "echo $b" to print out value of b.
```

## Question 5
``` 5
"$1" gives the first argument in the executed script. For example in a script where ./command -A -B, $1 would output -A.
```

## Question 6
``` 6
gcc -o HelloWorld HelloWorld.c
./HelloWorld >> output
echo "Hello World!" >> testing.md
diff output testing.md
echo All tests passed.
```

## Question 7
``` 7
Modifying ~/.profile will add a custom PATH. To make sure this change occurs evertime, this command should be run. "export PATH=$PATH:/usr/local/foo"
```

## Question 8
``` 8
4 hours
```

