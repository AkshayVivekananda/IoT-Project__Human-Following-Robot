# **💫 IoT Project - HUMAN FOLLOWING ROBOT**

## **✨ Table of Contents**

<br>
<div align="center">
<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th>Sl No</th>
    <th>Title</th>
  </tr>
  <tr>
    <td>1</td>
    <td><a href="#project-title">Project Title</a></td>
  </tr>
  <tr>
    <td>2</td>
    <td><a href="#about-the-project">About the Project</a></td>
  </tr>
  <tr>
    <td>3</td>
    <td><a href="#circuit-diagram">Circuit Diagram</a></td>
  </tr>
  <tr>
    <td>4</td>
    <td><a href="#source-code">Source Code(https://github.com/AkshayVivekananda/IoT-Project__Smart-Gloves/blob/main/README.md#-circuit-diagram)</a></td>
  </tr>
  <tr>
    <td>5</td>
    <td><a href="#list-of-components">List of Components</a></td>
  </tr>
  <tr>
    <td>6</td>
    <td><a href="#setup-and-installation">Setup and Installation</a></td>
  </tr>
</table>
</div>

<br>

## **💠 About the Project**

This project is a **Human Following Robot** designed to track and follow a person using ultrasonic and infrared sensors. The **HC-SR04 ultrasonic sensor** detects the distance between the robot and the human, while **IR sensors** assist in obstacle detection and path correction. The **Arduino Uno R3** acts as the main controller, driving four gear motors connected to wheels, enabling smooth and accurate movement behind the target person.

Such robots are useful in scenarios like personal assistance, carrying loads, warehouse automation, and elderly assistance.

Working video of the project: *\[Add video link here]*

<br>

## **💡 Circuit Diagram**

<p align="center">
<img src="./Source%20Code%20and%20Circuit%20Diagram/Circuit%20Diagram.jpg" alt="Circuit Diagram" style="width: 500px; height: 300px;">
</p>

<br>

## **💻 Source Code**

The source code for the project can be found in the folder or downloaded from the following link: [SOURCE CODE](https://drive.google.com/uc?export=download&id=1Sb3FewUtpXnANqbu5UzagMpI6pIyiYNy)

<br>

## **🛠️ List of Components**

<br>

<div align="center">
<table border="1" cellpadding="5" cellspacing="0" style="margin: 0 auto;">
  <tr>
    <th>Sl No</th>
    <th>Name</th>
    <th>Image</th>
    <th>Quantity</th>
  </tr>
  <tr>
    <td>1</td>
    <td>HC-SR04 Ultrasonic Sensor</td>
    <td><img src="./Stock%20Images/hcsr04.jpg" alt="HC-SR04" width="200" height="100"></td>
    <td>1</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Gear Motors</td>
    <td><img src="./Stock%20Images/gearmotor.jpg" alt="Gear Motor" width="200" height="100"></td>
    <td>4</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Wheels</td>
    <td><img src="./Stock%20Images/wheel.jpg" alt="Wheel" width="200" height="100"></td>
    <td>4</td>
  </tr>
  <tr>
    <td>4</td>
    <td>IR Sensor</td>
    <td><img src="./Stock%20Images/irsensor.jpg" alt="IR Sensor" width="200" height="100"></td>
    <td>2</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Arduino Uno R3</td>
    <td><img src="./Stock%20Images/arduino_uno.jpg" alt="Arduino Uno R3" width="200" height="100"></td>
    <td>1</td>
  </tr>
</table>
</div>

<br>

*Note: It is advisable to purchase from a wholesale electronics dealer for lower prices. We bought our components from Vishal Electronics, SP Road, Bangalore.*
**Location map**: [Vishal Electronics, SP Road Bangalore](https://maps.app.goo.gl/qmP8eU92v7zgoXFd9)

<br>

## **⚙️ Setup and Installation**

1. **Download the Entire GitHub Repo**: [Human Following Robot](https://github.com/AkshayVivekananda/Human-Following-Robot/archive/refs/heads/main.zip)

   * Extract the ZIP file to access the project files.

2. **Assembling the Circuit**: Connect the HC-SR04, IR sensors, gear motors, and Arduino Uno R3 as per the circuit diagram.

3. **Configuring Arduino IDE**:

   * Open the Arduino IDE.
   * Connect your Arduino Uno R3 to your computer via USB.
   * Go to **Tools > Board > Arduino Uno**.
   * Select the correct port under **Tools > Port**.

4. **Uploading the Code**:

   * Open the `source.ino` file in Arduino IDE.
   * Click on **Upload** to upload the code to the Arduino Uno.

5. **Testing**:

   * Power the robot and walk in front of it to check if it follows you smoothly.
   * Adjust the sensor positions or motor speed in code if needed.

---

If you want, I can also **add a short working principle diagram** so it looks visually rich in your README.
Do you want me to add that?
