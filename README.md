# Load cell calibration using Arduino

### [Description]

In this Project, I use a 5kg load cell with HX711 and Arduino Uno or mega. In this Project you will also see how to calibrate your load cell or strain gauge, Circuit diagram, Soldering, Programming and practical implementation.
### [The components and tools used in this project]

* [Arduino Uno](https://amzn.to/2tVz1vu) or [Mega 2560](https://amzn.to/2ze1kdu)
* [hx711](https://www.sparkfun.com/products/13879)
* [Load cell](https://www.sparkfun.com/products/14729)
* [Jumper Wires](https://amzn.to/2KMoVXs)
* [Digital Multimeter](https://amzn.to/2Nvft9i)
* [Wire Stripper](https://amzn.to/2KOqxfU)
* [wire cutter](https://amzn.to/2ucIq14)


 ## 1. About HX711
The HX711 Load Cell Amplifier accepts five wires from the load cell. These pins are labeled with colors; RED, BLK, WHT, GRN, and YLW.

![13879-SparkFun_Load_Cell_Amplifier_-_HX711-04](https://user-images.githubusercontent.com/39106620/65680633-453a5600-e04f-11e9-8654-81c20b12ce87.jpg)

These colors correspond to the conventional color coding of load cells, where red, black, green and white wires come from the strain gauge on the load cell and yellow is an optional ground wire that is not hooked up to the strain gauge but is there to ground any small outside EMI (electromagnetic interference). Sometimes instead of a yellow wire there is a larger black wire, foil, or loose wires to shield the signal wires to lessen EMI.
The four wires coming out from the wheatstone bridge on the load cell are "usually":

![2](https://user-images.githubusercontent.com/39106620/65681311-87b06280-e050-11e9-8346-c815dd671dad.PNG)

 ## 2. About Load cell
A load cell or a Strain Gauge is basically a Transducer which generates an electrical signal whose magnitude is proportional to the force applied. The various load cell types include Pneumatic, Hydraulic, and strain gauge.
In general, each load cell has four strain gauges that are hooked up in a wheatstone bridge formation as shown below.

![1](https://user-images.githubusercontent.com/39106620/65681265-6c455780-e050-11e9-9bbf-efc325504a6e.PNG)

Some load cells might have slight variations in color coding such as blue instead of green or yellow instead of black or white if there are only four wires (meaning no wire used as an EMI buffer). You might have to infer a little from the colors that you have or check the datasheet on the load cell, but in general you will usually see these colors.

  ## 3. Circuit Diagram
  Arduino, HX711 and Load cell
  
  ![hx711_bb](https://user-images.githubusercontent.com/39106620/65681972-e5917a00-e051-11e9-8dd1-ca983e845629.jpg)

 I had used Proteus to simulate the circuit :
 
 ![gg](https://user-images.githubusercontent.com/39106620/65682272-88e28f00-e052-11e9-8b9d-55e902df4631.PNG)

 
  
<p align="center"> *************************************************************************************************************************************</p>

