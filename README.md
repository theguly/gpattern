fork of https://github.com/ickerwx/pattern

main differences:
- by default, the script creates
- you can use anything that starts with c to create, and with o to find offset (i'm lazy...)
- you can specify pattern length both in decimal and hex (thanks [phra](https://github.com/phra/))



examples:
- ./pattern c 60                 # creates the same pattern
- ./pattern create 60            # creates the same pattern
- ./pattern c 0x3C               # creates the same pattern
- ./pattern 60                   # creates the same pattern
- ./pattern o a1Aa               # given a default len of 8192, find offset for given pattern
- ./pattern off a1Aa             # same as above
- ./pattern off a1Aa 10000       # same as above, but given a pattern len 10000
- ./pattern off a1Aa 0x8000       # same as above, but given a pattern len 0x8000
