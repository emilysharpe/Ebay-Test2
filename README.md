# Webscraping Set Up Tutorial

In this tutorial you are going to learn how to set up your computer for python webscraping. We will cover all 3 major operating systems. If you run into any problems you can reach me at kam@glance.ai or my preferred way of communication via Facebook Messenger at http://m.me/kameron.kales

## Watch this Tutorial on [YouTube](http://go.glance.ai/Sourcers-Who-Code-Tutorials)

### Mac OS:
The following instructions will only work for Mac. 

## Table of Contents.

Some of this will not make sense to start. Just trust me :) 

1. Learn to use Terminal/Command Prompt
2. Install XCode
3. Install Python 2.7
2. Install Text Editor (Sublime)
3. Install PIP
4. Install GIT
5. Register for a GitHub Account
6. Clone a repository
7. Start scraping!


## Step 1: Learn to use Command Prompt/Terminal
The command prompt/terminal is the best way to get your computer to do what you want. On Mac, it is called terminal. On Windows, it is called Command Prompt. They are the same thing. 

Find Terminal-

Navigate to your Applications tab and search for "Terminal" . Open Terminal. Don't lose this tab. You will love the terminal once you learn how to use it.

If you are feeling adventurous I would strongly recommend installing iterm2. It will replace your terminal and adds a lot of great features like copy and paste among others. Here is the link to install. 

Download [HERE](http://www.iterm2.com/)

## Step 2: Install XCode from App Store
This is mandatory. There is no way to progress without completing this step. It is also possible you will need to update your OS with Apple prior to completing this step. If so, plug your laptop in and go to sleep. That will take awhile.

* Navigate to App Store on your Mac

* Search XCode

* Install.

## Step 3: Install Python 2.7
Python might already be installed on your machine. To check this we are going to use the terminal. So, hopefully you still know where it is :)

* Navigate to Terminal

* Type python into the terminal. You should get a result like this. 

![Python Interpreter](/pictures/mac/check_python_version_on_mac.png)

You can tell which version of python you have by the top line. I have python 2.7.10. As long as you have 2.7 something everything will work :)

* If your terminal does not respond in this way, it most likely means you do not have python installed. Let's fix that.

* Run the following code in your terminal. Run each snippet by itself. Do not copy and paste all 4 into your terminal and hit enter. Copy and paste each one individually and hit enter to run it.

``ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
``

``brew doctor
``

``brew update
``

``brew install python
``

## Step 4: Install Text Editor (Sublime)
Navigate to [Sublime](http://www.sublimetext.com/3) to download. Click the OS X Button shown below.

![Sublime](/pictures/mac/os_x_sublime.png)

* Navigate to your downloads and double click the Sublime Text Build 31....dmg file to open and install it. After it installs, I recommend moving the download to your Applications folder. 


## Step 4: Install PIP
It is possible while doing this step you will see errors. If that happens please add sudo to the front of the command below.

* Type the following command in your command prompt.

``easy_install pip
``

* If you run into this error, please run this line of code instead 

``sudo easy_install pip
``

## Step 5: Install GIT
Is is possible GIT is already installed on your computer. We will check prior to reinstalling. 

Run this code in your command prompt to check if you have GIT

``git --version
``

If you see a version number printed out, you can progress onto Step 6. If you do not, continue below.

``brew install git
``

## Step 6: Register for a Github Account
Registering for a github account is incredibly useful. For the purpose of this video series alone, it will make your life 100x easier. 

Navigate to [Github](http://github.com)

Complete the sign up form shown below and confirm your email. 

![Github](/pictures/github.png)

Using Github enables you to store your code much like you store files with Google Drive. It also enables you to easily copy the code I write and run it in the same way I wrote it. 

You should choose the free account for our purposes. You will not need the additional features of a paid account. 

Answer the basic questions after declining the paid account and navigate to your profile page. The top right corner has an icon to click and dropdown a menu to view your profile. 

![Profile](/pictures/github_account.png)

## Step 7: Clone a Repository
Cloning a repository means to make a copy of it and bring it onto your computer to use. 

* Navigate to your command prompt and type 
``CD``

* Next, type 
``CD Desktop`` 

* Next, type 
``mkdir Projects``

* Next, type 
``CD Projects`` 
to switch into the projects folder. 

* Now, we are going to clone the repository.

* Click [HERE](https://github.com/KameronKales/Sourcers-Who-Code-Scraping-Tutorial-by-Glance) to open the repo.

* Find the green clone or download button on the right. You can check below for a screenshot example.

![Repo](/pictures/github_clone_repo.png)

* Click the green button and copy the url in the clone with git box. You can check below for a screenshot example.

![Git Clone](/pictures/clone_with_git.png)

* Navigate to your command prompt again and type 

``git clone https://github.com/KameronKales/Sourcers-Who-Code-Scraping-Tutorial-by-Glance.git ``

* Now, type the following

``CD Sourcers-Who-Code-Scraping-Tutorial-by-Glance/``

* Congratulations! You now have the full repository of code on your computer!! I'd suggest you have a drink or a nap, whatever is your cup of tea because that was the bulk of the hard part. 

## Step 8: Navigate to Repo and Run Scraper
Now that you have cloned the code above onto your computer (often referred to as a machine) you can run the web scraper!

* Navigate to your command prompt once again.

* Confirm you are inside the Sourcers-Who-Code-Scraping-Tutorial-by-Glance/ folder. If you are not do the following:

``CD``
``CD Desktop``
``CD Projects``
``CD Sourcers-Who-Code-Scraping-Tutorial-by-Glance/ ``

* Now that you are inside the directory we need to open your code. 

* Navigate to your Applications folder and select Sublime. Double click it to open. 

* Click the menu bar at the top where it says File (much like Microsoft Word) and scroll down to the Open option. Click that.

* Navigate to Desktop on the pop up and then into Projects.

* Select Sourcers-Who-Code-Scraping-Tutorial-by-Glance/ like shown below and click Open. Ensure your cursor is like the example below and all of the files open. 

![Select Files](/pictures/mac/open_repo.png)


* Once your files open on Sublime you can navigate around. I suggest starting with the Readme to learn about the repository. 

* The Readme should include steps to get started with the project under Getting Started and Installation. 

* Happy Scraping!


### Windows OS:
The following instructions will only work for Windows 10 Operating System. 

## Table of Contents.

Some of this will not make sense to start. Just trust me :) 

1. Learn to use Terminal/Command Prompt
2. Install Python 2.7
3. Install Text Editor (Sublime)
4. Install GIT
5. Register for a GitHub Account
6. Clone a repository
7. Start scraping!

## Step 1: Learn to use Command Prompt/Terminal
The command prompt/terminal is the best way to get your computer to do what you want. On Mac, it is called terminal. On Windows, it is called Command Prompt. They are the same thing. 

Find Terminal-

Navigate to your Desktop view tab and search for "Command Prompt" . Open Command Prompt. Don't lose this tab. You will love the command prompt once you learn how to use it.


## Step 2: Install Python 2.7
Python might already be installed on your machine. To check this we are going to use the terminal. So, hopefully you still know where it is :)

* Navigate to Command Prompt

* Type python into the command prompt. You should get a result like this. 

![Python Interpreter](/pictures/mac/check_python_version_on_mac.png)

You can tell which version of python you have by the top line. I have python 2.7.10. As long as you have 2.7 something everything will work :)

* If your terminal does not respond in this way, it most likely means you do not have python installed. Let's fix that.

* Navigate to this website [Install Python](https://www.python.org/downloads/release/python-2713//)

* Click the download Windows x86-64 MSI installer option. View the attached screenshot to confirm you are installing the right software.

![Download Python](/pictures/windows/Download_python.png)

* Select the following permissions shown in the screenshot below!

![Permissions For Python](/pictures/windows/Python_permissions.png)

* Ensure you select the options shown in the screenshot below!!!!! 

![Options for Python](pictures/windows/Python_loader.png)

* Congrats! You have now installed Python. Next, you should close out your Command Prompt and Re-open it. This is not entirely neccessary but in my experience restarting it after installing is best.

* You might notice the Mac guide above has a different Step 4 where we install pip. Luckily for you, Pip auto-installs with Python. 

## Step 4: Install Text Editor (Sublime)

* Navigate to [Sublime](https://www.sublimetext.com/3) to download. Click the Windows 64 bit Option shown below.

![Sublime](/pictures/windows/Windows_download_sublime.png)

* Double click the download once it completes to fully install. You should now be able to search your desktop for SublimeText3.


## Step 4: Install GIT
Is is possible GIT is already installed on your computer. We will check prior to reinstalling. 

Run this code in your command prompt to check if you have GIT

``git --version
``

If you see a version number printed out, you can progress onto Step 5. If you do not, continue below.

* Navigate your browser to [GIT](https://git-scm.com/download/win)

* Your download should automatically start. Once it is complete double click and click through all of the menus. The stock options will be all you need.

* Thanks to [Glenn Gutmatcher](https://www.linkedin.com/in/gutmach/) for pointing out a few possible errors while completing this step! 

* After Git installs, if you get an error when Gitbash first tries to self-launch of: Bash: fork: Resource temporarily unavailable

* Just close that window, and back in regular Windows command prompt window, type: 

``git --version
``

And it should show that you have Git now. 

* Congrats you have installed GIT!

## Step 5: Register for a Github Account
Registering for a github account is incredibly useful. For the purpose of this video series alone, it will make your life 100x easier. 

Navigate to [Github](http://github.com)

Complete the sign up form shown below and confirm your email. 

![Github](/pictures/github.png)

Using Github enables you to store your code much like you store files with Google Drive. It also enables you to easily copy the code I write and run it in the same way I wrote it. 

You should choose the free account for our purposes. You will not need the additional features of a paid account. 

Answer the basic questions after declining the paid account and navigate to your profile page. The top right corner has an icon to click and dropdown a menu to view your profile. 

![Profile](/pictures/github_account.png)

## Step 7: Clone a Repository
Cloning a repository means to make a copy of it and bring it onto your computer to use. 

* Navigate to your command prompt and type 
``CD``

* Next, type 
``CD Desktop`` 

* Next, type 
``mkdir Projects``

* Next, type 
``CD Projects`` 
to switch into the projects folder. 

* Now, we are going to clone the repository.

* Click [HERE](https://github.com/KameronKales/Sourcers-Who-Code-Scraping-Tutorial-by-Glance) to open the repo.

* Find the green clone or download button on the right. You can check below for a screenshot example.

![Repo](/pictures/github_clone_repo.png)

* Click the green button and copy the url in the clone with git box. You can check below for a screenshot example.

** Note: When you are on Github and there’s a folder you want and you click the green Clone or Download button, then click the icon to the right of the URL path which copies it to clipboard (as shown in video).

![Git Clone](/pictures/clone_with_git.png)

* Navigate to your command prompt again and type 

* Note: You cannot simply ctrl+v to paste the URL (or anything) in a Windows command prompt! Instead, you’ll need to hit the Alt key and Space bar simultaneously, then E (edit), then P (paste)

``git clone https://github.com/KameronKales/Sourcers-Who-Code-Scraping-Tutorial-by-Glance.git ``

* Bonus Points: if that was relatively easy for you, you might want to try one of the fancier solutions [HERE](https://www.howtogeek.com/howto/25590/how-to-enable-ctrlv-for-pasting-in-the-windows-command-prompt/?fref=gc&dti=298375607242234)

* Now, type the following

``CD Sourcers-Who-Code-Scraping-Tutorial-by-Glance/``

* Congratulations! You now have the full repository of code on your computer!! I'd suggest you have a drink or a nap, whatever is your cup of tea because that was the bulk of the hard part. 

## Step 8: Navigate to Repo and Run Scraper
Now that you have cloned the code above onto your computer (often referred to as a machine) you can run the web scraper!

* Navigate to your command prompt once again.

* Confirm you are inside the Sourcers-Who-Code-Scraping-Tutorial-by-Glance/ folder. If you are not do the following:

``CD``
``CD Desktop``
``CD Projects``
``CD Sourcers-Who-Code-Scraping-Tutorial-by-Glance/ ``

* Now that you are inside the directory we need to open your code. 

* Navigate to your Desktop folder and search for SublimeText3. Open it. 

* Click the menu bar at the top where it says File (much like Microsoft Word) and scroll down to the Open option. Click that.

* Navigate to Desktop on the pop up and then into Projects.

* Select Sourcers-Who-Code-Scraping-Tutorial-by-Glance/ like shown below and click Open. Ensure your cursor is like the example below and all of the files open. 

![Select Files](/pictures/windows/Windows_select_repo.png)

* Once your files open on Sublime you can navigate around. I suggest starting with the Readme to learn about the repository. 

* The Readme should include steps to get started with the project under Getting Started and Installation. 

* Happy Scraping!