0x04. Loops, conditions and parsing
-----------------------------------------------------------------------------------------------------------------------------------Learning Objectives: How to create SSH keys, What is the advantage of using #!/usr/bin/env bash over #!/bin/bash? How to use while, until and for loops, How to use if, else, elif and case condition statements, How to use the cut command, What are files and other comparison operators, and how to use them
Requirement: Allowed editors: vi, vim, emacs, All your files will be interpreted on Ubuntu 20.04 LTS, All your files should end with a new line, A README.md file, at the root of the folder of the project, is mandatory, All your Bash script files must be executable, You are not allowed to use awk, Your Bash script must pass Shellcheck (version 0.7.0) without any error, The first line of all your Bash scripts should be exactly #!/usr/bin/env bash. The second line of all your Bash scripts should be a comment explaining what is the script doing

Task 0. Create a SSH RSA key pairCreate a RSA key pair
-----------------------------------------------------------------------------------------------------------------------------------
Requirements: share your public key in your answer file 0-RSA_public_key.pub, Fill the SSH public key field of your intranet profile with the public key you just generated, Keep the private key to yourself in a secure location, you will use it later to connect to your servers using SSH. 
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 0-RSA_public_key.pub

Task 1. For Best School loop
--------------------------------------------------------------------------------------------------------------------------------------
Write a Bash script that displays Best School 10 times. You must use the for loop (while and until are forbidden)
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 1-for_best_school

Task 2. While Best School loop
----------------------------------------------------------------------------------------------------------------------------
Write a Bash script that displays Best School 10 times. You must use the while loop (for and until are forbidden)
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 2-while_best_school

Task 3. Until Best School loop
--------------------------------------------------------------------------------------------------------------------------------------
Write a Bash script that displays Best School 10 times. You must use the until loop (for and while are forbidden)
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 3-until_best_school

Task 4. If 9, say Hi!
---------------------------------------------------------------------------------------------------------------------------
Write a Bash script that displays Best School 10 times, but for the 9th iteration, displays Best School and then Hi on a new line. You must use the while loop (for and until are forbidden), You must use the if statement
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 4-if_9_say_hi

Task 5. 4 bad luck, 8 is your chance
----------------------------------------------------------------------------------------------------------------------------
Write a Bash script that loops from 1 to 10 and: displays bad luck for the 4th loop iteration, displays good luck for the 8th loop iteration, displays Best School for the other iterations. You must use the while loop (for and until are forbidden). You must use the if, elif and else statements
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 5-4_bad_luck_8_is_your_chance

Task 6. Superstitious numbers
----------------------------------------------------------------------------------------------------------------------------
Write a Bash script that displays numbers from 1 to 20 and: displays 4 and then bad luck from China for the 4th loop iteration displays 9 and then bad luck from Japan for the 9th loop iteration displays 17 and then bad luck from Italy for the 17th loop iteration. You must use the while loop (for and until are forbidden). You must use the case statement
 Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 6-superstitious_numbers

Task 7. Clock
----------------------------------------------------------------------------------------------------------------------------
Write a Bash script that displays the time for 12 hours and 59 minutes: display hours from 0 to 12 display minutes from 1 to 59, You must use the while loop (for and until are forbidden) Note that in this example, we only display the first 70 lines using the head command.
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 7-clock

Task 8. For ls
------------------------------------------------------------------------------------------------------------------------------------
Write a Bash script that displays: The content of the current directory In a list format where only the part of the name after the first dash is displayed (refer to the example) You must use the for loop (while and until are forbidden) Do not display hidden files 
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 8-for_ls 

Task 9. To file, or not to file
--------------------------------------------------------------------------------------------------------------------------------------
Write a Bash script that gives you information about the school file. You must use if and, else (case is forbidden) Your Bash script should check if the file exists and print: if the file exists: school file exists if the file does not exist: school file does not exist, If the file exists, print: if the file is empty: school file is empty, if the file is not empty: school file is not empty, if the file is a regular file: school is a regular file, if the file is not a regular file: (nothing)
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 9-to_file_or_not_to_file

Task 10. FizzBuzz
-------------------------------------------------------------------------------------------------------------------------------Write a Bash script that displays numbers from 1 to 100. Displays FizzBuzz when the number is a multiple of 3 and 5, Displays Fizz when the number is multiple of 3, Displays Buzz when the number is a multiple of 5, Otherwise, displays the number In a list format
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 10-fizzbuzz
 
Task 11. Read and cut
----------------------------------------------------------------------------------------------------------------
help: read, Write a Bash script that displays the content of the file /etc/passwd. Your script should only display: username, user id, Home directory path for the user, You must use the while loop (for and until are forbidden)
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 100-read_and_cut

Task 12. Tell the story of passwd
-------------------------------------------------------------------------------------------------------------------------------
Write a Bash script that displays the content of the file /etc/passwd, using the while loop + IFS. Format: The user USERNAME is part of the GROUP_ID gang, lives in HOME_DIRECTORY and rides COMMAND/SHELL. USER ID's place is protected by the passcode PASSWORD, more info about the user here: USER ID INFO. You must use the while loop (for and until are forbidden)
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 101-tell_the_story_of_passwd 

Task 13. Let's parse Apache logs
------------------------------------------------------------------------------------------------------------------------------------Write a Bash script that displays the visitor IP along with the HTTP status code from the Apache log file. Format: IP HTTP_CODE in a list format You must use awk You are not allowed to use while, for, until and cut. Download and commit the apache-access.log file along with your answers files
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 102-lets_parse_apache_logs

Task 14. Dig the data
-----------------------------------------------------------------------------------------------------------------------------------
Using what you did in the previous exercise, write a Bash script that groups visitors by IP and HTTP status code, and displays this data. The exact format must be: OCCURENCE_NUMBER IP HTTP_CODEIn list format Ordered from the greatest to the lowest number of occurrences, You must use awk, You are not allowed to use while, for, until and cut
Repo: GitHub repository: alx-system_engineering-devops Directory: 0x04-loops_conditions_and_parsing File: 103-dig_the-data
