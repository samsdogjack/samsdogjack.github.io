---
title: Setting up python virtual enviroment
date: 2023-08-09 11:11:11 -0500
catergories: [python, linux, mac os]
tags: [how-to, coding]
---

![alt text for screen readers](/images/python_logo.png "python")

## In this post we will look at how to set up a virtual enviroment in python.

### The folder that we will use will be a project folder for a upcoming project we can build and use the virtual enviroment to contain the libraries we will need to make it work.

### You can create a directory for this project any where you like but for this example we can use the home directory.

### Start with creating a folder. Open the terminal and from the home directory enter the command:
```
mkdir 'name_your_folder'
```

### After the folder in made you will change directory into the folder. Use the following command.
```
cd 'name_of_your_folder
```

### Once you are in the directory of the folder you created run this command.
```
python3 -m venv venv
```

### Now you can activate the enviroment.
```
source venv/bin/activate
```

### Now the project folder and virtual enviroment have been created and you are ready to start your project. When you are ready to leave the project you can simply type ```deactivate``` in terminal. The virtual enviroment will always be available to reactivate from your project folder.



