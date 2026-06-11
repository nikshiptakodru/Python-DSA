# 📅 45-Day Campus Drive — Day-Wise Roadmap

> **Daily target: 2h coding + 30min theory**
> Click any phase to navigate. Every day has: Topics

-----

## 🐍 Phase 1 — Python Foundations (Days 1–14)

-----

### Day 1 — Python Setup & Basics

**Topics**

- Install Python, VS Code, setup environment
- Variables, print(), input()
- int, float, str — type casting
- Basic arithmetic operators (+, -, *, /, //, %, **)

-----

### Day 2 — Strings & String Methods

**Topics**

- String slicing: `s[start:stop:step]`
- Methods: upper, lower, strip, split, join, replace
- f-strings and string formatting
- String immutability concept

-----

### Day 3 — Lists & List Operations

**Topics**

- Create, access, modify lists
- append, insert, remove, pop, sort, reverse
- List slicing and copying
- Nested lists (2D arrays concept)

-----

### Day 4 — Tuples, Sets & Dictionaries

**Topics**

- Tuple: immutable list, unpacking, packing
- Set: add, remove, union, intersection, difference
- Dict: key-value, get(), items(), keys(), values()
- When to use which data structure

-----

### Day 5 — Conditionals & Loops

**Topics**

- if / elif / else logic chains
- for loop with range(), enumerate()
- while loop + break + continue
- Nested loops, loop else clause

-----

### Day 6 — Functions & Scope

**Topics**

- def, return, default args, keyword args
- *args and **kwargs
- Local vs global scope (LEGB rule)
- Docstrings and type hints overview

-----

### Day 7 — Lambda, Map, Filter, Reduce

**Topics**

- lambda: anonymous one-liner functions
- map(): apply function to all items
- filter(): keep items matching condition
- reduce() from functools — running aggregate

-----

### Day 8 — List & Dict Comprehensions

**Topics**

- `[expr for x in list if cond]` syntax
- Dict comprehensions `{k:v for ...}`
- Nested comprehensions
- Generator expressions (memory efficient)

-----

### Day 9 — OOP: Classes & Objects

**Topics**

- class, `__init__`, self keyword
- Instance vs class variables
- Methods: instance, class, static
- Object creation and attribute access

-----

### Day 10 — OOP: Inheritance & Magic Methods

**Topics**

- Single and multi-level inheritance
- super() call
- `__str__`, `__repr__`, `__len__`, `__eq__`
- Method overriding

-----

### Day 11 — File Handling

**Topics**

- open(), read(), write(), append modes
- with statement (context manager)
- readlines(), writelines()
- CSV reading with csv module

-----

### Day 12 — Exception Handling

**Topics**

- try / except / else / finally
- Catching specific exceptions (ValueError, TypeError)
- raise custom exceptions
- Exception hierarchy overview

-----

### Day 13 — Modules, itertools & collections

**Topics**

- import, from…import, as alias
- os, sys, math, random modules
- itertools: combinations, permutations, product
- collections: Counter, defaultdict, deque

-----

### Day 14 — Python Revision + Mock Test

**Topics**

- Revise all Week 1–2 concepts
- Solve mixed-difficulty problems
- Time yourself: 45 min for 5 problems
- Identify weak areas and re-read

-----

## ⚡ Phase 2 — DSA for Placement (Days 15–28)

-----

### Day 15 — Arrays: Basics & Two Pointers

**Topics**

- Array traversal, prefix sums
- Two-pointer technique (sorted arrays)
- Sliding window: max sum subarray of size k
- Kadane’s algorithm: max subarray sum

-----

### Day 16 — Arrays: Medium Patterns

**Topics**

- Dutch national flag (3-way partition)
- Rotate array left/right by k
- Find duplicate in array (Floyd’s cycle)
- Merge two sorted arrays in-place

-----

### Day 17 — Strings: Pattern Problems

**Topics**

- Reverse words in a string
- Check anagram using Counter
- Longest substring without repeating chars
- Valid parentheses (stack approach preview)

-----

### Day 18 — Hashing & HashMap

**Topics**

- Frequency map with Counter/dict
- Two Sum with hashmap O(n)
- Group anagrams by sorted key
- Subarray with given sum (prefix + hash)

-----

### Day 19 — Linked List

**Topics**

- Node class, create LL, traverse
- Reverse a linked list (iterative + recursive)
- Detect cycle — Floyd’s algorithm
- Merge two sorted linked lists

-----

### Day 20 — Stack & Queue

**Topics**

- Stack using list: push, pop, peek
- Queue using deque: enqueue, dequeue
- Balanced parentheses problem
- Next Greater Element using stack

-----

### Day 21 — Sorting Algorithms

**Topics**

- Bubble, Selection, Insertion sort (understand, not memorize)
- Merge sort: divide and conquer, O(n log n)
- Quick sort: pivot, partition, O(n log n) avg
- Python sort() vs sorted() — timsort

-----

### Day 22 — Binary Search

**Topics**

- Classic binary search (lo, hi, mid)
- Search in rotated sorted array
- Find first and last position of element
- Binary search on answer (monotonic problems)

-----

### Day 23 — Recursion Basics

**Topics**

- Recursion tree visualization
- Base case + recursive case pattern
- Factorial, Fibonacci, Power(x, n)
- Tower of Hanoi step-by-step

-----

### Day 24 — Backtracking

**Topics**

- Backtracking template: choose → explore → unchoose
- Generate all subsets of array
- Generate all permutations
- N-Queens problem (classic)

-----

### Day 25 — Trees: Basics & BFS/DFS

**Topics**

- Binary tree node, insert, traversals (inorder/preorder/postorder)
- BFS using queue (level order)
- DFS using stack/recursion
- Height, depth, diameter of tree

-----

### Day 26 — BST & Tree Problems

**Topics**

- BST: insert, search, delete
- Validate if tree is BST
- Lowest Common Ancestor (LCA)
- Inorder of BST = sorted array

-----

### Day 27 — Dynamic Programming Intro

**Topics**

- Memoization vs tabulation
- Fibonacci with DP (top-down + bottom-up)
- 0/1 Knapsack problem
- Longest Common Subsequence (LCS)

-----

### Day 28 — DSA Mock Test Day

**Topics**

- Timed 90-min mock test
- Mix: 1 easy + 2 medium + 1 hard attempt
- Review all wrong solutions with approach notes
- Document all patterns solved this week

-----

## 🗄️ Phase 3 — SQL Mastery (Days 29–35)

-----

### Day 29 — SQL Basics

**Topics**

- SELECT, FROM, WHERE, DISTINCT
- Comparison operators: =, !=, >, <, BETWEEN, IN, LIKE
- ORDER BY ASC/DESC, LIMIT, OFFSET
- NULL handling: IS NULL, IS NOT NULL, COALESCE

-----

### Day 30 — Aggregations & GROUP BY

**Topics**

- COUNT, SUM, AVG, MAX, MIN
- GROUP BY with aggregate functions
- HAVING vs WHERE (key difference)
- Counting NULLs vs non-NULLs

-----

### Day 31 — JOINs: All Types

**Topics**

- INNER JOIN: matching rows only
- LEFT JOIN: all left + matching right
- RIGHT JOIN & FULL OUTER JOIN
- Self JOIN: employee-manager pattern
- CROSS JOIN (cartesian product)

-----

### Day 32 — Subqueries & CTEs

**Topics**

- Subquery in WHERE, FROM, SELECT
- Correlated subquery (row-by-row)
- WITH clause (CTE) for readability
- EXISTS vs IN performance difference

-----

### Day 33 — Window Functions

**Topics**

- ROW_NUMBER(), RANK(), DENSE_RANK()
- PARTITION BY … ORDER BY …
- LEAD() and LAG() for prev/next row
- SUM() OVER() running total

-----

### Day 34 — String & Date Functions

**Topics**

- UPPER, LOWER, TRIM, LENGTH, SUBSTRING
- CONCAT, REPLACE, INSTR
- DATE functions: NOW(), YEAR(), MONTH(), DATEDIFF()
- CASE WHEN … THEN … ELSE … END

-----

### Day 35 — SQL Mock Test + Hard Queries

**Topics**

- Recursive CTEs overview
- Query optimization: EXPLAIN, indexes
- Write 3 complex multi-join queries from scratch
- Timed: 10 SQL questions in 45 minutes

-----

## 📊 Phase 4 — Pandas & NumPy (Days 36–42)

-----

### Day 36 — NumPy Basics

**Topics**

- np.array(), ndarray, dtype
- Array creation: zeros, ones, arange, linspace
- Shape, reshape, flatten, transpose
- Indexing, slicing, boolean masking

-----

### Day 37 — NumPy Operations

**Topics**

- Broadcasting rules (shapes must align)
- Vectorized arithmetic (no loops needed)
- Statistical: mean, median, std, var, percentile
- np.where(), np.unique(), np.sort()

-----

### Day 38 — Pandas: Series & DataFrame

**Topics**

- pd.read_csv(), head(), tail(), info(), describe()
- Series vs DataFrame structure
- Selecting columns: df[‘col’] vs df[[‘col1’,‘col2’]]
- iloc[] and loc[] indexing

-----

### Day 39 — Pandas: Data Cleaning

**Topics**

- Handle missing: dropna(), fillna(), isnull()
- Remove duplicates: drop_duplicates()
- Rename columns, change dtypes, apply()
- String operations: str.lower(), str.contains()

-----

### Day 40 — Pandas: GroupBy & Aggregation

**Topics**

- groupby(‘col’).agg({‘col2’: ‘mean’})
- pivot_table() — the Excel pivot equivalent
- crosstab() for frequency tables
- transform() vs apply() difference

-----

### Day 41 — Pandas: Merge, Join & Concat

**Topics**

- pd.merge(df1, df2, on=‘key’, how=‘left’)
- pd.concat([df1, df2], axis=0/1)
- Join on index vs column
- Handling duplicate columns after merge

-----

### Day 42 — EDA Mini Project

**Topics**

- Pick dataset: IPL / Netflix / Covid / Zomato
- Data loading → cleaning → exploration
- 5 visualizations: bar, line, scatter, heatmap, boxplot
- Write 5 business insights in markdown cells

-----

## 🚀 Phase 5 — FastAPI & Django Basics (Days 43–45)

-----

### Day 43 — API Concepts + FastAPI Setup

**Topics**

- What is REST API? HTTP methods explained (GET/POST/PUT/DELETE)
- Request/Response cycle, status codes (200/201/400/404/500)
- Install FastAPI + uvicorn, first endpoint
- Path params, query params, request body

-----

### Day 44 — FastAPI Deep Dive + Pydantic

**Topics**

- Pydantic BaseModel for request validation
- POST endpoint to create resource
- In-memory CRUD: GET / POST / PUT / DELETE
- Auto-generated Swagger docs at /docs

-----

### Day 45 — Django Overview + Deploy

**Topics**

- Django project structure: settings, urls, views, models
- MTV pattern vs MVC explained
- Django ORM: Model class, makemigrations, migrate
- Deploy FastAPI app to Render (free tier)

-----

## 🤖 Optional Bonus — AI / ML / LLM Track (B1–B5)

*Run parallel to Phase 4–5 or after Day 45*

-----

### Day B1 — ML Fundamentals

**Topics**

- Supervised vs unsupervised learning
- Train/test split, overfitting, underfitting
- Evaluation: accuracy, precision, recall, F1
- Scikit-learn pipeline overview

-----

### Day B2 — Scikit-learn Models

**Topics**

- LinearRegression, LogisticRegression
- DecisionTreeClassifier, RandomForestClassifier
- KMeans clustering
- Feature engineering: scaling, encoding

-----

### Day B3 — LLM & Prompting Concepts

**Topics**

- What are LLMs? Tokens, context window explained
- Zero-shot, few-shot, chain-of-thought prompting
- OpenAI / Anthropic API basics
- Prompt engineering best practices

-----

### Day B4 — LangChain / RAG Basics

**Topics**

- LangChain: chains, prompts, LLMs, memory
- Retrieval Augmented Generation (RAG) concept
- Vector stores: FAISS, ChromaDB overview
- Build a simple Q&A over a document

-----

### Day B5 — Build & Deploy AI Project

**Topics**

- Pick one: Resume Screener / PDF Chatbot / Code Reviewer
- Integrate LLM API + FastAPI backend
- Add simple Streamlit or HTML frontend
- Write README, push to GitHub, deploy

-----

## 🎯 Non-Negotiables (Every Day)

|#|Rule                                                                     |
|-|-------------------------------------------------------------------------|
|⏱️|Minimum **2h coding + 30min theory** daily                               |
|📝|Maintain a **DSA pattern sheet** — note approach for every solved problem|
|🧑‍💻|Push to **GitHub daily** — even small progress counts                    |
|🎯|Start **mock interviews from Day 28** — Pramp / Interviewing.io          |
|📄|Build your **1-page ATS resume** in parallel from Day 14                 |
|💼|Update **LinkedIn** weekly with projects and learning                    |

-----