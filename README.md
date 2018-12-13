# Predicting-number-of-times-copper-is-processed-from-images

# Introduction 
# Severe Plastic Deformation (SPD) is a technique where tremendous strain is applied to the material. This process helps to improve yield stress, ductility and yield strength of the material. There are four methods by which SPD can be performed: High-pressure torsion; Twist extrusion; accumulative roll bonding; Equal channel angular pressing (ECAP). Of this four methods, we use ECAP on copper to improve it's conductivity too. After this process, the grain size and boundaries change. This difference in grain boundaries differe with the number of passes. In this project, we will get a sample with the known number of passes, and we will get another image and need to predict the number of passes the copper wire has gown through. 

#Difference after each pass
# The grain size(d) decreases as the number of passes increases. We can calculate grain size by drawing a line of length l on the image and counting the number of grains present on that line(n). Now we divide n by l to find the grain size (d).  
# We will measure the grain size of the train data, which will be a range for a particular pass. Now we will keep this as our base for our testing set and will find out % error in our predictions. 
