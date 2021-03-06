## Changelog

### 1.0.16  [:arrow_down: Download](https://github.com/QubitProducts/UniversalVariable-Magento-Extension/archive/1.0.16.zip)
* Export guest email on transaction pages

### 1.0.15  [:arrow_down: Download](https://github.com/QubitProducts/UniversalVariable-Magento-Extension/archive/1.0.15.zip)
* Improve theme and frontend compatibility; Added modman to github source for ease of development.

### 1.0.14
* Corrected `line_item` quantity for non-transaction pages

### 1.0.13
* Added `voucher_discount` in transaction

### 1.0.11
* Deprecated `listing` variable on category pages, because it loops all the products without pagination; only output `listing.query` in search result that contains search queries.

### 1.0.10
* when voucher code is not used, use empty string intead of null

### 1.0.9
* output user_id and store language code correctly

### 1.0.8
* Rename page categroy from controller/view naming to correct page category inclueding home, checkout, basket, confirmation, product, category pages
* Added `listing` variable for category pages 

### 1.0.7
* Added total_discount for a `line_item` in basket and transaction; it's useful to calculate average product cost when complicated sales discount rule applied.

### 1.0.6
* address get product details compatibility issue; output system version in universal variable for diagnosing. 

### 1.0.5
* verbosely check shipping and billing address, some systems does not have such value 

### 1.0.4
* handle more transaction pages provided by other checkout systems

### 1.0.3
* fixed issue with failed to load Data.php file

### 1.0.2
* ignore invisible products in basket and order
* calcuate the correct order prices for configurable products

### 1.0.1
* parse price into float data type

### 1.0.0
* inital release
* allow system output universal variables
* configure OpenTag script through configuration panel
