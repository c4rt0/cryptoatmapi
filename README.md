## README

* This is going to be a simple REST API which returns details
  of cryptocurrency atms located in Republic of Ireland.
    * id
    * country
    * town
    * postcode  
    * nameOfStore
    * openingHours
    * twoWay
    * coordinates
        * Lat
        * Long
    
### Usage

First install json-server with npm:

```.bash
npm install -g json-server
```

Once successfull, run the server with:
```.bash
json-server --watch db.json
```
