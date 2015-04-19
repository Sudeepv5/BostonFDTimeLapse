# Time Lapse
Working title - Project Crossbow!

Hosted project on Amazon S3:
https://s3.amazonaws.com/reapingcloud/TimeLapse/index.html

Descrition:
The application allows the user to view the locations and information about active food establishments and display any licensing data available if the establishment has a liquor license. User can move the sliders on page to see the number of restaurants that were issued liquor licenses in that particular range of time.

An async call is made to cityofboston.gov to retrieve the whole data at once and each restaurant is represented as a blimp on the map of Boston.

Setup:
Since some browsers do not allow cross-domain requests, I recommend on setting up a localhost and then run the index.html from there.


Datasets:
https://data.cityofboston.gov/Permitting/Active-Food-Establishment-Licenses/gb6y-34cq
https://data.cityofboston.gov/dataset/Liquor-Licenses/hda6-fnsh
