# 2AMD20-Knowledge-Engineering
**Research question:** FattenVall is a start-up power company that aims to establish the new charging infrastructure. For a different upcoming project, they want to place charging ports in the United States. Therefore, the research question now is to investigate at which locations is the highest demand and the largest market for electric charging stations for vehicles.  

**The data sources we used:**  
1.  Dataset: Electric Vehicle Population Data  
    Link: [https://www.kaggle.com/datasets/ratikkakkar/electric-vehicle-population-data?resource=download]  
2.  Dataset: Electric Vehicle Charging Stations in USA  
    Link: [https://developer.nrel.gov/docs/transportation/alt-fuel-stations-v1/all/#request-url]  
3.  Dataset: Kroger Store Locations Available for Research  
    Link: [https://data.world/xfu022]  
4.  Dataset: Target Store Dataset  
    Link: [https://www.kaggle.com/datasets/ben1989/target-store-dataset?select=target.csv]  
5.  Dataset: Walmart Store Locations across the United States  
    Link: [https://www.kaggle.com/datasets/thedevastator/walmart-store-locations-across-the-united-states]  
6.  Dataset: US Parking Data  
    Link: [https://www.kaggle.com/datasets/mfaisalqureshi/parking]  

**Data extraction:** This consisted in sourcing the files, opening them and keeping the relevant features for each. The relevant features we decided to keep were the geographical data, the number of occurrences of supermarkets, the number of occurrences of electric vehicles (EVs), charging stations, and total number of parking spots where available.  
**Data cleaning:** The data cleaning consisted of removing some entries that didn’t contribute knowledge to our question. A couple examples of such entries would be supermarkets with no parking lots, or charging stations that are owned by a Home Owners’ Association, which only allows members to use it. During this step we also extrapolated the zip codes from addresses in the datasets, as not all datasets included a zip code feature.  
**Merging:** To do this we first merged the datasets of supermarkets, creating a dataset of all candidate parking lots where we could add a charging stations. At this point we checked for EVs registered in each zip code, and charging stations located in them. Finally we merged the datasets using the zipcodes.  

**Conclusion:** This study aimed to support FattenVall in making informed decisions regarding the placement of EV charging stations, found that the area with highest demand is around the US state of Washington, with all the top zip codes being in the suburbs of Seattle or Portland, apart from Spokane. 
Through data integration, cleaning, and analysis, we gained valuable insights on factors such as charger traffic, EV numbers, and candidate parking lots. We were then able to use these insights to suggest valid answers to our clients. These findings offer actionable recommendations for FattenVall to establish an efficient and widespread charging infrastructure, contributing to the transition towards sustainable transportation and a greener future.  
