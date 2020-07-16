# intro_to_python
Intro to Python course July2020
To bring this data into your Python program, add the following lines of code:
```python
import pandas
data = pandas.read_csv("https://raw.githubusercontent.com/kasun-maldeni/intro-to-python/master/data.csv")
data = pandas.read_csv("https://raw.git.generalassemb.ly/kasun/intro-to-python/master/data.csv")
print(data.values)
