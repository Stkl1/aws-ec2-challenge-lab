# AWS EC2 Challenge Lab

This project is part of the AWS re/Start EC2 challenge lab. The goal was to set up a simple web server on an Amazon Linux EC2 instance and make a basic webpage available over the internet. I followed the required steps to build the network, launch the instance, install Apache, and upload a small HTML file to test everything.

## What I Did

- Created a new VPC with a public subnet
- Attached an Internet Gateway and updated the route table
- Launched an Amazon Linux EC2 instance (t3.micro)
- Used user data to install and start Apache automatically
- Connected to the instance using EC2 Instance Connect
- Added a simple HTML file to `/var/www/html`
- Opened the instance’s public IPv4 address in a browser to confirm the page loads

## Why I Did It

This lab helped me practice the basics of EC2, networking, and Linux server setup. It’s mainly a reference for myself as I continue learning AWS, but I’m also sharing it here as part of my cloud portfolio.

## Files Included

- `index.html` – the test webpage
- `screenshots/` – images showing each step of the setup
- `README.md` – this explanation

## Result

The EC2 instance successfully served the HTML page, and everything worked as expected. The screenshots show the full process from launching the instance to viewing the webpage in a browser.
