# RestaurantManagement
## Login
You can use test data for the first time. You can add new staff when you log in as manager.
### Manager
- ID:1000 Password:java
- ID:5555 Password:kazukazu

### Staff
* ID:1111 Password:password
* ID:3333 Password:david  
(Do not modify the dataFiles directly, it will affect the application.)  

## Manage Employees (Manager only)
### Add new staff
1. Click "Manage Employees" Button
2. Click "New" button
3. Fill in all information and click OK

###Edit staff
1. Click "Manage Employees" Button
2. Select a staff from the employees list
3. Click "Edit" button
4. Fill in all information and click OK

###Delete staff
1. Click "Manage Employees" Button 
2. Select a staff from the employees list
3. Click "Delete" button

##Manage Menu Items (Manager only)
###Add new item
1. Click "Manage menu items" Button 
2. Click "Add new menu item" button
3. Fill in all information and click OK

###Edit menu item
1. Click "Manage menu items" Button 
2. Select a menu item from the menu list
3. Click "Edit menu item" button
4. Fill in all information and click OK

###Delete menu item
1. Click "Manage menu items" Button 
2. Select a menu item from the menu list
3. Click "Delete menu item" button

## Show menu
You can see all menu items by clicking "ALL" button, you can see particular items categories by clicking "Drink, Alcohol, Main, or Dessert" button.  
## Taking order
### Create new order
1. Click "Show menu" button 
2. Click "New" button to create new order
![](readme_images/order.jpg)
3. Select adding items by clicking from the menu list on the right side.
4. Enter quantity and click "Add" button  side.(If quantity is emputy, one item will be added)
5. You can delete ordered item from the order detail by clicking "Delete" button  

### Edit order
1. Click "Show menu" button 
2. Select the order from the order list to edit
3. Click "Edit" button
4. You can add, delete ordered items

### Close or Cancel order
1. Select the order from the order list
2. Click "Close" button or "Cancel" button
3. The order closed or canceled can not edit

##About payments
* When you log in, the system automatic set start working time.
* Clock out button will set finish working time of the person currently logged in.
* Manager can make staff clocked out via manage employees, by selecting staff and clicking Clock out button.
* You can see a payment details for a day by clicking "Show payment" button

##Restaurant management system application for complete End to End management.

##Tech Stacks Used
1. Java
2. Microservices
3. Docker
4. Kubernetes  
