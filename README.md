## EX-10 Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Data Science Software Products - Company Name</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
    }
    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
    }
    header {
        background-color: #333;
        color: #fff;
        padding: 10px 20px;
        text-align: center;
    }
    h1, h2 {
        margin: 20px 0;
    }
    .product {
        background-color: #fff;
        padding: 20px;
        margin-bottom: 20px;
        border-radius: 5px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    .product img {
        max-width: 100%;
        height: auto;
        border-radius: 5px;
    }
    .product-details {
        margin-top: 20px;
    }
    .product-details p {
        margin-bottom: 10px;
    }
    .btn {
        display: inline-block;
        padding: 10px 20px;
        background-color: #007bff;
        color: #fff;
        text-decoration: none;
        border-radius: 5px;
    }
    .btn:hover {
        background-color: #0056b3;
    }
    footer{
    background-color: hsla(240, 87%, 32%, 0.616);
    color: papayawhip;
    text-align: center;
    padding: 20px 0;
    position: fixed;
    bottom: 0%;
    width: 100%;
}
</style>
</head>
<body>

<header>
    <h1>Data Science Software Products</h1>
</header>

<div class="container">
    <div class="product">
        <h2>REDaxis</h2>
        <img src="Products-1.png" alt="Product 1">
        <div class="product-details">
            <p>Description: A Design Thinking approach to problem-solving and identification of the most lucrative business opportunities. Powered by Fosfor , solutions developed for ERP customers, specializing in streamlined data sourcing and simplification of data development.</p>
            <p>Features:</p>
            <ul>
                <li>Context / Role-based Analytics Insights through Dashboards/Reports.</li>
                <li>Enhanced User Experience through advanced visualizations and Mobile BI.</li>
                <li>Executive Insights highlighting priorities among the Business As Usuals.</li>
            </ul>
            <a href="#" class="btn">Learn More</a>
        </div>
    </div>

    <div class="product">
        <h2>Unitrax</h2>
        <img src="Products-2.png" alt="Product 2">
        <img src="Products-3.png" alt="">
        <div class="product-details">
            <p>Description: Single version system auto-switching and household assettiering capabilities. Built-in, robust indexing capabilities, to extract records for a user-defined date, promptly upon request.</p>
            <p>Features:</p>
            <ul>
                <li>Built for 360o administration of insurance wealth products.</li>
                <li>Streamlines administration of a wide range of investment vehicles.</li>
                <li>Supports all Canadian registration types (e.g. RDSP, RESP, TFSA, RRIF, LIF, RRSP, IPP).</li>
            </ul>
            <a href="#" class="btn">Learn More</a>
        </div>
    </div>
</div>
<footer>
    <p>&copy;2024 SWETHA S All rights reserved</p>
  </footer>

</body>
</html>
```
## OUTPUT:

![image](https://github.com/Isreal129/Pharma/assets/125784931/42216e9e-5a02-4980-8a0d-4a5d756c7212)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
