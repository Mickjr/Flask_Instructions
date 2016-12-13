###################
<h1> Flask Instructions </h1>
###################

<pre> These are instructions on setting up the flask environment using a Mac</pre>

###################
<h2> Install Flask Environment</h2>
###################

<pre>Last login: Wed Aug 20 11:24:50 on ttys000
Antonios-MacBook-Pro-7:~ A_Figueroa$ cd /Applications/MAMP/htdocs 
Antonios-MacBook-Pro-7:htdocs A_Figueroa$ mkdir flaskenv
Antonios-MacBook-Pro-7:htdocs A_Figueroa$ cd flaskenv
Antonios-MacBook-Pro-7:flaskenv A_Figueroa$ sudo easy_install virtualenv
Password:
Searching for virtualenv
Best match: virtualenv 1.11.6
Processing virtualenv-1.11.6-py2.7.egg
virtualenv 1.11.6 is already the active version in easy-install.pth
Installing virtualenv script to /usr/local/bin
Installing virtualenv-2.7 script to /usr/local/bin

Using /Library/Python/2.7/site-packages/virtualenv-1.11.6-py2.7.egg
Processing dependencies for virtualenv
Finished processing dependencies for virtualenv
Antonios-MacBook-Pro-7:flaskenv A_Figueroa$ virtualenv venv
New python executable in venv/bin/python
Installing setuptools, pip...done.
Antonios-MacBook-Pro-7:flaskenv A_Figueroa$ . venv/bin/activate
(venv)Antonios-MacBook-Pro-7:flaskenv A_Figueroa$ sudo pip install flask</pre>

###################
<h2> Flask Run File </h2>
###################

<pre>(venv)Antonios-MacBook-Pro-7:flaskenv A_Figueroa$ ls
test.py venv
(venv)Antonios-MacBook-Pro-7:flaskenv A_Figueroa$ python test.py
Test
(venv)Antonios-MacBook-Pro-7:flaskenv A_Figueroa$</pre>

