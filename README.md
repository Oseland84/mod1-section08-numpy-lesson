
### Questions From Students At Beginning of Class


### Objectives
YWBAT 
* compare and contrast lists and sets in python
* calculate the number of permutations vs combinations for a given set of numbers
* compute the probability for the following situations
    * basic probability
    * probability with combinations
    * probability with permutations
* compute bernouli/binomial calculations


```python
import numpy as np
from string import ascii_uppercase
from collections import Counter
```

### Before we begin, we need the following function


```python
def factorial(n):
    """
    choose a student to write this function
    input
    n: int - some positive integer
    
    returns
    fac_n: int - n! ex: if n = 5 we return 5! = 120
    """
    pass
```


```python
# lst
lst = np.random.randint(0, 20, 10)
lst
```




    array([ 8,  6,  9,  9, 13, 17,  5,  5,  2, 17])




```python
# What is the set of the list above?
set(lst)
```


```python
# how many permutations exist for the set of numbers?

```


```python
# how many different groups of 3 can be made from the set of number?

```


```python
def combinations(n, k):
    """
    input
    n: int - the total number of objects
    k: int - the desired group size
    
    return
    m: int - the total number of groups of size k for a given population size n
    """
    pass
```


```python
first_letters = np.random.choice(list(ascii_uppercase), 30)
first_letters_dictionary = Counter(first_letters)
first_letters_dictionary
```




    Counter({'C': 1,
             'D': 1,
             'E': 2,
             'F': 2,
             'G': 1,
             'H': 1,
             'J': 2,
             'K': 2,
             'L': 1,
             'O': 1,
             'P': 1,
             'Q': 1,
             'R': 1,
             'S': 2,
             'T': 2,
             'U': 3,
             'W': 1,
             'X': 2,
             'Y': 2,
             'Z': 1})




```python
"""
The dictionary above is a dictionary of first letters of names of 30 students

What is the probability of choosing a student whose first name begins with an F or a G?

What is the probability of choosing a students whose first name begins with a vowel?

What is the probability of choosing a student and their first name doesn't begin with letters P-Y?
"""

# solutions here



```


```python
### Bernouli/Binomial Problems
```


```python
"""
Use the dictionary of first letter names above

You pick a student at random 10 times in a row.  If you pick a student who's
name begins with a P, Y, T, H, O, N you win the round!

What is the probability of winning exactly 6 games?


What is the probability of winning more than 6 games?


What is the probability of winning less than 6 games?


What is the probability of winning less than 4 games?
"""


```


```python
# Write a function that calculates a Bernouli Probability 

def bernouli(p, q, games, wins_needed):
    """
    input
    p: float - fill in description
    q: float - fill in description
    games: int - fill in description
    wins_needed: int - fill in description
    
    return
    prob: float - fill in description
    """
    pass
```
