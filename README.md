# Turing-Pi-2-Case
An open source case for Turing Pi 2 using laser cut acrylic and 3D printing.

<p align="center">
  <img height="300" src="./imgs/tp2_final_build.gif">
</p>

## Acrylic Pieces
The DXF files for cutting the acrylic pieces are in the ```/dxf``` folder. The inner cuts are in red so that you can order the cut operations to cut the inner details before cutting the outer perimeter.

### Fixed Paths
There were some issues with some of the DXF files where the outer cut was not a complete path. This issue has been fixed in the ```/dxf/fixed-paths``` folder but I have not performed a test cut with those files.

### Rounded Inner Corners for Ordering
Someone pointed out that some online cutting services will reject designs with interior angles of exactly 90 degrees. I rounded the interior corners of the offending pieces and put the updated DXF files in the ```/dxf/plasticsheetsshop-co-uk``` folder.

## 3D Printed Pieces
The STL files for printing the legs and I/O shield are in the ```/stl``` folder. I printed the parts in PLA with 0.35mm layer height slicing settings and got good results and reasonable print times.

## BOM
* [Brass heat-set inserts](https://www.mcmaster.com/94180A331/)
* [Low-profile hex screws](https://www.mcmaster.com/93070A064/)
* 4x 15mm M3 brass standoffs
* PLA filament
* 3mm thickness clear acrylic sheets
* [12mm Chassis Switch](https://www.amazon.com/NOYITO-Chassis-Extension-Suitable-Computer/dp/B07PPDNPW9)
* (Optional) 120mm x 15mm slim fan
  * 25mm M3 screws
  * M3 nuts