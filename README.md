# CodeTest
Webdriverio code test

How to run it locally:

1- install nodejs:
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash - sudo apt-get install 

2- Install WebdriverIO:
npm install -save-dev webdriverio

3- Download Selenium-standalone server:
npm install -g selenium-standalone

4- Create dir repository:
mkdir code-test

4- Go to directory and initiate Git repository:
cd code-test
git init

5- Download repository:
git pull https://github.com/AlanGDC/CodeTest.git

4- Install Selenium-standalone and start:
selenium-standalone install
selenium-standalone start

6- Execute Test1.js and Test2.js individualy (opcinaly for test):
node Test1.js
node Test2.js

5- Execute wdio config:
./node_modules/.bin/wdio config

6- Select this answers to config:
Q: Where do you want to execute your tests?
A: On my local machine

Q: Which framework do you want to use?
A: mocha

Q: Shall I install the framework adapter for you?
A: Yes (just press enter)

Q: Where are your test specs located?
A: ./test/specs/*/.js (just press enter)

Q: Which reporter do you want to use?
A: dot (just press space and enter)

Q: Shall I install the reporter library for you?
A: Yes (just press enter)

Q: Do you want to add a service to your test setup?
A: none (just press enter, let’s skip this for simplicity)

Q: Level of logging verbosity:
A: silent (just press enter)

Q: In which directory should screenshots gets saved if a command fails?
A: ./errorShots/ (just press enter)

Q: What is the base url?
A: http://localhost (just press enter)



6- Execute wdio :
./node_modules/.bin/wdio wdio.conf.js


What have blocks me:
It was half technical and half time trouble; at first i wasn't able to upload my files to github in bash, i think it was beause of my old git user already configurated, so i began working local until i finish the two test, wich i have already design. 
After that i began upload the files manualy in my Git repository for shorten time.
