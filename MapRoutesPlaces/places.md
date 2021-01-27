# Places API
This JSON return details Wattle & Daub Cafe in Bancroft Ontario, returning name, address components, phone number, business status, website and rating of the restaurant.

## Did not see any bugs

## URL
https://maps.googleapis.com/maps/api/place/details/json?place_id=ChIJa3whOtRl1EwRJHY-x81TCGk&fields=name,address_components,rating,formatted_phone_number,website,business_status&key=AIzaSyBhKkz8ahfRRGzlIcqXo0ioRK6zw_yZf6E

# JSON Return

"{
   "html_attributions" : [],
   "result" : {
      "address_components" : [
         {
            "long_name" : "26b",
            "short_name" : "26b",
            "types" : [ "street_number" ]
         },
         {
            "long_name" : "Station Street",
            "short_name" : "Station St",
            "types" : [ "route" ]
         },
         {
            "long_name" : "Bancroft",
            "short_name" : "Bancroft",
            "types" : [ "locality", "political" ]
         },
         {
            "long_name" : "Hastings County",
            "short_name" : "Hastings County",
            "types" : [ "administrative_area_level_2", "political" ]
         },
         {
            "long_name" : "Ontario",
            "short_name" : "ON",
            "types" : [ "administrative_area_level_1", "political" ]
         },
         {
            "long_name" : "Canada",
            "short_name" : "CA",
            "types" : [ "country", "political" ]
         },
         {
            "long_name" : "K0L 1C0",
            "short_name" : "K0L 1C0",
            "types" : [ "postal_code" ]
         }
      ],
      "business_status" : "OPERATIONAL",
      "formatted_phone_number" : "(613) 318-5455",
      "name" : "Wattle & Daub Cafe",
      "rating" : 4.7,
      "website" : "https://m.facebook.com/WattleandDaubCafe/"
   },
   "status" : "OK"
}"
