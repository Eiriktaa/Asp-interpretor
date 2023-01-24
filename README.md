# Asp-interpretor
- A showcase of an interpretor project that was given as the final exam in the course IN2030 @ UIO (2022)
- The code cannot be displayed in a public repository because it is still part of a running course, but any interested party can inquire to see more or discuss the code :)

The interpretor can be run by downloading the asp.jar file and running it as a jar file. 
```
java -jar asp.jar myAspFileHere.asp -logflag
```
Possible flags:
- -logS: scanner logfiles
- -logP: parser logfiles/syntax tree
- -logE: traces variables/function calls during runtime 


## Assignment
-The assignement was a 4 part project spanning the entire semester to create an interpretor for a python-like language. The language ASP is a barebones version of python containing most of the baseline functionalites of the language. The compiler itself is written in Java.

Part 1: Scanner
- This part of the project had us handle the the input of the source file. It tokenizes the source file and saves it in a syntax tree for the parser to handle

Part 2: Parser
- The parser uses recursive decent to parse the syntax tree and figures out if the code is valid.

Part 3/4: Runtime
- The compiler had to handle the various variables and their respective operations. The compiler should be able to handle all the operations/function calls/assignments that is part of the language

### IMAGES
#### Overview
![image](https://user-images.githubusercontent.com/21067937/214421754-5776e957-17c5-4524-b315-2f6187803209.png)
![image](https://user-images.githubusercontent.com/21067937/214428818-e88688a5-76f6-4304-a246-5cf8c41f42ce.png)
#### Scanner
![image](https://user-images.githubusercontent.com/21067937/214425174-5ca9ca4f-8b2b-4981-9acc-c19958d682ae.png)
#### Parser
![image](https://user-images.githubusercontent.com/21067937/214425794-665f9df8-7a20-4fdb-bf81-a0f21c2586e0.png)
#### Runtime
![image](https://user-images.githubusercontent.com/21067937/214426342-0d061834-5bf8-4fb4-a4c2-5de6aa36a8c0.png)
