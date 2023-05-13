# Bug Report Samples

You can find below some samples of bug reports that i wrote.

...................................

### The pictures of the products have different sizes

**Description**

Some shopcard pictures are bigger or smaller than the pictures of other products.

**Steps to reproduce**

1. Go to OWASP Juice Shop

**Expected results**

All the shopcard-pictures should have the same size, as the Apple Juice shopcard for example.

**Actual results**

Some shopcard-pictures have different sizes.

![Bug 9](https://github.com/mirela-dima/Bugs/assets/124343975/af30ed34-1147-4904-b294-d7ace100c343)

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

![Password field is missing](https://github.com/mirela-dima/Bugs/assets/124343975/7f012914-1bbf-4d7b-9758-1cd27b37a056)

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

![Broken link](https://github.com/mirela-dima/Bugs/assets/124343975/954844d0-1bf7-42a2-9e2d-94c977b511df)

......................................

### The order is payed and placed with an invalid card

**Preconditions**

The user is logged to https://juice-shop.herokuapp.com/#/

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

The order is placed with no problems (see the orders confirmation link).

https://juice-shop.herokuapp.com/ftp/order_1429-5cc8f9b6c8e59da1.pdf


....................................

### The text on the right side of the password field shows that only 20 characters are accepted

**Description**

The text under the password field on the right shows that only up to 20 characters are allowed, the text right under the password shows that should allow up to 40.

Steps to reproduce
1. Go to https://juice-shop.herokuapp.com/# 
2.  Click on Account button 
3. Click on Login
4. Click on Not yet a customer?
5. Digit the email
6. Digit the password of 27 characters
7. Choose a question
8. Add the answer to the security question
9. Click on Register Button.

**Expected results**
If the field does not allow more than 20 characters in the field, than the text on the left should be removed.
If the field does allow more than 20 characters in the field, than the text on the right should be removed.

**Actual results**
The field allows more that 20 characters, the text on the left should be removed.

**Text data**
Email  mirela.dima1982@yahoo.it
Password  123456789123456789123456789  - 27 characters

![proba 2](https://github.com/mirela-dima/Bugs/assets/124343975/0ced116c-e4d9-4edc-a228-2a9492c0fb7f)

.............................

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

.......................................

### The first choise in the Expiry Year of the card is 2080

**Precondition**

The user is successfully logged on https://juice-shop.herokuapp.com/#/.

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

