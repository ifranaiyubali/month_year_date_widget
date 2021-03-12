# month_year_date_widget
Have a Date widget for showing Month and Year , optionaly show year only  


Have extended the Widget from django's docs, also found the link in stack overflow

https://stackoverflow.com/questions/4733098/django-selectdatewidget-to-show-month-and-year-only

Based on SelectDateWidget, in

    django/trunk/django/forms/extras/widgets.py
    
Additionally have a default parameter to allow showing month or not and 
change the return statement at the end to retun month value as  1 if it not in the form

Also added range +10 and  -10 if the year is not set in the parameter

![image](https://user-images.githubusercontent.com/57422609/110920075-b1ef0080-8368-11eb-9c68-d7d61c52fa2e.png)


Usage 

Import as follows :

![image](https://user-images.githubusercontent.com/57422609/110920282-ee226100-8368-11eb-91c7-5265b8716a08.png)


Use like :

![image](https://user-images.githubusercontent.com/57422609/110920499-32156600-8369-11eb-9721-ef7b16485b14.png)
