# Linux-Fundamentals-Project
# Introduction to Linux

## Project Overview
This project introduces Linux by setting up an Ubuntu server on AWS EC2, connecting via SSH using the Ubuntu terminal (WSL), and performing package management with `apt`. I installed, verified, updated, and removed `tree`, and explored `nginx`.

## Steps Taken

### Installation and Initial Setup
- Installed WSL and Ubuntu on Windows to use the Ubuntu terminal.
- Created an AWS EC2 Ubuntu Server (`t2.micro`).
- Connected to the server using SSH from the Ubuntu terminal (WSL):

- **Screenshot**: Successful SSH connection:

![SSH Connection](./img/ssh-%20ec2-connection.2.png)

![](./img/ec2%20instance%20creation.1.png)

### Package Management
- Updated package lists: sudo apt update

![](./img/Sudo-apt-update.3.png)

- Installed `tree`: sudo apt install tree
- Verified with:tree /home/ubuntu
- **Screenshot**: `tree` output:

![](./img/tree-insatllation-and-verification.4.png)
- Updated packages:sudo apt upgrade

![](./img/Sudo-apt-upgrade.5.png)

- Removed `tree`:sudo apt remove tree

![](./img/Remove-tree.6.png)

- Installed `nginx`:sudo apt install nginx
  sudo systemctl start nginx

![](./img/intall-nginx.7.png)

- Verified `nginx` status and accessed its welcome page.
- **Screenshot**: `nginx` status:

![Nginx Status](./img/nginx-status.8.png)

- **Screenshot**: `nginx` welcome page:

![Nginx Page](./img/nginx-web-page.9.png)

## Tools Used
- **Ubuntu Terminal (WSL)**: For SSH and package management.
- **VS Code**: For creating this documentation.
- **AWS EC2**: For hosting the Ubuntu server.
- **GitHub**: For hosting the documentation.

## Lessons Learned
- WSL enables Ubuntu terminal usage on Windows.
- SSH securely connects to remote servers.
- `apt` simplifies package management on Ubuntu.

## Repository Link
[GitHub Repository](https://github.com/westgrin/Linux-Fundamentals-Project)

## Conclusion
This project provided hands-on experience with Linux on a cloud server, using the Ubuntu terminal for all operations.
