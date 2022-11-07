# Diabetes_Classification
# Principle
We Want to measure blood glucose changes, according to the heartbeat to extract data, blood glucose changes and light have a relationship, we add two polarizers, if the first polarizer is a vertical angle, then the light passes through. 
The vibration of light will be up and down in the form of vertical propagation forward, and the light in other angle is offset by the polarizer, if the second polarizer is also vertical, then the angle and intensity of light will not change
However, if an active chemical is added between the two polarizers, the angle of light can be changed to act as a polarizer, and sugar level happens to be such an active substance that can change the angle of light, while the higher the concentration of sugar, the greater the change in the angle of light.
When the angle is changed to be perpendicular to the second polarizer, then no light will pass through at that time.

# Data
The data obtained at this stage are the ones recorded without adding blood glucose at 0.001 second intervals
The obtained graphs were processed by detrend, denoise, slicing, normalization feature selection and so on. Then we added the data of diabetic patients, which is equivalent to adding glycogen as an active substance to change the angle of light, and then we processed the obtained data and compared the two sets of plots.
