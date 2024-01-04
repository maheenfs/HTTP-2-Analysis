<img width="259" alt="image" src="https://github.com/maheenfs/HTTP-2-Analysis/assets/47178028/4c585d6e-0074-4055-896e-fea7c6e758b9"># HTTP-2-Analysis
Examination of Rapid Reset and other DDoS Vulnerabilities

**Experiment**

Tested individual binary frames:

Header
Data
Settings
Window_Update
GoAway 

Tested by sending a sequences:

HEADER, SETTINGS, and DATA frames
HEADER, DATA
HEADER, SETTINGS, WINDOW_UPDATE
HEADER, PRIORITY, PING


