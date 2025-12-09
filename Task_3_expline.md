# line chart
question how does the product proice vary as we move through the data 
what I have do the line chgart need date so you could see trends over time so I try to cheat about this and use the index as the date so i can see the price how it move over index so when I do that using matplotlib to visula it I see it the price is over time movmemt is random there is no pattren I can see.
![line chart](line_chart.png)


# Bar chart
question how many item in each category 
so this we use to comparing gruops , from the data I count item in every category so I get that C has the high count then come D with 408 count then copme A with 403 count in the end come B with  378 so I see the distrbution is balncedna and range for all category it between below 450 and above 530 

![bar chart](bar_chart.png)

# Histogram 
we this to show the distribution for single numrical value
question how the product ratings distrubuted among customer
what I see that the chart show that the product ratings follow uniform distribution with more than 2300 count with mean 3 and alot of customer has give min rating 1 and 25% give  2.069490 and 50% give  3.082060 

![histogram](histogram.png)


# scatter plot
we use this to see the realatinship between two numarical varible
qestion are more expeinsive item get better rating
so I need to use scastter so it's price vs rating so does expeisive item get more ratings so 
what I see there something called correlation coefficaition that show like If we have x and y like if correlation = -1 that mean the when x get up then y get down if the correlation = 1 then if x up then y up so from my data I have calculated the correlation coefficition that it equil to 0.02 so the high price item have low ratings
![scatter](scatter.png)

# box plot or Pie chart
     box plot is good at show or comparing distrubition across diffrent group  , Pie chart good to show the parts of the must majority ot whole
so qestion how do price vary across diffrent category 
we can see Category B has the high median price 5499.0 and category A has the lowes 4745.0
  count         mean          std    min      25%     50%     75%  \
Category                                                                    
A         389.0  4782.910026  2702.106141  108.0  2593.00  4745.0  6943.0   
B         369.0  5410.330623  2758.644611  107.0  3182.00  5499.0  7960.0   
C         400.0  5086.802500  2858.905855  126.0  2746.75  4954.5  7429.0   
D         399.0  5032.468672  2896.589094  112.0  2541.00  5031.0  7575.5   

             max  
Category          
A         9997.0  
B         9919.0  
C         9974.0  
D         9988.0  


# Pie chart

qestion what is the proproation of item In stock vs out of stock 
Stock
In Stock        1513
Out of Stock    1497
so this show us that  the half of products are  unavailbe 

# Heat map
qestion are there any strong relationship between rating and price and discount 
I see that price vs rating  0.027 and price vs discount = 0.017 this show no strong correlation because the storng must be equil 1 to we can say predicatible
so this means the known the price tell us nothing about the rating and dicount

# ML predication
so in this I need trget varible I choose stock so  we need to pridicting stock status where an item is in stock or out of stouk 
so we need input that help could help us so I choose the rating and dicount why I choose this because customer buy item that have good rating and high dicount they become out of stock so the system must predict this demand or he will lose money

so this is classification machine learning problem to predict  stock status using discount and Rating as key driver of cusomer demand


