# CS-350-Emerging-Systems-Architectures-and-Technologies


    Summarize the project and what problem it was solving.
    The pwnled assignment was about implementing code into Code Composer Studio to control the LED lights
    on the TI-3220S LaunchPad. We did this by changing the duty cycle of the PWM (Pulse Width Modulation) 
    signal. The uart2echo assignment, on the other hand, was about also implementing code into CSS but this
    time to set up a UART communication between the LaunchPad microcontroller and the terminal interface. 

    What did you do particularly well?
    I implemented both codes to handle the logic to achieve the tasks particularly well. The transitions
    between the LEDs responded effectively to the modifications in the PWM duty cycle. I also used
    modular functions for the setup of the PWM to increase readability of the code. The 
    communication between the interface and the microchip was also successful. The UART interrupts
    were implmented efficiently and error handling is in place to to manage communication errors. 
    
    Where could you improve?
    Looking back over the code now, I see that I could've included more comments within the code to
    make it easier for other developers to read. This practice also enchances maintainability of the
    code. I could've made the PWM parameters more dynamic to ensure use by different hardware 
    configurations. For the uart2echo assignment, I could've added a buffer to manage multiple UART 
    channels. This would've enchanced the functionality of the system by having more channels to 
    communicate over. 
    
    What tools and/or resources are you adding to your support network?
    For these assignments, the use of thge TI LaunchPad's documentation was essential to understand
    the functionality of the system and how to make necesary changes. Familiarizing myself with CSS
    was also very helpful as I worked through the assigemnts. 
    
    What skills from this project will be particularly transferable to other projects and/or course work?
    Understanding PWM will be very helpful in the future for other applications that use PWM. Applications
    that could benefit from PWM include motor control and signal generation. I also added to my skills by 
    learning from the uart2echo assignment. Serial communication and interrupt handling will be very usefu
    l in the future as projects involving data logging and communication protocols use these skills.
    
    How did you make this project maintainable, readable, and adaptable?
    I followed best practice guidelines to implement the code to enusre maintainability, readability 
    and adaptability. These practices include organizing the code into defined functions, using
    descriptive name variables and writing structured code. By parameterizing the UART settings, 
    I allowed the setup for different communications to be easier. 
