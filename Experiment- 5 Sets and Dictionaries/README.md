
# Experiment 5: Sets and Dictionaries in Python

**Name:** Drishti Heda

**PRN:** 25070123045

**Batch:** EnTC A-3


## Title

To study Sets and Dictionaries in Python.

## Aim

To understand the fundamental properties of Python's built-in data structures (Sets and Dictionaries) and apply them to solve practical problems involving uniqueness and key-value mapping.

## Objective

* To explore the creation and properties of **Sets**, including their unordered nature and handling of duplicate values.
* To implement core set operations such as **Union, Intersection, Difference, and Symmetric Difference**.
* To understand the concept of **Frozensets** as immutable versions of sets.
* To learn the structure of **Dictionaries** and perform operations like adding, updating, searching, and removing key-value pairs.
* To apply these concepts to real-world scenarios like event registration, student databases, and login validation.

---

## Theory

### 1. Python Sets

A set is an unordered collection of items where every element is unique. Sets are written with curly brackets `{}`.

* **Duplicates Not Allowed:** Sets automatically filter out duplicate entries.
* **Value Consistency:** The values `True` and `1` are considered the same value in sets and are treated as duplicates.
* **Set Operations:**
* **Union (`|`):** Combines elements from both sets.
* **Intersection (`&`):** Returns only elements present in both sets.
* **Difference (`-`):** Returns elements present in the first set but not the second.
* **Symmetric Difference (`^`):** Returns elements present in either set, but not both.



### 2. Python Frozensets

A `frozenset` is an immutable version of a Python set object. While elements of a standard set can be modified, adding or removing elements is not allowed in a `frozenset`.

### 3. Python Dictionaries

Dictionaries are used to store data values in **key:value** pairs. They do not allow duplicate keys; if a duplicate key is provided, the dictionary takes the latest value given for that key.

* **Functionality:** Includes methods like `.get()` for searching, `.pop()` for removing elements, and `.values()` to view the dictionary contents.
* **Changeable:** Once a dictionary is created, you can change, add, or remove items.

---

## Conclusion

Through this experiment, I learned how to utilize **Sets** for maintaining unique data and performing mathematical set operations, which is essential for data filtering. I also gained proficiency in using **Dictionaries** to organize data into logical mappings. The practical problem statements, such as identifying unique event participants, tracking absent students, and validating user logins, demonstrated how these structures optimize data management tasks in Python.
