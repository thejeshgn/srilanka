Process used for creation:

1. Sri Lanaka has administrative 25 districts ( https://en.wikipedia.org/wiki/Districts_of_Sri_Lanka )
2. Sri Lanka has 22 Electoral districts, 1 for each district,  Theere are two exceptions; Jaffna (which covers the administrative districts of Jaffna and Kilinochchi) and Vanni (which covers the administrative districts of Mannar, Mullaitivu and Vavuniya).
( https://en.wikipedia.org/wiki/Electoral_districts_of_Sri_Lanka )
3. Now go to http://www.gadm.org/country
4. Download for Sri Lanka level 1 which is administrative district boundaries (http://biogeo.ucdavis.edu/data/gadm2.7/kmz/LKA_adm1.kmz). There are shapefiles too if you like them. http://gadm.org/

5. Add electoralDistrict and electoralDistrictCode parameters to each shape
6. Double check with district boundaries at http://www.statistics.gov.lk/misc/Map%20of%20Administrative%20District.pdf




electoralDistrict and electoralDistrictCode parameters

1. Ampara    - AMP
2. Anuradhapura - ANU
3. Badulla - BAD
4. Batticaloa - BAT
5. Colombo - COL
6. Galle - GAL
7. Gampaha - GAM
8. Hambantota - HAM
9. Jaffna (Jaffna and Kilinochchi) - JAF
10. Kalutara - KAL
11. Kandy - KAN
12. Kegalle - KEG
13. Kurunegala - KUR
14. Matale -  MTL
15. Matara - MTR
16. Monaragala - MON
17. Nuwara Eliya - NUW
18. Polonnaruwa - POL
19. Puttalam - PUT
20. Ratnapura - RAT
21. Trincomalee - TRI
22. Vanni (Mannar, Mullaitivu and Vavuniya) - VAN

- Its safe to filter by electoralDistrictCode to get the electoral district. 
- I have also created a merged file called LKA_electrol_districts.geojson

![process](https://i.giphy.com/12U5xhpCTfYHFS.gif)


![merging districts to form electrol districts](https://i.giphy.com/gopCCjGKErDqM.gif)

According to the constitution the Parliament should consist of 225 seats (members)
1. 36 seats were allocated to the nine provinces, four each (section 96(4)). A delimitation commission would apportion the four seats between the electoral districts in each province.
2. 160 seats were allocated to the electoral districts (section 98). An election commission would apportion the seats annually based on the number of registered electors.
3. 29 seats were reserved for the national list (section 99A).


