# Entone Settopbox IR

Supports the Entone settopbox on the Homey home assistant. 

Version 1.0.0 includes basic support for the Entone Kamai 400/500 series.
This includes:
- Power toggle
- Volume up/down/mute
- Channel up/down
- Switch to a specific channel

In the Netherlands this type of settopbox is used by T-Mobile Thuis.

Version 1.0.2 fixes a resource leak when sending signals.
Also the channel selector is repaired using enumeration for channels 0-99
to be used in the homey app and a text-field accepting a number for the flowcards.