# CS101 Spring 2026 — Practice Midterm Reflection

Name: Kallan Fuchs 
Date: 3/18/2026

After completing the practice test, please reflect on your experience by
answering the questions below. Replace each `TO-DO` with a thoughtful response
(a few sentences each). Your responses help you consolidate what you learned
and identify areas to review before the real midterm.

---

## 1. Self-Assessment

**Question:** How did you feel about your performance on the practice test?
Which topics felt most comfortable, and which ones felt most difficult?

**Your Answer:**

I feel very good although I want to look over adding list together and the algorithmic methods as I was confused on thoes two questions.

---

## 2. Tricky Questions

**Question:** Identify one question you got wrong (or were unsure about).
Explain the concept being tested and describe why the correct answer is right.

**Your Answer:**

I got only number 8 incorrect due to mixing up the .values() command so I answered d while c was the correct answer. 

---

## 3. Loops and Iteration

**Question:** In your own words, explain the difference between `range(a, b, step)`
with a positive step versus a negative step. Give one original example of each.

**Your Answer:**

range with a positive step would go from a up to b awhile a negitive step would start at a and go down until reaching b and example would be range(1,5) to go from 1-4 with a positve step and range(5,1,-1) to go from 5-2 with a negative step. 

---

## 4. Data Structures

**Question:** Python has lists, tuples, dictionaries, and sets. Describe one key
difference between a list and a tuple, and one key difference between a
dictionary and a set. When would you choose each?

**Your Answer:**

A list stores data in a changable list of values while a touple stores items in one variable that is not changable. A dictioary stores a key and a value which can be called upon using that key while a set is an unorginized grouping of unique items.

---

## 5. Functions

**Question:** What is a default parameter in a Python function? Write a short
example function that uses a default parameter, and explain what happens when
the caller omits that argument.

**Your Answer:**

A default parameter is a parameter that has a default value but can be overridden. An eample is def add(x = 5):
5 is the default value but if called as add(6) x would be changed to 6. 

---

## 6. List Comprehensions

**Question:** List comprehensions can include an optional filter condition.
Rewrite the following traditional loop as a list comprehension:

```python
result = []
for n in range(1, 11):
    if n % 3 == 0:
        result.append(n * 2)
```

**Your Answer:**

result = [n for n in range(1,11) if n % 3 == 0]

---

## 7. Operator Precedence

**Question:** Python evaluates `**` (exponentiation) right-to-left.
What is the value of `2 ** 2 ** 3`? Show your step-by-step reasoning.

**Your Answer:**

This would start as 2 ** 3 which equals 8 then python would consider 2 ** 8 wich is 256. 

---

## 8. Classes 

**Question:** What are classes in Python programming? Explain why they are necessary in programming.

**Your Answer:**

Classes are a gorup of functions all using the same variables which are nessesary to call repeatativ functions for seperat values such as students where each would have a name and grade and use there own set of the repeating functions. 

---

(Did you remember to add your name and date at the top of this document?)
