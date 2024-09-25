# Portfolio Website For Karan Raj Gupta

This is my first project in which I will show my skills on angular 18 , Docker , AWS and Backend with node and express. In this web page user will know about me and what I m capable of doing. Lets make a simple web page with small description about myself. 
In this hero section , there will be my name a short info and my skills . Also a button which will help users download my CV.



### Day 1 

** Initializing the project and setting it up on git **

Steps for installing Angular 18 and bootstrap .

--First Download npm manager using 
      - brew install node

--Second Download angular 18 using npm package manager  
      - npm install -g @angular/cli
      **Here -g stands for global.

--Third lets start a project. 
      - ng new Portfolio

--Now lets install bootstrap  
      - npm i bootstrap
    [Got 3 sever Vulnerabilites. But now lets ignore it]
    [Now need to add bootstrap to styles in angular.json. We can do this by adding "node_modules/bootstrap/dist/css/bootstrap.min.js" 
    Just after styles also we need to add javascript in script so that simple we can make dynamic . To do this lets add 
    node_modules/bootstrap/dist/js/bootstrap.min.js" in the script section of angular.json]

    ## what we want to do is make my name Karan Raj Gupta dynamic so that i can make changes to in .ts file and changes can 
       be seen in Website. 


