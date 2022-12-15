# Quiz 025

Create a program shows the graph of the function below for 100 values of x in the interval -10 < x < 10

```.py
from matplotlib import pyplot as plt

def produce():
    x_out = []
    y_out = []
    x = -10
    for i in range(100):
        x += 0.2
        x_out.append(x)
        y = abs(x)
        y_out.append(y)
    return x_out, y_out

value_y, value_x = produce()

plt.plot(value_y, value_x, color="red")
plt.xlabel("x")
plt.ylabel("$y = |x|$")
plt.show()
```

<img width="1512" alt="Screen Shot 2022-12-15 at 9 21 35 AM" src="https://user-images.githubusercontent.com/111751273/207743508-3d18ba21-8338-4191-babe-9e2c4e235e3a.png">
