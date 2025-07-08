# G-code Generation
## Download Slicer
- Download and unzip [3D printer_3DP CX300.zip](https://github.com/HKPolyU-UAV/3d_printing/blob/main/3D%20printer_3DP%20CX300.zip) to obtain the slicing GUI.
- Go to `3D printer_3DP CX300` > `software` > `Kisslicer1.5-3.10`, then run either `KISSlicer.exe` or `KISSlicer64.exe`.

## Check parameter settings on KISSlicer
1. Set `Settings Level` to `Expert`.

<p align='center'>
      <img src="../images/setting_expert.png" width=600>
</p>
   
2. Set parameters in `Style`:
   - Choose `Style Name`: `0.3`/`0.2`/`0.1` *(Higher number indicates greater layer thickness, resulting in a coarser print but shorter printing time)*. It's recommended to set it to `0.3` for prototypes.
   - Set `Infill`. A value of `20%` is recommended for prototypes.
   - Set `Infill Style`. It's recommended to use `Rounded` for prototypes.
     
   <p align='center'>
      <img src="../images/style_setting.png" width=600>
   </p>
   
 3. Set parameters in `Support`:
    - Always set `Support Name` to `sample support` if you want to use auto support generation.
    - Choose `Support: Coarse`.
    - Set `Raft Type` to `Off`. It's recommended to use `brim` instead of `raft` for easier removal.
    - Set `Support Z-Roof [mm]` to 400. Note that if your model's height is less than the `Support Z-Roof [mm]`, KISSlicer will only generate support up to this value on the z-axis.
    - Set `Brim Dia. [mm]` to `3` for normal cases. Increase this value if your model is large.
      
   <p align='center'>
      <img src="../images/support_setting.png" width=600>
   </p>
   
4. Set parameters in `Ext Map`:
   - Select the correct filament type under `Extruder 1 Material`. Usually, we use `PLA` or `TPU`.

   <p align='center'>
      <img src="../images/ext_map_setting.png" width=600>
   </p>
   
6. Set parameters in `Printer`:
   
   <p align='center'>
      <img src="../images/printer_setting.png" width=600>
   </p>

7. Load STL file(s) into KISSlicer and do slicing
   <p align='center'>
      <img src="../images/model_paths.png" width=600>
   </p>

8. Model rotation
   <p align='center'>
      <img src="../images/rotation.png" width=300> <img src="../images/rotation_choices.png" width=300>
   </p>

9. Check printing time and adjust location of model
   <p align='center'>
      <img src="../images/printing_time_location.png" width=300>
   </p>
