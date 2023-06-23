Attack is the best defense
--------------------------------------------------------------------------------------------------
Learning Objectives: Network basics, Docker  Tools: wireshark, telnet, tcpdump, docker hydra. Additional Resources: Network sniffing, ARP spoofing Connect to SendGrid’s SMTP relay using telnet What is Docker and why is it popular? Dictionary attack

#Tasks
-----------------------------------------------------------------------------------------------
0. ARP spoofing and sniffing unencrypted traffic
Repo: GitHub repository: alx-system_engineering-devops Directory: attack_is_the_best_defense File: 0-sniffing
1. Dictionary attack
Install Docker on your machine Ubuntu
Pull and run the Docker image sylvainkalache/264-1 with the command docker run -p 2222:22 -d -ti sylvainkalache/264-1
Find a password dictionary (you might need multiple of them)
Install and use hydra to try to brute force the account sylvain via SSH on the Docker container
Because the Docker container is running locally, hydra should access the SSH account via IP 127.0.0.1 and port 2222
Hint: the password is 11 characters long
Repo: GitHub repository: alx-system_engineering-devops Directory: attack_is_the_best_defense File: 1-dictionary_attack
