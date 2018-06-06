# practice
#plot the age of the universe vs redshift


import matplotlib.pyplot as plt
import numpy as np

plt.plot([1,2,3,4,5,7,8,9,10,11,12,13], [0.17,0.25,0.39,0.5,0.65,1.0,1.11,1.36,2.0,3.0,5.0,9.0])
plt.ylabel('Red Shift')
plt.xlabel('Universe Age in Billions of Years')
#plt.show()

plt.savefig('plot.png')
