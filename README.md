# Spring MVC and Hibernate CRM web application
The application connects to a MySQL database. It uses a controller to handle the incoming requests and redirect 
to relevant services. Trying to replicate a larger scale application, a facade service was implemented. The link with the database is done using a 
Data Access Object (DAO) which has a Customer entity reference. The Customer class has its fields mapped to the Customer table.

Project setup was done by importing Spring, Hibernate, JBDC and JSTL libraries jars from their respective websites and configuring the web and spring xml's.

The JSP's use JSTL and Spring tags to facilitate code development.

The main screen lists all of the customers retrieved from the database sorted by Last Name. 

Using the add customer button we can add a new customer in the database.

Using the search customer button users insert a query which will retrieve results from the database that match the first and last name. If no search input is provided then
customers are reordered by ID. If there are no matching entries then no results will be displayed.

Customers can be sorted alphabetically (first name, last name or email) by clicking the respective table headers.

Customers can have their details updated.

Customers can be deleted from the database.

**Application Overview**
![Screenshot 2022-03-11 134450](https://user-images.githubusercontent.com/91902093/157860963-78377442-35b4-41d5-8b6a-29667e15ea62.png)
**HomePage**
![customer-tracker-homepage](https://user-images.githubusercontent.com/91902093/157616958-2549936d-af63-41a4-9bca-082cf70232d1.png)
**New Customer Page**
![customer-tracker-newcustomerpage](https://user-images.githubusercontent.com/91902093/157616963-72d708f6-71ce-48aa-8eaf-3b85803cd4cb.png)
**Update Customer Page**
![customer-tracker-updatecustomerpage](https://user-images.githubusercontent.com/91902093/157616971-fdea5d65-527f-4c52-bebc-b7836ff6b5ba.png)
**Delete Customer Prompt**
![customer-tracker-deletecustomerprompt](https://user-images.githubusercontent.com/91902093/157616982-75221a50-5b70-4419-baad-e41a4fb224b0.png)
**Seach result page for "Jo" query**
![customer-tracker-searchresultforjo](https://user-images.githubusercontent.com/91902093/157617488-e326082c-8b55-4130-be53-3d006832415e.png)
