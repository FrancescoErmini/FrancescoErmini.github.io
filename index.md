
# Scrazle (2021)
<img src="images/scrazle.png?raw=true"/>
## Modular, scalable and distributed web scraping API and price comparison tool.
This is a personal project but, since the tecnology stack used is a relevant part of my experience, it's worth to be mentioned.I developed a decoupled frontend/backend architecture (django-rest, vanilla js) with a distributed tasks queue system (celery) and in-memory database (redis) for orchestrating the scraping jobs and an headless browser (puppeeter on node.js) to emulate user actions (click, search, pagination) and extract the data. All web page interactions are done both manually (via xpath, css selectors..) or automatically (thanks to a huge javascript logic that I realised). I also used the natural language toolkit and elasticsearch.I wrote functional tests on the backend side with py-unit, documented all methods with sphinx and all REST end-points with swagger UI.

{% raw %} 
#python #javascript #django_rest_framerwork #node.js #celery #redis #postgres #elasticsearch #json-schema #fuzzy_search #docker-ce #micro-services #puppeeter_headless_browser #xpath #css_selectors #socks5_proxy #JWT_token #OAuth2 #xls #csv #json #natural_language_toolkit #tokenization #stemming #lemmization
{% endraw %}
---

# Forest Sharing (2020): Django web portal for forest data entries.
## From zero to production
<img src="images/forestsharing.png?raw=true"/>
### I managed the realisation end-to-end of the Forest Sharing portal (Django): from requirements to design,  testing, deploy and release process management. The portal allows a user to sign-up, login and submit his forest properties (cadastral parcels). On the backend side the portal allow to manage and aggregate those properties.

#Django #GeoDjango #Nginx #uwsgi #boostrap4 #ajax #jquery #Leafleat-js #django-forms #GDPR #release_management
---

# Precision PoP (2021): Web Gis Portal for monitoring the health of poplars.
## Dealing with Google Cloud API
<img src="images/pop.png?raw=true"/>
### I developed one web page for poplars healty monitoring; I used google earth engine python client (gee) to compute forest data on satellite imagery every five days and a javascript map library (leaflet) to fetch and display the results.

*** #python #javascript #spatiallite #sqlite #google_earth_engine #leafleat-js #node.js #google_cloud_api #geojson #decoupled-architecture #robustness ***
---

# Catasto Query Tool (2019): Reverse all cadastral parcels data from Italy cadastre WMS service.
## Genius “Hack” algorithm to solve lack of data entries.
<img src="images/catastoquerytool.png?raw=true"/>
### I ideate and develop a tool to solve a lack of data entries. The tool queries the italian cadastre register on all coordinate points obtained on a grid of million of points and retrieve both the parcel identifier and the geometry shape for the parcel found in that point. The tool is written in python and use multiprocessing/multithreading to speed up the algorithm.

#python #postgres #postgis #numpy #opencv #multi-threading #wms #gis #big-data #brute-forcing #hack #problem-solving #(sometime)iamgenious
---

# WarnMe (2019):  Road curvature alert system for bikers
## First Android App development
<img src="images/warnme.png?raw=true"/>
### I made a prototype of an  android application and a bluetooth device used to alert a biker for upcoming curvature level / hairpin turn. The curvature computation is done via python scripts using the open street map API on a well known route. The Android App uses GPS/Android location services to track user position and generate an alert when the biker is approaching the curve.

#java #android #python #arduino #open-streep-map #ESP32 #bluetooth #GPS 
---

# OpenInnovationDapps (2018): Ethereum smart contract + web portal for a pay to access resources demo.
## Blockchain development
<img src="images/openinnovationdapps.png?raw=true"/>
### I made a prototype of a “crowdfund” portal where the project is funded by crypto currencies (Ethereum) gathered  with user participation to the project and all transaction are recorded on the Ethereum blockchain as “smart contract”.

#solidity #javascritp #web3-js #Ethereum #blockchain #smart-contrac #ganache #cryptokittieslovers
---

# HackPax (2017): Cyber security alert / training system for employee.
## Winner project for course on startup creation
<img src="images/hackpax.png?raw=true"/>
### I attended a 4-month course for the creation of startups. The course had frontal lessons of lean startup that were put into practice by the realization of one's own business project; My project was named ‘Hack Pax’ and won the first prize at the final judgment.

#lean-startup #elevetor-pith #public-speaking #story-telling #minimum_viable_product #wow_effect #cyber-security #2017-ransomware-attacks #wannacry #zero-day #human-factor
---

# Vineyard register (2017): vineyard digital register
## Model view controller with Martin Fowler Patterns on Java (Java EE/JPA/Hibernate/Wildfly)
<img src="images/vineyardregister.png?raw=true"/>
### This is the project I made for the software architecture class. The idea of a vineyard register born speaking with a friend who work as winemaker for a small wine factory. The challenge was to create an quick data entries web page  as replacement of the current workflow made of  the papers and excel.

#Java-EE #JPA #Hibernate #JBoss #Wildfly #accountability-pattern
---

# MyHome503 (2015): DIY domotic with Arduino in my house
## Huge domotic installation of Arduinos in my house
<img src="images/myhome503.png?raw=true"/>
### I developed a burglar alarm from scratch in Arduino (c code), controlled via SMS and RFID, with call alert and siren sound. I developed a domotic system for remote light switches and irrigation control. I used the framework openhab as user's UI. I formed myself I culture on embedded devices(avr, arm), peripherals (uart,spi,i2c) and protocols (rs485,mqtt).
#Arduino #Raspberry-Pi #IoT #MQTT #RS485 #C #node-red #openhab #PCB #gsm #sms #phone_dialer #power_meters #humidity_sensor #pir_sensors #RTC #burglar_alarm #wiring #electrician #RJ45 #hundreds_of_euros_spent #10k+_Arduino_code
---

# IoT 802.15.4 Cryptographic keys exchange via NFC (2015)
## Junior Thesis 
<img src="images/xbee.png?raw=true"/>
---


<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
