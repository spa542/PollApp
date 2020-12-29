# Poll App
# Author: Ryan Rosiak
<br /> <br />
## Project Description:
This project is a command line polling app (similar to straw poll). The program uses PostgresSQL to manage 2 large databases including open polls, options, and votes. The entire
database is managed and accessed using the object oriented approach and allows users to create polls, vote on existing polls, and select winners for polls based off tallied
votes. Some interesting features included are analytics for each poll as well as timestamps for when votes are submitted.
<br /> <br />
## Dependencies:
"These are specified in requirements.txt but will also specified below
* psycopg2-binary
* python-dotenv
* pythong 3.6 or greater
## To Install Dependencies:
"pip3 install (dependency listed above)"
<br /> <br />
## How to Run:
To run this program, you simply must run the app.py script. There will be a .env.example file provided if you would like to enter the DATABASE_URL in that file instead of on 
the spot command line. Once the DATABASE_URL is registered, the menu will appear and full use of the app will be available. (This app was tested using a free PostgresSQL service
called ElephantSQL)
<br /> <br />
## Sample Execution:
"python3 app.py"
<br /> <br />
## Current Issues
There are no known issues for this program.
