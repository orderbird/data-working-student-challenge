# data-working-student-challenge

## Introduction

Welcome. This tech challenge will give you an idea on how your work at Orderbird could look like. For that your main tools will be Python and SQL.

To start with this tech challenge, please copy this repository and create a Jupyter Notebook with your solution, locally. The timeline for this challenge ends today in one week. Please send us before the timeline ends your local version of this repository (EMAIL). And please do not create a pull request or fork this repository as your solution should not end up being public afterwards.

## The Data

You will find two datasets in this repository. The first one "items" shows menu card items, which where sold by our customers. Each item is separated into item_name and category. The category can bundle multiple item_names to one topic of a customers choice (e.g. the item names cola, fanta, sprite bundled to softdrinks). Each item has also a price (price of a single item) and an item_count, which is the quantity of sold items of one combination of item_name and category.

The other dataset "tags" has like the previous dataset item_name and category. And also a column tags, where some logic got applied to classify items. The values of this column are in form of a [set](https://docs.python.org/3/tutorial/datastructures.html#sets), which means each item_name and category in combination can have multiple tags.

## Tasks

The following tasks should be solved with Python. Only if it's mentioned to solve in SQL, SQL should be used. The main library to use is Pandas and for SQL [pandasql](https://pypi.org/project/pandasql/). But you will need other libraries too. If you are deciding to use alternative libraries as the two mentioned above, please explain your decision.

In general it's advisable to use a Data Scientist workflow. Generally speaking it consists of getting insights into the data you are working with, cleaning/preprocessing the data (e.g. removing duplicates, ...) and doing some analysis. And repeating the last two steps until the outcome is as you desire.

### Task 1

Load the data and get an overview about the datasets. Please describe what you see.

### Task 2

How many Jägermeister items were sold? (Hint: Regular expressions could be useful)

### Task 3

Calculate the total price of each tag and also the total price overall. And sort your result in descending order. (Hint: You are working with a set of tags. https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.explode.html)

Please explain which join you will use and why. And also explain why the size of your dataframe has changed or not.

#### Task 3.1

Solved with Python.

#### Task 3.2

Solved with SQL (pandasql).

### Task 4

What are the top 3 sold items based on quantity per tag?

#### Task 4.1

Solved with Python.

#### Task 4.2

Solved with SQL (pandasql).

---

Please do not create a pull request or fork this repository as your solution should not end up being public afterwards. If you have questions, please reach out to us (EMAIL).

Good luck and happy coding!
