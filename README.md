# imdb-scrapper

### Getting started  

This script scrapes imdb to fetch information about TV series.  
Also deals with mailing this info to the user_email account mentioned.
  
#### Prerequisite
Follow the following steps to get your script running:-  
  * you need to have python installed in your local machine.  
  * Download the zip file of this repositiory and extract it.  
  * connecting to database - open [**savetodb.py**](https://github.com/shubham-tin/imdb-scrapper/blob/master/savetodb.py)  
    enter your database credentials.  
    ```   
          host="localhost",  
          user="user",  
          passwd="*****",  
          db="tvseries"  
      ```    
    > 'import mysql.connector' ...install module if not present.  
    
  
  * Before running make small change to [**'mailing.py'**](https://github.com/shubham-tin/imdb-scrapper/blob/master/mailing.py) file.  
  * Enter your account credentials:- **username** and **password** and then save the file  
  <img src="https://github.com/shubham-tin/imdb-scrapper/blob/master/crendentials.png" alt="image" height="200px" width="400px"/>
  
  * cd to the repo folder from command line.  
  * Then from the command line  --->
  > **run > python imdbscrapper.py**  
  
  



