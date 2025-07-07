# G-code Generation
1. Download and unzip [3D printer_3DP CX300.zip](https://github.com/HKPolyU-UAV/3d_printing/blob/main/3D%20printer_3DP%20CX300.zip) to get the slicing GUI.\
   `3D printer_3DP CX300.zip` > `software` > `Kisslicer1.5-3.10` > `KISSlicer.exe` or `KISSlicer64.exe`

2. Check parameter settings on KISSlicer\
   2a. Set `Settings Level` to `expert`.\
   2b. In `Style`, choose `Style Name`: `0.3`/`0.2`/`0.1` (Higher number: higher layer thickness and coarse but less printing time). Recommend `0.3` for prototype.\
   2c. In `Style`, set `Infill`. Recommend `20%` for prototype.\
   2d. In `Style`, set `Infill Style`. Recommend `Rounded` for prototype.\
   2e. In `Support`, always set `Support Name` to `sample support` if you want to get the auto support generation.\
   2f. In `Support`, choose `Support: Coarse`.\
   2g. In `Support`, set `Raft Type` to `Off`. Recommend using `brim` instead of `raft` for easier removal.\
   2h. In `Support`, set `Support Z-Roof [mm]` to 400. If your model height is less than the `Support Z-Roof [mm]`, KISSlicer will only generate support up to the value of `Support Z-Roof [mm]` in the z-axis.
