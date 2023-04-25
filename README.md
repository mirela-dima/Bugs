# Bug Report Samples

You can find below some samples of bug reports that i wrote.

...................................

### The breadcrumbs are missing

**Priority**: 3

**Severity**: Low

**Description**

When I navigate the website, the breadcrumbs aren't available.

**Steps to reproduce**
1. Go to www.demoblaze.com
2. Click on Phone category
3. Click on a phone model

**Expected results**

The breadcrumbs should be available under the header that shows the stepps i’ve done to the product. Is should allow to click on and return to the diferent pages i’ve already been.

**Actual results**

The breadcrumbs aren’t available.

....................................

### The login page is incomplete

**Prioriry**:  1

**Severity**:  High

**Description**

The password field on the login page is missing.
The system allows the login without the password.

**Steps to reproduce** 
1. Go to www.XYZBank.com
3. Click on Customer login
4. Select your name from the dropdown
5. Press the login button

**Expected results**

The password field should be next to type in.

**Actual results**

The password field don't exist. The system gives the possibility to login without the password.

....................................

### The link http://www.pensiunea-mareaneagra.ro/ is a broken link

**Description**

The link http://www.pensiunea-mareaneagra.ro/ is a broken link.

**Steps to reproduce**
1. Go to Home - Primaria Techirghiol
2. Scroll down to Info Turism section
3. Click on Cazare
4. Click on Pensiunea Marea Neagra

**Expected results**

The main page of the Hotel site should open.

**Actual result**

The error message shows: This site can’t be reached.

....................................

### The pictures of the products have different sizes

**Description**

Some shopcard pictures are bigger or smaller than the pictures of other products.

**Steps to reproduce**

1. Go to OWASP Juice Shop

**Expected results**

All the shopcard-pictures should have the same size, as the Apple Juice shopcard for example.

**Actual results**

Some shopcard-pictures have different sizes.

......................................

### The order is payed and placed with an invalid card

**Preconditions**

The user is logged.

The incorrect card data is already added to the user account.

**Description**

The system confirms the order even if the card data is invalid.

**Steps to reproduce**
1. Add products to the cart
2. Click on Checkout button
3. Select the address
4. Click on Continue button
5. Choose a delivery option 
6. Click on Continue button
7. Select the card for the payment
8. Click on Continue button
9. Click on “Place your order and pay” button
10. Click on Print order confirmation icon.

**Expected results**

The system should not allow for the order to be placed.

**Actual results**

The order is placed with no problems (see the orders confirmation links).

https://juice-shop.herokuapp.com/ftp/order_1429-5cc8f9b6c8e59da1.pdf

https://juice-shop.herokuapp.com/ftp/order_1429-2dd08b3476aed83e.pdf

.......................................

### The first choise in the Expiry Year of the card is 2080

**Precondition**

The user is successfully logged in.

**Description**

In the Expiry Year dropdown the first year available to choose is 2080.

**Steps to reproduce**
1. Add products to the cart
2. Click on Checkout button
3. Select the delivery address
4. Click on Continue
5. Choose the One Day Deliver option
6. Click on Continue
7. Click on Add new card section
8. Add the Name
9. Add the Card number
10. Add the Expiry Month 
11. Click on the Expiry Year dropdown.

**Expected results**

The first year available should be 2023.

**Actual results**

The first year available is 2080.

**Test data**

Card Name: Mirela Dima

Card number: 4455887788774455

Expiry Mounth: 1

Expiry Year: 2023 

