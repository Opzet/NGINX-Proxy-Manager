<p align="center">
	<img src="https://nginxproxymanager.com/github.png">
	<br><br>
	<img src="https://img.shields.io/badge/version-2.11.1-green.svg?style=for-the-badge">
	<a href="https://hub.docker.com/repository/docker/jc21/nginx-proxy-manager">
		<img src="https://img.shields.io/docker/stars/jc21/nginx-proxy-manager.svg?style=for-the-badge">
	</a>
	<a href="https://hub.docker.com/repository/docker/jc21/nginx-proxy-manager">
		<img src="https://img.shields.io/docker/pulls/jc21/nginx-proxy-manager.svg?style=for-the-badge">
	</a>
</p>



## 3 Ways to install NGINX on Windows

### Introduction
NGINX, pronounced as ‘Engine-X’, is a powerful web server known for its high performance, stability, simple configuration, and low resource consumption. Although it’s originally developed for Linux, it’s possible to run NGINX on Windows systems as well. There are multiple ways you can install NGINX on Windows, each with its approaches and use cases. This guide provides a comprehensive look at several solutions for installing NGINX on a Windows environment.


### Approach 1: Official NGINX Windows Binary
NGINX offers an official pre-built Windows binary that is suitable for development and testing purposes. The official NGINX binaries are provided by the NGINX team and are compiled for Windows.

1.  Download the Windows version of NGINX from the official website, which can be found at nginx.org.
1.  Unzip the downloaded file to the desired location on your Windows machine.
1.  Open a Command Prompt with administrative privileges.
1.  Navigate to the directory where you unzipped NGINX and run the command start nginx.
1.  Confirm NGINX is running by accessing http://localhost in a web browser.

### Approach 2: Cygwin Environment
### Approach 3: Windows Subsystem for Linux (WSL)


- [Quick Setup](#quick-setup)
- [Full Setup](https://nginxproxymanager.com/setup/)
- [Screenshots](https://nginxproxymanager.com/screenshots/)

## Project Goal

Provide windows users with an easy way to accomplish reverse proxying hosts with SSL termination and it had to be so easy that a monkey could do it.

While there might be advanced options they are optional and the project should be as simple as possible
so that the barrier for entry here is low.

## Features

- Beautiful and Secure Admin Interface based on [Tabler](https://tabler.github.io/)
- Easily create forwarding domains, redirections, streams and 404 hosts without knowing anything about Nginx
- Free SSL using Let's Encrypt or provide your own custom SSL certificates
- Access Lists and basic HTTP Authentication for your hosts
- Advanced Nginx configuration available for super users
- User management, permissions and audit log

## Hosting Reverse Proxy on your network

1. Add port forwarding for port 80 and 443 to the server hosting NGINX
1. Use the Nginx Proxy Manager as your gateway to forward to your other web based services

## Quick Setup

This is the bare minimum configuration required. See the [documentation](https://nginxproxymanager.com/setup/) for more.

3. Bring up your stack by running

4. Log in to the Admin UI


When running, connect to it on port `81` for the admin interface.
Sometimes this can take a little bit because of the entropy of keys.

[http://127.0.0.1:81](http://127.0.0.1:81)

Default Admin User:
```
Email:    admin@example.com
Password: changeme
```

Immediately after logging in with this default user you will be asked to modify your details and change your password.

Documentation within the `develop` branch is available for preview at
[https://develop.nginxproxymanager.com](https://develop.nginxproxymanager.com)

### Contributors

Special thanks to [all of our contributors](https://github.com/NginxProxyManager/nginx-proxy-manager/graphs/contributors).


## Getting Support

1. [Found a bug?](https://github.com/NginxProxyManager/nginx-proxy-manager/issues)
2. [Discussions](https://github.com/NginxProxyManager/nginx-proxy-manager/discussions)
3. [Reddit](https://reddit.com/r/nginxproxymanager)
