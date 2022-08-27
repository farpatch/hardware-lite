# Farpatch Lite

A lite version of Farpatch -- a wireless debugger based on Black Magic Probe.

## Differences from the full version

* Farpatch Lite is smaller, and can fit into smaller areas
* There are no level shifters or voltage regulators -- your target MUST run at 3.3V!
* There are no damping resistors, which might affect signal integrity with the target
* There is no separate UART connector -- UART is integrated onto the SWD connector
* There is only one LED on the PCB

Farpatch Lite can be designed as a two-layer PCB, but a four-layer PCB stackup is preferred for signal integrity purposes.
