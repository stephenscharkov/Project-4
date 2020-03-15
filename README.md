#  Project 4: Plate Tectonics

# Infomation location:

  Code URL:https://github.com/stephenscharkov/Project-4/blob/master/code.ipynb
  
  README URL: https://github.com/stephenscharkov/Project-4/blob/master/README.md
  
# Problem Statement:

  This project was given to better understand noise levels underwater due to; rain, wind, marine animals, air guns, and earthquakes/ valcanic
  eruptions. For this project we will use data collected from profilers in the Juan de Fuca plate, which is off the west coast of the United 
  states and Canada, and the different situations we need to analyze. Using data from a Hydrophones we are able to analyze the situations of 
  intrest and analyze noice levels under the sea. The code is writen in python and will inform the user of noice levels in this ocean caused 
  by the many cases. 

# Results:
  
  
# Part 1: Wind and Rain Noise
  In Figures 1 to 4 the Power Spectral Density are shown agains frequency. The (a) graphs show the Oregon Shelf Cabled Benthic Experiment Package(OSCBEP) and the (b) graphs show the Oregon Offshore Cabled Benthic Experiment Package(OOCBEP). Graphs 1 to 4 are the following infromation 1:Rainy, 2: Windy, 3: Stormy, and 4: Dead.
  In the following graphs the following assumptions were made: 
  
    1. Data collected from the Hydrone is accurate
  
  ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Oregon%20Shelf%20Cabled%20Benthic%20Experiment%20Package%20Rainy.png)
  
  Figure 1.a: Location- OSCBEP, Status- Rainy, Time-  2019/01/20 16:09:49
  
  ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Oregon%20Offshore%20Cabled%20Benthic%20Experiment%20Package%20Rainy.png)
  
  Figure 1.b: Location- OOCBEP, Status- Rainy, Time- 2019/02/17 11:29:14
  
  ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Oregon%20Shelf%20Cabled%20Benthic%20Experiment%20Package%20Windy.png)
  
  Figure 2.a: Location- OSCBEP, Status- Windy, Time- 2019/01/02 00:09:49
  
  ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Oregon%20Offshore%20Cabled%20Benthic%20Experiment%20Package%20Windy.png)
  
  Figure 2.b: Location- OOCBEP, Status- Windy, Time- 2019/01/01 16:29:14
  
  ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Oregon%20Shelf%20Cabled%20Benthic%20Experiment%20Package%20Stormy.png)
  
  Figure 3.a: Location- OSCBEP, Status- Stormy, Time- 2019/01/06 19:09:49
  
  ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Oregon%20Offshore%20Cabled%20Benthic%20Experiment%20Package%20Stormy.png)
  
  Figure 3.b: Location- OOCBEP, Status- Windy, Time- 2019/01/04 14:29:14
  
  ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Oregon%20Shelf%20Cabled%20Benthic%20Experiment%20Package%20Dead.png)
  
  Figure 4.a: Location- OSCBEP, Status- Dead, Time- 2019/01/22 03:09:49
  
  ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Oregon%20Offshore%20Cabled%20Benthic%20Experiment%20Package%20Dead.png)
  
  Figure 4.b: Location- OOCBEP, Status- Dead, Time- 2019/01/19 23:29:14
  
  As seen in the comparison of rainy data (Figure 1.a & 1.b) and dead data (Figure 4.a & 4.b) the average ranges from ~10-15 PSD. For the comparison of windy data (Figure 2.a & 2.b) and dead data (Figure 4.a & 4.b) the average ranges from ~0-5 PSD. Based on these results we can conclude rian and wind do have an effect on the noice levels in the ocean witht the rain having a more impactful PSD level. The reason we are using two sits for comparing the noice levels is to varifiy if our trends of noice levels are the same and there is no miss reading or recording of data.  
  
# Part 2: Airgun, Marine Mammals, Earthquake/VolcanoNoise

In Figures 5 to 7 the frequency is ploted vs the time of a nocie under the water. There is a color bar on the side that shows the saverity of the data.
  In the following graphs the following assumptions were made: 
  
    1. Data collected from the Hydrone is accurate
  


 ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Axial%20Base%20Seafloor%20Airgun.png)
 
  Figure 5: Axial Base Seafloor: Airgun 
  
  ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Axial%20Base%20Seafloor%20Earthquake.png)

  Figure 6: Axial Base Seafloor: Earthquakes
  
  ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Oregon%20Slope%20Base%20Seafloor%20Marine%20Animal.png)

  Figure 7: Oregon Slope Base Seafloor: Marine Animal
  
  Compare the bandwidth of these three signals(1point). Are they consistent with what is shown in the Wenz curve(refer to the Ocean Noise slides)?
  
  In comparing the 3 figures above of the air gun (Figure 5), earthquake (Figure 6), and marine animals (Figure 7) we can see diffent patterns amerging that are similar to what we exepct from the Wenz curve. We can see that the air gun data is sharpe on ony occures for a couple of seconds with a frequency range between 0 to 5000Hz. The Earthquake has a range from 0 to 100Hz with a the largest frequenct occuring at the instance of the earthquake then decating to 0 after.The marine animal vary heavly on the spicies of the anmial and that can be seen the Figure 7. There are two differnt spices at this time segment but the overall frequenct band is the same (1000 to 5000Hz).
  
  
  ![alt text](https://github.com/stephenscharkov/Project-4/blob/master/Wentz%20Curve.png)
  
  
  # Conclusion:
  
  Accurate measurements of noice can be made using information collected from hydrophones due to the simaler to the Wenz curve.
  
  # References:
  
    https://ooinet.oceanobservatories.org/
    https://earthquake.usgs.gov/earthquakes/map/
    
    
