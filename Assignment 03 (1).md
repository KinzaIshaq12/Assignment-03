# Assignment 03: -

### 1. Create a string variable with your name and print it.


```python
my_name = "KINZA ISHAQ"
print(my_name)
```

    KINZA ISHAQ
    

### 2. Define a multiline string that includes line breaks and print it.


```python
string = """I am Student of M.Phil. 
I am completing assignment which is assigned by our professor.
It is easy to understand and execute"""
print(string)
```

    I am Student of M.Phil. 
    I am completing assignment which is assigned by our professor.
    It is easy to understand and execute
    

### 3. Access the first character of a string.


```python
first_character = string[0]
print(first_character)
```

    I
    

### 4. Access the last character of a string.


```python
len(string)
```




    124




```python
last_character = string[123]
print(last_character)
```

    e
    

### 5. Access the second to the fifth character of a string.


```python
multi_characters = string[1:4]
print(multi_characters)
```

     am
    

### 6. Attempt to change a character within an existing string and explain the result.


```python
new_string = string[:9] + 'd' + string[17:]

print(new_string)

```

    I am Studd.Phil. 
    I am completing assignment which is assigned by our professor.
    It is easy to understand and execute
    

### 7. Slice a string to obtain the first 3 characters.


```python
three_characters = string[:3]
print(three_characters)
```

    I a
    

### 8. Slice a string to obtain the last 4 characters.


```python
four_characters = string[120:124]
print(four_characters)
```

    cute
    

### 9. Slice a string to get every second character.


```python
every_second = string[::2]
print(every_second)
```

    Ia tdn fMPi.
     mcmltn sinetwihi sindb u rfso.I ses oudrtn n xct
    

### 10. Reverse a string using slicing.


```python
reverse = string[::-1]
print(reverse)
```

    etucexe dna dnatsrednu ot ysae si tI
    .rosseforp ruo yb dengissa si hcihw tnemngissa gnitelpmoc ma I
     .lihP.M fo tnedutS ma I
    

### 11. Create two string variables and concatenate them.


```python
a = "Kinza"
b = "Ishaq"
concatenate = a + b
print(concatenate)
```

    KinzaIshaq
    

### 12. Concatenate a string with a number (convert the number to a string first).


```python
message = "my birthday is"
print(message)
```

    my birthday is
    


```python
num = 12
print(num)
```

    12
    


```python
type(num)
```




    int




```python
string = str(num)
print(string)
type(string)
```

    12
    




    str




```python
concatenate = message + string
print(concatenate)
```

    my birthday is12
    

### 13. Generate a string that repeats "abc" 10 times.


```python
string = "abc" * 10
print(string)
```

    abcabcabcabcabcabcabcabcabcabc
    

### 14. Create a string containing a repeating pattern of your choice.


```python
repeat = "12" * 15
print(repeat)
```

    121212121212121212121212121212
    

### 15. Convert a string to lowercase using the lower() method.


```python
string = "KINZA"
print(string)

```

    KINZA
    


```python
lower_name = str.lower(string)
print(lower_name)
```

    kinza
    

### 16. Convert a string to uppercase using the upper() method.


```python
string = "kinza"
print(string)

```

    kinza
    


```python
upper_name = str.upper(string)

print(upper_name)
```

    KINZA
    

### 17. Remove leading and trailing whitespace from a string using the strip() method.


```python
text_message = "   i am a girl and i am 24 years old   "
print(text_message)
```

       i am a girl and i am 24 years old   
    


```python
stripped_string = text_message.strip()
print(stripped_string)
```

    i am a girl and i am 24 years old
    

### 18. Check if a string starts with a specific prefix using the startswith() method.

### Condition 01: -


```python
message = "KINZA ISHAQ"
prefix = "KINZA"
start = message.startswith(prefix)
print(start)
```

    True
    

### Condition 02: -


```python
message = "KINZA ISHAQ"
prefix = "ISHAQ"
start = message.startswith(prefix)
print(start)
```

    False
    

### 19. Split a string into a list of words using the split() method.


```python
string = "NN & AI CLASS ASSIGNMENT"
splitted = string.split()
print(splitted)
```

    ['NN', '&', 'AI', 'CLASS', 'ASSIGNMENT']
    

### 20. Join a list of words into a single string using the join() method.


```python
words = ["kinza" , "ishaq" , "m.phil" , "student"]
joined = " ".join(words)
print(joined)
```

    kinza ishaq m.phil student
    


```python

```
