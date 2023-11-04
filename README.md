# Hosting-Website-using-AWS-server
### linux project 

create and launch the instance  
After establishing connection with the instance run the following commands  

`sudo apt update`  
`sudo apt install apache2`  
`cd /var/www/html/`  
create these files and write the given respective codes  
`sudo vim index.html`  
`sudo vim style.css`  
`sudo vim timer.js`  
`sudo vim utilis.css`  

## To see the website  
Copy and paste the public ip address of the instance in the browser  
http://51.20.102.25/  

## To make the static ip address  
Allocate elastic ip address  
Then associte the IP address with the instance using action button
