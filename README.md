# CS-350
Foster Hare <br>
Professor Satterfield

# Artifact 1
Milestone 3 : Morse Code LED
# Summarize the project and what problem it was solving.

This project used a Raspberry Pi to display messages like "SOS" and "OK" in Morse code using LEDs. A button toggled between messages, and the code used a state machine to manage blinking and timing.

# What did you do particularly well?

I followed the state machine pattern effectively and used threading to keep the system responsive. The LED logic worked cleanly.

# Where could you improve?

I could clean up unused comments and optimize the message parsing logic.

# What tools and/or resources are you adding to your support network?

I added more hands-on with GPIOZero, LCD management, and state machines. This also boosted my confidence with threading.

# What skills from this project will be particularly transferable to other projects and/or course work?

Working with GPIO, threading, and LCDs will help in future embedded or hardware-interfacing projects.

# How did you make this project maintainable, readable, and adaptable?

I used classes, comments, and modular design. The display class and state machine logic are separated, which helps reuse and update the code later.

# Artifact 2
Project Two: Smart Thermostat Lab

# Summarize the project and what problem it was solving.

This project built a smart thermostat using a Raspberry Pi. It read temperature from a sensor, let users change the set point with buttons, showed info on an LCD, and sent status updates to a server via UART.

# What did you do particularly well?

I successfully integrated multiple components like the sensor, LCD, buttons, LEDs, and serial communication. The state machine made controlling modes easy.

# Where could you improve?

The code could be more modular, and the display could show clearer feedback for the user. Also, error handling could be added for serial issues.

# What tools and/or resources are you adding to your support network?

I became more familiar with I2C sensors, UART communication, and PWM LED control, which are useful in hardware and IoT projects.

# What skills from this project will be particularly transferable to other projects and/or course work?

Reading sensors, controlling outputs, and designing user interfaces on embedded devices will help in both coursework and real-world jobs.

# How did you make this project maintainable, readable, and adaptable?

I used a clear class structure, meaningful variable names, and a state machine. This makes it easier to adjust for more features like fan control or mobile app integration.
