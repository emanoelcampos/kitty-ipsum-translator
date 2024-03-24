# kitty_ipsum_1.txt info

### Number of lines:
```
$ wc -l kitty_ipsum_1.txt

27
```

### Number of words:
```
$ wc -w kitty_ipsum_1.txt

332
```

### Number of characters:
```
$ wc -m kitty_ipsum_1.txt

1738
```

### Number of times meow or meowzer appears:
```
$ grep -o 'meow[a-z]*' kitty_ipsum_1.txt | wc -l

7
```

### Lines that they appear on:
```
$ grep -n 'meow[a-z]*' kitty_ipsum_1.txt | sed -E 's/([0-9]+).*/\1/'

1
4
10
22
23
```
