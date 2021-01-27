# Directions API 

I displayed my understanding of this JSON task by changing the origins and destination, Bancroft Library to the Bancroft Golf Course. I added in the mode of transport to biking.

## URL 

https://maps.googleapis.com/maps/api/directions/json?origin=North+Hastings+Public+Library&destination=Bancroft+Golf+Course&mode=bicycling&key=%20AIzaSyBhKkz8ahfRRGzlIcqXo0ioRK6zw_yZf6E

# JSON Response

```json
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJTdMO3uVk1EwRMKu4c6lM8gM",
         "types" : [ "establishment", "library", "point_of_interest" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJc8j0WZtl1EwRTsivepvRWfM",
         "types" : [ "establishment", "point_of_interest" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 45.0853064,
               "lng" : -77.8523568
            },
            "southwest" : {
               "lat" : 45.0569887,
               "lng" : -77.864588
            }
         },
         "copyrights" : "Map data ©2021",
         "legs" : [
            {
               "distance" : {
                  "text" : "3.7 km",
                  "value" : 3687
               },
               "duration" : {
                  "text" : "12 mins",
                  "value" : 715
               },
               "end_address" : "543 Hastings St N, Bancroft, ON K0L 1C0, Canada",
               "end_location" : {
                  "lat" : 45.0853064,
                  "lng" : -77.864588
               },
               "start_address" : "14 Flint Ave, Bancroft, ON K0L 1C0, Canada",
               "start_location" : {
                  "lat" : 45.05731410000001,
                  "lng" : -77.8523568
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 101
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 45.0569887,
                        "lng" : -77.8535548
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e on \u003cb\u003eFlint Ave\u003c/b\u003e toward \u003cb\u003eHastings St N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-62 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "eg_rGfpdzMf@xCVrA"
                     },
                     "start_location" : {
                        "lat" : 45.05731410000001,
                        "lng" : -77.8523568
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.6 km",
                        "value" : 3586
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 700
                     },
                     "end_location" : {
                        "lat" : 45.0853064,
                        "lng" : -77.864588
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eHastings St N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-62 N\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ee_rGtwdzMkHlDe@T[Na@PoB~@C@o@XmB~@WJ_@ROFaAb@cAb@}@ZuAl@{@`@iAh@oBpA}@~@QRo@j@GFg@j@[d@GHMRa@v@Uf@MVc@|@EJe@`ACBc@t@W^k@h@]VYNa@PYJUH{@Zq@RULa@Rs@b@w@j@o@j@}@t@}@j@w@`@w@Zk@Ng@Ho@H}AJmA?k@@mAA}@Cw@GqAMc@Gc@Ke@Ke@Mc@M]Kg@Sw@]c@S_@QWQYSm@_@mA_AAA}@s@_@YAA[Us@k@m@g@]Yg@_@m@]{@c@i@WmAa@QEi@Qq@MSEIAYEc@CEA]CI?YAo@Ck@DgAFc@BiBTq@HUDa@JC@]JODSHUHKDUHKD_@RA?_@TA@mA|@i@f@i@h@iAlAON}@nASX]j@oAtB]z@KVSh@_@hAe@fBCFMd@Oj@IZ"
                     },
                     "start_location" : {
                        "lat" : 45.0569887,
                        "lng" : -77.8535548
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "eg_rGfpdzM~@lFqIbEqDbBuExBqAj@aC~@qCnAiAh@oBpAoArAw@r@cApAU\\iBtDsAfCcAhAw@f@mCbAgA`@uAv@gBvA}@t@}@j@oB|@sAXmCTyB@kCEiCUgASkAYaAY_Bq@cAe@q@e@{B_B_Au@qB}AkAaAuA}@eB{@_Bg@yBg@cAKqBIsBLmCXgANe@LwAd@mAh@qBtAsApAyA|AqAhBmB`D}@|BwA~EYfA"
         },
         "summary" : "Hastings St N/ON-62 N",
         "warnings" : [
            "Bicycling directions are in beta. Use caution – This route may contain streets that aren't suited for bicycling."
         ],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
