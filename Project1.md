# WEB STACK IMPLEMENTATION IN AWS


A technology stack is a set of frameworks and tools used to develop a software product. This set of frameworks and tools are very specifically chosen to work together in creating a well-functioning software. 

![newimage1](https://user-images.githubusercontent.com/50987494/208643619-19a76c00-2795-4828-96a9-ec6734fbc949.png)


##   INSTALLING APACHE AND UPDATING THE FIREWALL

#update a list of packages in package manager

`sudo apt update`

#run apache2 package installation

`sudo apt install apache2`

To verify that apache2 is running as a Service in our OS, use following command

`sudo systemctl status apache2`

![sudo-systemctl](https://user-images.githubusercontent.com/50987494/208656852-30e09961-91a9-4c75-8b86-12f016dccb7c.PNG)

Our server is running and we can access it locally and from the Internet (Source 0.0.0.0/0 means ‘from any IP address’).

we then access our server locally in the ubuntu shell by running the following

`curl http://localhost:80`

![curl-local80](https://user-images.githubusercontent.com/50987494/208658930-fbda0c76-4a92-4b3a-8384-3bfadfdcf858.PNG)

Open a web browser of your choice and try to access following url to ensure its working, we can pick 
