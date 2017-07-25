This practice was certainly more challenging than the prvious text conversion practice. This was because the two scripts that we wrote to execute the commands had a more sophisticated struture and also they contained some new elements such as defining a unique identifier and time stamp. The second script was even more complicated and although now I understand the logic of what is in there, I could not have written it without looking at John's script and his explanations!  

 The [first script](https://github.com/sepideharc/task-4-data/blob/master/data-script.sh):  
 
 * First I created a list of five questions.    
    I wrote the first script that when you run it will do the following:  
   - Ask each question of the user running the script.  
   - Write a random string of characters to a variable as a unique identifier.  
   - Write the datestamp to a variable.  
   - Accept text input from the user and write each answer as a variable.  
   - Save all answers and other data to a [CSV file](https://github.com/sepideharc/task-4-data/blob/master/data-backup.csv).    
   
 *To gather some data I answered the questions twice (John also kindly answered the questions)in order to create a database that has the appropriate variables and variable types.  
 The [second script](https://github.com/sepideharc/task-4-data/blob/master/write-to-db.sh) to automate transfering data to SQL:
  I wrote the second script (With major help from John) to write my data into a MySQL database.  
  I had to Run this script after collecting data in the data backup.csv file.  
  To begin the script I Set MySQL credentials and  then copy everything in backup into temp in the SQL. I Get to my SQLWrite data from    tmp.csv into database table. Then dump current version of database into export file and lastly removed the temporary file.  
   
   This was challenging but *fun* and *satisfying* when you see it run!
