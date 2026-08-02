# EggWUUUHH design history

This document preserves and reorganizes the robot-specific engineering record originally published on [Angelo Demetroulakos' project page](https://angelojamesny.com/tubba-2023-24). It is an original summary rather than a copy of the website. Robot media from that page was archived here on August 1, 2026.

## Challenge and design goals

FTC Team 9384 began work on September 9, 2023 for the CENTERSTAGE season. The game rewarded robots for collecting thin hexagonal pixels and placing them on an angled backdrop or in marked field zones. Endgame tasks added the option to hang from the stage truss and launch a paper airplane into an external scoring area.

These tasks drove several top-level requirements:

- reach multiple backdrop heights without sacrificing a compact starting configuration;
- collect and retain up to two pixels quickly;
- place pixels against an angled scoring surface with predictable control;
- preserve mecanum mobility while packaging several mechanisms inside the chassis;
- launch the paper airplane repeatably; and
- add a fast, reliable suspension mechanism before the championship stage.

The robot passed through four major competition iterations.

## Iteration 1 — kickoff through Qualifier 2

### Linear slides

The backdrop's height and angle led the team to a vertically extending slide system. Standard drawer slides were stacked together with 3D-printed parts serving as both spacers and pulley supports. A motor changed the direction of tension in the slide string to extend or retract the assembly.

### Chassis

The mecanum drive used a custom chassis built from four parallel aluminum plates. Plate profiles incorporated mounting holes and mechanism clearances, while aluminum extrusions tied the structure together.

### Intake

The first active intake used three stages so two pixels could move through the robot quickly. Star wheels initially gripped the game piece, counter-rotating rollers pulled it farther inward, and flexible zip ties swept it into the outtake area.

### Outtake

The initial outtake held the pixels in a box and used 3D-printed flexible belts to eject them. It was fast, but could not release a pixel at the angle needed to score reliably on the backdrop. That limitation drove the next redesign.

### Plane launcher

A spring provided the launch energy. One servo released the spring and another raised the launcher to its firing angle, separating the aiming and trigger functions.

## Iteration 2 — Qualifier 2 through Qualifier 4

The chassis, intake, slides, and plane-launcher concepts were retained. Most development focused on the outtake.

The replacement outtake pivoted downward until it contacted the backdrop, allowing each pixel to slide into place rather than being thrown toward the angled surface. A pinching mechanism retained the first loaded pixel while a second pixel waited above it, making controlled two-pixel cycles possible.

## Iteration 3 — Qualifier 4 through Super Qualifier

The team preserved the proven core mechanisms and added a small servo-driven pincher to the intake. During autonomous operation, this arm could rotate downward and collect pre-stacked pixels. The plane launcher's working mechanism stayed the same while its supporting frame was refined.

## Iteration 4 — Super Qualifier through State Championship

The mature chassis, slides, intake, outtake, and launcher remained in service. The major addition was the climber.

After testing multiple climbing concepts, the team selected a winch-driven design for its speed, stiffness, and holding torque. Hooks on both sides of the robot pivoted toward the rear. String attached near each hook's center pulled the mechanism downward, while rubber bands provided passive assistance to raise its resting height. The winch then supported the robot from the truss.

## Mechanism takeaways

- Keeping successful subsystems unchanged between events reduced risk and concentrated effort on the mechanisms that limited scoring.
- The outtake redesign changed the interaction with the field: supporting the box against the backdrop was more repeatable than ejecting toward it.
- A small intake attachment added autonomous capability without replacing the established pixel path.
- The final climber combined active winch force with passive elastic assistance, reducing the number of powered operations required to deploy the hooks.

## Video reference

- [Official 2023–2024 FTC CENTERSTAGE game animation](https://www.youtube.com/watch?v=6e-5Uo1dRic&t=30s)

The video is linked rather than mirrored because it is third-party material published by FIRST.

## Archived project media

The files below are local copies of the original project images. They are kept under their source filenames to preserve provenance.

<details>
<summary><strong>Open the complete 20-image development gallery</strong></summary>

<table>
  <tr>
    <td width="50%"><img src="../images/project-history/img_0376-dJoJBnWvDZf40Dqq.jpg" alt="Robot development image img 0376"></td>
    <td width="50%"><img src="../images/project-history/img_0380-AzGr8QZoL0FM5Bqb.jpg" alt="Robot development image img 0380"></td>
  </tr>
  <tr>
    <td><img src="../images/project-history/img_0388-A1aKQOZoa3I38gvZ.jpg" alt="Robot development image img 0388"></td>
    <td><img src="../images/project-history/capture-1-mnl36MM0EEFr0RwO.png" alt="Robot CAD capture 1"></td>
  </tr>
  <tr>
    <td><img src="../images/project-history/capture-2-A1aKr1g9P5HR1pPw.png" alt="Plane launcher design capture"></td>
    <td><img src="../images/project-history/img_0526_-1-YZ92XMGG33iKGNro.jpg" alt="Robot development image img 0526"></td>
  </tr>
  <tr>
    <td><img src="../images/project-history/img_0721-AzGrDlV3kBc3ZGrE.jpg" alt="Robot development image img 0721"></td>
    <td><img src="../images/project-history/img_1331_-1-YX4Pz1PNkNi9RZ4X.jpg" alt="Climber mechanism development image"></td>
  </tr>
  <tr>
    <td><img src="../images/project-history/img_1668-YrDNKZR7vViPJz5K.jpg" alt="Robot development image img 1668"></td>
    <td><img src="../images/project-history/img_1670-YD04ReJ9pGCVWQOX.jpg" alt="Robot development image img 1670"></td>
  </tr>
  <tr>
    <td><img src="../images/project-history/img_1738-Y4L4peVobwcnn09v.jpg" alt="Robot development image img 1738"></td>
    <td><img src="../images/project-history/img_1739-m5Kvr1bDy8i2BZjq.jpg" alt="Robot development image img 1739"></td>
  </tr>
  <tr>
    <td><img src="../images/project-history/img_1743-A0xNrDlwPVt2lG6V.jpg" alt="Robot development image img 1743"></td>
    <td><img src="../images/project-history/img_1744-AzGrDl4N1MUZa32b.jpg" alt="Robot development image img 1744"></td>
  </tr>
  <tr>
    <td><img src="../images/project-history/img_1745-dJoJN9WZvVfWpBOp.jpg" alt="Robot development image img 1745"></td>
    <td><img src="../images/project-history/img_1746-dJoJN93OKBuzr8qg.jpg" alt="Robot development image img 1746"></td>
  </tr>
  <tr>
    <td><img src="../images/project-history/img_1747-Yg2l5RMRjoh60x5K.jpg" alt="Robot development image img 1747"></td>
    <td><img src="../images/project-history/img_1748-A85prOLO4EhPn7X0.jpg" alt="Robot development image img 1748"></td>
  </tr>
  <tr>
    <td><img src="../images/project-history/img_1749-mk3D5R1RqgSzbrZy.jpg" alt="Robot development image img 1749"></td>
    <td><img src="../images/project-history/capture-1-YKbJN1oDpai8pnBg.png" alt="Robot CAD capture 2"></td>
  </tr>
</table>

</details>

## Related resources

- [CAD downloads](../README.md#cad-downloads)
- [Engineering portfolio and notebook](../README.md#engineering-documentation)
- [Original GrabCAD publication](https://grabcad.com/library/ftc-9384-2023-2024-robot-1)
- [Original project page](https://angelojamesny.com/tubba-2023-24)
