# Test Files for PHP

This repository contains two files to help determine if you have PHP installed and working on your system, and will familiarize you with the basics of PHP and running a backend server.

## How to Use

Once you have succesfully installed PHP on your computer, and have copied this repository onto your machine, you should be able to follow these steps to run your first PHP web page.

1. Open the CLI of your choice (e.g. Command Prompt, Git Bash) and navigate to the directory where you have placed or created the index.php and hello.php files.
2. Run the following command: `php -S localhost:8000` (Note: You can designate your port with a number other than 8000 if you need or wish to). If succesful, you should receive a message stating that the server is listening at the port you designated. 
3. Open a browser and enter the url for the port you designated in the previous step. The browser will read your index.php file as though it were an html file, while also being able to read and run any included php scripts. If succesful, your browser will display the success message produced by your PHP script in the index file.
4. In addition to rendering your index file, you can render other php files in your directory by navigating to their corresponding URLs. You should be able to display your Hello.php file in the browser by appending '/hello.php' to the url of your port. (e.g. http://localhost:8000/hello.php)
5. Finally, you can stop running your development server by closing terminal or inputing the appropriate exit prompt in your CLI.

Hopefully this guide will help familiarize you with the basics needed to understand how to begin developing with PHP.