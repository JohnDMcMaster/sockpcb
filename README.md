# sockext

Chip socket extension cable adapters.
They are primarily intended to be high quality fixtures for invasive chip analysis such as microprobing, laser fault injection, and EM SCA.

Example: BP Microsystems programmers are high quality but physically large.
Unfortunately this large size precludes it from being used to read out a chip on my probe station.
Solution: extend the socket from the programmer via ribbon cable to an adapter board on the probe station (dipext-pin + dipext-sock + cable).

Projects:
  * dipext-sock: converts an IDC connector to a ZIF40 socket. Also adds patch connections
  * dipext-pin: converts DIP40 pins into an IDC connector. Also adds patch connections
  * dipext-pin-r: like above but flips pins for backside analysis
    * WARNING: not updated for new pin order
  * dipspy: patch a chip similar to dipext-sock + dipext-pin w/o cables and such
    * FIXME: needs rev to use SMD to make solder easier

IMPORTANT: pin order was swapped at this rev to match crimp connectors:
  * dipext-sock_r3
  * dipext-pin_r6
  * WARNING: dipext-pin-r_r1 is not compatible / updated yet
