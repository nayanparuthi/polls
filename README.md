# Polls
A website application where:
1. Logged in users can create polls that can be public or private
2. Public polls can be voted by non-logged in users
3. Private polls need login for voting
4. Both Public and private polls can be seen on the homepage.

Design of a poll:
A poll has a question, and any number of options. Voting on any option will display the results of the poll.

# Download files
https://github.com/nayanparuthi/polls
# Set Xampp Server
# Import file to phpmyadmin 
polls.sql
# Install Python3
# Install Requirements:
Open command prompt and locate to the folder where this file exists and push this command

pip install -r requirements.txt
# set the FLASK_APP and FLASK_DEBUG variables
set FLASK_APP=application.py

set FLASK_DEBUG=1
# Finally run with

flask run

Now if we visit 127.0.0.1:5000 ,we should see our application

