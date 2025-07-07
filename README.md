# Product Table
### NAME : Harish Ragav S  Date: 7/7/25 
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
```
<!DOCTYPE html>
<html>
<head>
    <title>Product Table</title>
</head>
<body>

    <h1>Product Listing</h1>

    <table border="1">
        <caption>Available Products and Their Details</caption>

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
                <td>Phone</td>
                <td>$499</td>
                <td>Budget-friendly smartphone</td>
            </tr>
            <tr>
                <td>Tablet</td>
                <td>₹25,000</td>
                <td>Portable and efficient for media</td>
            </tr>
            <tr>
                <td>Headphones</td>
                <td>$79</td>
                <td>Noise-cancelling and wireless</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
```

## Output:
![image](https://github.com/user-attachments/assets/ef23fdb4-c1c2-43dc-a826-1749a39a6b4d)

## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
