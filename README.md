# Project-KIET-E-Content-Video-App-

Steps to activate project on LINUX-

# Step 1 : Install apache/httpd
# Step 2 : Install mysql server 
# Step 3 : Create database named 'vss_db'
# Step 4 : Clone the project from github to /var/www/html/ directory.
# Step 5 : Go to directory ~# cd database/
# Step 6 : Run Command ~# mysql -u username -p database_name < vss_db.sql
# Step 7 : Update db_connect.php file - $conn= new mysqli('localhost','user','password','vss_db')
# Step 8 : Restart apache server ~# service apache2 restart
# Step 9 : Open the project on web browser http://localhost/video_sharing/

############### HAPPY CODING #####################################
