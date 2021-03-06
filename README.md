# simple-product-api-php
### FILE STRUCTURE
At the end of this tutorial, we will have the following folders and files.  
├─ api/  
├─── config/  
├────── core.php - file used for core configuration  
├────── database.php - file used for connecting to the database.  
├─── objects/  
├────── product.php - contains properties and methods for "product" database queries.  
├────── category.php - contains properties and methods for "category" database queries.  
├─── product/  
├────── create.php - a file that will accept posted product data to be saved to the database.  
├────── delete.php - a file that will accept a product ID to delete a database record.  
├────── read.php - a file that will output JSON data based on "products" database records.  
├────── read_paging.php - a file that will output "products" JSON data with pagination.  
├────── read_one.php - a file that will accept product ID to read a record from the database.  
├────── update.php - a file that will accept a product ID to update a database record.  
├────── search.php - a file that will accept keywords parameter to search "products" database.  
├─── category/  
├────── read.php - a file that will output JSON data based on "categories" database records.  
├─── shared/  
├────── utilities.php - a file that will return pagination array.  
