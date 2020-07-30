# Haugaland Kraft environment and electrical use comparing library

This library is ment to provide data for the functionalities presented in the prototype created by summer interns 2020 in the energy project. 
The librabry contains two methods that has a HashMap as a return value. The two methods both expects a amount of kWh as a parameter and includes as follows:


## ENERGY EQUIVALENTS 

- Washing machine (WM). Returns how many 60 degrees programs the given kWh is equivalent to. Based on 1 kWh per wash. 
Data found on the following [site](https://www.huseierne.no/hus-bolig/tema/okonomi/hva-koster-det-a-bruke-vaskemaskinen-na) 
- Tumble dryer (TD). Returns how many rounds the given kWh is equivalent to. Based on a A-rating dryer, 3 kWh per round.
Data found on the following [site](https://www.huseierne.no/hus-bolig/tema/okonomi/hva-koster-det-a-bruke-vaskemaskinen-na)
- Dish washer (DW). Returns how many rounds of a 65 degrees ordinary program the given kWh is equivalent to. Based on 1.05 per wash.
Data found on the following [site](https://www.tv2.no/a/6570978/)
- Light bulb (LB). Returns how many hours a 40 watt light bulb the given kWh is equivalent to. 
Data found on the following [site](https://blogg.fortum.no/hvor-mye-koster-lyset-i-lyspaera)
- Charge phone (CP). Returns how many times a phone with a mid sized battery can be charged with a capasity of 10 watt (Samsung G S10 and iPone XS). 
Data found on the following [site](https://www.tek.no/artikkel/i/xP71qp/sa-mye-koster-det-a-lade-en-mobil-til-100-prosent-hver-eneste-dag-i-et)
- Frozen pizza (FP). Returns how many fried frozen pizzas the given kWh is equivalent to. Based on 15 min, 0,55 kWh per pizza.
Data found on the following [site](https://www.los.no/om-los/energilosen/stromsparing/Sa-mye-strom-bruker-de-elektriske-apparatene/)
- Shower time (ST). Returns number of minutes of showering the  given kWh is equivalent to. Based on 0,558 kWh per minute, with a normal showerhead, 16 liters per minute.
Data found on the following [site](https://www.dinside.no/bolig/hvor-mye-koster-det-a-ta-en-dusj/60988994) 
-  Netflix streamtime (NS). Returns how many hours of streaming Netflix the given kWh is equivalent to. Based on 0.163 kWh per hour.
Data found on the following [site](https://www.carbonbrief.org/factcheck-what-is-the-carbon-footprint-of-streaming-video-on-netflix)  
-  Driving Tesla (DT) -> Returns of many km of driving a Tesla the given kWh is equivalent to. Based on a Model S 60, 0.181 kWh per km.
Data found on the following [site](https://www.tesla.com/en_EU/support/european-union-energy-label)
   
   
 ## ENVIRONMENTAL EQUIVALENTS
 All the given returns are based on [Duckys](https://www.ducky.eco) calculations that a kWh causes 0,128 kg of CO2-eq
   
 - Plane travel (PT). Returns how many airplane trips Haugesund-Oslo the emisson caused by the given kWh is equivalent to. Based on 85kg per trip.
 Data found on the following [site](https://www.dagsavisen.no/nyheter/innenriks/sa-mye-forurenser-flyturene-dine-1.434165)
 - Tree production (TP). Returns how many trees is needed to filter the emisson caused by the given kWh is equivalent to. Based on that one tree filters 250kg during a lifetime.
 Data found on the following [site](https://mossy.earth/pages/carbon-offsetting-guide)
-  Car trip (CT). Returns how many km of driving a fossil-powered car the emisson caused by the given kWh is equivalent to. Based on [Duckys](https://www.ducky.eco) data, 257g per km driven 
-  Meat production (MP). Returns how much meatproduction the emisson caused by the given kWh is equivalent to. Per 100 g, 105kg per
 Data found on the following [site](https://forskning.no/landbruk-mat-miljo/enorm-utregning-sa-ille-er-kjott-for-miljoet/259128)
-  Jeans production (JP). Returns how many jeans produced the emisson caused by the given kWh is equivalent to. Based on 33,4kg per
 Data found on the following [site](https://e24.no/naeringsliv/i/Jorp8b/fns-handelsorgan-klesindustriens-utslipp-er-stoerre-enn-fly-og-sjoefart)
 - Electric vehicle driving (EV). Returns how many km of driving a electric car the emisson caused by the given kWh is equivalent to. Based on [Duckys](https://www.ducky.eco) data 81g per km driven 
 
 
 
 
   
