### <center>INSTALLING Nginx Web Server 

In this project I would be implementing a similar stack like Apache but with NGINX Webserver.

In order to begin this project the following is required ;

<ol>
  <li>AWS account</li>
  <li>EC2 instance of t2.nano running Ubuntu Server 20.04 LTS (HVM) image</li>
  <li>Git Bash</li> 
  </ol>

Lets begin:-

In order to display web pages for visitors to view my website, I'm going to deploy Ngnix. Its a high performance web server.

Login to AWS management console, open EC2 then launch instance if you haven't created one (Ubuntu Server).

 ![Ubuntu Server](./Images/instance.JPG)

 First I'm going to update the server package index by running the command 
 
 <code>sudo apt update</code> then <code>sudo apt install nginx</code> to install Nginx Web server

 ![Ubuntu Server](./Images/ngnix.JPG)
