# VW/Audi 07K 2.5L I5 Swap

## Consolidated 07K technical reference

The 07K is currently one of the most developed non-Porsche engine swaps for the 944 platform. The long-running Rennlist
development thread began in 2014 and records the transition from feasibility work to running cars and commercial hardware
[S007]. Boost Brothers Garage now sells a substantially complete 944/07K conversion system [S008].

The forum material has been reorganized here by engineering subsystem rather than forum chronology.

### Technical sections

- [Donor selection and engine](donor-selection-and-engine.md)
- [Bellhousing, clutch, pilot bearing, and torque tube](bellhousing-clutch-torque-tube.md)
- [Oiling, oil pan, engine mounts, and installation geometry](oiling-and-engine-mounting.md)
- [Intake, exhaust, turbo, and throttle packaging](intake-exhaust-turbo.md)
- [Cooling, power steering, and air conditioning](cooling-power-steering-ac.md)
- [ECU, wiring, gauges, and fuel system](ecu-wiring-gauges-fuel.md)
- [Completed builds and lessons learned](completed-builds-and-lessons.md)
- [Development history](development-history.md)
- [Rennlist source map](source-map.md)

## Reference engine

A 2008 Volkswagen Rabbit 2.5 is a useful donor reference:
- 2,480 cc inline five
- DOHC, 20 valves
- cast-iron block / aluminum head
- 170 hp / 177 lb-ft [S007A]

The thread increasingly favored **2008-2010** engines as a practical donor sweet spot because they combine the revised
timing-chain system with the earlier mechanically controlled oil-pump arrangement. See
[Donor Selection](donor-selection-and-engine.md) for the early/late distinctions and crankshaft discussion.

## Why the engine is attractive in a 944

The original development thread reports the 07K as approximately **6.5 inches shorter from bellhousing face to crank pulley**
than the Porsche 2.5 architecture, with a block roughly 2.5 inches shorter. The rear timing-chain assembly extends behind the
nominal bellhousing plane, so that figure is a packaging clue rather than a complete engine-envelope measurement [S007].

The shorter front package permits the engine to sit farther rearward and creates useful radiator/front-accessory clearance.

## Current commercial conversion hardware

Boost Brothers' current full kit is listed at **$6,295** with an approximately six-week lead time at the baseline date [S008].
The vendor states that the system:
- bolts the 07K to the stock crossmember and torque tube,
- retains the stock crossmember, power-steering rack and vacuum brake booster,
- clears the factory hood,
- requires no sheet-metal modification,
- leaves passenger-side room for turbo hardware.

The current kit includes engine mounts, valve cover, oil-filter block, power-steering relocation hardware, bellhousing,
modified upper and baffled lower oil pan, intake manifold, cooling adapters, clutch and flywheel [S008].

Important: vendor statements remain attributed as vendor claims until independently verified.

## Weight evidence

S&P Automotive weighed a fully dressed 07K + 02J, without A/C, at 447 lb and the 02J separately at 92 lb [S010].
Subtracting gives an inferred dressed engine package of about **355 lb**. This is not the same as a 944 swap-ready engine
because the transmission/flywheel/clutch definitions differ.

Rennlist builder discussions place an iron-block 07K around **380-400 lb** in near swap-ready configurations and a stock
944 NA around 400-420 lb depending configuration [S009][S011]. The 07K's principal packaging advantage may therefore be
fore-aft length and rearward mass placement rather than a dramatic total-weight reduction.

## Documented Boost Brothers test mule

A November 2024 Engine Swap Depot article provides an independent published snapshot of the Boost Brothers development car
[S027]. It reports:
- Garrett G25-660 turbocharger,
- Boost Brothers intake manifold,
- **350 hp and 320 lb-ft on a lower-boost setting**,
- SPEC clutch,
- factory Porsche torque tube,
- five-speed rear transaxle.

The thread itself documents higher-output development states, including a 400+ whp dyno phase. These are different tune
states and should not be conflated.

## Current maturity assessment

**Maturity: Very high relative to other non-Porsche swaps.**

The conversion now has mature solutions for:
- bellhousing / torque-tube interface
- clutch / pilot bearing / hydraulic release
- oil pan and pickup
- engine mounts
- intake manifold
- cooling adapters
- power steering
- current standalone ECU/harness
- factory gauge integration

Areas that remain build-specific or underdocumented:
- air conditioning
- exact early-chassis wiring differences
- verified before/after corner weights
- long-term mileage data from multiple completed cars
- standardized turbo/exhaust/intercooler packaging
- configuration-defined complete swap-ready engine weight

## Thread-consolidation status

This is a **first-pass technical consolidation** of the thread using indexed Rennlist pages and targeted searches across the
major subsystems. Rennlist blocks direct automated retrieval of some pages, so this should not yet be represented as a literal
line-by-line review of every one of the 182 pages. The [source map](source-map.md) identifies the technically useful pages
retrieved in this pass and the remaining gaps for follow-up review.

## Source anchors

See [SOURCE_INDEX.md](../../SOURCE_INDEX.md): S007, S008, S009, S010, S011, S027.
