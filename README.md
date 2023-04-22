Device tree for Oppo A71 CPH1717

Configurations
========================================================

The Honor V9 Play (codenamed _"CPH1717"_)
It was announced on September 20?? .

## Device specifications

Basic             | Spec Sheet
-----------------:|:-------------------------
SoC               | MediaTek MT6750, Octa-core(4 x 1.5GHz Cortex A53 + 4 x 1.0GHz Cortex A53
CPU               | MediaTek MT6750
GPU               | Mali-T860
Memory            | 3/4 GB RAM
Android           | 7.0
User Interface    | ???
Storage           | 32 GB
MicroSD           | Up to 128 GB
Battery           | 3000 mAh (non-removable)
Display           | 720 x 1280 pixels, 5.2" (282ppi)
Rear Camera       | 13.0 MP
Front Camera      | 8.0 MP



# Build TWRP
  
        cd (source-dir)
        . build/envsetup.sh
        lunch omni_CPH1717-eng
        mka clean
        mka recoveryimage

