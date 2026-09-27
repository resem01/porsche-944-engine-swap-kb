# 07K ECU, Wiring, Factory Gauges, and Fuel System

## Engine-management evolution

The thread spans several generations of engine-management strategy.

### Early discussion

Options considered:
- modified OE Volkswagen ECU
- VEMS
- custom standalone systems

The 07K crank trigger is a 60-2 arrangement at the rear of the engine, so standalone control does not require a special trigger wheel on the flywheel.

Relevant page:
- [Page 15](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-15.html)

### Performance Electronics era

NineX/Boost Brothers later partnered with Performance Electronics around the PE ECU and a dedicated swap harness.

By 2020 the production harness was described as:
- fully labeled
- terminated for 07K sensors
- provisioned for Porsche firewall connections
- intended to support factory gauge integration

Source:
- [Page 131](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-131.html)

### Current Haltech era

Boost Brothers currently sells:
- Haltech Elite 750
- terminated 07K swap harness
- CAN wideband
- IAT sensor
- NA or turbo base tune

The current harness supports:
- crank sensor
- cam sensor
- ignition coils
- injectors
- VVT
- coolant temperature
- TPS
- IAC
- oil pressure
- fuel pressure
- boost control
- alternator
- tach output
- spare I/O

Current source:
- [Boost Brothers ECU/harness package](https://www.boostbrothersgarage.com/products/07k-standalone-ecu-swap-harness-package)

The current Haltech package supersedes the earlier PE product as the normal vendor-supported path.

## Throttle strategy

The current Elite 750 package is configured around:
- cable-operated VR6 throttle body
- conventional TPS
- separate IAC

The product page explicitly states that the offered Elite 750 configuration does **not** support DBW.

## Factory gauge integration

The development architecture intentionally retains Porsche senders where needed.

### Coolant temperature

The custom rear coolant flange provides:
- 07K coolant-temperature sensor → ECU
- Porsche 944 coolant-temperature sender → factory cluster

### Oil pressure

The oil-filter block provides ports for:
- ECU/data-logging pressure sensor
- Porsche 944 oil-pressure sender

The thread suggests using a tee or multi-port fitting when both are desired.

Relevant page:
- [Page 152](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-152.html)

### Tachometer

The PE-era harness and the current Boost Brothers harness both provide a tach-output strategy. Current vendor documentation explicitly lists a tach output with a universal connector.

### Boost/economy gauge

The thread noted that vacuum/boost display requires an appropriate manifold-pressure source or separate instrumentation; this was not automatically handled as part of the standard factory-gauge integration.

## Early-car wiring

The developers expected some early-944 firewall connector/pin differences.

Their approach:
- pre-pinned leads for normal Porsche firewall connections
- extend/relocate individual wires if the early chassis uses a different location

This remains an area that should be documented specifically on the project's 1985 chassis.

Source:
- [Page 123](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-123.html)

## Installation sequencing

Page 131 contains an important practical note: some engine wiring is much easier with the intake manifold removed. A builder can potentially reach some areas from below, but the preferred sequence is to complete inaccessible wiring before permanently installing the intake.

Source:
- [Page 131](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-131.html)

## Harness failure history

A later retrospective identifies the main documented kit-component problem:
- an early PE harness used incorrect resistor values for the coil packs
- the coils overheated
- the harness design was corrected
- the developers reported no subsequent recurrence

Source:
- [Page 161](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-161.html)

This failure should remain documented even though the current vendor has moved to a different ECU/harness architecture.

## Fuel system

Naturally aspirated and low-power builds can retain simpler fuel-system arrangements, but turbo power quickly changes requirements.

The development team recommended for turbo cars:
- Bosch 044-class pump
- power the pump from a dedicated ECU-controlled relay/circuit rather than relying on undersized factory Porsche pump wiring

Source:
- [Page 161](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-161.html)

The current full-kit page also specifies:
- Aeromotive 13136 fuel-pressure regulator

## Status

**Mature ECU/wiring path exists today.**

The historical PE harness remains relevant only for existing cars and development history; the current supported package is Haltech-based.
