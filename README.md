# Bug Report Samples

You can find below some samples of bug reports that i wrote.

...................................

The breadcrumbs are missing

Priority: 3
Severity: low

Description
When I navigate the website, the breadcrumbs should be available.

Steps to reproduce
1. Go to www.demoblaze.com
2. Click on Phone category
3. Click on a phone model

Expected results
The breadcrumbs should be available under the header that shows the stepps i’ve done to the product. Is should allow to click on and return to the diferent pages i’ve already been.

Actual results
The breadcrumbs aren’t available.

....................................

The login page is incomplete

Prioriry  1
Severity  High

Description:
The password field on the login page is missing.
The system allows the login without the password.

Steps to reproduce 
1. Go to XYZ Bank 
2. Click on Customer login
3. Select your name from the dropdown
4. Press the login button

Expected results
The password field should be next to type in.

Actual results
The password field don't exist. The system gives the possibility to login without the password.

....................................

The pictures of the products have different sizes

Description
Some shopcard pictures are bigger or smaller than the pictures of other products.

Steps to reproduce
1. Go to OWASP Juice Shop

Expected results
All the shopcard-pictures should have the same size, as the Apple Juice shopcard for example.

Actual results
Some shopcard-pictures have different sizes.

......................................

The first choise in the Expiry Year of the card is 2080

Precondition:
The user is successfully logged in.

Description
In the Expiry Year dropdown the first year available to choose is 2080.

Steps to reproduce
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

Expected results
The first year available should be 2023.

Actual results
The first year available is 2080.

Test data
Card Name: Mirela Dima
Card number: 4455887788774455
Expiry Mounth: 1
Expiry Year: 2023 


