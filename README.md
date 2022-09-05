Thursday
0800hrs --- 1000hrs
was working on creating a python API that has create, read, update and delete function for Books
-I Install fastapi in for me to be able to import the module in my project.
-Using Vscode as my text editor
-Using the terminal i started my project, naming it Books and then i started an app naming it TheBookHub.
-then i intalled fa 
was able to install an set up the venv environment and activate it and setting the the project to use the interpreter in the venv (
jimmy file) python.exe
-using uvicorn to start my app and the server.
-before implemented my work in my main project i created a python file (main.py)
were i tested my code from.
-so for my path operation it had a decorate @app followed by the HTTP method which in this case is .get then the specific or the urlpath("/")
then below it had a specific operating function (): in performing all certain logical tasks and  it gets to return some data and  thats the data 
to be return to the user when they his a certain specific path operation.
-So i then installed the postman app to test if my api was working properly
-i then had to copy the http address to the postman app and tested my path operation and it worked so my api was working properly.


task 2

1400hrs --- 1530hrs

-Resuming form from where i had left i turn tried to test the crud in on the postman application
Create ----> POST --->/post
Read {  i. GET ----->/posts/:id
	   GET	---->/post
Update ----> PUT/PATCH ---->/post/:id
Delete ----> Delete ---->/post/:id

C-create i then used @app.post("/create_posts")
		     def create_posts():
				return{"message": "succefully create post"}
