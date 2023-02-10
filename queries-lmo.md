# interesting-shodan-queries
Query Shodan interessante che hem trovad mi e di mè amis...

## Query

### Turbine a vent 
```
http.title:'Wind Turbine Control System'
```

### Pannei solar del Carlo Gavazzi
```
http.favicon.hash:-636619181
```

### Webterm Access Control
```
http.title:webterm
```

### Segnai di ZTL
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
### Segnai stradai che cambien in Australia
```
Saferoads VMS
```

### Generazzion del Pass Verd Europee
```
http.favicon.hash:-1955025782
```
Incoeu ghe n'è squasi nessun de europee, ma se pensa che l'è stada la manera che 'n quajvun gh'ha fad el pass verd a l'Adolf Hitler

### Cadena de pompista veneta
```
org:"GRUPPO NORD PETROLI SRL"
```

### Casse italiane
```
http.title:’cassa’ country:IT
```

### Statisteghe di pompista italian
```
http.html:'veeder root' country:IT
```
