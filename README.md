# Hostboot Binaries
This package contains binary images related to hardware initialization.

## Content Description

### POWER8
- centaur_sbec_pad.img.ecc : Centaur SBE image (P8 platforms)
-	cvpd.bin : Centaur VPD
- gpu_gpe1.bin : NVIDIA GPU initialization
-	n1.ref_image.hdr.bin.ecc : Naples (P8+) hardware image
-	naples_sbe.img.ecc : Naples (P8+) SBE image
-	p8.ref_image.hdr.bin.ecc : P8 hardware image
-	venice_sbe.img.ecc : P8 SBE image

### POWER9
-	href.manifest : Build artifacts corresponding to p8.ref_image.hdr.bin.ecc
-	ima_catalog.bin : In Memory Accumulation catalog bina
-	ionv.bin : NVIDIA GPU executable
-	nimbus_sbe.img.ecc : Nimbus (P9) SBE image   [deprecated]
-	p9n.hw.overlays.bin : Nimbus (P9) hardware ring overlay data
-	p9n.hw.rings.bin : Nimbus (P9) hardware ring data
-	p9n.ref_image.bin : Nimbus (P9) hardware image  [deprecated]
-	releaseNotes.txt : Build information for P9 images This file really needs to be renamed to p9_releaseNotes.txt
-	selfRest.bin : Self Restore engine data for P9
