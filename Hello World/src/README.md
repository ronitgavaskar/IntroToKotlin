# What does this program do?
Just a simple program written in Kotlin to print the message "Hello World"

# How do we run this program?
(i) `kotlinc HelloWorld.kt -include-runtime -d hello.jar`
* Compiles the program HelloWorld.kt 
* `include-runtime` makes the .jar runnable by   including the kotlin     
    library.
* `-d` flag points out what we want output to     be and may either be a 
    directory or a .jar file

(ii) `java hello.jar`
* Runs the above program which is now compiled 
      into a jar file
* `Expected Output: Hello World!`