# Intro-to-Continuous-Attractor-Networks

Continuous Attractor Networks produce a single, reliable estimate from multiple, imprecise and unreliable measurements. 
It is able, for example, to integrate measurements of altitude from barometers, accelerometers, and ultrasonic or laser 
rangefinders into one result. Each sensor may generate samples at different rates and sensors may drop out at any time. 
Laser rangefinders are very precise but if the laser light impinges on a non-normal reflective surface, there will be no 
light returned to the sensor and so no measurement - this is an example of what is called a 'drop-out'. This kind of 
non-linearity wreaks havoc for Kalman filters which is currently the most popular approach to multi-sensor fusion
