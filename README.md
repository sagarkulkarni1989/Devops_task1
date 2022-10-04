 ## Task 1: Git/GitHub
* git clone https://github.com/sagarkulkarni1989/Devops_task1.git
* git branch
* mkdir Tasks1
* cd Tasks1/
* touch README.md
* git add .
* git commit -m "added file"
* git push origin main
* git branch dev
* git checkout dev
* touch testfile.md
* git add .
* git commit -m "added file"
* git push origin dev
* git checkout main
* git branch %USERNAME-new_feature
* git checkout %USERNAME-new_feature
* git status
* git log
* touch ./Task1/README.md
* git status
* touch .gitignore
* vim .gitignore    add  .*
* cat .gitignore
* git add .
* git commit -m "added gitignore file"
* git push origin %USERNAME-new_feature
* git checkout sagar-new_feature
* echo "Devops certification" > README.md
* cat README.md
* git restore README.md
* git checkout main
* git merge dev
* git branch delete sagar-new_feature
* git push origin --delete sagar-new_feature
* # ## Task 2: AWS Cloud
Task 
1. Done
2. Done 
3. Done 
4. check SSH connection from your host to the created EC2: 
      1. ssh -i mydevopskey.pem ec2-user@15.207.71.250

5. ping and SSH passed from one instance to another and vice versa. Configure SSH connectivity:
	 - login to both instances using default username and create user in both instances
	 - create a user : Create ansadmin
	 - passwd ansadmin
	4. sudo su - ansadmin
	6. ssh-keygen
	7. ssh-copy-id ansadnin@targetinstance
 	8. ssh ansadmin@target machine public IP
6. Install web server- nginx
	1. sudo amazon-linux-extras list | grep epel
	2. sudo amazon-linux-extras enable epel
	3. sudo yum install epel-release
	4. sudo yum install nginx
	5. systemctl start nginx
	6. systemctl enable nginx
	7. systemctl status nginx
	8. nginx -v
	9. cd /usr/share/nginx/html
	10. cat /etc/os-release   OS information`
	11. vim index.html    - Add information`
	12. hit public ip to browser
