# Dat250-expass1

### The installation:
For the installation part of this assignment I had no problems. This is because I already had everything needed 
for the software development environment from previous work. 

### Validating the software environment
Heroku requires that I have a Heroku account, Java 8 installed and Maven 3 installed. 
The first thing I did was to create an account. 
Then I checked if I had the correct versions by using these command-lines in the terminal: 
* Java: **java -version**
* Maven: **mvn -v** <br>

The output I got from this was: 
* Java: **java version "1.8.0_201"**
* Maven: **Apache Maven 3.6.3** <br>

These are the correct versions of the software and there is no need for any updates. 

Heroku also requires **Git** which I already have. To double check I just wrote **git** in the terminal and got all the
commands up for Git.
I also logged into my already existing **github** account to create this repository and connect it to **IntelliJ**. 


### Technical problems with Heroku
The first problem I encountered was that my Java was running on JDR and not JDK. JDK was required for Maven to build. 
By changing Java to run on JDK the build was successful.  
The second problem was with the config vars. When I tried to execute this command **heroku config:set ENERGY="20 GeV"**
my terminal said it did not recognize the command. I used git bash as a terminal and when I switched to powershell the
command executed. 
Then with add-ons it asked us to provide credit card verification to create them. I was told in the lab that this
was not necessary for our assignment.
The last problem I encountered was with postgres. Since I did not have this installed on my computer I had to do it to
make the command execute. This was a bit confusing, but I maneged to do it after some attempts. 

This is the web-URL for my tutorial: 
<https://shrouded-savannah-37500.herokuapp.com>

### Unsolved issues
