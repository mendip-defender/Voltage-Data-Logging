### Voltage Logging of a 10 V reference using an HP 34401A

## The Gear
I have an old HP 34401A that I purchased from the bay of E. I also have a 10 V ref using an LTZ1000 ref as seen here, https://www.eevblog.com/forum/metrology/ultra-precision-reference-ltz1000/msg2785940/

## The Setup
No photos yet, but the referance and the multimeter are connected together using a twisted pair of test leads and bannan plugs on the ends. Its in my bedroom which does have a bit of a temp swing and later on I will also log that data with the setup.
Currently using a Raspberry Pi running Jupyter Notebook connecting to the 34401A via GPIB. I am using Hi-Z, and 6.5digit SLOW, display off. I do have 7 digits but that is because when in GPIB mode I get an extra digit free.
