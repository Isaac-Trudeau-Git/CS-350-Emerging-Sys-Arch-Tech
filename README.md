# CS-350-Emerging-Sys-Arch-Tech

**Summarize the project and what problem it was solving.**
This project was to create a working thermostat using raspberry pi that output information to a display and sent data to a server. I needed to use I2C temp and humidity sensor AHT20 along with GPIO signals to turn on, off, and pulse a red or blue LED light depending on if the thermostate was in the heating or cooling mode. Buttons were used to signal changing the state from off, heating, and cooling and to raise and lower the setpoint. The state machine library was used to control the states. All code was written in python. 

**What did you do particularly well?**
The part I did well on is the hardware setup and the coding portion. I was able to successfully have the hardware configured correctly without the need to troubleshoot my connections and the code was fairly straight forward. Although we only had to input the TODO sections of the code it was a great learning experiance. 

**Where could you improve?**
I was not very confident in my creation of the state machine drawing and I believe I could refine my ability to convey the process that is more easily understood. I also think I could improve on gaining a deeper understanding of the hardware architecture as I have a very high level concept of it but lack the lower level concepts. 

**What tools and/or resources are you adding to your support network?**
The raspberry pi was a very fun tool to use during the project and it was great to see everything come together and work. I think this along with other technologies related to embedded systems will be good tools to add to my support network. The python state machine library was very useful in simplifying tasks and I found forums like stack overflow to be useful in getting answers to questions. 

**What skills from this project will be particularly transferable to other projects and/or course work?**
The skills that I think will be useful for other projects is having a better understanding of serial communications and designing with libraries that I have not previously used such as the state machine one for python. Projects like this are also a good way to keep improving on code and learning new things. 

**How did you make this project maintainable, readable, and adaptable?**
I made this project maintainable, readable, and adaptable by writing clean code that contained the necessary amount of comments and good naming conventions. I had also written a report the described the function of the code and used separate functions for each aspect allow it to be easily reconfigured or adapted. I had also created a state machine diagram that shows the flow of logic and variables that control its function. 
