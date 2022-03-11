# data-working-student-challenge

## Introduction

Welcome. This tech challenge will give you an idea on how your work at orderbird could look like. If you choose to accept the challenge then please submit your solution within one week from now on. If life prevents you from submitting it on time then please let us know (data-tech-challenge@orderbird.com).

To start with this tech challenge, please copy this repository and locally add a Jupyter Notebook with your solution. Please *do not* create a pull request or fork this repository as your solution should not end up being public afterwards. 

## The Data

You are given two datasets in this repository. The first one "items" contains menu card items which were sold by our customers. Each item is separated into item_name and category. The category can bundle multiple item_names to one topic of a customer's choice (e.g. the item names cola, fanta, sprite bundled to softdrinks). Each item has also a price (price of a single item) and an item_count, which is the quantity of sold items of one combination of item_name and category.

The other dataset "tags" provides item_name and category enriched with labels (tags) which resulted from a classification task applied on the item. The tags are given as a [set](https://docs.python.org/3/tutorial/datastructures.html#sets). Please notice that an item (i.e. item_name and its category) can have multiple tags or no tags (empty set).

## Tasks

The following tasks should be solved with Python and/or SQL (applied on a DataFrame). We recommend to use Pandas and [pandasql](https://pypi.org/project/pandasql/). If you decide to use alternative libraries as the two mentioned above, please explain your decision.

We recommend to follow a "Data Scientific workflow" which starts with loading the data, followed by a cleansing/preprocessing step (e.g. removing duplicates, ...) and ends with doing some awesome analysis.

### Task 1

Load the data and get an overview about the datasets by answering the following questions
1. How many different items, i.e. combinations of (item_name, category), do you see?
2. How many different categories do you see?
3. How many different tags do you see? (Hint: You are working with a set of tags. Hence, "explode" is your friend :-) )

**Show that for each item, i.e. (item_name, category), there exists a (maybe empty) set of tags.**

### Task 2

How many Jägermeister items were sold? (Hint: Regular expressions could be useful)

### Task 3

Calculate the total turnover, i.e. #items times the price, of each tag and sort your result in descending order. 

You can decide if you want to solve this task with Pandas, SQL or even both variants.

### Task 4

What are the top 3 sold items based on quantity per tag?

You can decide if you want to solve this task with Pandas, SQL or even both variants.

## And now what?

Please send us a zipped file containing your local copy of this git-repository with your solution notebook.
Please *do not* create a pull request or fork this repository as your solution should not end up being public afterwards. If you have questions, please reach out to us (data-tech-challenge@orderbird.com).

Good luck and happy coding!
