# FinalProject_RutgersDS
FinalProject_RutgersDS
The following table summarizes all the variables in the dataset:
Variables	Type	Meaning
Total cost	continuous	the cost ($) incurred to Drivetime to buy the vehicles
Mileage	continuous	the total miles that the vehicles have travelled at the time of purchase
Vehicle.age	ordinal	The age of the vehicle at the time it was purchased by Drivetime
Vehicle.age.group	categorical	which age group the vehicles belong to: one-three, four+, six+ and seven+
color.set	categorical	the color of the vehicles
makex	categorical	manufacturer brands
state	categorical	where the vehicle is sold
make.model	categorical	the brands and the model of the vehicles
lot.sale.day	Continuous (independent variable)	Number of days the vehicles are in the lot before being sold
overage	Categorical
(class label)	“YES" means the lot.sale.days is higher than 90 days.
“NO" means the lot.sale.days is lower than 90 days.

Pairs plots are a powerful tool to quickly explore distributions and relationships in a dataset. Seaborn provides a simple default method for making pair plots that can be customized and extended through the Pair Grid class. In a data analysis project, a major portion of the value often comes not in the flashy machine learning, but in the straightforward visualization of data. A pairs plot is provides us with a comprehensive first look at our data and is a great starting point in data analysis projects.

![final1](https://user-images.githubusercontent.com/44449907/61760036-33f77380-ad98-11e9-9b41-2cded425fa24.png)
![final 2](https://user-images.githubusercontent.com/44449907/61760058-4671ad00-ad98-11e9-840e-35bd03edbb97.png)
![final 3](https://user-images.githubusercontent.com/44449907/61760079-51c4d880-ad98-11e9-911c-c19be2460c9f.png)
Here is the call to new function with new data row to get prediction. 
![final 4](https://user-images.githubusercontent.com/44449907/61760086-5be6d700-ad98-11e9-8dc8-44c8ed1e4388.png)

Flask App For entering new data and get predicted car value
![final 5](https://user-images.githubusercontent.com/44449907/61760106-63a67b80-ad98-11e9-9af5-903f51d59c74.png)
