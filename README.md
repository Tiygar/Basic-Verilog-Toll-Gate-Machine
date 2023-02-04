# Basic-Verilog-Toll-Gate-Machine
Toll Gate machine simulation using verilog code.
Main Aim of the Project: This Project aims to make a toll gate for a school refectory that will automatically detect the card which the useris giving as input and it will analyze the card to in 3 ways:
Is this card valid for this school?
Is this a student or a teacher?
Does the user have enough Money?

How does the system work? (with details)
Firstly we have a school that has 127 teachers and 896 students to maket he problem simpler. For the toll machine there is a distance sensor that will be sure to turn the code on when something is closer than 5 cm to the sensor. Then the code will start working and it will firstly detect the card and get a value from card, i used a 11 bit binary number for 2 cards in my Project. After it reads the card id, it will search the id in its storage, firstly the teacher cards has been made so first 127 numbers belong to teachers which means first 8 bits so the rest of the bits will be zero. So the machine will decide if this is a teacher card or not, if this is a teacher card it will take 13 liras from the teacher card and if this is a student card then it will take 5 liras from the student card. In both cases it will allow the user to pass. If the user doesnt have enough Money, it wont allow the user to pass.
