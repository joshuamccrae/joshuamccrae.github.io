# Joshua McCrae

### MAE 4190 - Fast Robots

<img src="ferraripose.png" width="350" height="467">

Hey! My name is Joshua McCrae and I am currently a Mechanical Engineering student at Cornell University. I am originally from New Castle, Delaware. I enjoy things such as listening to hip-hop and lo-fi music, working out, cars, and going down Youtube rabbit-holes. Welcome to my GitHub Webpage!

# Labs

## Lab 1 - Artemis Setup and Connection

### Lab 1A: Setup

The purpose of this portion of the lab is to get comfortable using the Arduino IDE and Sparkfun Apollo 3 board manager. Once I downloaded the Arduino IDE and installed the correct board manager, I was able to connect my Artemis Nano to my laptop and upload some basic example sketches to it:

### Example 1: Blink

[![artemis blink test](http://img.youtube.com/vi/U8jd9H0t-VI/0.jpg)](http://www.youtube.com/watch?v=U8jd9H0t-VI)

In this example, the Artemis recieves a signal from the Arduino IDE to blink it's LED repeatedly until the program is terminated. The blue blinking LED can be seen in action below.

### Example 2: Serial

[![artemis serial test](http://img.youtube.com/vi/iKPp8C9dj7k/0.jpg)](http://www.youtube.com/watch?v=iKPp8C9dj7k)

In this example, we input some text into the serial monitor (in this case "hello") and the Artemis "echo's", or repeats this input back to us as seen below.

### Example 3: Temperature Sensing

[![artemis temp test](http://img.youtube.com/vi/pteChHeaMxI/0.jpg)](http://www.youtube.com/watch?v=pteChHeaMxI)

Here, I am increasing the temperature of the Artemis chip by breathing on it. This temperature change is reflected in the serial monitor output as seen below.

### Example 4: Pitch Sensing

[![artemis pitch test](http://img.youtube.com/vi/CNzyPZD0Jy4/0.jpg)](http://www.youtube.com/watch?v=CNzyPZD0Jy4)

Lastly, this example tests the onboard microphone on our Artemis. I increase the frequency of the loudest sound it detects by whistling, the value output to the serial monitor increases, as seen below. 

### Lab 1B - BLE Connection and Notification Handling

In this portion of the lab, my goal was to establish a BLE (Bluetooth Low Energy) connection with my Artemis so that it can communicate wireless with my computer. In order to achieve this, I installed the latest version of Python and upgraded also upgraded pip. In order to send Python code to my computer, I created a virtual environment to use Jupyter Notebooks to make scripts for my code.



