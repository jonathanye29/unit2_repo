# Quiz 029

Create a function that receives a dictionary with letters in the alphabet as keys and a string. The functions returns the dictionary with a count as value for the occurrence of each letter:

```.py
def count_letters(my_dict, msg):
    for letter in msg:
        if letter in my_dict.keys():
            my_dict[letter] += 1
    return my_dict

test1  = count_letters({'w':0,'l':0,'c':0}, "Hello world")
test2  = count_letters({'a':0,'e':0,'i':0,'o':0,'u':0}, "Why did  I choose CS?")
print(test1)
print(test2)
```

![](quiz029.jpg)

## Part B
### How many different colors could you represent in a 6 bit computer? 
Systems with a 6-bit RGB palette use 2 bits for each of the red, green, and blue color components. This results in a (22)3 = 43 = 64-color palette.

Citation: https://en.wikipedia.org/wiki/List_of_monochrome_and_RGB_color_formats#:~:text=6%2Dbit%20RGB,-Systems%20with%20a&text=6%2Dbit%20RGB%20systems%20include,AT%20(16%20colors%20at%20once)
