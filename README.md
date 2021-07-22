# SomaSensorServer
Takes the quaternion data from the ESP32 Hub and creates a skeleton whose positions / rotations can be output as Vive Trackers

The server is run through the SomaSensorsVR_Gui. It takes the rotational data of the trackers and uses inverse kinematics to spit out the positions / rotations of the skeleton.

To use this, open SomaSensorsVR_Gui and "Select Client". Choose SomaDev_V2.0.exe and hit ok. Now the server should be connected to the GUI.
