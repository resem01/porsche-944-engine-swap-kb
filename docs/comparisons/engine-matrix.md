# Primary Engine Comparison Matrix

**Baseline Research Compilation v0.1**

The purpose of this matrix is screening, not final engineering release. Weight values are especially sensitive to
what was attached when weighed; see [Dimensions and Weight](dimensions-and-weight.md).

| Engine | Representative spec | Block | Stock output | Weight evidence | 944 swap maturity | Current support / principal issue |
|---|---|---|---|---|---|---|
| Porsche 944 NA M44 | 2.5L SOHC I4 | Aluminum | 143 hp / 137 lb-ft (US 1985) [S001] | 166 kg / 366 lb dry is repeatedly cited from Porsche workshop data [S002]; ~400 lb ready-to-run builder measurement [S009] | Factory | Baseline |
| Porsche 944 Turbo / 951 | 2.5L turbo SOHC I4 | Aluminum | 217 hp SAE / 243 lb-ft for early US Turbo; 220 PS European [S003] | Swap-ready comparison still needs a documented scale measurement | Factory | Factory performance/thermal/driveline baseline |
| Porsche 968 M44/43 | 3.0L DOHC 16V I4 | Aluminum | 236 hp US / 225 lb-ft; Porsche lists 240 PS / 305 Nm [S004][S005] | 172 kg / 379 lb dry reported from factory service data [S006] | High | Mechanically close to 944; donor scarcity and wiring are major issues [S025] |
| VW/Audi 07K | 2.5L DOHC 20V I5 | Iron | 170 hp / 177 lb-ft in 2008 Rabbit reference form [S007A] | ~355 lb dressed engine inferred from 447-lb engine+02J minus 92-lb 02J [S010]; ~380-400 lb swap-ready reports [S009][S011] | Very high | Most complete current non-Porsche ecosystem; Boost Brothers full kit [S008] |
| VW/Audi 1.8T 058 | 1.8L turbo DOHC 20V I4 | Iron | Output varies by donor/tune | ~353 lb dressed engine inferred from 445-lb engine+02J minus 92-lb 02J [S010] | High | Active MWR catalog plus multiple documented 315-450 hp 944/924-family builds; fabrication, booster and HVAC compromises remain [S013][S028][S029][S030] |
| Honda K24A2 | 2.4L DOHC I4 | Aluminum | 205 hp / 164 lb-ft (2006 TSX) [S014] | Builder weighing exercise shows ~240-320 lb depending exact configuration [S015] | Emerging | Running turbo 944 exists, but the 944-specific hardware path remains unproven; KPower does not currently support the 944 chassis [S016][S031][S032] |
| GM Ecotec | L61 proof-of-concept; LNF as comparison reference | Aluminum | LNF reference: 260 hp / 260 lb-ft [S018] | Consistent 944-ready weight still needs measurement | Limited but proven | Completed L61 turbo 944 retained factory torque tube and made 415 whp before later ECU work [S017] |
| GM aluminum LS | LS3 6.2L OHV V8 reference | Aluminum | 430 hp / 425 lb-ft current LS3 crate reference [S020] | LS1 ~447 lb and LS2 ~490 lb reported ready for 944-type installation [S011] | Very high | Mature multi-vendor history; G Force currently lists $2,565 core and $5,515 complete kits [S019][S033] |
| Ford 2.3 EcoBoost | Mustang longitudinal turbo I4 | Aluminum | 310 hp / 320 lb-ft US reference [S021] | No verified 944-ready weight in baseline | Low | Longitudinal donor architecture is attractive; September 2026 sweep still found no mature 944 kit/completed build [S022][S037] |

## Provisional feasibility-study engine

| Engine | Representative spec | Block | Stock output | Packaging evidence | Why it remains in study |
|---|---|---|---|---|---|
| Nissan VK56DE | 5.6L DOHC 32V V8 | Aluminum | 317 hp / 385 lb-ft (Titan reference) [S023] | Builder reports ~30 in long × 30 in wide × 33 in tall [S024] | Strong NA torque and growing adapter ecosystem [S026], but width/height, sump, steering and hood clearance are unproven in a 944 |

## Interpretation

At this stage, the **07K, 1.8T and aluminum LS** have the strongest commercial 944-specific support. The **1.8T** now has especially strong evidence of repeated track-car implementation, while the **07K** better preserves stock 944 engine-bay systems. The **968 3.0** has the strongest Porsche-native compatibility but weak donor economics. The **K24** has a documented running 944 but remains commercially immature. The **Ecotec** has a proven high-power historical installation with no current comprehensive kit found. **EcoBoost** remains a feasibility concept. **VK56** remains a formal feasibility study.

All source IDs resolve in [SOURCE_INDEX.md](../SOURCE_INDEX.md).
