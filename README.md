# jengamez.github.io
# Unit 02: CSS and Bootstrap Homework: Resonsive Portfolio

## Description
This is a 60 second timed quiz on coding. I began with the simplest task, making the questions.  I went through many different ways to syntax the questions, choices and answers. In the end, I decided to use the index. 

I created a function for start time. Within this a setInterval () that will repeatly call a function at 1000 milliseconds.  The clearInterval () is called to stop the timer when seconds equal zero.

I made an Event listener called the startTime () to begin the timer.  Next the hideStartArea () is called to hide the <h1>, <p>, and <button> elements. Then the displayQuestion () is called to display the first question.  

When the user clicks on one of the choices, a series of actions happens. The srcElement event references which choice was clicked on, and given the variable clickID. An answer variable was created so I can see in the console log which choice was selected.  correctID variable was created to compare to the correctAnswer. If they match, then the score increments.

In the dislayQuestion () I made the h1 the question.  So that the questions wouldn't show up on the page over and over, I cleared the wrapper's contents using the innerHTML property with empty quotes.  The question element was appended to the parent wrapper element. I made a div for the choices element, so that I could append the buttonEl div to it. I made a for loop to loop through the questions and choices.

## License

This project is licensed under the MIT License.