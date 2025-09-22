# Times-Tables-Game
A simple times tables practise game. You can try it online [here](https://dado-dev.github.io/Times-Tables-Game/).
## Interface
### Question
The current question is displayed underneath the title.  
The quesition will be in the format `2 x 3`, where `x` refers to multiply.  

Each question is generated based on the two pools of numbers.
### Score
Your "score" is displayed underneath the current question in both **fraction** and **percentage** form.  
They both show `correct answers / total questions answered`
### Options
For every question, there are four options. One of which is **correct**; others similar, but **incorrect**.  
Each option is displayed in a **large green box**.  

Click on the disired option to submit it as your answer for the current question.
### Outcome
The outcome of the last question is displayed between the score and the options.  
*Note: the outcome won't be visible if you are on the first question.*  

If you answered the previous question **correctly**, the outcome text will display `Correct!` in **green** text.  
If you instead answered **incorrectly**, the outcome text will display `Incorrect!` in **red** text.  
As well as this, it will display the **correct** answer to the previous question in the form `2 x 3 is 6`.
### Pools
The **pools** are displayed underneath the options.  
They determine which numbers will be picked from when generating the next questions.  

The pools contain options for all numbers **1-12**, as this is the standard in most schools.  

To the right of each pool, is a **toggle all** button.  
This button - as expected - will toggle all of the options in that pool.
