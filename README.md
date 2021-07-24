# Airbnb-seattle-Exploratory-data-analysis

## Installation Instructions:
  1. Download / clone the repository to local using below command.
  
     git clone https://github.com/Tara889/Airbnb-seattle-Exploratory-data-analysis.git4
     
  2. Create and activate Anaconda environment, using below command.
  
     conda create -n env-name python=3.6
     
     conda activate env-name
     
  3. cd into directory, install python dependencies using below command.
  
     pip install -r requirements.txt
     
  4. Once done, go to jupiyter notebook and run the notebook, command below.
  
     jupyter notebook
     
 ## Project motivation:
    This project is part of Udacity Data Science nanodegree program: Project write a blogpost
    
 ## File descriptions:
    
    1. Seattle Airbnb Dataset.ipynb -> Main jupyter notebook file(code)
    2. listings.csv -> Input data - Air Bnb Seattle listings data-set
    3. readme.md -> Instructions file
    
 ## Results:
    
   ### Questions of Interest
   1) What are the most common amenities?
      
   ![image](https://user-images.githubusercontent.com/87708828/126874722-9e2482dd-11b7-4497-a9e6-e290ac059be6.png)
     
    In the above chart you can see that the most common amenities in Seattle listings are:

    Internet
    Wireless Internet
    Heating
    Smoke Detector
    Essentials
    Whereas the least common amenities in Seattle listings are:

    Indoor Fireplace
    Hangers
    Elevator in Building
    Other pet(s)

   2) What are the features that attracts the guests most for renting a property?

   ![image](https://user-images.githubusercontent.com/87708828/126874848-591157b2-d1b9-468e-8a03-0f294f68b986.png)
    
    So for the answer of Question-2 ("What attracts the guests most for renting a property?") we can say that having a Washer/Dryer increases the booking rate for next 30 days       more than 15%. Also having a kitchen and allowing pets are good ideas for increasing the popularity for a listing.

    Also when comparing different room_types, an "Entire home/apt" is more than 10% more popular than a private room or a shared room. It looks like having a pool or serving         breakfast does not help a listing to be preferred, probably because of the increased price with these amenities.

   3) what are the attributes associated with the price of a listing?
    
   ![image](https://user-images.githubusercontent.com/87708828/126874889-a4e10f4f-11db-4f82-9883-5a5a782c8d89.png)

    The highest r-squared value is achieved with 79 features and the r-squared value is 0.6244

   4) What is the impact on price if it is be close to downtown?

   ![image](https://user-images.githubusercontent.com/87708828/126874910-7964f604-bcee-4d47-a1e9-75c58a33311f.png)

    As can be seen above, the 'distance_from_downtown' feature has a negative effect on price. As the distance from downtown increases, the price of listing decreases. For one       kilometer additional distance from downtown, the price of listing decrease around 3 USD.
    
