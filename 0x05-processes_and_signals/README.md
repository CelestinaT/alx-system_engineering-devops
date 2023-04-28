0x05. Processes and signals
-------------------------------------------------------------------------------------------------------------------------------------
Learning Objectives: What is a PID? What is a process? How to find a process’ PID, How to kill a process What is a signal? What are the 2 signals that cannot be ignored?
Requirements: Allowed editors: vi, vim, emacs All your files will be interpreted on Ubuntu 20.04 LTSAll your files should end with a new line, A README.md file, at the root of the folder of the project, is mandatory, All your Bash script files must be executable, Your Bash script must pass Shellcheck (version 0.7.0 via apt-get) without any error, The first line of all your Bash scripts should be exactly #!/usr/bin/env bash, The second line of all your Bash scripts should be a comment explaining what is the script doing
Task 0. What is my PID
---------------------------------------------------------------------------------------------------------------
Write a Bash script that displays its own PID.
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x05-processes_and_signals File: 0-what-is-my-pid
Task 1. List your processes
---------------------------------------------------------------------------------------------------------------------
Write a Bash script that displays a list of currently running processes. Must show all processes, for all users, including those which might not have a TTY, Display in a user-oriented format,Show process hierarchy
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x05-processes_and_signals File: 1-list_your_processes
Task 2. Show your Bash PID
---------------------------------------------------------------------------------------------------------------------------
Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process. You cannot use pgrep. The third line of your script must be # shellcheck disable=SC2009 
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x05-processes_and_signals File: 2-show_your_bash_pid
Task 3. Show your Bash PID made easy
--------------------------------------------------------------------------------------------------------------------------------
Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash. You cannot use ps
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x05-processes_and_signals File: 3-show_your_bash_pid_made_easy
 
Task 4. To infinity and beyond
------------------------------------------------------------------------------------------------------------------
Write a Bash script that displays To infinity and beyond indefinitely. In between each iteration of the loop, add a sleep 2
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x05-processes_and_signals File: 4-to_infinity_and_beyond
Task 5. Don't stop me now!
-----------------------------------------------------------------------------------------------------------------
Write a Bash script that stops 4-to_infinity_and_beyond process. You must use kill, Terminal #0
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x05-processes_and_signals File: 5-dont_stop_me_now
Task 6. Stop me if you can
--------------------------------------------------------------------------------------------------------------
Write a Bash script that stops 4-to_infinity_and_beyond process. You cannot use kill or killall, Terminal #0
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x05-processes_and_signals File: 6-stop_me_if_you_can
Task 7. Highlander
--------------------------------------------------------------------------------------------------------------
Write a Bash script that displays: To infinity and beyond indefinitely. With a sleep 2 in between each iteration, I am invincible!!! when receiving a SIGTERM signal, Make a copy of your 6-stop_me_if_you_can script, name it 67-stop_me_if_you_can, that kills the 7-highlander process instead of the 4-to_infinity_and_beyond one. Terminal #0
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x05-processes_and_signals File: 7-highlander
Task 8. Beheaded process
------------------------------------------------------------------------------------------------------------------------------
Write a Bash script that kills the process 7-highlander.
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x05-processes_and_signals File: 8-beheaded_process
Task 9. Process and PID file
------------------------------------------------------------------------------------------------------------------
Write a Bash script that: Creates the file /var/run/myscript.pid containing its PID,Displays To infinity and beyond indefinitely, Displays I hate the kill command when receiving a SIGTERM signal, Displays Y U no love me?! when receiving a SIGINT signal, Deletes the file /var/run/myscript.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal

Repo: GitHub repository: alx-system_engineering-devops Directory: 0x05-processes_and_signals File: 100-process_and_pid_file
Task 10. Manage my process
-------------------------------------------------------------------------------------------------------------------------------------
Write a manage_my_process Bash script that: Indefinitely writes I am alive! to the file /tmp/my_process, In between every I am alive! message, the program should pause for 2 seconds, Write Bash (init) script 101-manage_my_process that manages manage_my_process. (both files need to be pushed to git). When passing the argument start: Starts manage_my_process, Creates a file containing its PID in /var/run/my_process.pid Displays manage_my_process started, When passing the argument stop: Stops manage_my_process, Deletes the file /var/run/my_process.pid Displays manage_my_process stopped, When passing the argument restart, Stops manage_my_process, Deletes the file /var/run/my_process.pid, Starts manage_my_process, Creates a file containing its PID in /var/run/my_process.pid, Displays manage_my_process restarted, Displays Usage: manage_my_process {start|stop|restart} if any other argument or no argument is passed
Repo: GitHub repository: alx-system_engineering-devops, Directory: 0x05-processes_and_signals File: 101-manage_my_process, manage_my_process
Task 11. Zombie
-----------------------------------------------------------------------------------------------------------------------------¬-
Write a C program that creates 5 zombie processes. For every zombie process created, it displays Zombie process created, PID: ZOMBIE_PID. Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl. When your code is done creating the parent process and the zombies, use the function bellow
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x05-processes_and_signals File: 102-zombie.c
 
