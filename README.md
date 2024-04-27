# VPC

# VPC Setup Project 

## Project Overview

This project demonstrates the setup and configuration of a Virtual Private Cloud (VPC) on AWS, with a focus on deploying a simple web application for testing purposes. The project includes creating subnets, instances, security groups, and a load balancer within the VPC environment.

## Project Structure

- **CFK (temp converter)**: Contains the application code for a temperature converter web app.
    - [temp.html](CFK/temp.html): HTML file containing the code for the temperature converter application.
      
## Detailed Setup Steps

### 1. VPC Creation and Subnet Configuration

- **Step 1:** Navigate to the AWS Management Console.
- **Step 2:** Go to the VPC service and create a new VPC.
- **Step 3:** Create public and private subnets within the VPC across different availability zones.
- **Step 4:** Allocate instances to the subnets based on security and accessibility requirements.

### 2. Bastion Host Setup

- **Step 1:** Deploy a Bastion host instance in the public subnet.
- **Step 2:** Configure SSH access to private instances via the Bastion host for enhanced security.

### 3. Auto Scaling Group and Launch Template

- **Step 1:** Set up an Auto Scaling Group with a launch template to automatically deploy instances.
- **Step 2:** Define scaling policies to ensure optimal performance and resource utilization.

### 4. Load Balancer Configuration

- **Step 1:** Create a load balancer to distribute incoming traffic across instances.
- **Step 2:** Configure target groups to route traffic effectively based on predefined criteria.

### 5. Security Group Settings

- **Step 1:** Configure security groups to control inbound and outbound traffic to instances.
- **Step 2:** Open port 80 in the security group to allow access to the deployed web application.

### 6. Application Deployment

- **Step 1:** Clone or download the `temp.html` file from the provided link: [temp.html](CFK/temp.html)
- **Step 2:** Deploy the `temp.html` file to the instances or a suitable server within the VPC.
- **Step 3:** Test the application functionality by accessing it through the load balancer DNS or the instance's public IP address.

## Troubleshooting Tips

- If encountering deployment issues, refer to AWS documentation or seek assistance from AWS support.
- Double-check security group settings to ensure proper access to instances and applications.

## Conclusion

This README provides a comprehensive guide to setting up the VPC environment and deploying the temperature converter web application. 

