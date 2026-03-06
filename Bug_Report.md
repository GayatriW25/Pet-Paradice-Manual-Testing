## Defect 1 : Login page accepts unlimited characters in username and password fields

Defect ID: DP001 

Module:
Login Page

Severity:
Medium

Priority:
Medium

Description:
The login page allows users to enter unlimited characters in the username and password fields. The system should restrict the input length according to defined validation rules.

Steps to Reproduce:

Open the application login page

Enter more than 100 characters in the username field

Enter more than 100 characters in the password field

Click Login

Expected Result:
System should restrict input length or show validation message.

Actual Result:
System accepts unlimited characters without validation.

Status:
Fixed

## Defect 2: User can see other users' orders

Defect ID: DP002  
Module: Order History  
Severity: High  
Priority: High  

Description:  
When a user checks the order history, the system displays orders of all users instead of showing only the logged-in user's orders.

Steps to Reproduce:
1. Login as a user
2. Place an order
3. Navigate to Order History page
4. Observe the list of orders displayed

Expected Result:  
The system should display only the orders placed by the logged-in user.

Actual Result:  
The system displays orders of all users.

Status: Open


## Defect 3: Pet added to cart is not linked to unique ID

Defect ID: DP003
Module: Cart
Severity: High
Priority: High

Description:
When a user adds a pet to the cart, it should be added with the pet’s unique ID, but currently, the cart adds items in sequence/order instead of associating them with the correct pet ID.

Steps to Reproduce:

Login as a user

Add any pet to the cart

Check the cart database or cart list

Expected Result:
The pet should be added to the cart using its unique ID so that the correct pet details are maintained.

Actual Result:
Pets are added in sequential order regardless of their unique ID, causing mismatches in cart and order details.

Status: Open
