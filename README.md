# # # # CPIT252-Lab2-Submission
## ## Deliverables for lab 2

I changed the code to make it follow the Singleton design patter by following these steps:

1. change the Logger class constructor visibility to private 
2. create an instance variable of type Logger inside class Logger
3. create a new static method inside the Logger class that when invoked, it creates a new instance inside the variable we created above, and return it to the caller. however, only do that when the variable is null or empty(meaning it'll only work for the first time)
4. change the code of every other place where they create a new Logger object, and instead make them call the method we created above via the class name.

after these steps, we ensured that only one Logger object is created and we achieved our goal.
