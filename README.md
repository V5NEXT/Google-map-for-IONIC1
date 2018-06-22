# Google-map-for-IONIC1
Google map Integration for IONIC 1 with custom lattitude and longitude

1 :Dependencies :

    ngMap - Directives to interact with Google Maps Javascript API
    ngCordova - For user Geolocation
    cordova-plugin-geolocation - To access the device gps info
    Google Maps Javascript API - API de Google Maps
    Google Maps Marker Clusterer - To create markers clusters in Google Maps
    
 2 :  ADD Cordova Plugin For Geo location :
   
   cordova plugin add cordova-plugin-geolocation (refer : https://cordova.apache.org/docs/en/latest/reference/cordova-plugin-geolocation/ )
   
 3 :  Also We need google map API key for coonecting to map : (It should be added in index file, for instace change my key)
   
   https://developers.google.com/maps/documentation/javascript/get-api-key

4 : We also need to add css in ionic.app.scss :

.scroll {
  height: 100%;
}

#map {
  width: 100%;
  height: 100%;
}

Please do reach me for any queries! Thank you!
