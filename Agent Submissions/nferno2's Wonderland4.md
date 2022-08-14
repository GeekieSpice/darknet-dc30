## 

+-+-+

QUEST: NFERNO2'S WONDERLAND4

+-+-+

Perhaps you've noticed at this point ADS-B tends to be displayed in hexadecimal instead of raw binary even if it doesn't make it easier to read always. Let's step up the challenge a bit. We intercepted another message from DARKNET1 this time it was:

`8DA4207F99406A8D685802EBFADA`

What is the sum of DARKNET1's current velocity (in knots) and heading (in degrees)? (Round down to the nearest whole knot or degree)

---

```
import pyModeS as pms  
pms.tell("8DA4207F99406A8D685802EBFADA")
```

```
             Message: 8DA4207F99406A8D685802EBFADA 
        ICAO address: A4207F 
     Downlink Format: 17 
            Protocol: Mode-S Extended Squitter (ADS-B) 
                Type: Airborne velocity 
               Speed: 149 knots
               Track: 135.27 degrees
       Vertical rate: -1344 feet/minute
                Type: Ground speed 

Process finished with exit code 0
```

Speed had a rounding error and should have actually been 150... i need to look into this

The correct answer was 285

