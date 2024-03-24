# kitty_ipsum_1.txt info

### Number of lines:
``` bash    
$ wc -l kitty_ipsum_1.txt

27
```

### Number of words:
```  bash 
$ wc -w kitty_ipsum_1.txt

332
```

### Number of characters:
```  bash 
$ wc -m kitty_ipsum_1.txt
?
1738
```

### Number of times meow or meowzer appears:
```  bash 
$ grep -o 'meow[a-z]*' kitty_ipsum_1.txt | wc -l

7
```

### Lines that they appear on:
```  bash 
$ grep -n 'meow[a-z]*' kitty_ipsum_1.txt | sed -E 's/([0-9]+).*/\1/'

1
4
10
22
23
```
