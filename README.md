# Webscraping Instagram with Python


---

## Purpose

This repo contains a couple of jupyter notebooks to be used for scraping posts from instagram on the basis of a hashtag.

The scripts are configured to be executible fully online, using [mybinder](https://mybinder.org) or a similar jupyter hub server environment. To use mybinder, use the badge below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kasev/webscraping_instagram/master)

---
## Authors
* Vojtěch Kaše [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)]([0000-0002-6601-1605](https://www.google.com/url?q=http://orcid.org/0000-0002-6601-1605&sa=D&ust=1588773325679000)), SDAM project, vojtech.kase@gmail.com

## License
CC-BY-SA 4.0, see attached License.md

---
# How to use this repository

## Sources and prerequisites

Data for the scripts are scraped directly from Instagram via its native API. The script is preconfigured in a way that the scraped data are automatically saved to sciencedata.dk. Thus, to have the scripts fully functional, you must have a sciencedata.dk account and be able to properly configure the [sddk](https://pypi.org/project/sddk/) python package.


### Software
* Python 3 with packages specified in requirements.txt

### Registered account
1. sciencedata.dk
2. google (optional)
3. github (optional)


---
## Installation
---
Click on the badge above and wait - mybinder will install all you need.


## Instructions 

1. setup your sciencedata.dk account and choose a folder where you want to save your data
2. launch the repository on mybinder using the badge
3. for a full integration with google, create a Google API key & Google Service Account Credentials files and upload them to your sciencedata or elsewhere (from where you can load them to your python environment).
4. use mybinder terminal with preinstalled git to get your scripts back to github 






