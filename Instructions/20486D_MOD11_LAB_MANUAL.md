# Module 11: Managing Security

# Lab: Managing Security

#### Scenario

You have been asked to create a web-based library application for your organization's customers. The application should have a page showing the most recommended books, login and register pages, and ability to add books to the library for only authorized users. The application should contain Identity configuration, variety of different settings for authorization, and demonstration of cross-site request forgery attack.

#### Objectives

After completing this lab, you will be able to:

- Use Identity.
- Add Authorization.
- Avoid the Cross-Site Request Forgery Attack.

#### Lab Setup

Estimated Time: **60 minutes**

### Preparation Steps

1.	Ensure that you have cloned the **20486D** directory from GitHub. It contains the code segments for this course's labs and demos. (**https://github.com/MicrosoftLearning/20486D-DevelopingASPNETMVCWebApplications/tree/master/Allfiles**)

### Exercise 1: Use Identity

#### Scenario

In this exercise, you will first add entity framework database context to the **LibraryContext** class. You will then enable using identity in the **startup** class. After that you will add sign in, and register user logic. Finally, you will retrieve data from the identity property in the **LendingBook.cshtml** view.

The main tasks for this exercise are as follows:

1.	Add the Entity Framework database context.

2.	Enable using Identity.

3.	Add sign in logic.

4.	Add Register a user logic.

5.	Retrieve data from the Identity property.

6.	Run the application.


#### Task 1: Add the Entity Framework database context

1. Open the **Command Prompt** window using **Run as administrator**.

2. In Administrator: Command Prompt, run the following command: **cd <The location of Allfiles\Mod11\Labfiles\01_Library_begin\Library folder on your machine>**.

3. Run the following command: **npm install**.

4. Close the **Command Prompt** window.

5. Open the **Library.sln** solution from the following location: **Allfiles\Mod11\Labfiles\01_Library_begin**.

6. In the **User** class, add a **USING** statement for the following namespace:

   - **Microsoft.AspNetCore.Identity**

7. Change the **User** class to inherit from the **IdentityUser** class.

8. In the **LibraryContext** class, add a **USING** statement for the following namespace:

   - **Microsoft.AspNetCore.Identity.EntityFrameworkCore**

9. Change the  **LibraryContext** class to inherit from the **IdentityDbContext&lt;User&gt;** class.

#### Task 2: Enable using Identity

1. 


#### Task 3: Add sign in logic

1. 

#### Task 4: Add Register a user logic

1.

#### Task 5: Retrieve data from the Identity property

1. 

#### Task 6: Run the application

1. 

>**Results**: After completing this exercise, you will be able to configure identity in the application, add logic to the sign in and register pages, and retrieve data from identity.

### Exercise 2: Add Authorization

#### Scenario

In this exercise, you will first add **AuthorizeAttribute** to the **LibraryController** class. You will then configure role-based and claim based policy authentication. And, you will add the relevant attribute in the **AccountController** class and in the **LibrarianController** class.

The main tasks for this exercise are as follows:

1. Add the AuthorizeAttribute to an action.

2. Add Role-based Policy Authentication.

3. Add Claim-based Policy Authentication.

4. Run the application.

#### Task 1: Add the AuthorizeAttribute to an action

1. 

#### Task 2: Add Role-based Policy Authentication

1. 

#### Task 3: Add Claim-based Policy Authentication

1. 

#### Task 4: Run the application

1. 

>**Results**: After completing this exercise, you will be able to add authorization in the application, add configuration and the relevant attribute for role-based and claim based policy authentication.


### Exercise 3: Avoid the Cross-Site Request Forgery Attack



#### Scenario

In this exercise, you will first write the cross-site request forgery attack in a separate project. You will then run the application and see the possible attack. Finaly, you will  avoid the cross-site request forgery attack by adding the **ValidateAntiForgeryToken** attribute in the **AccountController** class, run the application and see the attack is not possible.

The main tasks for this exercise are as follows:

1. Write the Cross-Site Request Forgery attack.

2. Run the application – now the attack is possible.

3. Avoid the Cross-Site Request Forgery attack.

4. Run the application – now the attack is not possible.


#### Task 1: Write the Cross-Site Request Forgery attack

1. 

#### Task 2: Run the application – now the attack is possible

1.

#### Task 3: Avoid the Cross-Site Request Forgery attack

1. 

#### Task 4: Run the application – now the attack is not possible

1. 

>**Results**: After completing this exercise, you will be able to avoid cross-site request forgery attack.


©2018 Microsoft Corporation. All rights reserved.

The text in this document is available under the  [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/legalcode), additional terms may apply. All other content contained in this document (including, without limitation, trademarks, logos, images, etc.) are  **not**  included within the Creative Commons license grant. This document does not provide you with any legal rights to any intellectual property in any Microsoft product. You may copy and use this document for your internal, reference purposes.

This document is provided &quot;as-is.&quot; Information and views expressed in this document, including URL and other Internet Web site references, may change without notice. You bear the risk of using it. Some examples are for illustration only and are fictitious. No real association is intended or inferred. Microsoft makes no warranties, express or implied, with respect to the information provided here.