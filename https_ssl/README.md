# Webstack Projects - HTTPS SSL Setup

This repository contains configurations and scripts for setting up SSL termination, enforcing HTTPS, and configuring HAProxy for web servers.

## Project 1: HAProxy SSL Termination

### Objective

Configure HAProxy to terminate SSL and serve encrypted traffic for a specified subdomain. Ensure that accessing the root page of the domain displays "Holberton School."

### Steps

1. Install HAProxy 1.5 or higher.
2. Obtain an SSL certificate using Certbot.
3. Configure HAProxy to handle SSL termination and route traffic.
4. Configure your backend web server to serve the root page.
5. Reload HAProxy configuration.
6. Test SSL termination and content delivery.

## Project 2: Redirect HTTP to HTTPS

### Objective

Enforce HTTPS traffic by configuring HAProxy to automatically redirect HTTP traffic to HTTPS.

### Steps

1. Open HAProxy configuration file (`/etc/haproxy/haproxy.cfg`).
2. Add configuration to set up redirection.
3. Reload HAProxy configuration.
4. Test HTTP to HTTPS redirection using `curl`.

## Usage

Clone this repository and navigate to the relevant project directory. Follow the steps outlined in each project's `README.md` to set up and configure HAProxy for SSL termination and redirection.

## Author

[Maxime Bakunzi](https://github.com/Maxime-Bakunzi)

