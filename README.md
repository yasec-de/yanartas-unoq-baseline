Yanartas "unoq-baseline" Pillowbox Payload
==========================================

This repository contains *unoq-baseline*, a payload for a [Yanartas
Pillowbox](https://ashen.yasec.de/yanartas-pillowbox) mesh that adapts the mesh's connectors to an [arduino uno
Q](https://docs.arduino.cc/hardware/uno-q/) shield as a super simple, baseline design for
[`ashen-firmware`](https://git.yasec.de/yasec/ashen-firmware) development.

> [!NOTE]
> This hardware has 

License
-------

© 2026 Dr.-Ing. Jan Sebastian 'jaseg' Götte

This project is licensed [CERN-OHL-S v2`](https://ohwr.org/cern_ohl_s_v2.txt).

LLM/AI Policy
-------------

This project does not accept LLM-generated contributions.

Known issues
------------

The arduino shield kicad footprint is flipped, so silk and connectors are on the wrong side of the board. It works, but
it doesn't look as nice and it's unnecessarily difficult to plug in the mesh.
