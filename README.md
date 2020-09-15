
# ISY Net Energy Meter

![NetEnergyMeter](https://github.com/sjpbailey/udi-poly-ami-nem/blob/master/AMI_NEM_Poly_2.png)

## Added Watts for Instaneous Demand

![WattADDED](https://github.com/sjpbailey/udi-poly-ami-nem/blob/master/Update_Add_Watts.png)

The purpose of this Simple Nodeserver is to display/report, nodes for AMI Net Energy Meter within the ISY as AMI-NEM Meter.
Adds your Smart Meter in the Administrative Console instead of just in the Event Viewer.

* Supported Nodes
* Net Energy Meter
  * Instantaneous Demand Watts
  * Delivered kWh Today
  * Delivered kWh Yesterday
  * Delivered kWh Total

### Configuration

#### Defaults

* Default Short Poll:  Every 5 minutes
* Default Long Poll: Every 10 minutes (heartbeat)
* user: default_user
* password: default_password
* isy_ip: 127.0.0.1

##### User Provided

* Enter your admin user name, password and IP address to the ISY controller
* Save and restart the NodeServer
