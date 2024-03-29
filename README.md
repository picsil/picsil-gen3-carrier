# picsil-gen3-carrier
A carrier board for Particle Boron with support for three OneWire or dry contact sensors, onboard 32KB FRAM and DS18B20 temperature sensor, and ESD protected sensor inputs.

## NOTE
There are known problems with this circuit. Be aware of this before using it, since you will need to make changes.

### Known issues:
- J1-J3 use the wrong footprint. It uses STX-3120-3BM (mono), where it should be STX-3120-3B (stereo).
- U4 uses the wrong footprint, at least for the parts I have. I was unable to find a part that uses the footprint in this design.
- D4 is potentially a problem. Consider removing it if unsure.
