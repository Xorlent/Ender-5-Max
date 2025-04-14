## Ender-5 Max Bed Plate Leveling Shims
### Background
The Ender-5 Max build plate is quite thin for its size which results in significant warping.  To give your bed mesh leveling the best chance of success, add shims to move the four corners of the bed roughly level with each other.
### Evaluating Your Bed Mesh
1. In Orca Slicer, connect to your printer and click the "Device" tab
2. Scroll down and within the right info column you will see a 3D graph of the measured mesh.  Assess which corners of the bed need shims to bring them near level with the highest corner and print the required shims.
   - If the mesh does not appear or looks like incorrect data, clear the current bed mesh data and perform all printer calibration routines, then perform step 2.
4. Unplug machine, remove bed mount screw closest to the center of the machine, then back out the outer screw 2-3 turns.
5. Slide the required shim stack-up under the mount, re-secure the mount.
   - _Do not overtighten screws or the shims will get compressed._
6. Plug in and power on the machine.
7. In the Orca Slicer "Device" tab, clear the current bed mesh data.
8. Perform all printer calibration routines.
9. Once calibration is complete, in the Orca Slicer "Device" tab, evaluate the current bed mesh data to see if you achieved the desired result.
### Shim Printing Instructions
- Print in PETG or similar
- Print with .125mm layer height
  - 4 perimeter walls for .6mm nozzle
  - 5 perimeter walls for .4mm nozzle
### Other Info
Shims have telltales that allow you to quickly check stack-up without removal:
- .5mm: Tab is closest to the center of the printer
- .25mm: Tab is centered between the bed mount screws
- .125mm: Tab is closest to the outer perimeter of the printer
