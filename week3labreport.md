# WEEK 3 LAB REPORT

## Command Line Options for the command 'find'
   Source for finding the commands:`man find` in terminal

## 1.-type
  i) `find / -type f`: This will display a list of all the files in the ./written_2 directory.
  
  <img width="788" alt="Screenshot 2023-02-13 at 3 27 03 PM" src="https://user-images.githubusercontent.com/122570270/218597349-ad1ea2ff-34a2-4b14-9d88-8bdd4d0a4921.png">
  
  ii) `find ./written_2 -type d`: This will display a list of all the directories in the ./written_2 directory.
  
  <img width="618" alt="Screenshot 2023-02-13 at 3 28 18 PM" src="https://user-images.githubusercontent.com/122570270/218597563-f50edba5-bdf4-4aac-985f-16e51765262d.png">

## 2.-size
   i) `find ./written_2 -type f -size +10k`:This will display a list of all the files in the ./written_2 directory that are larger than 10 kilobytes. 
   
   <img width="619" alt="Screenshot 2023-02-13 at 3 30 22 PM" src="https://user-images.githubusercontent.com/122570270/218597871-ce6825ac-c416-46b2-8839-006cf3f2dfbc.png">
   
   ii)`find ./written_2 -type f -size 100c`:This will display a list of all the files in the ./written_2 directory that are exactly 100 bytes in size.
   
   <img width="621" alt="Screenshot 2023-02-13 at 3 31 45 PM" src="https://user-images.githubusercontent.com/122570270/218598047-39c475e0-1d38-4ae8-bd3b-573a5a6d67a8.png">

## 3.-mtime
  i)`find ./written_2 -type f -mtime -7`:This will display a list of all the files in the ./written_2 directory that have been modified within the last 7 days.
  
  <img width="604" alt="Screenshot 2023-02-13 at 3 33 35 PM" src="https://user-images.githubusercontent.com/122570270/218598328-ebf5b783-f534-423b-9548-c4fc8fca738a.png">
  
  ii)`find ./written_2 -type f -mtime +10`:This will display a list of all the files in the ./written_2 directory that have been modified more than 10 days ago.
  
  <img width="607" alt="Screenshot 2023-02-13 at 3 34 36 PM" src="https://user-images.githubusercontent.com/122570270/218598455-fed04860-38e9-4305-9f89-6267fcf2fbfb.png">

## 4. -exec
  i)`find ./written_2 -type f -name "*.txt" -exec rm {} \;`:In this example, the -exec option is used to execute the rm command on each file that is found by the find command. The {} syntax is a placeholder for the current file being processed, and the \; is used to terminate the -exec option.
  
  <img width="626" alt="Screenshot 2023-02-13 at 3 37 12 PM" src="https://user-images.githubusercontent.com/122570270/218598756-06a58299-ad10-4096-9e1b-e23ba95446c3.png">

  ii)`find ./written_2 -type d -exec chmod 755 {} \;`:In this example, the -exec option is used to execute the chmod command on each directory that is found by the find command. The {} syntax is a placeholder for the current directory being processed, and the \; is used to terminate the -exec option.
  
  <img width="626" alt="Screenshot 2023-02-13 at 3 38 13 PM" src="https://user-images.githubusercontent.com/122570270/218598858-12f4867c-484d-4a4b-961c-161a74b99a9b.png">

  


