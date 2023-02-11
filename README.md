# ANPR
We can see rise on smart cities lately with new promising technologies that helps shape a better & secure future. Automatic number plate recognitions is one of the
solutions.
Automatic Number plate recognition is an image processing technology which uses a license plate number to identify the vehicle details. Eliminating human intervention, making the overall process efficient, faster, secure and safe making it suitable for mass surveillance. It captures the image of vehicles plate and recognizes its
license number, can be assisted in the detection of stolen vehicles, identifying , owner details etc.
Our project presents a recognition method in which the vehicle plate image is obtained ,extracted and the image is processed to get the number plate information.
As mentioned, number plate recognition is an image processing technology which uses license plate to identify the registered vehicles
by first detecting the vehicle and then captures the vehicle’s plate image.
A Python code to detect the license plate and recongination.We achieve this by using three of its libraries; pytesseract, imutils, and
OpenCv that crops number plate to store it in some location and use that image as input to pytesseract (OCR) to extract text (License
plate number) extracted number is segmented as an image then character recognition (OCR) technique is used for the character
recognition.
•Taking an image of a car as input then Processes the input the image taken as the input undergoes processing to detect the part of
the car that is the license plate. Lastly Recognizing the number plate the values of the detected license plate are extracted from the
number plate image.
• OpenCV - We will use it to preprocess our image and also display the images that have undergone processing.
•Imutils - We will need this library to resize our images.
•Pytesseract - We will need this library to extract the license plate text from the detected license plate.
•The resulting data is then used to compare with the records on a database so as to come up with the specific information like the
vehicle owner, place of registration, address, etc. its performance is tested on real image.
