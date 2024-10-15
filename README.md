# Webtoon Content Web Application

## Overview
This project demonstrates a basic web application designed to display webtoon titles, genres, and descriptions using mock data. The application is hosted on an AWS EC2 instance, ensuring scalability, availability, and security.

## Files
- `index.html`: The main HTML file displaying webtoon content.
- Additional files (CSS, JS, images) may be included for styling and functionality.

## Cloud Deployment
1. **Cloud Provider**: Amazon Web Services (AWS)
2. **Instance Type**: EC2 t2.micro
3. **Security Group**: Opened ports 80 (HTTP) and 22 (SSH).
4. **Deployment Steps**:
   - Clone the repository:  
     `git clone https://github.com/VISHNUCHARAN24/cloud-computing-assignment.git`
   - Navigate to the project directory and move `index.html` to `/var/www/html/`.
   - Start the Nginx server:  
     `sudo systemctl start nginx`
   - Access the application via the public IP of the EC2 instance.

## Instructions
For details on how to access the application, please refer to the deployment steps.

## License
This project is licensed under the MIT License.
