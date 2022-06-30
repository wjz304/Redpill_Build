# Redpill_Build

## 介绍  
[Redpill_Build](https://github.com/wjz304/Redpill_Build)



## Note
Options Ranked | 1a | 1b | 2a | 2b | 2c | 3a | 3b  
-|-|-|-|-|-|-|- 
DSM Platform | DS918+ | DS3622xs+ | DS920+ | DS1621+ | DS3617xs | DVA3221 | DS3615xs  
Architecture | apollolake | broadwellnk | geminilake | v1000 | broadwell | denverton | bromolow  
DSM Versions | 7.0.1-7.1.0-42661 | 7.0.1-7.1.0-42661 | 7.0.1-7.1.0-42661 | 7.0.1-7.1.0-42661 | 7.0.1-7.1.0-42661 | 7.0.1-7.1.0-42661 | 7.0.1-7.1.0-42661  
Loader | TCRP 0.8 | TCRP 0.8 | TCRP 0.8 | TCRP 0.8 | TCRP 0.8 | TCRP 0.8 | TCRP 0.8
Drive Slot Mapping  | sataportmap/diskidxmap | sataportmap/diskidxmap | device tree | device tree | sataportmap/diskidxmap | sataportmap/diskidxmap | sataportmap/diskidxmap
QuickSync Transcoding | Yes | No | Yes | No | No | No | No
NVMe Cache Support | Yes | Yes | Yes | Yes | Yes (as of 7.0) | Yes | No
RAIDF1 Support | No | Yes | No | No | Yes | No | Yes
Oldest CPU Supported | Haswell* | any x86-64 | Haswell** | any x86-64 | any x86-64 | Haswell* | any x86-64
Max CPU Threads | 8 | 24 | 8 | 16 | 24 (as of 7.0) | 16 | 16
Key Note | currently best for most users | best for very large installs | see slot mapping topic below | AMD Ryzen, see slot mapping topic | obsolete use DS3622xs+ | AI/Deep Learning nVIDIA GPU | obsolete  
|||||||
* \* FMA3 instruction support required. All Haswell Core processors or later support it.  Very few Pentiums/Celerons do (J-series CPUs are a notable exception).
Piledriver is believed to be the minimum AMD CPU architecture equivalent to Intel Haswell.  
* \*\* Based on history, DS920+ should require Haswell. There is anecdotal evidence gradually emerging that DS920+ will run on x86-64 hardware.