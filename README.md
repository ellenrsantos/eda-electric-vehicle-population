# 📊 Exploratory Data Analysis - Electric Vehicle Population Data.

![image](https://github.com/user-attachments/assets/ca8f4eb0-a7cc-4443-940c-4c4f7b8cd4e3)

# 📜 Context:
Is known that the automobilist market has been growing and changing for the latest years. One of the highest changes was the creation of the Electric Cars (EVs). 

The percentage of electric vehicles (EVs) in the United States varies by type of measurement¹:
- New vehicle sales: In May 2024, EVs made up 6.8% of new vehicle sales, while plug-in hybrid vehicles (PHEVs) made up 1.7%. Combined, EVs and PHEVs made up 8.5% of new vehicle sales. 
- Registered vehicles: Only 0.86% of registered vehicles in the United States are electric. 
- Adoption rate: The average EV penetration rate in the United States so far in 2024 is 6.8%, down from 7.5% in 2023.

Some analysts predict that EVs will make up 8% of vehicle sales in 2024, 14% in 2027, and 29% in 2030².

This particular database is about the two types of Electric Vehicles, EVs and PHEVs. 
- EVs³: All-electric vehicles, also referred to as battery electric vehicles (BEVs), have an electric motor instead of an internal combustion engine. The vehicle uses a large traction battery pack to power the electric motor and must be plugged in to a wall outlet or charging equipment, also called electric vehicle supply equipment (EVSE). Because it runs on electricity, the vehicle emits no exhaust from a tailpipe and does not contain the typical liquid fuel components, such as a fuel pump, fuel line, or fuel tank.
![image](https://github.com/user-attachments/assets/aab04879-b3b8-4d75-b49b-91f819d44047)

- PHEVs³: Plug-in hybrid electric vehicles (PHEVs) use batteries to power an electric motor and another fuel, such as gasoline, to power an internal combustion engine (ICE). PHEV batteries can be charged using a wall outlet or charging equipment, by the ICE, or through regenerative braking. The vehicle typically runs on electric power until the battery is nearly depleted, and then the car automatically switches over to use the ICE.
![image](https://github.com/user-attachments/assets/d225a0a3-3dd1-4b82-afe2-34a53e0815d0)

# 📖 Description:
For this analysis, I chose a open acess dataset available in Data Gov (link below) about the electric vehicle population. This dataset shows the Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) that are currently registered through the Washington State Department of Licensing (DOL).

Acess link (Open Acess): https://catalog.data.gov/dataset/electric-vehicle-population-data

# 💡 Insights:
- For the geographic distribution of EVs in the USA, it is noticed that the highest concentration of cars is in Washington. Is it correct to expect that only Washington state has EVs in the highest volume?

    - If we look only at the dataset, not the context, we will probably say yes, but that is not the correct answer. This mistake can happen when analyzing the dataset without understanding the source. 
    
    - The first question about this dataset is: Who provided this dataset? State of Washington. 
    
    - Thus, these data were collected by the state and provided to the community. It's noticed that some occurrences are from another state, but the number is smaller.
      
![newplot](https://github.com/user-attachments/assets/0918075d-2b70-42e3-8714-cd4c5514caee)
    
- The most common EVs are Tesla with two principal models (Model Y and Model 3). Second place is Chevrolet with two models also (Bolt EV and Volt). 

- In 2023, the highest quantity of EVs in the dataset. It could happen for two reasons: 

    - End of Covid pandemic.
    
    - Return to presential work and classes (high school/college).
![image](https://github.com/user-attachments/assets/f9b33f70-d664-4e80-aa99-4d31d6c13138)
    
- If you want a Battery Electric Vehicle (BEV), you can choose one of these brands: Tesla, Nissan, Chevrolet, VW, Ford, Kia, BWM, among others. 

- If you want a Plug-in Hybrid Electric Vehicle (PHEV), you can choose one of these brands: Toyota, Jeep, BWM, Chevrolet, among others.   




# 📌 References:

1 - https://www.edmunds.com/electric-car/articles/percentage-of-electric-cars-in-us.html#:~:text=The%20electric%20vehicle%20market%20share,according%20to%20Edmunds%20sales%20data)

2 - https://www.utilitydive.com/news/US-electric-vehicle-EV-adoption-slowdown-BOA-Bloomberg/719826/#:~:text=The%20EV%20penetration%20rate%20has,2027%20and%2029%25%20in%202030)

3 - https://afdc.energy.gov/vehicles/how-do-all-electric-cars-work
