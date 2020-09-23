<div align="center">

## ^\!Play music directly to PC's Internal Speaker


</div>

### Description

Play music directly to PC's Internal Speaker
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[my name  is Nitin Jindal \(from Panchkula,Haryana\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/my-name-is-nitin-jindal-from-panchkula-haryana.md)
**Level**          |Intermediate
**User Rating**    |4.4 (75 globes from 17 users)
**Compatibility**  |C, C\+\+ \(general\)
**Category**       |[Graphics/ Sound](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics-sound__3-15.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/my-name-is-nitin-jindal-from-panchkula-haryana-play-music-directly-to-pc-s-internal-speake__3-7587/archive/master.zip)





### Source Code

```
/** Play music directly to PC's Internal Speaker PLEASE VOTE FOR ME ! Nitin Jindal */
#include <stdio.h>
#include <stdlib.h>
#include <dos.h>
#include <conio.h>
main()
{
float octave[7]={130.81,146.83,164.81,174.61,196.220,246.94};
int adn;
while(!kbhit())
{
adn=random(7);
sound(octave[adn]*10);
delay(190);
nosound();
}}
```

