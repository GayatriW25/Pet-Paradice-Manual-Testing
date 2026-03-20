**TC_001 – User Registration**

**Module:** Registration
**Test Scenario:** Verify user registration functionality
**Precondition:** Pet Paradise application is installed
**Test Data:** Valid username, password, email, etc.

**Steps:**

- Open the Pet Paradise application
- Navigate to the Registration page
- Enter valid user details
- Click Register button

**Expected Result:**
User should be registered successfully and a confirmation message should be displayed.

**TC_002 – Login with Valid Credentials**

**Module:** Login
**Test Scenario:** Verify login with valid credentials
Precondition: User is registered
Test Data: Valid username and password

**Steps:**

- Open the application
- Enter valid username and password
- Click Login button

Expected Result:
User should login successfully and the dashboard should open.

**TC_003 – Login with Invalid Credentials**

Module: Login
Test Scenario: Verify login with invalid credentials
Precondition: Pet Paradise application is installed
Test Data: Invalid username or password

**Steps:**

- Open the application
- Enter invalid username/password
- Click Login button

Expected Result:
Error message should be displayed indicating invalid credentials.

**TC_004 – Pet List Display**

Module: Pet Listing
Test Scenario: Verify pet list display
Precondition: User is logged in
Test Data: N/A

**Steps:**

- Login to the application
- Click View Pets

Expected Result:
List of pets should be displayed correctly.

**TC_005 – Add Pet to Cart**

Module: Cart
Test Scenario: Verify add pet to cart
Precondition: User is logged in and pets are available
Test Data: Pet ID to add

**Steps:**
- Login to the application
- Navigate to View Pets
- Select a pet

Click Add to Cart button

Expected Result:
Selected pet should be added to the cart with correct details linked to the logged-in user.

**TC_006 – Remove Pet from Cart**

Module: Cart
Test Scenario: Verify remove pet from cart
Precondition: User has items in cart
Test Data: Pet ID in cart

**Steps:**

- Go to Cart page
- Select the pet to remove
- Click Remove button

Expected Result:
Selected pet should be removed from the cart and cart total updated accordingly.

**TC_007 – Place Order**

Module: Orders
Test Scenario: Verify order placement
Precondition: User has items in cart
Test Data: Cart items

**Steps:**

- Go to Cart page
- Click Place Order button
- Confirm the order

Expected Result:
Order should be placed successfully, and order details should be saved in the database linked to the logged-in user.

**TC_008 – Logout**

Module: Login/Logout
Test Scenario: Verify logout functionality
Precondition: User is logged in
Test Data: N/A

**Steps:**

- Click Logout button

Expected Result:
User should be logged out successfully and redirected to the login page.
