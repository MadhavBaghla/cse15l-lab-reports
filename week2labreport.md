# Week 2 Lab Report

## Part 1
## Write a web server called StringServer that supports the path and behavior described below. It should keep track of a single string that gets added to by incoming requests.

1.The handlerequest method in our code is called.

2.`localhost:4000/add-message?s=my name jeff` is the argument it takes in Output 1 and `localhost:4000/add-message?s=I like rotissori chicken` is the argument it takes in Output 2.
   Ouput 1 takes the value `my name jeff` and output 2 takes the value `I like rotissori chicken`.

3.Value of the array stringarary is updated as it stores the string after '=' in the URL.

CODE

![](https://user-images.githubusercontent.com/122570270/215683581-2254b764-5dae-438e-b621-c543fa3ace74.jpeg)

OUTPUT 1

Method: handlerequest

Argument:localhost:4000/add-message?s=my name jeff

Value:my name jeff

Values changed:None

![](https://user-images.githubusercontent.com/122570270/215684026-f83a4493-edbc-43af-83eb-267128dc0f95.jpeg)

OUTPUT 2
Method: handlerequest

Argument:localhost:4000/add-message?s=I like rotissori chicken

Value:I like rotissori chicken

Values changed:None

![](https://user-images.githubusercontent.com/122570270/215685036-537c188a-fcb3-4744-8cfa-69921a31d5f0.jpeg)

## Part 2


1.Failure inducing inputs


<img width="629" alt="Screenshot 2023-01-30 at 11 06 47 PM" src="https://user-images.githubusercontent.com/122570270/215690468-3faf9231-2b1f-4d2c-9123-b78d89f02051.png">

2.Symptoms

<img width="624" alt="Screenshot 2023-01-30 at 11 07 27 PM" src="https://user-images.githubusercontent.com/122570270/215690480-90146d08-8e46-4af5-bf1a-109886d8b20a.png">
 
 3.Fixing the code
  
 <img width="367" alt="Screenshot 2023-01-30 at 11 18 46 PM" src="https://user-images.githubusercontent.com/122570270/215692807-0ddddbb7-c8fd-4b5b-ab91-6c4e232b67f8.png">


## Part 3

1.I learnt how to run a web server in lab.

2.I also learnt what a symptom is and how we can write tests to check the correctness of a program.

