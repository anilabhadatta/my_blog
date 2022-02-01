# my_blog

To run this project you must have installed pythhon 3.8 and above. Clone this repo in your system and open the terminal inside the folder and run the following command to install the necessary python modules:
## pip install -r requirements.txt
The project is built using HTML,CSS and backend using Django and contains a AWS-PostGres database or local SQLITE database. 
To start the server enter the following command:
## python manage.py runserver

This project is deployed in Amazon AWS using Elastic BeanStalk , RDS-PostGres, S3 Bucket, To access the webpage click on any link below:
## http://anilabha.me or http://myfirstblog-env.eba-jpkp7diw.us-east-2.elasticbeanstalk.com/

If you want to deploy this project in AWS Elastic Beanstalk then make sure to provide Secret Key in settings.py and AWS PostGres Auth details or use the local SQLITE database and AWS S3 Bucket Auth details if you want to use S3 bucket to save static files and images.
