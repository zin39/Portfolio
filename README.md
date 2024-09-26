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

--Now lets setup this project on github.
  [-- git remote add origin git@github.com:zin39/Portfolio.git
  -- (I did "git push -u origin main" and i ended up with error "error: src refspec main does not match any error: failed to push 
      some refs to 'github.com:zin39/Portfolio.git'")]
       This error occured because there was no branch named "main". So this error occured. So to overcome this I first did "git branch".
        which showed me the available branches and master branch was seen . Afte that we followed this steps.
  -- git add .
  -- git commit -m "This is a Portfolio Website"
  -- git push -u origin main

Like this we setup our github project. 

After these steps we are going to work with navbar first. 

## So to work with navbar i  m going to use bootstrap.
  while searching for methods to make navbar i ended up searching mdbootstrap which will help build me a navbar . In the navbar i m going to keep items like -home -project and -skills.

### Day 2

Today we found a navbar which is simple and easy to apply from "https://mdbootstrap.com/docs/standard/navigation/navbar/examples-and-customization/#section-5"

[Today when I was inserting a logo in the navbar I faced an error. When I put the location of the logo in src. It wasn't apearing but when I added "output": "public" in assests of angular.json it started working.]

Another issue that we found today was the toggle button was not working even though i had added "node_modules/bootstrap/dist/js/bootstrap.bundle.min.js" this in the script section. 
Later i figured out that we need to add data-bs-toggle and data-bs-target in button for navbar toggler.

When I was trying to change color for the button of Download CV . It wasnot working 



