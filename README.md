# Suguna-K
Simple quiz application with MCQ questions

Created a multiple choice quiz using javascript,In this quiz,the user will have to choose the correct answer out of choices.If the user didn't answer the question within the time limit,it will go to next question automatically,and the question is marked as wrong.

To set up the structure of our JavaScript quiz, we’ll need to start with the following HTML:

A <div> to hold the quiz
A <button> to submit the quiz
A <div> to display the results
  
We can then select these HTML elements and store references to them in variables like so:

const quizContainer = document.getElementById('quiz');
const resultsContainer = document.getElementById('results');
const submitButton = document.getElementById('submit');

Next we’ll need to build a quiz, show results, and put it all together. We can start by laying out our functions, and we’ll fill them in as we go:
