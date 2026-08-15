<div align="center">

# EggWUUUHH

### FTC Team 9384 Hydraulic Hydras · 2023–2024 Robot CAD

[![FTC Team](https://img.shields.io/badge/FTC-Team%209384-00AEEF?style=for-the-badge&labelColor=0369A1)](https://ftc-events.firstinspires.org/team/9384)
<img alt="Season: 2023-2024" src="https://img.shields.io/badge/Season-2023--2024-8B5CF6?style=for-the-badge&labelColor=6D28D9"> <img alt="CAD: STEP" src="https://img.shields.io/badge/CAD-STEP-22C55E?style=for-the-badge&labelColor=15803D"> <img alt="License: CC BY 4.0" src="https://img.shields.io/badge/License-CC%20BY%204.0-F59E0B?style=for-the-badge&labelColor=B45309">

Open mechanical design files, robot photography, engineering documentation, and season resources for FTC Team 9384's 2023–2024 competition robot.

[Robot Overview](#robot-and-game) · [Download CAD](#cad-downloads) · [Design History](docs/DESIGN_HISTORY.md) · [View Documentation](#engineering-documentation) · [GrabCAD Model](https://grabcad.com/library/ftc-9384-2023-2024-robot-1) · [Reuse & Attribution](#license-and-attribution)

</div>

<img src="images/IMG_1351.jpg" alt="FTC Team 9384's 2023–2024 robot EggWUUUHH">

---

## About the robot

**EggWUUUHH** is FTC Team 9384 Hydraulic Hydras' robot from the 2023–2024 season. This repository preserves the complete robot assembly alongside the chassis, intake, lift, outtake, climber, and camera mount designs used during development.

The models were originally published on [GrabCAD by Angelo Demetroulakos](https://grabcad.com/library/ftc-9384-2023-2024-robot-1). They are mirrored here so that every file can be downloaded directly without relying on an external CAD library account.

The robot's original project page is available at [angelojamesny.com/tubba-2023-24](https://angelojamesny.com/tubba-2023-24). Its robot specific technical narrative and media have been independently summarized and preserved in this repository so the engineering record remains useful if that site is retired.

## Robot and game

EggWUUUHH was built to compete in the 2023–2024 FTC game **CENTERSTAGE**. During a match, robots collected hexagonal pixels and scored them on an angled backdrop or in designated field areas. Endgame opportunities included suspending from the stage truss and launching a paper airplane into an off field scoring zone. See the [official CENTERSTAGE game animation](https://www.youtube.com/watch?v=6e-5Uo1dRic&t=30s) for a visual explanation.

The team developed the robot through four major competition iterations. The core architecture combined a custom four plate aluminum chassis, mecanum drivetrain, string driven linear slides, active multi stage intake, two pixel outtake, plane launcher, and—late in the season—a winch powered climber.

| System | Design summary |
| --- | --- |
| Chassis | Four parallel aluminum plates with mechanism specific mounting and clearance features, supported by structural extrusions and a mecanum drivetrain. |
| Linear slides | Stacked drawer slides separated by 3D printed pulley blocks and driven vertically by a motorized string system. |
| Intake | Three active stages moved pixels from the floor into the robot: compliant star wheels, counter rollers, and flexible zip tie sweepers. |
| Outtake | The final pivoting box contacted the backdrop and lowered pixels into place; a pincher retained the first pixel while a second waited above it. |
| Plane launcher | A spring supplied launch energy, with separate servos controlling release and aiming angle. |
| Climber | A fast winch pulled side mounted pivoting hooks; string lowered the hooks and rubber bands passively helped raise them. |

Read the complete, rewritten season narrative in [`docs/DESIGN_HISTORY.md`](docs/DESIGN_HISTORY.md).

## Repository contents

```text
.
├── CAD/                         # Downloadable STEP models
├── images/                      # Robot photos and renderings
│   └── project-history/         # Archived iteration and subsystem media
├── docs/DESIGN_HISTORY.md       # Rewritten season and mechanism history
├── Portfolio&Notebook/          # Engineering portfolio and notebook PDFs
├── ATTRIBUTION.md               # Required credit and reuse guidance
├── CHECKSUMS.sha256             # Integrity hashes for distributed assets
├── LICENSE                      # Creative Commons Attribution 4.0
└── README.md
```

## CAD downloads

All models use the vendor neutral STEP format and can be imported by Fusion 360, Onshape, SOLIDWORKS, Inventor, FreeCAD, and most modern mechanical CAD packages.

| Model | Contents | Direct download |
| --- | --- | --- |
| `Main v18.step` | Complete robot assembly | [Download](CAD/Main%20v18.step?raw=1) |
| `Final Chassis V130.step` | Final chassis assembly | [Download](CAD/Final%20Chassis%20V130.step?raw=1) |
| `Chassis and Climber.step` | Chassis and climbing assembly | [Download](CAD/Chassis%20and%20Climber.step?raw=1) |
| `Intake.step` | Intake subsystem | [Download](CAD/Intake.step?raw=1) |
| `Lift and Outtake.step` | Lift and outtake subsystem | [Download](CAD/Lift%20and%20Outtake.step?raw=1) |
| `Logitech920Mount_v4.step` | Logitech C920 camera mount | [Download](CAD/Logitech920Mount_v4.step?raw=1) |

To open a model:

1. Download the desired `.step` file from the table.
2. In your CAD application, choose **Import** or **Open** and select the STEP file.
3. Confirm the imported document's units and component hierarchy before editing or manufacturing parts.

STEP files contain geometry rather than the original parametric design history. Import behavior and component naming can vary by CAD application.

## Engineering documentation

| Document | Description | Open or download |
| --- | --- | --- |
| Engineering Portfolio | Team and robot overview prepared for judging | [9384 2024 Portfolio FINAL.pdf](Portfolio%26Notebook/9384%202024%20Portfolio%20FINAL.pdf) |
| Engineering Notebook | Detailed 2023–2024 engineering record | [9384 Notebook 2024 FINAL.pdf](Portfolio%26Notebook/9384%20Notebook%202024%20FINAL.pdf) |

## Gallery

<table>
  <tr>
    <td width="50%"><img src="images/IMG_1351.jpg" alt="FTC 9384 EggWUUUHH robot photograph"></td>
    <td width="50%"><img src="images/IMG_1350.png" alt="Rear view of the FTC 9384 EggWUUUHH robot"></td>
  </tr>
  <tr>
    <td width="50%"><img src="images/project-history/img_0376-dJoJBnWvDZf40Dqq.jpg" alt="Early active intake iteration"></td>
    <td width="50%"><img src="images/project-history/img_1331_-1-YX4Pz1PNkNi9RZ4X.jpg" alt="Final side-mounted climbing mechanism"></td>
  </tr>
</table>

The repository contains [20 additional original-resolution development images](images/project-history), all indexed in the [complete design history](docs/DESIGN_HISTORY.md).

## Software

Robot software is maintained separately in [HydraulicLib](https://github.com/Tea505/HydraulicLib). This repository focuses on mechanical design and engineering documentation.

## Verification

SHA-256 hashes for the CAD models, images, and PDFs are recorded in [`CHECKSUMS.sha256`](CHECKSUMS.sha256). After downloading files, compare their hashes with that manifest to confirm that the transfer completed without corruption.

## License and attribution

Unless otherwise noted, original material in this repository is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE). You may copy, redistribute, remix, transform, and build upon the material, including commercially, provided that you give appropriate credit, link to the license, and indicate whether changes were made.

Use this suggested credit when publishing this work or a derivative:

> Based on the FTC 9384 2023–2024 Robot by Angelo Demetroulakos and FTC Team 9384 Hydraulic Hydras, licensed under CC BY 4.0. Source: https://github.com/AloeVeraZ/FTC9384-2024-Robot

See [`ATTRIBUTION.md`](ATTRIBUTION.md) for complete reuse guidance. Team names, logos, third party product names, and third party component geometry remain the property of their respective owners; the license grants rights only to material the repository's contributors are authorized to license.

## Disclaimer

These files are provided as is for educational and design reference purposes. Verify dimensions, materials, clearances, fasteners, and applicable competition rules before manufacturing or operating any mechanism.

---

<div align="center">

Built by **FTC Team 9384 · Hydraulic Hydras**

</div>
