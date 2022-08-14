## 

+-+-+

QUEST: NFERNO2'S WONDERLAND3

+-+-+

It is time to take a look at the actual code transmitted by ADS-B. Here is the first ADS-B message we intercepted from the aircraft in question:

`1000110110100100001000000111111100100011000100000001010010001011001110000101010100110001101101001000101100101001`

What is the aircraft's callsign?

---

```
import pyModeS as pms  
pms.tell("8DA4207F2310148B385531B48B29")
```

```
             Message: 8DA4207F2310148B385531B48B29 
        ICAO address: A4207F 
     Downlink Format: 17 
            Protocol: Mode-S Extended Squitter (ADS-B) 
                Type: Identification and category 
           Callsign:: DARKNET1 

Process finished with exit code 0
```

---
