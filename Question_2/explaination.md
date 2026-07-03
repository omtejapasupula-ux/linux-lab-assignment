1. `umask`

   - **Explanation:** This command displays the current user file-creation mask. The output showed **0002**, meaning by default, write permissions are removed for "others" when new files or directories are created.

2. `mkdir -p project_workspace/docs project_workspace/code`

   - **Explanation:** I used the **-p** flag to create a parent directory (**project_workspace**) and two nested subdirectories (**docs** and **code**) simultaneously. This created the required project workspace structure.

3. `touch project_workspace/docs/design.txt`

   - **Explanation:** This command created a new empty text file named **design.txt** inside the **docs** directory. It serves as a placeholder for project documentation.

4. `ls -l project_workspace/docs/design.txt`

   - **Explanation:** This command displayed the permissions, owner, group, size, and other details of the newly created file. I observed the default permissions **-rw-rw-r--** applied according to the current **0002** umask.

5. `chmod 700 project_workspace/code`

   - **Explanation:** I modified the permissions of the **code** directory to **rwx------**. This allows only the owner to read, write, and execute the directory, improving its security.

6. `chown $USER:$USER project_workspace/docs/design.txt`

   - **Explanation:** This command sets the owner and group owner of **design.txt** to the current user (**omteja**). It ensures proper ownership of the project file.
