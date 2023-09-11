Python Web Server
SCS2205 Computer Networks I

Configurations
In the server.py file:

These are the default configurations:

HOST = "127.0.0.1" # Required host
PORT = 2728 # Required port
ROOT = "C:\Computer Network Assignments\Take Home01\htdocs"  # Absolute path of the htdocs directory
PHP_FILE_PATH = "C:\Computer Network Assignments\Take Home01\htdocs\WebPages"  # Location of the php file
PHP_FILE_NAME = "run.php" # Name of the php file
PORT_2 = "8000" # Any port that is not in use for the localhost

Run server locally
Run the below command using command prompt from the directory where the server.py file is located

python server.py
Viewing the other pages
Copy and paste the below URLs in your web browser to view the pages. You can also use localhost instead of 127.0.0.1

http://127.0.0.1:2728/
http://127.0.0.1:2728/about.php
http://127.0.0.1:2728/contact.php
http://127.0.0.1:2728/text.php

NOTE
This program is made for Windows OS, so it can be only run on a Windows PC.