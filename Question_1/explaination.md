1. `whoami`

   - **Explanation:** I ran this command to display my current effective user ID. It confirmed that I am logged in as the user **omteja**.

2. `groups`

   - **Explanation:** This command prints the groups a user belongs to. The output verified that my user belongs to the **omteja** and **users** groups.

3. `echo $SHELL`

   - **Explanation:** By echoing the SHELL environment variable, I verified the command-line interpreter in use. The output showed **/bin/bash** as my current shell.

4. `pwd`

   - **Explanation:** This command prints the absolute path of the current working directory. It confirmed that I was operating within my home directory, **/home/omteja**.

5. `ls -ls`

   - **Explanation:** This command lists the directory contents along with their sizes and permissions. The output showed that the current working directory is empty and does not contain any files or folders.

6. `ping -c 4 google.com`

   - **Explanation:** This command sent four ICMP echo requests to Google to test external network connectivity. It returned four successful replies with **0% packet loss**, confirming that the system is connected to the internet.
