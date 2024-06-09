!!Download pip if you have not. Follow instructions here to install pip: https://www.geeksforgeeks.org/how-to-install-pip-on-windows/
1.	Open your XAMPP Control Panel and start Apache and MySQL.
2.	Download the zip version of this source code folder (click on the green button "code" and then "Download zip") and paste it into the XAMPP's "htdocs" directory. (when u download, it may be saved as "sleeptight-main", if yes, rename back to "sleeptight")
3.	Browse the PHPMyAdmin in a browser. i.e. http://localhost/phpmyadmin
4.	Create a new database naming edoc.
5.	Import the provided SQL file. The file is known as SQL_Database_edoc.sql located inside the source code root folder.
6.	To start, enter http://localhost/sleeptight 
7.	Open Command prompt & run as administrator and install the followings (for window users)
- python -m pip install --upgrade pip
-	pip install flask
-	pip install pip install Flask-Cors
-	pip install python-pdf
-	pip install firebase-admin
-	pip install pickle5 
-	pip install pandas
-	pip install scikit-learn
-	pip install Flask-SQLAlchemy
-	pip install db
-	and more… will add when u guys send me more error messages
8.	Open Command Prompt, type “cd \xampp\htdocs\sleeptight\firebase” (edit path according till u reach the “firebase” folder) and then type “python app.py”. This is to start Flask to interact with the data from Firebase (dynamic database). To end, type "ctrl c".

Open Command Prompt, type “cd \xampp\htdocs\sleeptight\firebase” (edit path according till u reach the “firebase” folder) and then type “python app.py”. This is to start Flask to interact with the data from Firebase (dynamic database). To end, type "ctrl c".

Remember to stop XAMPP Apache and MySQL if you are not using it anymore
