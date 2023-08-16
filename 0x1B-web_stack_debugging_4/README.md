0x1B. Web stack debugging #4
----------------------------------

Requirements
General
All your files will be interpreted on Ubuntu 14.04 LTS
All your files should end with a new line
A README.md file at the root of the folder of the project is mandatory
Your Puppet manifests must pass puppet-lint version 2.1.1 without any errors
Your Puppet manifests must run without error
Your Puppet manifests first line must be a comment explaining what the Puppet manifest is about
Your Puppet manifests files must end with the extension .pp
Files will be checked with Puppet v3.4
Install puppet-lint
$ apt-get install -y ruby
$ gem install puppet-lint -v 2.1.1

Tasks
---------------------------------------

0. Sky is the limit, let's bring that limit higher:  In this web stack debugging task, test how well  web server setup featuring Nginx is doing under pressure. When it is not doing well with huge amount of failed requests. Using ApacheBench which is a quite popular tool in the industry,  simulate HTTP requests to a web server and fix stack to 0. Repo: GitHub repository: alx-system_engineering-devops Directory: 0x1B-web_stack_debugging_4 File: 0-the_sky_is_the_limit_not.pp
1. User limit: Change the OS configuration so that it is possible to login with the holberton user and open a file without any error message. Repo: GitHub repository: alx-system_engineering-devops Directory: 0x1B-web_stack_debugging_4 File: 1-user_limit.pp
