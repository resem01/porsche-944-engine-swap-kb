# Dimensions and Weight

## Why this needs a strict method

Internet engine-weight figures are often incompatible. A bare long block cannot be compared directly with an engine
that includes manifolds, accessories, flywheel, clutch and conversion bellhousing. This project therefore records the
configuration with every weight.

## Common dimensional datums

For 944 packaging comparisons, record dimensions from:
- bellhousing / torque-tube mating plane
- crankshaft centerline
- frontmost crank pulley or accessory
- lowest sump point
- highest valve-cover/intake point
- widest intake-side point
- widest exhaust-side point

Overall bounding-box dimensions may be retained, but are secondary.

## Weight configurations

1. Bare long block
2. Factory dry engine
3. Dressed engine with intake/exhaust/accessories
4. Engine + flywheel/clutch
5. 944 swap-ready assembly including conversion bellhousing/adapters/mounting hardware

## Baseline evidence

| Engine | Configuration | Weight / dimension | Evidence | Status |
|---|---|---:|---|---|
| Porsche 944 NA | Factory dry | 166 kg / 366 lb | Secondary reports quote Porsche workshop manual [S002] | Needs primary manual scan |
| Porsche 944 NA | Manifolds/accessories/clutch/bellhousing, ready to run | ~400 lb | Builder report in Rennlist discussion [S009] | Useful comparison; exact configuration should be replicated |
| Porsche 968 3.0 | Factory dry | 172 kg / 379 lb | Factory-service-manual-derived reference [S006] | Good baseline; primary scan desirable |
| VW/Audi 07K | Fully dressed + 02J, no A/C | 447 lb | Shop scale data [S010] | Measured combined assembly |
| VW/Audi 02J | Transmission | 92 lb | Same scale source [S010] | Measured |
| VW/Audi 07K | Dressed engine inferred from above | ~355 lb | 447 - 92 lb [S010] | Inference; flywheel/clutch definition follows source |
| VW/Audi 07K | Bellhousing face to crank pulley relative to Porsche | 6.5 in shorter than Porsche 2.5 architecture | 07K development thread [S007] | Builder/development datum; direct remeasurement desirable |
| VW/Audi 1.8T | Fully dressed + 02J, no A/C | 445 lb | Shop scale data [S010] | Measured combined assembly |
| VW/Audi 1.8T | Dressed engine inferred from above | ~353 lb | 445 - 92 lb [S010] | Inference |
| Honda K24A2 | Various stripped/dressed states | ~240-320 lb | Builder progressively weighed components [S015] | Configuration-sensitive; do not quote as one engine weight |
| Aluminum LS1 | Swap-ready-type assembly | ~447 lb | Builder recollection with shorty manifolds, flywheel/clutch [S011] | Builder report |
| Aluminum LS2 | Accessories/manifolds/clutch/bellhousing | ~490 lb | Reported by 944 builder community [S011] | Builder report |
| Nissan VK56 | Overall builder bounding box | ~30 L × 30 W × 33 H in | Physical builder measurement [S024] | Screening only; not referenced to 944 datums |

## Immediate measurement priorities

1. Measure the 1985 944 chassis from torque-tube/bellhousing plane and crank centerline to hood, crossmember, firewall,
   steering shaft, brake booster and radiator envelope.
2. Measure a stock 944 NA engine using those same datums before removal if practical.
3. Obtain equivalent datum measurements for a candidate 07K donor.
4. Use these data to test the VK56 and other feasibility candidates before investing in adapter design.

Structured values are maintained in [data/measurements.csv](../../data/measurements.csv).
