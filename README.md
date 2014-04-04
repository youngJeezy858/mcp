mcp
===

Master Control Program:  A program to control Cyber Security Gymnasiums.  

Setting up the environment:

In the EC2 Management Console

* Click Launch Instance
* Then click community AMI
* Search for 14.04 and pick the 64 bit AMI.
* Connect to instance, sudo apt-get update && sudo apt-get dist-upgrade -y
* sudo apt-get install ruby-rails-4.0
* sudo apt-get install sqlite3 libsqlite3-dev
* mkdir rails_projects
* cd rails_projects && rails new mcp
* cd mcp && bundle
