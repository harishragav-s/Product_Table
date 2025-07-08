# Product Table
### NAME : Harish Ragav S  Date: 8/7/25 
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
index.html 
```
<!DOCTYPE html>
<html>
<head>
    <title>Product Table</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1 style="text-align: center;">Product Table</h1>

    <table>
        <caption>Available Products</caption>
        <thead>
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Laptop</td>
                <td>₹45,000</td>
                <td>High-speed performance</td>
            </tr>
            <tr>
                <td>Smartphone</td>
                <td>₹20,000</td>
                <td>Budget-friendly Android phone</td>
            </tr>
            <tr>
                <td>Headphones</td>
                <td>₹2,500</td>
                <td>Noise-cancelling over-ear headphones</td>
            </tr>
            <tr>
                <td>Smartwatch</td>
                <td>₹3,999</td>
                <td>Fitness tracker with heart rate monitor</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
```
style.css 
```
body {
    background-color: #f9f9f9;
    font-family: Arial, sans-serif;
}

table {
    width: 80%;
    margin: auto;
    border-collapse: collapse;
}

caption {
    font-weight: bold;
    margin-bottom: 15px;
    font-size: 18px;
}

thead th {
    background-color: #4CAF50;
    color: white;
    padding: 10px;
    text-align: left;
}

td {
    border: 1px solid #ddd;
    padding: 10px;
}

tbody tr:nth-child(even) {
    background-color: #f2f2f2;
}

tbody tr:hover {
    background-color: #e9f5e9;
}
```

## Output:
![image](https://github.com/user-attachments/assets/de6b211a-2052-4b77-93f2-bc073753b625)

## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
