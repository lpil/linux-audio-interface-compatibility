# Linux Audio-Interface Compatibility

A list of audio interfaces that have been tested with Linux. Hopefully this
will help some people answer the question of "does it work on Linux" before
spending some money.


## Devices

- ✓ [Allen & Heath XONE:K2](#allen--heath-xonek2)
- ✓ [ESI UDJ6](#esi-udj6)
- ✓ [Native Instruments Audio 2](#native-instruments-audio-2)
- ✖️ [Pioneer DJM-750MK2](#pioneer-djm-750mk2)

### Allen & Heath XONE:K2

✓ Working. Tested on Ubuntu 16.04.

USB, 0 inputs, 4 outputs.

http://www.allen-heath.com/ahproducts/xonek2/

### ESI UDJ6

✓ Working. Tested on Ubuntu 16.04.

USB, 0 inputs, 6 outputs.

http://www.esi-audio.com/products/udj6/

The headphone output is incredibly loud. Turning down the volume with the ALSA
mixer lowers the volume but not the noise floor, so you get a very noisy
signal not really suited for use with headphones. Would work well for 6 hot
signals going into an external mixer or such.

### Native Instruments Audio 2

✓ Working. Tested on Ubuntu 16.04.

USB, 0 inputs, 4 outputs.

https://www.native-instruments.com/en/products/traktor/dj-audio-interfaces/traktor-audio-2/

## Pioneer DJM-750MK2

✖️ Not working. Nothing appears to happen when plugged. Tested on Ubuntu 16.04.

USB, 10 inputs, 10 output (?).

https://www.pioneerdj.com/en-gb/product/mixer/djm-750mk2/black/overview/
