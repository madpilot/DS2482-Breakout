# DS2482 Breakout

Eagle layout for a breakout board for the Maxim DS2482 I2C to 1-wire chip

![https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/c822edcd17d805c57f6984b0aa2cb01e.png] ![https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/e076e6471cf0fa1e368f836e1539cffc.png]

*This is a work in progress! I just sent the boards off to OSH Park for etching, so I haven't confirmed it _actually_ works yet.*

## Components

1 x Maxim DS2482 Single-Channel 1-Wire Master
2 x 1.2k SMD resistors (Package: M0805 )

## Pin out of connector (looking component side up, connector on the left)

1: Vcc - Nominally 5V. You can use 3.3V but the pull up resistors probably nned to be changed
2: 1-wire - the 1-wire network wire
3: Ground.
4: The SCL pin on the I2C interface
5: The SDA pin on the I2C interface

## Ardiuno Same code

Coming soon...

## References

https://www.maximintegrated.com/en/products/interface/controllers-expanders/DS2482-100.html
