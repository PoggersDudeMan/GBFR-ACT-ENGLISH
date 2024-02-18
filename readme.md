# GBFR-ACT-English

This is a forked version of [this repo](https://github.com/nyaoouo/GBFR-ACT).
The main goal of this version is an english translation and UI improvments.

## Granblue Fantasy Relink - Analytics for Combat Tracking

![img](./demo.png)

### Changes

   - Character names are displayed in english.
   - Now dark themed.
   - Numbers have comma separators.

### Setup Steps

1. **Install Python 3.11**
   - Download link: [https://www.python.org/ftp/python/3.11.6/python-3.11.6-amd64.exe](https://www.python.org/ftp/python/3.11.6/python-3.11.6-amd64.exe)
   - Note: It is recommended to install with administrator privileges.
   - Note 2: This script does not support conda environments well, it is advised not to use conda environments.
   - Note 3: Having multiple versions of Python installed may cause conflicts.

2. **Run act_ws.py or uac_start.cmd**
   - Double-click `act_ws.py` or `uac_start.cmd` to run. If there are no issues, a cmd window will pop up indicating that ACT has been successfully installed.
   - Note: Your folder may need to be in the same directory as Python to resolve certain issues.

3. **Open act_ws.html**
   - It is recommended to use Chrome browser to open `act_ws.html`.
   - Note: People have reported it is also working on Edge and Opera (and likely will on others).
  
## Accuracy
   - Does not appear to attribute debuff damage (such as burn or poison) to anyone.
   - Appears to accurately track all other damage instances reliably.
   - Numbers also 'match up' with other players using the combat tracker during a fight.
