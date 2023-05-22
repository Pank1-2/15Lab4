# CSE 15l Lab Report 4 - Kiko Pan 
In this lab report I will reproducing steps 4-9 in Week 7's lab. 

## Part 1 (step 4) 
After opening the terminal, I logged into ieng6 by typing my log in username and then my password when it prompted me to do so. 
```ssh cs15lsp23ba@ieng6.ucsd.edu <Enter> ```
  After typing my password, I also clicked ```<Enter>```
 <img src = "Screen Shot 2023-05-22 at 11.29.42 AM.png" width = "750" height ="280">
 
 ## Part 2 (step 5) 
 In a previous step, I forked the lab7 repository on my github account. I copied the clone link from my github and ran ``` git clone https://github.com/Pank1-2/lab7.git <Enter> ``` on the terminal. 
 
 <img src = "Screen Shot 2023-05-22 at 2.00.22 PM.png" width = "500" height ="150">
 
 ## Part 3 (step 6) 
 Before I run the tests in the lab7 file, I want to go into the file first. To do that I ran ```cd lab7 <Enter>```. To run the tests, I ran ```sh ./test.sh <Enter> ```. There is a bug in the code causing a failure. 
 
 <img src = "Screen Shot 2023-05-22 at 11.55.20 AM.png" width = "650" height ="200">
 
 ## Part 4 (step 7) 
 In this step, I will be editing the code to make the tests run. To go into the file, I ran ```vim ListExamples.java <Enter>```. I then typed ```?ind <Enter>``` which brought me to the area that needs to be edited. Then I did ```<right><right><right><right><right>``` which brought my cursor on top of the number 1. I then clicked ```x``` which deleted the 1. To change it to index2 instead, I inserted a 2 by clicking ```i```. So, I did ```<i><1><ESC>```. Then, to save the changes, I did ```<Ctrl-C><:wq><Enter>``` which saved the changes and exited vim.
<img src = "Screen Shot 2023-05-22 at 12.19.11 PM.png" width = "450" height ="500">
  
## Part 5 (step 8) 
To see if my tests run after editing the code, I ran the same command from part 3. I did ```sh ./test.sh <Enter> ```. 
<img src = "Screen Shot 2023-05-22 at 12.20.23 PM.png" width = "600" height ="150">

## Part 6 (step 9) 
To commit and push changes onto my GitHub account, I first added the files I wanted to commit by running ```git add ListExamples.java <Enter>```. Then, just to check the status of my repository and my modified files, I ran ```git status <Enter>```. 
 <img src = "Screen Shot 2023-05-22 at 12.29.27 PM.png" width = "600" height ="250">
 
After checking the status, I began to commit the changes by running ```git commit -m "fixed ListExamples" <Enter>```. This command commits my changes and adds a little message about what I did. Then in order to fork the changes onto my GitHub account, I ran ```git push origin main <Enter> ```.

<img src = "Screen Shot 2023-05-22 at 1.49.42 PM.png" width = "600" height ="350">
 



 

