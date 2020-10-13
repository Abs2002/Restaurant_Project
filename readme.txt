Centrum Stravovania Billing Application v1.0.0.1
-
This tkinter application is made to take order from the customer
and genrate the invoice bill with QR code having the information of
the customer's name phonenumber amount and mode of payment.

the bill details are stored in the MySQL table of the restaurant and
the data can be manupilated the admin

Features
-
 - All the food items have buttons of their own
 - When Button is pressed the food item gets displayed on listobx
 - When we tap on evaluate button it then gives total amount with
   GST and service charges in the next textbox
 - When we select on the fooditem in the listbox and tap on the
   delete button it removes the specified fooditem
 - When we tap on the delete all button it removes all fooditems
   are removed the listbox
 - When we place order it takes the all arguements from the GUI and
   make a PDF invoice with QR code of the above details
 - The details are also taken and inserted into the mysql table to store
   the data in it.

NextVersions
-
More fooditem buttons will added in this GUI and Better appearence
will be presented. Next Version will be v1.0.2.4

Note:
-
All the queries of mysql are made in seprate .sql file
wihch is in the same directory. Mysql is cumpulsory for this program.

Additional Python Modules to install if not
-
 - pip install pyqrcode (windows) or python-pip3 install pyqrcode (Linux, Mac)
 - pip install mysql-connector (Windows) or python-pip3 install mysql-connector (Linux, Mac)
 - pip install fpdf (windows) or python-pip3 install fpdf (Linux, Mac)
 - pip install pypng (Windows) or python-pip3 install pypng (Linux, Mac)

Developed by Anirudh Bishnoi
GitHub ID Name : Abs2002

Name of the Restaurant(Fictional) just for giving a cool name
Samples of the program are added in the same directory