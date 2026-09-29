# 07K Completed Builds and Lessons Learned

The 07K swap moved beyond feasibility and into multiple running cars. This file captures the useful lessons rather than every project update.

## Original development cars

### Naturally aspirated development car

A naturally aspirated 07K 944 was used to validate:
- mounting
- oil-pan fit
- bellhousing/clutch
- cooling
- ECU integration
- factory gauge operation

The car was later dismantled so its components could be reused in a more extensive widebody/high-power project.

### Alan's turbo development car

The turbo development car became the principal proof-of-concept for the complete system.

By August 2021 the developers described it as:
- fully sorted
- running well
- having resolved mostly plumbing/installation issues rather than fundamental swap-architecture problems

Source:
- [Rennlist page 161](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-161.html)

### July 2020 first-drive/tuning state

Before final dyno development, Alan reported driving the turbo car at **12 psi on wastegate spring only**, with no added ignition timing or VVT tuning. The tuner monitored knock and reportedly found none through **18 psi** during development testing.

The planned base-tune strategy was:
- ~12 psi wastegate-spring mode
- ~18 psi electronically controlled mode
- user-selectable by switch if an EBC solenoid was fitted

The developer explicitly declined to publish final horsepower at that stage until tuning was finished and cross-checked on other dynos.

Source:
- [Page 143, post #2143](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-143.html#post16794139)

## Dyno evidence

During 2020 tuning, the development team reported power beginning with "4" on the dyno and later discussion references approximately **450 whp** for Alan's turbo car.

A later PE ECU package offered in the classifieds carried a **427 hp turbo tune**, showing another documented calibration state.

Sources:
- [Page 149](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-149.html)
- [Page 161](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-161.html)
- [Page 171](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-171.html)

Because the dyno, boost pressure, fuel, and calibration differ between references, these should be treated as separate tune states.

## Boost Brothers test mule — later published snapshot

Engine Swap Depot documented the Boost Brothers 944 test mule in November 2024 with:
- Garrett G25-660
- 350 hp
- 320 lb-ft
- lower-boost tune
- SPEC clutch
- stock Porsche torque tube
- factory five-speed rear transaxle

Source:
- [Engine Swap Depot](https://engineswapdepot.com/?p=123906)

## Additional completed/running builds

The thread continued to produce independent installations after the original development cars.

In August 2024, a builder with a 1989 Turbo chassis reported first start after following Alan's general architecture and using local fabrication for manifold/plumbing work.

Source:
- [Rennlist page 177](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-177.html)

This is useful evidence that the architecture can be reproduced outside the original development team, even when individual fabrication differs.

## Documented problems and fixes

### Oil-filter-block check valve

Symptom:
- lifter/head oiling noise

Initial suspicion:
- turbo oil feed location

Actual cause:
- faulty check valve in the oil-filter block

Resolution:
- component fault corrected; head oil-feed strategy retained

### Early PE harness coil-resistor problem

Symptom:
- ignition coils overheating

Cause:
- incorrect resistor values in early harness design

Resolution:
- harness specification corrected

### Engine installation difficulty

Builders reported difficulty engaging the last inch or two of installation when:
- clutch alignment was imperfect
- oil-pan/crossmember clearance limited engine angle
- crossmember was only partially lowered

Later recommendation:
- remove crossmember
- install upper/lower pan before engine installation
- minimize attached external components during drop-in

## Transmission considerations

The developers' practical guidance:
- NA transaxle: acceptable for naturally aspirated 07K
- turbo 07K: NA transaxle longevity becomes questionable
- 951 or 968 transaxle preferred as power rises
- 01E conversion is possible but requires additional fabrication

No single torque number should be treated as a guaranteed Porsche transaxle limit. During the July 2020 turbo-car development, the team was already discussing 951-transaxle life as boost/power increased, with 01E conversion presented as the higher-power alternative rather than as part of the basic swap.

Source:
- [Page 140](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-140.html)

## Weight distribution

The developers expected a modest improvement because the 07K package sits farther rearward than the Porsche four-cylinder, but the thread did not produce a robust before/after corner-weight dataset.

A 2025 discussion similarly suggested that the change exists but may not be dramatic enough for an average driver to notice.

Source:
- [Page 181](https://rennlist.com/forums/944-turbo-and-turbo-s-forum/803341-vw-audi-07k-2-5l-20v-i5-swap-thread-181.html)

## Best installation lessons from the thread

- Use the later revised timing-chain donor if possible.
- Treat the bellhousing/pilot-bearing geometry as a system; do not improvise one part without checking stack height.
- Complete inaccessible wiring before final intake installation.
- Install rear coolant flange before the engine goes in.
- Install pan/pickup/bellhousing/clutch/TOB before the engine goes in.
- Install exhaust manifold and power steering after the engine is in.
- Remove the crossmember rather than fighting the final engine-installation angle.
- Preserve factory gauge senders in parallel with ECU sensors.
- For turbo builds, upgrade pump power wiring rather than depending on old Porsche fuel-pump wiring.
- Do not treat early kit part numbers as current without checking the vendor's present documentation.
