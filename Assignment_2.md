1. Basic Playbook
Create a simple playbook that prints "Hello, World!" to the console.
Task: Use the debug module to display a message.
2. Install a Package
Write a playbook that installs the curl package on a target machine.
Task: Use the apt module for Ubuntu or the yum module for CentOS.
3. Create a Directory
Create a playbook that creates a directory named /tmp/my_directory on the target machine.
Task: Use the file module to ensure the directory is present.
4. Copy a File
Write a playbook that copies a file from the control machine to the target machine.
Task: Use the copy module to transfer a file.
5. Template a Configuration File
Create a playbook that uses a Jinja2 template to generate a configuration file.
Task: Use the template module to render a template file.
6. Manage a Service
Write a playbook that ensures the nginx service is installed and running.
Task: Use the service module to manage the service state.
7. User Management
Create a playbook that adds a new user named testuser to the target machine.
Task: Use the user module to create the user.
8. Run a Shell Command
Write a playbook that runs the command uptime on the target machine and captures the output.
Task: Use the command module to execute the command.
9. Setup a Cron Job
Create a playbook that sets up a cron job to run a script every day at 5 AM.
Task: Use the cron module to schedule the job.
10. Conditional Tasks
Write a playbook that checks if a file exists and performs actions based on that condition.
Task: Use the stat module to check for the file and conditionally use the copy module. 
11. Check Disk Space
Write a playbook that checks the disk space on the target machine and prints the output.
Task: Use the command module to run df -h and capture the output with the register keyword.
12. Backup a File
Create a playbook that backs up a specific file (e.g., /etc/hosts) to a backup directory.
Task: Use the copy module with the remote_src option to copy the file to a new location.
13. Install Multiple Packages
Write a playbook that installs multiple packages (e.g., git, vim, and htop) in one task.
Task: Use the apt or yum module with a list of packages.
14. Create a Virtual Environment
Create a playbook that sets up a Python virtual environment in a specified directory.
Task: Use the command module to run python3 -m venv /path/to/venv.
15. Download a File
Write a playbook that downloads a file from a URL to the target machine.
Task: Use the get_url module to fetch a file from the internet.
16. Set File Permissions
Create a playbook that changes the permissions of a file or directory.
Task: Use the file module to set the desired permissions (e.g., chmod 755).
17. Configure a Firewall
Write a playbook that configures the firewall to allow specific ports (e.g., HTTP and HTTPS).
Task: Use the ufw module for Ubuntu or firewalld for CentOS.
18. Create a Group
Create a playbook that creates a new group named devs on the target machine.
Task: Use the group module to create the group.
19. Remove a User
Write a playbook that removes a user from the target machine.
Task: Use the user module with the state: absent parameter.
20. Template a Systemd Service
Create a playbook that uses a Jinja2 template to generate a systemd service file.
Task: Use the template module to create the service file in /etc/systemd/system/. 
1. Create a Simple Inventory File
Write a static inventory file that lists a few hosts and their IP addresses.
Task: Create a file named inventory.ini with at least three hosts.
2. Basic Playbook Structure
Create a basic playbook that includes a name, hosts, and a simple task.
Task: Use the debug module to print a message indicating the playbook is running.
3. Install Apache Web Server
Write a playbook that installs the Apache web server on a target machine.
Task: Use the apt module for Ubuntu or the yum module for CentOS.
4. Start and Enable a Service
Create a playbook that starts and enables the Apache service to run on boot.
Task: Use the service module to manage the service.
5. Create and Write to a File
Write a playbook that creates a file and writes some text to it.
Task: Use the copy module with content to create a file.
6. Remove a File
Create a playbook that removes a specific file from the target machine.
Task: Use the file module with state: absent to delete the file.
7. Set Up a Simple Cron Job
Write a playbook that sets up a cron job to run a script every hour.
Task: Use the cron module to schedule the job.
8. Change File Ownership
Create a playbook that changes the ownership of a file to a specific user.
Task: Use the file module to set the owner.
9. Gather Facts About a Host
Write a playbook that gathers facts about the target machine and displays them.
Task: Use the setup module to collect facts.
10. Use Conditionals in Tasks
Create a playbook that checks if a package is installed and installs it if it is not.
Task: Use the package module with when conditions to control execution. 