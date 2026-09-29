# Porsche 968 3.0 — Wiring and Integration Notes

Sources: S025, S025A, S036.

## Later 944 / S2 conversion pattern

The best documented 968 conversions are into later 944S/S2-family cars because the electrical and mechanical architectures are
closer.

Builders commonly retain:
- S2 bellhousing
- S2 flywheel
- S2 torque tube
- S2 transmission

and transplant:
- 968 engine
- 968 engine harness
- 968 DME
- MAF
- related sensors/intake hardware

## Critical DME-power detail

Builder documentation identifies **DME pin 27** as requiring switched Terminal 15 power.

In the 968 this path is associated with the 14-pin diagnostic/alarm connector. If the donor alarm/start-enable path is omitted
without recreating the switched supply, the engine will not run.

A 2016 follow-up thread provided a full wiring change chart/pinout around this issue [S036].

## Early-car implication

The project's 1985 944 will require more electrical adaptation than an S/S2 conversion:
- connector families differ,
- gauge/sender integration differs,
- starter/charging circuits must be mapped,
- alarm/ignition-start functions cannot simply be copied from a late car.

Therefore an early-944/968 swap should be planned as:
1. mechanically Porsche-native,
2. electrically a custom integration project.

That is a materially different risk profile from the same engine installed into an S2.
