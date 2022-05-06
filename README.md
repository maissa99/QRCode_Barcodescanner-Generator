# QRCode_Barcodescanner-Generator-App
an application based on the QR code and barcode and it performs two tasks: 1) generation of a QR code from the data entered. 2) Scan a QR or barcode.
it is an application based on QR code and barcodes and it
performs two tasks:
1) generation of a QR code from the text entered.
2) Scan a QR or barcode.
So the application has two independent parts ,each performs a task.
-In the scan, the app asks for permission to activate the camera the
first time and then it will display a message
+ “PERMISSION_GRANTED” if the user accepts the activation of the
camera
+“PERMISSION_DENIED” if the user refuses the activation of the
camera
-Then a message will display that "scanner started" just aim the
 the QR code and the barcode with your camera and the results are going to be displayed at the bottom and they
will be saved automatically in a “Firebase” database
-If we exit the application during the scanning process, a message will
be displayed "scanner stopped".
-In the generation of the QR code, the user is asked to enter text
and click the "generate QR code" button to generate a code from
these and save the generated code in the gallery of the device 
by clicking on the “save” button.
-Once the application is uploaded, nothing could be simpler, a first activity
of progress is going to be displayed at the beginning then the menu activity and here you just have to
choose which option if generating a code or scanning a code and the
the result will be displayed if in the form of a link or a numeric code (in the case
scan) or in the form of a QR code with an image format (in the case of
generation).
