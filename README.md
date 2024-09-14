# 🛒 Exploratory Data Analysis on Retail Sales Data

I have used a dataset from Kaggle (public domain) related to the Retail Sales Data collected from 10 different shopping malls in Istanbul, Turkey.
![image](https://github.com/user-attachments/assets/06136fa9-8b72-44a1-93d5-1b0d1b0cc888)


### 📁 Link to the dataset:
[Kaggle - Customer Shopping Dataset](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset)

### 📊 Columns in the dataset:
- `invoice_no`: Invoice number
- `customer_id`
- `gender`: Either male or female
- `age`
- `category`: Such as clothing, shoes, cosmetics, et cetera
- `quantity`
- `price`: This is the price per unit item
- `payment method`: Either cash, debit card, or credit card
- `shopping_mall`: Name of the mall

---

## 🏗️ Project Structure:
1. **Data Loading and Cleaning**
2. **Feature Engineering**
3. **Descriptive Statistics**
4. **Data Visualization**
5. **Data Analysis**
6. **Recommendations**

---

### 1️⃣ Data Loading and Cleaning
This step involved:
- Loading the dataset into a Pandas dataframe
- Handling missing values
- Removing duplicates
- Correcting data types
- Formatting the dates

### 2️⃣ Feature Engineering
This step involved creating columns based on:
- Categorization of malls (Luxury mall, mega mall, mixed-use mall, and outlet mall)
- Location of mall (whether located on the European side or the Asian side of Istanbul)
- Total price of items
- Categorization of ages into different groups (baby, young adult, middle-aged adult, and old adult)
- Total price of items purchased by each gender
- Total price of items purchased by each age group
- Total price of items purchased in each category
- Total price of items purchased through each payment method
- Total price of items purchased in each shopping mall
- Total price of items purchased in each mall location
- Total price of items purchased in each type of mall
- Unit price of items purchased by each gender
- Total quantity of items purchased by each gender
- Total quantity of items purchased from each category
- Total quantity of items purchased through each payment method
- Total quantity of items purchased in each shopping mall
- Total quantity of items purchased in each type of mall
- Total quantity of items purchased in each mall location
- Total quantity of items purchased by each age group

### 3️⃣ Descriptive Statistics
This step involved getting KPIs from the crucial columns using measures of central tendency. Here are a few important insights derived from this step:
- The average age of a person shopping in the malls is 43 years.
- On average, a customer buys about 3 items of any type from the shopping mall.
- On average, a person spends 689.26 Turkish Liras per item in a shopping mall.
- The number of purchases made by females is higher than those of males.
- The payment method for most invoices is cash.
- The majority of the invoices come from malls located on the European side of Istanbul.

### 4️⃣ Data Visualization
In this step, I utilized various types of graphs such as bar charts and pie charts using **matplotlib** and **seaborn** libraries to explore and understand the data.

A few pivotal graphs created at this stage were:
- Comparison of Payment Methods
- Total Amount Spent
- Purchase Trends in Each Month

### 5️⃣ Data Analysis
From the graphs and descriptive statistics, I made the following inferences:
- Customers aged 37 years have the most invoices in shopping malls.
- On average, a customer buys about 3 items of any type from the shopping mall.
- On average, a person spends 689.26 Turkish Liras per item in a shopping mall.
- The maximum number of invoices are from the Mall of Istanbul.
- More invoices are issued to females, who spend more and purchase a higher quantity of items than males.
- Both male and female customers frequently visit luxury and mega malls, as well as malls located in the European part of Istanbul.
- Young adults (aged 3 to 39 years) have more invoices compared to middle-aged and old adults, hence the total price and quantity of items purchased is higher.
- Clothing emerges as the most popular category among all the invoices, followed by cosmetics and food/beverages.
- Clothing and shoes, followed by technology items, have the highest total price.
- Price per item is the highest for technology, followed by shoes and clothing.
- Customers spend more in the month of October, with a sharp decrease in November and a slight increase in December. Males shop the most in September, while female customers shop more in July and October.
- Most payments are made in cash, followed by credit card.
- More invoices are issued by Kanyon and Mall of Istanbul than other malls.
- Invoices are dominated by purchases from mega malls.
- Most invoices are from malls located in the European part of Istanbul.

### 6️⃣ Recommendations
Here are my top recommendations based on the insights gathered:
- Malls should locate themselves in the European part of Istanbul and upgrade their infrastructure to become luxury or mega malls.
- Malls should focus more on their young adult (aged 3 to 39 years) customers.
- Malls should also focus more on their female customers, as the number of invoices, total price, and quantity of items purchased by females is higher than that of males.
- Malls should prepare adequately for the month of October, as it has the highest sales volume.
- Malls should ensure that customers can easily pay using cash.
- Malls should focus more on selling clothing items to customers.

---


