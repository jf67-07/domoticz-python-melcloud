# domoticz-python-melcloud
## History

This is a merge of
  https://github.com/tuk90/domoticz-python-melcloud.git
and
  https://github.com/nonolk/domoticz-python-melcloud.git

## Installation
1. Clone repository into your domoticz plugins folder
```
cd domoticz/plugins
git clone https://github.com/jf67-07/domoticz-python-melcloud.git 
```
2. Restart domoticz
3. Make sure that "Accept new Hardware Devices" is enabled in Domoticz settings
4. Go to "Hardware" page and add new item with type "MELCloud plugin"
## Plugin update

```
cd domoticz/plugins/Melcloud
git pull
```
## Testing without Domoticz
1. Clone repository
```
cd scripts/tests
git clone https://github.com/nonolk/domoticz-python-melcloud.git
```
2. Edit TestCode.py
```
Parameters['Username'] = 'xxxxxxxxxxxxx@xxx.xxx'  # your account mail
Parameters['Password'] = 'xxxxxxxxxx'             # your account password
```
3. Run test
```
python3 plugin.py
```
