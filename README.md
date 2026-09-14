# PVsyst 100 kWp Grid-Connected Rooftop PV Design

A grid-connected rooftop solar photovoltaic system design and performance simulation completed using **PVsyst**. The project evaluates the technical performance of a 100 kWp-class rooftop PV system designed for Kilinochchi, Sri Lanka.

The study includes PV module and inverter sizing, string configuration, 3D near-shading modelling, electrical mismatch analysis, inter-row pitch optimization, tilt-angle analysis, and system-loss evaluation.

## Project Objective

The objective of this project was to design and simulate a rooftop grid-connected solar PV system and assess how array geometry, shading, module orientation, pitch, tilt, and electrical configuration influence energy yield and performance ratio.

## Software Used

- PVsyst V8.1.5
- Meteonorm 9.0 meteorological dataset
- PVsyst 3D near-shading scene and loss analysis tools

## Project Location

| Parameter | Value |
|---|---|
| Location | Kilinochchi, Sri Lanka |
| Coordinates | 9.3840° N, 80.4087° E |
| Altitude | 29 m |
| Time zone | UTC +5:30 |
| Meteorological data | Meteonorm 9.0 synthetic dataset |
| Ground albedo | 0.20 |
| System type | Grid connected |

## System Configuration

| Parameter | Value |
|---|---|
| Target PV capacity | 100 kWp class |
| Installed DC capacity | 105 kWp |
| PV module type | 550 Wp monocrystalline bifacial module |
| Total number of modules | 190 |
| Inverter rating | 100 kWac |
| String configuration | 10 strings × 19 modules |
| DC/AC ratio | 1.05 |
| Number of MPPT inputs | 2 |
| Strings per MPPT | 5 |
| Approximate string MPP voltage at 50°C | 718 V |
| Inverter MPPT voltage range | 180–1000 V |

## Array Layout

The PV array consists of five rooftop sheds installed on the main building roof. The baseline configuration uses landscape-oriented modules, a north-south pitch of 2.5 m, a tilt angle of 9.5°, and an azimuth of 0°.

| Parameter | Baseline Value |
|---|---|
| Module orientation | Landscape |
| Modules per shed layout | 19 × 2 |
| Number of sheds | 5 |
| Tilt angle | 9.5° |
| Inter-row pitch | 2.5 m |
| Azimuth | 0° |
| Near-shading model | Linear shading / Fast table |

## 3D Shading Environment

A 3D near-shading scene was created to represent the rooftop installation environment.

| Element | Details |
|---|---|
| Main building roof | 50 m × 30 m × 8 m |
| Adjacent building | 15 m × 15 m × 12 m |
| Adjacent building position | 5 m east of the main building |
| Rooftop obstruction | Cylindrical vent, 1.5 m radius and 2 m height |
| PV array | Five rooftop sheds |

## Simulations Performed

- Baseline simulation using the linear near-shading model
- Electrical shading simulation using the “According to Strings” model
- Comparison of geometric shading and electrical mismatch losses
- Inter-row pitch variation from 2.5 m to 3.2 m
- Tilt-angle variation from 9.5° to 18.0°
- Analysis of energy yield, performance ratio, shading loss, mismatch loss, and the PVsyst Loss Tree
- Assessment of thermal, ohmic, soiling, mismatch, and inverter-related losses

## Key Engineering Considerations

- The DC/AC ratio of 1.05 provides a balanced match between the 105 kWp DC array and 100 kWac inverter.
- The string MPP voltage of approximately 718 V at high operating temperature remains within the inverter MPPT range.
- Near shading can cause both geometric irradiance losses and additional electrical mismatch losses.
- Increasing inter-row pitch can reduce mutual shading but requires more rooftop area.
- Increasing tilt can improve plane-of-array irradiance during some periods but may increase inter-row shading.
- Loss-tree analysis supports practical maintenance planning, including module cleaning, thermal management, wiring checks, and shading control.

## Files Included

- PVsyst project files, where included
- PVsyst simulation report
- PV array characteristics
- Single-line diagram
- 3D near-shading scene
- Simulation result screenshots
- Loss-tree and shading analysis

## Author

**H. M. N. P. Herath**  
Electrical Installation Design — EC9180  
Electrical Engineering Mini Project

## Disclaimer

This repository is published for academic and portfolio purposes. The project uses generic PV component data and a synthetic meteorological dataset. Results are intended for simulation and learning purposes and should not be treated as a final construction design without detailed site assessment, equipment validation, structural assessment, electrical protection design, and applicable utility approvals.
