0x0A. Configuration management
--------------------------------------------------------------------------------------------------
Learning Objectives: Intro to Configuration Management, Puppet resource type: file (check “Resource types” for all manifest types in the left menu), Puppet’s Declarative Language: Modeling Instead of Scripting, Puppet lint, Puppet emacs mode
General Requirements# All your files will be interpreted on Ubuntu 20.04 LTS All your files should end with a new line A README.md file at the root of the folder of the project is mandatory, Puppet manifests must pass puppet-lint version 2.1.1 without any errors, Puppet manifests must run without error, Puppet manifests first line must be a comment explaining what the Puppet manifest is about Puppet manifests files must end with the extension .pp

Tasks
-------------------------------------------------------------------------------------------
0. Create a file: Puppet is used to create a file in /tmp. Requirements: File path is /tmp/school File permission is 0744 File owner is www-data File group is www-data File contains I love Puppet Repo: GitHub repository: alx-system_engineering-devops Directory: 0x0A-configuration_management File: 0-create_a_file.pp
1. Install a package: Puppet is used to install flask from pip3. Requirements: Install flask Version must be 2.1.0 Repo: GitHub repository: alx-system_engineering-devops Directory: 0x0A-configuration_management File: 1-install_a_package.pp
2. Execute a command: Puppet is used to create a manifest that kills a process named killmenow. Requirements: Must use the exec Puppet resource Must use pkill Repo: GitHub repository: alx-system_engineering-devop Directory: 0x0A-configuration_management File: 2-execute_a_command.pp
