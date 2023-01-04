
1) In a terminal type chmod +x Script.sh this should allow accses to Script file.

2) In the same terminal type ./Script.sh 4 xterm windows should pop up.

3) In the first window type ./sensor <Threshold> <Name> where threshold is the max value you would like to increment to.

4) In the second window type ./controller 

5) In the third window type ./acuator

6) In the fourth window type ./cloud

7) The files will send data between eachother and show what is being sent and recived in each xterm window.

8) Cloud will display a final message based on if the threshold is reahed succsessfully or not.

// Each file should stay open until the required value is sent/recived properly. 
// All the files will remain running until they recive or send what is required. 
