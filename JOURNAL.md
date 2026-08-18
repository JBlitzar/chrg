
# Aug 17: Getting started

Got a rec from a peer to use IP6518. Architecture is:

- PD trigger in, else supply some lines
- IP6518 out per port

How many ports do I want? Probably more than two, but more than six seems excessive. Four is probably a good target for now.

Might buy a dedicated brick later, but charging off of laptop is fine for now, I guess.

Should I auto boost to some standard 20v or 24v in case PEBKAC plugs in a charger with weak PD that can't supply 20v? Probably not. I know my bricks. If no PG, it simply won't work.

Found a datasheet at https://www.tinytronics.nl/product_files/004122_IP6518-datasheet.pdf , schematic on page 8.

Yeah, made the rest of the design, copied it four times and changed the labels. Inductor sourcing was exciting but not too tricky. Ended up just putting one fuse. And I think LEDs for each is good UX. 

![](journal/schem1.png)

Time spent: 0.93 hours
