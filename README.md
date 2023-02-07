# interesting-shodan-queries
Interesting Shodan queries found by me or by some friends...

## Queries 

### Wind turbine 
```
http.title:'Wind Turbine Control System'
```
### Webterm Access Control
```
http.title:webterm
```

### Italian crappy TRZ (ZTL) variable sign
```
<script> var IP1=
```
or
```
var MSGR1
```
ZTL = Trafic restricted zone, AP = Pedestrian Zone.

Basically every system now behind password. Protected ones are identifiable by:

```
Basic realm="Embedded-Device" country:IT
```

BTW, not every device in the scope of the query's a variable sign. Try:
```
Anteprima - Display
```
For public previews (and some protected backend!)

or...
```
Authentication on device failed : access denied.
```
### Australian Variable Road Signs
```
Saferoads VMS
```

### European Green Certificate Generations
```
http.favicon.hash:-1955025782
```
Hardly any European today, but it was the alleged way some people gave Adolf Hitler a Green Certificate

### Venetan gas station chain
```
org:"GRUPPO NORD PETROLI SRL"
```

### Italian Point of Sale
```
http.title:’cassa’ country:IT
```

### Italian fuel station stats
```
http.html:'veeder root' country:IT
```