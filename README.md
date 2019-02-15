# PHP Environment Setup

This repository contains two files to help determine if you have PHP installed and working on your system, and will familiarize you with the basics of PHP and running a backend server.

## How to Use

Once you have succesfully installed PHP on your computer, you should be able to follow these steps to run your first PHP web page. If you do not have PHP installed, please see the Troubleshooting and Resource sections for further guidance on setting up PHP on your machine.

1. For this first step, you can either attempt to create the php files you will be working with yourself, or you can clone/download this directory onto your machine. I personally recommend you view the two php files in this directory, and create them yourself on your machine to further reinforce your understanding of php and how it interacts with/relates to html.
2. Once you have the index.php and hello.php files on your machine, open the CLI of your choice (e.g. Command Prompt, Git Bash) and navigate to the directory where you have placed or created the files.
3. Run the following command: `php -S localhost:8000` (Note: You can designate your port with a number other than 8000 if you need or wish to). If succesful, you should receive a message stating that the server is listening at the port you designated. 
4. Open a browser and enter the url for the port you designated in the previous step. The browser will read your index.php file as though it were an html file, while also being able to read and run any included php scripts. If succesful, your browser will display the success message produced by your PHP script in the index file.
5. In addition to rendering your index file, you can render other php files in your directory by navigating to their corresponding URLs. You should be able to display your Hello.php file in the browser by appending '/hello.php' to the url of your port. (e.g. http://localhost:8000/hello.php)
6. Finally, you can stop running your development server by closing terminal or inputing the appropriate exit prompt in your CLI.

Hopefully this guide will help familiarize you with the basics needed to understand how to begin developing with PHP.

## Troubleshooting & Resources

As this guide is intended for first time PHP users, you may not be able to follow the steps above without running into an error or needing to do research. Please peruse the following section for resources or guidance that may help with your issues.

### How do I get started with a PHP installation?

There are generally 2 ways you can go about installing PHP on your machine. You can install PHP directly or you can install a pre-packaged stack of technologies which can prove to be easier and will help prepare you for developing more robust applications down the line. I recommend installing the stack.

#### Installing PHP as part of a stack (recommended)

When you first began researching PHP, you may have seen one of these following acronyms before: **LAMP**, **WAMP**, **MAMP**
In all three of these, the AMP stands for Apache, MySQL, and PHP. If you are unfamiliar, Apache is a web server software, MySQL is a database software. They are a vital part of many professional software stacks.
The first letter in the acronym's listed above refer to the operating system that the stack is designed to run on: L for Linux, W for Windows, and M for macOS.

**LAMP**
- If your machine is running on a Linux OS, search online for a stack appropriate to your operating system. The requirements and set up will likely vary depending on your machine

**WAMP**
- If you are running a Windows machine, WampServer is an easy and reliable tool for your first setup. It is what I personally set up as used for my php installation.
- Download Link: http://www.wampserver.com/en/#download-wrapper
- Handy Guide: https://www.makeuseof.com/tag/how-to-set-up-your-own-wampserver/

**MAMP**
- Despite the M in MAMP standing for MacOS, the MAMP installer is capable of building and installing its stack up on windows as well.
- Download Link: https://www.mamp.info/en/downloads/
- Handy Guide: https://www.taniarascia.com/local-environment/


#### Installing PHP on it's own
 
If you are not interested in setting up the stack, you can begin a manual installation process and follow guides at the following url from PHP's official website  http://php.net/manual/en/install.php
