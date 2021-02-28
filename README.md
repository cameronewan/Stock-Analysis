# Stock-Analysis
## Overview of Project
For this project Steve wanted us to create a workbook that was capable of analyzing data about certain stocks at the click of a button. Once we did that we were interested in finding out if we could produce the same outcome for the entire stock market. We did this by refactoring the code we wrote for Steve. We were interested in seeing if we refactored our code to loop through the entire dataset once if our runtime would be faster or not.
## Results
What we can conclude after refactoring our code is that the run time did decrease for both 2018 and 2017. This was possible because in our new refactored code there were less steps that had to be done by the computer. Essentially, we made our code more efficient. The first two images that can be seen here are from our original script, and the second two our from our refactored code.<img width="425" alt="Screen Shot 2021-02-23 at 1 57 40 PM" src="https://user-images.githubusercontent.com/75695931/109437239-c4c11700-79f1-11eb-9706-5f3f37559a04.png">
<img width="415" alt="Screen Shot 2021-02-28 at 5 16 56 PM" src="https://user-images.githubusercontent.com/75695931/109437240-c559ad80-79f1-11eb-81a1-35deb2e8d2ed.png">.<img width="418" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/75695931/109437178-8592c600-79f1-11eb-909b-39a5c54d9f67.png"> <img width="418" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/75695931/109437173-8166a880-79f1-11eb-888b-88ce5348f54c.png">. 
If we were to compare our original code with our refactored code we wold see some subtle differences, but it is exactly those differences which allow our refactored code to run faster.
### Orignal 
<img width="691" alt="Screen Shot 2021-02-28 at 6 34 33 PM" src="https://user-images.githubusercontent.com/75695931/109437722-5a5da600-79f4-11eb-8356-89ba950bd09e.png">
## Refactored
<img width="784" alt="Screen Shot 2021-02-28 at 6 34 14 PM" src="https://user-images.githubusercontent.com/75695931/109437725-5b8ed300-79f4-11eb-811c-3cfb632faf7a.png">
Another part of the data that we can compare is the returns for the stocks we analyzed. We can see that all but one of the stocks in 2017 (TERP) had positive returns. However, in 2018, all the stocks but two (ENPH & RUN) had negative returns suggesting that in 2018 the stock market was not as good to invest in as it was in 2017. 

<img width="292" alt="Screen Shot 2021-02-23 at 4 43 34 PM" src="https://user-images.githubusercontent.com/75695931/109437291-271a1780-79f2-11eb-8280-3a58af34aef0.png">
<img width="306" alt="Screen Shot 2021-02-28 at 5 18 03 PM" src="https://user-images.githubusercontent.com/75695931/109437292-27b2ae00-79f2-11eb-8984-eaa0a7e89f21.png">

## Summary
### Advantages and disadvantages of refactoring code in general.
Like anything else there are pros and cons to refactoring code. Some pros include, peer review, improving the code, and bug fixes all of which are importance steps in create a good clean code. Have someone else look at your code can always be beneficial because they might see something you do not. Also as we saw in our challenge for this week, if we can made our code run faster than we should. Cons, if you refactor code that does not need to be refactored you might end up causing more problems than you solve. This might end up with you creating bugs in the code. It can also be very time consuming if you are working with a long and messy code which is why refactoring should be done in the early stages.  

### Advantages and disadvantages of the original and refactored VBA script.
What was great about our original script is that it works, and it works well which is almost most important. We know that for the stock we wanted to analyze for Steve that it worked. However, one of the disadvantages was that it was not the fastest run time that we could get, and it was not looping through all the stocks. This is where our refactored code was better because not only did loop through all the stocks, but it did so in a quicker amount of time. One disadvantage that I ran into when refactoring my code was that there were many more bugs that I had to sort out as I went compared to our original code. This is exactly why refactoring working code may not always be the best idea. 

