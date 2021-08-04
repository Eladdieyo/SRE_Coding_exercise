# SRE_Coding_exercise
Comic ID Scraper
This will serve as rhe README for the HTML Scraper that will be generated using the Python coding language. THe challenge, solution, and any release notes will be found within this repository. 
Instructions on the challenge can be found in the SRE_Coding_Interview attachment that can be found within the repo. 

Step 1: 
Setting up the environment. 
First:
Change over to Z shell by running the following command:
chsh -s /bin/zsh

Install homebrew using this command:
curl https://docs.brew.sh/Installation

Run command:
brew list

if you do not have Python in the list you need to install python using the command:
brew install python

Python 3.9 should be installed.

To check installation type python3 to enter interactive shell and paste print ("hello") and press enter. If it says hello back to you, you are on the right path. If not, go over the previous steps until you get to this point. to exit out of the shell use Control + z

Next, you will need to make sure you are using the correct version of pip. 
Use the command: "pip3 list" to see what libraries have been installed. If you do not have beautiful soup 4 (which you should not have yet) use the command: "pip3 install bs4" to install beautiful soup 4. You should receive a successful installation message. 

Now that we have the library installed, we need to create a web scraper.You typically use web scrapers to search and capture code that we are looking for specifically within a certain web page. 

For this particular exercise I will be using VS Code with the Python Extension. My local machine is a Mac. 
