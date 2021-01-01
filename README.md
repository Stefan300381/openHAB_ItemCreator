# openHAB_ItemCreator

A simple webpage that helps to create an \*.items file for openHAB 2.5.10 and 3.0 (using API Token, see below)

## How to use:
#### 1. clone or download the repository into you openhab html directory 
##### Example:
```
cd /etc/openhab2/html
git clone https://github.com/Stefan300381/openHAB_ItemCreator
```
#### 2. Make sure the file permissions are correct 
##### Example:
```
sudo chown -R openhab:openhab openHAB_ItemCreator/
```
#### 3. Browse to http://YOUR_OH_IP:YOUR_OH:PORT/static/openHAB_ItemCreator/index.html

Example Screenshot:
<br>
<img src="https://raw.githubusercontent.com/Stefan300381/openHAB_ItemCreator/dev/assets/demo.png" width="30%" height="30%">

#### Remark for openHAB 2.x vs 3.x:
The first field (API Token) should be ignored for openHAB 2 instances.
For openHAB 3 you need to create an API token first (and insert it here) to authorize any client using the REST web services.
To do so you, login to your local "create API Token" portal: 
```
http://OPENHAB_HOST:OPENHAB_PORT/createApiToken
```
<br>
<img src="https://raw.githubusercontent.com/Stefan300381/openHAB_ItemCreator/dev/assets/createAPIToken.png" width="30%" height="30%">
