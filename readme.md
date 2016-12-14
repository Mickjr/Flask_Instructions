###################
<h1> Flask Instructions </h1>
###################

<pre> These are instructions on setting up the flask environment using a Mac</pre>

###################
<h2> Install Flask Environment</h2>
###################

<pre>Last login: Wed Aug 20 11:24:50 on ttys000
Mantons-MacBook-Pro-7:~ M_Horton$ cd /Applications/MAMP/htdocs
Mantons-MacBook-Pro-7:htdocs M_Horton$ mkdir flaskenv
Mantons-MacBook-Pro-7:htdocs M_Horton$ cd flaskenv
Mantons-MacBook-Pro-7:flaskenv M_Horton$ sudo easy_install virtualenv
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
Mantons-MacBook-Pro-7:flaskenv M_Horton$ virtualenv venv
New python executable in venv/bin/python
Installing setuptools, pip...done.
Mantons-MacBook-Pro-7:flaskenv M_Horton$ . venv/bin/activate
(venv)Mantons-MacBook-Pro-7:flaskenv M_Horton$ sudo pip install flask</pre>

###################
<h2> Flask Run File </h2>
###################

<pre>(venv)Mantons-MacBook-Pro-7:flaskenv M_Horton$ ls
test.py	venv
(venv)Mantons-MacBook-Pro-7:flaskenv M_Horton$ python test.py
Test
(venv)Mantons-MacBook-Pro-7:flaskenv M_Horton$ </pre>
