# Takeaway Scores on the Doors

This is a Google Chrome Extension for displaying Scores on the Doors on JUST EAT and Deliveroo.

Clicking on the rating image gets you to the *Food Standards Agency* record for that restaurant.

* Uses *Food Hygiene Rating Scheme Application Programming Interface* ([FHRS API](http://api.ratings.food.gov.uk/Help)) to fetch the rating for each restaurant based on the business postcode and name.
* Uses [fuzzyset.js](https://github.com/Glench/fuzzyset.js) to analyse the similarities in restaurant names in case of mismatching.

Please note that this extension is *not perfect* and sometimes there might be some inaccuracies, if the data do not agree on both sides. That might mean, a business has changed location or name, but hasn't updated the records yet. Also, some restaurants might use a slightly different name on each takeaway to potentially attract customers, which could lead to mismatches.

## Install

[Install it via Chrome Web Store](https://chrome.google.com/webstore/detail/takeaway-scores-on-the-do/cgfblelihkaeaeliedhajkmjllcehbdp)

## Contribute

* Clone the code
* Make changes
* Under *Extensions* click *Load unpacked extension* and select the folder
* Make a pull request

## How it looks

### JUST EAT
![image](ss_just_eat.png)
![image](ss_just_eat2.png)

### Deliveroo
![image](ss_deliveroo.png)
