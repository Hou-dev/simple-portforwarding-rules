# Simple Port Forwarding Rules
Port forwarding iptables, ufw and firewalld
This program was made to automate the port forwarding process used in Linux distribution. Tools used were excel spreadsheet, python 3.x and Qt used for the interface.

## How to use program?
First select "Destination" text box and input the destionaton port of your PC on the local network. Click the checkbox and enter the program you need to port forward.

![Annotation 2020-08-04 160340](https://user-images.githubusercontent.com/59487209/89344838-255ec000-d66c-11ea-9884-eb403f793b07.png)

The next thing to do is hit the finder button. The Output table should be populated with new rules which defaults to iptables. As shown in the image below.

![Annotation 2020-08-04 160859](https://user-images.githubusercontent.com/59487209/89345334-d6fdf100-d66c-11ea-8547-0bb78e977174.png)

My program also supports other types of firewalls such as firewalld. Select the list on the right and scroll to firewalld and hit generate. Make sure you have the destionation address and the finder selected the program you need to port forward.

![Annotation 2020-08-04 161244](https://user-images.githubusercontent.com/59487209/89345618-5d1a3780-d66d-11ea-8aa3-2d44560a2e6f.png)

### Some thoughts on what can be done better
This was my first time making a GUI using QT so it took at little while to under stand how to use it. 
I should have used a database like system to the search becuase the results of the finder has to match exactly, I cannot make partial mataches at the matches
