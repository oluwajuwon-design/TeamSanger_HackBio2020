# Team-Sanger_HackBio2020

## About

This is a repository for the task assigned to team-sanger during the 5 weeks internship programme orgnised by HackBio in the year 2020. It is more of a collaborative project assignments that involved exploring softwares used in bioinformatics. Each team member need to fork the repository and make the neccesary changes applicable to the assigned task (creating his/her scripts). Information about each member and their scripts that could be used to generate individual profile is also included here. Every member is required to add their names, the software they used in creating the scrips as well as dependencies (if any - should be stated clearly). 

## Team Members Names
Please kindly add your names here to have a comprehensive list of the Sanger Team.

1. Winfred Gatua
2. Akurut Eva
3. Umar Ahmad
4. Khatendra Reang
5. Maruf Ahmed
6. Olayemi Rotimi
7. Ankita Kumari
8. Ibiyinka Daramola

## Programming language

Use the table below to key in your name and programming language used to generate your script. If there are dependencies (in the language used), please kindly mention it in the table too. 

|      Name     |  Language  | Dependencies |
|:-------------:|:----------:|:------------:|
| Winfred Gatua | Javascript |  NodeJs Runtime Environment Download |
|  Maruf Ahmed  |      Perl     |       Perl installlation (v5.30.3)(https://www.perl.org/get.html)      |
|  Maruf Ahmed  |      PHP     |       PHP (v7.3.11)(https://www.geeksforgeeks.org/how-to-execute-php-code-using-command-line/)      |
|  Maruf Ahmed  |      R     |       R (v3.6.3)(https://www.datacamp.com/community/tutorials/installing-R-windows-mac-ubuntu)      |
|  Maruf Ahmed  |      Python     |      Python (v3.7.7)      |
| Akurut Eva    |Julia       |  Julia installation      |
| Olayemi Rotimi| Python 3.8
|  Ibiyinka Daramola        |  Python 3.8             | 
  Khatendra Reang        Bash
  
# Workflow
![Workflow](https://github.com/winfrednyoroka/TeamSanger_HackBio2020/blob/master/Flowchart.png)


# Help
To execute the scripts from this repository, a general script is provided that contains information on cloning the repository itself. Using *git clone* followed by the link to the repository allows you to clone. Upon cloning, it will provides command to change the directory from the current repository to the Team_Sanger Repository. To execute the scripts, you need to add rights to execute which can be achieved by *chmod +x script*. A for loop is provided that helps loop through each and every script and execute as per the commands within the loop. 

**Note**
You need to install all the softwares listed above for the scripts to be executed. 
In case you bump into an error of **bad interpreter** when executing the scripts. Check the location of your software using this the example command as shown below:

# For example
which R
/usr/local/bin/R

which python3
/usr/local/bin/python3

which perl
/usr/local/bin/perl

which ruby
/usr/bin/ruby

which php
/usr/bin/php

# Remember your location may vary ! Whatever the location is just add it to the title.
```
On your terminal. Having found the path to either the compiler or interpreter then check the shebang (e.g #!/usr/local/bin/bash) of the individual script and edit it to suit your local machine.
