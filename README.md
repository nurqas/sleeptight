1.	Open your XAMPP Control Panel and start Apache and MySQL.
2.	Download the zip version of this source code folder and paste it into the XAMPP's "htdocs" directory. (when  downloaded, it may be saved as "sleeptight-main", if yes, rename back to "sleeptight")
3.	Browse the PHPMyAdmin in a browser. i.e. http://localhost/phpmyadmin
4.	Create a new database naming "edoc"
5.	Import the provided SQL file. The file is known as SQL_Database_edoc.sql located inside the source code root folder.
   
6.	To start, enter http://localhost/sleeptight 
7.	Open Command prompt & run as administrator and install the followings (for window users)
- python -m pip install --upgrade pip
-	pip install flask
-	pip install pip install Flask-Cors
-	pip install python-pdf
-	pip install fpdf
-	pip install firebase-admin
-	pip install pickle5 
-	pip install pandas
-	pip install scikit-learn
-	pip install Flask-SQLAlchemy
-	pip install db

8.	Open Command Prompt, type “cd \xampp\htdocs\sleeptight\firebase” (edit path according till u reach the “firebase” folder) and then type “python app.py”. This is to start Flask to interact with the data from Firebase (dynamic database). To end, type "ctrl c".


ADMIN
Email: admin@edoc.com
Password: 123

Doctor
Email: doctor@edoc.com
Password: 123

Patient
Email: patient@edoc.com
Password: 123

Website Template taken from: https://www.sourcecodester.com/hashenudara/simple-doctors-appointment-project.html
