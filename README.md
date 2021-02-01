LIVE PROJECT INTERNSHIP OVERVIEW 

FRONT/BACK END STORY:
-Donor List Dropdown/ Link to Nav Bar

Adding Donor List Dropdown/ Link Dropdown/ Link to Nav Bar
This story required me to add in a new NavBar section for the currently existing page, Donor List.  The purpose of this was to allow the admin or back end user of this functioning website a quick link to a list of Donors using the NavBar only seen by the admin user.

 ![alt tag](https://github.com/BrielleLinna/Software-Developer-Internship/blob/main/Intern%20Photos/Story1-code.PNG?raw=true)
 
 ![alt tag](Before-admin_donorlist.PNG)
 
 BACK END STORY:
 Create Survey Model and CRUD (

This story required me to build a new SurveyModel, and then a secondary RentalSurvey model which was to extend from the SurveyModel. I needed to create a table-per-hierarchy table for the Survey model. Additionally,  I needed to create a 1-1 relationship between the existing RentalRequest and the new RentalSurvey models and change RentalRequwets  Survey property to type RentalSurvey. Lastly, I needed to create a SurveyController that generated CRUD view pages.

Here is an example of the image provided as a launching point:

![alt tag](Story104.png)


Step 1: Create new Survey Model and define properties and create a 1:1 relationship1

![alt tag](Story107.PNG)

![alt tag](Story108.PNG)

![alt tag](Story109.PNG)

![alt tag](Story110.PNG)

Step 2:Create a TPH relationship with Rebtal Survey and Survey Model

![alt tag](Story111.PNG)

Step 3: Make RentalRequest's Survey property of type RentalSurvey

![alt tag](Story106.PNG)

Step 4: Create Survey Controller with CRUD pages.

![alt tag](Story113.PNG)

