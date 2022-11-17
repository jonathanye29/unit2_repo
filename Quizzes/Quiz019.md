# Quiz 019
Create a function that changes the vowels in a string to numbers such as a=4,e=3,i=1,o=0 and space by _


```.py
# METHOD 1
def get_l3tt3r(msg:str):
    out = ""
    for letter in msg:
        if letter.lower() == "a":
            out += "4"
        elif letter.lower() == "e":
            out += "3"
        elif letter.lower() == "i":
            out += "1"
        elif letter.lower() == "o":
            out += "0"
        elif letter.lower() == " ":
            out += "_"
        else:
            out += letter
    return out
    
# METHOD 2
def get_l3tt3r2(msg:str):
    out = ""
    letters = {"a": "4", "e": "3", "i": "1", "o": "0", " ": "_"}
    for letter in msg:
        if letter.lower() in letters:
            out += letters[letter.lower()]
        else:
            out += letter
    return out
```

![](qui019.jpg)


## Boolean Circuit

![](quiz019booleancircuit.jpg)




