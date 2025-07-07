# 3D Printing Tutorial
Printer model: [Phineas 3DP CX-300](https://www.phineas3dp.com/%E7%94%A2%E5%93%81%E7%9B%AE%E9%8C%84)\
Build volume: 304x304x415mm^3\
Filament types: PLA, PETG, ABS, PC, PA, TPU, TPE

## G-code Generation
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
---
## 3D Printing (Using Web Control)
[Official guide from Phineas 3DP](https://docs.google.com/presentation/d/1etEfz05OivFhBJf1LgV1eZHr3E9O6gLQuy2fu7P-YVM/edit?slide=id.g13eb052e2cc_1_0#slide=id.g13eb052e2cc_1_0_) (in Traditional Chinese only)

<p align="center">
  ![Demo](videos/3Dprinting_resize.gif)
</p>

---
## Change filament
---
## Buy Filament (PLA & TPU)
[NHH website](https://www.nhh.com.hk/en/3dprinting/Product.html)\
[NHH Facebook page](https://www.facebook.com/profile.php?id=100057169131130&locale=zh_HK)\
Contact `NHH` via Facebook Messenger to get the updated product prices/discounts.
