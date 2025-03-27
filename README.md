# Stealth Fork (Beta)  

<p align="center">
The one where Micron R1 & Salad Fork had a baby...
</p>

![Rendering of a StealthFork](./Images/StealthFork.png)

<p align="center">
  <a aria-label="Stars" href="https://github.com/PrintersForAnts/StealthFork/stargazers">
    <img src="https://img.shields.io/github/stars/PrintersForAnts/StealthFork?style=for-the-badge&logo=github&logoColor=%23FFFF00&labelColor=%2363666a&color=%23FFFF00"></a> &nbsp;
    
  <a aria-label="Forks" href="https://github.com/PrintersForAnts/StealthFork/network/members">
    <img src="https://img.shields.io/github/forks/PrintersForAnts/StealthFork?style=for-the-badge&logo=github&logoColor=%23FFFF00&labelColor=%2363666a&color=%23FFFF00"></a> &nbsp;
    
  <a aria-label="License" href="https://github.com/PrintersForAnts/StealthFork/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/PrintersForAnts/StealthFork?style=for-the-badge&logo=opensourcehardware&logoColor=%23FFFF00&labelColor=%2363666a&color=%23FFFF00"></a> &nbsp;
    
  <a aria-label="Commits" href="https://github.com/PrintersForAnts/StealthFork/commits/main">
    <img src="https://img.shields.io/github/commit-activity/y/PrintersForAnts/StealthFork?style=for-the-badge&logo=github&logoColor=%23FFFF00&labelColor=%2363666a&color=%23FFFF00"></a> &nbsp;
    
  <a aria-label="Discord" href="https://discord.gg/doomcube">
    <img alt="Discord" src="https://img.shields.io/discord/825469421346226226?style=for-the-badge&logo=discord&logoColor=%23FFFF00&label=Discord&labelColor=%2363666a&color=%23FFFF00"></a>
</p>

## About  

Stealth Fork is an experimental design that blends the awesome aesthetic and compact form factor of the [**Micron+ R1**](https://github.com/PrintersForAnts/Micron/tree/main/R1_Beta) with the fixed gantry of the [**Salad Fork**.](https://github.com/PrintersForAnts/Salad_Fork) If you’ve ever wanted a machine that blends the best of both, this is it.  

### Additional Features Ported from Micron:
- Bottom panel as stock
- Dual shear add-ons for A/B motors
- Pinned variants of A/B & X/Y as stock
- Optimised belt path
- Larger feet for more stability
- 3.5-inch / 4.3-inch display mounts as stock
- 2x Keystone mounts in rear skirt
- Stealthy aesthetics

> **Note:** This repository is a work in progress. I'll be updating it as things evolve. The goal is a seamless build experience, without compromising the high standards of either parent design.  

---

## Current Status  

- ✅ **STLs Uploaded** – All required STLs for a 180mm or 160mm build are included.
- 🔜 **CAD Files Coming Soon** – Once files are cleaned up, they'll be added (Skirt CAD files available).
- ⚠️ **Beta Release** – While all parts have been printed successfully, a full assembly is still pending. Expect minor refinements.

---

## Required Parts from Micron R1

Some parts are not included in this repo and need to be pulled directly from the **Micron R1 Repo** to convert your current Salad Fork.

| **Category** | **Micron R1 Repo Link** | **Required Parts** |
|-------------|-----------------|-----------------|
| **Panel Clips & Misc** | [Panels](https://github.com/PrintersForAnts/Micron/tree/main/R1_Beta/STLs/Panels) | All except: Bowden Entry Accent Front Cover, Top Hinge Leaf |
| **X Axis** | [X Axis](https://github.com/PrintersForAnts/Micron/tree/main/R1_Beta/STLs/Gantry/X_Axis) | All |
| **AB Double Shear Mounts** | [AB Drives](https://github.com/PrintersForAnts/Micron/tree/main/R1_Beta/STLs/Gantry/AB_Drives/double_shear_mounts) | All |
| **Front Skirt Display Mounts** | [Skirt Displays](https://github.com/PrintersForAnts/Micron/tree/main/R1_Beta/STLs/Skirts/Displays) | All except: Bezels |

---

## Print Recommendations

**All STLs should be correctly oriented for printing.**

- **Material**: ABS or ASA
- **Infill**: 40% (Grid, Gyroid, Honeycomb, Triangle or Cubic)
- **Supports**: Not required
- **Layer Height**: 0.2mm (Including first layer)
- **Wall Count**: 4
- **Extrusion Width**: Forced 0.4mm
- **Solid Top/Bottom Layers**: 5

---

## BOM

A full BOM will be provided, but for now, the large differences are:

|**Item**|**Qty**|**Link**|**Notes**|
|------|------|------|---|
|Feet|x4|[Ali Express](https://s.click.aliexpress.com/e/_EJ0t67E)|
|Waveshare 4.3 Display|x1|[Ali Express](https://s.click.aliexpress.com/e/_EGOmTWc)|
|M5x20 BHCS|x4|[Ali Express](https://s.click.aliexpress.com/e/_ExQz6rS)|
|M3x8 BCHS|x40~|[Ali Express](https://s.click.aliexpress.com/e/_EyFT87W)|To replace M3x6 BHCS for skirt mounting, and replace M3x10 BHCS on gantry mounting.|
|M3x12 BHCS|x25~|[Ali Express](https://s.click.aliexpress.com/e/_Ew2GXKg)|For mounting bottom panel to skirts.|
|M3x25 BHCS|x3|[Ali Express](https://s.click.aliexpress.com/e/_ExoTSVa)|To mount skirt corners.|
|M3x20 BHCS|x1|[Ali Express](https://s.click.aliexpress.com/e/_Eu5EjP6)|To mount power inlet corner.|

---

## Feedback & Discussion  

If you're building a Stealth Fork, I'd love to hear your thoughts! 

Join the discussion, suggest improvements, or share feedback in the 'stealth_fork' channel on the Doomcube Discord.  

---

## Raising Issues

If you encounter any issues, please report them via the Issues section on the Git repository. 

Be as detailed as possible — include steps to reproduce and any relevant screenshots. 

Your feedback helps improve the Stealth Fork for everyone!

---

## Version History

| Date         | Changes                                                    |
|--------------|------------------------------------------------------------|
| 27-Mar-2025  | Added STLs & CAD to convert Salad Fork rear panel to StealthFork Bowden entry. |
| 19-Mar-2025  | Fixed bottom panel DXFs. *(Thanks TurtleCrawler)*          |
| 18-Mar-2025  | Uploaded bottom panel STLs & DXFs for 180mm & 160mm builds |
| 15-Mar-2025  | Uploaded 160mm skirt STLs<br>Uploaded 160_Skirts_v16.step<br>Uploaded 180_Skirts_v24.step<br>Added missing Rear_Centre_Skirt_Keystone_x1.stl (180mm) |
| 10-Mar-2025  | Initial release of beta STLs                               |

---

## Acknowledgements

- HartK for the awesome Micron  
- Yeri for the equally awesome Salad Fork

---

## Build Showcase

**Coming Soon**