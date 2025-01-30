WordPress Deployment with Ansible
This repository contains an Ansible playbook to automate the deployment of a WordPress site on a remote server. The playbook handles everything from installing dependencies, configuring the web server, setting up the database, and customizing the WordPress installation.

Features
Automated WordPress Deployment: Fully automated setup of WordPress on a remote server.

Dependency Installation: Installs and configures all required packages (Apache, MySQL, PHP, and more).

Database Configuration: Creates a MySQL database and user for WordPress.

WordPress Setup: Downloads and configures the latest version of WordPress.

Security Enhancements: Automatically generates and configures secure authentication keys and salts for WordPress.

Idempotent Playbook: Safe to run multiple times without causing unintended changes.
