## My final project for COMM318 _Stories from Data_ (Fall2020)

### What are the costs to immigration and border enforcement initiative along the Southwest border and its sectors?

The establishment of Customs and Border Patrol and controversial initiatives have never been as contested as they are today, as many immmigration and border researchers believe it costs more to maintain border crossing sectors that their results. Specifically, they argue that border crossing/sectors established for the apprehension of illegal migrants, firearms, and drugs - and the cost fo staffing them- cost more than what they actually apprehend. Additionally, many immigration and border researchers, human rights activists and civil rights groups believe these initiatives don't actually deter illegal immigration, but force migrants to choose more dangerous paths in crossing the border, leading to more reported deaths and rescues.

Using CBP open data that details varialble statistics ranging from migrant deaths, migrant detainments, drug and firearm apprehensions, to staffing (by fiscal year for all sectors including an aggregate account for the southwest border overall), and my own created border patrol budget tracker spreadsheet, I explore the trends over time of the various variables mentioned, to answer the following questions: 

   __Apprehensions and Deaths__: Do DHS/CBP initiatives actually deter illegal immigration? Or do the initiatives just push migrants to choosing more hazardous crossing corridors that leads to higher death rates per fiscal year apprehension count? Are there sectors migrants favor more that are then targeted by initiatives that then push migrants to cross in other sectors?
        -More people crossing should be correlated with higher death count, but what if there is an increase in the migrant death rate but a decrease in apprehensions? This could mean that border crossing have become more dangerous overall 
    
   __Budget__: What do the increases in the budget look like once these initiatives are implemented? How does this translate to changes in staffing? 

   __Apprehensions and Deaths__: What's the breakdown of total apprehensions when it comes to family apprehensions, unaccompanied minors, and accompanied minors, and accompanied minors for each sector? What are the larger southwest border trends over fiscal years?

   __Apprehensions and Deaths__: How has violence changed along the US-Mexico border per year? Are there more rescues due to claims in the first question?
    
   __Drugs__: How have the amounts of drug seizures changed over time for the US-Mexico border? 
   
* Note: all data is in Fiscal Years, and run from October of the previous year to September of the year being described,  (not in calendar years)


#### For the purposes of this project, I focused on the following sectors and initiatives:
    
   __US-Mexico border crossings checkpoints/sectors__:
    
    - Arizona: Yuma, Tucson
    
    - California: El Centro, San Diego 
    
    - Texas: Del Rio, Laredo, El Paso, Rio grande Valley
    
    -Southwest border: aggregated count for all sectors above 

   __US-Mexico immigration and border security initiatives/programs__: 
    
    - Prevention through Deterrence Initiatives: initatives/programs that increased border security: staff, equipment and funding 

        - Operation Blockade: implemented in South Texas and Ciudad Juarez, Mexico, Sept. 1993
            - Sectors affected: Del Rio, Laredo, El Paso, Rio Grande Valley

        - Operation Gatekeeper: implemented in Southern California, 1994 
            - Sectors affected: El Centro, San Diego 
        
        - Operation Safeguard: implemented in Arizona, 1994-1999 
            - Sectors affected: Yuma, Tucson 

        - Operation Rio Grande: implemented in South Texas, 1997 
            - Sectors affected: Del Rio, Laredo, El Paso, Rio Grande Valley
   
        - Other initiatives: Secure Fence Act of 2006: authorized and partially funded the construction of 700 miles of fence/wall along the southern border (Signed October 2006)
            - Sectors affected: all sectors 


#### I also divided the data files I used into separate notebooks focusing on the the different themes of my research questions, defining each variable used for context: 

   __Apprehensions__: 
    
    - Family Apprehensions: families(either adults, children, or legal guardians) apprehended at the US-Mexico border with a family member 
    
    - Unaccompanied minors/juveniles Apprehensions: minors under 18 years of age apprehended at the US-Mexico border traveling alone 
    
    - Accompanied minors/juveniles Apprehensions: minors under 18 years of age 
    
   __Violence variables__: 
    
    - Deaths: reported deaths of migrants at the US-Mexico border who were verified or whose bodies were recovered 
    
    - Assaults: reported assaults of migrants at the US-Mexico border 
    
    - Rescues: reported rescues of migrants at the US-Mexico border who were reported, responded to, rescued and filed. 
    
   __Drugs__:
    
    - Marijuana: counts of marijuana that were seized at the US-Mexico border measured in pounds (lbs)
    
    - Cocaine: counts of cocaine that were seized at the US-Mexico border measured in pounds (lbs)
    
Each notebook outlines the process I used to answer my research questions, some observations and some interpretations. Using the results found, I answer my research questions fully in a mock academic report that can be found in the `Visualizing the Costs of Immigration
Enforcement and Border Security on the USMexico Border` pdf document in the `data_story_presentation` folder.

I hope everything is clear and that you enjoy the data! 

Acknowledgments: I would like to thank Jacob Kaplan from the University of Pennsylvania for web-scraping the stats and summaries data set files, collating them into various spreadsheets, and making them publicly available on ICPRS here: https://www.openicpsr.org/openicpsr/project/109522/version/V3/view. 

