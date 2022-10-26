# Quiz 017

Create a function that produces the average world length of the input list


```.py
def averageLength(words:list)->float:
    total = 0
    for word in words:
        total += len(word)
    return total / len(words)

