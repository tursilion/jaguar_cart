20161105

These cart layouts are for ExpressPCB and the newer ExpressPCB Plus (eventually I'll get them moved into KiCAD). They provide a single-chip Atari Jaguar cartridge layout. The first is tested, the second is partially tested and adds the EEPROM (and I like the rounded lines ;) ). They support 2MB (27C160) or 4MB (27C322) ROMs in 16-bit mode, which as far as everything I've tested goes, works fine.

You can find a tool that will patch your ROM images to run in 16-bit mode (as well as to drop on a universal fast-boot header that checksums the cart but is still patchable, but boots in 1 second instead of 5) here: https://github.com/tursilion/makefastboot

No warranty, no support, but if they work for you, enjoy.
