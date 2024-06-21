# Zones, Regions and Multi-regions

As of March 27, 2024, GCP has 40 regions and 121 zones across more than 200 countries and territories.

* Multi-region - 

1. US - Iowa, Toronto, Ashburn
2. Europe - London, Frankfurt
3. Asia Pacific - Mumbai, Delhi

Inside regions there are zones (Datacenter), So Region is Asia Pacific and zones are Mumbai, Pune, Kolkata means in all these cities google have their Datacenter.

Why we need multiple zones in one Region ?
* Due to High Availability, For any reason if one goes down another will be there, So It is suggested to distribute your data into multiple availability zones.
* There should be 100 miles (160.93 Kms) difference between any 2 zones. 


# Resource Hierarchy in Google Cloud

* Top Level       - Organization (contains all billing and accounts)
* Second Level    - Folders 
* Third Level     - Projects (associated with 1 billing account)
* Forth Level     - Resources (resource belong to 1 project only)

Resource > VM's and Storages or any resource / services

Note: In case of Personal account Organizations and Folders will not present. Will directly get Project (My project).

Tip: Always we setup permissions on Project and Resource level not on top level.

Note: Billing always works from Bottom to Top, because all bills will be paid by the organizations. 






