This is a full REST API json server used for development purposes -  it acts as a simpler database for smaller applications. It is hosted on Heroku so it will power down after 30 minutes of inactivity - it will take a few seconds to start up the dynos the first time you use it. 
The data comes from the starting roster of the Chicago Blackhawks. 

As of 9/30/2019, it has only one route - /profile, which has 7 rsesources:
- id
- name
- position
- age
- birthplace
- gamesPlayed
- picture


