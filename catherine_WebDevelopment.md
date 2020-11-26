# hello :raised_hand: This is Catherine<br> Here we are going to learn the basics of 
<ol>
<li>REPL</li>
<li>express.js</li>
<li>Core modules in node.js</li>
</ol>
Hope you like :+1: and understand this :stuck_out_tongue_winking_eye:,


# 	INTRO TO REPL:
#### REPL is nothing but <b> read–eval–print -loop </b>.
It a simple interactive computer programming environment that takes single user inputs, executes them, and returns the result to the user

•	The <b>read</b> function accepts an expression from the user, and parses it into a data .For example 2+3

•	The <b>eval</b> function takes this internal data structure and evaluates it. function + is called on the arguments 2 and 3, yielding the result 5.

•	  The <b>print</b> function takes the result yielded by eval, and prints it out to the user. If it is a complex expression, it may be pretty-printed to make it easier to understand

•	The development environment then returns to the read state, creating a <b>loop</b>, which terminates when the program is closed.
Example:
<br>
````
>$ node
> 2 + 3
5
> console.log(‘hello world’)
Hello world
>
````
### OUTPUT::point_down:
<img src="https://github.com/catherinekennedy/images/blob/main/repl.jpeg?raw=true" >

# INTRO TO EXPRESS.JS:
:mushroom:	Express.js is free  :free: open source web application frameworks for node.js .<br>
:mushroom:	It is used for designing and building web application :computer: .<br>
:mushroom:	It is used to build both static and dynamic web pages.<br>


## How to get started with express.js:
  **Step1 :** you need to install express in your node as it is not a core module.
   
   > npm i express@4.16.4
 
 now the version 4.16.4 is installed in node.js<br>
**step2 :** then ,code your program as <br>

 ````` const express=require(‘express’)
 const app = express()
app.get(‘’,(req,res)=>{
     res.send(‘hello world!’)
 })
  app.listen(4000,()=>{
  console.log(‘the port 4000 is   running’)
  })
 `````
   **Step3 :** Now go to  the browser and enter the URL
>http://localhost:4000
   to see your output.
   
   ## you have made your :thumbsup: own server. congrats :raised_hands:
   
  ### THUS THE FINAL OUTPUT::point_down:
<img src="https://github.com/catherinekennedy/images/blob/main/1output.jpeg?raw=true" >
 
 ### THUS THE FINAL OUTPUT IN command promt ::point_down:
<img src="https://github.com/catherinekennedy/images/blob/main/finalpage.jpeg?raw=true" >
  
   
 
 ## Explanation :
 * The get() function has a path name and a callback fuction with 2 arguments namely **req**-request and **res**-response.
* The send() function is used to display it to the user.Here both HTML or JSON can be used to send
 
### For example : to get **HTML**
```res.send(‘ <h1>  hello world </h1> ’)```
### Output:
<img src="https://github.com/catherinekennedy/images/blob/main/htmloutput.jpeg?raw=true" >
<br><br>

### For example : to get **JSON**
```
res.send({
  Name:’catherine’,
  Location:’chennai’
  })
```
### Output::point_down:
<img src="https://github.com/catherinekennedy/images/blob/main/jsonoutput.jpeg?raw=true" >

<br><hr><br><br>
# WHAT IS CORE MODULE?
<p> Core module operate at lower level. They are inbuilt with node.js . So, there is no need to install separately like we do to install nodemon and request in NPM </p><br>

### Some of the core modules in node.js are,<br>

|module|use|
|---------|---------|
| fs   |   to work with file I/O |
|  http  |  to create Node.js http server  |
| path |   to deal with file paths |
| querystring |  to deal with query string   |

#### SYNTAX:
>const  module = require('module_name');

core modules are complex compared to third-party modules,but anyway you dont need internet to install like third-party module
### Thus if you like follow me on <br>
<a herf="https://github.com/catherinekennedy"><img src="https://github.com/catherinekennedy/images/blob/main/githun.png" width="100px" height="100px"></a><br>
<a herf="https://www.instagram.com/cather_ine_kenny"><img src="https://github.com/catherinekennedy/images/blob/main/insta.jpg"  height="100px"></a><br>
<a herf="www.linkedin.com/in/catherine-robin-kennedy"><img src="https://github.com/catherinekennedy/images/blob/main/linkedin.png"  height="100px"></a>








 

   
