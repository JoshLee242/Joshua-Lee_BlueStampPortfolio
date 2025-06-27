# Gesture Controlled Robot


<!-- Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails! 

<!-- You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions: 
<!--```HTML 
<!-- This is an HTML comment in Markdown 
<!-- Anything between these symbols will not render on the published site
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|-->
| Joshua L | Leigh High School | Mechanical Engineering | Incoming Sophomore |

<!--**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**-->

![Headstone Image](logo.svg)
  
# Final Milestone

<!-- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.** -->

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->

<!-- For your final milestone, explain the outcome of your project. Key details to include are: -->
<!-- What you've accomplished since your previous milestone -->
<!-- What your biggest challenges and triumphs were at BSE -->
<!-- A summary of key topics you learned about -->
<!-- What you hope to learn in the future after everything you've learned at BSE -->



# Second Milestone


<!-- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.** -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/rfFcs0vRWrc?si=0Uea5Bc9E_d-Tqno" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Description 

Since my first milestone, I have worked on the Bluetooth connection and the code that allows the Bluetooth to control the DC motors. I was able to connect the Bluetooth to the motors, and now, just by tilting the second Bluetooth module, I can move the robot forwards, backwards, right, and left. In the process of making this robot, I was surprised that when I understood the code better, I was able to debug it way quicker than before. Another thing that surprised me was that making the hardware of the robot is 3 times easier than coding the software to control it. 

# Challenges

Challenges that I faced while making this progress included making the mistake of flipping the RX and TX pin orders and a couple of faulty batteries. Before I realized that the motors were not responding because of the wrong RX TX order, I spent a while changing the code and making sepeate test codes. However, after that didn't work, I finally checked the setup code and realized I had swapped the RX and TX order. Luckily, after I fixed that, all I had to do was change two dead batteries, and the robot worked.

# What's Next?

In the 3rd milestone, I will create boxes for all my circuit boards so they don't slide around while the robot is moving, while also adding finishing touches such as organizing the wires and making framing for the whole robot to look aesthetically pleasing.

<!-- For your second milestone, explain what you've worked on since your previous milestone. You can highlight: -->
<!-- Technical details of what you've accomplished and how they contribute to the final goal -->
<!-- What has been surprising about the project so far -->
<!-- Previous challenges you faced that you overcame -->
<!-- What needs to be completed before your final milestone -->

# First Milestone

<!-- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.** -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/OUJAr9vSj64?si=nnV3Ibp3feq13sb9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- For your first milestone, describe what your project is and how you plan to build it. You can include: -->
<!-- An explanation about the different components of your project and how they will all integrate together -->
<!-- Technical progress you've made so far -->
<!-- Challenges you're facing and solving in your future milestones -->
<!-- What your plan is to complete your project -->

# Description
My main project is the Gesture Controlled Robot, and I plan to finish it in this camp. The project includes two major components - the 4 DC motors for movement and the Bluetooth connections for control. These two components will work together to move the robot around and display the gesture controlling feature. By this first milestone, I have completed the hardware for the robot along with the code that controls the motor movement. As seen in Figure 1, the hardware includes the drivetrain, Arduino UNO board, L280N board, Bluetooth receiver end, and the Bluetooth master. The code I implemented coded the motor movement for the robot. I did this by connecting the Arduino UNO and L280N boards to the motors, which allowed me to easily code the movement through the IN1, IN2, IN3, and IN4 ports. I have also connected the two Bluetooth modules - one master and one slave - so they are now ready to code and control the movement of the robot. The master module is seen in Figure 2, and the slave module is found in Figure 1.

# Challenges
When configuring the motors for the first time, I realized that one motor on each side was spinning in the wrong direction. At  first, I didn't know what was wrong and tried to change the code, but I realized that I had to change the motor polarity for them to move in the correct direction. So, I flipped the two sets of wires connected to the L280N board and was able to fix the motor polarity. 

# What's Next?
To finish this project, I now have to code the Bluetooth to control the movement of my robot along with adding some modifications.


# Starter Project (Milestone)

<iframe width="560" height="315" src="https://www.youtube.com/embed/ux6VDJUyapE?si=GVTSBreFM2V7pruh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Description

For my starter project, I chose to do the RGB slider. The reason for this is that I want to design headlights and taillights for my gesture-controlled robot that turn on when I move forward or backward. This project provided me with experience in coding LEDs, which will help me make these modifications to my final project. The RGB slider is a small board that contains three RGB sliders, an LED, and a USB-C port. The three RGB sliders control an LED. Three colors - blue, red, and green - are mixed to display different colors on the LED. As you slide the sliders up and down, the strength of the color increases or decreases. There are almost an infinite combinations of colors I can use to light up my LED, and everything on the board is powered by a USB-C that is connected to my laptop. 

# Challenges

Challenges that I faced while making the RGB slider included soldering too much and soldering the whole board upside down. As easy as this project was, I forgot to ask my instructor if I was doing everything on the right side. This made me have to redo the entire RGB slider on the other side of the board. To do this, I unsoldered everything and resoldered it on the other side. 

# What's Next?

The next thing I will do is create my main project - the gesture-controlled robot.

# Schematics
<!-- Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resources to create professional schematic diagrams, though BSE recommends Tinkercad because it can be done easily and for free in the browser. -->


(https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. --><img width="1077" alt="Screenshot 2025-06-23 at 10 35 58 AM" src="https://github.com/user-attachments/assets/3361343b-8cfd-46c9-b240-7cd21a854c9d" />

Figure 1: Schematic of the Gesture Controlled Robot's hardware - Arduino UNO, L280N, 4 DC motors, 4 AAA batteries, and HC-O5

<img width="404" alt="Screenshot 2025-06-23 at 10 36 30 AM" src="https://github.com/user-attachments/assets/08002af4-b6ea-41a2-be5d-0f0e5a7ad2d7" />

Figure 2: Schematic of Bluetooth sending module (gauntlet) - HC-O5, MPU 6050, and Arduino NANO

# Code 


```c++

// Bluetooth to motor movement code - robot

#include <SoftwareSerial.h>        //includes library softwareserial

char data;                         //introduces variable DATA

int enA = 5;                       // sets motor pins
int in1 = 6;                       // in1, right top motor, in2 right bottom motor, in3, left top motor, in4, left bottom
int in2 = 7;
int in3 = 8;
int in4 = 9;
int enB = 10;


SoftwareSerial Bluetooth(2, 3);   //(TX , RX)

void setup() {
  Serial.begin(9600);             //begins serial monitor and sets 9600 baud
  Bluetooth.begin(9600);          //begins bluetooth search and sets 9600 baud
  
  pinMode(enA, OUTPUT);
  pinMode(in1, OUTPUT);           // Sets all ports as outputs
  pinMode(in2, OUTPUT);
  pinMode(in3, OUTPUT);
  pinMode(in4, OUTPUT);
  pinMode(enB, OUTPUT);
}

void loop() {
  
  if (Bluetooth.available()) {    // checks bluetooth buffezone 
    data = Bluetooth.read();      // sets variable DATA as bluetooth.read
    Serial.println(data);         // prints said DATA

   if (data == 'F') {             //If the data is F, B, L, R, or S, the motor movement aligns
      driveForward();
    } else if (data == 'B') {
      driveBackward();
    } else if (data == 'L') {
      turnLeft();
    } else if (data == 'R') {
      turnRight();
    } else {
      stopMotors();
    }
  }
}

void driveForward() {
  digitalWrite(in1, HIGH); digitalWrite(in2, LOW); analogWrite(enA, 255);  //Motor movement from in1,2,3,4, pins HIGH or LOW to deterime direction
  digitalWrite(in3, HIGH); digitalWrite(in4, LOW); analogWrite(enB, 255);
}

void driveBackward() {
  digitalWrite(in1, LOW); digitalWrite(in2, HIGH); analogWrite(enA, 255);
  digitalWrite(in3, LOW); digitalWrite(in4, HIGH); analogWrite(enB, 255);
}

void turnRight() {
  digitalWrite(in1, HIGH); digitalWrite(in2, LOW); analogWrite(enA, 255);
  digitalWrite(in3, LOW); digitalWrite(in4, HIGH); analogWrite(enB, 255);
}

void turnLeft() {
  digitalWrite(in1, LOW); digitalWrite(in2, HIGH); analogWrite(enA, 255);
  digitalWrite(in3, HIGH); digitalWrite(in4, LOW); analogWrite(enB, 255);
}

void stopMotors() {
  digitalWrite(in1, LOW); digitalWrite(in2, LOW); analogWrite(enA, 0);
  digitalWrite(in3, LOW); digitalWrite(in4, LOW); analogWrite(enB, 0);
}

// end

//Accelerometer Data code - gauntlet code

#include <Wire.h>              // library for I2C communication
#include <SoftwareSerial.h>    // library to use software-defined serial communication

// Set up Bluetooth communication on pins 2 (TX) and 3 (RX)
SoftwareSerial Bluetooth(2, 3); // bluetooth module connected to digital pins 2 and 3

const int MPU = 0x68;          // address of the MPU6050 accelerometer
float AccX, AccY, AccZ;        // variables to store the acceleration values
char lastCommand = ' ';        // to store the last command sent

void setup() {
  Wire.begin();                // starts IC2 communication
  Serial.begin(9600);          // starts Serial monitor communication
  Bluetooth.begin(9600);       // start Bluetooth communication

  // wakes up the MPU6050 by writing 0 
  Wire.beginTransmission(MPU);
  Wire.write(0x6B);            // accesses the power
  Wire.write(0);               // sets it to 0 to wake up the MPU6050
  Wire.endTransmission(true);
}

void loop() {
  // request accelerometer data starting from register 0x3B
  Wire.beginTransmission(MPU);
  Wire.write(0x3B);            
  Wire.endTransmission(false); 
  Wire.requestFrom(MPU, 6, true); // requests 6 bytes (X, Y, Z axes)

  // Combines high and low bytes to get raw acceleration data
  int16_t rawX = Wire.read() << 8 | Wire.read();  
  int16_t rawY = Wire.read() << 8 | Wire.read();  
  int16_t rawZ = Wire.read() << 8 | Wire.read(); 

  // Convert raw values to accx, y, z
  AccX = rawX / 16384.0;
  AccY = rawY / 16384.0;
  AccZ = rawZ / 16384.0;

  char command; // Command to be sent based on tilt

  // Decide which direction to move based on tilt:
  if (AccX > 0.3) 
    command = 'F';            // Tilt forward - Forward
  else if (AccX < -0.3) 
    command = 'B';            // Tilt backward - Backward
  else if (AccY > 0.3) 
    command = 'L';            // Tilt left -  Left
  else if (AccY < -0.3) 
    command = 'R';            // Tilt right - Right
  else 
    command = 'S';            // No tilt - Stop

  // Only send the command if it has changed since last time
  if (command != lastCommand) {
    Bluetooth.write(command);  // send the command to Bluetooth module
    Serial.println(command);   // also print to serial monitor for debugging
    lastCommand = command;     // update the last command
  }

  delay(100);  // Small delay to reduce how often data is sent (every 100 ms)
}
// end 

// Motor movement code

int enA = 5;
int in1 = 6;
int in2 = 7;
int in3 = 8;
int in4 = 9;
int enB = 10;

void driveforward(){
  digitalWrite(in1, HIGH);
  digitalWrite(in2, LOW);
  analogWrite(enA, 255);
  digitalWrite(in3, HIGH);
  digitalWrite(in4, LOW);
  analogWrite(enB,255);
  delay(1000);
}

void drivebackward(){
  digitalWrite(in1, LOW);
  digitalWrite(in2,HIGH);
  analogWrite(enA,255);
  digitalWrite(in3, LOW);
  digitalWrite(in4, HIGH);
  analogWrite(enB,255);
  delay(1000);
}


void stop(){
  digitalWrite(in1, LOW);
  digitalWrite(in2, LOW);
  digitalWrite(in3, LOW);
  digitalWrite(in4, LOW);
  delay(1000);
}


void setup(){
  Serial.begin(9600);
  pinMode(enA, OUTPUT);
  pinMode(in1, OUTPUT);
  pinMode(in2, OUTPUT);
  pinMode(in3, OUTPUT);
  pinMode(in4, OUTPUT);
  pinMode(enB, OUTPUT);

}

void loop(){
  
  driveforward();
  stop();
  drivebackward();
  stop();

}

```

<!--# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs.

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here. -->
