# Ecommerce Sales Reporting

<p align="center">
  <!-- Replace 'image_url' with the actual URL of your image -->
  <img src="pic1.jpeg" alt="Ecommerce-Picture">
</p>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/dsrichard97/Ecommerce" alt="Last Commit">
  <img src="https://img.shields.io/badge/Financial_Analysis-Trends-red" alt="Financial Analysis">
  <img src="https://img.shields.io/badge/STAT-Time_Series-blue" alt="Time Series">
  <img src="https://img.shields.io/badge/Excel-green" alt="Excel">
  <img src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103" alt="Open Source">
  </a>
</p>



## Table of Contents
- [Focus](#focus)
- [Business Problem](#bussines)
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Reports](#report)

## Focus 
To showcase excel skill and financial skills in relationship to business data using visualizations to export meaningful results.

## Business Problem
A US Based Ecommerce Sales Company wants to create a Sales Dashbpoard Showing information of YTD Sales and generate rich insights using excel and data provided below.


## Introduction
ECommerce, or Electronic Commerce, refers to the buying and selling of goods or services using the internet, and the transfer of money and data to execute these transactions. It has transformed the traditional retail landscape, enabling businesses to reach a global audience with minimal physical presence. eCommerce is not just limited to online shopping; it encompasses a wide range of activities including online auctions, payment gateways, online ticketing, and internet banking.

The growth of eCommerce has been propelled by the advancement in technology, particularly mobile computing and online payment systems, making it more accessible and convenient for consumers worldwide. It allows for a more personalized shopping experience through data analytics, targeted marketing, and customer service chatbots.


## Data Source

![EcommerceData](https://github.com/dsrichard97/Ecommerce/blob/main/vidgif.gif)

### eCommerce Transactions Data Dictionary
| Field Name    | Data Type | Description                                           |
|---------------|-----------|-------------------------------------------------------|
| TransactionID | Integer   | Unique identifier for each transaction.               |
| Date          | Date      | The date when the transaction occurred.               |
| ProductID     | Integer   | Identifier for the product being purchased.           |
| Quantity      | Integer   | The number of products purchased in the transaction.  |
| UnitPrice     | Float     | Price of one unit of the product.                     |
| CustomerID    | Integer   | Unique identifier for the customer.                   |
| PaymentType   | String    | Method of payment (e.g., Credit Card, PayPal).        |
| Country       | String    | The country where the transaction took place.         |

This dataset captures detailed information about individual transactions in an eCommerce setting, including the product details, quantity purchased, pricing, customer information, and geographical data. It's designed to help analyze sales performance, customer buying patterns, and product popularity, which are crucial for making informed business decisions in the retail domain.



## Report
<div class='tableauPlaceholder' id='viz1708121665262' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sa&#47;SalesDashboard_17081176398890&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SalesDashboard_17081176398890&#47;Dashboard1' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sa&#47;SalesDashboard_17081176398890&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1708121665262');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='1000px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='850px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='1000px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='850px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.minHeight='1550px';vizElement.style.maxHeight=(divElement.offsetWidth*1.77)+'px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


