# Suguna-K
Simple quiz application with MCQ questions

Created a multiple choice quiz using javascript,In this quiz,the user will have to choose the correct answer out of choices.If the user didn't answer the question within the time limit,it will go to next question automatically,and the question is marked as wrong.

To set up the structure of our JavaScript quiz, we’ll need to start with the following HTML:

A  <div> to hold the quiz
A  <button> to submit the quiz
A  <div> to display the results
  
We can then select these HTML elements and store references to them in variables like so:

const question = document.getElementById('quiz');
const quizscreen = document.getElementById('results');
const Button = document.getElementById('submit');

Next we’ll need to build a quiz, show results, and put it all together. 

We can start by laying out our functions, and we’ll fill them in as we go:

Here, we have functions to build the quiz and show the results. We’ll run our quizquestions function immediately, and we’ll have our resultscreen function run when the user clicks the submit button.

The next thing our quiz needs is some questions to display. We’ll use object literals to represent the individual questions and an array to hold all of the questions that make up our quiz. Using an array will make the questions easy to iterate over

First, we create an output variable to contain all the HTML output including questions and answer choices.

Next, we can start building the HTML for each question. We’ll need to loop through each question like so

For each question, we’ll want to generate the correct HTML, and so our first step is to create an array to hold the list of possible answers.

At this point, we want to build out our resultscreen function to loop over the answers, check them, and show the results.

First, we select all the answer containers in our quiz’s HTML. Then we’ll create variables to keep track of the user’s current answer and the total number of correct answers.

Now we can loop through each question and check the answers.

Once the answer-checking loop is finished, we can show how many questions the user got right.


 Thank You
