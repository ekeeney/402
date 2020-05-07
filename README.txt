# 402

Hi Everyone - hopefully this will be a resource for you to be able to put your Tableau into the website portion of the final project: 

First, I'm making the assumption that you have made a Tableau DASHBOARD - not just sheets
  - A dashboard is an interactive interface that combines your different Tableau outputs
  
After you have made the dashboard, follow these steps to put the dashboard into your website
1. Make a Tableau Public Account: https://public.tableau.com

2. Extract your data within Tableau: 
      Data > [your data source] > Extract Data > Extract 
          ** Hint: you data source will likely be the name of your first table and then (BMGT402_DB_XXX)**

3. Publish the Dashboard to Tableau Public: 
      Server > Tableau Public > Save To Tableau Public As 

4. View your Tableau Dashboard on Tableau Public in your browser 

5. Find the share button at the bottom of the graphic [it has 3 spheres connected with 2 lines] 

6. Copy the "Embedded Code" [you must copy all of this]

7. Input the embedded code into the tableauReport code found on lines 14 and 15 [you can delete what I have - that's a placeholder]
    ** It may come up as a long string, pretty much use common sense to make it look nicer
    ** Change this to fit your own website

8. Copy this entire page to new a .php within your project 
      ** Hint: the easiest way to do this is to duplicate the "insert_one_table.php" or equivalent
            You will NOT need a process document for adding this page 

9. Create a new "Button" on the homepage for the file through the index.php file just as you modified them in lab
      ** Hint: You might need to copy, paste and modify some of the code to make a whole extra button

When you click the button, you should now see your dashboard on the website! 
