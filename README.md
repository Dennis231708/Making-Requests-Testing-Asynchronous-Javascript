# Making-Requests-Testing-Asynchronous-Javascript
Thinkful assesment
Making requests: Testing asynchronous JavaScript
Instructions
To complete this practice problem, you will be writing tests for a number of functions that make external requests using the axios library. Each function makes an HTTP request.

Existing files
The src/main.js file includes an axios variable and a BASE_URL variable which points to the correct URL for the students server. Please don't change either of these lines. Within this file are three functions—index(), create(), and show()—which have already been completed for you.

index()
Method	Path
GET	/students
The index() function should return all of the students.

create()
Method	Path
POST	/students
The create() function should take an object, body, and create a new student.

show()
Method	Path
GET	/students/:id
The show() function should take an id and return a student.

Tasks
The test for the index() function has already been completed for you as an example. You will need to complete the tests for the create() and show() functions in the test/main.test.js file.

For the create() function, you will need to write tests to verify that the function does the following:

Makes a POST request to the appropriate URL
Resolves with a promise containing the newly saved student
Log an error to the console
For the show() function, you will need to write tests to verify that the function does the following:

Makes a GET request to the appropriate URL
Resolves with a promise containing the student data
Logs an error to the console
Tips
You may complete this challenge on your own machine before uploading it to Qualified.
Reference the related lesson for help on completing this practice problem.
