# opencv-intruder-detection
Sample Project that uses OpenCV and Behavior Trees to  perform some action in response to detecting motion and facial recognition 

OpenCV for motion detection and face recognition.

Behavior Tree logic:

If motion detected: Start face recognition.

If face is known: Ignore.

If unknown face: Trigger alarm or send notification.

If no movement for a while: Enter power-saving mode.
