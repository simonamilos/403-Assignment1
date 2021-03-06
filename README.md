#Instructions

You should do following excersizes:

## Task 1 - Show Text in a Browser

Create a PHP page, with the standard HTML `<head>`, `<title>` and `<body>` tags. This is not strictly necessary but is good practice and should the the first step for each exercise. Consider creating a template file with these tags already in place. Remember to save your file with the .php extension.

Inside the `<body>` tag, create a PHP section that will show the text “Hello World!” in the browser. Check your work by opening the page in a browser. If you get a blank page, check to be sure that you ended each statement with “;” and that you included the opening and closing PHP markers. When you are ready, move on to the answer script.

## Task 2 - Create and Use Variables

Next, create two variables, one for the word “Twinkle” and one for the word “star”. Echo the statement to the browser, this time substituting the variables for the relevant words. Change the value of each variable to whatever you like, and echo the statement a third time. Remember to include code to show your statements on different lines.

## Task 3 - Arithmetic Operators and Variables

PHP includes all the standard arithmetic operators. For this PHP exercise, you will use them along with variables to print equations to the browser. In your script, create the following variables:
$x=10;
$y=7;

Write code to print out the following:

	10 + 7 = 17
	10 - 7 = 3
	10 * 7 = 70
	10 / 7 = 1.4285714285714
	10 % 7 = 3

## Task 4 - Arithmetic-Assignment Operators and Variables

Arithmetic-assignment operators perform an arithmetic operation on the variable at the same time as assigning a new value. For this PHP exercise, write a script to reproduce the output below. Manipulate only one variable using no simple arithmetic operators to produce the values given in the statements.

Hint: In the script each statement ends with *"Value is now $variable."*

	Value is now 8.
	Add 2. Value is now 10.
	Subtract 4. Value is now 6.
	Multiply by 5. Value is now 30.
	Divide by 3. Value is now 10.
	Increment value by one. Value is now 11.
	Decrement value by one. Value is now 10.```

## Task 5 -  Variable Content and Destruction

When you are writing scripts, you will often need to see exactly what is inside your variables. For this PHP exercise, think of the ways you can do that, then write a script that outputs the following, using the echo statement only for line breaks.

	string(5) "Harry"
	Harry
	int(28)
	NULL

## Task 6 - Concatenation of Strings

For this PHP exercise, write a script using the following variable:
	$around="around";

Single quotes and double quotes don't work the same way in PHP. Using single quotes (' ') and the concatenation operator, echo the following to the browser, using the variable you created:
	What goes around comes around.

## Task 7 - Variable Data Types

PHP allows several different types of variables. For this PHP exercise, you will create one variable and assign it different values, then test its type for each value.

Write a script using one variable “$whatsit” to print the following to the browser. Your echo statements may include no words except “Value is”. In other words, use the function that will output the variable type to get the requested text. Use simple HTML to print each statement on its own line and add a relevant title to your page. Include line breaks in your code to produce clean, readable HTML.

	Value is string.
	Value is double.
	Value is boolean.
	Value is integer.
	Value is NULL.


Use numbers only in the above variable assignments, not in the echo statements. You will need a third variable as well.


# Notes

Put all tasks in separate files. Don't forget HTML markup. 


# Assignment submission

1. To start, [**fork** the repository][forking].
1. [**Clone**][ref-clone] the repository to your computer.
1. Modify the files and [**commit**][ref-commit] changes to complete your solution.
1. [**Push**][ref-push]/sync the changes up to GitHub.
1. [Create a **pull request**][pull-request] on the original repository to turn in the assignment.
1. Enter link to your repository in Canvas

[create-repo]: https://help.github.com/articles/create-a-repo
[private-repos]: /guide/private_repos
[add-to-team-action]: https://github.com/education/teachers_pet/#giving-others-access
[teachers-pet]: https://github.com/education/teachers_pet
[help-add-to-team]: https://help.github.com/articles/adding-organization-members-to-a-team
[help-access-control]: https://help.github.com/articles/what-are-the-different-access-permissions#organization-accounts
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[raw]: https://raw.githubusercontent.com/education/guide/master/docs/forks.md