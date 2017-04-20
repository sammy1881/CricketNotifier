# CricLiveNotifier

# MAC
Mac User can download the zip file which has standalone app. To run the app download it and run it via terminal: <br /><br />
./CricketNotifier.app/Contents/MacOS/CricketNotifier <br /><br />

To stop:<br /><br />

./CricketNotifier.app/Contents/MacOS/CricketNotifier stop<br /><br />

NOTE: The standalone app should run without installing any dependencies.<br /><br />

<br /><br />
Live Cricket Score Notification for MAC OS users<br /><br />
![img](http://i.imgur.com/LAxL7kI.png)<br />
![img](http://i.imgur.com/hYfzda9.png)<br />
![img](http://i.imgur.com/7b1dOvp.png)<br />
  - Over by Over Updates
  - Boundary Updates
  - Wicket Updates
  - Match Result Updates
  - Through OS build in Notification with Sound
  - Fetching data from CricBuzz live xml

# Requirements:

<h3>For MAC: If running the python script not the App</h3>

* [Beautiful Soup] - Python library for pulling data out of HTML and XML files.
* [lxml] - XML and HTML Parser for Python
* [python-crontab] - Crontab module for read and writing crontab files
* For better performance change Python Notification as 'Alerts' (after first run) at System preferences > Notifications > Python > Alerts

<h3>For Linux:</h3>

* [Beautiful Soup] - Python library for pulling data out of HTML and XML files.
* [lxml] - XML and HTML Parser for Python
* [python-crontab] - Crontab module for read and writing crontab files
* pynotify : Install it using "pip install pynotify"
* mplayer : If you need sound with your Linux Notification you'll have to install mplayer as the dependecy. In fedora it can be done with "sudo dnf install mplayer"


# How to Use:
Start
```sh
$ python CricLiveNotifier.py
$ 1: RSA vs ENG - 4th Test
$ 2: IND vs AUS - 4th ODI
$ Select your Match by Entering the Number > 1
$ Notification with sound (Y/N) > y
$ Auto Close Notification after seconds( 0 - 15 && manual close - 0) > 0
$ Done. Enjoy the match with CricLiveNotifier :)
```

Stop
```sh
$ python CricLiveNotifier.py stop
```
# License:
The MIT License (MIT)

# Bug Report:
Issue it here: https://github.com/sammy1881/CricLiveNotifier/issues

  [Beautiful Soup]: <http://www.crummy.com/software/BeautifulSoup/bs4/doc/>
  [lxml]: <http://lxml.de/>
  [python-crontab]: <https://pypi.python.org/pypi/python-crontab>
