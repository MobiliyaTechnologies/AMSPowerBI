# ASTRA PowerBI
## History Report
The report showcases trends of various capabilities of sensors which are tagged to an asset across time. 
It also shows the instances when rules applied on sensor groups are breached by a sensor(s).

### History-Data Page
The visual showcases trend of various capabilities with their units across time. 
It can be filtered to history dates till the sensor group is not deleted.
It shows following metrics on top left and right flip bars:
* Sensor for which data is being shown.
* Asset which is tagged with the sensor.
* Next refresh time of report.
* Last refresh time of report.
* Last instance of Sensor data in source.

### Rule-Triggers Page:

This visual showcases trends of sensors under sensor group for which a rule has been applied.
It shows if a sensor has breached rule or not. 
If it has it shows the details such as the time when the rule was breached and the trend of the sensor before and after breaching the rule. 
It can be filtered to history dates till the sensor group is not deleted.

It shows following metrics on top left and right flip bars:
* Sensor for which data is being shown.
* Asset which is tagged with the sensor.
* Time at which rule was breached last.
* Next refresh time of report.
* Last refresh time of report.
* Last instance of Sensor data in source.