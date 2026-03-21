# PDP-11 Test Code

This is a collection of very small pdp-11 assembly programs I have written for testing and demos.


## Building
```
macro11.exe .\test.mac -l test.lst
```

## Light Chaser
```
001000 012700  000001              MOV #1, R0
                               LOOP:
001004 006100                      ROL R0
001006 000005                      RESET
001010 000775                      BR LOOP
```

## Useful pdp-11 links
 * [Demo Programs](https://blog.tephra.me/pdp-11-40-test/)
 * [SpaceWar](https://github.com/MattisLind/SPACEWAR/tree/ar11-patch) (AR11)
 * [PDP-11 Diagnostics - Database](https://www.retrocmp.com/images/stories/joerg/pdp11_diagnostic_database/index.html)
 * [MACRO-11 Win32](https://github.com/j-hoppe/MACRO11)