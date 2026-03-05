# Oculus-Prediction-Changer
Changes hertz (Frames Per Second) and Prediction Rate ( Default Settings 1000 and 1000 )
To keep it working in-game you have to turn on "Multi-tasking" inside of Advanced or Experimental depending on your headset.

# How It Works
 generates lots layered graphics depending on the rate and the power, it creates thousands of geometric shapes with transparency effects and rotations.

# How do i use it?
Prediction Power: Controls the number of layers drawn per frame (unlimited values)

https://github.com/user-attachments/assets/8be3c6e3-90be-4a77-ba0e-334959a98560


Prediction Rate: Sets the target frames per second (1-1000+)

Real-time FPS Display: Shows actual performance impact

On/Off Toggle: Start and stop the stress test instantly


# Understanding
// This single line runs 'power' times per frame, creating massive GPU load
for(let layer = 0; layer < power; layer++) { /* draw complex shapes */ }
