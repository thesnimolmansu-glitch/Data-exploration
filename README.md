# Data exploration
Excel Assignment 1 - Data Exploration
## Step 1: Explore the Dataset
First, I looked at the dataset and identified the main columns, such as:

- Quantity
- Category
- Price
- Price Range
- Product ID

I checked the data to understand what type of information was available
before performing calculations.

## Step 2: Calculate the Total Price of the Dataset
I calculated the total price of all products using the SUM function.

Formula:
=SUM(Price_Range)

## Step 3: Count the Total Number of Products
I used the COUNT function to find how many products are in the dataset.

Formula:
=COUNT(Price_Range)


## Step 4: Calculate the Average Price
I used the AVERAGE function to calculate the average price of the products.

Formula:
=AVERAGE(Price_Range)

## Step 5: Find the Minimum Price
I used the MIN function to find the lowest price in the dataset.

Formula:
=MIN(Price_Range)

## Step 6: Find the Maximum Price
I used the MAX function to find the highest price in the dataset.

Formula:
=MAX(Price_Range)

## Step 7: Use SUMIF
I used the SUMIF function to calculate the total of a selected
group based on a condition.

Formula structure:
=SUMIF(criteria_range, criteria, sum_range)

Example:
=SUMIF(Category_Range,"Electronics",Price_Range)

## Step 8: Use COUNTIF
I used COUNTIF to count how many records meet a specific condition.

Formula structure:
=COUNTIF(criteria_range, criteria)

Example:
=COUNTIF(Category_Range,"Electronics")

## Step 9: Extract Characters Using LEFT
I used the LEFT function to extract characters from the beginning
of the Product ID.

Formula:
=LEFT(Product_ID,2)

## Step 10: Extract Characters Using MID
I used the MID function to extract characters from the middle
of a Product ID.

Formula structure:
=MID(text, start_num, num_chars)

## Step 11: Separate the Product ID
I used text functions such as LEFT and MID to break the Product ID
into separate parts.

This helped me create separate columns for different parts of the
Product ID, such as:

- Product ID Left
- Product ID Mid
- Product ID / Country Code

This makes the data easier to analyze and understand.

---

## Step 12: Check the Results
After applying the formulas, I checked the results against the
original dataset to make sure the calculations were correct.

## Functions Practiced

The main Excel functions used in this assignment were:

1. SUM       → Calculate a total
2. COUNT     → Count numeric values
3. AVERAGE   → Calculate an average
4. MIN       → Find the smallest value
5. MAX       → Find the largest value
6. SUMIF     → Add values based on a condition
7. COUNTIF   → Count values based on a condition
8. LEFT      → Extract characters from the left
9. MID       → Extract characters from the middle


In this assignment, I learned how to:

- Explore a dataset
- Calculate basic statistics in Excel
- Use SUM, COUNT and AVERAGE
- Find minimum and maximum values
- Use SUMIF and COUNTIF with conditions
- Extract parts of text using LEFT and MID
- Organize data into separate columns
- Check whether Excel calculations are correct

