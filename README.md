# Robin's Timed Coding Quiz

I have created a timer-based quiz application that stores high scores. This timed quiz on JavaScript fundamentals stores high scores
so that the user can track their progress compared to their peers.
The user arrives at the landing page and is presented with a call to action to "Start Quiz". Also note the navigation option to view "Highscores" and the "Time" value set at 0. With a click of the "Start Quiz" button the user is present with a series of questions. The timer is started with a value and begins to countdown immediately. The score is calculated by time remaining. If the user answers correctly and quickly they will recieve a higher score. Answering incorrectly results in a time penalty, and will result in a lower score. When time runs out and/or all questions are answered, the final score is presented to the user and the user is asked to enter their initials/Name. Their final score and initials/Name are then stored in `localStorage`.
