# interesting-shodan-queries
Query Shodan interessanti trovate da me o da alcuni amici...

## Query

### Turbine a vento
```
http.title:'Wind Turbine Control System'
```

### Pannelli solari di Carlo Gavazzi
```
http.favicon.hash:-636619181
```

### Webterm Access Control
```
http.title:webterm
```

### Segnali variabili delle ZTL
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
### Segnali stradali variabili in Australia
```
Saferoads VMS
```

### Generazione del Green Pass europeo
```
http.favicon.hash:-1955025782
```

Oggi quasi nessuno in Europa, ma si pensa che è stato il modo che ha permesso di generare un green pass per Adolf Hitler

### Benzinai veneti
```
org:"GRUPPO NORD PETROLI SRL"
```

### Casse italiane
```
http.title:’cassa’ country:IT
```
### Statistiche di benzinai italiani
```
http.html:'veeder root' country:IT
```
