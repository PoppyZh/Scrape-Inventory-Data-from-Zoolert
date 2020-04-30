
This is a small project about using python scripts to scrape and save the data from Zoolert.com. This is inspired by our 4-target-stores trip this week. I drove around in Brooklyn trying to find some cleaning supplies and disinfecting wipes. But I got nothing. Later I found zoolert. So I decided to write a script and monitor the restocking activities online. 

# About zoolert
Zoolert alerts consumers of restock of products both online and offline. During Cov19, the household items related to cleaning and disinfectanting are frequently sold out on Amazon. Zoolert allows users to set up alerts to track restocks. 


# Method

The notebook detailed how to extract home-related products from zoolert and their historical restocking data. The data is limited to 600 entries per product. To compose a complete picture, one needs to run the code multiple times and combine the data row-wise. The code will automatically extract the data and save it as a separate file using the date. 

# Results

Using the data I scraped from alst week, I did some simply visualization on when did the retailers restock products such as disinfecting wipes and hand soaps, and how long does the stocks last before it runs out again. See the notebook for more info. 
![](n_restocks.PNG)
![](retailer_byweekday.PNG)
