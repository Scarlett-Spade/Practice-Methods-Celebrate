# PRACTICE METHODS 

This is a [Skillcrush](https://skillcrush.com/) course challenge. 

# INSTRUCTIONS

In the object literal, below the weeklyHourGoal property, create a new property called achievedStudyGoal and give it a value of false.

Below achievedStudyGoal, create a new property called addStudyTime. Make addStudyTime a method with hours as a parameter.

Inside the addStudyTime method, modify the hoursThisWeek property by adding the value of the hoursThisWeek property to the value of hours. Hints: Don’t forget to use the this keyword to access object properties from inside your method. Also, this is a great place to use the += assignment operator to create cleaner code!

Still in the method, write an if statement to evaluate if the value of hoursThisWeek property is greater or equal to the value of the weeklyHourGoal property. 

If the condition of the if statement evaluates to true, set the achievedStudyGoal property to true.

Below the addStudyTime method, add another method called celebrate with no parameters.

Inside the method, add the class “celebrate” to the body element.

Also in the method, remove the class “hide” for both the success and dance elements.

Inside the addStudyTime method’s if statement, call the celebrate() method. Hint: Don’t forget the this keyword!

At the bottom of the script.js file, call learning.addStudyTime(). As an argument, pass the method a number that will make the value of hoursThisWeek greater than the weeklyHourGoal. This will trigger celebrate() to run.
