# Patient-Health-Monitoring-System---IoT
In IOT based monitoring project designed for keep on time track on the health status of the patient and updating to doctor at remote location anytime. With this effective device, health status of a critically ill patient can be constantly monitored. It can be used to keep track of health of aged people who frequently have heart or blood pressure issues. The IoT project developed here is built on Arduino UNO. It is interfaced with ESP8266 Wi-Fi modem to connect with an internet router and access the cloud server. The Arduino is interfaced with LM-35 temperature sensor to sense the body temperature and a pulse sensor to read pulse rate  It continuously monitors the pulse rate and body temperature and updates them to an IoT platform. If any abnormalities are detected then system immediately sends notification to doctor. The IoT platform used in this project is ThingSpeak. Thingspeak has capabilities for Visualizing the collected data in the form of charts, Ability to create apps for collaborating with web services or social network and other APIs.  The data from ThingSpeak to android application will send by HTTP request and HTTP response protocol. A threshold value is being set for pulse rate and body temperature. In android application there will be separate  login credentials for patient and doctor. When the doctor will login, list of patients will be displayed along with two tags  Patient Details and  Health Status. In health status data from the Thingspeak will be fetched, doctor can check the medicine that the patient is consuming and can update is depending upon the health status. The patient can check the health status and medicine list and can also update details accordingly. Such a system consist of physiological data that stores, process and communicate through a local manner such as smart phones by using the system the health care professionals can monitor and advice their patient all the time. 
