# What Sells a Car?

In this project I'm an analyst on the Crankshaft List. Hundreds of free vehicle advertisements are published on the site every day. I need to study the data collected over the last few years and determine which factors influence the price of a vehicle.

**We have the following parameters**
* Price
* Age of the vehicle when the advertisement was placed
* Mileage
* Number of cylinders
* Condition

**Data Description**

The dataset contains the following fields:

* price
* model_year
* model
* condition
* cylinders
* fuel - gasoline, diesel etc.
* odometer - the vehicle's mileage when the advertisement was published
* transmission
* paint_color
* is_4wd - If the vehicle is 4 by 4 (Boolean type)
* date_posted - the date the advertisement was published
* days_listed - days from publication to withdrawal

**Conclusion**

We see a clear relationship between the newer the car, the higher the price, and the more expensive it is with fewer kilometers. Automatic cars are clearly more expensive too. The most expensive colors are black, gray, red and white. White being the most common (analyzed earlier with .describe()). So the most expensive car would be a white car with low mileage, new and automatic.
