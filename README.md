# GRX STRING LIGHTS

3D printing project for decorative string light covers with Voronoi pattern, Granada-inspired design.

## Current Files

| File | Description |
|------|-------------|
| `Voronoi-Granada_light_smooth.3mf` | Optimized for light weight + smooth finish (0.20mm) |
| `Voronoi-Granada_light_smooth_0p16.3mf` | Ultra-smooth variant (0.16mm layer height) |
| `Granada-90-preserved-hole.stl` | 90% scaled test model with original hole size |

## Print Settings (v3 - Light & Smooth)

| Parameter | Value |
|-----------|-------|
| Layer height | 0.20mm (or 0.16mm for ultra-smooth) |
| Line width | 0.45mm |
| Wall loops | 2 |
| Top layers | 4 |
| Bottom layers | 3 |
| Infill density | 7% |
| Infill pattern | Gyroid |
| Outer wall speed | 80mm/s |
| Top surface speed | 80mm/s |

**Target weight:** <12g per unit

## Changelog

### v3 - Light & Smooth (2025-12-09)
- Reduced infill from 10% to 7% for lighter weight
- Increased top layers from 3 to 4 for better surface quality
- Reduced outer wall speed from 150 to 80mm/s for smoother finish
- Reduced top surface speed from 200 to 80mm/s for premium top surfaces
- Added 0.16mm ultra-smooth variant for finest layer lines
- Added 90% scaled test model (Granada-90-preserved-hole.stl)

### v2 - Lightweight Optimized (2025-12-09)
- Reduced layer height from 0.28mm to 0.20mm for smoother finish
- Changed infill from 15% grid to 10% gyroid for weight reduction
- Increased top/bottom layers from 2 to 3 for better surface quality
- Reduced outer wall speed from 200 to 150mm/s
- (Archived in git history as `Voronoi-Granada-Light.3mf`)

### v1 - Initial Release
- Added `Voronoi-Granada.3mf` - Initial Voronoi pattern design (archived in git history)
