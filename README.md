# SoftEggs
## Daniel Gelfand, Britni Canale, Tabassum Fabiha, Dennis Chen

## <b> How to install and run STORYTIME</b><br>
1) Use the following guide <a href="https://help.github.com/articles/cloning-a-repository/">here</a> to learn how to clone STORYTIME.

2) Ensure you have python3 and a virtual environment installed and activated before you run STORYTIME. Also make sure you have flask installed within your virtual environment. To learn how to set up a virtual environment, click <a href="https://stackoverflow.com/questions/41972261/what-is-a-virtualenv-and-why-should-i-use-one"> here</a>. To activate your virtual environment, enter the following commands:  
 ```console  
 foo@bar:~$ cd path  
 foo@bar:~/path$ . bin/activate  
 ```  
3) To install flask:
 ```console
 foo@bar:~/path$ pip install flask
 ```
 
4) Move to the newly clone repository and run the python file:
```console
foo@bar:~$ cd path
foo@bar:~/path$ python3 app.py
```
5) STORYTIME will be run on the machine's local IP address. This address will be available as a link in the terminal, or you can manually type it in as http://127.0.0.1:5000/.

6) For instructions on how to use the different features of the application, read "How to use STORYTIME" below.

7) To quit the app in the terminal, press `CTRL+C`<br><br>

## <b>How STORYTIME works</b><br>

STORYTIME is an interactive website where users can view, add to, and create new stories. In order to use STORYTIME, each user will be required to sign in or register. Users will be able to create any story, add to any story they haven't previously edited, and view any story they have previously edited.<br><br>

## <b> How to use STORYTIME </b><br>

### <b>Logging in:</b> 

To use STORYTIME, each user will be prompted to first login to the website. If they do not have an account, they will have the option to register for an account, and then will be prompted to log in after registering. If the user is already logged in and opens STORYTIME they will be immediately taken to the home page.<br>

### <b>Viewing stories:</b> 

On the home page, stories that the user has previously added to or created will be visible with all entries that were added prior to and after the user's entry. Stories that were previously edited by a user cannot be added to again by that user.<br>

### <b>Creating stories:</b> 

On the home page, there will be a button labeled "Create" that will take the user to a page where they can create a story. They can input a title and an entry to that story. If a story already exists with the title they input, they will be asked to choose a new title. After clicking the submit button, they will be taken back to the home page, where the new story will be visible along with any other stories the user has created or added to.<br>

### <b>Adding to stories:</b> 

On the home page, there will be search bar. The user can use this search bar to input the title of a story they know exists or any keywords related to a story. The search will take the user to a new page, where they will see any stories relating to their search. Then, the user can select a story to add to. If they do this, they will be taken to a page where they will see ONLY the most recent entry to the story. Beneath there will be a text area where they can input a new entry. After clicking submit, they will be taken back to the home page, where the new story will be visible along with any other stories the user has created or added to.<br>

### <b>Other shortcuts:</b> 

Each page after login will have a heading. The site name will be a link that will take the user back home from any other page they may be on. The search bar will be available on any page as well, along with the logout button. <br><br>
