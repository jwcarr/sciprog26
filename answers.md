Unit 1
======

Question 1
----------

What is the result of `5 * 8 + 40 / 2`?

- [x] `60.0`
- [ ] `40.0`
- [ ] `120`


Question 2
----------

What is the result of `10 / 5`?

- [ ] `0.5`
- [ ] `2`
- [ ] `DivisionError`
- [x] `2.0`


Question 3
----------

What is the result of `f"Ciao, {name * 3}!"` given that `name = "Pedro"`?

- [ ] `'Ciao, Pedro!Ciao, Pedro!Ciao, Pedro!'`
- [x] `'Ciao, PedroPedroPedro!'`
- [ ] `'Ciao, Pedro!Pedro!Pedro!'`
- [ ] `FormattingError`


Question 4
----------

What is the result of `(1 == 2) == False`?

- [x] `True`
- [ ] `False`
- [ ] `SyntaxError`


Question 5
----------

Given the list of colors defined above, what is the result of `colors[2][1]`?

- [ ] `'red'`
- [ ] `'green'`
- [x] `'r'`
- [ ] `True`


Question 6
----------

What's the difference between lists and dictionaries?

- [ ] Only dictionaries have indexes.
- [ ] Dictionaries can hold strings, while lists can only hold numbers.
- [ ] Lists and dictionaries are essentially the same.
- [x] Dictionary items are accessed by key and list items are accessed by index.


Question 7
----------

Which of these statements is wrong?

- [x] Each if-statement needs to be completed with an else clause.
- [ ] If-statements restrict a block of code to running only under certain conditions.
- [ ] If-statements modify the sequential flow of the program.
- [ ] Every if-statement contains an expression that is evaluated.


Question 8
----------

Given the for-loop `for number in range(10, 20):`, how many times would its associated code block be executed?

- [ ] 9
- [ ] 20
- [x] 10
- [ ] 2
- [ ] Unknown/unpredictable


Question 9
----------

In the first line, why is there a set of empty brackets?

- [ ] The brackets indicate that `numbers_divisible_by_3_and_7` is comprised of ints.
- [ ] The brackets are a requirement of while-loops.
- [x] The brackets create an empty list.


Question 10
-----------

How many times does the while-loop run?

- [ ] 100
- [x] 2100
- [ ] 99
- [ ] 2099
- [ ] Unknown/unpredictable


Question 11
-----------

Why is `current_number += 1` not inside the if-statement? (warning: putting this line inside the if-statement will result in an infinite loop! Why?)

- [ ] The `+=` operator is syntactically part of the while-loop, so it cannot appear within the if-statement.
- [x] We want to increment `number_to_check` on every iteration of the while-loop, regardless of whether the if-statement's condition is met.
- [ ] Placing `current_number += 1` inside the if-statement is optional and a matter of personal preference.


Question 12
-----------

What happens if you change `and` to `or` in the if-statement? How does this change the resulting numbers?

- [x] The `or` condition is less restrictive than `and`, so we find 100 numbers more quickly.
- [ ] While-loops cannot be used with an `or`-based condition.
- [ ] Using `or` results in an infinite loop because it's possible for both conditions to be true at the same time.


Question 13
-----------

How would you modify the code to find numbers that are also divisible by five?

- [ ] `if number_to_check % 3 == 0 and % 7 == 0 and % 5 == 0:`
- [ ] `if number_to_check % 3 == 0 or number_to_check % 7 == 0 or number_to_check % 5 == 0:`
- [ ] `if number_to_check % 3 == 0 and number_to_check % 7 == 0 or number_to_check % 5 == 0:`
- [x] `if number_to_check % 3 == 0 and number_to_check % 7 == 0 and number_to_check % 5 == 0:`


Unit 2
======

Question 1
----------

Given that `numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`, what would the result of the following expression be: `max(numbers[0:5]) + min(numbers[5:10])`?

- [ ] 9
- [ ] 10
- [x] 11
- [ ] 12


Question 2
----------

What is the result of `sorted(['blue', 'red', 'green', 'yellow', 'black'])[-1]`?

- [ ] `['blue', 'black', 'green', 'red', 'yellow']`
- [ ] `['black', 'blue', 'green', 'red', 'yellow']`
- [ ] `['yellow', 'red', 'green', 'blue', 'black']`
- [x] `'yellow'`
- [ ] `'black'`


Question 3
----------

What is the result of the following: `colors = ['blue', 'red', 'green', 'yellow', 'black']; shuffle(colors); print(colors[0])`?

- [ ] `'blue'`
- [ ] `'red'`
- [ ] `'green'`
- [ ] `'yellow'`
- [ ] `'black'`
- [x] Unknown/unpredictable


Question 4
----------

Which of the following statements is incorrect?

- [ ] It is possible to write Python code without any functions.
- [x] Using a function makes your code run faster.
- [ ] Functions help organize code into discrete chunks.
- [ ] All functions have a return value.


Question 5
----------

Given the above function definition, what is the result of `raise_x_to_y(2, 2 * 8)`?

- [ ] 16
- [ ] 32
- [x] 65536


Question 6
----------

True or false? A function must take at least one argument.

- [ ] True
- [x] False 


Question 7
----------

True or false? A function will always return the same output if it is given the same input.

- [ ] True
- [x] False


Question 8
----------

What is the result of `colors = ['blue', 'red', 'green', 'yellow', 'black']; sorted_colors = colors.sort(); print(sorted_colors)`?

- [ ] `['black', 'blue', 'green', 'red', 'yellow']`
- [ ] `['blue', 'red', 'green', 'yellow', 'black']`
- [ ] `TypeError`
- [x] `None`


Question 9
----------

What is the result of `'hello world'.split(' ')[0]`?

- [x] `'hello'`
- [ ] `'h'`
- [ ] `['hello', 'world']`
- [ ] `['h', 'e', 'l', 'l', 'o', ' ', 'w', 'o', 'r', 'l', 'd']`


Question 10
-----------

Which of these statements is incorrect?

- [ ] A collection of related functions can be organized together in a class.
- [ ] Functions must be declared before they can be used.
- [x] The `sum()` function has to be imported from the `math` module before it can be used.
- [ ] A given function is allowed to call itself.


Horoscope exercise
------------------

Here's one way to determine someone's star sign based on their birthday.

```python
sign_dates = {
	"Aries": [[3, 21], [4, 19]],
	"Taurus": [[4, 20], [5, 20]],
	"Gemini": [[5, 21], [6, 20]],
	"Cancer": [[6, 21], [7, 22]],
	"Leo": [[7, 23], [8, 22]],
	"Virgo": [[8, 23], [9, 22]],
	"Libra": [[9, 23], [10, 22]],
	"Scorpio": [[10, 23], [11, 21]],
	"Sagittarius": [[11, 22], [12, 21]],
	"Capricorn": [[12, 22], [1, 19]],
	"Aquarius": [[1, 20], [2, 18]],
	"Pisces": [[2, 19], [3, 20]],
}

def determine_star_sign_from_birthday(target_month, target_date):
	determined_sign = None
	for sign, ((start_month, start_date), (end_month, end_date)) in sign_dates.items():
		if (target_month == start_month and target_date > start_date) or (target_month == end_month and target_date < end_date):
			determined_sign = sign
	return determined_sign

print( determine_star_sign_from_birthday(12, 16) ) # December 16 -> Sagittarius
```

Sum functions
-------------

Here's three ways to create a sum function.

```python
def sum1(nums):
    total = 0
    for num in nums:
        total += num
    return total

def sum2(nums):
    total = 0
    index = 0
    while index < len(nums):
        total += nums[index]
        index += 1
    return total

def sum3(nums, total=0):
    if len(nums) == 0:
        return total
    return sum3(nums[1:], total + nums[0])
```


Unit 3
======

Question 1
----------

Why do we open a file using a with-statement (context manager)?

- [ ] A with-statement is required for file system access.
- [x] When we exit the with-statement, the file is closed automatically.
- [ ] With statements allow us to iterate over the lines inside a file.


Question 2
----------

What kind of data is suitable for storing in a CSV file?

- [ ] Hierarchically nested data.
- [ ] Binary data, such as EEG recordings.
- [x] Any kind of data that can be arranged in a table.
- [ ] Any kind of data.


Question 3
----------

What kind of data is suitable for storing in a JSON file?

- [x] Hierarchically nested data.
- [ ] Binary data, such as EEG recordings.
- [ ] Any kind of data that can be arranged in a table.
- [ ] Any kind of data.


Question 4
----------

Given the example project organization I showed above, how would analysis.py access the experiment 2 data file?

- [ ] `'data/exp2/data.csv'`
- [ ] `'data/exp2_data.csv'`
- [ ] `'exp2/data.csv'`
- [ ] `Path('..') / 'data' / 'exp2_data.csv'`
- [ ] `Path('data') / 'exp2' / 'data.csv'`
- [x] `Path('..') / 'data' / 'exp2' / 'data.csv'`


Question 5
----------

What is the result of `[letter.upper() for letter in "hello"]`?

- [ ] `'HELLO'`
- [ ] `'Hello'`
- [x] `['H', 'E', 'L', 'L', 'O']`
- [ ] `['HELLO']`
- [ ] `None`


Question 6
----------

Which is these statements is false?

- [ ] In Python, variables can change type.
- [x] If a variable is annotated as an `int`, it is not allowed to be any other type.
- [ ] Python is a dynamically-typed language.
- [ ] Type hints are optional in Python.


Question 7
----------

In what situation would you use Python's try/except feature?

- [ ] To make sure that a chunk of code won't crash.
- [x] To take corrective action if a particular type of error occurs.
- [ ] To alert the user to a potential issue in the code.


ASCII art exercise
------------------

Here's one way to convert an image into ASCII art:

```python
from  PIL import Image

characters_ordered_by_darkness = r"@B%8&WM#oahkbdpqwmZO0QLCJUYXzcvunxrjft/()1{}[]?-+~<>i!lI;:,^`'. "

def convert_image_to_ascii(image_file: str, output_width: int) -> str:
    image = Image.open(image_file)
    grayscale_image = image.convert("L")
    aspect_ratio = grayscale_image.height / grayscale_image.width
    output_height = int(output_width * aspect_ratio * 0.5)
    resized_image = grayscale_image.resize((output_width, output_height))
    pixels = resized_image.getdata()
    output_string = ""
    for pixel_index, pixel in enumerate(pixels, 1):
        mapped_character_index = pixel // (256 // len(characters_ordered_by_darkness))
        mapped_character = characters_ordered_by_darkness[mapped_character_index]
        output_string += mapped_character
        if (pixel_index % output_width) == 0:
            output_string += "\n"
    return output_string

ascii_image = convert_image_to_ascii("dog.jpg", output_width=100)
print(ascii_image)
```


Unit 4
======

Question 1
----------

What is the result of `np.array([1, 2, 3]) ** 2`?

- [x] `array([1, 4, 9])`
- [ ] `array([2, 4, 6])`
- [ ] `6`
- [ ] `12`


Question 2
----------

What is the result of `np.ones(10) * np.zeros(10)`?

- [ ] `0`
- [ ] `100`
- [ ] `array([0, 0, 0, 0, 0, 0, 0, 0, 0, 0])`
- [x] `array([0., 0., 0., 0., 0., 0., 0., 0., 0., 0.])`


Question 3
----------

What is the result of `np.arange(10)[5:]`?

- [ ] `array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])`
- [ ] `array([5, 6, 7, 8, 9, 10])`
- [x] `array([5, 6, 7, 8, 9])`
- [ ] `array([6, 7, 8, 9])`


Question 4
----------

What is the result of `np.log2([2, 4, 8, 16, 32, 64])`?

- [ ] `array([2., 4., 8., 16., 32., 64.])`
- [ ] `array([2., 4., 6., 8., 10., 12.])`
- [x] `array([1., 2., 3., 4., 5., 6.])`


Question 5
----------

What is the correlation coefficient if we reverse the happiness-level data using `my_happiness_level_reversed = list(reversed([80, 50, 60, 55, 60, 99, 85]))`?

- [ ] 0.9315420132168272
- [ ] -0.9315420132168272
- [x] -0.2772306621931542
- [ ] Approximately 0.0


Question 6
----------

Which statement is correct?

- [ ] Kmeans clustering looks for correlations in a dataset to create clusters.
- [x] Kmeans clustering finds a set of clusters that minimize the average distance between cluster members.
- [ ] Kmeans clustering uses the mean value of a dataset to identify outliers.


Question 7
----------

Functions are usually followed by parentheses, so, in the code above, why do we write `minimize(good_icecream, 0.5)` rather than `minimize(good_icecream<strong><u>()</u></strong>, 0.5)`?

- [ ] We don't need to use parentheses because the `good_icecream` function does not have any inputs initially.
- [ ] `good_icecream` is being used as a string in this scenario.
- [x] This allows us to pass the `good_icecream` function into the `minimize` function, rather than the function's return value.


Question 8
----------

What was the mean accuracy of all the subjects who were in the "size" condition?

- [ ] 54%
- [x] 68%
- [ ] 72%
- [ ] 86%


Icecream exercise
-----------------

Here's one way to print out which flavors are good and which are bad based on the results of the cluster analysis.

```python
from scipy.cluster.vq import kmeans2
import numpy as np

def print_good_or_bad(flavors, centroids, clusters):
    index_of_bad_cluster = np.argmin(centroids)
    for flavor, cluster_index in zip(flavors, clusters):
        if cluster_index == index_of_bad_cluster:
            print(f'{flavor} is bad')
        else:
            print(f'{flavor} is good')

flavors = ['banana','bubblegum','butterscotch','cherry','chocolate','coffee','mango','mint','pistachio','raspberry','vanilla','watermelon']
centroids, clusters = kmeans2(icecream_rankings, 2)
print_good_or_bad(flavors, centroids, clusters)
```

Leap year exercise
------------------

Here's one way to account for leap years in the birthday-paradox simulation.

```python
def generate_birthdays(n_people):
    birthdays = []
    for _ in range(n_people):
        if np.random.random() < 0.25:
            # this person was born in a leap year
            # so there are 366 possible days
            birthdays.append( np.random.randint(1, 367) )
        else:
            # regular year: 365 possible days
            birthdays.append( np.random.randint(1, 366) )
    return birthdays
```

