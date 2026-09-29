# VW/Audi 1.8T 20V Swap

## Baseline status

The 1.8T is an established 944 conversion with **active commercial support** from Motor Werks Racing (MWR) [S012][S013][S028].
The September 2026 sweep strengthens its maturity rating: MWR is still selling the core installation system and a broad
supporting catalog, and it documents multiple completed 944/924-based track cars at substantial power levels.

## Engine selection

MWR specifically supports the **058-base 1.8T**, documented for:
- Audi A4 1997-1999
- Volkswagen Passat 1998-1999

MWR does **not** support the later 06A because its chain-driven oil pump increases the engine's effective length [S013].

The factory AEB harness and ECU can be retained with OBD2 capability, but wiring modification is required and ECU tuning is
strongly recommended. The system is not plug-and-play [S013].

## Chassis/drivetrain integration

MWR's installation hardware mates the 058 block to the Porsche torque-tube architecture.

The current FAQ states that the installation/mount system fits manual-transmission:
- 1983-1989 naturally aspirated 944
- 1987-1988 924S
- 944S
- 944 Turbo
- 944S2

Turbo/S2 cars require a naturally aspirated 944 bellhousing and starter ring. The standard conversion retains the Porsche
5-speed transmission, torque tube, clutch hydraulics, and starter [S013].

MWR also documents higher-power cars converted to Porsche 986/987 cable-shift gearboxes rather than retaining the original
016-family transaxle [S029][S030][S044].

## Current commercial ecosystem

The September 2026 MWR catalog includes [S028]:
- engine installation kit — from $1,899
- subframe/engine-mount kit — from $1,599
- oil manifold
- water-fitting/manifold kits
- electric water pump/controller
- intake manifold
- multiple turbo/header packages
- oil cooler
- radiator
- intercooler
- electric fan kit
- 350+ hp clutch kit for the NA gearbox
- brake-booster delete kit
- engine-refresh/internal parts

Many parts are built in batches or to order. MWR states typical pre-order lead time of about **6-8 weeks** for applicable
made-to-order parts [S028].

## Brake booster, HVAC, and fabrication

MWR explicitly states:
- additional fabrication is required,
- its listed intake requires brake-booster removal; a custom intake or booster modification can retain assist,
- the standard conversion was developed for track use,
- factory A/C and heat are **not supported**,
- automatic-transmission chassis are not supported [S013].

These limitations distinguish the 1.8T from the current 07K system, whose vendor architecture is designed around keeping
the stock brake booster and more of the factory engine-bay arrangement.

## Transmission durability

MWR reports successful use of the naturally aspirated 944 gearbox in its track builds at **up to about 320 whp** over roughly
eight years of experience. For higher output it offers/uses Cayman-family gearbox conversions, which it describes as suitable
to roughly 500 whp [S013].

This is vendor experience, not a guaranteed transaxle torque limit.

## Documented completed builds

### 1988 Gulf Tribute
MWR documents [S029]:
- 315 hp / 365 lb-ft
- K04 Sport turbo
- Maxx standalone ECU
- 986 cable-shift 5-speed
- rear-mounted alternator
- 2,350-lb track-car weight

### 1983 FATurbo Express
MWR documents [S044]:
- 345 hp / 300 lb-ft
- Garrett GT2860RS
- 986 gearbox
- rear-mounted alternator
- manual brakes

### 1987 Rothman's / GTP-style build
MWR documents [S030]:
- 450 hp / 395 lb-ft
- 8,000-rpm limit
- BorgWarner 6758 EFR
- 987 gearbox
- 2,050-lb completed track-car weight

These are vendor-documented builds, but they establish that the conversion family has moved far beyond a one-off prototype.

## Weight evidence

S&P Automotive measured a fully dressed 1.8T + 02J, without A/C, at **445 lb**, and an 02J at **92 lb** [S010].
The resulting inferred engine-package weight is roughly **353 lb**, but this is not directly equivalent to 944 swap-ready trim.

MWR publishes lower package-weight claims elsewhere; because the component definitions differ, this project does not mix those
figures into one "engine weight."

## Current maturity assessment

**Maturity: High.**

Strengths:
- current commercial conversion hardware
- multiple completed 944/924-family cars
- factory ECU option
- broad VW/Audi tuning ecosystem
- proven 300-450 hp track configurations

Limitations:
- fabrication remains necessary
- brake-booster conflict with standard MWR intake
- no standard A/C/heat solution
- 058-specific donor requirement
- higher-power builds often migrate away from the original Porsche gearbox

## Source anchors

See [SOURCE_INDEX.md](../../SOURCE_INDEX.md): S010, S012, S013, S028, S029, S030, S044.
