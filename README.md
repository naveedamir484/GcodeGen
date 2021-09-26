
# Gcode Generator Software (Version 1.0)

It is very difficult to find a software which can convert any type 
of image file into gcode and send it to the CNC machine parallelly at a same time after
maintianig the COM Connection and could see working progress visually. So combining 
all these functions into one I came up with this idea to develop this software. Whole
software is writting in python3 and Tkinter library is used to make User interface.


<h4>Link for Youtube Video: https://youtu.be/CsNLeWpOZ_k </h4>
<h4>Link for .exe (setup): https://drive.google.com/drive/folders/1q6yQTF9iraXVfrgFC2kPzPZUfiSWEtS-?usp=sharing</h4>


<p align="center">
  <img src="images/1.png"  width="350" alt="accessibility text">
</p>

# Contents

* Features
* Technology Used
* Note for contributors
* Feedback
* Developer

# Features


* This software basically has 7 modes to process differnt types of image and with differnt methods.
* User can adjust Contrast and Brightness and convert into greyScale before processing.
* User can send Gcode file directly to CNC machine using 7th mode "Gcode Sender"
* User can Visualise the Gcode file in 7th mode.
* Different Speed modes are availble such as Slow, Fast, Super-fast in Raster-Gcode, consequently compromise with the quality.
* Automatically convert reactangular image file into square internally during processing, to adjust CNC machine configuration. 
* User could send the gcode parallelly after maintaining the connection with CNC Machine or MicroController.
* Avalable Modes are :</b>

<b>1. Raster-Gcode:</b> 
Take Raster Images (*.jpg ,*.png) as input and generate Gcode file as Output along with live visualisation.There are modes for the quality of gcode to be Generated.

<b>2. Matrix Function:</b> Its a special function It divides the image into multiple rows and cols and append the gcode of each gridImage(ixj) successively. I made
This Option for Personal Use.  

<b>3. Hash Printing:</b> Take Raster Images (*.jpg ,*.png) as input and convert to HASHED image and then produce Gcode of the same. Com-Port connectivity is 
available along with live visualisation.  

<b>4. Dot Printing:</b> Take Raster Images (*.jpg ,*.png) as input and convert to Dotted image and then produce Gcode of the same.Com-Port connectivity is available 
along with live visualisation. 

<b>5. SVG To Gcode:</b>Takes *.svg image formate as input and Generate the Gcode file 

<b>6. DXF To Gcode:</b>Takes *.dxf image formate as input and Generate the Gcode file 

<b>7. G-code Sender:</b> G-code Sender to send the gcode file using COM-PORT communication or Bluetooth communication along with live Visualisation.



# Technology Used

* Python3, OpenCV2 
* numpy, Pillow  
* Image Processing concepts are used
* tkinter is used for User Interface.
* Serial library is used to Maintain COM port Connection.


# Note for contributors

* All Suggestions are Accepted and Wellcome.
* Fork repository and Contribute.
* Contact naveedamir484@gmail.com for any query.
* Extrace zip file or Clone this repository.
* Open this Project in Visual Studio.
* Open setup.py file and Run it ....Ready to go.

# Feedback
Feel free to report issues and bugs. It will be helpful for further upgradation of this website.

# Developer
<li>This software is open source and free to use for everyone.</li>
<li>Developed By: Naveed Aamir (MNNIT Allahabad)</li>
<li>Email: naveedamir484@gmail.com </li>
<li>Date: July 2021</li>
<li>Language: Python3</li>

