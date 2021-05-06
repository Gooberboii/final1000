# About Me
## This is for my final project.

Click [here](setup/README.md) for General Information
![logo](images/gslogo.png)

```
# Python program to shuffle a deck of card

import itertools, random

deck = list(itertools.product(range(1,14),['Spade','Heart','Diamond','Club']))

random.shuffle(deck)

print("You got:")
for i in range(5):
   print(deck[i][0], "of", deck[i][1])
```




## Reporting Bugs and Contributing Code

* Want to report a bug or request a feature? Please open [an issue](https://github.com/Gooberboii/markdown_example/issues/new).