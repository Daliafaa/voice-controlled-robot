## Model

Jupyter notebooks for creating a TensorFlow Lite model for "wake word" recognition.

A pre-trained model has already been generated and added to the firmware folder.


## Firmware

ESP32 firmware built using Platform.io. This runs the neural network trying to detect the words  `Left`,  `Right`,  `Forward`  and  `Backward`.

The code assumes there are two continuous servos attached to the board such as the FS90R servo - these are readily available from various suppliers and you can normally buy them with wheels as well.

# 3dPrinting

This contains the 3d models that I used to build my 2 wheeled robot. It's designed around the FS90R continuous servos and a cylindrical power bank.
