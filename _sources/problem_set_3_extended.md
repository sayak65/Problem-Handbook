# Problem Set 3 | Extended

---

+++

 <p style="background-color: #a29bfe; padding: 3px 5px; border: 1px solid #ccc; border-radius: 10px; display: inline-block; width: auto; font-size: 10px;">Sayak</p>

+++

### 1. Counting Point Mutation

---

[Adapted From Rosalind](https://rosalind.info/problems/hamm/)

Given two DNA sequences of equal length, count the total number of point mutations within the sequences.


```{card} Test Input
GAGCCTACTAACGGGAT <br>
CATCGTAATGACGGCCT
```

```{card} Test Output
7
```

+++

### 2. Farmer Sayak's Fibonacci Fowls

---

Farmer Sayak has a unique breed of chickens that follow a peculiar and well-known mathematical pattern in their population growth - the [Fibonacci sequence](https://en.wikipedia.org/wiki/Fibonacci_sequence). Each month, the number of chickens on his farm increases following this sequence, and Farmer Sayak needs your help to predict the population of his chickens in the coming months.

Write a program that calculates the number of chickens in Farmer Sayak's farm after a certain number of months, following the Fibonacci sequence. The initial population of the farm is the first two numbers in the sequence.

```{card} Input
- `first_month_population`: An integer representing the number of chickens in the first month.
- `second_month_population`: An integer representing the number of chickens in the second month.
- `months`: An integer representing the number of months after which Farmer Sayak wants to know the population of his chickens.
```

```{card} Output
An integer representing the number of chickens on Farmer Sayak's farm after the given number of months.
```


```{card} Sample Input and Output
- Example 1:
    - Input: `first_month_population = 1, second_month_population = 1, months = 5`
    - Output: `8`
- Example 2:
    - Input: `first_month_population = 1, second_month_population = 2, months = 6`
    - Output: `21`
- Example 3:
    - Input: `first_month_population = 2, second_month_population = 3, months = 4`
    - Output: `19`
```

+++

### 3. The Mysterious Alien Message

---

In the year 2040, a team of space explorers on Mars discovers a strange, coded message etched into the rocks of a Martian cave. The symbols are strangely reminiscent of Earth's DNA nucleotides - Adenine (A), Cytosine (C), Guanine (G), and Thymine (T). The team believes that deciphering the frequency of these symbols could be the key to unlocking the message's meaning.
You are the lead programmer on the Mars mission, tasked with analyzing this mysterious message. The team has transcribed the symbols into a string format resembling a DNA sequence. Your mission is to create a program that will analyze this string and display the frequency of each symbol in a bar chart format on the command line. This will help the team to visually interpret the pattern and possibly understand the message's origin and meaning.

Write a program that takes a string representing the Martian message and counts the number of occurrences of each symbol - 'A', 'C', 'G', and 'T'. Then, display these counts in a bar chart format on the command line, in the order of A, C, G, T.

```{card} Input
`dna_string`: A string representing the transcribed Martian message, composed only of characters 'A', 'C', 'G', and 'T'.
```

```{card} Output
A command line bar chart representing the count of each symbol in the given order: A, C, G, T.
```

```{card} Constrain
The `dna_string` is composed only of uppercase letters 'A', 'C', 'G', and 'T'.
```

```{card} Sample Input and Output

- Input: `dna_string = "ATGCCGTAAAGGCCCC"
- Output: <br>
4 6 4 2 <br>
<br>
`=========` <br>
`A-|****  ` <br>
`C-|******` <br>
`G-|****  ` <br>
`T-|**    ` <br>
`=========` <br>
```

+++