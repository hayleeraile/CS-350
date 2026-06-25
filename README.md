# CS-350
-Summarize the project and what problem it was solving.
For this project, we needed to create a thermostat using a 
Raspberry Pi and components like a humidity/temperature sensor. 
The thermostat was supposed to read the temperature and humidity 
from the sensor over an I2C interface. It also allowed a user to 
use a button to switch between an off, heat and cooling state. Other 
buttons were adding to allow the user to change the temperature up or 
down. The information was displayed onto an LCD screen. The different 
states were shown by the color of LED that corresponded with that state. 
UART communication was used to update the data for the thermostat every 30 seconds. 

-What did you do particularly well?
I think that I was able to integrate different hardware components to 
create one single application really well. This was something new to me
but I love working with puzzles and similar things, so it wasn't as complicated
as I thought. 

-Where could you improve?
I believe I could improve on the coding aspect of things. Based on my instructor feedback,
I should have spent more time looking at how the state entry methods worked to correctly and 
immediately reflect the threshold behavior. I need to spend more time on each section to ensure 
that it is properly running how it is supposed to. A final walkthrough test could have helped 
figure this out even though at the time I believed the system was running as intended. 

-What tools and/or resources are you adding to your support network?
Using documentation, especially when working with something like a Raspberry Pi and a solderless 
bread board helped when I ran into an issue. Course materials like the textbook we worked with and
any resources the professor shared were valuable information as well. 

-What skills from this project will be particularly transferable to other projects and/or course work?
Designing state machines, writing Python code, creating a system with hardware components, and trouble shooting
the hardware and/or software when an issue arises. 

-How did you make this project maintainable, readable, and adaptable?
Having the code contain small functions that each have their own task made it easy to read and keep track of. The state 
machines that were created kept hardware logic and thermostat logic separate.
