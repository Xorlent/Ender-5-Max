## Ender-5 Max Bed Plate Leveling Shims
### Background
The Ender-5 Max build plate is quite thin for its size which results in significant warping.  To give your bed mesh leveling the best chance of success, add shims to move the four corners of the bed roughly level with each other.
### Preparation
1. It is highly recommended you add a thin washer to all of the bed mount screws on the left side of the printer, as the shoulders on the supplied screw heads are not large enough for proper fastening.
2. With the printer powered on: In Orca Slicer, connect to your printer and click the "Device" tab
3. Scroll down; within the right-hand info column you will see a 3D graph of the measured mesh.  If the mesh does not appear or looks like incorrect data, clear the current bed mesh data and perform all printer calibration routines, then move on "Evaluating Your Bed Mesh".
### Evaluating Your Bed Mesh
1. In Orca Slicer, connect to your printer and click the "Device" tab
2. Scroll down; within the right-hand info column you will see a 3D graph of the measured mesh.  Assess which corners of the bed need shims to bring them near level with the highest corner and print the required shims.
3. Unplug machine, remove bed mount screw closest to the center of the machine, then back out the outer screw 2-3 turns.
4. Slide the required shim stack-up under the mount, re-secure the mount.
   - _Do not overtighten screws or the shims will get compressed._
5. Plug in and power on the machine.
6. In the Orca Slicer "Device" tab, clear the current bed mesh data.
7. Perform all printer calibration routines.
8. Once calibration is complete, in the Orca Slicer "Device" tab, evaluate the current bed mesh data to see if you achieved the desired result.
### Shim Printing Instructions
- Print in PETG or similar
- Print with .125mm layer height
  - 4 perimeter walls for .6mm nozzle
  - 5 perimeter walls for .4mm nozzle
### Other Info
Shims have telltales that allow you to quickly check stack-up without removal:
- .5mm: Tab is closest to the center of the printer (light blue)
- .25mm: Tab is centered between the bed mount screws (gray)
- .125mm: Tab is closest to the outer perimeter of the printer (dark blue)
![Shim Render](https://github.com/Xorlent/Ender-5-Max/blob/main/Bed%20Shims/Shims.jpg "Shims")
