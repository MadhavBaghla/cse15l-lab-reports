# WEEK 4 LAB REPORT

1.) Log into ieng6:
Type ```history``` in terminal and copy paste ur ssh login command

<img width="679" alt="Screenshot 2023-02-27 at 8 10 47 AM" src="https://user-images.githubusercontent.com/122570270/221735022-1d0f7833-4e2b-45a5-bfc3-9d5fa339db12.png">

2.)Clone your fork of the repository from your Github account:
Type ```git clone <repository link>``` and ```<enter>```

<img width="677" alt="Screenshot 2023-02-27 at 8 12 39 AM" src="https://user-images.githubusercontent.com/122570270/221735421-1ee6f3e9-7b28-4d9f-99fe-54d78c9f7318.png">

3.)Run the tests, demonstrating that they fail:

Ctrl+V-->javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java

```<enter>```

java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests

```<enter>```


<img width="982" alt="Screenshot 2023-02-27 at 8 21 41 AM" src="https://user-images.githubusercontent.com/122570270/221735710-751139ff-1a18-4043-94e5-7d489927d125.png">

4.)Edit the code file to fix the failing test

Type git nano List ```<tab>``` and Edit your code in nano by using ```<down>``` to reach the part of the code which had errors.
Keys entered:```<down><down><down><down><down><down><down><down><down><down><down><down><down><right><right><right><right><right><right><right><right><right><right><right><right><right><right><right><right><right><right><right><right>``` 
and then type in the modified code.

Ctrl+O to save

Ctrl+X to exit

<img width="982" alt="Screenshot 2023-02-27 at 10 39 28 AM" src="https://user-images.githubusercontent.com/122570270/221736034-1db3c8b4-eef2-4fb0-a130-1b502b7c0da8.png">

<img width="1004" alt="Screenshot 2023-02-27 at 10 39 52 AM" src="https://user-images.githubusercontent.com/122570270/221736193-66e6bf49-637e-4b02-855c-deac5a5cd5fd.png">

5.)Run the tests, demonstrating that they now succeed

After saving the changes and exiting nano, ```<up><up><up>``` to run the Junit tests again 
 
OR

Ctrl+V-->javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java

```<enter>```

java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests

```<enter>```



<img width="982" alt="Screenshot 2023-02-27 at 10 39 28 AM" src="https://user-images.githubusercontent.com/122570270/221737334-3e911c70-261a-4760-979f-6968d93bf01e.png">

6.)Commit and push the resulting change to your Github account

Type ```git add ListExamples.java```, then 
```git commit -m"Updated"```, then
      ```git origin push main``` 

<img width="524" alt="Screenshot 2023-02-27 at 6 07 24 PM" src="https://user-images.githubusercontent.com/122570270/221737916-8cdb19ad-2b02-4487-a345-c8918dace690.png">




        

