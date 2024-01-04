# Kali


Blackbird is a user name enumeration tool developed by Cyber Hunter Lab. This is one of the OSINT tools to find usernames across social media websites.

What is OSINT?
Open-source intelligence (OSINT) methods involve collecting, analyzing, and disseminating publicly available information to address specific intelligence requirements.

This information is gathered from diverse sources and distributed to the appropriate audience at the appropriate time.

Using these tools enables the comprehensive analysis and collection of information about a particular topic. However, the process can be laborious and time-consuming.

Blackbird Tool
This new user enumeration tool was developed by Cyber Hunter Lab and allowed to use only for Educational purposes.

The tool will check for over 581 websites within a second for a given username and display a graphical result.


The tool was found to be developed in React JS and is available to use with Linux, Mac, and Windows platforms.

According to the developers, the tool has over 1000 UserAgents to cross the information from the social media for the targeted username.

The tool can also extract data such as bio, location, and profile picture along with the username.

Features
Implement Flask Web Server to optimize UX
Export results in PDF
Implement metadata extraction
Publish a docker image
Deploy on Cloud
Export results in CSV
Installation
git clone https://github.com/p1ngul1n0/blackbird
cd blackbird

Install requirements
pip install -r requirements.txt

Usage
Search by username
python blackbird.py -u username

To Find Supported Websites
python blackbird.py –list-sites

To Use proxy
python blackbird.py -u crash –proxy http://127.0.0.1:8080
