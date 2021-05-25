Processor Info
==============

This is a project to collect processor model details, find samples
with largest BogoMIPS values and share lscpu reports collected by
Linux users at https://linux-hardware.org.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total processor models: 2678.

About
-----

The structure of the repository is the following:

    {VENDOR}/{MODEL PREFIX}/{MODEL NAME}/{FAMILY}-{MODEL}-{STEPPING}/{PROBE ID}

    ( e.g. Intel/Core/Core i7-3630QM/6-58-9/87A12F3AED )

CPU Models
----------

| MFG       | Model                          | BogoMIPS | Cores | L1d  | L1i  | L2    | L3     | Max MHz | Virt  |
|-----------|--------------------------------|----------|-------|------|------|-------|--------|---------|-------|
| AMD       | Ryzen Threadripper 3990X 64... | 793600   | 128   | 32K  | 32K  | 512K  | 16384K | 6352    | AMD-V |
| Intel     | Xeon Phi 7250                  | 759696   | 272   | 32K  | 32K  | 1024K |        | 1600    |       |
| AMD       | Ryzen Threadripper PRO 3995... | 689920   | 128   | 2M   | 2M   | 32M   | 256M   | 2700    | AMD-V |
| Intel     | Xeon Phi 7210                  | 665600   | 256   | 32K  | 32K  | 1024K |        | 1300    | VT-x  |
| Intel     | Xeon Platinum 8280             | 604912   | 112   | 32K  | 32K  | 1024K | 39424K | 4000    | VT-x  |
| AMD       | EPYC 7742 64-Core              | 576000   | 128   | 32K  | 32K  | 512K  | 16384K | 2250    | AMD-V |
| AMD       | EPYC 7702 64-Core              | 510080   | 128   | 32K  | 32K  | 512K  | 16384K | 2000    | AMD-V |
| AMD       | Ryzen Threadripper 3970X 32... | 499200   | 64    | 32K  | 32K  | 512K  | 16384K | 6605    | AMD-V |
| AMD       | Ryzen Threadripper PRO 3975... | 447168   | 64    | 1M   | 1M   | 16M   | 128M   | 3500    | AMD-V |
| AMD       | EPYC 7642 48-Core              | 440736   | 96    | 32K  | 32K  | 512K  | 16384K | 2300    | AMD-V |
| AMD       | Ryzen Threadripper 2990WX 3... | 435072   | 64    | 32K  | 64K  | 512K  | 8192K  | 3000    | AMD-V |
| AMD       | EPYC 7552 48-Core              | 422400   | 96    | 32K  | 32K  | 512K  | 16384K | 2200    | AMD-V |
| AMD       | Ryzen Threadripper 3960X 24... | 405744   | 48    | 32K  | 32K  | 512K  | 16384K | 7333    | AMD-V |
| AMD       | Ryzen Threadripper 2970WX 2... | 355152   | 48    | 32K  | 64K  | 512K  | 8192K  | 3700    | AMD-V |
| AMD       | EPYC 7502P 32-Core             | 319360   | 64    | 1M   | 1M   | 16M   | 128M   | 2500    | AMD-V |
| AMD       | Ryzen 9 5950X 16-Core          | 291200   | 32    | 512K | 512K | 8M    | 64M    | 7866    | AMD-V |
| AMD       | Ryzen 9 3950X 16-Core          | 287456   | 32    | 32K  | 32K  | 512K  | 16384K | 6767    | AMD-V |
| AMD       | EPYC 7601 32-Core              | 281024   | 64    | 32K  | 64K  | 512K  | 8192K  |         | AMD-V |
| Intel     | Xeon Platinum 8180             | 280336   | 56    | 32K  | 32K  | 1024K | 39424K | 3800    | VT-x  |
| Intel     | Xeon Platinum 8171M            | 270400   | 52    | 32K  | 32K  | 1024K | 36608K | 3800    | VT-x  |
| AMD       | EPYC 7402P 24-Core             | 268752   | 48    | 32K  | 32K  | 512K  | 16384K | 2800    | AMD-V |
| AMD       | Ryzen Threadripper 2950X 16... | 268736   | 32    | 32K  | 64K  | 512K  | 8192K  | 4150    | AMD-V |
| AMD       | Ryzen Threadripper 1950X 16... | 262368   | 32    | 32K  | 64K  | 512K  | 8192K  | 4000    | AMD-V |
| AMD       | EPYC 7501 32-Core              | 255488   | 64    | 32K  | 64K  | 512K  | 8192K  | 2000    | AMD-V |
| Intel     | Xeon Gold 6242R                | 248000   | 40    | 32K  | 32K  | 1024K | 36608K |         | VT-x  |
| Intel     | Xeon Platinum 8173M            | 224000   | 56    | 896K | 896K | 28M   | 38.5M  | 3500    | VT-x  |
| Intel     | Xeon Gold 6254                 | 223200   | 36    | 32K  | 32K  | 1024K | 25344K | 4000    | VT-x  |
| Intel     | Core i9-9980XE                 | 216000   | 36    | 32K  | 32K  | 1024K | 25344K | 4500    | VT-x  |
| Intel     | Core i9-10980XE                | 216000   | 36    | 576K | 576K | 18M   | 24.8M  | 4800    | VT-x  |
| AMD       | Ryzen 9 3900X 12-Core          | 206424   | 24    | 32K  | 32K  | 512K  | 16384K | 6398    | AMD-V |
| Intel     | 06_55                          | 201656   | 56    | 32K  | 32K  | 1024K | 39424K | 3200    | VT-x  |
| AMD       | Ryzen 9 5900X 12-Core          | 201600   | 24    | 32K  | 32K  | 512K  | 32768K | 7313    | AMD-V |
| Intel     | Xeon Platinum 8160M            | 201600   | 48    | 32K  | 32K  | 1024K | 33792K | 3700    | VT-x  |
| Intel     | Xeon Gold 6252                 | 201600   | 48    | 32K  | 32K  | 1024K | 36608K |         | VT-x  |
| AMD       | Ryzen Threadripper 1920X 12... | 201576   | 24    | 32K  | 64K  | 512K  | 8192K  | 4200    | AMD-V |
| Intel     | Xeon Gold 6248                 | 200000   | 40    | 32K  | 32K  | 1024K | 28160K | 3900    | VT-x  |
| AMD       | Ryzen 9 3900XT 12-Core         | 199200   | 24    | 32K  | 32K  | 512K  | 16384K | 6215    | AMD-V |
| Intel     | Xeon E5-2696 v4                | 193644   | 44    | 704K | 704K | 5.5M  | 55M    | 3700    | VT-x  |
| Intel     | Xeon E5-2699 v4                | 193600   | 44    | 1.4M | 1.4M | 11M   | 110M   | 3600    | VT-x  |
| Intel     | Xeon Gold 6148                 | 192040   | 40    | 32K  | 32K  | 1024K | 28160K | 3700    | VT-x  |
| AMD       | EPYC 7302 16-Core              | 192000   | 32    | 32K  | 32K  | 512K  | 16384K | 3000    | AMD-V |
| AMD       | EPYC 7302P 16-Core             | 192000   | 32    | 32K  | 32K  | 512K  | 16384K | 3000    | AMD-V |
| AMD       | EPYC 7401P 24-Core             | 191952   | 48    | 768K | 1.5M | 12M   | 64M    | 2000    | AMD-V |
| Intel     | Xeon Gold 6240                 | 187200   | 36    | 2.3M | 2.3M | 72M   | 99M    | 3900    | VT-x  |
| Intel     | Core i9-7980XE                 | 187164   | 36    | 32K  | 32K  | 1024K | 25344K | 4400    | VT-x  |
| Intel     | Core i9-9940X                  | 184800   | 28    | 32K  | 32K  | 1024K | 19712K | 4500    | VT-x  |
| Intel     | Core i9-10940X                 | 184772   | 28    | 448K | 448K | 14M   | 19.3M  | 4800    | VT-x  |
| AMD       | EPYC 7282 16-Core              | 179200   | 32    | 512K | 512K | 8M    | 64M    | 2800    | AMD-V |
| Intel     | Core i9-7960X                  | 179200   | 32    | 32K  | 32K  | 1024K | 22528K | 4400    | VT-x  |
| Intel     | Core i9-7940X                  | 173600   | 28    | 32K  | 32K  | 1024K | 19712K | 4500    | VT-x  |
| Intel     | Xeon Gold 5218R                | 168040   | 40    | 32K  | 32K  | 1024K | 28160K |         | VT-x  |
| Intel     | Xeon Gold 6230                 | 168000   | 40    | 1.3M | 1.3M | 40M   | 55M    | 2100    | VT-x  |
| AMD       | Ryzen Threadripper 2920X 12... | 167976   | 24    | 32K  | 64K  | 512K  | 8192K  | 3500    | AMD-V |
| Intel     | Core i9-10920X                 | 167976   | 24    | 32K  | 32K  | 1024K | 19712K | 4800    | VT-x  |
| Intel     | Xeon E5-2697A v4               | 166496   | 32    | 32K  | 32K  | 256K  | 40960K | 3600    | VT-x  |
| Intel     | Xeon Gold 6142                 | 166464   | 32    | 32K  | 32K  | 1024K | 22528K | 3700    | VT-x  |
| Intel     | Xeon Gold 6139                 | 165600   | 36    | 32K  | 32K  | 1024K | 25344K | 3700    | VT-x  |
| Intel     | Xeon E5-2696 v3                | 165204   | 36    | 32K  | 32K  | 256K  | 46080K | 3800    | VT-x  |
| Intel     | Xeon E5-2699 v3                | 165204   | 36    | 32K  | 32K  | 256K  | 46080K | 3600    | VT-x  |
| Intel     | Xeon Gold 5220                 | 158436   | 36    | 32K  | 32K  | 1024K | 25344K | 3900    | VT-x  |
| AMD       | Ryzen 9 3900 12-Core           | 158400   | 24    | 32K  | 32K  | 512K  | 16384K | 3300    | AMD-V |
| AMD       | EPYC 7351P 16-Core             | 153280   | 32    | 32K  | 64K  | 512K  | 8192K  | 2400    | AMD-V |
| Intel     | Xeon E5-2695 v4                | 151164   | 36    | 576K | 576K | 4.5M  | 45M    | 3300    | VT-x  |
| Intel     | Core i9-10900K                 | 148040   | 20    | 32K  | 32K  | 256K  | 20480K | 5300    | VT-x  |
| Intel     | Core i9-10900KF                | 148040   | 20    | 320K | 320K | 2.5M  | 20M    | 5400    | VT-x  |
| Intel     | Core i9-10900X                 | 148000   | 20    | 32K  | 32K  | 1024K | 19712K | 4800    | VT-x  |
| Intel     | Xeon W-2255                    | 148000   | 20    | 32K  | 32K  | 1024K | 19712K | 4700    | VT-x  |
| Intel     | Xeon W-1290P                   | 147980   | 20    | 320K | 320K | 2.5M  | 20M    | 5300    | VT-x  |
| Intel     | Xeon E5-2698 v3                | 147232   | 32    | 32K  | 32K  | 256K  | 40960K | 3600    | VT-x  |
| Intel     | Xeon Gold 5218                 | 147232   | 32    | 32K  | 32K  | 1024K | 22528K | 3900    | VT-x  |
| AMD       | Ryzen 7 5800X 8-Core           | 147200   | 16    | 32K  | 32K  | 512K  | 32768K | 6480    | AMD-V |
| Intel     | Xeon Gold 5218                 | 147200   | 32    | 32K  | 32K  | 1024K | 22528K | 2301    | VT-x  |
| Intel     | Xeon E5-2697 v3                | 145628   | 28    | 32K  | 32K  | 256K  | 35840K | 3600    | VT-x  |
| Intel     | Core i9-10850K                 | 144040   | 20    | 32K  | 32K  | 256K  | 20480K | 5200    | VT-x  |
| Intel     | Xeon E5-2687W v4               | 144024   | 24    | 32K  | 32K  | 256K  | 30720K | 3500    | VT-x  |
| Intel     | Core i9-10910                  | 144000   | 20    | 320K | 320K | 2.5M  | 20M    | 5000    | VT-x  |
| Intel     | Xeon Gold 6136                 | 144000   | 24    | 32K  | 32K  | 1024K | 25344K | 3700    | VT-x  |
| AMD       | Ryzen 7 3800X 8-Core           | 140864   | 16    | 32K  | 32K  | 512K  | 16384K | 5381    | AMD-V |
| Intel     | Core i9-9900X                  | 140000   | 20    | 32K  | 32K  | 1024K | 19712K | 4500    | VT-x  |
| Intel     | Xeon W-2175                    | 139972   | 28    | 448K | 448K | 14M   | 19.3M  | 4300    | VT-x  |
| Intel     | Core i9-7920X                  | 139200   | 24    | 32K  | 32K  | 1024K | 16896K | 4700    | VT-x  |
| AMD       | Ryzen 7 3700X 8-Core           | 137648   | 16    | 32K  | 32K  | 512K  | 16384K | 6022    | AMD-V |
| AMD       | Ryzen 7 PRO 4750G with Rade... | 137584   | 16    | 256K | 256K | 4M    | 8M     | 4454    | AMD-V |
| AMD       | Ryzen 7 2700X Eight-Core       | 137328   | 16    | 32K  | 64K  | 512K  | 8192K  | 4300    | AMD-V |
| AMD       | Ryzen 7 PRO 3700 8-Core        | 134448   | 16    | 256K | 256K | 4M    | 32M    | 6094    | AMD-V |
| Intel     | Xeon Gold 6130                 | 134432   | 32    | 32K  | 32K  | 1024K | 22528K | 3700    | VT-x  |
| Intel     | Xeon Silver 4216               | 134432   | 32    | 32K  | 32K  | 1024K | 22528K | 3200    | VT-x  |
| Intel     | Xeon E5-2680 v4                | 134428   | 28    | 32K  | 32K  | 256K  | 35840K | 3300    | VT-x  |
| AMD       | Ryzen 7 3800XT 8-Core          | 134400   | 16    | 256K | 256K | 4M    | 32M    | 5575    | AMD-V |
| Intel     | Core i9-7900X                  | 132000   | 20    | 32K  | 32K  | 1024K | 14080K | 4500    | VT-x  |
| Intel     | Xeon W-2155                    | 132000   | 20    | 32K  | 32K  | 1024K | 14080K | 4500    | VT-x  |
| AMD       | Ryzen 7 2700 Eight-Core        | 131184   | 16    | 32K  | 64K  | 512K  | 8192K  | 4100    | AMD-V |
| AMD       | Ryzen 7 1800X Eight-Core       | 130880   | 16    | 32K  | 64K  | 512K  | 8192K  | 4050    | AMD-V |
| Intel     | Xeon E5-2697 v2                | 130152   | 24    | 32K  | 32K  | 256K  | 30720K | 3500    | VT-x  |
| AMD       | Ryzen Threadripper 1900X 8-... | 129328   | 16    | 32K  | 64K  | 512K  | 8192K  | 4050    | AMD-V |
| Intel     | Xeon E5-2695 v3                | 128548   | 28    | 32K  | 32K  | 256K  | 35840K | 3300    | VT-x  |
| Intel     | Core i9-9900KS                 | 128048   | 16    | 32K  | 32K  | 256K  | 16384K | 5000    | VT-x  |
| Intel     | Xeon W-1290                    | 128000   | 20    | 32K  | 32K  | 256K  | 20480K | 5200    | VT-x  |
| AMD       | Ryzen 7 1700X Eight-Core       | 127984   | 16    | 32K  | 64K  | 512K  | 8192K  | 4000    | AMD-V |
| AMD       | Ryzen 5 1600 Six-Core          | 126144   | 16    | 32K  | 64K  | 512K  | 8192K  | 3950    | AMD-V |
| Intel     | Xeon E5-2680 v3                | 125976   | 24    | 32K  | 32K  | 256K  | 30720K | 3300    | VT-x  |
| AMD       | Ryzen 7 1700 Eight-Core        | 125408   | 16    | 32K  | 64K  | 512K  | 8192K  | 3925    | AMD-V |
| Intel     | Xeon E5-2690 v3                | 124824   | 24    | 32K  | 32K  | 256K  | 30720K | 3500    | VT-x  |
| Intel     | Xeon W-2245                    | 124784   | 16    | 256K | 256K | 8M    | 16.5M  | 4700    | VT-x  |
| Intel     | Xeon E5-2687W v3               | 124000   | 20    | 32K  | 32K  | 256K  | 25600K | 3500    | VT-x  |
| Intel     | Core i7-10700K                 | 121632   | 16    | 32K  | 32K  | 256K  | 16384K | 12000   | VT-x  |
| Intel     | Core i7-9800X                  | 121632   | 16    | 32K  | 32K  | 1024K | 16896K | 4500    | VT-x  |
| Intel     | Core i7-10700KF                | 121584   | 16    | 32K  | 32K  | 256K  | 16384K | 5100    | VT-x  |
| Intel     | Xeon E5-2678 v3                | 120048   | 24    | 32K  | 32K  | 256K  | 30720K | 3300    | VT-x  |
| Intel     | Xeon E5-2690 v2                | 120000   | 20    | 32K  | 32K  | 256K  | 25600K | 3600    | VT-x  |
| Intel     | Core i7-6950X                  | 120000   | 20    | 32K  | 32K  | 256K  | 25600K | 4300    | VT-x  |
| Intel     | Xeon W-2150B                   | 120000   | 20    | 32K  | 32K  | 1024K | 14080K | 4500    | VT-x  |
| Intel     | Xeon W-2145                    | 118400   | 16    | 32K  | 32K  | 1024K | 11264K | 4500    | VT-x  |
| Intel     | Xeon E-2288G                   | 118384   | 16    | 32K  | 32K  | 256K  | 16384K | 5000    | VT-x  |
| Intel     | Core i9-9900K                  | 115232   | 16    | 32K  | 32K  | 256K  | 16384K | 5200    | VT-x  |
| Intel     | Core i9-9900KF                 | 115232   | 16    | 32K  | 32K  | 256K  | 16384K | 5100    | VT-x  |
| Intel     | Core i9-9900K                  | 115232   | 16    | 32K  | 32K  | 256K  | 16384K | 5200    | VT-x  |
| Intel     | Xeon Gold 6244                 | 115232   | 16    | 32K  | 32K  | 1024K | 25344K | 4400    | VT-x  |
| AMD       | Ryzen 7 PRO 4700G with Rade... | 115200   | 16    | 256K | 256K | 4M    | 8M     | 3600    | AMD-V |
| Intel     | Core i9-9900KF                 | 115200   | 16    | 32K  | 32K  | 256K  | 16384K | 5000    | VT-x  |
| Intel     | Core i7-11700K                 | 115200   | 16    | 48K  | 32K  | 512K  | 16384K | 5000    | VT-x  |
| Intel     | Core i7-11700KF                | 115200   | 16    | 384K | 256K | 4M    | 16M    | 5000    | VT-x  |
| Intel     | Xeon E5-2695 v2                | 115200   | 24    | 32K  | 32K  | 256K  | 30720K | 3200    | VT-x  |
| Intel     | Core i7-7820X                  | 115200   | 16    | 32K  | 32K  | 1024K | 11264K | 4500    | VT-x  |
| Intel     | Xeon E5-2676 v3                | 115176   | 24    | 384K | 384K | 3M    | 30M    | 3000    | VT-x  |
| AMD       | Ryzen 7 4700G with Radeon G... | 115024   | 16    | 32K  | 32K  | 512K  | 4096K  | 3600    | AMD-V |
| Intel     | Xeon Platinum 8260             | 114912   | 24    | 32K  | 32K  | 1024K | 36608K | 2400    | VT-x  |
| Intel     | Core i7 X 990                  | 112572   | 12    | 32K  | 32K  | 256K  | 12288K | 3468    | VT-x  |
| Intel     | Core i9-11900K                 | 112128   | 16    | 384K | 256K | 4M    | 16M    | 5300    | VT-x  |
| Intel     | Xeon E5-2680 v2                | 112100   | 20    | 32K  | 32K  | 256K  | 25600K | 3600    | VT-x  |
| Intel     | Core i9-10900                  | 112040   | 20    | 320K | 320K | 2.5M  | 20M    | 5200    | VT-x  |
| Intel     | Xeon W-3223                    | 112032   | 16    | 256K | 256K | 8M    | 16.5M  | 4200    | VT-x  |
| Intel     | Xeon Gold 5117                 | 112028   | 28    | 32K  | 32K  | 1024K | 19712K | 2800    | VT-x  |
| Intel     | Xeon E5-2660 v4                | 112000   | 28    | 32K  | 32K  | 256K  | 35840K | 3200    | VT-x  |
| Intel     | Xeon Gold 6144                 | 112000   | 16    | 256K | 256K | 8M    | 24.8M  | 4200    | VT-x  |
| Intel     | Core i9-10900F                 | 111980   | 20    | 320K | 320K | 2.5M  | 20M    | 5200    | VT-x  |
| Intel     | Xeon E5-2683 v3                | 111748   | 28    | 448K | 448K | 3.5M  | 35M    | 3000    | VT-x  |
| Intel     | Xeon Gold 5118                 | 110424   | 24    | 32K  | 32K  | 1024K | 16896K | 3200    | VT-x  |
| Intel     | Xeon E5-2670 v3                | 110400   | 24    | 32K  | 32K  | 256K  | 30720K | 3100    | VT-x  |
| Intel     | Xeon E5-2687W v2               | 108864   | 16    | 32K  | 32K  | 256K  | 25600K | 3400    | VT-x  |
| AMD       | Ryzen 7 PRO 1700X Eight-Core   | 108784   | 16    | 32K  | 64K  | 512K  | 8192K  | 3400    | AMD-V |
| Intel     | Xeon E-2278G                   | 108784   | 16    | 256K | 256K | 2M    | 16M    | 5000    | VT-x  |
| Intel     | Xeon X5675                     | 108180   | 12    | 32K  | 32K  | 256K  | 12288K | 3192    | VT-x  |
| Intel     | Core i7-6850K                  | 108084   | 12    | 32K  | 32K  | 256K  | 15360K | 4200    | VT-x  |
| AMD       | Ryzen 5 3600 6-Core            | 107784   | 12    | 32K  | 32K  | 512K  | 16384K | 5500    | AMD-V |
| AMD       | Opteron 6386 SE                | 107568   | 16    | 512K | 2M   | 64M   | 48M    | 2800    | AMD-V |
| Intel     | Xeon E5-2667 v2                | 105680   | 16    | 32K  | 32K  | 256K  | 25600K | 4000    | VT-x  |
| Intel     | Xeon Silver 4214               | 105624   | 24    | 32K  | 32K  | 1024K | 16896K | 3200    | VT-x  |
| Intel     | Xeon Gold 6234                 | 105600   | 16    | 256K | 256K | 8M    | 24.8M  | 4000    | VT-x  |
| Intel     | Xeon E5-2650 v4                | 105576   | 24    | 32K  | 32K  | 256K  | 30720K | 2201    | VT-x  |
| AMD       | Ryzen 9 5900HX with Radeon ... | 105440   | 16    | 256K | 256K | 4M    | 16M    | 3300    | AMD-V |
| AMD       | Ryzen 9 4900H with Radeon G... | 105392   | 16    | 256K | 256K | 4M    | 8M     | 3300    | AMD-V |
| AMD       | Ryzen 9 5900HS with Radeon ... | 105392   | 16    | 256K | 256K | 4M    | 16M    | 3300    | AMD-V |
| Intel     | Core i7-5930K                  | 105036   | 12    | 32K  | 32K  | 256K  | 15360K | 4500    | VT-x  |
| Intel     | Xeon E5-2660 v3                | 103980   | 20    | 32K  | 32K  | 256K  | 25600K | 3300    | VT-x  |
| AMD       | Ryzen 5 3600X 6-Core           | 103224   | 12    | 32K  | 32K  | 512K  | 16384K | 5329    | AMD-V |
| AMD       | Ryzen 5 2600 Six-Core          | 102624   | 12    | 32K  | 64K  | 512K  | 8192K  | 4175    | AMD-V |
| AMD       | Ryzen 5 PRO 4650G with Rade... | 102588   | 12    | 32K  | 32K  | 512K  | 4096K  | 4307    | AMD-V |
| Intel     | Core i7-6900K                  | 102448   | 16    | 256K | 256K | 2M    | 20M    | 4000    | VT-x  |
| Intel     | Xeon E5-2667 v3                | 102416   | 16    | 32K  | 32K  | 256K  | 20480K | 3600    | VT-x  |
| Intel     | Xeon Silver 4215R              | 102416   | 16    | 32K  | 32K  | 1024K | 11264K | 4000    | VT-x  |
| Intel     | Xeon Gold 6134                 | 102400   | 16    | 32K  | 32K  | 1024K | 25344K |         | VT-x  |
| Intel     | Xeon W-2140B                   | 102384   | 16    | 32K  | 32K  | 1024K | 11264K | 4200    | VT-x  |
| AMD       | Ryzen 7 5800H with Radeon G... | 102208   | 16    | 256K | 256K | 4M    | 16M    | 3200    | AMD-V |
| AMD       | Ryzen 7 5800HS with Radeon ... | 102208   | 16    | 256K | 256K | 4M    | 16M    | 3200    | AMD-V |
| AMD       | Ryzen 7 PRO 2700 Eight-Core    | 102192   | 16    | 256K | 512K | 4M    | 16M    | 3200    | AMD-V |
| Intel     | Xeon E5-1660 v4                | 102160   | 16    | 32K  | 32K  | 256K  | 20480K | 3800    | VT-x  |
| Intel     | Xeon Silver 4116               | 100968   | 24    | 32K  | 32K  | 1024K | 16896K | 3000    | VT-x  |
| AMD       | Ryzen 5 5600X 6-Core           | 100800   | 12    | 192K | 192K | 3M    | 32M    | 5914    | AMD-V |
| Intel     | Xeon X5660                     | 100800   | 12    | 32K  | 32K  | 256K  | 12288K | 2801    | VT-x  |
| Intel     | Xeon E5-2670 v2                | 99980    | 20    | 32K  | 32K  | 256K  | 25600K | 3300    | VT-x  |
| AMD       | Ryzen 5 2600X Six-Core         | 99408    | 12    | 32K  | 64K  | 512K  | 8192K  | 4150    | AMD-V |
| Intel     | Core i9-9900                   | 99232    | 16    | 32K  | 32K  | 256K  | 16384K | 5000    | VT-x  |
| Intel     | Core i9-10980HK                | 99232    | 16    | 256K | 256K | 2M    | 16M    | 5300    | VT-x  |
| AMD       | EPYC 7252 8-Core               | 99184    | 16    | 256K | 256K | 4M    | 64M    | 3100    | AMD-V |
| AMD       | Ryzen 7 PRO 4750GE with Rad... | 99056    | 16    | 256K | 256K | 4M    | 8M     | 3100    | AMD-V |
| Intel     | Core i7-4930K                  | 98988    | 12    | 32K  | 32K  | 256K  | 12288K | 25500   | VT-x  |
| Intel     | Core i7-5820K                  | 98988    | 12    | 32K  | 32K  | 256K  | 15360K | 4500    | VT-x  |
| Intel     | Xeon E5-2687W 0                | 98976    | 16    | 32K  | 32K  | 256K  | 20480K | 3800    | VT-x  |
| Intel     | Core i5-10600K                 | 98436    | 12    | 32K  | 32K  | 256K  | 12288K | 12000   | VT-x  |
| Intel     | Core i5-10600KF                | 98388    | 12    | 192K | 192K | 1.5M  | 12M    | 4800    | VT-x  |
| Intel     | Core i7-3930K                  | 97092    | 12    | 32K  | 32K  | 256K  | 12288K | 5700    | VT-x  |
| Intel     | Core i7-8086K                  | 96192    | 12    | 32K  | 32K  | 256K  | 12288K | 5100    | VT-x  |
| Intel     | Core i7-5960X                  | 96160    | 16    | 32K  | 32K  | 256K  | 20480K | 4600    | VT-x  |
| Intel     | Xeon E5-2640 v4                | 96100    | 20    | 32K  | 32K  | 256K  | 25600K | 3400    | VT-x  |
| Intel     | Xeon E5-2470 v2                | 96020    | 20    | 32K  | 32K  | 256K  | 25600K | 3200    | VT-x  |
| AMD       | Ryzen 5 1600X Six-Core         | 96000    | 12    | 32K  | 64K  | 512K  | 8192K  | 4000    | AMD-V |
| Intel     | Xeon E5-1680 v2                | 95984    | 16    | 32K  | 32K  | 256K  | 25600K | 3900    | VT-x  |
| AMD       | Ryzen 7 PRO 1700 Eight-Core    | 95856    | 16    | 256K | 512K | 4M    | 16M    | 3000    | AMD-V |
| AMD       | Ryzen 9 4900HS with Radeon ... | 95856    | 16    | 32K  | 32K  | 512K  | 4096K  | 3000    | AMD-V |
| Intel     | Xeon E5-1660 v3                | 95776    | 16    | 32K  | 32K  | 256K  | 20480K | 3500    | VT-x  |
| Intel     | Xeon E7- 4870                  | 95740    | 20    | 32K  | 32K  | 256K  | 30720K | 2395    | VT-x  |
| Intel     | Xeon E5-2690 0                 | 95584    | 16    | 32K  | 32K  | 256K  | 20480K | 3800    | VT-x  |
| Intel     | Core i5-11600K                 | 93924    | 12    | 288K | 192K | 3M    | 12M    | 4900    | VT-x  |
| Intel     | Core i5-11600KF                | 93888    | 12    | 288K | 192K | 3M    | 12M    | 5100    |       |
| Intel     | Core i7-6800K                  | 93000    | 12    | 32K  | 32K  | 256K  | 15360K | 4300    | VT-x  |
| Intel     | Core i7-10700                  | 92832    | 16    | 256K | 256K | 2M    | 16M    | 4800    | VT-x  |
| Intel     | Core i7-10700F                 | 92832    | 16    | 32K  | 32K  | 256K  | 16384K | 4800    | VT-x  |
| AMD       | Ryzen 7 4800H with Radeon G... | 92704    | 16    | 32K  | 32K  | 512K  | 4096K  | 2900    | AMD-V |
| AMD       | Ryzen 7 4800HS with Radeon ... | 92656    | 16    | 256K | 256K | 4M    | 8M     | 2900    | AMD-V |
| Intel     | Xeon E5-2650 v3                | 92000    | 20    | 32K  | 32K  | 256K  | 25600K | 3000    | VT-x  |
| Intel     | Xeon E5-2650 v2                | 91536    | 16    | 32K  | 32K  | 256K  | 20480K | 3400    | VT-x  |
| AMD       | Ryzen 5 3600XT 6-Core          | 91236    | 12    | 32K  | 32K  | 512K  | 16384K | 5195    | AMD-V |
| Intel     | Xeon E-2186G                   | 91188    | 12    | 32K  | 32K  | 256K  | 12288K | 4700    | VT-x  |
| Intel     | Xeon E-2276G                   | 91188    | 12    | 32K  | 32K  | 256K  | 12288K | 4900    | VT-x  |
| Intel     | Xeon E7- 4860                  | 90560    | 20    | 32K  | 32K  | 256K  | 24576K | 2262    | VT-x  |
| Intel     | Core i7-8700K                  | 88824    | 12    | 32K  | 32K  | 256K  | 12288K | 5000    | VT-x  |
| Intel     | Xeon W-2135                    | 88800    | 12    | 32K  | 32K  | 1024K | 8448K  | 4500    | VT-x  |
| AMD       | Ryzen 5 1600 Six-Core          | 88788    | 12    | 32K  | 64K  | 512K  | 8192K  | 3650    | AMD-V |
| AMD       | Ryzen 5 PRO 4400G with Rade... | 88788    | 12    | 32K  | 32K  | 512K  | 4096K  | 3700    | AMD-V |
| Intel     | Xeon E-2176G                   | 88788    | 12    | 32K  | 32K  | 256K  | 12288K | 4700    | VT-x  |
| AMD       | Ryzen 5 4600G with Radeon G... | 88632    | 12    | 32K  | 32K  | 512K  | 4096K  | 3700    | AMD-V |
| Intel     | Xeon E5-2660 v2                | 88080    | 20    | 32K  | 32K  | 256K  | 25600K | 3000    | VT-x  |
| Intel     | Xeon Silver 4114               | 88020    | 20    | 32K  | 32K  | 1024K | 14080K | 3000    | VT-x  |
| Intel     | Xeon Silver 4210               | 88020    | 20    | 32K  | 32K  | 1024K | 14080K | 3200    | VT-x  |
| Intel     | Xeon E5-2630 v4                | 88000    | 20    | 32K  | 32K  | 256K  | 25600K | 3100    | VT-x  |
| Intel     | Xeon E5-4640 v2                | 87780    | 20    | 32K  | 32K  | 256K  | 20480K | 2700    | VT-x  |
| Intel     | Core i7-4960X                  | 86436    | 12    | 32K  | 32K  | 256K  | 15360K | 4300    | VT-x  |
| Intel     | Xeon E-2246G                   | 86424    | 12    | 192K | 192K | 1.5M  | 12M    |         | VT-x  |
| Intel     | Xeon E5-1650 v4                | 86412    | 12    | 32K  | 32K  | 256K  | 15360K | 4000    | VT-x  |
| Intel     | Xeon E5645                     | 86400    | 12    | 32K  | 32K  | 256K  | 12288K | 2527    | VT-x  |
| Intel     | Xeon E5-2680 0                 | 86400    | 16    | 32K  | 32K  | 256K  | 20480K | 3500    | VT-x  |
| Intel     | Xeon E5-2651 v2                | 86400    | 24    | 32K  | 32K  | 256K  | 30720K | 2200    | VT-x  |
| Intel     | Xeon W-2133                    | 86400    | 12    | 32K  | 32K  | 1024K | 8448K  | 3900    | VT-x  |
| AMD       | Ryzen 5 PRO 3600 6-Core        | 86232    | 12    | 192K | 192K | 3M    | 32M    | 3600    | AMD-V |
| Intel     | Xeon E7-L8867                  | 85100    | 20    | 1.3M | 1.3M | 10M   | 120M   |         | VT-x  |
| Intel     | Core i7 X 980                  | 84300    | 12    | 32K  | 32K  | 256K  | 12288K | 3334    | VT-x  |
| Intel     | Xeon E5-1650 v3                | 84144    | 12    | 32K  | 32K  | 256K  | 15360K | 3800    | VT-x  |
| Intel     | Core i7-3970X                  | 84072    | 12    | 32K  | 32K  | 256K  | 15360K | 4000    | VT-x  |
| Intel     | Xeon E5-1650 v2                | 84036    | 12    | 32K  | 32K  | 256K  | 12288K | 4200    | VT-x  |
| Intel     | Core i7-7800X                  | 84024    | 12    | 32K  | 32K  | 1024K | 8448K  | 4800    | VT-x  |
| Intel     | Xeon E-2146G                   | 83988    | 12    | 32K  | 32K  | 256K  | 12288K | 4500    | VT-x  |
| Intel     | Xeon X5670                     | 83940    | 12    | 32K  | 32K  | 256K  | 12288K | 3059    | VT-x  |
| Intel     | Xeon E5-2670 0                 | 83568    | 16    | 32K  | 32K  | 256K  | 20480K | 3300    | VT-x  |
| Intel     | Xeon W3690                     | 83424    | 12    | 32K  | 32K  | 256K  | 12288K | 3591    | VT-x  |
| Intel     | Xeon E5-2689 0                 | 83408    | 16    | 32K  | 32K  | 256K  | 20480K | 3600    | VT-x  |
| Intel     | Xeon X5690                     | 83208    | 12    | 32K  | 32K  | 256K  | 12288K | 3591    | VT-x  |
| Intel     | Xeon E5-2640 v3                | 83200    | 16    | 32K  | 32K  | 256K  | 20480K | 3400    | VT-x  |
| Intel     | Xeon D-1571                    | 83168    | 32    | 32K  | 32K  | 256K  | 24576K | 2100    | VT-x  |
| Intel     | Xeon E5-2689 0                 | 83040    | 16    | 256K | 256K | 2M    | 20M    | 3600    | VT-x  |
| Intel     | Xeon E5-2670 0                 | 83024    | 16    | 512K | 512K | 4M    | 40M    | 3300    | VT-x  |
| Intel     | Xeon E5-2643 v3                | 81624    | 12    | 32K  | 32K  | 256K  | 20480K | 3700    | VT-x  |
| Intel     | Xeon E-2236                    | 81588    | 12    | 32K  | 32K  | 256K  | 12288K | 4800    | VT-x  |
| AMD       | Ryzen 5 PRO 2600 Six-Core      | 81432    | 12    | 32K  | 64K  | 512K  | 8192K  | 3400    | AMD-V |
| Intel     | Core i7 980                    | 81072    | 12    | 32K  | 32K  | 256K  | 12288K | 3334    | VT-x  |
| AMD       | FX-9590 Eight-Core             | 80264    | 8     | 16K  | 64K  | 2048K | 8192K  | 5000    | AMD-V |
| Intel     | Xeon X5680                     | 80196    | 12    | 32K  | 32K  | 256K  | 12288K | 3458    | VT-x  |
| Intel     | Xeon W3680                     | 80172    | 12    | 32K  | 32K  | 256K  | 12288K | 3458    | VT-x  |
| Intel     | Xeon E5-4620 v3                | 80000    | 20    | 640K | 640K | 5M    | 50M    | 2600    | VT-x  |
| AMD       | Opteron 6380                   | 79984    | 16    | 16K  | 64K  | 2048K | 6144K  | 2500    | AMD-V |
| Intel     | Xeon E7- 4850                  | 79900    | 20    | 1.3M | 1.3M | 10M   | 96M    | 2000    | VT-x  |
| Intel     | Core i7-11700                  | 79872    | 16    | 48K  | 32K  | 512K  | 16384K | 4900    | VT-x  |
| Intel     | Core i9-11900F                 | 79872    | 16    | 48K  | 32K  | 512K  | 16384K | 5200    |       |
| Intel     | Xeon E-2136                    | 79488    | 12    | 32K  | 32K  | 256K  | 12288K | 4500    | VT-x  |
| Intel     | Core i7-3960X                  | 79428    | 12    | 32K  | 32K  | 256K  | 15360K | 5700    | VT-x  |
| Intel     | Core i7-3960X                  | 79248    | 12    | 32K  | 32K  | 256K  | 15360K | 25500   | VT-x  |
| Intel     | Core i5-10600                  | 79224    | 12    | 192K | 192K | 1.5M  | 12M    | 4800    | VT-x  |
| Intel     | Xeon W-1250                    | 79188    | 12    | 192K | 192K | 1.5M  | 12M    | 4700    | VT-x  |
| AMD       | Ryzen 5 PRO 4650GE with Rad... | 79080    | 12    | 192K | 192K | 3M    | 8M     | 4247    | AMD-V |
| Intel     | Xeon E5-1660 0                 | 79020    | 12    | 192K | 192K | 1.5M  | 15M    | 3300    | VT-x  |
| Intel     | Core i7 970                    | 76968    | 12    | 32K  | 32K  | 256K  | 12288K | 3201    | VT-x  |
| Intel     | Xeon W3670                     | 76968    | 12    | 32K  | 32K  | 256K  | 12288K | 3325    | VT-x  |
| Intel     | Core i7-3930K                  | 76872    | 12    | 192K | 192K | 1.5M  | 12M    | 3800    | VT-x  |
| Intel     | Xeon E5-1650 0                 | 76848    | 12    | 32K  | 32K  | 256K  | 12288K | 5700    | VT-x  |
| Intel     | Core i7-8700                   | 76824    | 12    | 32K  | 32K  | 256K  | 12288K | 4600    | VT-x  |
| Intel     | Core i7-8700B                  | 76824    | 12    | 32K  | 32K  | 256K  | 12288K | 4600    | VT-x  |
| Intel     | Core i9-9980HK                 | 76816    | 16    | 256K | 256K | 2M    | 16M    | 5000    | VT-x  |
| Intel     | Xeon E-2286M                   | 76816    | 16    | 32K  | 32K  | 256K  | 16384K | 5000    | VT-x  |
| Intel     | Core i9-10885H                 | 76816    | 16    | 32K  | 32K  | 256K  | 16384K | 5300    | VT-x  |
| Intel     | Xeon W-10885M                  | 76816    | 16    | 32K  | 32K  | 256K  | 16384K | 5300    | VT-x  |
| Intel     | Xeon E5-2665 0                 | 76816    | 16    | 32K  | 32K  | 256K  | 20480K | 3100    | VT-x  |
| Intel     | Xeon E5-4640 0                 | 76816    | 16    | 32K  | 32K  | 256K  | 20480K | 3000    | VT-x  |
| AMD       | FX-9370 Eight-Core             | 76800    | 8     | 16K  | 64K  | 2048K | 8192K  | 4400    | AMD-V |
| AMD       | Opteron 6378                   | 76800    | 16    | 16K  | 64K  | 2048K | 6144K  | 2400    | AMD-V |
| Intel     | Xeon X5650                     | 76800    | 12    | 32K  | 32K  | 256K  | 12288K | 2793    | VT-x  |
| Intel     | Xeon E5-2630 v3                | 76800    | 16    | 32K  | 32K  | 256K  | 20480K | 3200    | VT-x  |
| Intel     | Core i9-10900T                 | 76000    | 20    | 320K | 320K | 2.5M  | 20M    | 4600    | VT-x  |
| Intel     | Core i9-10900T                 | 75980    | 20    | 32K  | 32K  | 256K  | 20480K | 4500    | VT-x  |
| AMD       | FX-8350 Eight-Core             | 74776    | 8     | 16K  | 64K  | 2048K | 8192K  | 4600    | AMD-V |
| Intel     | Core i5-10500                  | 74424    | 12    | 32K  | 32K  | 256K  | 12288K | 4500    | VT-x  |
| Intel     | Core i7-4820K                  | 73992    | 8     | 32K  | 32K  | 256K  | 10240K | 25500   | VT-x  |
| Intel     | Core i9-9880H                  | 73728    | 16    | 32K  | 32K  | 256K  | 16384K | 4800    | VT-x  |
| AMD       | Opteron 6376                   | 73616    | 16    | 16K  | 64K  | 2048K | 6144K  | 2300    | AMD-V |
| Intel     | Core i7-10875H                 | 73616    | 16    | 32K  | 32K  | 256K  | 16384K | 5100    | VT-x  |
| Intel     | Core i9-10880H                 | 73584    | 16    | 256K | 256K | 2M    | 16M    | 5100    | VT-x  |
| Intel     | Core i7-3820                   | 72792    | 8     | 32K  | 32K  | 256K  | 10240K | 25500   | VT-x  |
| Intel     | Xeon E5-2690 v4                | 72632    | 14    | 32K  | 32K  | 256K  | 35840K | 2600    | VT-x  |
| AMD       | FX-8370E Eight-Core            | 72584    | 8     | 16K  | 64K  | 2048K | 8192K  | 4300    | AMD-V |
| Intel     | Xeon X7560                     | 72448    | 16    | 32K  | 32K  | 256K  | 24576K | 2266    | VT-x  |
| AMD       | FX-8320E Eight-Core            | 72032    | 8     | 16K  | 64K  | 2048K | 8192K  | 4000    | AMD-V |
| Intel     | Core i7-4790K                  | 72024    | 8     | 32K  | 32K  | 256K  | 8192K  | 4800    | VT-x  |
| AMD       | Ryzen 5 4600H with Radeon G... | 72000    | 12    | 192K | 192K | 3M    | 8M     | 3000    | AMD-V |
| AMD       | Ryzen 5 4600HS with Radeon ... | 71868    | 12    | 192K | 192K | 3M    | 8M     | 3000    | AMD-V |
| Intel     | Xeon E5-2660 0                 | 70704    | 16    | 32K  | 32K  | 256K  | 20480K | 3000    | VT-x  |
| AMD       | FX-8300 Eight-Core             | 70664    | 8     | 16K  | 64K  | 2048K | 8192K  | 4400    | AMD-V |
| Intel     | Xeon E5-4620 0                 | 70448    | 16    | 32K  | 32K  | 256K  | 16384K | 2600    | VT-x  |
| Intel     | Xeon D-2141I                   | 70400    | 16    | 32K  | 32K  | 1024K | 11264K | 2201    | VT-x  |
| Intel     | Xeon X5670                     | 70392    | 12    | 32K  | 32K  | 256K  | 12288K |         | VT-x  |
| Intel     | Core i7-10870H                 | 70384    | 16    | 256K | 256K | 2M    | 16M    | 5000    | VT-x  |
| Intel     | Core i7-4770K                  | 70384    | 8     | 32K  | 32K  | 256K  | 8192K  | 4600    | VT-x  |
| Intel     | Core i9-8950HK                 | 69696    | 12    | 32K  | 32K  | 256K  | 12288K | 8300    | VT-x  |
| Intel     | Xeon E-2186M                   | 69696    | 12    | 32K  | 32K  | 256K  | 12288K | 4800    | VT-x  |
| Intel     | Core i5-10400                  | 69624    | 12    | 32K  | 32K  | 256K  | 12288K | 4300    | VT-x  |
| Intel     | Core i5-10400F                 | 69600    | 12    | 32K  | 32K  | 256K  | 12288K | 4300    | VT-x  |
| Intel     | Core i5-10400                  | 69588    | 12    | 32K  | 32K  | 256K  | 12288K | 4300    | VT-x  |
| Intel     | Core i5-10400F                 | 69588    | 12    | 192K | 192K | 1.5M  | 12M    | 4300    | VT-x  |
| Intel     | Xeon E5-2667 0                 | 69552    | 12    | 32K  | 32K  | 256K  | 15360K | 3500    | VT-x  |
| AMD       | FX-8370 Eight-Core             | 69352    | 8     | 16K  | 64K  | 2048K | 8192K  | 4000    | AMD-V |
| AMD       | FX-8320 Eight-Core             | 69032    | 8     | 16K  | 64K  | 2048K | 8192K  | 4300    | AMD-V |
| Intel     | Core i7-7740X                  | 68792    | 8     | 32K  | 32K  | 256K  | 8192K  | 4700    | VT-x  |
| Intel     | Xeon E5-2650L v2               | 68000    | 20    | 640K | 640K | 5M    | 50M    | 2100    | VT-x  |
| AMD       | Ryzen 3 3100 4-Core            | 67472    | 8     | 32K  | 32K  | 512K  | 8192K  | 4137    | AMD-V |
| AMD       | FX-8120 Eight-Core             | 67456    | 8     | 16K  | 64K  | 2048K | 8192K  | 4200    | AMD-V |
| Intel     | Core i7-7700K                  | 67232    | 8     | 32K  | 32K  | 256K  | 8192K  | 5100    | VT-x  |
| Intel     | Xeon E5-2620 v4                | 67216    | 16    | 32K  | 32K  | 256K  | 20480K | 3000    | VT-x  |
| Intel     | Xeon Silver 4110               | 67216    | 16    | 32K  | 32K  | 1024K | 11264K | 3000    | VT-x  |
| AMD       | Opteron 6272                   | 67200    | 16    | 16K  | 64K  | 2048K | 6144K  | 2100    | AMD-V |
| Intel     | Xeon Silver 4208               | 67200    | 16    | 32K  | 32K  | 1024K | 11264K | 3200    | VT-x  |
| AMD       | Ryzen 5 1500X Quad-Core        | 67192    | 8     | 32K  | 64K  | 512K  | 8192K  | 4200    | AMD-V |
| AMD       | Eng Sample, ZS288145TCG54_3... | 67188    | 12    | 16K  | 64K  | 2048K | 6144K  | 2800    | AMD-V |
| Intel     | Xeon E-2276ME                  | 67188    | 12    | 32K  | 32K  | 256K  | 12288K | 2800    | VT-x  |
| Intel     | Xeon E-2276M                   | 67188    | 12    | 32K  | 32K  | 256K  | 12288K | 4700    | VT-x  |
| Intel     | Xeon W-10855M                  | 67188    | 12    | 192K | 192K | 1.5M  | 12M    | 5100    | VT-x  |
| Intel     | Core i9-9900T                  | 67184    | 16    | 32K  | 32K  | 256K  | 16384K | 4400    | VT-x  |
| AMD       | FX-8150 Eight-Core             | 67032    | 8     | 16K  | 64K  | 2048K | 8192K  | 3800    | AMD-V |
| AMD       | Ryzen 5 3400G with Radeon V... | 66400    | 8     | 32K  | 64K  | 512K  | 4096K  | 4150    | AMD-V |
| AMD       | Ryzen 5 PRO 3400G with Rade... | 65600    | 8     | 32K  | 64K  | 512K  | 4096K  | 4100    | AMD-V |
| Intel     | Xeon W-2225                    | 65592    | 8     | 32K  | 32K  | 1024K | 8448K  | 4600    | VT-x  |
| AMD       | Ryzen 5 2400G with Radeon V... | 65472    | 8     | 32K  | 64K  | 512K  | 4096K  | 4100    | AMD-V |
| Intel     | Core i7 870                    | 65128    | 8     | 32K  | 32K  | 256K  | 8192K  | 2934    | VT-x  |
| Intel     | Xeon E-2176M                   | 65088    | 12    | 32K  | 32K  | 256K  | 12288K | 4400    | VT-x  |
| Intel     | Core i5-11500                  | 65088    | 12    | 48K  | 32K  | 512K  | 12288K | 4600    | VT-x  |
| Intel     | Core i7-10850H                 | 64812    | 12    | 192K | 192K | 1.5M  | 12M    | 5100    | VT-x  |
| Intel     | Core i7-9850HE                 | 64788    | 12    | 192K | 192K | 1.5M  | 9M     | 4400    | VT-x  |
| Intel     | Xeon E5-2650 0                 | 64192    | 16    | 32K  | 32K  | 256K  | 20480K | 2800    | VT-x  |
| Intel     | Core i7-6700K                  | 64160    | 8     | 32K  | 32K  | 256K  | 8192K  | 4800    | VT-x  |
| Intel     | Xeon E5-2640 v2                | 64032    | 16    | 32K  | 32K  | 256K  | 20480K | 2500    | VT-x  |
| Intel     | Xeon W-2125                    | 64024    | 8     | 32K  | 32K  | 1024K | 8448K  | 4500    | VT-x  |
| Intel     | Core i7 930                    | 64000    | 8     | 32K  | 32K  | 256K  | 8192K  | 2926    | VT-x  |
| Intel     | Core i7-10700T                 | 63984    | 16    | 256K | 256K | 2M    | 16M    | 4500    | VT-x  |
| Intel     | Core i7-9750H                  | 62460    | 12    | 32K  | 32K  | 256K  | 12288K | 4500    | VT-x  |
| Intel     | Core i7-10750H                 | 62460    | 12    | 32K  | 32K  | 256K  | 12288K | 5000    | VT-x  |
| AMD       | Opteron 6344                   | 62424    | 12    | 96K  | 384K | 12M   | 12M    | 2600    | AMD-V |
| Intel     | Core i7-8850H                  | 62424    | 12    | 32K  | 32K  | 256K  | 9216K  | 4300    | VT-x  |
| Intel     | Core i7-9750H                  | 62424    | 12    | 32K  | 32K  | 256K  | 12288K | 4500    | VT-x  |
| Intel     | Core i7-9750HF                 | 62424    | 12    | 192K | 192K | 1.5M  | 12M    | 4500    | VT-x  |
| Intel     | Core i7-9850H                  | 62424    | 12    | 32K  | 32K  | 256K  | 12288K | 4600    | VT-x  |
| Intel     | Xeon E5-2630 v2                | 62412    | 12    | 32K  | 32K  | 256K  | 15360K | 3100    | VT-x  |
| AMD       | Opteron 6238                   | 62400    | 12    | 16K  | 64K  | 2048K | 6144K  | 2600    | AMD-V |
| Intel     | Xeon Gold 6126                 | 62400    | 12    | 32K  | 32K  | 1024K | 19712K | 2601    | VT-x  |
| Intel     | Xeon X3440                     | 61464    | 8     | 32K  | 32K  | 256K  | 8192K  | 2534    | VT-x  |
| AMD       | Ryzen 3 PRO 4350G with Rade... | 60824    | 8     | 128K | 128K | 2M    | 4M     | 3800    | AMD-V |
| Intel     | Xeon E-2174G                   | 60816    | 8     | 32K  | 32K  | 256K  | 8192K  | 4700    | VT-x  |
| Intel     | Xeon E3-1270 v6                | 60816    | 8     | 128K | 128K | 1M    | 8M     | 4200    | VT-x  |
| AMD       | Ryzen 3 3300X 4-Core           | 60800    | 8     | 128K | 128K | 2M    | 16M    | 3800    | AMD-V |
| Intel     | Xeon E5649                     | 60792    | 12    | 32K  | 32K  | 256K  | 12288K | 2533    | VT-x  |
| Intel     | Xeon E3-1275 v6                | 60672    | 8     | 32K  | 32K  | 256K  | 8192K  | 4200    | VT-x  |
| Intel     | Xeon E5-2640 0                 | 60024    | 12    | 32K  | 32K  | 256K  | 15360K | 3000    | VT-x  |
| Intel     | Core i7-4790                   | 59904    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| Intel     | Xeon E5-2640 0                 | 59856    | 12    | 192K | 192K | 1.5M  | 15M    | 3000    | VT-x  |
| Intel     | Xeon E5-1620 v2                | 59224    | 8     | 32K  | 32K  | 256K  | 10240K | 3900    | VT-x  |
| Intel     | Xeon E3-1245 v6                | 59216    | 8     | 32K  | 32K  | 256K  | 8192K  | 4100    | VT-x  |
| Intel     | Xeon E3-1240 v6                | 59192    | 8     | 32K  | 32K  | 256K  | 8192K  | 4100    | VT-x  |
| Intel     | Xeon E3-1280 v5                | 59192    | 8     | 128K | 128K | 1M    | 8M     | 4000    | VT-x  |
| AMD       | Ryzen 5 1400 Quad-Core         | 59080    | 8     | 32K  | 64K  | 512K  | 4096K  | 3700    | AMD-V |
| Intel     | Xeon E5-1630 v3                | 59064    | 8     | 32K  | 32K  | 256K  | 10240K | 3800    | VT-x  |
| Intel     | Core i7-3770K                  | 59032    | 8     | 32K  | 32K  | 256K  | 8192K  | 6300    | VT-x  |
| Intel     | Xeon E5-2448L 0                | 57760    | 16    | 32K  | 32K  | 256K  | 20480K | 1800    | VT-x  |
| Intel     | Core i7-2700K                  | 57688    | 8     | 32K  | 32K  | 256K  | 8192K  | 6300    | VT-x  |
| Intel     | Xeon E3-1270 V2                | 57688    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| Intel     | Core i7-9700K                  | 57656    | 8     | 32K  | 32K  | 256K  | 12288K | 5200    | VT-x  |
| Intel     | Xeon E3-1271 v3                | 57656    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| Intel     | Xeon E5-2620 v3                | 57648    | 12    | 32K  | 32K  | 256K  | 15360K | 3200    | VT-x  |
| Intel     | Core i7-7700                   | 57632    | 8     | 32K  | 32K  | 256K  | 8192K  | 4200    | VT-x  |
| Intel     | Xeon E5-1620 0                 | 57624    | 8     | 32K  | 32K  | 256K  | 10240K | 4200    | VT-x  |
| Intel     | Xeon E3-1276 v3                | 57624    | 8     | 128K | 128K | 1M    | 8M     | 4000    | VT-x  |
| Intel     | Core i7-9700KF                 | 57616    | 8     | 32K  | 32K  | 256K  | 12288K | 4900    | VT-x  |
| Intel     | Core i7-9700K                  | 57616    | 8     | 32K  | 32K  | 256K  | 12288K | 5100    | VT-x  |
| Intel     | Core i7-9700KF                 | 57616    | 8     | 32K  | 32K  | 256K  | 12288K | 4900    | VT-x  |
| Intel     | Core i3-10100                  | 57616    | 8     | 32K  | 32K  | 256K  | 6144K  | 4300    | VT-x  |
| Intel     | Core i3-10100F                 | 57616    | 8     | 128K | 128K | 1M    | 6M     | 4301    | VT-x  |
| Intel     | Xeon E5-2630L v3               | 57616    | 16    | 32K  | 32K  | 256K  | 20480K | 2900    | VT-x  |
| Intel     | Xeon Silver 4108               | 57616    | 16    | 256K | 256K | 8M    | 11M    | 3000    | VT-x  |
| Intel     | Xeon W-2123                    | 57616    | 8     | 32K  | 32K  | 1024K | 8448K  | 3900    | VT-x  |
| Intel     | Core i7-8700T                  | 57600    | 12    | 32K  | 32K  | 256K  | 12288K | 4000    | VT-x  |
| Intel     | Xeon E-2144G                   | 57600    | 8     | 32K  | 32K  | 256K  | 8192K  | 4500    | VT-x  |
| Intel     | Xeon X5687                     | 57600    | 8     | 32K  | 32K  | 256K  | 12288K | 3592    | VT-x  |
| Intel     | Xeon E5-2440 0                 | 57600    | 12    | 32K  | 32K  | 256K  | 15360K | 2900    | VT-x  |
| Intel     | Xeon E3-1275 v5                | 57600    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| Intel     | Xeon E5620                     | 57592    | 8     | 32K  | 32K  | 256K  | 12288K | 2527    | VT-x  |
| AMD       | Ryzen 5 PRO 2400G with Rade... | 57512    | 8     | 32K  | 64K  | 512K  | 4096K  | 3600    | AMD-V |
| AMD       | Ryzen 5 2500X Quad-Core        | 57504    | 8     | 128K | 256K | 2M    | 8M     | 3600    | AMD-V |
| AMD       | Ryzen 7 4800U with Radeon G... | 57504    | 16    | 32K  | 32K  | 512K  | 4096K  | 1800    | AMD-V |
| AMD       | Ryzen 7 5700U with Radeon G... | 57488    | 16    | 32K  | 32K  | 512K  | 4096K  | 4369    | AMD-V |
| AMD       | Ryzen 5 3350G with Radeon V... | 57488    | 8     | 32K  | 64K  | 512K  | 4096K  | 3600    | AMD-V |
| AMD       | Ryzen 5 PRO 3350G with Rade... | 57488    | 8     | 128K | 256K | 2M    | 4M     | 3600    | AMD-V |
| Intel     | Xeon E3-1280 V2                | 57464    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| Intel     | Xeon E5-2450L 0                | 57456    | 16    | 32K  | 32K  | 256K  | 20480K | 2300    | VT-x  |
| Intel     | Core i7-2600K                  | 57112    | 8     | 32K  | 32K  | 256K  | 8192K  | 6300    | VT-x  |
| AMD       | FX-6350 Six-Core               | 56700    | 6     | 16K  | 64K  | 2048K | 8192K  | 4500    | AMD-V |
| Intel     | Core i7-2600                   | 56688    | 8     | 32K  | 32K  | 256K  | 8192K  | 6300    | VT-x  |
| AMD       | Opteron 6328                   | 56312    | 8     | 16K  | 64K  | 2048K | 6144K  | 3200    | AMD-V |
| Intel     | Xeon E3-1240 V2                | 56304    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Xeon E5-2637 v2                | 56208    | 8     | 32K  | 32K  | 256K  | 15360K | 3800    | VT-x  |
| Intel     | Core i7-4771                   | 56088    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| Intel     | Xeon E-2134                    | 56064    | 8     | 32K  | 32K  | 256K  | 8192K  | 4500    | VT-x  |
| Intel     | Xeon E3-1230 v6                | 56064    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| Intel     | Core i7-3770                   | 56064    | 8     | 32K  | 32K  | 256K  | 8192K  | 6300    | VT-x  |
| Intel     | Xeon E3-1240 v5                | 56064    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| Intel     | Xeon E3-1245 v5                | 56064    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| Intel     | Core i7-4770                   | 56016    | 8     | 32K  | 32K  | 256K  | 8192K  | 4500    | VT-x  |
| Intel     | Xeon E5-1620 v3                | 56016    | 8     | 32K  | 32K  | 256K  | 10240K | 3600    | VT-x  |
| Intel     | Xeon E3-1241 v3                | 56000    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| Intel     | Xeon E3-1246 v3                | 56000    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| Intel     | Xeon E3-1275 v3                | 56000    | 8     | 128K | 128K | 1M    | 8M     | 3900    | VT-x  |
| Intel     | Xeon E3-1285 v4                | 55992    | 8     | 128K | 128K | 1M    | 6M     | 3800    | VT-x  |
| Intel     | Xeon E5-1620 v4                | 55992    | 8     | 32K  | 32K  | 256K  | 10240K | 3800    | VT-x  |
| AMD       | Ryzen 5 PRO 1500 Quad-Core     | 55888    | 8     | 32K  | 64K  | 512K  | 8192K  | 3500    | AMD-V |
| AMD       | Ryzen 3 4300GE with Radeon ... | 55888    | 8     | 128K | 128K | 2M    | 4M     | 3500    | AMD-V |
| Intel     | Xeon E5-2637 v3                | 55888    | 8     | 32K  | 32K  | 256K  | 15360K | 3700    | VT-x  |
| Intel     | Xeon E3-1275 V2                | 55872    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| Intel     | Xeon E3-1270 v3                | 55872    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| Intel     | Xeon E3-1231 v3                | 55496    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Xeon X5677                     | 55472    | 8     | 32K  | 32K  | 256K  | 12288K | 3459    | VT-x  |
| AMD       | FX-6300 Six-Core               | 55446    | 6     | 16K  | 64K  | 2048K | 8192K  | 4400    | AMD-V |
| Intel     | Xeon E5-2630 0                 | 55320    | 12    | 32K  | 32K  | 256K  | 15360K | 2800    | VT-x  |
| AMD       | Opteron 6176                   | 55212    | 12    | 64K  | 64K  | 512K  | 5118K  | 2300    | AMD-V |
| Intel     | Core i5-10500T                 | 55212    | 12    | 32K  | 32K  | 256K  | 12288K | 3800    | VT-x  |
| Intel     | Xeon E31240                    | 54904    | 8     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| AMD       | FX-8100 Eight-Core             | 54760    | 8     | 16K  | 64K  | 2048K | 8192K  | 3400    | AMD-V |
| AMD       | FX-8310 Eight-Core             | 54648    | 8     | 16K  | 64K  | 2048K | 8192K  | 3400    | AMD-V |
| Intel     | Core i7-6700                   | 54568    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| Intel     | Xeon E3-1230 v5                | 54528    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Xeon E3-1240 v3                | 54424    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Xeon E3-1245 V2                | 54400    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Xeon E3-1245 v3                | 54400    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Xeon L5640                     | 54396    | 12    | 32K  | 32K  | 256K  | 12288K | 2394    | VT-x  |
| Intel     | Xeon E31270                    | 54392    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Xeon D-1537                    | 54384    | 16    | 256K | 256K | 2M    | 12M    | 2300    | VT-x  |
| AMD       | Ryzen 7 PRO 4750U with Rade... | 54320    | 16    | 32K  | 32K  | 512K  | 4096K  | 1700    | AMD-V |
| Intel     | Xeon E31275                    | 54272    | 8     | 128K | 128K | 1M    | 8M     | 3401    | VT-x  |
| Intel     | Core i7 975                    | 53464    | 8     | 32K  | 32K  | 256K  | 8192K  | 3334    | VT-x  |
| Intel     | Xeon W5590                     | 53200    | 8     | 128K | 128K | 1M    | 8M     | 3326    | VT-x  |
| Intel     | Core i7-8750H                  | 53004    | 12    | 32K  | 32K  | 256K  | 9216K  | 4100    | VT-x  |
| Intel     | Xeon E3-1230 V2                | 52872    | 8     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Core i7-11370H                 | 52832    | 8     | 192K | 128K | 5M    | 12M    | 4800    | VT-x  |
| Intel     | Xeon E3-1230 v3                | 52816    | 8     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| AMD       | Opteron 6174                   | 52800    | 12    | 64K  | 64K  | 512K  | 5118K  | 2200    | AMD-V |
| Intel     | Xeon E5-2430 0                 | 52800    | 12    | 32K  | 32K  | 256K  | 15360K | 2700    | VT-x  |
| Intel     | Xeon E5-2643 0                 | 52800    | 8     | 32K  | 32K  | 256K  | 10240K | 3500    | VT-x  |
| Intel     | Xeon E5-2420 v2                | 52800    | 12    | 32K  | 32K  | 256K  | 15360K | 2700    | VT-x  |
| Intel     | Xeon E5-4627 v2                | 52800    | 8     | 32K  | 32K  | 256K  | 16384K | 3600    | VT-x  |
| Intel     | Core i7 940                    | 52792    | 8     | 32K  | 32K  | 256K  | 8192K  | 2933    | VT-x  |
| Intel     | Xeon D-1531                    | 52788    | 12    | 32K  | 32K  | 256K  | 9216K  | 2700    | VT-x  |
| Intel     | Core i7-5775C                  | 52768    | 8     | 32K  | 32K  | 256K  | 6144K  | 3700    | VT-x  |
| AMD       | Ryzen 5 3400GE with Radeon ... | 52696    | 8     | 128K | 256K | 2M    | 4M     | 3300    | AMD-V |
| AMD       | Ryzen 5 PRO 3400GE w_ Radeo... | 52696    | 8     | 32K  | 64K  | 512K  | 4096K  | 3300    | AMD-V |
| Intel     | Core i7-4940MX                 | 52696    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| Intel     | Xeon E31245                    | 52680    | 8     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Core i7-5775R                  | 52672    | 8     | 128K | 128K | 1M    | 6M     | 3800    | VT-x  |
| Intel     | Core i7 960                    | 52344    | 8     | 32K  | 32K  | 256K  | 8192K  | 3325    | VT-x  |
| Intel     | Core i7 950                    | 52064    | 8     | 32K  | 32K  | 256K  | 8192K  | 3068    | VT-x  |
| Intel     | Xeon E5-4627 v4                | 52000    | 10    | 320K | 320K | 2.5M  | 25M    | 3200    | VT-x  |
| Intel     | Core i7 965                    | 51888    | 8     | 32K  | 32K  | 256K  | 8192K  | 3201    | VT-x  |
| Intel     | Xeon L5639                     | 51816    | 12    | 32K  | 32K  | 256K  | 12288K | 2129    | VT-x  |
| Intel     | Xeon E31235                    | 51472    | 8     | 32K  | 32K  | 256K  | 8192K  | 3600    | VT-x  |
| Intel     | Xeon E31230                    | 51264    | 8     | 32K  | 32K  | 256K  | 8192K  | 3600    | VT-x  |
| Intel     | Core i7 920                    | 51256    | 8     | 32K  | 32K  | 256K  | 8192K  | 2793    | VT-x  |
| Intel     | Xeon W3565                     | 51216    | 8     | 32K  | 32K  | 256K  | 8192K  | 3325    | VT-x  |
| Intel     | Xeon W5580                     | 51216    | 8     | 256K | 256K | 2M    | 16M    | 3193    | VT-x  |
| Intel     | Xeon W3570                     | 51200    | 8     | 32K  | 32K  | 256K  | 8192K  | 3193    | VT-x  |
| Intel     | Core i7-4790S                  | 51200    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| Intel     | Core i7 920                    | 51192    | 8     | 32K  | 32K  | 256K  | 8192K  | 2793    | VT-x  |
| Intel     | Xeon X5672                     | 51192    | 8     | 32K  | 32K  | 256K  | 12288K | 3201    | VT-x  |
| AMD       | Ryzen 5 2400GE with Radeon ... | 51120    | 8     | 32K  | 64K  | 512K  | 4096K  | 3200    | AMD-V |
| Intel     | Core i7-4770R                  | 51112    | 8     | 32K  | 32K  | 256K  | 6144K  | 3900    | VT-x  |
| AMD       | Ryzen 5 PRO 2400GE w_ Radeo... | 51104    | 8     | 32K  | 64K  | 512K  | 4096K  | 3200    | AMD-V |
| Intel     | Core i7-3770S                  | 51104    | 8     | 32K  | 32K  | 256K  | 8192K  | 4200    | VT-x  |
| Intel     | Core i7-3940XM                 | 51080    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| Intel     | Xeon E5-2620 v2                | 50592    | 12    | 32K  | 32K  | 256K  | 15360K | 2600    | VT-x  |
| AMD       | Opteron 6172                   | 50400    | 12    | 64K  | 64K  | 512K  | 5118K  | 2100    | AMD-V |
| AMD       | Ryzen 5 3500X 6-Core           | 50400    | 6     | 32K  | 32K  | 512K  | 16384K | 4616    | AMD-V |
| Intel     | Xeon E5-2620 0                 | 50388    | 12    | 32K  | 32K  | 256K  | 15360K | 2500    | VT-x  |
| AMD       | Ryzen 5 4600U with Radeon G... | 50328    | 12    | 192K | 192K | 3M    | 8M     | 2100    | AMD-V |
| AMD       | Ryzen 5 PRO 4650U with Rade... | 50328    | 12    | 32K  | 32K  | 512K  | 4096K  | 2100    | AMD-V |
| AMD       | Ryzen 5 5500U with Radeon G... | 50304    | 12    | 192K | 192K | 3M    | 8M     | 4056    | AMD-V |
| Intel     | Core i7-8705G                  | 49616    | 8     | 32K  | 32K  | 256K  | 8192K  | 4100    | VT-x  |
| Intel     | Core i7-4770S                  | 49600    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| AMD       | Opteron 4386                   | 49592    | 8     | 128K | 512K | 16M   | 12M    | 3100    | AMD-V |
| Intel     | Core i7-7920HQ                 | 49592    | 8     | 32K  | 32K  | 256K  | 8192K  | 4100    | VT-x  |
| Intel     | Core i7-8809G                  | 49592    | 8     | 32K  | 32K  | 256K  | 8192K  | 8300    | VT-x  |
| Intel     | Xeon E3-1535M v6               | 49592    | 8     | 32K  | 32K  | 256K  | 8192K  | 4200    | VT-x  |
| Intel     | Core i7-3920XM                 | 49480    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| AMD       | FX-6200 Six-Core               | 49410    | 6     | 16K  | 64K  | 2048K | 8192K  | 4100    | AMD-V |
| AMD       | FX-6100 Six-Core               | 49362    | 6     | 16K  | 64K  | 2048K | 8192K  | 3900    | AMD-V |
| Intel     | Xeon W3550                     | 49088    | 8     | 32K  | 32K  | 256K  | 8192K  | 3060    | VT-x  |
| Intel     | Core i7 860                    | 48720    | 8     | 32K  | 32K  | 256K  | 8192K  | 2933    | VT-x  |
| Intel     | Core i7-9700                   | 48016    | 8     | 32K  | 32K  | 256K  | 12288K | 4700    | VT-x  |
| Intel     | Xeon E3-1505M v6               | 48016    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| Intel     | Core i7-9700F                  | 48000    | 8     | 32K  | 32K  | 256K  | 12288K | 4700    | VT-x  |
| Intel     | Core i7-7820EQ                 | 48000    | 8     | 128K | 128K | 1M    | 8M     | 3000    |       |
| Intel     | Core i3-10100T                 | 48000    | 8     | 32K  | 32K  | 256K  | 6144K  | 3800    | VT-x  |
| Intel     | Xeon E3-1575M v5               | 48000    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| AMD       | Opteron 4284                   | 47992    | 8     | 64K  | 256K | 8M    | 8M     | 3000    | AMD-V |
| Intel     | Xeon W3520                     | 47992    | 8     | 32K  | 32K  | 256K  | 8192K  | 2793    | VT-x  |
| Intel     | Xeon E5-2623 v3                | 47992    | 8     | 32K  | 32K  | 256K  | 10240K | 3500    | VT-x  |
| Intel     | Core i7-1185G7                 | 47936    | 8     | 192K | 128K | 5M    | 12M    | 4800    | VT-x  |
| AMD       | Opteron 6220                   | 47880    | 8     | 16K  | 64K  | 2048K | 6144K  | 3000    | AMD-V |
| AMD       | Ryzen 5 3500 6-Core            | 47418    | 6     | 32K  | 32K  | 512K  | 8192K  | 3950    | AMD-V |
| Intel     | Xeon X3470                     | 47144    | 8     | 32K  | 32K  | 256K  | 8192K  | 3066    | VT-x  |
| Intel     | Core i7 K 875                  | 47096    | 8     | 32K  | 32K  | 256K  | 8192K  | 2934    | VT-x  |
| Intel     | Xeon X5570                     | 47040    | 8     | 32K  | 32K  | 256K  | 8192K  | 3059    | VT-x  |
| Intel     | Xeon W3540                     | 46936    | 8     | 32K  | 32K  | 256K  | 8192K  | 3059    | VT-x  |
| Intel     | Xeon X5647                     | 46808    | 8     | 32K  | 32K  | 256K  | 12288K | 2927    | VT-x  |
| Intel     | Core i7-7820HQ                 | 46480    | 8     | 32K  | 32K  | 256K  | 8192K  | 3900    | VT-x  |
| Intel     | Core i7-7700T                  | 46464    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Core i7-7820HK                 | 46464    | 8     | 32K  | 32K  | 256K  | 8192K  | 4300    | VT-x  |
| Intel     | Core i7-6920HQ                 | 46464    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Xeon E3-1535M v5               | 46464    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Xeon E3-1545M v5               | 46392    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Core i7-4910MQ                 | 46296    | 8     | 32K  | 32K  | 256K  | 8192K  | 4100    | VT-x  |
| AMD       | Phenom II X6 1100T             | 46092    | 6     | 64K  | 64K  | 512K  | 6144K  | 3300    | AMD-V |
| Intel     | Xeon E5-2420 0                 | 45612    | 12    | 32K  | 32K  | 256K  | 15360K | 2400    | VT-x  |
| AMD       | Opteron 6168                   | 45588    | 12    | 64K  | 64K  | 512K  | 5118K  | 1900    | AMD-V |
| AMD       | FX-6120 Six-Core               | 45570    | 6     | 16K  | 64K  | 2048K | 8192K  | 3500    | AMD-V |
| Intel     | Core i7-7700HQ                 | 44968    | 8     | 32K  | 32K  | 256K  | 6144K  | 3800    | VT-x  |
| Intel     | Xeon E3-1505M v5               | 44960    | 8     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Core i7-6700T                  | 44944    | 8     | 32K  | 32K  | 256K  | 8192K  | 3600    | VT-x  |
| Intel     | Core i7-2600S                  | 44928    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Core i7-6820EQ                 | 44928    | 8     | 32K  | 32K  | 256K  | 8192K  | 3500    | VT-x  |
| Intel     | Core i7-1165G7                 | 44864    | 8     | 192K | 128K | 5M    | 12M    | 4700    | VT-x  |
| Intel     | Xeon W3530                     | 44800    | 8     | 32K  | 32K  | 256K  | 8192K  | 2926    | VT-x  |
| Intel     | Xeon X5560                     | 44800    | 8     | 32K  | 32K  | 256K  | 8192K  | 2801    | VT-x  |
| Intel     | Xeon E3-1515M v5               | 44792    | 8     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Core i7-4980HQ                 | 44768    | 8     | 32K  | 32K  | 256K  | 6144K  | 4000    | VT-x  |
| Intel     | Core i7-3840QM                 | 44712    | 8     | 32K  | 32K  | 256K  | 8192K  | 3800    | VT-x  |
| Intel     | Core i7-4810MQ                 | 44712    | 8     | 32K  | 32K  | 256K  | 6144K  | 3800    | VT-x  |
| Intel     | Core i7-4900MQ                 | 44696    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| AMD       | Phenom II X6 1090T             | 44688    | 6     | 64K  | 64K  | 512K  | 6144K  | 3600    | AMD-V |
| Intel     | Xeon X3460                     | 44680    | 8     | 32K  | 32K  | 256K  | 8192K  | 2794    | VT-x  |
| Intel     | Core i5-9600K                  | 44442    | 6     | 32K  | 32K  | 256K  | 9216K  | 5000    | VT-x  |
| Intel     | Core i5-9600K                  | 44412    | 6     | 32K  | 32K  | 256K  | 9216K  | 4700    | VT-x  |
| Intel     | Core i5-9600KF                 | 44394    | 6     | 32K  | 32K  | 256K  | 9216K  | 4700    | VT-x  |
| Intel     | Core i5-9600KF                 | 44394    | 6     | 32K  | 32K  | 256K  | 9216K  | 4600    | VT-x  |
| AMD       | FX-6330 Six-Core               | 43506    | 6     | 16K  | 64K  | 2048K | 8192K  | 3600    | AMD-V |
| Intel     | Core i7-6820HK                 | 43408    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| Intel     | Core i7-8559U                  | 43392    | 8     | 32K  | 32K  | 256K  | 8192K  | 4500    | VT-x  |
| Intel     | Core i7-6820HQ                 | 43392    | 8     | 32K  | 32K  | 256K  | 8192K  | 3600    | VT-x  |
| Intel     | Core i5-8600K                  | 43212    | 6     | 32K  | 32K  | 256K  | 9216K  | 4900    | VT-x  |
| Intel     | Core i7-4790T                  | 43192    | 8     | 128K | 128K | 1M    | 8M     | 3900    | VT-x  |
| Intel     | Core i7-3820QM                 | 43136    | 8     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Core i7-4800MQ                 | 43128    | 8     | 32K  | 32K  | 256K  | 6144K  | 3700    | VT-x  |
| Intel     | Core i7-3740QM                 | 43120    | 8     | 32K  | 32K  | 256K  | 6144K  | 4100    | VT-x  |
| Intel     | Core i7-5700HQ                 | 43120    | 8     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| Intel     | Core i7-2960XM                 | 43096    | 8     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Core i7-3820QM                 | 43096    | 8     | 128K | 128K | 1M    | 8M     | 3700    | VT-x  |
| Intel     | Xeon E3-1275L v3               | 43096    | 8     | 128K | 128K | 1M    | 8M     | 3900    | VT-x  |
| Intel     | Xeon X3450                     | 42784    | 8     | 32K  | 32K  | 256K  | 8192K  | 2668    | VT-x  |
| Intel     | Xeon X5550                     | 42664    | 8     | 32K  | 32K  | 256K  | 8192K  | 2668    | VT-x  |
| Intel     | Xeon E5640                     | 42664    | 8     | 32K  | 32K  | 256K  | 12288K | 2668    | VT-x  |
| Intel     | Core i5-11300H                 | 41776    | 8     | 192K | 128K | 5M    | 8M     | 4400    | VT-x  |
| Intel     | Core i5-1145G7                 | 41776    | 8     | 192K | 128K | 5M    | 8M     | 4400    | VT-x  |
| AMD       | Phenom II X6 1075T             | 41760    | 6     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| Intel     | Core i7-6700HQ                 | 41616    | 8     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| Intel     | Core i7-6770HQ                 | 41616    | 8     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| AMD       | Opteron 6140                   | 41600    | 8     | 64K  | 64K  | 512K  | 5118K  |         | AMD-V |
| Intel     | Xeon Silver 4112               | 41600    | 8     | 32K  | 32K  | 1024K | 8448K  | 3000    | VT-x  |
| AMD       | Opteron 4276 HE                | 41592    | 8     | 16K  | 64K  | 2048K | 8192K  | 2600    | AMD-V |
| Intel     | Core i5-10400H                 | 41592    | 8     | 128K | 128K | 1M    | 8M     | 4600    | VT-x  |
| AMD       | Phenom II X6 1055T             | 41586    | 6     | 64K  | 64K  | 512K  | 6144K  | 2800    | AMD-V |
| Intel     | Core i7-4720HQ                 | 41584    | 8     | 32K  | 32K  | 256K  | 6144K  | 3800    | VT-x  |
| Intel     | Core i7-3720QM                 | 41520    | 8     | 32K  | 32K  | 256K  | 6144K  | 3600    | VT-x  |
| Intel     | Core i7-4960HQ                 | 41504    | 8     | 32K  | 32K  | 256K  | 6144K  | 3800    | VT-x  |
| Intel     | Xeon E-2226G                   | 40794    | 6     | 192K | 192K | 1.5M  | 12M    | 4700    | VT-x  |
| Intel     | Xeon E5630                     | 40536    | 8     | 32K  | 32K  | 256K  | 12288K | 2660    | VT-x  |
| Intel     | Xeon E5540                     | 40528    | 8     | 32K  | 32K  | 256K  | 8192K  | 2534    | VT-x  |
| Intel     | Core i7 S 860                  | 40528    | 8     | 32K  | 32K  | 256K  | 8192K  | 2534    | VT-x  |
| Intel     | Xeon C5549                     | 40432    | 8     | 256K | 256K | 2M    | 16M    | 2528    |       |
| Intel     | Core i5-8400H                  | 40008    | 8     | 32K  | 32K  | 256K  | 8192K  | 4200    | VT-x  |
| Intel     | Core i5-9400H                  | 40008    | 8     | 32K  | 32K  | 256K  | 8192K  | 4300    | VT-x  |
| Intel     | Core i5-10300H                 | 40008    | 8     | 128K | 128K | 1M    | 8M     | 4500    | VT-x  |
| Intel     | Core i7-3770T                  | 39992    | 8     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Core i7-4770T                  | 39992    | 8     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Core i7-4710HQ                 | 39976    | 8     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| Intel     | Core i7-2860QM                 | 39920    | 8     | 32K  | 32K  | 256K  | 8192K  | 3600    | VT-x  |
| Intel     | Core i7-2920XM                 | 39920    | 8     | 32K  | 32K  | 256K  | 8192K  | 3500    | VT-x  |
| Intel     | Core i7-4710MQ                 | 39920    | 8     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| Intel     | Xeon E3-1265L v3               | 39920    | 8     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Core i7-4870HQ                 | 39920    | 8     | 32K  | 32K  | 256K  | 6144K  | 3700    | VT-x  |
| Intel     | Xeon E3-1265L V2               | 39912    | 8     | 32K  | 32K  | 256K  | 8192K  | 3500    | VT-x  |
| Intel     | Xeon E-2126G                   | 39744    | 6     | 32K  | 32K  | 256K  | 12288K | 4500    | VT-x  |
| Intel     | Core i5-1135G7                 | 38720    | 8     | 48K  | 32K  | 1280K | 8192K  | 4200    | VT-x  |
| Intel     | Core i5-9300H                  | 38432    | 8     | 32K  | 32K  | 256K  | 8192K  | 4100    | VT-x  |
| Intel     | Core i7-10710U                 | 38412    | 12    | 192K | 192K | 1.5M  | 12M    | 4700    | VT-x  |
| Intel     | Core i5-9300H                  | 38408    | 8     | 32K  | 32K  | 256K  | 8192K  | 4100    | VT-x  |
| Intel     | Core i5-9300HF                 | 38408    | 8     | 128K | 128K | 1M    | 8M     | 4100    | VT-x  |
| Intel     | Core i5-10200H                 | 38408    | 8     | 128K | 128K | 1M    | 8M     | 4100    | VT-x  |
| Intel     | Atom C2758                     | 38408    | 8     | 24K  | 32K  | 1024K |        | 2400    | VT-x  |
| AMD       | Opteron 6136                   | 38400    | 8     | 64K  | 64K  | 512K  | 5118K  | 2400    | AMD-V |
| AMD       | Opteron 3280                   | 38400    | 8     | 16K  | 64K  | 2048K | 8192K  | 2400    | AMD-V |
| Intel     | Core i7-10810U                 | 38400    | 12    | 192K | 192K | 1.5M  | 12M    | 4900    | VT-x  |
| Intel     | Core i3 550                    | 38400    | 4     | 32K  | 32K  | 256K  | 4096K  | 3200    | VT-x  |
| Intel     | Core i7-2760QM                 | 38400    | 8     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| Intel     | Core i7-4700EQ                 | 38400    | 8     | 32K  | 32K  | 256K  | 6144K  | 3400    | VT-x  |
| Intel     | Atom C2750                     | 38400    | 8     | 24K  | 32K  | 1024K |        | 2401    | VT-x  |
| Intel     | Core i7-6700TE                 | 38400    | 8     | 32K  | 32K  | 256K  | 8192K  | 3400    | VT-x  |
| Intel     | Xeon E5530                     | 38392    | 8     | 32K  | 32K  | 256K  | 8192K  | 2400    | VT-x  |
| Intel     | Core i7-10710U                 | 38388    | 12    | 192K | 192K | 1.5M  | 12M    | 4700    | VT-x  |
| Intel     | Core i7-3630QM                 | 38344    | 8     | 32K  | 32K  | 256K  | 6144K  | 3400    | VT-x  |
| Intel     | Core i7-4700MQ                 | 38344    | 8     | 32K  | 32K  | 256K  | 6144K  | 3400    | VT-x  |
| Intel     | Core i7-4700HQ                 | 38336    | 8     | 32K  | 32K  | 256K  | 6144K  | 3400    | VT-x  |
| Intel     | Core i7-3635QM                 | 38328    | 8     | 32K  | 32K  | 256K  | 6144K  | 3400    | VT-x  |
| Intel     | Core i7-4860HQ                 | 38320    | 8     | 128K | 128K | 1M    | 6M     | 3600    | VT-x  |
| Intel     | Xeon E31260L                   | 38312    | 8     | 32K  | 32K  | 256K  | 8192K  | 3300    | VT-x  |
| AMD       | FX-4170 Quad-Core              | 37788    | 4     | 16K  | 64K  | 2048K | 8192K  | 4200    | AMD-V |
| AMD       | Athlon II X4 631 Quad-Core     | 37520    | 4     | 64K  | 64K  | 1024K |        | 4700    | AMD-V |
| Intel     | Core i5-8600                   | 37194    | 6     | 32K  | 32K  | 256K  | 9216K  | 4300    | VT-x  |
| Intel     | Core i5-9600                   | 37194    | 6     | 192K | 192K | 1.5M  | 9M     | 4600    | VT-x  |
| Intel     | Core i5-8300H                  | 36872    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| Intel     | Core i7-1068NG7                | 36864    | 8     | 48K  | 32K  | 512K  | 8192K  | 4100    | VT-x  |
| Intel     | Core i5-8259U                  | 36864    | 8     | 32K  | 32K  | 256K  | 6144K  | 3800    | VT-x  |
| Intel     | Core i7-10510U                 | 36864    | 8     | 32K  | 32K  | 256K  | 8192K  | 4900    | VT-x  |
| Intel     | Core i7-10610U                 | 36864    | 8     | 128K | 128K | 1M    | 8M     | 4900    | VT-x  |
| Intel     | Xeon E3-1265L v4               | 36808    | 8     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| AMD       | Opteron 6134                   | 36800    | 8     | 64K  | 64K  | 512K  | 5118K  | 2300    | AMD-V |
| AMD       | Ryzen 7 3700U with Radeon V... | 36792    | 8     | 32K  | 64K  | 512K  | 4096K  | 2300    | AMD-V |
| Intel     | Core i7-2820QM                 | 36792    | 8     | 32K  | 32K  | 256K  | 8192K  | 3400    | VT-x  |
| Intel     | Core i7-4712MQ                 | 36784    | 8     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| AMD       | Ryzen 7 3750H with Radeon V... | 36744    | 8     | 128K | 256K | 2M    | 4M     | 2300    | AMD-V |
| AMD       | Ryzen 7 PRO 3700U w_ Radeon... | 36744    | 8     | 32K  | 64K  | 512K  | 4096K  | 2300    | AMD-V |
| Intel     | Core i7-3610QM                 | 36744    | 8     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Core i7-4712HQ                 | 36728    | 8     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Core i7-4850HQ                 | 36728    | 8     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| Intel     | Core i7-3615QM                 | 36720    | 8     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Core i7-3610QE                 | 36712    | 8     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| AMD       | Phenom II X6 1065T             | 36642    | 6     | 64K  | 64K  | 512K  | 6144K  | 2900    | AMD-V |
| AMD       | FX-4350 Quad-Core              | 36412    | 4     | 16K  | 64K  | 2048K | 8192K  | 4200    | AMD-V |
| Intel     | Xeon L5520                     | 36352    | 8     | 32K  | 32K  | 256K  | 8192K  | 2266    | VT-x  |
| AMD       | Phenom II X6 1035T             | 36312    | 6     | 64K  | 64K  | 512K  | 6144K  | 2600    | AMD-V |
| Intel     | Xeon E5520                     | 36264    | 8     | 32K  | 32K  | 256K  | 8192K  | 2268    | VT-x  |
| Intel     | Core i7-2670QM                 | 36208    | 8     | 32K  | 32K  | 256K  | 6144K  | 3100    | VT-x  |
| AMD       | Six-Core                       | 36162    | 6     | 384K | 384K | 3M    | 6M     | 3000    | AMD-V |
| Intel     | Core i5-8500                   | 36036    | 6     | 32K  | 32K  | 256K  | 9216K  | 4100    | VT-x  |
| Intel     | Core i5-9500                   | 36012    | 6     | 32K  | 32K  | 256K  | 9216K  | 4400    | VT-x  |
| AMD       | A10-7860K Radeon R7, 12 Com... | 36000    | 4     | 16K  | 96K  | 2048K |        | 4500    | AMD-V |
| Intel     | Core i5-8500B                  | 36000    | 6     | 192K | 192K | 1.5M  | 9M     | 4100    | VT-x  |
| Intel     | Core i5-9500E                  | 36000    | 6     | 32K  | 32K  | 256K  | 9216K  | 3000    | VT-x  |
| AMD       | FX-4300 Quad-Core              | 35532    | 4     | 16K  | 64K  | 2048K | 4096K  | 4500    | AMD-V |
| AMD       | A10-7870K Radeon R7, 12 Com... | 35472    | 4     | 16K  | 96K  | 2048K |        | 4100    | AMD-V |
| AMD       | A10-6800K APU with Radeon H... | 35372    | 4     | 16K  | 64K  | 2048K |        | 4400    | AMD-V |
| Intel     | Core i7-2720QM                 | 35208    | 8     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Xeon X5470                     | 35200    | 4     | 32K  | 32K  | 6144K |        | 3336    | VT-x  |
| Intel     | Core i7-2675QM                 | 35200    | 8     | 32K  | 32K  | 256K  | 6144K  | 3100    | VT-x  |
| Intel     | Xeon D-1518                    | 35200    | 8     | 32K  | 32K  | 256K  | 6144K  | 2200    | VT-x  |
| Intel     | Atom C3758                     | 35200    | 8     | 24K  | 32K  | 2048K |        | 2200    | VT-x  |
| Intel     | Core i5-10310U                 | 35192    | 8     | 32K  | 32K  | 256K  | 6144K  | 4400    | VT-x  |
| Intel     | Core i7-4702MQ                 | 35160    | 8     | 32K  | 32K  | 256K  | 6144K  | 3200    | VT-x  |
| Intel     | Core i7-3632QM                 | 35152    | 8     | 32K  | 32K  | 256K  | 6144K  | 3200    | VT-x  |
| AMD       | Ryzen 7 2700U with Radeon V... | 35144    | 8     | 32K  | 64K  | 512K  | 4096K  | 2200    | AMD-V |
| AMD       | Ryzen 7 PRO 2700U w_ Radeon... | 35144    | 8     | 128K | 256K | 2M    | 4M     | 2200    | AMD-V |
| Intel     | Core i7-4702HQ                 | 35128    | 8     | 32K  | 32K  | 256K  | 6144K  | 3200    | VT-x  |
| Intel     | Core i7-4770HQ                 | 35128    | 8     | 32K  | 32K  | 256K  | 6144K  | 3400    | VT-x  |
| Intel     | Core i7-4785T                  | 35120    | 8     | 32K  | 32K  | 256K  | 8192K  | 3200    | VT-x  |
| AMD       | A8-6600K APU with Radeon HD... | 35108    | 4     | 16K  | 64K  | 2048K |        | 4400    | AMD-V |
| AMD       | A10-7850K Radeon R7, 12 Com... | 34956    | 4     | 16K  | 96K  | 2048K |        | 4300    | AMD-V |
| Intel     | Core i5-9400                   | 34860    | 6     | 32K  | 32K  | 256K  | 9216K  | 4100    | VT-x  |
| Intel     | Core i5-9400F                  | 34860    | 6     | 32K  | 32K  | 256K  | 9216K  | 4100    | VT-x  |
| Intel     | Core i5-9400                   | 34860    | 6     | 32K  | 32K  | 256K  | 9216K  | 4100    | VT-x  |
| Intel     | Core i5-9400F                  | 34812    | 6     | 32K  | 32K  | 256K  | 9216K  | 4100    | VT-x  |
| Intel     | Xeon L5630                     | 34808    | 8     | 32K  | 32K  | 256K  | 12288K | 2134    | VT-x  |
| Intel     | Core i5-9400                   | 34794    | 6     | 192K | 192K | 1.5M  | 9M     | 4100    | VT-x  |
| AMD       | FX-4330 Quad-Core              | 34688    | 4     | 16K  | 64K  | 2048K | 8192K  | 4000    | AMD-V |
| AMD       | A10-5800K APU with Radeon H... | 34584    | 4     | 16K  | 64K  | 2048K |        | 4300    | AMD-V |
| AMD       | A8-5600K APU with Radeon HD... | 34572    | 4     | 16K  | 64K  | 2048K |        | 4300    | AMD-V |
| AMD       | Athlon X4 860K Quad Core       | 34500    | 4     | 16K  | 96K  | 2048K |        | 4400    | AMD-V |
| AMD       | A10-7890K Radeon R7, 12 Com... | 34348    | 4     | 16K  | 96K  | 2048K |        | 4100    | AMD-V |
| AMD       | Athlon X4 760K Quad Core       | 34340    | 4     | 16K  | 64K  | 2048K |        | 4300    | AMD-V |
| AMD       | A10-6790K APU with Radeon H... | 34324    | 4     | 16K  | 64K  | 2048K |        | 4000    | AMD-V |
| Intel     | Core i7 X 940                  | 34048    | 8     | 32K  | 32K  | 256K  | 8192K  | 2134    | VT-x  |
| Intel     | Core i7-8650U                  | 33800    | 8     | 32K  | 32K  | 256K  | 8192K  | 4200    | VT-x  |
| Intel     | Core i7-1160G7                 | 33792    | 8     | 192K | 128K | 5M    | 12M    | 4400    | VT-x  |
| Intel     | Core i5-10210U                 | 33792    | 8     | 32K  | 32K  | 256K  | 6144K  | 4200    | VT-x  |
| Intel     | Core i7-8665U                  | 33792    | 8     | 32K  | 32K  | 256K  | 8192K  | 4800    | VT-x  |
| AMD       | Six-Core Opteron 8439 SE       | 33768    | 6     | 768K | 768K | 6M    | 12M    | 2800    | AMD-V |
| Intel     | Core i5-8400                   | 33708    | 6     | 32K  | 32K  | 256K  | 9216K  | 4000    | VT-x  |
| Intel     | Core i3-7350K                  | 33612    | 4     | 32K  | 32K  | 256K  | 4096K  | 4400    | VT-x  |
| AMD       | Ryzen 5 3500U with Radeon V... | 33608    | 8     | 32K  | 64K  | 512K  | 4096K  | 2100    | AMD-V |
| Intel     | Core i5-10210U                 | 33608    | 8     | 32K  | 32K  | 256K  | 6144K  | 4200    | VT-x  |
| Intel     | Core i5-10210U                 | 33600    | 8     | 32K  | 32K  | 256K  | 6144K  |         | VT-x  |
| AMD       | Ryzen 5 3550H with Radeon V... | 33568    | 8     | 32K  | 64K  | 512K  | 4096K  | 2100    | AMD-V |
| Intel     | Core i7-3612QM                 | 33560    | 8     | 32K  | 32K  | 256K  | 6144K  | 3100    | VT-x  |
| AMD       | Ryzen 5 PRO 3500U w_ Radeon... | 33544    | 8     | 32K  | 64K  | 512K  | 4096K  | 2100    | AMD-V |
| AMD       | Ryzen 5 3450U with Radeon V... | 33536    | 8     | 32K  | 64K  | 512K  | 4096K  | 2100    | AMD-V |
| AMD       | Ryzen 5 Microsoft Surface  ... | 33536    | 8     | 32K  | 64K  | 512K  | 4096K  | 2100    | AMD-V |
| Intel     | Core i7-2710QE                 | 33520    | 8     | 128K | 128K | 1M    | 6M     | 3000    | VT-x  |
| AMD       | FX-4100 Quad-Core              | 33228    | 4     | 16K  | 64K  | 2048K | 8192K  | 3600    | AMD-V |
| Intel     | Core i5 660                    | 33212    | 4     | 32K  | 32K  | 256K  | 4096K  | 3466    | VT-x  |
| AMD       | Phenom II X4 965               | 32908    | 4     | 64K  | 64K  | 512K  | 6144K  | 3600    | AMD-V |
| AMD       | Athlon X4 750K Quad Core       | 32740    | 4     | 16K  | 64K  | 2048K |        | 4100    | AMD-V |
| AMD       | A10-7700K Radeon R7, 10 Com... | 32716    | 4     | 16K  | 96K  | 2048K |        | 4100    | AMD-V |
| AMD       | FX-4130 Quad-Core              | 32680    | 4     | 16K  | 64K  | 2048K | 4096K  | 3800    | AMD-V |
| AMD       | Phenom II X6 1045T             | 32616    | 6     | 64K  | 64K  | 512K  | 6144K  | 2700    | AMD-V |
| AMD       | Ryzen 3 3200G with Radeon V... | 32348    | 4     | 32K  | 64K  | 512K  | 4096K  | 3800    | AMD-V |
| AMD       | FX-4320 Quad-Core              | 32156    | 4     | 16K  | 64K  | 2048K | 4096K  | 4000    | AMD-V |
| AMD       | FX-4150 Quad-Core              | 32144    | 4     | 16K  | 64K  | 2048K | 4096K  | 4000    | AMD-V |
| Intel     | Core i3-7300                   | 32076    | 4     | 32K  | 32K  | 256K  | 4096K  | 4000    | VT-x  |
| Intel     | Core i3-8350K                  | 32064    | 4     | 32K  | 32K  | 256K  | 8192K  | 4400    | VT-x  |
| Intel     | Core i5-7640X                  | 32064    | 4     | 32K  | 32K  | 256K  | 6144K  | 4200    | VT-x  |
| Intel     | Core i3 530                    | 32040    | 4     | 32K  | 32K  | 256K  | 4096K  | 3059    | VT-x  |
| Intel     | Core i7-8550U                  | 32024    | 8     | 32K  | 32K  | 256K  | 8192K  | 4000    | VT-x  |
| Intel     | Core i3 540                    | 32016    | 4     | 32K  | 32K  | 256K  | 4096K  | 3067    | VT-x  |
| AMD       | Athlon 3000G with Radeon Ve... | 32008    | 4     | 64K  | 128K | 1M    | 4M     | 3800    | AMD-V |
| Intel     | Core i7-8565U                  | 32008    | 8     | 32K  | 32K  | 256K  | 8192K  | 4600    | VT-x  |
| Intel     | Core i7-8565U                  | 32008    | 8     | 32K  | 32K  | 256K  | 8192K  | 4600    | VT-x  |
| Intel     | Core i7-9700T                  | 32008    | 8     | 32K  | 32K  | 256K  | 12288K | 4300    | VT-x  |
| Intel     | Xeon E3-1240L v3               | 32008    | 8     | 128K | 128K | 1M    | 8M     | 3000    | VT-x  |
| AMD       | Opteron 6128                   | 32000    | 8     | 64K  | 64K  | 512K  | 5118K  | 2000    | AMD-V |
| Intel     | Core i7-2635QM                 | 32000    | 8     | 32K  | 32K  | 256K  | 6144K  | 2900    | VT-x  |
| AMD       | Ryzen 3 2200G with Radeon V... | 31996    | 4     | 32K  | 64K  | 512K  | 4096K  | 3850    | AMD-V |
| Intel     | Pentium Gold G6400             | 31996    | 4     | 32K  | 32K  | 256K  | 4096K  | 4000    | VT-x  |
| Intel     | Core i7-6822EQ                 | 31992    | 8     | 32K  | 32K  | 256K  | 8192K  | 2000    | VT-x  |
| Intel     | Core i7-4765T                  | 31976    | 8     | 32K  | 32K  | 256K  | 8192K  | 3000    | VT-x  |
| Intel     | Core i7-2630QM                 | 31960    | 8     | 32K  | 32K  | 256K  | 6144K  | 2900    | VT-x  |
| AMD       | Athlon X4 880K Quad Core       | 31956    | 4     | 16K  | 96K  | 2048K |        | 4000    | AMD-V |
| AMD       | Ryzen 5 2500U with Radeon V... | 31952    | 8     | 32K  | 64K  | 512K  | 4096K  | 2000    | AMD-V |
| AMD       | Ryzen 7 4700U with Radeon G... | 31952    | 8     | 256K | 256K | 4M    | 8M     | 2000    | AMD-V |
| AMD       | Ryzen 5 PRO 2500U w_ Radeon... | 31944    | 8     | 32K  | 64K  | 512K  | 4096K  | 2000    | AMD-V |
| Intel     | Core i5-1038NG7                | 31944    | 8     | 192K | 128K | 2M    | 6M     | 3800    | VT-x  |
| AMD       | A10-6790B APU with Radeon H... | 31940    | 4     | 32K  | 128K | 4M    |        | 4000    | AMD-V |
| AMD       | A8-7650K Radeon R7, 10 Comp... | 31936    | 4     | 16K  | 96K  | 2048K |        | 4000    | AMD-V |
| AMD       | Ryzen Embedded V1605B with ... | 31936    | 8     | 32K  | 64K  | 512K  | 4096K  | 2000    | AMD-V |
| Intel     | Core i7-2630QM                 | 31936    | 8     | 128K | 128K | 1M    | 6M     | 2900    | VT-x  |
| Intel     | Core i7-4750HQ                 | 31928    | 8     | 32K  | 32K  | 256K  | 6144K  | 3200    | VT-x  |
| Intel     | Core i7 X 920                  | 31920    | 8     | 32K  | 32K  | 256K  | 8192K  | 2000    | VT-x  |
| AMD       | Phenom II X4 980               | 31820    | 4     | 64K  | 64K  | 512K  | 6144K  | 3700    | AMD-V |
| AMD       | Phenom II X4 955               | 31688    | 4     | 64K  | 64K  | 512K  | 6144K  | 3700    | AMD-V |
| AMD       | Six-Core Opteron 8435          | 31356    | 6     | 64K  | 64K  | 512K  | 6144K  | 2600    | AMD-V |
| Intel     | Core i3-7100                   | 31312    | 4     | 32K  | 32K  | 256K  | 3072K  | 3900    | VT-x  |
| Intel     | Core i3-6320                   | 31308    | 4     | 32K  | 32K  | 256K  | 4096K  | 3900    | VT-x  |
| Intel     | Pentium Gold G5600             | 31296    | 4     | 32K  | 32K  | 256K  | 4096K  | 3900    | VT-x  |
| AMD       | Phenom II X4 960T              | 31200    | 4     | 64K  | 64K  | 512K  | 6144K  | 3600    | AMD-V |
| AMD       | Athlon II X4 640               | 31200    | 4     | 64K  | 64K  | 512K  |        | 3000    | AMD-V |
| AMD       | Six-Core Opteron 2435          | 31200    | 6     | 64K  | 64K  | 512K  | 6144K  | 2600    | AMD-V |
| AMD       | Opteron 4180                   | 31200    | 6     | 64K  | 64K  | 512K  | 6144K  |         | AMD-V |
| AMD       | A8-9600 RADEON R7, 10 COMPU... | 31156    | 4     | 32K  | 96K  | 1024K |        | 3900    | AMD-V |
| AMD       | Athlon X4 870K Quad Core       | 31152    | 4     | 32K  | 192K | 4M    |        | 3900    | AMD-V |
| AMD       | A10-8850 Radeon R7, 12 Comp... | 31144    | 4     | 16K  | 96K  | 2048K |        | 3900    | AMD-V |
| AMD       | A10-9700 RADEON R7, 10 COMP... | 31140    | 4     | 32K  | 96K  | 1024K |        | 3900    | AMD-V |
| AMD       | Athlon X4 950 Quad Core        | 31140    | 4     | 32K  | 96K  | 1024K |        | 3900    | AMD-V |
| Intel     | Core2 Quad Q9550               | 30952    | 4     | 32K  | 32K  | 6144K |        | 2834    | VT-x  |
| Intel     | Core i5 760                    | 30644    | 4     | 32K  | 32K  | 256K  | 8192K  | 2933    | VT-x  |
| Intel     | Core i3-4370                   | 30452    | 4     | 32K  | 32K  | 256K  | 4096K  | 3800    | VT-x  |
| Intel     | Core i5-7600K                  | 30428    | 4     | 32K  | 32K  | 256K  | 6144K  | 5100    | VT-x  |
| Intel     | Core i5-8350U                  | 30408    | 8     | 32K  | 32K  | 256K  | 6144K  | 3600    | VT-x  |
| Intel     | Core i5-8365U                  | 30408    | 8     | 32K  | 32K  | 256K  | 6144K  | 4100    | VT-x  |
| Intel     | Pentium Gold G5420             | 30408    | 4     | 32K  | 32K  | 256K  | 4096K  | 3800    | VT-x  |
| AMD       | Ryzen 3 1200 Quad-Core         | 30396    | 4     | 32K  | 64K  | 512K  | 4096K  | 3500    | AMD-V |
| Intel     | Pentium Gold G5500             | 30396    | 4     | 32K  | 32K  | 256K  | 4096K  | 3800    | VT-x  |
| Intel     | Core i3-6300                   | 30396    | 4     | 32K  | 32K  | 256K  | 4096K  | 3800    | VT-x  |
| AMD       | Phenom II X4 970               | 30372    | 4     | 64K  | 64K  | 512K  | 6144K  | 3500    | AMD-V |
| AMD       | A12-9800 RADEON R7, 12 COMP... | 30356    | 4     | 32K  | 96K  | 1024K |        | 3800    | AMD-V |
| AMD       | Athlon 200GE with Radeon Ve... | 30344    | 4     | 32K  | 64K  | 512K  | 4096K  | 3800    | AMD-V |
| AMD       | A10-5800B APU with Radeon H... | 30340    | 4     | 16K  | 64K  | 2048K |        | 3800    | AMD-V |
| AMD       | Ryzen 3 1300X Quad-Core        | 30340    | 4     | 32K  | 64K  | 512K  | 4096K  | 3800    | AMD-V |
| Intel     | Core2 Quad Q9500               | 30260    | 4     | 32K  | 32K  | 3072K |        | 2834    | VT-x  |
| Intel     | Xeon E5-2430 v2                | 30018    | 6     | 32K  | 32K  | 256K  | 15360K | 3000    | VT-x  |
| Intel     | Core i7 Q 840                  | 29824    | 8     | 32K  | 32K  | 256K  | 8192K  | 1867    | VT-x  |
| Intel     | Xeon L3426                     | 29792    | 8     | 32K  | 32K  | 256K  | 8192K  | 1999    | VT-x  |
| AMD       | A10-6700 APU with Radeon HD... | 29744    | 4     | 16K  | 64K  | 2048K |        | 3700    | AMD-V |
| Intel     | Core i3-4170                   | 29616    | 4     | 32K  | 32K  | 256K  | 3072K  | 3700    | VT-x  |
| Intel     | Core i3-4360                   | 29612    | 4     | 32K  | 32K  | 256K  | 4096K  | 3700    | VT-x  |
| Intel     | Pentium Gold G5400             | 29608    | 4     | 32K  | 32K  | 256K  | 4096K  | 3700    | VT-x  |
| Intel     | Core i3-9300                   | 29608    | 4     | 128K | 128K | 1M    | 8M     | 4300    | VT-x  |
| Intel     | Core i3-6100                   | 29608    | 4     | 32K  | 32K  | 256K  | 3072K  | 3700    | VT-x  |
| Intel     | Pentium G4620                  | 29600    | 4     | 32K  | 32K  | 256K  | 3072K  | 3700    | VT-x  |
| Intel     | Core i7 Q 740                  | 29600    | 8     | 32K  | 32K  | 256K  | 6144K  | 1734    | VT-x  |
| Intel     | Core i3-8300                   | 29596    | 4     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| AMD       | PRO A12-8870 R7, 12 COMPUTE... | 29544    | 4     | 64K  | 192K | 2M    |        | 3700    | AMD-V |
| AMD       | +8G                            | 29544    | 4     | 16K  | 96K  | 2048K |        | 3700    | AMD-V |
| AMD       | A10-7850K APU with Radeon R... | 29544    | 4     | 16K  | 96K  | 2048K |        | 3700    | AMD-V |
| AMD       | A10 PRO-7850B R7, 12 Comput... | 29544    | 4     | 16K  | 96K  | 2048K |        | 3700    | AMD-V |
| Intel     | Core i3 540                    | 29432    | 4     | 32K  | 32K  | 256K  | 4096K  | 3067    | VT-x  |
| AMD       | Phenom II X4 B40               | 29396    | 4     | 64K  | 64K  | 512K  |        | 3000    | AMD-V |
| Intel     | Xeon E5450                     | 29392    | 4     | 32K  | 32K  | 6144K |        | 3003    | VT-x  |
| Intel     | Core i3-4160                   | 29380    | 4     | 32K  | 32K  | 256K  | 3072K  | 3600    | VT-x  |
| Intel     | Core2 Quad Q9550               | 29308    | 4     | 32K  | 32K  | 6144K |        | 3400    | VT-x  |
| AMD       | Phenom II X4 975               | 28940    | 4     | 64K  | 64K  | 512K  | 6144K  | 3600    | AMD-V |
| AMD       | Phenom II X4 B55               | 28924    | 4     | 64K  | 64K  | 512K  | 6144K  | 3600    | AMD-V |
| Intel     | Xeon E5440                     | 28896    | 4     | 32K  | 32K  | 6144K |        | 3400    | VT-x  |
| Intel     | Core i5 750                    | 28892    | 4     | 32K  | 32K  | 256K  | 8192K  | 2799    | VT-x  |
| Intel     | Core i5-1130G7                 | 28872    | 8     | 192K | 128K | 5M    | 8M     | 4000    | VT-x  |
| Intel     | Core i5-4690                   | 28844    | 4     | 32K  | 32K  | 256K  | 6144K  | 3900    | VT-x  |
| Intel     | Core2 Quad Q6600               | 28828    | 4     | 32K  | 32K  | 4096K |        | 3000    | VT-x  |
| Intel     | Core i3-8100                   | 28828    | 4     | 32K  | 32K  | 256K  | 6144K  | 3600    | VT-x  |
| Intel     | Core i5-3570K                  | 28828    | 4     | 32K  | 32K  | 256K  | 6144K  | 6300    | VT-x  |
| Intel     | Core i5-8250U                  | 28816    | 8     | 32K  | 32K  | 256K  | 6144K  | 3400    | VT-x  |
| Intel     | Core i5-8265U                  | 28808    | 8     | 32K  | 32K  | 256K  | 6144K  | 3900    | VT-x  |
| Intel     | Core i5-8265U                  | 28808    | 8     | 32K  | 32K  | 256K  | 6144K  | 3900    | VT-x  |
| Intel     | Core i3-9100F                  | 28808    | 4     | 32K  | 32K  | 256K  | 6144K  | 4200    | VT-x  |
| Intel     | Core i3-9100                   | 28808    | 4     | 32K  | 32K  | 256K  | 6144K  | 4200    | VT-x  |
| Intel     | Core i3-9100F                  | 28808    | 4     | 32K  | 32K  | 256K  | 6144K  | 4200    | VT-x  |
| Intel     | Pentium G4600                  | 28808    | 4     | 32K  | 32K  | 256K  | 3072K  | 3600    | VT-x  |
| Intel     | Xeon X5450                     | 28808    | 4     | 32K  | 32K  | 6144K |        | 3000    | VT-x  |
| AMD       | Ryzen 3 PRO 3200G with Rade... | 28800    | 4     | 32K  | 64K  | 512K  | 4096K  | 3600    | AMD-V |
| Intel     | Core i5-8265UC                 | 28800    | 8     | 32K  | 32K  | 256K  | 6144K  | 3900    | VT-x  |
| Intel     | Core i3-8100B                  | 28800    | 4     | 128K | 128K | 1M    | 6M     | 3600    | VT-x  |
| Intel     | Core i5 680                    | 28800    | 4     | 32K  | 32K  | 256K  | 4096K  | 3592    | VT-x  |
| Intel     | Core i3-4340                   | 28800    | 4     | 32K  | 32K  | 256K  | 4096K  | 3600    | VT-x  |
| Intel     | Core i3-4350                   | 28800    | 4     | 64K  | 64K  | 512K  | 4M     | 3600    | VT-x  |
| Intel     | Core i3-6098P                  | 28800    | 4     | 32K  | 32K  | 256K  | 3072K  | 3600    | VT-x  |
| Intel     | Core2 Extreme Q6850            | 28796    | 4     | 32K  | 32K  | 4096K |        | 3006    | VT-x  |
| Intel     | Xeon E5450                     | 28796    | 4     | 32K  | 32K  | 6144K |        | 3166    | VT-x  |
| AMD       | Athlon II X4 645               | 28792    | 4     | 64K  | 64K  | 512K  |        | 3100    | AMD-V |
| AMD       | A8-7670K Radeon R7, 10 Comp... | 28760    | 4     | 16K  | 96K  | 2048K |        | 3600    | AMD-V |
| AMD       | A10-8750 Radeon R7, 12 Comp... | 28748    | 4     | 16K  | 96K  | 2048K |        | 3600    | AMD-V |
| AMD       | PRO A10-8750B R7, 12 Comput... | 28744    | 4     | 32K  | 192K | 4M    |        | 3600    | AMD-V |
| Intel     | Core i7-4860EQ                 | 28728    | 8     | 32K  | 32K  | 256K  | 6144K  | 3200    | VT-x  |
| Intel     | Core i5-3570                   | 28640    | 4     | 32K  | 32K  | 256K  | 6144K  | 6300    | VT-x  |
| Intel     | Core i5-4690K                  | 28560    | 4     | 32K  | 32K  | 256K  | 6144K  | 4800    | VT-x  |
| AMD       | Phenom II X4 B50               | 28520    | 4     | 64K  | 64K  | 512K  | 6144K  | 3100    | AMD-V |
| AMD       | A10-5700 APU with Radeon HD... | 28496    | 4     | 16K  | 64K  | 2048K |        | 3400    | AMD-V |
| AMD       | Ryzen 5 4500U with Radeon G... | 28458    | 6     | 192K | 192K | 3M    | 8M     | 2375    | AMD-V |
| Intel     | Xeon X5450                     | 28448    | 4     | 32K  | 32K  | 6144K |        | 3006    | VT-x  |
| AMD       | A10-7800 Radeon R7, 12 Comp... | 28152    | 4     | 16K  | 96K  | 2048K |        | 3500    | AMD-V |
| AMD       | A8-6500B APU with Radeon HD... | 28136    | 4     | 16K  | 64K  | 2048K |        | 3500    | AMD-V |
| AMD       | Phenom II X4 955               | 28128    | 4     | 64K  | 64K  | 512K  | 6144K  | 3200    | AMD-V |
| AMD       | Phenom II X4 945               | 28092    | 4     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| AMD       | Athlon II X4 630               | 28080    | 4     | 64K  | 64K  | 512K  |        | 2800    | AMD-V |
| Intel     | Core i3-3250                   | 28080    | 4     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| Intel     | Pentium G4560                  | 28056    | 4     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| Intel     | Core i3-4330                   | 28048    | 4     | 32K  | 32K  | 256K  | 4096K  | 3500    | VT-x  |
| Intel     | Core i5-7600                   | 28040    | 4     | 32K  | 32K  | 256K  | 6144K  | 4100    | VT-x  |
| Intel     | Xeon X5460                     | 28040    | 4     | 32K  | 32K  | 6144K |        | 3166    | VT-x  |
| Intel     | Core i5-6600K                  | 28040    | 4     | 32K  | 32K  | 256K  | 6144K  | 4500    | VT-x  |
| Intel     | Core i7-7567U                  | 28032    | 4     | 32K  | 32K  | 256K  | 4096K  | 4000    | VT-x  |
| Intel     | Xeon E-2224G                   | 28032    | 4     | 32K  | 32K  | 256K  | 8192K  | 4700    | VT-x  |
| Intel     | Core i5-2550K                  | 28016    | 4     | 32K  | 32K  | 256K  | 6144K  | 3800    | VT-x  |
| Intel     | Core i3-3240                   | 28016    | 4     | 32K  | 32K  | 256K  | 3072K  | 3400    | VT-x  |
| Intel     | Core i3-4150                   | 28012    | 4     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| AMD       | Ryzen 3 2300X Quad-Core        | 28008    | 4     | 128K | 256K | 2M    | 8M     | 3500    | AMD-V |
| AMD       | A8-6500 APU with Radeon HD ... | 28000    | 4     | 16K  | 64K  | 2048K |        | 3500    | AMD-V |
| AMD       | Athlon 240GE with Radeon Ve... | 28000    | 4     | 32K  | 64K  | 512K  | 4096K  | 3500    | AMD-V |
| AMD       | Ryzen 3 PRO 2200G with Rade... | 28000    | 4     | 32K  | 64K  | 512K  | 4096K  | 3500    | AMD-V |
| AMD       | Ryzen 3 PRO 1300 Quad-Core     | 27996    | 4     | 128K | 256K | 2M    | 8M     | 3500    | AMD-V |
| AMD       | PRO A10-9700 R7, 10 COMPUTE... | 27948    | 4     | 32K  | 96K  | 1024K |        | 3500    | AMD-V |
| AMD       | A10 PRO-7800B R7, 12 Comput... | 27948    | 4     | 16K  | 96K  | 2048K |        | 3500    | AMD-V |
| AMD       | A8-7680 Radeon R7, 10 Compu... | 27948    | 4     | 32K  | 96K  | 1024K |        | 3500    | AMD-V |
| AMD       | Athlon X4 845 Quad Core        | 27948    | 4     | 32K  | 96K  | 1024K |        | 3500    | AMD-V |
| AMD       | FX-770K Quad Core              | 27944    | 4     | 16K  | 96K  | 2048K |        |         | AMD-V |
| Intel     | Core i5 670                    | 27820    | 4     | 32K  | 32K  | 256K  | 4096K  | 3468    | VT-x  |
| Intel     | Core i3-4130                   | 27744    | 4     | 32K  | 32K  | 256K  | 3072K  | 3400    | VT-x  |
| Intel     | Pentium D                      | 27732    | 4     | 16K  |      | 2048K |        |         | VT-x  |
| AMD       | Phenom II X4 850               | 27720    | 4     | 64K  | 64K  | 512K  |        | 3300    | AMD-V |
| Intel     | Core i7 Q 820                  | 27672    | 8     | 32K  | 32K  | 256K  | 8192K  | 1734    | VT-x  |
| Intel     | Core i5 670                    | 27664    | 4     | 32K  | 32K  | 256K  | 4096K  | 3468    | VT-x  |
| Intel     | Core Q 820                     | 27656    | 8     | 32K  | 32K  | 256K  | 8192K  | 1734    | VT-x  |
| Intel     | Core i5-8600T                  | 27648    | 6     | 32K  | 32K  | 256K  | 9216K  | 3700    | VT-x  |
| AMD       | Opteron 4174 HE                | 27600    | 6     | 64K  | 64K  | 512K  | 6144K  | 2300    | AMD-V |
| AMD       | Phenom II X4 965               | 27348    | 4     | 64K  | 64K  | 512K  | 6144K  | 3400    | AMD-V |
| AMD       | Athlon II X4 559               | 27328    | 4     | 64K  | 64K  | 512K  | 6144K  | 2700    | AMD-V |
| Intel     | Core i7 Q 720                  | 27328    | 8     | 32K  | 32K  | 256K  | 6144K  | 1600    | VT-x  |
| AMD       | Phenom II X4 B60               | 27324    | 4     | 64K  | 64K  | 512K  |        |         | AMD-V |
| AMD       | Phenom II X4 B60               | 27320    | 4     | 64K  | 64K  | 512K  | 6144K  | 3400    | AMD-V |
| AMD       | Phenom II X4 B65               | 27320    | 4     | 64K  | 64K  | 512K  | 6144K  | 3400    | AMD-V |
| Intel     | Core i5-4670                   | 27308    | 4     | 32K  | 32K  | 256K  | 6144K  | 3800    | VT-x  |
| Intel     | Core i3-2130                   | 27288    | 4     | 32K  | 32K  | 256K  | 3072K  | 3400    | VT-x  |
| Intel     | Core i5-7500                   | 27272    | 4     | 32K  | 32K  | 256K  | 6144K  | 3800    | VT-x  |
| Intel     | Core i3-7100T                  | 27264    | 4     | 32K  | 32K  | 256K  | 3072K  | 3400    | VT-x  |
| Intel     | Core i5-4670K                  | 27256    | 4     | 32K  | 32K  | 256K  | 6144K  | 4500    | VT-x  |
| AMD       | Phenom II X4 920               | 27212    | 4     | 64K  | 64K  | 512K  | 6144K  | 2800    | AMD-V |
| Intel     | Core i3-2120                   | 27212    | 4     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| Intel     | Core i5-2500K                  | 27212    | 4     | 32K  | 32K  | 256K  | 6144K  | 6300    | VT-x  |
| Intel     | Core i5-2500                   | 27204    | 4     | 32K  | 32K  | 256K  | 6144K  | 5900    | VT-x  |
| Intel     | Core i3-3220                   | 27204    | 4     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| AMD       | Athlon 220GE with Radeon Ve... | 27200    | 4     | 32K  | 64K  | 512K  | 4096K  | 3400    | AMD-V |
| Intel     | Core2 Quad Q9505               | 27200    | 4     | 32K  | 32K  | 3072K |        | 2834    | VT-x  |
| Intel     | Core i3-3245                   | 27200    | 4     | 32K  | 32K  | 256K  | 3072K  | 3400    | VT-x  |
| Intel     | Xeon Bronze 3106               | 27200    | 8     | 32K  | 32K  | 1024K | 11264K | 1700    | VT-x  |
| Intel     | Xeon E-2124G                   | 27196    | 4     | 128K | 128K | 1M    | 8M     | 4500    | VT-x  |
| Intel     | Xeon E-2224                    | 27196    | 4     | 32K  | 32K  | 256K  | 8192K  | 4600    | VT-x  |
| Intel     | Pentium Gold G6400T            | 27196    | 4     | 64K  | 64K  | 512K  | 4M     | 3400    | VT-x  |
| Intel     | Core i5-4590                   | 27184    | 4     | 32K  | 32K  | 256K  | 6144K  | 3700    | VT-x  |
| Intel     | Xeon E5-2609 v4                | 27168    | 8     | 32K  | 32K  | 256K  | 20480K | 1700    | VT-x  |
| AMD       | A10-7700K APU with Radeon R... | 27160    | 4     | 16K  | 96K  | 2048K |        | 3400    | AMD-V |
| AMD       | Athlon X4 750 Quad Core        | 27148    | 4     | 16K  | 64K  | 2048K |        |         | AMD-V |
| Intel     | Core i5-3470                   | 27064    | 4     | 32K  | 32K  | 256K  | 6144K  | 6300    | VT-x  |
| AMD       | Phenom II X4 925               | 26968    | 4     | 64K  | 64K  | 512K  | 6144K  | 2800    | AMD-V |
| AMD       | Phenom II X4 840               | 26952    | 4     | 64K  | 64K  | 512K  |        | 3200    | AMD-V |
| AMD       | Phenom II X4 B50               | 26880    | 4     | 64K  | 64K  | 512K  | 6M     | 3200    | AMD-V |
| Intel     | Core i3 560                    | 26788    | 4     | 32K  | 32K  | 256K  | 4096K  | 3333    | VT-x  |
| Intel     | Core i5 661                    | 26756    | 4     | 32K  | 32K  | 256K  | 4096K  | 3334    | VT-x  |
| Intel     | Core i5 650                    | 26752    | 4     | 32K  | 32K  | 256K  | 4096K  | 3333    | VT-x  |
| Intel     | Core i5 661                    | 26748    | 4     | 32K  | 32K  | 256K  | 4096K  | 3334    | VT-x  |
| Intel     | Core i5 660                    | 26748    | 4     | 32K  | 32K  | 256K  | 4096K  | 3466    | VT-x  |
| AMD       | Phenom II X4 B35               | 26688    | 4     | 64K  | 64K  | 512K  | 6144K  | 2900    | AMD-V |
| AMD       | Athlon II X4 635               | 26680    | 4     | 64K  | 64K  | 512K  |        | 2900    | AMD-V |
| Intel     | Core i3-3225                   | 26632    | 4     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| Intel     | Core2 Quad Q9300               | 26628    | 4     | 32K  | 32K  | 3072K |        | 3000    | VT-x  |
| AMD       | Phenom II X4 B55               | 26516    | 4     | 64K  | 64K  | 512K  |        | 3300    | AMD-V |
| AMD       | FX-4200 Quad-Core              | 26516    | 4     | 16K  | 64K  | 2048K | 8192K  | 3300    | AMD-V |
| Intel     | Core i5-6600                   | 26508    | 4     | 32K  | 32K  | 256K  | 6144K  | 3900    | VT-x  |
| Intel     | Core2 Quad Q9650               | 26500    | 4     | 32K  | 32K  | 6144K |        | 3003    | VT-x  |
| Intel     | Core i5-9500T                  | 26496    | 6     | 32K  | 32K  | 256K  | 9216K  | 3700    | VT-x  |
| Intel     | Core i5-9500TE                 | 26496    | 6     | 32K  | 32K  | 256K  | 9216K  | 2200    | VT-x  |
| Intel     | Xeon E-2124                    | 26496    | 4     | 32K  | 32K  | 256K  | 8192K  | 4300    | VT-x  |
| Intel     | Xeon E3-1225 v6                | 26496    | 4     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Xeon E3-1225 v5                | 26496    | 4     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Core i5-3550                   | 26488    | 4     | 32K  | 32K  | 256K  | 6144K  | 3700    | VT-x  |
| Intel     | Core i3-2125                   | 26484    | 4     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| AMD       | Phenom II X4 B45               | 26400    | 4     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| AMD       | A8-3870 APU with Radeon HD ... | 26400    | 4     | 64K  | 64K  | 1024K |        | 3300    | AMD-V |
| Intel     | Core i7-6567U                  | 26396    | 4     | 32K  | 32K  | 256K  | 4096K  | 3600    | VT-x  |
| Intel     | Core i3-6300T                  | 26396    | 4     | 64K  | 64K  | 512K  | 4M     | 3300    | VT-x  |
| AMD       | Athlon X4 740 Quad Core        | 26388    | 4     | 16K  | 64K  | 2048K |        | 3200    | AMD-V |
| Intel     | Core i5-2400                   | 26388    | 4     | 32K  | 32K  | 256K  | 6144K  | 6300    | VT-x  |
| Intel     | Core2 Quad Q9400               | 26368    | 4     | 32K  | 32K  | 3072K |        | 2672    | VT-x  |
| Intel     | Core i5-4570                   | 26364    | 4     | 32K  | 32K  | 256K  | 6144K  | 3600    | VT-x  |
| Intel     | Core i5-4460                   | 26360    | 4     | 32K  | 32K  | 256K  | 6144K  | 3400    | VT-x  |
| AMD       | Ryzen 3 3200GE with Radeon ... | 26348    | 4     | 32K  | 64K  | 512K  | 4096K  | 3300    | AMD-V |
| AMD       | Ryzen 3 PRO 3200GE w_ Radeo... | 26348    | 4     | 32K  | 64K  | 512K  | 4096K  | 3300    | AMD-V |
| Intel     | Xeon E3-1226 v3                | 26348    | 4     | 32K  | 32K  | 256K  | 8192K  | 3700    | VT-x  |
| Intel     | Core i3-4370T                  | 26340    | 4     | 64K  | 64K  | 512K  | 4M     | 3300    | VT-x  |
| AMD       | Phenom II X4 945               | 26160    | 4     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| Intel     | Xeon E5472                     | 26096    | 4     | 32K  | 32K  | 6144K |        | 3000    | VT-x  |
| AMD       | Phenom II X4 925               | 25984    | 4     | 64K  | 64K  | 512K  | 6144K  | 2800    | AMD-V |
| Intel     | Core i5-2450P                  | 25828    | 4     | 32K  | 32K  | 256K  | 6144K  | 3700    | VT-x  |
| AMD       | Athlon II X4 650               | 25780    | 4     | 64K  | 64K  | 512K  |        | 3200    | AMD-V |
| AMD       | A8-5500 APU with Radeon HD ... | 25736    | 4     | 16K  | 64K  | 2048K |        | 3200    | AMD-V |
| AMD       | Phenom II X4 20                | 25712    | 4     | 64K  | 64K  | 512K  | 6144K  | 3200    | AMD-V |
| Intel     | Core i5 650                    | 25708    | 4     | 32K  | 32K  | 256K  | 4096K  | 3333    | VT-x  |
| AMD       | Athlon II X4 620               | 25688    | 4     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| Intel     | Core i5 K 655                  | 25680    | 4     | 32K  | 32K  | 256K  | 4096K  | 3201    | VT-x  |
| Intel     | Core2 Extreme X9770            | 25640    | 4     | 32K  | 32K  | 6144K |        | 3200    | VT-x  |
| AMD       | Phenom II X4 B35               | 25636    | 4     | 64K  | 64K  | 512K  | 6144K  | 2900    | AMD-V |
| Intel     | Core i3-3210                   | 25632    | 4     | 32K  | 32K  | 256K  | 3072K  | 3200    | VT-x  |
| Intel     | Core2 Quad Q9450               | 25628    | 4     | 32K  | 32K  | 6144K |        | 3200    | VT-x  |
| Intel     | Xeon X5482                     | 25608    | 4     | 32K  | 32K  | 6144K |        | 3200    | VT-x  |
| Intel     | Core i3-6100T                  | 25608    | 4     | 32K  | 32K  | 256K  | 3072K  | 3200    | VT-x  |
| Intel     | Core i5-6500                   | 25608    | 4     | 32K  | 32K  | 256K  | 6144K  | 3600    | VT-x  |
| AMD       | A8-5500B APU with Radeon HD... | 25600    | 4     | 16K  | 64K  | 2048K |        | 3200    | AMD-V |
| AMD       | Athlon 200GE with Radeon Ve... | 25600    | 4     | 32K  | 64K  | 512K  | 4096K  | 3200    | AMD-V |
| Intel     | Core2 Quad Q6700               | 25600    | 4     | 32K  | 32K  | 4096K |        | 2670    | VT-x  |
| Intel     | Core2 Quad                     | 25600    | 4     | 32K  | 32K  | 4096K |        | 2670    | VT-x  |
| Intel     | Core2 Quad Q8400               | 25600    | 4     | 32K  | 32K  | 2048K |        | 3200    | VT-x  |
| AMD       | Ryzen 3 PRO 2100GE w_ Radeo... | 25596    | 4     | 32K  | 64K  | 512K  | 4096K  | 3200    | AMD-V |
| Intel     | Pentium Gold G5420T            | 25596    | 4     | 32K  | 32K  | 256K  | 4096K  | 3200    | VT-x  |
| Intel     | Xeon X5482                     | 25596    | 4     | 32K  | 32K  | 6144K |        | 3203    | VT-x  |
| Intel     | Core i5-4690S                  | 25596    | 4     | 32K  | 32K  | 256K  | 6144K  | 3900    | VT-x  |
| Intel     | Xeon W-2104                    | 25596    | 4     | 128K | 128K | 4M    | 8.3M   | 3200    | VT-x  |
| Intel     | Core i3-2100                   | 25560    | 4     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| Intel     | Core i5-3450                   | 25560    | 4     | 32K  | 32K  | 256K  | 6144K  | 6300    | VT-x  |
| AMD       | PRO A8-8650B R7, 10 Compute... | 25552    | 4     | 16K  | 96K  | 2048K |        | 3200    | AMD-V |
| AMD       | Ryzen 3 2200GE with Radeon ... | 25552    | 4     | 32K  | 64K  | 512K  | 4096K  | 3200    | AMD-V |
| AMD       | Ryzen 3 PRO 2200GE w_ Radeo... | 25552    | 4     | 128K | 256K | 2M    | 4M     | 3200    | AMD-V |
| Intel     | Core i3-4170T                  | 25552    | 4     | 32K  | 32K  | 256K  | 3072K  | 3200    | VT-x  |
| AMD       | Phenom II X4 B97               | 25544    | 4     | 64K  | 64K  | 512K  | 6144K  | 3200    | AMD-V |
| AMD       | A8-7600 Radeon R7, 10 Compu... | 25544    | 4     | 16K  | 96K  | 2048K |        | 3100    | AMD-V |
| Intel     | Xeon E3-1225 V2                | 25544    | 4     | 32K  | 32K  | 256K  | 8192K  | 3600    | VT-x  |
| AMD       | Athlon X4 840 Quad Core        | 25540    | 4     | 16K  | 96K  | 2048K |        | 3100    | AMD-V |
| Intel     | Xeon E3-1225 v3                | 25540    | 4     | 32K  | 32K  | 256K  | 8192K  | 3600    | VT-x  |
| Intel     | Core2 Extreme X9775            | 25536    | 4     | 32K  | 32K  | 6144K |        | 3200    | VT-x  |
| Intel     | Core i5-4440                   | 25536    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Xeon                           | 25532    | 4     | 16K  |      | 2048K |        |         | VT-x  |
| Intel     | Core i5-3330                   | 25396    | 4     | 32K  | 32K  | 256K  | 6144K  | 6300    | VT-x  |
| Intel     | Xeon X5460                     | 25388    | 4     | 32K  | 32K  | 6144K |        | 3167    | VT-x  |
| Intel     | Core i5-8500T                  | 25344    | 6     | 32K  | 32K  | 256K  | 9216K  | 3500    | VT-x  |
| Intel     | Core2 Extreme X9650            | 25332    | 4     | 32K  | 32K  | 6144K |        | 3000    | VT-x  |
| Intel     | Core2 Extreme X9650            | 25332    | 4     | 32K  | 32K  | 6144K |        |         | VT-x  |
| AMD       | Opteron 4170 HE                | 25200    | 6     | 64K  | 64K  | 512K  | 5118K  | 2100    | AMD-V |
| AMD       | Athlon II X4 630               | 25180    | 4     | 64K  | 64K  | 512K  |        | 2800    | AMD-V |
| Intel     | Core i5-3340                   | 25016    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| AMD       | Phenom II X4 B45               | 24964    | 4     | 64K  | 64K  | 512K  |        | 3100    | AMD-V |
| Intel     | Core i5-2380P                  | 24880    | 4     | 32K  | 32K  | 256K  | 6144K  | 3400    | VT-x  |
| Intel     | Core i5-3350P                  | 24824    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Core i7-5557U                  | 24812    | 4     | 32K  | 32K  | 256K  | 4096K  | 3400    | VT-x  |
| Intel     | Xeon E3-1220 V2                | 24808    | 4     | 32K  | 32K  | 256K  | 8192K  | 3500    | VT-x  |
| Intel     | Xeon E31220                    | 24800    | 4     | 32K  | 32K  | 256K  | 8192K  | 3400    | VT-x  |
| Intel     | Xeon E31225                    | 24800    | 4     | 32K  | 32K  | 256K  | 6144K  | 3400    | VT-x  |
| Intel     | Core i5-4670S                  | 24800    | 4     | 32K  | 32K  | 256K  | 6144K  | 3800    | VT-x  |
| Intel     | Xeon E3-1220 v3                | 24800    | 4     | 32K  | 32K  | 256K  | 8192K  | 3500    | VT-x  |
| AMD       | Ryzen 3 1200 Quad-Core         | 24796    | 4     | 32K  | 64K  | 512K  | 8192K  | 3100    | AMD-V |
| Intel     | Core i5-7267U                  | 24796    | 4     | 32K  | 32K  | 256K  | 4096K  | 3500    | VT-x  |
| Intel     | Core i3-8100T                  | 24796    | 4     | 32K  | 32K  | 256K  | 6144K  | 3100    | VT-x  |
| Intel     | Core i3-9100T                  | 24796    | 4     | 32K  | 32K  | 256K  | 6144K  | 3700    | VT-x  |
| Intel     | Core i3-4160T                  | 24792    | 4     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| Intel     | Pentium Gold G5400T            | 24776    | 4     | 32K  | 32K  | 256K  | 4096K  | 3100    | VT-x  |
| AMD       | A12-9800E RADEON R7, 12 COM... | 24760    | 4     | 32K  | 96K  | 1024K |        | 3100    | AMD-V |
| AMD       | A8 PRO-7600B R7, 10 Compute... | 24760    | 4     | 16K  | 96K  | 2048K |        | 3100    | AMD-V |
| AMD       | PRO A12-9800E R7, 12 COMPUT... | 24752    | 4     | 32K  | 96K  | 1024K |        | 3100    | AMD-V |
| AMD       | PRO A8-9600 R7, 10 COMPUTE ... | 24752    | 4     | 32K  | 96K  | 1024K |        | 3100    | AMD-V |
| Intel     | Core i3-2105                   | 24752    | 4     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| Intel     | Core i5-3570S                  | 24752    | 4     | 128K | 128K | 1M    | 6M     | 3800    | VT-x  |
| Intel     | Core i3-4350T                  | 24752    | 4     | 32K  | 32K  | 256K  | 4096K  | 3100    | VT-x  |
| AMD       | Phenom II X4 B50               | 24744    | 4     | 64K  | 64K  | 512K  | 6144K  | 3100    | AMD-V |
| Intel     | Xeon E5-1607 v4                | 24744    | 4     | 32K  | 32K  | 256K  | 10240K | 3100    | VT-x  |
| Intel     | Core i5-5675R                  | 24740    | 4     | 32K  | 32K  | 256K  | 4096K  | 3600    | VT-x  |
| Intel     | Core i5-2320                   | 24728    | 4     | 32K  | 32K  | 256K  | 6144K  | 6300    | VT-x  |
| AMD       | Athlon II X4 651 Quad-Core     | 24712    | 4     | 64K  | 64K  | 1024K |        | 3000    | AMD-V |
| Intel     | Core i5-4430                   | 24480    | 4     | 32K  | 32K  | 256K  | 6144K  | 3200    | VT-x  |
| Intel     | Xeon E5430                     | 24320    | 4     | 32K  | 32K  | 6144K |        | 2670    | VT-x  |
| AMD       | Phenom II X4 940               | 24160    | 4     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| AMD       | Phenom II X4 B40               | 24108    | 4     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| AMD       | Athlon X4 640                  | 24108    | 4     | 64K  | 64K  | 512K  |        | 3000    | AMD-V |
| AMD       | Phenom II X4 B95               | 24104    | 4     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| AMD       | Phenom II X4 B95               | 24104    | 4     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| Intel     | Core2 Quad Q8200               | 24076    | 4     | 32K  | 32K  | 2048K |        | 2336    |       |
| Intel     | Core i5-7400                   | 24016    | 4     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| Intel     | Core i3-8109U                  | 24008    | 4     | 32K  | 32K  | 256K  | 4096K  | 3600    | VT-x  |
| Intel     | Core i7-10510Y                 | 24008    | 8     | 128K | 128K | 1M    | 8M     | 4500    | VT-x  |
| Intel     | Xeon E3-1220 v6                | 24008    | 4     | 32K  | 32K  | 256K  | 8192K  | 3500    | VT-x  |
| Intel     | Xeon E3-1220 v5                | 24008    | 4     | 32K  | 32K  | 256K  | 8192K  | 3500    | VT-x  |
| AMD       | Athlon II X4 640               | 24000    | 4     | 64K  | 64K  | 512K  |        | 3000    | AMD-V |
| Intel     | Xeon E5472                     | 24000    | 4     | 32K  | 32K  | 6144K |        |         |       |
| Intel     | Xeon X3370                     | 24000    | 4     | 32K  | 32K  | 6144K |        | 2997    | VT-x  |
| Intel     | Xeon E5-2630L 0                | 24000    | 6     | 32K  | 32K  | 256K  | 15360K | 2500    | VT-x  |
| Intel     | Core i3-4150T                  | 24000    | 4     | 32K  | 32K  | 256K  | 3072K  | 3000    | VT-x  |
| Intel     | Core i5-4590S                  | 24000    | 4     | 32K  | 32K  | 256K  | 6144K  | 3700    | VT-x  |
| Intel     | Xeon E5-1607 v2                | 24000    | 4     | 32K  | 32K  | 256K  | 10240K | 3000    | VT-x  |
| AMD       | PRO A10-9700E R7, 10 COMPUT... | 23996    | 4     | 32K  | 96K  | 1024K |        | 3000    | AMD-V |
| Intel     | Core i7-1065G7                 | 23984    | 8     | 48K  | 32K  | 512K  | 8192K  | 3900    | VT-x  |
| Intel     | Xeon X3220                     | 23976    | 4     | 32K  | 32K  | 4096K |        | 3000    | VT-x  |
| Intel     | Core i5-1035G4                 | 23968    | 8     | 192K | 128K | 2M    | 6M     | 3700    | VT-x  |
| Intel     | Core i3-1115G4                 | 23968    | 4     | 96K  | 64K  | 2.5M  | 6M     | 4100    | VT-x  |
| Intel     | Core i5-1035G7                 | 23960    | 8     | 48K  | 32K  | 512K  | 6144K  | 3700    | VT-x  |
| AMD       | A10-9700E RADEON R7, 10 COM... | 23956    | 4     | 32K  | 96K  | 1024K |        | 3000    | AMD-V |
| AMD       | FX-9830P RADEON R7, 12 COMP... | 23956    | 4     | 32K  | 96K  | 1024K |        | 3000    | AMD-V |
| Intel     | Core i7-4610M                  | 23956    | 4     | 32K  | 32K  | 256K  | 4096K  | 3700    | VT-x  |
| AMD       | EPYC 3201 8-Core               | 23952    | 8     | 32K  | 64K  | 512K  | 8192K  | 1500    | AMD-V |
| Intel     | Core i5-3550S                  | 23952    | 4     | 32K  | 32K  | 256K  | 6144K  | 3700    | VT-x  |
| AMD       | A6-3650 APU with Radeon HD ... | 23948    | 4     | 64K  | 64K  | 1024K |        | 2600    | AMD-V |
| Intel     | Core i7-3540M                  | 23944    | 4     | 32K  | 32K  | 256K  | 4096K  | 3700    | VT-x  |
| Intel     | Xeon X5365                     | 23940    | 4     | 32K  | 32K  | 4096K |        | 3000    | VT-x  |
| Intel     | Xeon X5365                     | 23940    | 4     | 256K | 256K | 16M   |        |         | VT-x  |
| Intel     | Xeon X5472                     | 23940    | 4     | 32K  | 32K  | 6144K |        | 3000    | VT-x  |
| Intel     | Xeon E5-1607 0                 | 23940    | 4     | 32K  | 32K  | 256K  | 10240K | 3000    | VT-x  |
| Intel     | Xeon E5-2637 0                 | 23940    | 4     | 32K  | 32K  | 256K  | 5120K  | 3500    | VT-x  |
| Intel     | Core i5-2310                   | 23908    | 4     | 32K  | 32K  | 256K  | 6144K  | 6000    | VT-x  |
| Intel     | Core i5-3470S                  | 23892    | 4     | 32K  | 32K  | 256K  | 6144K  | 3600    | VT-x  |
| Intel     | Core i3-4130T                  | 23660    | 4     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| Intel     | Core i5 M 480                  | 23528    | 4     | 32K  | 32K  | 256K  | 3072K  | 2667    | VT-x  |
| Intel     | Core2 Quad Q8200               | 23520    | 4     | 32K  | 32K  | 2048K |        | 2336    |       |
| Intel     | Core2 Extreme Q6800            | 23504    | 4     | 32K  | 32K  | 4096K |        | 2926    | VT-x  |
| Intel     | Core i3 530                    | 23408    | 4     | 32K  | 32K  | 256K  | 4096K  | 2926    | VT-x  |
| AMD       | Athlon II X4 635               | 23316    | 4     | 64K  | 64K  | 512K  |        | 2900    | AMD-V |
| AMD       | Quad-Core Opteron 1389         | 23308    | 4     | 256K | 256K | 2M    | 6M     | 2900    | AMD-V |
| AMD       | Phenom II X4 840T              | 23304    | 4     | 64K  | 64K  | 512K  | 6144K  | 2900    | AMD-V |
| Intel     | Core i7-7500U                  | 23252    | 4     | 32K  | 32K  | 256K  | 4096K  | 3500    | VT-x  |
| Intel     | Core i3 M 380                  | 23252    | 4     | 32K  | 32K  | 256K  | 3072K  | 2533    | VT-x  |
| Intel     | Core i7-7600U                  | 23240    | 4     | 32K  | 32K  | 256K  | 4096K  | 3900    | VT-x  |
| Intel     | Pentium G4560T                 | 23240    | 4     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| Intel     | Core i5-6267U                  | 23240    | 4     | 32K  | 32K  | 256K  | 4096K  | 3300    | VT-x  |
| Intel     | Core i5-4570S                  | 23236    | 4     | 32K  | 32K  | 256K  | 6144K  | 3600    | VT-x  |
| Intel     | Core i5-3470T                  | 23220    | 4     | 32K  | 32K  | 256K  | 3072K  | 3600    | VT-x  |
| AMD       | A8-3850 APU with Radeon HD ... | 23208    | 4     | 64K  | 64K  | 1024K |        | 2900    | AMD-V |
| Intel     | Core i5-5287U                  | 23204    | 4     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| AMD       | A6-3670 APU with Radeon HD ... | 23200    | 4     | 64K  | 64K  | 1024K |        | 2900    | AMD-V |
| Intel     | Xeon W-2102                    | 23196    | 4     | 128K | 128K | 4M    | 8.3M   | 2900    | VT-x  |
| Intel     | Core i7-3520M                  | 23164    | 4     | 32K  | 32K  | 256K  | 4096K  | 3600    | VT-x  |
| Intel     | Core i5-4210H                  | 23164    | 4     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| Intel     | Core i5-3380M                  | 23156    | 4     | 32K  | 32K  | 256K  | 3072K  | 3600    | VT-x  |
| Intel     | Core i5-4460S                  | 23156    | 4     | 32K  | 32K  | 256K  | 6144K  | 3400    | VT-x  |
| Intel     | Core i5-4570T                  | 23156    | 4     | 32K  | 32K  | 256K  | 4096K  | 3600    | VT-x  |
| Intel     | Core i7-4600M                  | 23156    | 4     | 32K  | 32K  | 256K  | 4096K  | 3600    | VT-x  |
| Intel     | Core i5-4340M                  | 23152    | 4     | 32K  | 32K  | 256K  | 3072K  | 3600    | VT-x  |
| Intel     | Core i3-3240T                  | 23148    | 4     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| Intel     | Core i5-3475S                  | 23148    | 4     | 32K  | 32K  | 256K  | 6144K  | 3600    | VT-x  |
| Intel     | Core i5-2300                   | 23080    | 4     | 32K  | 32K  | 256K  | 6144K  | 6300    | VT-x  |
| AMD       | Athlon II X4 641 Quad-Core     | 23068    | 4     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| AMD       | Athlon II X3 455               | 22770    | 3     | 64K  | 64K  | 512K  |        | 3300    | AMD-V |
| Intel     | Xeon E5-2609 v3                | 22770    | 6     | 384K | 384K | 3M    | 30M    | 1900    | VT-x  |
| Intel     | Xeon E5440                     | 22700    | 4     | 32K  | 32K  | 6144K |        | 2834    | VT-x  |
| Intel     | Xeon X3360                     | 22672    | 4     | 32K  | 32K  | 6144K |        | 2833    | VT-x  |
| Intel     | Xeon X3360                     | 22672    | 4     | 32K  | 32K  | 6144K |        | 20000   | VT-x  |
| Intel     | Xeon X3363                     | 22668    | 4     | 32K  | 32K  | 6144K |        | 2834    | VT-x  |
| Intel     | Core i5 M 560                  | 22608    | 4     | 32K  | 32K  | 256K  | 3072K  | 2667    | VT-x  |
| AMD       | Phenom II X4 820               | 22508    | 4     | 64K  | 64K  | 512K  | 4096K  | 2800    | AMD-V |
| AMD       | Phenom II X4 B93               | 22500    | 4     | 64K  | 64K  | 512K  | 6144K  | 2800    | AMD-V |
| AMD       | Athlon X4 630                  | 22500    | 4     | 64K  | 64K  | 512K  |        | 2800    | AMD-V |
| Intel     | Core i5-7440HQ                 | 22484    | 4     | 32K  | 32K  | 256K  | 6144K  | 3800    | VT-x  |
| Intel     | Core i7-6600U                  | 22472    | 4     | 32K  | 32K  | 256K  | 4096K  | 3400    | VT-x  |
| Intel     | Core i3 M 330                  | 22464    | 4     | 32K  | 32K  | 256K  | 3072K  | 2133    | VT-x  |
| Intel     | Core i5-6402P                  | 22464    | 4     | 128K | 128K | 1M    | 6M     | 3400    | VT-x  |
| Intel     | Core i5-3340S                  | 22424    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Core i3-7167U                  | 22408    | 4     | 64K  | 64K  | 512K  | 3M     | 2800    | VT-x  |
| Intel     | Xeon E5462                     | 22404    | 4     | 32K  | 32K  | 6144K |        | 2803    | VT-x  |
| Intel     | Xeon                           | 22400    | 4     | 16K  |      | 2048K |        | 2800    |       |
| Intel     | Xeon L5410                     | 22400    | 4     | 32K  | 32K  | 6144K |        | 2333    | VT-x  |
| Intel     | Core i7 M 640                  | 22400    | 4     | 32K  | 32K  | 256K  | 4096K  | 2800    | VT-x  |
| Intel     | Xeon E5-1603 v3                | 22400    | 4     | 32K  | 32K  | 256K  | 10240K | 2800    | VT-x  |
| Intel     | Core i7-4558U                  | 22400    | 4     | 32K  | 32K  | 256K  | 4096K  | 3300    | VT-x  |
| AMD       | Phenom 9950 Quad-Core          | 22396    | 4     | 64K  | 64K  | 512K  | 2048K  | 2800    | AMD-V |
| AMD       | Phenom II X4 830               | 22396    | 4     | 64K  | 64K  | 512K  | 6144K  | 2800    | AMD-V |
| Intel     | Core i5-7600T                  | 22396    | 4     | 128K | 128K | 1M    | 6M     | 3700    | VT-x  |
| Intel     | Core i5-4308U                  | 22396    | 4     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| Intel     | Core i5-8257U                  | 22392    | 8     | 32K  | 32K  | 256K  | 6144K  | 3900    | VT-x  |
| AMD       | Athlon X4 730 Quad Core        | 22368    | 4     | 32K  | 128K | 4M    |        | 2800    | AMD-V |
| AMD       | A12-9730P RADEON R7, 10 COM... | 22364    | 4     | 32K  | 96K  | 1024K |        | 2800    | AMD-V |
| Intel     | Core i7-2640M                  | 22364    | 4     | 32K  | 32K  | 256K  | 4096K  | 3500    | VT-x  |
| Intel     | Core i5-4200H                  | 22364    | 4     | 32K  | 32K  | 256K  | 3072K  | 3400    | VT-x  |
| AMD       | PRO A10-8770E R7, 10 COMPUT... | 22360    | 4     | 64K  | 192K | 2M    |        | 2800    | AMD-V |
| Intel     | Core i3-3220T                  | 22356    | 4     | 32K  | 32K  | 256K  | 3072K  | 2800    | VT-x  |
| Intel     | Core i5-3360M                  | 22356    | 4     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| Intel     | Core i5-3450S                  | 22356    | 4     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| Intel     | Core i5-3360M                  | 22348    | 4     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| Intel     | Core i5-4330M                  | 22348    | 4     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| Intel     | Core i5-4440S                  | 22348    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Core i5-5575R                  | 22348    | 4     | 32K  | 32K  | 256K  | 4096K  | 3300    | VT-x  |
| Intel     | Core i5 M 460                  | 22344    | 4     | 32K  | 32K  | 256K  | 3072K  | 2534    | VT-x  |
| Intel     | Xeon E5-1603 0                 | 22344    | 4     | 32K  | 32K  | 256K  | 10240K | 2800    | VT-x  |
| AMD       | Phenom II X4 B93               | 22340    | 4     | 64K  | 64K  | 512K  | 6144K  | 2800    | AMD-V |
| Intel     | Core i5-4570TE                 | 22012    | 4     | 32K  | 32K  | 256K  | 4096K  | 3300    | VT-x  |
| Intel     | Core i5-7200U                  | 21720    | 4     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| Intel     | Core i3-6100H                  | 21716    | 4     | 32K  | 32K  | 256K  | 3072K  | 2700    | VT-x  |
| Intel     | Core i5-6400                   | 21712    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| AMD       | Quad-Core Opteron 1385         | 21708    | 4     | 64K  | 64K  | 512K  | 6144K  | 2700    | AMD-V |
| Intel     | Core i3-7130U                  | 21704    | 4     | 32K  | 32K  | 256K  | 3072K  | 2700    | VT-x  |
| Intel     | Core i5-7300U                  | 21704    | 4     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| Intel     | Core i5-7500T                  | 21696    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Core i5-6600T                  | 21696    | 4     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| Intel     | Core i5-5257U                  | 21624    | 4     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| Intel     | Core i5-9400T                  | 21606    | 6     | 32K  | 32K  | 256K  | 9216K  | 3400    | VT-x  |
| Intel     | 06_17                          | 21600    | 4     | 32K  | 32K  | 2048K |        |         | VT-x  |
| Intel     | Core i5-2390T                  | 21600    | 4     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| Intel     | Core i5-2500S                  | 21600    | 4     | 32K  | 32K  | 256K  | 6144K  | 3700    | VT-x  |
| Intel     | Core i5-3330S                  | 21600    | 4     | 32K  | 32K  | 256K  | 6144K  | 3200    | VT-x  |
| Intel     | Core i5-4430S                  | 21592    | 4     | 32K  | 32K  | 256K  | 6144K  | 3200    | VT-x  |
| Intel     | Core i7-4600U                  | 21576    | 4     | 32K  | 32K  | 256K  | 4096K  | 3300    | VT-x  |
| AMD       | A12-9720P RADEON R7, 12 COM... | 21568    | 4     | 32K  | 96K  | 1024K |        | 2700    | AMD-V |
| AMD       | FX-9800P RADEON R7, 12 COMP... | 21568    | 4     | 32K  | 96K  | 1024K |        | 2700    | AMD-V |
| Intel     | Core i7-2620M                  | 21568    | 4     | 32K  | 32K  | 256K  | 4096K  | 3400    | VT-x  |
| AMD       | Ryzen 3 4300U with Radeon G... | 21564    | 4     | 128K | 128K | 2M    | 4M     | 2700    | AMD-V |
| AMD       | PRO A12-9800B R7, 12 COMPUT... | 21560    | 4     | 64K  | 192K | 2M    |        | 2700    | AMD-V |
| AMD       | FX-7600P Radeon R7, 12 Comp... | 21560    | 4     | 16K  | 64K  | 2048K |        | 2700    | AMD-V |
| Intel     | Core i5-3340M                  | 21560    | 4     | 32K  | 32K  | 256K  | 3072K  | 3400    | VT-x  |
| Intel     | Core i5-4310M                  | 21560    | 4     | 32K  | 32K  | 256K  | 3072K  | 3400    | VT-x  |
| Intel     | Core i5-4570R                  | 21556    | 4     | 32K  | 32K  | 256K  | 4096K  | 3200    | VT-x  |
| Intel     | Core i5-3335S                  | 21548    | 4     | 32K  | 32K  | 256K  | 6144K  | 3200    | VT-x  |
| AMD       | Athlon II X3 460               | 21426    | 3     | 64K  | 64K  | 512K  |        | 3400    | AMD-V |
| Intel     | Xeon L5408                     | 21412    | 4     | 32K  | 32K  | 6144K |        |         | VT-x  |
| Intel     | Xeon E5430                     | 21384    | 4     | 32K  | 32K  | 6144K |        | 2670    | VT-x  |
| Intel     | Xeon X3350                     | 21336    | 4     | 32K  | 32K  | 6144K |        | 2670    | VT-x  |
| Intel     | Xeon L5430                     | 21332    | 4     | 32K  | 32K  | 6144K |        | 2667    | VT-x  |
| Intel     | Xeon X3330                     | 21332    | 4     | 32K  | 32K  | 3072K |        | 2670    | VT-x  |
| Intel     | Core i7 M 620                  | 21332    | 4     | 32K  | 32K  | 256K  | 4096K  | 2667    | VT-x  |
| Intel     | Core i3 M 390                  | 21332    | 4     | 32K  | 32K  | 256K  | 3072K  | 2666    | VT-x  |
| Intel     | Core i7 M 620                  | 21332    | 4     | 32K  | 32K  | 256K  | 4096K  | 2667    | VT-x  |
| Intel     | Xeon X5355                     | 21328    | 4     | 32K  | 32K  | 4096K |        | 2664    | VT-x  |
| Intel     | Xeon X3350                     | 21328    | 4     | 32K  | 32K  | 6144K |        | 2667    | VT-x  |
| Intel     | Core2 Quad Q8300               | 21320    | 4     | 32K  | 32K  | 2048K |        | 2500    | VT-x  |
| Intel     | Xeon X5355                     | 21280    | 4     | 32K  | 32K  | 4096K |        | 2667    | VT-x  |
| Intel     | Core i5 M 580                  | 21280    | 4     | 32K  | 32K  | 256K  | 3072K  | 2667    | VT-x  |
| AMD       | Athlon II X3 445               | 21207    | 3     | 64K  | 64K  | 512K  |        | 3100    | AMD-V |
| AMD       | Phenom II X3 720               | 21000    | 3     | 64K  | 64K  | 512K  | 6144K  | 2900    | AMD-V |
| AMD       | Phenom 9850 Quad-Core          | 20996    | 4     | 64K  | 64K  | 512K  | 2048K  | 2500    | AMD-V |
| AMD       | Phenom II X4 810               | 20904    | 4     | 64K  | 64K  | 512K  | 4096K  | 2600    | AMD-V |
| AMD       | Phenom II X4 910               | 20896    | 4     | 64K  | 64K  | 512K  | 6144K  | 2600    | AMD-V |
| AMD       | Phenom II X4 910e              | 20896    | 4     | 64K  | 64K  | 512K  | 6144K  | 2600    | AMD-V |
| AMD       | Athlon X4 620                  | 20892    | 4     | 256K | 256K | 2M    |        | 2600    | AMD-V |
| AMD       | Athlon II X4 620e              | 20892    | 4     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| AMD       | Phenom II X4 10                | 20868    | 4     | 64K  | 64K  | 512K  | 6144K  |         | AMD-V |
| Intel     | Core i7-6500U                  | 20820    | 4     | 32K  | 32K  | 256K  | 4096K  | 3100    | VT-x  |
| Intel     | Core i3-10110U                 | 20808    | 4     | 32K  | 32K  | 256K  | 4096K  | 4100    | VT-x  |
| Intel     | Core i5-4278U                  | 20808    | 4     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| Intel     | Core i5-6440HQ                 | 20808    | 4     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| Intel     | Core i5-4288U                  | 20804    | 4     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| AMD       | Ryzen 3 3250U with Radeon G... | 20800    | 4     | 32K  | 64K  | 512K  | 4096K  | 2600    | AMD-V |
| Intel     | Core i7-4510U                  | 20800    | 4     | 32K  | 32K  | 256K  | 4096K  | 3100    | VT-x  |
| Intel     | Core i3-10110U                 | 20796    | 4     | 64K  | 64K  | 512K  | 4M     | 4100    | VT-x  |
| Intel     | Core i7-6498DU                 | 20796    | 4     | 32K  | 32K  | 256K  | 4096K  | 3100    | VT-x  |
| Intel     | Core i5-10210Y                 | 20792    | 8     | 32K  | 32K  | 256K  | 6144K  | 4000    | VT-x  |
| Intel     | Core i5-3230M                  | 20776    | 4     | 32K  | 32K  | 256K  | 3072K  | 3200    | VT-x  |
| Intel     | Core i5-2540M                  | 20772    | 4     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| Intel     | Core i5-3320M                  | 20772    | 4     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| Intel     | Core i5-4300M                  | 20772    | 4     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| AMD       | A10-9630P RADEON R5, 10 COM... | 20768    | 4     | 32K  | 96K  | 1024K |        | 2600    | AMD-V |
| AMD       | Ryzen 3 3200U with Radeon V... | 20768    | 4     | 32K  | 64K  | 512K  | 4096K  | 2600    | AMD-V |
| Intel     | Core i5-4210M                  | 20768    | 4     | 32K  | 32K  | 256K  | 3072K  | 3200    | VT-x  |
| AMD       | Ryzen Embedded R1606G with ... | 20760    | 4     | 32K  | 64K  | 512K  | 4096K  | 2600    | AMD-V |
| Intel     | Core i7-5600U                  | 20760    | 4     | 32K  | 32K  | 256K  | 4096K  | 3200    | VT-x  |
| Intel     | Core i5-4310U                  | 20760    | 4     | 32K  | 32K  | 256K  | 3072K  | 3000    | VT-x  |
| Intel     | Core i3-2120T                  | 20752    | 4     | 32K  | 32K  | 256K  | 3072K  | 2600    | VT-x  |
| Intel     | Core i3-3130M                  | 20752    | 4     | 32K  | 32K  | 256K  | 3072K  | 2600    | VT-x  |
| Intel     | Core i7-3687U                  | 20752    | 4     | 32K  | 32K  | 256K  | 4096K  | 3300    | VT-x  |
| AMD       | Athlon II X3 450               | 20553    | 3     | 64K  | 64K  | 512K  |        | 3200    | AMD-V |
| AMD       | 10_05                          | 20541    | 3     | 192K | 192K | 1.5M  |        |         | AMD-V |
| Intel     | Core i5-8400T                  | 20448    | 6     | 32K  | 32K  | 256K  | 9216K  | 3300    | VT-x  |
| Intel     | Xeon Bronze 3104               | 20406    | 6     | 32K  | 32K  | 1024K | 8448K  | 1700    | VT-x  |
| Intel     | Xeon E5-2603 v4                | 20394    | 6     | 32K  | 32K  | 256K  | 15360K | 1700    | VT-x  |
| Intel     | Core i5 M 540                  | 20264    | 4     | 32K  | 32K  | 256K  | 3072K  | 2534    | VT-x  |
| Intel     | Core i5 M 540                  | 20220    | 4     | 32K  | 32K  | 256K  | 3072K  | 2534    | VT-x  |
| Intel     | Core2 Extreme Q9300            | 20216    | 4     | 32K  | 32K  | 6144K |        | 2535    | VT-x  |
| Intel     | Core i3 M 370                  | 20208    | 4     | 32K  | 32K  | 256K  | 3072K  | 2400    | VT-x  |
| Intel     | Core i5 M 450                  | 20208    | 4     | 32K  | 32K  | 256K  | 3072K  | 2400    | VT-x  |
| AMD       | Phenom II X4 905e              | 20088    | 4     | 64K  | 64K  | 512K  | 6144K  | 2500    | AMD-V |
| AMD       | Athlon II X4 615e              | 20088    | 4     | 64K  | 64K  | 512K  |        | 2500    | AMD-V |
| Intel     | Core i5-2400S                  | 20072    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Core i5-2405S                  | 20064    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Pentium Dual-Core E5700        | 20048    | 2     | 32K  | 32K  | 2048K |        | 3003    | VT-x  |
| Intel     | Xeon L5420                     | 20036    | 4     | 32K  | 32K  | 6144K |        | 2500    | VT-x  |
| Intel     | Core i5-2450M                  | 20032    | 4     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| Intel     | Core i5-2520M                  | 20024    | 4     | 32K  | 32K  | 256K  | 3072K  | 3200    | VT-x  |
| Intel     | Core i5-3210M                  | 20016    | 4     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| Intel     | Xeon E5-2609 v2                | 20016    | 4     | 32K  | 32K  | 256K  | 10240K | 2500    | VT-x  |
| AMD       | Phenom II X4 905e              | 20008    | 4     | 64K  | 64K  | 512K  | 6144K  | 2500    | AMD-V |
| Intel     | Xeon L5420                     | 20008    | 4     | 32K  | 32K  | 6144K |        | 2500    | VT-x  |
| Intel     | Core i3-3120M                  | 20008    | 4     | 32K  | 32K  | 256K  | 3072K  | 2500    | VT-x  |
| Intel     | Core i5-7300HQ                 | 20004    | 4     | 32K  | 32K  | 256K  | 6144K  | 3500    | VT-x  |
| Intel     | Xeon E5420                     | 20004    | 4     | 32K  | 32K  | 6144K |        | 2500    | VT-x  |
| Intel     | Core i5-6300U                  | 20004    | 4     | 32K  | 32K  | 256K  | 3072K  | 3000    | VT-x  |
| Intel     | Core i5-6500T                  | 20004    | 4     | 32K  | 32K  | 256K  | 6144K  | 3100    | VT-x  |
| AMD       | Phenom 9850B Quad-Core         | 20000    | 4     | 64K  | 64K  | 512K  | 2048K  |         | AMD-V |
| Intel     | Xeon E5420                     | 20000    | 4     | 32K  | 32K  | 6144K |        | 2500    | VT-x  |
| AMD       | A8-3820 APU with Radeon HD ... | 19996    | 4     | 64K  | 64K  | 1024K |        | 2500    | AMD-V |
| Intel     | Core i7-7660U                  | 19996    | 4     | 32K  | 32K  | 256K  | 4096K  | 4000    | VT-x  |
| Intel     | Xeon X3320                     | 19996    | 4     | 32K  | 32K  | 3072K |        |         | VT-x  |
| Intel     | Xeon X3320                     | 19996    | 4     | 32K  | 32K  | 3072K |        | 2497    | VT-x  |
| Intel     | Core i5-4690T                  | 19992    | 4     | 128K | 128K | 1M    | 6M     | 3500    | VT-x  |
| Intel     | Core i7-3537U                  | 19976    | 4     | 32K  | 32K  | 256K  | 4096K  | 3100    | VT-x  |
| AMD       | A10-9620P RADEON R5, 10 COM... | 19972    | 4     | 32K  | 96K  | 1024K |        | 2500    | AMD-V |
| AMD       | A10-5750M APU with Radeon H... | 19972    | 4     | 16K  | 64K  | 2048K |        | 2500    | AMD-V |
| AMD       | Ryzen 3 2200U with Radeon V... | 19972    | 4     | 32K  | 64K  | 512K  | 4096K  | 2500    | AMD-V |
| Intel     | Core i5-4200M                  | 19972    | 4     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| Intel     | Core i5-4300U                  | 19972    | 4     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| AMD       | A12-9700P RADEON R7, 10 COM... | 19968    | 4     | 32K  | 96K  | 1024K |        | 2500    | AMD-V |
| AMD       | A10-5757M APU with Radeon H... | 19968    | 4     | 16K  | 64K  | 2048K |        | 2500    | AMD-V |
| AMD       | A10-7400P Radeon R6, 10 Com... | 19968    | 4     | 16K  | 96K  | 2048K |        | 2500    | AMD-V |
| AMD       | PRO A10-9700B R7, 10 COMPUT... | 19960    | 4     | 32K  | 96K  | 1024K |        | 2500    | AMD-V |
| AMD       | PRO A12-8830B R7, 10 COMPUT... | 19960    | 4     | 64K  | 192K | 2M    |        | 2500    | AMD-V |
| AMD       | A10-6700T APU with Radeon H... | 19960    | 4     | 16K  | 64K  | 2048K |        | 2500    | AMD-V |
| Intel     | Core i7-3667U                  | 19960    | 4     | 32K  | 32K  | 256K  | 4096K  | 3200    | VT-x  |
| Intel     | Core i3-4100M                  | 19960    | 4     | 32K  | 32K  | 256K  | 3072K  | 2500    | VT-x  |
| Intel     | Core i3-5157U                  | 19960    | 4     | 32K  | 32K  | 256K  | 3072K  | 2400    | VT-x  |
| Intel     | Core i3-2100T                  | 19952    | 4     | 64K  | 64K  | 512K  | 3M     | 2500    | VT-x  |
| Intel     | Xeon X5472                     | 19944    | 4     | 32K  | 32K  | 6144K |        | 3000    | VT-x  |
| AMD       | Phenom II X3 B75               | 19761    | 3     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| Intel     | Pentium J2900                  | 19332    | 4     | 24K  | 32K  | 1024K |        | 2665    | VT-x  |
| AMD       | Phenom 9750 Quad-Core          | 19324    | 4     | 64K  | 64K  | 512K  | 2048K  | 2400    | AMD-V |
| Intel     | Pentium J2850                  | 19324    | 4     | 24K  | 32K  | 1024K |        | 2415    | VT-x  |
| AMD       | Phenom 9600 Quad-Core          | 19316    | 4     | 64K  | 64K  | 512K  | 2048K  | 2300    | AMD-V |
| AMD       | Athlon X3 450                  | 19287    | 3     | 64K  | 64K  | 512K  |        | 3200    | AMD-V |
| Intel     | Xeon E5-2609 0                 | 19284    | 4     | 32K  | 32K  | 256K  | 10240K | 2400    | VT-x  |
| Intel     | Xeon X3430                     | 19272    | 4     | 32K  | 32K  | 256K  | 8192K  | 2401    | VT-x  |
| Intel     | Core i3-7100U                  | 19216    | 4     | 32K  | 32K  | 256K  | 3072K  | 2400    | VT-x  |
| Intel     | Core i5-2430M                  | 19216    | 4     | 32K  | 32K  | 256K  | 3072K  | 3000    | VT-x  |
| Intel     | Core i5-6200U                  | 19216    | 4     | 32K  | 32K  | 256K  | 3072K  | 2800    | VT-x  |
| Intel     | Core i5-4258U                  | 19208    | 4     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| Intel     | Core i7-7560U                  | 19204    | 4     | 32K  | 32K  | 256K  | 4096K  | 3800    | VT-x  |
| Intel     | Core i5-7400T                  | 19204    | 4     | 32K  | 32K  | 256K  | 6144K  | 3000    | VT-x  |
| Intel     | Core i5 M 520                  | 19204    | 4     | 32K  | 32K  | 256K  | 3072K  | 2400    | VT-x  |
| Intel     | Core i7-5500U                  | 19204    | 4     | 32K  | 32K  | 256K  | 4096K  | 3000    | VT-x  |
| Intel     | Xeon E5-2407 v2                | 19204    | 4     | 32K  | 32K  | 256K  | 10240K | 2400    | VT-x  |
| Intel     | Core i5-4210U                  | 19204    | 4     | 32K  | 32K  | 256K  | 3072K  | 2700    | VT-x  |
| Intel     | Core i5-6198DU                 | 19204    | 4     | 32K  | 32K  | 256K  | 3072K  | 2800    | VT-x  |
| AMD       | Athlon II X4 610e              | 19200    | 4     | 64K  | 64K  | 512K  |        | 2400    | AMD-V |
| Intel     | Pentium 6405U                  | 19200    | 4     | 64K  | 64K  | 512K  | 2M     | 2400    | VT-x  |
| Intel     | Core i5 M 520                  | 19200    | 4     | 32K  | 32K  | 256K  | 3072K  | 2400    | VT-x  |
| Intel     | Atom C2550                     | 19200    | 4     | 96K  | 128K | 2M    |        | 2401    | VT-x  |
| Intel     | Atom C2558                     | 19200    | 4     | 96K  | 128K | 2M    |        | 2400    | VT-x  |
| Intel     | Core i3-6157U                  | 19200    | 4     | 32K  | 32K  | 256K  | 3072K  | 2400    | VT-x  |
| Intel     | Core i3-2370M                  | 19196    | 4     | 32K  | 32K  | 256K  | 3072K  | 2400    | VT-x  |
| Intel     | Core i7-3517U                  | 19184    | 4     | 32K  | 32K  | 256K  | 4096K  | 3000    | VT-x  |
| Intel     | Core i3-3110M                  | 19180    | 4     | 32K  | 32K  | 256K  | 3072K  | 2400    | VT-x  |
| Intel     | Core i3-4000M                  | 19176    | 4     | 32K  | 32K  | 256K  | 3072K  | 2400    | VT-x  |
| AMD       | A10-9600P RADEON R5, 10 COM... | 19172    | 4     | 32K  | 96K  | 1024K |        | 2400    | AMD-V |
| AMD       | Athlon 300U with Radeon Veg... | 19172    | 4     | 32K  | 64K  | 512K  | 4096K  | 2400    | AMD-V |
| AMD       | Athlon Gold 3150U with Rade... | 19172    | 4     | 32K  | 64K  | 512K  | 4096K  | 2400    | AMD-V |
| Intel     | Core i7-4500U                  | 19172    | 4     | 32K  | 32K  | 256K  | 4096K  | 3000    | VT-x  |
| AMD       | A8-3800 APU with Radeon HD ... | 19164    | 4     | 64K  | 64K  | 1024K |        | 2400    | AMD-V |
| AMD       | PRO A10-8730B R5, 10 COMPUT... | 19164    | 4     | 32K  | 96K  | 1024K |        | 2400    | AMD-V |
| Intel     | Core i5-2435M                  | 19164    | 4     | 32K  | 32K  | 256K  | 3072K  | 3000    | VT-x  |
| Intel     | Core i5-3437U                  | 19164    | 4     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| AMD       | Ryzen Embedded R1505G with ... | 19160    | 4     | 32K  | 64K  | 512K  | 4096K  | 2400    | AMD-V |
| Intel     | Core i3-4330TE                 | 19152    | 4     | 32K  | 32K  | 256K  | 4096K  | 2400    | VT-x  |
| AMD       | Phenom II X940 Quad-Core       | 19148    | 4     | 64K  | 64K  | 512K  |        | 2400    | AMD-V |
| Intel     | Core i5-1035G1                 | 19048    | 8     | 192K | 128K | 2M    | 6M     | 3600    | VT-x  |
| Intel     | Core i7-1060NG7                | 19040    | 8     | 48K  | 32K  | 512K  | 8192K  | 3800    | VT-x  |
| Intel     | Core i7-1185G7E                | 19040    | 8     | 192K | 128K | 5M    | 12M    | 4400    | VT-x  |
| Intel     | Xeon L5410                     | 18724    | 4     | 32K  | 32K  | 6144K |        | 2331    | VT-x  |
| Intel     | Core i3 M 350                  | 18720    | 4     | 32K  | 32K  | 256K  | 3072K  | 2266    | VT-x  |
| AMD       | Athlon 5350 APU with Radeon R3 | 18712    | 4     | 32K  | 32K  | 2048K |        | 2100    | AMD-V |
| Intel     | Xeon E5410                     | 18664    | 4     | 32K  | 32K  | 6144K |        | 2333    | VT-x  |
| Intel     | Core i5 M 430                  | 18632    | 4     | 32K  | 32K  | 256K  | 3072K  | 2267    | VT-x  |
| Intel     | Xeon E5345                     | 18620    | 4     | 32K  | 32K  | 4096K |        | 2333    | VT-x  |
| Intel     | Xeon E5345                     | 18620    | 4     | 32K  | 32K  | 4096K |        | 2333    | VT-x  |
| AMD       | Quad-Core Opteron 2356         | 18496    | 4     | 64K  | 64K  | 512K  | 2048K  | 2300    | AMD-V |
| AMD       | Phenom 9650 Quad-Core          | 18488    | 4     | 64K  | 64K  | 512K  | 2048K  | 2300    | AMD-V |
| AMD       | Phenom X4 Quad-Core GP-9600    | 18484    | 4     | 64K  | 64K  | 512K  | 2048K  | 2300    | AMD-V |
| AMD       | Phenom 9600B Quad-Core         | 18484    | 4     | 64K  | 64K  | 512K  | 2048K  | 2300    | AMD-V |
| AMD       | Quad-Core Opteron 2376         | 18484    | 4     | 64K  | 64K  | 512K  | 6144K  | 2300    | AMD-V |
| AMD       | Quad-Core Opteron 1356         | 18480    | 4     | 64K  | 64K  | 512K  | 2048K  | 2300    | AMD-V |
| AMD       | Athlon II X4 605e              | 18480    | 4     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| Intel     | Core i3-6100U                  | 18472    | 4     | 32K  | 32K  | 256K  | 3072K  | 2301    | VT-x  |
| Intel     | Core i3-7020U                  | 18436    | 4     | 32K  | 32K  | 256K  | 3072K  | 2300    | VT-x  |
| Intel     | Pentium 4417U                  | 18436    | 4     | 32K  | 32K  | 256K  | 2048K  | 2300    | VT-x  |
| Intel     | Core i3-8145U                  | 18436    | 4     | 32K  | 32K  | 256K  | 4096K  | 3900    | VT-x  |
| Intel     | Pentium 5405U                  | 18436    | 4     | 32K  | 32K  | 256K  | 2048K  | 2300    | VT-x  |
| Intel     | Core i3-7020U                  | 18436    | 4     | 32K  | 32K  | 256K  | 3072K  | 2300    | VT-x  |
| Intel     | Pentium 4415U                  | 18436    | 4     | 32K  | 32K  | 256K  | 2048K  | 2300    | VT-x  |
| Intel     | Core i5-6300HQ                 | 18436    | 4     | 32K  | 32K  | 256K  | 6144K  | 3200    | VT-x  |
| Intel     | Pentium 5405U                  | 18432    | 4     | 32K  | 32K  | 256K  | 2048K  | 2300    | VT-x  |
| Intel     | Core i3-8145U                  | 18432    | 4     | 32K  | 32K  | 256K  | 4096K  | 3900    | VT-x  |
| Intel     | Core i5-7360U                  | 18432    | 4     | 32K  | 32K  | 256K  | 4096K  | 3600    | VT-x  |
| Intel     | Core i5-2410M                  | 18408    | 4     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| Intel     | Core i7-4650U                  | 18404    | 4     | 32K  | 32K  | 256K  | 4096K  | 3300    | VT-x  |
| Intel     | Core i5-6500TE                 | 18404    | 4     | 128K | 128K | 1M    | 6M     | 3300    | VT-x  |
| Intel     | Core i5-4200U                  | 18400    | 4     | 32K  | 32K  | 256K  | 3072K  | 2600    | VT-x  |
| AMD       | Athlon II X4 605e              | 18396    | 4     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| Intel     | Core i3-8145UC                 | 18396    | 4     | 64K  | 64K  | 512K  | 4M     | 3900    | VT-x  |
| Intel     | Core i5-4670T                  | 18396    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Core i3-2348M                  | 18376    | 4     | 32K  | 32K  | 256K  | 3072K  | 2300    | VT-x  |
| Intel     | Core i3-2350M                  | 18376    | 4     | 32K  | 32K  | 256K  | 3072K  | 2300    | VT-x  |
| AMD       | A10-4600M APU with Radeon H... | 18372    | 4     | 16K  | 64K  | 2048K |        | 2300    | AMD-V |
| Intel     | Core i5-5300U                  | 18372    | 4     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| AMD       | R-464L APU with Radeon HD G... | 18364    | 4     | 32K  | 128K | 4M    |        | 2300    | AMD-V |
| Intel     | Core i5-2415M                  | 18364    | 4     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| Intel     | Core i5-3427U                  | 18364    | 4     | 32K  | 32K  | 256K  | 3072K  | 2800    | VT-x  |
| Intel     | Core i5-2500T                  | 18356    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Core i5-3570T                  | 18356    | 4     | 32K  | 32K  | 256K  | 6144K  | 3300    | VT-x  |
| Intel     | Xeon E3-1220L V2               | 18356    | 4     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| Intel     | Xeon X3363                     | 18132    | 4     | 32K  | 32K  | 6144K |        | 2830    | VT-x  |
| Intel     | Core i3 M 350                  | 18132    | 4     | 32K  | 32K  | 256K  | 3072K  | 2266    | VT-x  |
| Intel     | Core2 Quad Q9100               | 18088    | 4     | 32K  | 32K  | 6144K |        | 2267    | VT-x  |
| AMD       | Athlon II X3 440               | 18087    | 3     | 64K  | 64K  | 512K  |        | 3000    | AMD-V |
| AMD       | Athlon II X3 440               | 18087    | 3     | 64K  | 64K  | 512K  |        | 3000    | AMD-V |
| AMD       | Phenom II X3 740               | 18084    | 3     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| AMD       | Phenom II X3 B75               | 17955    | 3     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| Intel     | Core i5-1030NG7                | 17816    | 8     | 48K  | 32K  | 512K  | 6144K  | 3500    | VT-x  |
| Intel     | Core2 Duo E8500                | 17730    | 2     | 32K  | 32K  | 6144K |        | 3167    | VT-x  |
| AMD       | Phenom 9550 Quad-Core          | 17692    | 4     | 64K  | 64K  | 512K  | 2048K  | 2200    | AMD-V |
| AMD       | Quad-Core Opteron 2354         | 17692    | 4     | 64K  | 64K  | 512K  | 2048K  |         | AMD-V |
| AMD       | Phenom 9500 Quad-Core          | 17684    | 4     | 64K  | 64K  | 512K  | 2048K  | 2200    | AMD-V |
| AMD       | Athlon II X4 600e              | 17680    | 4     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| Intel     | Core i5-6400T                  | 17680    | 4     | 32K  | 32K  | 256K  | 6144K  | 2800    | VT-x  |
| Intel     | Core i3-8130U                  | 17668    | 4     | 32K  | 32K  | 256K  | 4096K  | 3400    | VT-x  |
| Intel     | Core i7-6650U                  | 17668    | 4     | 32K  | 32K  | 256K  | 4096K  | 3400    | VT-x  |
| Intel     | Core i3-8121U                  | 17664    | 4     | 32K  | 32K  | 256K  | 4096K  | 3200    | VT-x  |
| Intel     | Core i5-7260U                  | 17664    | 4     | 32K  | 32K  | 256K  | 4096K  | 3400    | VT-x  |
| Intel     | Core i7-6560U                  | 17664    | 4     | 32K  | 32K  | 256K  | 4096K  | 3200    | VT-x  |
| Intel     | Core i5-5200U                  | 17636    | 4     | 32K  | 32K  | 256K  | 3072K  | 2700    | VT-x  |
| Intel     | Core i3-2330M                  | 17616    | 4     | 32K  | 32K  | 256K  | 3072K  | 2200    | VT-x  |
| Intel     | Core i3-5020U                  | 17604    | 4     | 32K  | 32K  | 256K  | 3072K  | 2200    | VT-x  |
| Intel     | Atom C3558                     | 17604    | 4     | 96K  | 128K | 8M    |        | 2200    | VT-x  |
| AMD       | Quad-Core Opteron 2374 HE      | 17600    | 4     | 64K  | 64K  | 512K  | 6144K  | 2200    | AMD-V |
| Intel     | Xeon E5-2407 0                 | 17600    | 4     | 32K  | 32K  | 256K  | 10240K | 2200    | VT-x  |
| Intel     | Pentium D1508                  | 17600    | 4     | 32K  | 32K  | 256K  | 3072K  | 2600    | VT-x  |
| AMD       | A6-6420K APU with Radeon HD... | 17598    | 2     | 16K  | 64K  | 1024K |        | 4400    | AMD-V |
| Intel     | Core i7-5650U                  | 17596    | 4     | 64K  | 64K  | 512K  | 4M     | 3200    | VT-x  |
| AMD       | A8-7410 APU with AMD Radeon... | 17584    | 4     | 32K  | 32K  | 2048K |        | 2200    | AMD-V |
| Intel     | Core i3-2328M                  | 17576    | 4     | 32K  | 32K  | 256K  | 3072K  | 2200    | VT-x  |
| AMD       | A6-3620 APU with Radeon HD ... | 17572    | 4     | 64K  | 64K  | 1024K |        | 2200    | AMD-V |
| AMD       | Phenom II N970 Quad-Core       | 17564    | 4     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| Intel     | Core i7-3517UE                 | 17564    | 4     | 64K  | 64K  | 512K  | 4M     | 2800    | VT-x  |
| Intel     | Core i7-2655LE                 | 17560    | 4     | 32K  | 32K  | 256K  | 4096K  | 2900    | VT-x  |
| Intel     | Xeon E31220L                   | 17560    | 4     | 32K  | 32K  | 256K  | 3072K  | 3400    | VT-x  |
| Intel     | Core i5-5200DU                 | 17556    | 4     | 32K  | 32K  | 256K  | 3072K  | 2700    | VT-x  |
| Intel     | Core i7-5###U                  | 17556    | 4     | 64K  | 64K  | 512K  | 4M     | 2700    | VT-x  |
| Intel     | Pentium Dual-Core E5800        | 17486    | 2     | 32K  | 32K  | 2048K |        | 3203    | VT-x  |
| AMD       | Athlon II X3 435               | 17478    | 3     | 64K  | 64K  | 512K  |        | 2900    | AMD-V |
| AMD       | Athlon II X3 435               | 17478    | 3     | 64K  | 64K  | 512K  |        | 2900    | AMD-V |
| AMD       | Phenom II N950 Quad-Core       | 17424    | 4     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| Intel     | Pentium N3540                  | 17364    | 4     | 24K  | 32K  | 1024K |        | 2665    | VT-x  |
| Intel     | Pentium N3520                  | 17360    | 4     | 24K  | 32K  | 1024K |        | 2415    | VT-x  |
| Intel     | Pentium N3530                  | 17360    | 4     | 24K  | 32K  | 1024K |        | 2582    | VT-x  |
| AMD       | A6-6400K APU with Radeon HD... | 17318    | 2     | 16K  | 64K  | 1024K |        | 4100    | AMD-V |
| AMD       | A6-5400K APU with Radeon HD... | 17286    | 2     | 16K  | 64K  | 1024K |        | 4300    | AMD-V |
| Intel     | Atom D2700                     | 17196    | 4     | 24K  | 32K  | 512K  |        |         |       |
| Intel     | Atom 330                       | 17104    | 4     | 24K  | 32K  | 512K  |        | 1599    |       |
| Intel     | Xeon E5506                     | 17068    | 4     | 32K  | 32K  | 256K  | 4096K  | 2128    | VT-x  |
| Intel     | Xeon E5606                     | 17068    | 4     | 32K  | 32K  | 256K  | 8192K  | 2133    | VT-x  |
| Intel     | Xeon X3210                     | 17064    | 4     | 32K  | 32K  | 4096K |        | 2133    | VT-x  |
| AMD       | A4-6300 APU with Radeon HD ... | 17054    | 2     | 16K  | 64K  | 1024K |        | 3700    | AMD-V |
| Intel     | Core i7 L 640                  | 17028    | 4     | 32K  | 32K  | 256K  | 4096K  | 2134    | VT-x  |
| Intel     | Core i7 L 640                  | 17028    | 4     | 32K  | 32K  | 256K  | 4096K  | 2134    | VT-x  |
| Intel     | Pentium 4405U                  | 16900    | 4     | 32K  | 32K  | 256K  | 2048K  | 2100    | VT-x  |
| AMD       | Quad-Core Opteron 2352         | 16876    | 4     | 64K  | 64K  | 512K  | 2048K  | 2100    | AMD-V |
| AMD       | FX-8800P Radeon R7, 12 Comp... | 16804    | 4     | 32K  | 96K  | 1024K |        | 2100    | AMD-V |
| Intel     | Core i3-5010U                  | 16804    | 4     | 32K  | 32K  | 256K  | 3072K  | 2100    | VT-x  |
| Intel     | Core2 Duo E7400                | 16798    | 2     | 32K  | 32K  | 3072K |        | 3400    | VT-x  |
| Intel     | Core i3-2310M                  | 16796    | 4     | 32K  | 32K  | 256K  | 3072K  | 2100    | VT-x  |
| AMD       | A8-5550M APU with Radeon HD... | 16776    | 4     | 16K  | 64K  | 2048K |        | 2100    | AMD-V |
| AMD       | FX-7500 Radeon R7, 10 Compu... | 16776    | 4     | 16K  | 96K  | 2048K |        | 2100    | AMD-V |
| AMD       | A6-3600 APU with Radeon HD ... | 16772    | 4     | 64K  | 64K  | 1024K |        | 2100    | AMD-V |
| AMD       | A10-5745M APU with Radeon H... | 16772    | 4     | 16K  | 64K  | 2048K |        | 2100    | AMD-V |
| AMD       | Ryzen 3 3300U with Radeon V... | 16772    | 4     | 32K  | 64K  | 512K  | 4096K  | 2100    | AMD-V |
| AMD       | A8-5557M APU with Radeon HD... | 16768    | 4     | 16K  | 64K  | 2048K |        | 2100    | AMD-V |
| AMD       | A10 PRO-7350B R6, 10 Comput... | 16768    | 4     | 16K  | 96K  | 2048K |        | 2100    | AMD-V |
| AMD       | Embedded R-Series RX-421ND     | 16768    | 4     | 128K | 256K | 4M    |        | 2100    | AMD-V |
| AMD       | Opteron X3421 APU              | 16768    | 4     | 64K  | 192K | 2M    |        | 2100    | AMD-V |
| AMD       | PRO A12-8800B R7, 12 Comput... | 16768    | 4     | 32K  | 96K  | 1024K |        | 2100    | AMD-V |
| Intel     | Core i3-2312M                  | 16768    | 4     | 64K  | 64K  | 512K  | 3M     | 2100    | VT-x  |
| Intel     | Core i3-5015U                  | 16768    | 4     | 32K  | 32K  | 256K  | 3072K  | 2100    | VT-x  |
| AMD       | Embedded R-Series RX-421BD ... | 16764    | 4     | 32K  | 96K  | 1024K |        | 2100    | AMD-V |
| Intel     | Core i7-4550U                  | 16760    | 4     | 32K  | 32K  | 256K  | 4096K  | 3000    | VT-x  |
| Intel     | Celeron E3300                  | 16700    | 2     | 32K  | 32K  | 1024K |        | 3500    | VT-x  |
| AMD       | Athlon II X3 425               | 16272    | 3     | 64K  | 64K  | 512K  |        | 2700    | AMD-V |
| AMD       | Athlon II X3 425e              | 16272    | 3     | 64K  | 64K  | 512K  |        | 2700    | AMD-V |
| AMD       | A4-6320 APU with Radeon HD ... | 16244    | 2     | 16K  | 64K  | 1024K |        | 3800    | AMD-V |
| AMD       | Quad-Core Opteron 2350         | 16080    | 4     | 64K  | 64K  | 512K  | 2048K  | 2000    | AMD-V |
| Intel     | Core i3-5005U                  | 16024    | 4     | 32K  | 32K  | 256K  | 3072K  | 2000    | VT-x  |
| AMD       | A6-5200 APU with Radeon HD ... | 16004    | 4     | 32K  | 32K  | 2048K |        | 2000    | AMD-V |
| Intel     | Core2 Quad Q9000               | 16004    | 4     | 32K  | 32K  | 3072K |        | 2001    | VT-x  |
| Intel     | Celeron J1900                  | 16004    | 4     | 24K  | 32K  | 1024K |        | 2415    | VT-x  |
| Intel     | Core i5-4260U                  | 16004    | 4     | 32K  | 32K  | 256K  | 3072K  | 2700    | VT-x  |
| Intel     | Core i3-6006U                  | 16004    | 4     | 32K  | 32K  | 256K  | 3072K  | 2000    | VT-x  |
| AMD       | A4-3300 APU with Radeon HD ... | 16000    | 2     | 64K  | 64K  | 512K  |        | 4000    | AMD-V |
| Intel     | Xeon E5335                     | 16000    | 4     | 32K  | 32K  | 4096K |        |         | VT-x  |
| Intel     | Xeon E5405                     | 16000    | 4     | 32K  | 32K  | 6144K |        |         | VT-x  |
| Intel     | Xeon E5504                     | 16000    | 4     | 32K  | 32K  | 256K  | 4096K  | 2000    | VT-x  |
| Intel     | Celeron J1850                  | 16000    | 4     | 24K  | 32K  | 1024K |        | 1999    | VT-x  |
| Intel     | Celeron J1900                  | 16000    | 4     | 24K  | 32K  | 1024K |        | 2415    | VT-x  |
| Intel     | Pentium N3510                  | 16000    | 4     | 24K  | 32K  | 1024K |        | 1999    | VT-x  |
| Intel     | Celeron J1900                  | 16000    | 4     | 24K  | 32K  | 1024K |        | 2415    | VT-x  |
| Intel     | Xeon E5405                     | 15996    | 4     | 32K  | 32K  | 6144K |        |         | VT-x  |
| Intel     | Core i7 L 620                  | 15996    | 4     | 32K  | 32K  | 256K  | 4096K  | 2000    | VT-x  |
| Intel     | Core i5-4590T                  | 15996    | 4     | 32K  | 32K  | 256K  | 6144K  | 3000    | VT-x  |
| Intel     | Core i5-6360U                  | 15996    | 4     | 32K  | 32K  | 256K  | 4096K  | 3100    | VT-x  |
| Intel     | Pentium Dual-Core E6700        | 15994    | 2     | 32K  | 32K  | 2048K |        | 3203    | VT-x  |
| Intel     | Xeon L5335                     | 15984    | 4     | 32K  | 32K  | 4096K |        |         | VT-x  |
| Intel     | Celeron J4125                  | 15980    | 4     | 96K  | 128K | 4M    |        | 2700    | VT-x  |
| AMD       | A10-4655M APU with Radeon H... | 15976    | 4     | 16K  | 64K  | 2048K |        | 2000    | AMD-V |
| AMD       | A6-7310 APU with AMD Radeon... | 15976    | 4     | 32K  | 32K  | 2048K |        | 2000    | AMD-V |
| AMD       | A8-6410 APU with AMD Radeon... | 15976    | 4     | 32K  | 32K  | 2048K |        | 2000    | AMD-V |
| AMD       | Ryzen 3 2300U with Radeon V... | 15976    | 4     | 32K  | 64K  | 512K  | 4096K  | 2000    | AMD-V |
| AMD       | A6-5400K APU with Radeon HD... | 15972    | 2     | 16K  | 64K  | 1024K |        | 4000    | AMD-V |
| Intel     | Pentium Silver J5040           | 15972    | 4     | 96K  | 128K | 4M    |        | 3200    | VT-x  |
| Intel     | Pentium Gold 7505              | 15972    | 4     | 48K  | 32K  | 1280K | 4096K  | 3500    | VT-x  |
| AMD       | Athlon X2 370K Dual Core       | 15970    | 2     | 16K  | 64K  | 1M    |        | 4000    | AMD-V |
| AMD       | A10 Extreme Edition Radeon ... | 15968    | 4     | 32K  | 96K  | 1024K |        | 2000    | AMD-V |
| AMD       | Embedded G-Series GX-420GI ... | 15968    | 4     | 32K  | 96K  | 1024K |        | 2000    | AMD-V |
| AMD       | GX-420CA SOC with Radeon HD... | 15968    | 4     | 32K  | 32K  | 2048K |        | 2000    | AMD-V |
| AMD       | 410 APU 410 APU with Radeon... | 15968    | 4     | 32K  | 32K  | 2048K |        | 2000    | AMD-V |
| AMD       | A4-6250J APU with AMD Radeo... | 15968    | 4     | 128K | 128K | 2M    |        | 2000    | AMD-V |
| AMD       | GX-420MC SOC                   | 15968    | 4     | 128K | 128K | 2M    |        | 2000    | AMD-V |
| AMD       | HP Hexa-Core                   | 15968    | 4     | 32K  | 32K  | 2048K |        | 2000    | AMD-V |
| AMD       | PRO A4-3350B APU with Radeo... | 15968    | 4     | 32K  | 32K  | 2048K |        | 2000    | AMD-V |
| AMD       | Ryzen 3 PRO 2300U w_ Radeon... | 15968    | 4     | 128K | 256K | 2M    | 4M     | 2000    | AMD-V |
| AMD       | Phenom II N930 Quad-Core       | 15964    | 4     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| Intel     | Core i7 L 620                  | 15960    | 4     | 32K  | 32K  | 256K  | 4096K  | 2000    | VT-x  |
| Intel     | Core i7-5550U                  | 15960    | 4     | 32K  | 32K  | 256K  | 4096K  | 3000    | VT-x  |
| Intel     | Core i3-4158U                  | 15960    | 4     | 32K  | 32K  | 256K  | 3072K  | 2000    | VT-x  |
| Intel     | Core i5-4350U                  | 15960    | 4     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| AMD       | Phenom 9350e Quad-Core         | 15956    | 4     | 64K  | 64K  | 512K  | 2048K  |         | AMD-V |
| Intel     | Xeon E3-1235L v5               | 15936    | 4     | 32K  | 32K  | 256K  | 8192K  | 3000    | VT-x  |
| AMD       | Phenom II X2 555               | 15908    | 2     | 64K  | 64K  | 512K  | 6144K  | 3700    | AMD-V |
| AMD       | Phenom II X3 710               | 15681    | 3     | 64K  | 64K  | 512K  | 6144K  | 2600    | AMD-V |
| AMD       | Athlon II X3 420e              | 15669    | 3     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| AMD       | A6-7400K Radeon R5, 6 Compu... | 15572    | 2     | 16K  | 96K  | 1024K |        | 3900    | AMD-V |
| AMD       | A6-6400B APU with Radeon HD... | 15570    | 2     | 16K  | 64K  | 1M    |        | 3900    | AMD-V |
| Intel     | Pentium D                      | 15434    | 2     | 16K  |      | 2048K |        | 3403    |       |
| Intel     | Atom E3845                     | 15336    | 4     | 96K  | 128K | 2M    |        | 1915    | VT-x  |
| Intel     | Atom E3845                     | 15332    | 4     | 24K  | 32K  | 1024K |        | 1915    | VT-x  |
| AMD       | A4-7300 APU with Radeon HD ... | 15276    | 2     | 16K  | 64K  | 1024K |        | 3800    | AMD-V |
| Intel     | Atom D510                      | 15212    | 4     | 24K  | 32K  | 512K  |        | 1666    |       |
| Intel     | Core i3-4030U                  | 15204    | 4     | 32K  | 32K  | 256K  | 3072K  | 1900    | VT-x  |
| Intel     | Core i5-4250U                  | 15204    | 4     | 32K  | 32K  | 256K  | 3072K  | 2600    | VT-x  |
| Intel     | Xeon                           | 15200    | 2     | 16K  |      | 2048K |        |         |       |
| Intel     | Core i3-3227U                  | 15196    | 4     | 32K  | 32K  | 256K  | 3072K  | 1900    | VT-x  |
| Intel     | Pentium 3825U                  | 15196    | 4     | 32K  | 32K  | 256K  | 2048K  | 1900    | VT-x  |
| Intel     | Core2 Duo E7600                | 15178    | 2     | 32K  | 32K  | 3072K |        | 3067    | VT-x  |
| AMD       | A8-3530MX APU with Radeon H... | 15176    | 4     | 64K  | 64K  | 1024K |        | 1900    | AMD-V |
| AMD       | A8-4500M APU with Radeon HD... | 15176    | 4     | 16K  | 64K  | 2048K |        | 1900    | AMD-V |
| AMD       | A10-7300 Radeon R6, 10 Comp... | 15176    | 4     | 16K  | 64K  | 2048K |        | 1900    | AMD-V |
| AMD       | A4 PRO-7300B APU with Radeo... | 15172    | 2     | 16K  | 64K  | 1024K |        | 3800    |       |
| AMD       | A8 PRO-7150B R5, 10 Compute... | 15172    | 4     | 16K  | 96K  | 2048K |        | 1900    | AMD-V |
| Intel     | Pentium 4                      | 15168    | 2     | 16K  |      | 2048K |        | 3403    |       |
| Intel     | Core i5-4460T                  | 15164    | 4     | 32K  | 32K  | 256K  | 6144K  | 2700    | VT-x  |
| Intel     | Core i3-4025U                  | 15164    | 4     | 32K  | 32K  | 256K  | 3072K  | 1800    | VT-x  |
| Intel     | Core i3-4110U                  | 15164    | 4     | 64K  | 64K  | 512K  | 3M     | 1800    | VT-x  |
| Intel     | Pentium 4                      | 15162    | 2     | 16K  |      | 1024K |        | 2800    |       |
| Intel     | Xeon                           | 15162    | 2     | 16K  |      | 2048K |        | 3800    |       |
| Intel     | Core2 Duo E8400                | 15090    | 2     | 32K  | 32K  | 6144K |        | 10336   | VT-x  |
| AMD       | Phenom 8850B Triple-Core       | 15066    | 3     | 192K | 192K | 1.5M  | 2M     | 2500    | AMD-V |
| AMD       | Phenom II X3 705e              | 15066    | 3     | 64K  | 64K  | 512K  | 6144K  | 2500    | AMD-V |
| Intel     | Atom D2550                     | 14936    | 4     | 24K  | 32K  | 512K  |        |         |       |
| Intel     | Atom N2800                     | 14932    | 4     | 24K  | 32K  | 512K  |        | 1862    |       |
| Intel     | Celeron N2920                  | 14932    | 4     | 24K  | 32K  | 1024K |        | 1999    | VT-x  |
| Intel     | Pentium Dual-Core E5500        | 14898    | 2     | 32K  | 32K  | 2048K |        | 2803    | VT-x  |
| Intel     | Xeon L5320                     | 14892    | 4     | 32K  | 32K  | 4096K |        |         | VT-x  |
| AMD       | A6-3500 APU with Radeon HD ... | 14832    | 3     | 64K  | 64K  | 1024K |        | 2400    | AMD-V |
| AMD       | Athlon II X2 270               | 14820    | 2     | 64K  | 64K  | 1024K |        | 3400    | AMD-V |
| AMD       | A4-6300B APU with Radeon HD... | 14776    | 2     | 16K  | 64K  | 1M    |        | 3700    | AMD-V |
| AMD       | A6-7470K Radeon R5, 6 Compu... | 14772    | 2     | 16K  | 96K  | 1024K |        | 3700    | AMD-V |
| Intel     | Pentium D                      | 14746    | 2     | 16K  |      | 1024K |        | 3200    |       |
| AMD       | Phenom II X2 B59               | 14736    | 2     | 64K  | 64K  | 512K  | 6144K  | 3400    | AMD-V |
| AMD       | Phenom II X2 565               | 14734    | 2     | 64K  | 64K  | 512K  | 6144K  | 3400    | AMD-V |
| Intel     | Pentium 4                      | 14706    | 2     | 16K  |      | 1024K |        |         |       |
| Intel     | Pentium Dual-Core E6600        | 14674    | 2     | 32K  | 32K  | 2048K |        | 3301    | VT-x  |
| Intel     | Celeron N2940                  | 14672    | 4     | 24K  | 32K  | 1024K |        | 2249    | VT-x  |
| Intel     | Core2 Duo E7500                | 14666    | 2     | 32K  | 32K  | 3072K |        | 7866    | VT-x  |
| Intel     | Celeron N2930                  | 14664    | 4     | 24K  | 32K  | 1024K |        | 2165    | VT-x  |
| AMD       | Athlon II X2 240               | 14560    | 2     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| Intel     | Celeron E3400                  | 14524    | 2     | 32K  | 32K  | 1024K |        | 2603    | VT-x  |
| Intel     | Pentium Dual-Core E5400        | 14518    | 2     | 32K  | 32K  | 2048K |        | 2700    | VT-x  |
| AMD       | Athlon II X2 280               | 14470    | 2     | 64K  | 64K  | 1024K |        | 3600    | AMD-V |
| Intel     | Pentium 4                      | 14468    | 2     | 16K  |      | 2048K |        | 3600    |       |
| AMD       | Phenom 8750 Triple-Core        | 14466    | 3     | 64K  | 64K  | 512K  | 2048K  | 2400    | AMD-V |
| AMD       | Phenom 9150e Quad-Core         | 14464    | 4     | 64K  | 64K  | 512K  | 2048K  | 1800    | AMD-V |
| AMD       | Phenom II X2 560               | 14464    | 2     | 64K  | 64K  | 512K  | 6144K  | 3600    | AMD-V |
| AMD       | Phenom II X3 700e              | 14463    | 3     | 64K  | 64K  | 512K  | 6144K  | 2400    | AMD-V |
| AMD       | Athlon II X2 255               | 14444    | 2     | 64K  | 64K  | 1024K |        | 3100    | AMD-V |
| Intel     | Pentium Dual-Core E6500        | 14432    | 2     | 32K  | 32K  | 2048K |        | 2936    | VT-x  |
| Intel     | Atom D525                      | 14432    | 4     | 24K  | 32K  | 512K  |        | 1800    |       |
| Intel     | Core i5-6260U                  | 14424    | 4     | 32K  | 32K  | 256K  | 4096K  | 2900    | VT-x  |
| Intel     | Xeon E5-2603 v2                | 14408    | 4     | 32K  | 32K  | 256K  | 10240K | 1800    | VT-x  |
| Intel     | Core i5-5350U                  | 14404    | 4     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| Intel     | Pentium G3470                  | 14402    | 2     | 32K  | 32K  | 256K  | 3072K  | 3600    | VT-x  |
| AMD       | Phenom 8750B Triple-Core       | 14400    | 3     | 64K  | 64K  | 512K  | 2048K  | 2400    | AMD-V |
| Intel     | Core i7-2677M                  | 14400    | 4     | 32K  | 32K  | 256K  | 4096K  | 2900    | VT-x  |
| Intel     | Pentium G4520                  | 14400    | 2     | 64K  | 64K  | 512K  | 3M     | 3600    | VT-x  |
| Intel     | Core2 Duo E6750                | 14398    | 2     | 32K  | 32K  | 4096K |        | 3200    | VT-x  |
| Intel     | Core2 Duo E6850                | 14398    | 2     | 32K  | 32K  | 4096K |        | 3003    | VT-x  |
| Intel     | Core2 Duo E8400                | 14398    | 2     | 32K  | 32K  | 6144K |        | 3600    | VT-x  |
| Intel     | Xeon E5-2403 0                 | 14396    | 4     | 32K  | 32K  | 256K  | 10240K | 1800    | VT-x  |
| Intel     | Xeon E5-2403 v2                | 14396    | 4     | 32K  | 32K  | 256K  | 10240K | 1800    | VT-x  |
| AMD       | Athlon II X2 220               | 14390    | 2     | 64K  | 64K  | 512K  |        | 2800    | AMD-V |
| Intel     | Core i3-3217U                  | 14388    | 4     | 32K  | 32K  | 256K  | 3072K  | 1800    | VT-x  |
| Intel     | Core i5-3337U                  | 14388    | 4     | 32K  | 32K  | 256K  | 3072K  | 2700    | VT-x  |
| Intel     | Pentium 4                      | 14384    | 2     | 16K  |      | 2048K |        | 3600    |       |
| AMD       | A4-6210 APU with AMD Radeon... | 14380    | 4     | 32K  | 32K  | 2048K |        | 1800    | AMD-V |
| AMD       | A8-3510MX APU with Radeon H... | 14376    | 4     | 64K  | 64K  | 1024K |        | 1800    | AMD-V |
| AMD       | A8-7100 Radeon R5, 8 Comput... | 14376    | 4     | 16K  | 64K  | 2048K |        | 1800    | AMD-V |
| AMD       | A10-8700P Radeon R6, 10 Com... | 14376    | 4     | 32K  | 96K  | 1024K |        | 1800    | AMD-V |
| AMD       | A4-7210 APU with AMD Radeon... | 14376    | 4     | 32K  | 32K  | 2048K |        | 1800    | AMD-V |
| AMD       | A6-6310 APU with AMD Radeon... | 14376    | 4     | 32K  | 32K  | 2048K |        | 1800    | AMD-V |
| AMD       | E2-7110 APU with AMD Radeon... | 14376    | 4     | 32K  | 32K  | 2048K |        | 1800    | AMD-V |
| AMD       | A6-5400B APU with Radeon HD... | 14374    | 2     | 16K  | 64K  | 1024K |        | 3600    | AMD-V |
| AMD       | PRO A10-8700B R6, 10 Comput... | 14372    | 4     | 32K  | 96K  | 1024K |        | 1800    | AMD-V |
| AMD       | 310 APU 310 APU with Radeon... | 14372    | 4     | 32K  | 32K  | 2048K |        | 1800    | AMD-V |
| AMD       | Phenom II P960 Quad-Core       | 14368    | 4     | 64K  | 64K  | 512K  |        | 1800    | AMD-V |
| Intel     | Pentium 4                      | 14364    | 2     | 16K  |      | 2048K |        |         |       |
| Intel     | Pentium 4                      | 14362    | 2     | 16K  |      | 1024K |        |         |       |
| Intel     | Celeron J4115                  | 14288    | 4     | 96K  | 128K | 4M    |        | 2500    | VT-x  |
| AMD       | Phenom II X2 570               | 14064    | 2     | 64K  | 64K  | 512K  | 6144K  | 3500    | AMD-V |
| AMD       | Phenom II X2 521               | 14064    | 2     | 64K  | 64K  | 1024K |        | 3500    | AMD-V |
| AMD       | Athlon II X2 4450e             | 14042    | 2     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| Intel     | Pentium G4500                  | 14022    | 2     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| AMD       | A4-5300 APU with Radeon HD ... | 14018    | 2     | 16K  | 64K  | 1024K |        | 3400    | AMD-V |
| Intel     | Pentium G3460                  | 14006    | 2     | 32K  | 32K  | 256K  | 3072K  | 3500    | VT-x  |
| AMD       | Athlon II X2 240e              | 14000    | 2     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| AMD       | A6-9500 RADEON R5, 8 COMPUT... | 13998    | 2     | 32K  | 96K  | 1024K |        | 3500    | AMD-V |
| Intel     | Celeron G5905                  | 13998    | 2     | 64K  | 64K  | 512K  | 4M     | 3500    | VT-x  |
| Intel     | Xeon X5260                     | 13998    | 2     | 32K  | 32K  | 6144K |        | 3336    | VT-x  |
| AMD       | A6-7480 Radeon R5, 8 Comput... | 13978    | 2     | 32K  | 96K  | 1024K |        | 3500    | AMD-V |
| AMD       | PRO A6-8570 R5, 8 COMPUTE C... | 13974    | 2     | 32K  | 96K  | 1024K |        | 3500    | AMD-V |
| AMD       | PRO A4-8350B R5, 6 Compute ... | 13972    | 2     | 16K  | 96K  | 1024K |        | 3500    | AMD-V |
| AMD       | Phenom II X2 550               | 13920    | 2     | 64K  | 64K  | 512K  | 6144K  | 3100    | AMD-V |
| Intel     | Core2 Duo E8500                | 13906    | 2     | 32K  | 32K  | 6144K |        | 3167    | VT-x  |
| AMD       | Phenom 8650 Triple-Core        | 13875    | 3     | 64K  | 64K  | 512K  | 2048K  | 2300    | AMD-V |
| AMD       | Phenom 8600 Triple-Core        | 13860    | 3     | 64K  | 64K  | 512K  | 2048K  | 2300    | AMD-V |
| Intel     | Pentium D                      | 13856    | 2     | 16K  |      | 2048K |        | 3403    | VT-x  |
| Intel     | Pentium Dual-Core E5300        | 13836    | 2     | 32K  | 32K  | 2048K |        | 5603    | VT-x  |
| Intel     | Core i5-L16G7                  | 13820    | 5     | 160K | 160K | 1.5M  | 4M     | 4300    | VT-x  |
| AMD       | Phenom 8600B Triple-Core       | 13770    | 3     | 192K | 192K | 1.5M  | 2M     | 2300    | AMD-V |
| AMD       | Phenom II N870 Triple-Core     | 13770    | 3     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| AMD       | Athlon II X3 405e              | 13767    | 3     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| Intel     | Atom N570                      | 13668    | 4     | 24K  | 32K  | 512K  |        | 1667    | VT-x  |
| AMD       | Phenom II X2 511               | 13660    | 2     | 64K  | 64K  | 1024K |        | 3400    | AMD-V |
| AMD       | Phenom 8450 Triple-Core        | 13659    | 3     | 64K  | 64K  | 512K  | 2048K  | 2100    | AMD-V |
| Intel     | Core i5-2557M                  | 13604    | 4     | 32K  | 32K  | 256K  | 3072K  | 2700    | VT-x  |
| Intel     | Pentium 4                      | 13600    | 2     | 16K  |      | 2048K |        | 3400    |       |
| Intel     | Pentium G3450                  | 13600    | 2     | 32K  | 32K  | 256K  | 3072K  | 3400    | VT-x  |
| Intel     | Core i3-4005U                  | 13600    | 4     | 32K  | 32K  | 256K  | 3072K  | 1701    | VT-x  |
| Intel     | Celeron G5900                  | 13598    | 2     | 64K  | 64K  | 512K  | 2M     | 3400    | VT-x  |
| Intel     | Pentium 4425Y                  | 13596    | 4     | 64K  | 64K  | 512K  | 2M     | 1700    | VT-x  |
| Intel     | Core i3-4010U                  | 13592    | 4     | 32K  | 32K  | 256K  | 3072K  | 1700    | VT-x  |
| Intel     | Pentium 4                      | 13590    | 2     |      |      |       |        | 3000    |       |
| Intel     | Core i5-3317U                  | 13584    | 4     | 32K  | 32K  | 256K  | 3072K  | 2600    | VT-x  |
| AMD       | A6-3430MX APU with Radeon H... | 13580    | 4     | 64K  | 64K  | 1024K |        | 1700    | AMD-V |
| AMD       | A4-5300B APU with Radeon HD... | 13580    | 2     | 16K  | 64K  | 1024K |        | 3400    | AMD-V |
| AMD       | A8-5545M APU with Radeon HD... | 13580    | 4     | 16K  | 64K  | 2048K |        | 1700    | AMD-V |
| AMD       | A6-9400 RADEON R5, 6 COMPUT... | 13578    | 2     | 32K  | 96K  | 1M    |        | 3400    | AMD-V |
| Intel     | Core i7-2637M                  | 13572    | 4     | 32K  | 32K  | 256K  | 4096K  | 2800    | VT-x  |
| AMD       | Athlon II X2 B28               | 13570    | 2     | 64K  | 64K  | 1024K |        | 3400    | AMD-V |
| Intel     | Core i5-3317U                  | 13568    | 4     | 32K  | 32K  | 256K  | 3072K  | 2600    | VT-x  |
| Intel     | Core i7-4610Y                  | 13568    | 4     | 32K  | 32K  | 256K  | 4096K  | 2900    | VT-x  |
| Intel     | Pentium 4                      | 13566    | 2     |      |      |       |        |         |       |
| Intel     | Atom T5700                     | 13516    | 4     | 24K  | 32K  | 2048K |        | 1700    | VT-x  |
| AMD       | Athlon II X2 240               | 13480    | 2     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| Intel     | Pentium D                      | 13448    | 2     | 16K  |      | 1024K |        | 3000    |       |
| Intel     | Pentium Dual-Core E6300        | 13440    | 2     | 32K  | 32K  | 2048K |        | 2800    | VT-x  |
| Intel     | Xeon X5260                     | 13364    | 2     | 32K  | 32K  | 6144K |        | 3330    | VT-x  |
| Intel     | Core2 Duo E8600                | 13356    | 2     | 32K  | 32K  | 6144K |        | 3336    | VT-x  |
| Intel     | Core2 Duo E7300                | 13356    | 2     | 32K  | 32K  | 3072K |        | 2670    |       |
| Intel     | Pentium Dual-Core E6800        | 13338    | 2     | 32K  | 32K  | 2048K |        | 3333    | VT-x  |
| Intel     | Core2 E8600                    | 13332    | 2     | 32K  | 32K  | 6144K |        |         |       |
| Intel     | Core2 4400                     | 13324    | 2     | 32K  | 32K  | 2048K |        | 2003    |       |
| Intel     | Pentium Dual-Core E5200        | 13298    | 2     | 32K  | 32K  | 2048K |        | 2500    |       |
| AMD       | Athlon II X2 265               | 13264    | 2     | 64K  | 64K  | 1024K |        | 3300    | AMD-V |
| AMD       | Phenom 8550 Triple-Core        | 13260    | 3     | 64K  | 64K  | 512K  | 2048K  | 2200    | AMD-V |
| AMD       | Athlon II X3 400e              | 13260    | 3     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| Intel     | Pentium G4400                  | 13254    | 2     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| Intel     | Pentium G3260                  | 13206    | 2     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| AMD       | Athlon II X2 250               | 13200    | 2     | 64K  | 64K  | 1024K |        | 3000    | AMD-V |
| Intel     | Pentium G3430                  | 13200    | 2     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| AMD       | Athlon II X2 250               | 13198    | 2     | 64K  | 64K  | 1024K |        | 3000    | AMD-V |
| AMD       | Phenom II N850 Triple-Core     | 13170    | 3     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| Intel     | Pentium G3440                  | 13170    | 2     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| Intel     | Pentium G2140                  | 13168    | 2     | 32K  | 32K  | 256K  | 3072K  | 3300    | VT-x  |
| Intel     | Pentium E5300                  | 13000    | 2     | 32K  | 32K  | 2048K |        | 2603    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 6400+   | 12904    | 2     | 64K  | 64K  | 1024K |        | 3200    | AMD-V |
| Intel     | Atom N2600                     | 12896    | 4     | 24K  | 32K  | 512K  |        | 1650    |       |
| AMD       | Athlon II X2 260               | 12890    | 2     | 64K  | 64K  | 1024K |        | 3200    | AMD-V |
| Intel     | Core i5-7Y57                   | 12868    | 4     | 64K  | 64K  | 512K  | 4M     | 3300    | VT-x  |
| Intel     | Core m3-7Y30                   | 12868    | 4     | 32K  | 32K  | 256K  | 4096K  | 2600    | VT-x  |
| Intel     | Core i5-8200Y                  | 12864    | 4     | 32K  | 32K  | 256K  | 4096K  | 3900    | VT-x  |
| Intel     | Core i7-7Y75                   | 12864    | 4     | 32K  | 32K  | 256K  | 4096K  | 3600    | VT-x  |
| Intel     | Core i7-8500Y                  | 12864    | 4     | 32K  | 32K  | 256K  | 4096K  | 4200    | VT-x  |
| Intel     | Core m3-8100Y                  | 12864    | 4     | 32K  | 32K  | 256K  | 4096K  | 3400    | VT-x  |
| Intel     | Pentium 4415Y                  | 12864    | 4     | 32K  | 32K  | 256K  | 2048K  | 1600    | VT-x  |
| Intel     | Pentium N3700                  | 12844    | 4     | 24K  | 32K  | 1024K |        | 2499    | VT-x  |
| Intel     | Celeron J3160                  | 12844    | 4     | 24K  | 32K  | 1024K |        | 2240    | VT-x  |
| Intel     | Pentium N3710                  | 12844    | 4     | 24K  | 32K  | 1024K |        | 2665    | VT-x  |
| Intel     | Celeron N3150                  | 12840    | 4     | 24K  | 32K  | 1024K |        | 2165    | VT-x  |
| Intel     | Pentium J3710                  | 12840    | 4     | 24K  | 32K  | 1024K |        | 2748    | VT-x  |
| AMD       | Athlon II X2 B26               | 12806    | 2     | 64K  | 64K  | 1024K |        | 3200    | AMD-V |
| AMD       | Phenom II X2 B57               | 12804    | 2     | 64K  | 64K  | 512K  | 6144K  | 3200    | AMD-V |
| Intel     | Xeon                           | 12804    | 2     | 16K  |      | 1024K |        |         |       |
| Intel     | Core i5-7Y54                   | 12804    | 4     | 32K  | 32K  | 256K  | 4096K  | 3200    | VT-x  |
| Intel     | Celeron G4920                  | 12804    | 2     | 32K  | 32K  | 256K  | 2048K  | 3200    | VT-x  |
| Intel     | Core i5-2467M                  | 12804    | 4     | 32K  | 32K  | 256K  | 3072K  | 2300    | VT-x  |
| Intel     | Celeron N2910                  | 12804    | 4     | 96K  | 128K | 2M    |        | 1599    | VT-x  |
| Intel     | Atom Z3795                     | 12804    | 4     | 24K  | 32K  | 1024K |        | 2399    | VT-x  |
| Intel     | Pentium G3258                  | 12804    | 2     | 32K  | 32K  | 256K  | 3072K  | 25500   | VT-x  |
| Intel     | Pentium G3420                  | 12804    | 2     | 32K  | 32K  | 256K  | 3072K  | 3200    | VT-x  |
| Intel     | Core i5-5250U                  | 12804    | 4     | 32K  | 32K  | 256K  | 3072K  | 2700    | VT-x  |
| Intel     | Celeron N3160                  | 12804    | 4     | 24K  | 32K  | 1024K |        | 2240    | VT-x  |
| Intel     | Pentium E6700                  | 12800    | 2     | 32K  | 32K  | 2048K |        | 3192    | VT-x  |
| Intel     | Pentium G3250                  | 12800    | 2     | 32K  | 32K  | 256K  | 3072K  | 3200    | VT-x  |
| Intel     | Atom x7-Z8700                  | 12800    | 4     | 24K  | 32K  | 1024K |        | 2400    | VT-x  |
| Intel     | Atom x7-Z8750                  | 12800    | 4     | 24K  | 32K  | 1024K |        | 2560    | VT-x  |
| Intel     | Atom C3508                     | 12800    | 4     | 24K  | 32K  | 2048K |        | 1600    | VT-x  |
| Intel     | Core2 X6800                    | 12798    | 2     | 32K  | 32K  | 4096K |        | 2936    | VT-x  |
| Intel     | Celeron G4930                  | 12798    | 2     | 32K  | 32K  | 256K  | 2048K  | 3200    | VT-x  |
| Intel     | Celeron E3200                  | 12798    | 2     | 32K  | 32K  | 1024K |        | 2403    | VT-x  |
| Intel     | Pentium G2130                  | 12798    | 2     | 32K  | 32K  | 256K  | 3072K  | 3200    | VT-x  |
| AMD       | Athlon 5150 APU with Radeon R3 | 12796    | 4     | 32K  | 32K  | 2048K |        | 1600    | AMD-V |
| AMD       | Athlon X2 340 Dual Core        | 12782    | 2     | 16K  | 64K  | 1024K |        | 3200    | AMD-V |
| AMD       | A4-4020 APU with Radeon HD ... | 12782    | 2     | 16K  | 64K  | 1024K |        | 3200    | AMD-V |
| AMD       | A6-3410MX APU with Radeon H... | 12780    | 4     | 64K  | 64K  | 1024K |        | 1600    | AMD-V |
| AMD       | A8-3520M APU with Radeon HD... | 12780    | 4     | 64K  | 64K  | 1024K |        | 1600    | AMD-V |
| AMD       | A8-4555M APU with Radeon HD... | 12780    | 4     | 16K  | 64K  | 2048K |        | 1600    | AMD-V |
| AMD       | A9-9430 RADEON R5, 5 COMPUT... | 12776    | 2     | 32K  | 64K  | 1024K |        | 3200    | AMD-V |
| AMD       | A8-8600P Radeon R6, 10 Comp... | 12776    | 4     | 32K  | 64K  | 1024K |        | 1600    | AMD-V |
| AMD       | PRO A8-8600B R6, 10 Compute... | 12776    | 4     | 32K  | 96K  | 1024K |        | 1600    | AMD-V |
| AMD       | Phenom II P920 Quad-Core       | 12772    | 4     | 64K  | 64K  | 512K  |        | 1600    | AMD-V |
| Intel     | Core i5-4300Y                  | 12772    | 4     | 32K  | 32K  | 256K  | 3072K  | 2300    | VT-x  |
| Intel     | Xeon E5310                     | 12768    | 4     | 32K  | 32K  | 4096K |        |         | VT-x  |
| Intel     | Core i3-4030Y                  | 12768    | 4     | 64K  | 64K  | 512K  | 3M     | 1600    | VT-x  |
| Intel     | Core i5-4202Y                  | 12768    | 4     | 32K  | 32K  | 256K  | 3072K  | 2000    | VT-x  |
| Intel     | Core i5-4302Y                  | 12768    | 4     | 32K  | 32K  | 256K  | 3072K  | 2300    | VT-x  |
| AMD       | Athlon II X2 245               | 12758    | 2     | 64K  | 64K  | 1024K |        | 2900    | AMD-V |
| Intel     | Core i3 U 330                  | 12748    | 4     | 32K  | 32K  | 256K  | 3072K  | 1199    | VT-x  |
| Intel     | Core i5 U 430                  | 12748    | 4     | 32K  | 32K  | 256K  | 3072K  | 1200    | VT-x  |
| Intel     | Atom E3940                     | 12748    | 4     | 24K  | 32K  | 1024K |        | 1800    | VT-x  |
| Intel     | Atom E3950                     | 12748    | 4     | 24K  | 32K  | 1024K |        | 2000    | VT-x  |
| Intel     | Core2 E8500                    | 12698    | 2     | 32K  | 32K  | 6144K |        | 3164    | VT-x  |
| Intel     | Core2 Duo E7200                | 12696    | 2     | 32K  | 32K  | 3072K |        | 4009    |       |
| AMD       | Phenom 8400 Triple-Core        | 12657    | 3     | 64K  | 64K  | 512K  | 2048K  | 2100    | AMD-V |
| Intel     | 2160                           | 12614    | 2     | 32K  | 32K  | 1024K |        | 1803    |       |
| AMD       | Athlon 64 X2 Dual Core 6000+   | 12600    | 2     | 64K  | 64K  | 1024K |        | 3000    | AMD-V |
| AMD       | Phenom II N830 Triple-Core     | 12597    | 3     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| Intel     | Pentium G2120                  | 12464    | 2     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 6000+   | 12462    | 2     | 64K  | 64K  | 512K  |        | 3100    | AMD-V |
| AMD       | Athlon II X2 255               | 12460    | 2     | 64K  | 64K  | 1024K |        | 3100    | AMD-V |
| AMD       | Phenom II X2 550               | 12456    | 2     | 64K  | 64K  | 512K  | 6144K  | 3100    | AMD-V |
| Intel     | Core2 6700                     | 12408    | 2     | 32K  | 32K  | 4096K |        | 2670    | VT-x  |
| Intel     | Pentium G3240                  | 12406    | 2     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| Intel     | Celeron G4900                  | 12404    | 2     | 32K  | 32K  | 256K  | 2048K  | 3100    | VT-x  |
| AMD       | Athlon X2 255                  | 12400    | 2     | 128K | 128K | 2M    |        | 3100    | AMD-V |
| AMD       | A9-9425 RADEON R5, 5 COMPUT... | 12400    | 2     | 32K  | 64K  | 1024K |        | 3100    | AMD-V |
| AMD       | A4-5050 APU with Radeon HD ... | 12396    | 4     | 32K  | 32K  | 2048K |        | 1550    | AMD-V |
| Intel     | Pentium G870                   | 12378    | 2     | 32K  | 32K  | 256K  | 3072K  | 3100    | VT-x  |
| AMD       | A4-5100 APU with Radeon HD ... | 12376    | 4     | 32K  | 32K  | 2048K |        | 1550    | AMD-V |
| AMD       | Athlon II X2 215               | 12364    | 2     | 64K  | 64K  | 512K  |        | 2700    | AMD-V |
| Intel     | Pentium G860                   | 12364    | 2     | 32K  | 32K  | 256K  | 3072K  | 3000    | VT-x  |
| Intel     | Xeon                           | 12294    | 2     |      |      |       |        |         |       |
| Intel     | Mobile Intel Pentium 4         | 12266    | 2     |      |      |       |        | 3059    |       |
| Intel     | Core2 T9900                    | 12266    | 2     | 32K  | 32K  | 6144K |        | 3067    | VT-x  |
| Intel     | Pentium E6600                  | 12266    | 2     | 32K  | 32K  | 2048K |        |         | VT-x  |
| Intel     | Core2 Extreme X9100            | 12266    | 2     | 32K  | 32K  | 6144K |        | 3067    | VT-x  |
| Intel     | Pentium 4                      | 12264    | 2     |      |      |       |        | 2399    |       |
| Intel     | Core2 Duo T9900                | 12240    | 2     | 32K  | 32K  | 6144K |        | 3068    | VT-x  |
| Intel     | Core2 Duo E8300                | 12240    | 2     | 32K  | 32K  | 6144K |        | 2834    | VT-x  |
| Intel     | Core2 Duo E8435                | 12234    | 2     | 32K  | 32K  | 6144K |        | 3067    | VT-x  |
| Intel     | Core2 Duo E8435                | 12234    | 2     | 32K  | 32K  | 6144K |        | 3066    | VT-x  |
| Intel     | Core2 Duo E4700                | 12220    | 2     | 32K  | 32K  | 2048K |        | 2603    |       |
| AMD       | Athlon 64 X2 Dual Core 5200+   | 12104    | 2     | 64K  | 64K  | 512K  |        | 2700    | AMD-V |
| Intel     | Core m7-6Y75                   | 12100    | 4     | 64K  | 64K  | 512K  | 4M     | 3100    | VT-x  |
| Intel     | Core m3-6Y30                   | 12096    | 4     | 32K  | 32K  | 256K  | 4096K  | 2200    | VT-x  |
| Intel     | Core m5-6Y54                   | 12096    | 4     | 32K  | 32K  | 256K  | 4096K  | 2700    | VT-x  |
| Intel     | Core m5-6Y57                   | 12096    | 4     | 32K  | 32K  | 256K  | 4096K  | 2800    | VT-x  |
| AMD       | Phenom II X2 545               | 12080    | 2     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| AMD       | Phenom II X2 545               | 12060    | 2     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| AMD       | A4-4000 APU with Radeon HD ... | 12060    | 2     | 16K  | 64K  | 1024K |        | 3000    | AMD-V |
| AMD       | Athlon II X2 250e              | 12056    | 2     | 64K  | 64K  | 1024K |        | 3000    | AMD-V |
| Intel     | Pentium E5700                  | 12056    | 2     | 32K  | 32K  | 2048K |        |         | VT-x  |
| AMD       | Athlon X2 250                  | 12054    | 2     | 64K  | 64K  | 1024K |        | 3000    | AMD-V |
| AMD       | Athlon II X2 B24               | 12054    | 2     | 64K  | 64K  | 1024K |        | 3000    | AMD-V |
| AMD       | Athlon II X2 B24               | 12052    | 2     | 64K  | 64K  | 1024K |        | 3000    | AMD-V |
| AMD       | Phenom II X2 B55               | 12044    | 2     | 64K  | 64K  | 512K  | 6144K  | 3000    | AMD-V |
| Intel     | Pentium 4                      | 12026    | 2     | 16K  |      | 1024K |        |         |       |
| Intel     | Xeon L3110                     | 12022    | 2     | 64K  | 64K  | 6M    |        | 2997    | VT-x  |
| Intel     | Core2 Duo E4600                | 12020    | 2     | 32K  | 32K  | 2048K |        | 2403    |       |
| Intel     | Pentium G2030                  | 12010    | 2     | 32K  | 32K  | 256K  | 3072K  | 3000    | VT-x  |
| Intel     | Pentium G3220                  | 12008    | 2     | 32K  | 32K  | 256K  | 3072K  | 3000    | VT-x  |
| Intel     | Celeron J3455                  | 12004    | 4     | 24K  | 32K  | 1024K |        | 2300    | VT-x  |
| AMD       | Athlon 7750 Dual-Core          | 12000    | 2     | 64K  | 64K  | 512K  | 2048K  | 2700    | AMD-V |
| Intel     | Xeon 5160                      | 12000    | 2     | 32K  | 32K  | 4096K |        | 3000    | VT-x  |
| Intel     | Atom N550                      | 12000    | 4     | 24K  | 32K  | 512K  |        | 1500    |       |
| Intel     | Pentium G4500T                 | 12000    | 2     | 32K  | 32K  | 256K  | 3072K  | 3000    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 4800+   | 11998    | 2     | 64K  | 64K  | 512K  |        | 2500    | AMD-V |
| Intel     | Xeon E3110                     | 11998    | 2     | 32K  | 32K  | 6144K |        | 3000    | VT-x  |
| Intel     | Xeon E3110                     | 11998    | 2     | 32K  | 32K  | 6144K |        | 3000    | VT-x  |
| Intel     | Pentium 4405Y                  | 11996    | 4     | 32K  | 32K  | 256K  | 2048K  | 1500    | VT-x  |
| Intel     | Atom Z3775D                    | 11992    | 4     | 24K  | 32K  | 1024K |        | 2415    | VT-x  |
| Intel     | Celeron J4105                  | 11984    | 4     | 24K  | 32K  | 4096K |        | 2500    | VT-x  |
| Intel     | Pentium Silver J5005           | 11984    | 4     | 24K  | 32K  | 4096K |        | 2800    | VT-x  |
| Intel     | Pentium J4205                  | 11984    | 4     | 24K  | 32K  | 1024K |        | 2600    | VT-x  |
| AMD       | A9-9420 RADEON R5, 5 COMPUT... | 11982    | 2     | 32K  | 64K  | 1024K |        | 3000    | AMD-V |
| AMD       | A6-3420M APU with Radeon HD... | 11980    | 4     | 64K  | 64K  | 1024K |        | 1500    | AMD-V |
| AMD       | A8-3500M APU with Radeon HD... | 11980    | 4     | 64K  | 64K  | 1024K |        | 1500    | AMD-V |
| AMD       | A4-5000 APU with Radeon HD ... | 11980    | 4     | 32K  | 32K  | 2048K |        | 1500    | AMD-V |
| AMD       | GX-415GA SOC with Radeon HD... | 11980    | 4     | 32K  | 32K  | 2048K |        | 1500    | AMD-V |
| AMD       | E2-6110 APU with AMD Radeon... | 11980    | 4     | 32K  | 32K  | 2048K |        | 1500    | AMD-V |
| Intel     | Celeron J3455                  | 11980    | 4     | 96K  | 128K | 2M    |        | 2300    | VT-x  |
| Intel     | Celeron J3455E                 | 11980    | 4     | 96K  | 128K | 2M    |        | 2300    | VT-x  |
| AMD       | A6-9500E RADEON R5, 6 COMPU... | 11978    | 2     | 32K  | 96K  | 1024K |        | 3000    | AMD-V |
| AMD       | PRO A6-7350B R5, 5 COMPUTE ... | 11978    | 2     | 32K  | 64K  | 1024K |        | 3000    | AMD-V |
| Intel     | Core i3-2375M                  | 11976    | 4     | 32K  | 32K  | 256K  | 3072K  | 1500    | VT-x  |
| Intel     | Core i3-4020Y                  | 11976    | 4     | 32K  | 32K  | 256K  | 3072K  | 1500    | VT-x  |
| Intel     | Core i5-4210Y                  | 11976    | 4     | 32K  | 32K  | 256K  | 3072K  | 1900    | VT-x  |
| Intel     | Core i3-2377M                  | 11972    | 4     | 32K  | 32K  | 256K  | 3072K  | 1500    | VT-x  |
| Intel     | Core i5-3339Y                  | 11972    | 4     | 32K  | 32K  | 256K  | 3072K  | 2000    | VT-x  |
| Intel     | Core i3-4012Y                  | 11972    | 4     | 32K  | 32K  | 256K  | 3072K  | 1500    | VT-x  |
| AMD       | Phenom II N660 Dual-Core       | 11970    | 2     | 64K  | 64K  | 1024K |        | 3000    | AMD-V |
| Intel     | Xeon 5160                      | 11970    | 2     | 128K | 128K | 8M    |        | 2988    | VT-x  |
| AMD       | Phenom II P860 Triple-Core     | 11967    | 3     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| Intel     | Pentium G850                   | 11952    | 2     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| Intel     | Core2 Duo E6550                | 11760    | 2     | 32K  | 32K  | 4096K |        | 2380    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 5600+   | 11758    | 2     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| Intel     | Atom Z3775                     | 11736    | 4     | 24K  | 32K  | 1024K |        | 2399    | VT-x  |
| Intel     | Core2 E7500                    | 11732    | 2     | 32K  | 32K  | 3072K |        |         |       |
| Intel     | Core i7 U 680                  | 11732    | 4     | 64K  | 64K  | 512K  | 4M     | 1467    | VT-x  |
| Intel     | Atom Z3770                     | 11732    | 4     | 24K  | 32K  | 1024K |        | 2399    | VT-x  |
| Intel     | Core2 Duo T9800                | 11708    | 2     | 32K  | 32K  | 6144K |        | 2935    | VT-x  |
| Intel     | Core2 Duo T6600                | 11704    | 2     | 32K  | 32K  | 2048K |        | 2933    |       |
| Intel     | Pentium G6960                  | 11704    | 2     | 32K  | 32K  | 256K  | 3072K  | 2933    | VT-x  |
| Intel     | Core2 Duo E8335                | 11674    | 2     | 32K  | 32K  | 6144K |        | 2926    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 5600+   | 11660    | 2     | 64K  | 64K  | 512K  |        | 2900    | AMD-V |
| AMD       | Athlon II X2 245               | 11656    | 2     | 64K  | 64K  | 1024K |        | 2900    | AMD-V |
| AMD       | Athlon X2 245                  | 11652    | 2     | 128K | 128K | 2M    |        | 2900    | AMD-V |
| AMD       | Athlon II X2 225               | 11652    | 2     | 64K  | 64K  | 512K  |        | 2900    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 5400+   | 11648    | 2     | 64K  | 64K  | 512K  |        | 2800    | AMD-V |
| AMD       | Athlon II X2 240e              | 11646    | 2     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| Intel     | Pentium G4400T                 | 11622    | 2     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| Intel     | Celeron G3930                  | 11620    | 2     | 32K  | 32K  | 256K  | 2048K  | 2900    | VT-x  |
| Intel     | Atom x5-Z8500                  | 11616    | 4     | 24K  | 32K  | 1024K |        | 2240    | VT-x  |
| Intel     | Pentium G2020                  | 11610    | 2     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| Intel     | Celeron G3920                  | 11610    | 2     | 32K  | 32K  | 256K  | 2048K  | 2900    | VT-x  |
| Intel     | Atom x5-Z8350                  | 11608    | 4     | 24K  | 32K  | 1024K |        | 1999    | VT-x  |
| Intel     | Pentium G645                   | 11600    | 2     | 32K  | 32K  | 256K  | 3072K  | 2900    | VT-x  |
| Intel     | Celeron G1850                  | 11600    | 2     | 32K  | 32K  | 256K  | 2048K  | 2900    | VT-x  |
| AMD       | A9-9410 RADEON R5, 5 COMPUT... | 11584    | 2     | 32K  | 64K  | 1024K |        | 2900    | AMD-V |
| AMD       | A6-5357M APU with Radeon HD... | 11582    | 2     | 16K  | 64K  | 1024K |        | 2900    | AMD-V |
| AMD       | A6-5350M APU with Radeon HD... | 11578    | 2     | 16K  | 64K  | 1024K |        | 2900    | AMD-V |
| AMD       | Athlon II X2 245e              | 11570    | 2     | 64K  | 64K  | 1024K |        | 2900    | AMD-V |
| AMD       | Phenom II N640 Dual-Core       | 11570    | 2     | 64K  | 64K  | 1024K |        | 2900    | AMD-V |
| Intel     | Pentium G840                   | 11536    | 2     | 32K  | 32K  | 256K  | 3072K  | 2800    | VT-x  |
| Intel     | Pentium G2010                  | 11534    | 2     | 32K  | 32K  | 256K  | 3072K  | 2800    | VT-x  |
| Intel     | Atom x5-Z8300                  | 11524    | 4     | 24K  | 32K  | 1024K |        | 1915    | VT-x  |
| Intel     | Atom x5-Z8550                  | 11524    | 4     | 24K  | 32K  | 1024K |        | 2400    | VT-x  |
| Intel     | Atom x5-Z8330                  | 11520    | 4     | 24K  | 32K  | 1024K |        | 1920    | VT-x  |
| Intel     | Pentium Dual-Core E5200        | 11452    | 2     | 32K  | 32K  | 2048K |        | 2875    |       |
| AMD       | Phenom 8250e Triple-Core       | 11451    | 3     | 64K  | 64K  | 512K  | 2048K  | 1900    | AMD-V |
| AMD       | Phenom II P840 Triple-Core     | 11370    | 3     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| AMD       | Athlon II X2 B22               | 11274    | 2     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 5400+   | 11256    | 2     | 64K  | 64K  | 512K  |        | 2800    | AMD-V |
| AMD       | Athlon Dual Core 5400B         | 11254    | 2     | 64K  | 64K  | 512K  |        | 2800    | AMD-V |
| AMD       | Dual Core Opteron 890          | 11252    | 2     | 256K | 256K | 4M    |        |         |       |
| AMD       | Athlon 7850 Dual-Core          | 11250    | 2     | 64K  | 64K  | 512K  | 2048K  | 2800    | AMD-V |
| AMD       | Athlon X2 240                  | 11250    | 2     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| Intel     | Pentium G6950                  | 11244    | 2     | 32K  | 32K  | 256K  | 3072K  | 2800    | VT-x  |
| Intel     | Celeron G3900                  | 11242    | 2     | 32K  | 32K  | 256K  | 2048K  | 2800    | VT-x  |
| Intel     | Celeron G1840                  | 11210    | 2     | 32K  | 32K  | 256K  | 2048K  | 2800    | VT-x  |
| Intel     | Core2 Duo T9600                | 11204    | 2     | 32K  | 32K  | 6144K |        | 2801    | VT-x  |
| Intel     | Core2 E7400                    | 11204    | 2     | 32K  | 32K  | 3072K |        |         |       |
| AMD       | Athlon II X2 B22               | 11200    | 2     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| Intel     | Core2 Duo T9600                | 11200    | 2     | 32K  | 32K  | 6144K |        | 2801    | VT-x  |
| Intel     | Pentium G6950                  | 11200    | 2     | 32K  | 32K  | 256K  | 3072K  | 2800    | VT-x  |
| Intel     | Celeron G1630                  | 11200    | 2     | 32K  | 32K  | 256K  | 2048K  | 2800    | VT-x  |
| Intel     | Celeron G1830                  | 11200    | 2     | 32K  | 32K  | 256K  | 2048K  | 2800    | VT-x  |
| Intel     | Core M-5Y71                    | 11200    | 4     | 32K  | 32K  | 256K  | 4096K  | 2900    | VT-x  |
| AMD       | Dual-Core Opteron 2220         | 11198    | 2     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| AMD       | Phenom X2 Dual-Core GE-4060    | 11198    | 2     | 64K  | 64K  | 1024K |        |         | AMD-V |
| Intel     | Pentium E5500                  | 11198    | 2     | 32K  | 32K  | 2048K |        | 2800    | VT-x  |
| Intel     | Pentium E6300                  | 11198    | 2     | 32K  | 32K  | 2048K |        |         | VT-x  |
| Intel     | Core i3-2365M                  | 11192    | 4     | 32K  | 32K  | 256K  | 3072K  | 1400    | VT-x  |
| AMD       | A6-3400M APU with Radeon HD... | 11184    | 4     | 64K  | 64K  | 1024K |        | 1400    | AMD-V |
| AMD       | Athlon Silver 3050e with Ra... | 11184    | 4     | 64K  | 128K | 1M    | 4M     | 1400    | AMD-V |
| AMD       | A4-3420 APU with Radeon HD ... | 11182    | 2     | 128K | 128K | 1M    |        | 2800    | AMD-V |
| Intel     | Pentium G640                   | 11182    | 2     | 32K  | 32K  | 256K  | 3072K  | 2800    | VT-x  |
| Intel     | Core2 Duo P9700                | 11176    | 2     | 32K  | 32K  | 6144K |        | 2801    | VT-x  |
| Intel     | Core i3-2367M                  | 11176    | 4     | 32K  | 32K  | 256K  | 3072K  | 1400    | VT-x  |
| AMD       | Phenom II N620 Dual-Core       | 11174    | 2     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| Intel     | Pentium G3250T                 | 11174    | 2     | 32K  | 32K  | 256K  | 3072K  | 2800    | VT-x  |
| Intel     | Mobile Intel Pentium 4         | 11172    | 2     |      |      |       |        | 3192    |       |
| Intel     | Core2 Extreme X7900            | 11172    | 2     | 32K  | 32K  | 4096K |        | 2800    | VT-x  |
| Intel     | Core2 Duo E8235                | 11172    | 2     | 32K  | 32K  | 6144K |        | 2800    | VT-x  |
| Intel     | Core i5-2537M                  | 11172    | 4     | 32K  | 32K  | 256K  | 3072K  | 2300    | VT-x  |
| Intel     | Core i3-3229Y                  | 11172    | 4     | 32K  | 32K  | 256K  | 3072K  | 1400    | VT-x  |
| Intel     | Core i5-4200Y                  | 11172    | 4     | 64K  | 64K  | 512K  | 3M     | 1900    | VT-x  |
| Intel     | Core2 Extreme X7900            | 11170    | 2     | 32K  | 32K  | 4096K |        | 2800    | VT-x  |
| Intel     | Pentium G630                   | 11124    | 2     | 32K  | 32K  | 256K  | 3072K  | 2700    | VT-x  |
| AMD       | A4-3400 APU with Radeon HD ... | 11122    | 2     | 64K  | 64K  | 512K  |        | 2700    | AMD-V |
| AMD       | Athlon Dual Core 4850e         | 10998    | 2     | 64K  | 64K  | 512K  |        | 2500    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 5000+   | 10948    | 2     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 5000+   | 10926    | 2     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| Intel     | Pentium G620                   | 10918    | 2     | 32K  | 32K  | 256K  | 3072K  | 2600    | VT-x  |
| AMD       | Sempron 3850 APU with Radeo... | 10916    | 4     | 32K  | 32K  | 2048K |        | 1300    | AMD-V |
| AMD       | Athlon II X2 215               | 10852    | 2     | 64K  | 64K  | 512K  |        | 2700    | AMD-V |
| AMD       | Athlon II X2 4400e             | 10850    | 2     | 64K  | 64K  | 1024K |        | 2700    | AMD-V |
| AMD       | Athlon II X2 235e              | 10848    | 2     | 64K  | 64K  | 1024K |        | 2700    | AMD-V |
| AMD       | Athlon X2 215                  | 10848    | 2     | 64K  | 64K  | 512K  |        | 2700    | AMD-V |
| Intel     | Celeron G1620                  | 10810    | 2     | 32K  | 32K  | 256K  | 2048K  | 2700    | VT-x  |
| Intel     | Celeron E3500                  | 10804    | 2     | 32K  | 32K  | 1024K |        | 2700    | VT-x  |
| Intel     | Core2 6600                     | 10800    | 2     | 32K  | 32K  | 4096K |        | 2448    | VT-x  |
| Intel     | Celeron G1820                  | 10800    | 2     | 32K  | 32K  | 256K  | 2048K  | 2700    | VT-x  |
| Intel     | Pentium E5400                  | 10798    | 2     | 32K  | 32K  | 2048K |        |         |       |
| AMD       | A6-4400M APU with Radeon HD... | 10784    | 2     | 16K  | 64K  | 1024K |        | 2700    | AMD-V |
| AMD       | A4-5150M APU with Radeon HD... | 10784    | 2     | 16K  | 64K  | 1024K |        | 2700    | AMD-V |
| Intel     | Pentium G3240T                 | 10782    | 2     | 32K  | 32K  | 256K  | 3072K  | 2700    | VT-x  |
| Intel     | Celeron G555                   | 10776    | 2     | 64K  | 64K  | 512K  | 2M     | 2700    | VT-x  |
| AMD       | Phenom II P820 Triple-Core     | 10773    | 3     | 64K  | 64K  | 512K  |        | 1800    | AMD-V |
| Intel     | Core2 Duo E8200                | 10772    | 2     | 32K  | 32K  | 6144K |        | 2670    | VT-x  |
| Intel     | Atom Z3735F                    | 10696    | 4     | 24K  | 32K  | 1024K |        | 1832    | VT-x  |
| Intel     | Atom Z3735G                    | 10696    | 4     | 24K  | 32K  | 1024K |        | 1832    | VT-x  |
| Intel     | Core i5 U 470                  | 10692    | 4     | 32K  | 32K  | 256K  | 3072K  | 1334    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 5200+   | 10686    | 2     | 64K  | 64K  | 1024K |        | 2600    | AMD-V |
| Intel     | Atom Z3735D                    | 10684    | 4     | 24K  | 32K  | 1024K |        | 1832    | VT-x  |
| Intel     | Core2 Duo P8800                | 10670    | 2     | 32K  | 32K  | 3072K |        | 2668    | VT-x  |
| Intel     | Core2 Duo T9550                | 10670    | 2     | 32K  | 32K  | 6144K |        | 2668    | VT-x  |
| Intel     | Atom Z3740                     | 10668    | 4     | 24K  | 32K  | 1024K |        | 1866    | VT-x  |
| Intel     | Xeon 3070                      | 10666    | 2     | 32K  | 32K  | 4096K |        | 2660    | VT-x  |
| Intel     | Core2 Duo P9600                | 10664    | 2     | 32K  | 32K  | 6144K |        | 2668    | VT-x  |
| Intel     | Atom Z3740D                    | 10664    | 4     | 24K  | 32K  | 1024K |        | 1832    | VT-x  |
| Intel     | Atom Z3736F                    | 10664    | 4     | 24K  | 32K  | 1024K |        | 2165    | VT-x  |
| Intel     | Atom Z3745                     | 10664    | 4     | 24K  | 32K  | 1024K |        | 1866    | VT-x  |
| Intel     | Core i7 U 660                  | 10644    | 4     | 64K  | 64K  | 512K  | 4M     | 1334    |       |
| Intel     | Core2 Duo E4400                | 10640    | 2     | 32K  | 32K  | 2048K |        | 2667    |       |
| Intel     | Xeon 5150                      | 10640    | 2     | 32K  | 32K  | 4096K |        | 2667    | VT-x  |
| Intel     | Core2 Duo E8335                | 10640    | 2     | 32K  | 32K  | 6144K |        | 2667    | VT-x  |
| Intel     | Core i3 U 380                  | 10640    | 4     | 32K  | 32K  | 256K  | 3072K  | 1333    | VT-x  |
| Intel     | Xeon 5150                      | 10638    | 2     | 32K  | 32K  | 4096K |        | 2667    | VT-x  |
| Intel     | Xeon                           | 10632    | 2     |      |      |       |        |         |       |
| AMD       | Dual Core Opteron 185          | 10622    | 2     | 64K  | 64K  | 1024K |        | 2600    |       |
| Intel     | Core2 Duo E8135                | 10612    | 2     | 32K  | 32K  | 6144K |        | 2660    | VT-x  |
| Intel     | Core2 6400                     | 10568    | 2     | 32K  | 32K  | 2048K |        | 2136    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 4200+   | 10560    | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| Intel     | Celeron G540                   | 10498    | 2     | 32K  | 32K  | 256K  | 2048K  | 2500    | VT-x  |
| AMD       | Athlon 64 FX-60 Dual Core      | 10456    | 2     | 64K  | 64K  | 1024K |        |         |       |
| AMD       | Athlon II X2 210e              | 10456    | 2     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 5000+   | 10452    | 2     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 5200+   | 10452    | 2     | 64K  | 64K  | 1024K |        | 2600    | AMD-V |
| AMD       | Dual Core Opteron 285          | 10448    | 2     | 256K | 256K | 4M    |        | 2600    |       |
| AMD       | Athlon 64 X2 Dual Core 5000+   | 10446    | 2     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| Intel     | Celeron G1610                  | 10434    | 2     | 32K  | 32K  | 256K  | 2048K  | 2600    | VT-x  |
| AMD       | Athlon Dual Core 5000B         | 10422    | 2     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| AMD       | Athlon Dual Core 5050e         | 10422    | 2     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| AMD       | Athlon 64 Dual Core 5200+      | 10404    | 2     | 64K  | 64K  | 1024K |        | 2600    | AMD-V |
| AMD       | A6-9225 RADEON R4, 5 COMPUT... | 10404    | 2     | 32K  | 64K  | 1024K |        | 2600    | AMD-V |
| Intel     | Celeron G550                   | 10404    | 2     | 32K  | 32K  | 256K  | 2048K  | 2600    | VT-x  |
| AMD       | E2-3800 APU with Radeon HD ... | 10384    | 4     | 32K  | 32K  | 2048K |        | 1300    | AMD-V |
| AMD       | A6-9230 RADEON R4, 5 COMPUT... | 10380    | 2     | 32K  | 64K  | 1024K |        | 2600    | AMD-V |
| AMD       | QC-4000                        | 10380    | 4     | 32K  | 32K  | 2048K |        | 1300    | AMD-V |
| Intel     | Core i3-4010Y                  | 10380    | 4     | 32K  | 32K  | 256K  | 3072K  | 1300    | VT-x  |
| Intel     | Core2 Duo T9500                | 10378    | 2     | 32K  | 32K  | 6144K |        | 2601    | VT-x  |
| Intel     | Pentium G2030T                 | 10376    | 2     | 32K  | 32K  | 256K  | 3072K  | 2600    | VT-x  |
| Intel     | Pentium G3220T                 | 10376    | 2     | 32K  | 32K  | 256K  | 3072K  | 2600    | VT-x  |
| Intel     | 5Y70                           | 10376    | 4     | 32K  | 32K  | 256K  | 4096K  | 2600    | VT-x  |
| Intel     | Core M-5Y51                    | 10376    | 4     | 32K  | 32K  | 256K  | 4096K  | 2600    | VT-x  |
| AMD       | Turion II N550 Dual-Core       | 10374    | 2     | 64K  | 64K  | 1024K |        | 2600    | AMD-V |
| Intel     | Core2 Extreme X7800            | 10374    | 2     | 32K  | 32K  | 4096K |        | 2600    | VT-x  |
| Intel     | Core2 Duo T7800                | 10374    | 2     | 32K  | 32K  | 4096K |        | 2601    | VT-x  |
| ARM       | Cortex-A7                      | 10360    | 4     |      |      |       |        | 2000    |       |
| Intel     | Core2 6400                     | 10240    | 2     | 32K  | 32K  | 2048K |        | 2136    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 4400+   | 10196    | 2     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| Intel     | Core2 P8700                    | 10134    | 2     | 32K  | 32K  | 3072K |        | 2534    | VT-x  |
| Intel     | Core2 Duo P9500                | 10134    | 2     | 32K  | 32K  | 6144K |        | 2535    | VT-x  |
| Intel     | Xeon W3505                     | 10134    | 2     | 32K  | 32K  | 256K  | 4096K  | 2527    | VT-x  |
| Intel     | Core2 Duo P8700                | 10132    | 2     | 32K  | 32K  | 3072K |        | 2535    | VT-x  |
| Intel     | Core2 Duo T9400                | 10132    | 2     | 32K  | 32K  | 6144K |        | 2535    | VT-x  |
| Intel     | Core2 Duo T9400                | 10132    | 2     | 32K  | 32K  | 6144K |        | 2535    | VT-x  |
| Intel     | Pentium Dual E2200             | 10120    | 2     | 32K  | 32K  | 1024K |        | 2203    |       |
| Intel     | Core2 Duo E4500                | 10094    | 2     | 32K  | 32K  | 2048K |        | 2300    |       |
| AMD       | Athlon 64 X2 Dual Core 4800+   | 10050    | 2     | 64K  | 64K  | 512K  |        | 2500    | AMD-V |
| AMD       | Athlon 7550 Dual-Core          | 10046    | 2     | 64K  | 64K  | 512K  | 2048K  | 2500    | AMD-V |
| AMD       | Sempron X2 190                 | 10044    | 2     | 64K  | 64K  | 512K  |        | 2500    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 4000+   | 10038    | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| AMD       | Turion II N530 Dual-Core       | 10000    | 2     | 64K  | 64K  | 1024K |        | 2500    | AMD-V |
| Intel     | Pentium E5200                  | 10000    | 2     | 32K  | 32K  | 2048K |        | 6300    |       |
| Intel     | Core2 Duo T9300                | 10000    | 2     | 32K  | 32K  | 6144K |        | 2501    | VT-x  |
| AMD       | Athlon Dual Core 4850B         | 9996     | 2     | 64K  | 64K  | 512K  |        | 2500    | AMD-V |
| AMD       | A4-4300M APU with Radeon HD... | 9986     | 2     | 16K  | 64K  | 1024K |        | 2500    | AMD-V |
| AMD       | A6-9220 RADEON R4, 5 COMPUT... | 9984     | 2     | 32K  | 64K  | 1024K |        | 2500    | AMD-V |
| AMD       | PRO A4-4350B R4, 5 COMPUTE ... | 9984     | 2     | 32K  | 64K  | 1024K |        | 2500    | AMD-V |
| Intel     | Pentium 2030M                  | 9982     | 2     | 32K  | 32K  | 256K  | 2048K  | 2500    | VT-x  |
| Intel     | Pentium G645T                  | 9980     | 2     | 32K  | 32K  | 256K  | 3072K  | 2500    | VT-x  |
| AMD       | Turion II P560 Dual-Core       | 9978     | 2     | 64K  | 64K  | 1024K |        | 2500    | AMD-V |
| Intel     | Pentium G2020T                 | 9976     | 2     | 32K  | 32K  | 256K  | 3072K  | 2500    | VT-x  |
| Intel     | Celeron G1840T                 | 9976     | 2     | 32K  | 32K  | 256K  | 2048K  | 2500    | VT-x  |
| AMD       | Turion II Ultra Dual-Core M... | 9974     | 2     | 64K  | 64K  | 1024K |        | 2500    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 4800+   | 9792     | 2     | 64K  | 64K  | 1024K |        | 2400    |       |
| Intel     | Core2 Duo T8300                | 9766     | 2     | 32K  | 32K  | 3072K |        | 2401    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 4600+   | 9742     | 2     | 64K  | 64K  | 512K  |        | 2400    | AMD-V |
| AMD       | Dual-Core Opteron 8216         | 9716     | 2     | 64K  | 64K  | 1024K |        |         | AMD-V |
| Intel     | Celeron J1800                  | 9684     | 2     | 24K  | 32K  | 1024K |        | 2582    | VT-x  |
| Intel     | Pentium Dual E2220             | 9678     | 2     | 32K  | 32K  | 1024K |        | 2403    |       |
| AMD       | Athlon 64 X2 Dual Core 4600+   | 9670     | 2     | 64K  | 64K  | 512K  |        | 2400    |       |
| Intel     | Celeron J1800                  | 9666     | 2     | 24K  | 32K  | 1024K |        | 2582    | VT-x  |
| Intel     | Celeron J1800                  | 9666     | 2     | 24K  | 32K  | 1024K |        | 2582    | VT-x  |
| AMD       | Turion 64 X2 Mobile Technol... | 9648     | 2     | 64K  | 64K  | 512K  |        | 2400    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 4600+   | 9648     | 2     | 64K  | 64K  | 512K  |        | 2400    |       |
| AMD       | Dual Core Opteron 180          | 9646     | 2     | 128K | 128K | 2M    |        | 2400    |       |
| AMD       | Athlon 64 X2 Dual Core 4600+   | 9646     | 2     | 64K  | 64K  | 512K  |        | 2400    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 4600+   | 9644     | 2     | 64K  | 64K  | 512K  |        | 2400    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 5000+   | 9644     | 2     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| AMD       | Athlon 7450 Dual-Core          | 9644     | 2     | 64K  | 64K  | 512K  | 2048K  | 2400    | AMD-V |
| Intel     | Celeron G530                   | 9630     | 2     | 32K  | 32K  | 256K  | 2048K  | 2400    | VT-x  |
| AMD       | Turion II Ultra Dual-Core M... | 9604     | 2     | 64K  | 64K  | 1024K |        | 2400    | AMD-V |
| Intel     | Core2 Duo P8600                | 9604     | 2     | 32K  | 32K  | 3072K |        | 2401    | VT-x  |
| AMD       | Turion II P540 Dual-Core       | 9600     | 2     | 64K  | 64K  | 1024K |        | 2400    | AMD-V |
| AMD       | Turion Dual-Core ZM-87         | 9600     | 2     | 64K  | 64K  | 1024K |        | 2400    | AMD-V |
| AMD       | Turion X2 Ultra Dual-Core M... | 9600     | 2     | 64K  | 64K  | 1024K |        | 2400    | AMD-V |
| HiSilicon | Kunpeng-920                    | 9600     | 48    | 6M   | 6M   | 48M   | 192M   | 2600    |       |
| Intel     | Core m3-7Y32                   | 9600     | 4     | 32K  | 32K  | 256K  | 4096K  | 3000    | VT-x  |
| Intel     | Core2 Duo T7700                | 9600     | 2     | 32K  | 32K  | 4096K |        | 2401    | VT-x  |
| Intel     | Xeon 3060                      | 9600     | 2     | 64K  | 64K  | 4M    |        | 2394    | VT-x  |
| Intel     | Core2 P8600                    | 9600     | 2     | 32K  | 32K  | 3072K |        | 2401    | VT-x  |
| Intel     | Xeon W3503                     | 9600     | 2     | 32K  | 32K  | 256K  | 4096K  | 2394    | VT-x  |
| Intel     | Core i7 U 640                  | 9600     | 4     | 32K  | 32K  | 256K  | 4096K  | 1200    | VT-x  |
| Intel     | Pentium G640T                  | 9600     | 2     | 64K  | 64K  | 512K  | 3M     | 2400    |       |
| AMD       | Turion Dual-Core ZM-86         | 9598     | 2     | 64K  | 64K  | 1024K |        | 2400    | AMD-V |
| AMD       | E2-3200 APU with Radeon HD ... | 9598     | 2     | 64K  | 64K  | 512K  |        | 2400    | AMD-V |
| Intel     | Core2 Duo T7700                | 9598     | 2     | 32K  | 32K  | 4096K |        | 2401    | VT-x  |
| Intel     | Core2 Duo P8600                | 9598     | 2     | 32K  | 32K  | 3072K |        | 2401    | VT-x  |
| Intel     | Pentium B980                   | 9594     | 2     | 32K  | 32K  | 256K  | 2048K  | 2400    |       |
| Intel     | Pentium 2020M                  | 9588     | 2     | 32K  | 32K  | 256K  | 2048K  | 2400    | VT-x  |
| AMD       | A9-9400 RADEON R5, 5 COMPUT... | 9586     | 2     | 32K  | 64K  | 1024K |        | 2400    | AMD-V |
| AMD       | A6-9210 RADEON R4, 5 COMPUT... | 9582     | 2     | 32K  | 64K  | 1024K |        | 2400    | AMD-V |
| Intel     | Core2 Duo P9400                | 9580     | 2     | 32K  | 32K  | 6144K |        | 2401    | VT-x  |
| Intel     | Celeron G1620T                 | 9580     | 2     | 32K  | 32K  | 256K  | 2048K  | 2400    | VT-x  |
| Intel     | Core2 Duo P9400                | 9578     | 2     | 32K  | 32K  | 6144K |        | 2401    | VT-x  |
| Intel     | Celeron G1820T                 | 9578     | 2     | 32K  | 32K  | 256K  | 2048K  | 2400    | VT-x  |
| Intel     | Pentium 3560M                  | 9578     | 2     | 32K  | 32K  | 256K  | 2048K  | 2400    | VT-x  |
| AMD       | Athlon II N350 Dual-Core       | 9576     | 2     | 64K  | 64K  | 512K  |        | 2400    | AMD-V |
| Intel     | Core2 Duo E8135                | 9576     | 2     | 32K  | 32K  | 6144K |        | 2400    | VT-x  |
| Intel     | Core i5 U 540                  | 9576     | 4     | 32K  | 32K  | 256K  | 3072K  | 1200    | VT-x  |
| Intel     | Core2 4300                     | 9574     | 2     | 32K  | 32K  | 2048K |        | 2400    |       |
| Intel     | Core i3-1005G1                 | 9524     | 4     | 48K  | 32K  | 512K  | 4096K  | 3400    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 4400+   | 9474     | 2     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| Intel     | Core2 T7600                    | 9364     | 2     | 32K  | 32K  | 4096K |        | 2333    | VT-x  |
| Intel     | Core2 Duo E6540                | 9332     | 2     | 32K  | 32K  | 4096K |        | 2333    | VT-x  |
| Intel     | Xeon 3065                      | 9332     | 2     | 64K  | 64K  | 4M    |        | 2333    | VT-x  |
| Intel     | Xeon 5140                      | 9332     | 2     | 32K  | 32K  | 4096K |        | 2333    | VT-x  |
| Intel     | Core2 6300                     | 9320     | 2     | 32K  | 32K  | 2048K |        | 1870    | VT-x  |
| Intel     | Xeon 5140                      | 9310     | 2     | 32K  | 32K  | 4096K |        | 2333    | VT-x  |
| Intel     | Pentium Dual-Core T4500        | 9268     | 2     | 32K  | 32K  | 1024K |        | 2300    |       |
| Intel     | Pentium Dual E2180             | 9246     | 2     | 32K  | 32K  | 1024K |        | 2003    |       |
| AMD       | Athlon Dual Core 4450e         | 9242     | 2     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| AMD       | Athlon 5200 Dual-Core          | 9242     | 2     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| AMD       | Athlon Dual Core 4450B         | 9240     | 2     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| AMD       | TurionX2 Ultra DualCore Mob... | 9208     | 2     | 128K | 128K | 2M    |        | 2300    | AMD-V |
| AMD       | A4-9125 RADEON R3, 4 COMPUT... | 9204     | 2     | 32K  | 64K  | 1024K |        | 2300    | AMD-V |
| AMD       | Turion II P520 Dual-Core       | 9202     | 2     | 64K  | 64K  | 1024K |        | 2300    | AMD-V |
| AMD       | Turion 64 X2 Mobile Technol... | 9200     | 2     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| AMD       | Turion II Dual-Core Mobile ... | 9200     | 2     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| AMD       | Turion X2 Ultra Dual-Core M... | 9200     | 2     | 64K  | 64K  | 1024K |        | 2300    | AMD-V |
| AMD       | Turion X2 Ultra Dual-Core M... | 9200     | 2     | 64K  | 64K  | 1024K |        | 2300    | AMD-V |
| AMD       | TurionX2 Dual Core Mobile R... | 9200     | 2     | 128K | 128K | 1M    |        | 2300    | AMD-V |
| Intel     | Pentium G630T                  | 9198     | 2     | 32K  | 32K  | 256K  | 3072K  | 2300    | VT-x  |
| AMD       | PRO A6-9500B R5, 6 COMPUTE ... | 9186     | 2     | 32K  | 96K  | 1024K |        | 2300    | AMD-V |
| AMD       | Athlon Silver 3050U with Ra... | 9186     | 2     | 32K  | 64K  | 512K  | 4096K  | 2300    | AMD-V |
| Intel     | Pentium B970                   | 9186     | 2     | 32K  | 32K  | 256K  | 2048K  | 2300    |       |
| AMD       | A4-3330MX APU with Radeon H... | 9182     | 2     | 64K  | 64K  | 1024K |        | 2300    | AMD-V |
| Intel     | Pentium 3550M                  | 9182     | 2     | 32K  | 32K  | 256K  | 2048K  | 2300    | VT-x  |
| Intel     | Celeron G1610T                 | 9180     | 2     | 32K  | 32K  | 256K  | 2048K  | 2300    | VT-x  |
| AMD       | Athlon II P360 Dual-Core       | 9178     | 2     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| Intel     | Pentium G3320TE                | 9178     | 2     | 64K  | 64K  | 512K  | 3M     | 2300    | VT-x  |
| AMD       | Athlon X2 Dual Core BE-2400    | 9176     | 2     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| AMD       | Athlon II N330 Dual-Core       | 9176     | 2     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| Intel     | Core2 Duo P8400                | 9070     | 2     | 32K  | 32K  | 3072K |        | 2268    | VT-x  |
| Intel     | Core2 P8400                    | 9066     | 2     | 32K  | 32K  | 3072K |        | 2267    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 4200+   | 9064     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| Intel     | Core2 Duo P7550                | 9046     | 2     | 32K  | 32K  | 3072K |        | 2266    | VT-x  |
| Intel     | Core2 Duo P8400                | 9046     | 2     | 32K  | 32K  | 3072K |        | 2268    | VT-x  |
| Intel     | Pentium P6300                  | 9046     | 2     | 32K  | 32K  | 256K  | 3072K  | 2266    |       |
| Intel     | Core2 Duo P7570                | 9044     | 2     | 32K  | 32K  | 3072K |        | 2267    | VT-x  |
| Intel     | Core2 Duo P9300                | 9044     | 2     | 32K  | 32K  | 6144K |        | 2268    | VT-x  |
| Intel     | Core2 Duo P9300                | 9042     | 2     | 32K  | 32K  | 6144K |        | 2267    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 4400+   | 9020     | 2     | 64K  | 64K  | 1024K |        | 2200    |       |
| Intel     | Core2 6420                     | 8958     | 2     | 32K  | 32K  | 4096K |        | 2136    | VT-x  |
| Intel     | Pentium Silver N6000           | 8908     | 4     | 128K | 128K | 1.5M  | 4M     | 3300    | VT-x  |
| Intel     | Celeron E1500                  | 8876     | 2     | 32K  | 32K  | 512K  |        | 2203    |       |
| AMD       | Athlon 64 X2 Dual Core 4200+   | 8844     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | Turion 64 X2 Mobile Technol... | 8840     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | Athlon 5000 Dual-Core          | 8840     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 4200+   | 8838     | 2     | 64K  | 64K  | 512K  |        | 2200    |       |
| Intel     | Celeron 3965U                  | 8832     | 2     | 32K  | 32K  | 256K  | 2048K  | 2200    | VT-x  |
| Intel     | Pentium Dual E2160             | 8810     | 2     | 32K  | 32K  | 1024K |        | 1900    |       |
| AMD       | Turion II Dual-Core Mobile ... | 8802     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | AthlonX2 DualCore QL-66        | 8802     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | Turion X2 Dual-Core Mobile ... | 8802     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | TurionX2 Dual Core Mobile R... | 8802     | 2     | 128K | 128K | 1M    |        | 2200    | AMD-V |
| Intel     | Core2 Duo T5900                | 8802     | 2     | 32K  | 32K  | 2048K |        | 2200    |       |
| Intel     | Pentium Dual-Core T4400        | 8802     | 2     | 32K  | 32K  | 1024K |        | 2200    |       |
| AMD       | Dual-Core Opteron 1214         | 8800     | 2     | 64K  | 64K  | 1024K |        | 2200    | AMD-V |
| AMD       | Athlon II Dual-Core M340       | 8800     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | Athlon II P340 Dual-Core       | 8800     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | Turion X2 Dual-Core Mobile ... | 8800     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | Turion X2 Ultra Dual-Core M... | 8800     | 2     | 64K  | 64K  | 1024K |        | 2200    | AMD-V |
| Intel     | Core2 Duo T7500                | 8800     | 2     | 32K  | 32K  | 4096K |        | 2201    | VT-x  |
| Intel     | Core2 Duo T7500                | 8800     | 2     | 32K  | 32K  | 4096K |        | 2201    | VT-x  |
| Intel     | Core2 Duo T6670                | 8800     | 2     | 32K  | 32K  | 2048K |        | 2201    | VT-x  |
| Intel     | Pentium Dual-Core E2210        | 8798     | 2     | 32K  | 32K  | 1024K |        | 2203    |       |
| Intel     | Pentium N4200                  | 8792     | 4     | 24K  | 32K  | 1024K |        | 2500    | VT-x  |
| Intel     | Pentium B960                   | 8790     | 2     | 32K  | 32K  | 256K  | 2048K  | 2200    |       |
| Intel     | Celeron N3450                  | 8788     | 4     | 24K  | 32K  | 1024K |        | 2200    | VT-x  |
| AMD       | A4-9120 RADEON R3, 4 COMPUT... | 8786     | 2     | 32K  | 64K  | 1024K |        | 2200    | AMD-V |
| AMD       | A6-7000 Radeon R4, 5 Comput... | 8786     | 2     | 16K  | 96K  | 1M    |        | 2200    | AMD-V |
| AMD       | Turion II Neo N54L Dual-Core   | 8784     | 2     | 64K  | 64K  | 1024K |        | 2200    | AMD-V |
| AMD       | A8-7050 Radeon R5, 6 Comput... | 8784     | 2     | 16K  | 64K  | 1024K |        | 2200    | AMD-V |
| AMD       | A6 PRO-7050B R4, 5 Compute ... | 8782     | 2     | 16K  | 96K  | 1024K |        | 2200    | AMD-V |
| AMD       | GX-222GC SOC with Radeon R5... | 8782     | 2     | 32K  | 32K  | 1024K |        | 2200    | AMD-V |
| Intel     | Pentium G620T                  | 8780     | 2     | 32K  | 32K  | 256K  | 3072K  | 2200    | VT-x  |
| Intel     | Celeron 2970M                  | 8780     | 2     | 32K  | 32K  | 256K  | 2048K  | 2200    | VT-x  |
| Intel     | Core2 T6670                    | 8778     | 2     | 32K  | 32K  | 2048K |        | 2201    | VT-x  |
| Intel     | Core M-5Y31                    | 8776     | 4     | 32K  | 32K  | 256K  | 4096K  | 2400    | VT-x  |
| Intel     | Celeron N4100                  | 8756     | 4     | 24K  | 32K  | 4096K |        | 2400    | VT-x  |
| Intel     | Pentium Silver N5000           | 8756     | 4     | 24K  | 32K  | 4096K |        | 2700    | VT-x  |
| Intel     | Celeron N4120                  | 8756     | 4     | 96K  | 128K | 4M    |        | 2600    | VT-x  |
| Intel     | Pentium Silver N5030           | 8752     | 4     | 24K  | 32K  | 4096K |        | 3100    | VT-x  |
| Intel     | Pentium N4200                  | 8752     | 4     | 96K  | 128K | 2M    |        | 2500    | VT-x  |
| Intel     | Celeron N2830                  | 8686     | 2     | 24K  | 32K  | 1024K |        | 2415    | VT-x  |
| Intel     | Celeron N2840                  | 8684     | 2     | 24K  | 32K  | 1024K |        | 2582    | VT-x  |
| Intel     | Pentium Dual T3400             | 8670     | 2     | 32K  | 32K  | 1024K |        | 2167    |       |
| Intel     | Core2 T7400                    | 8670     | 2     | 32K  | 32K  | 4096K |        | 2167    | VT-x  |
| Intel     | Core2 Duo T5850                | 8668     | 2     | 32K  | 32K  | 2048K |        | 2167    |       |
| Intel     | 1600                           | 8654     | 2     | 32K  | 32K  | 2048K |        | 2167    | VT-x  |
| Intel     | T2600                          | 8654     | 2     | 32K  | 32K  | 2048K |        | 2167    | VT-x  |
| Intel     | Core Duo T2600                 | 8644     | 2     | 32K  | 32K  | 2048K |        | 2167    | VT-x  |
| Intel     | Atom D425                      | 8642     | 2     | 24K  | 32K  | 512K  |        |         |       |
| ARM       | Cortex-A72                     | 8640     | 16    | 128K | 192K | 1M    | 8M     | 2594    |       |
| Intel     | Pentium P6200                  | 8574     | 2     | 32K  | 32K  | 256K  | 3072K  | 2133    |       |
| Intel     | Core2 Duo P7450                | 8536     | 2     | 32K  | 32K  | 3072K |        | 2133    | VT-x  |
| Intel     | Celeron N2820                  | 8536     | 2     | 24K  | 32K  | 1024K |        | 2399    | VT-x  |
| Intel     | Core2 Duo L9600                | 8534     | 2     | 32K  | 32K  | 6144K |        | 2134    | VT-x  |
| Intel     | Xeon 3050                      | 8532     | 2     | 32K  | 32K  | 2048K |        | 2128    | VT-x  |
| Intel     | Xeon 3050                      | 8532     | 2     | 32K  | 32K  | 2048K |        | 2128    | VT-x  |
| Intel     | Core2 Duo P7450                | 8532     | 2     | 32K  | 32K  | 3072K |        | 2133    |       |
| Intel     | Core2 Duo E6400                | 8512     | 2     | 32K  | 32K  | 2048K |        | 2133    | VT-x  |
| Intel     | Core i5 U 520                  | 8512     | 4     | 32K  | 32K  | 256K  | 3072K  | 1067    | VT-x  |
| Intel     | Core i7 U 620                  | 8512     | 4     | 32K  | 32K  | 256K  | 4096K  | 1067    | VT-x  |
| AMD       | Athlon X2 Dual Core BE-2350    | 8438     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| AMD       | Athlon Dual Core 4050e         | 8438     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| Intel     | Core2 Duo T8100                | 8430     | 2     | 32K  | 32K  | 3072K |        | 13794   | VT-x  |
| AMD       | A6-4455M APU with Radeon HD... | 8428     | 2     | 16K  | 64K  | 2048K |        | 2100    | AMD-V |
| AMD       | Athlon X2 Dual-Core QL-65      | 8404     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| Intel     | Pentium Dual-Core T4300        | 8404     | 2     | 32K  | 32K  | 1024K |        | 2100    |       |
| AMD       | Athlon 64 X2 Dual Core 3600+   | 8402     | 2     | 64K  | 64K  | 256K  |        | 2000    | AMD-V |
| AMD       | Athlon II Dual-Core M320       | 8402     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| AMD       | Athlon X2 Dual-Core QL-64      | 8402     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| AMD       | AthlonX2 DualCore QL-64        | 8402     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| AMD       | Turion X2 Dual-Core Mobile ... | 8402     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| AMD       | Turion X2 Ultra Dual-Core M... | 8402     | 2     | 64K  | 64K  | 1024K |        | 2100    | AMD-V |
| Intel     | Pentium B950                   | 8402     | 2     | 32K  | 32K  | 256K  | 2048K  | 2100    |       |
| AMD       | Athlon II P320 Dual-Core       | 8400     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| AMD       | Turion Dual-Core RM-72         | 8400     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| Intel     | Core2 Duo T6500                | 8400     | 2     | 32K  | 32K  | 2048K |        | 2100    |       |
| Intel     | Core2 Duo T6570                | 8400     | 2     | 32K  | 32K  | 2048K |        | 2101    | VT-x  |
| AMD       | Athlon Dual-Core QL-64         | 8398     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| AMD       | Athlon Dual-Core QL-65         | 8398     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| AMD       | A4-3310MX APU with Radeon H... | 8388     | 2     | 64K  | 64K  | 1024K |        | 2100    | AMD-V |
| Intel     | Celeron Dual-Core T3500        | 8382     | 2     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Pentium P6100                  | 8382     | 2     | 32K  | 32K  | 256K  | 3072K  | 2000    |       |
| Intel     | Pentium A1018                  | 8380     | 2     | 32K  | 32K  | 256K  | 1024K  | 2100    |       |
| AMD       | Turion 64 X2 Mobile Technol... | 8378     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| AMD       | Athlon X2 Dual Core BE-2350    | 8378     | 2     | 64K  | 64K  | 512K  |        | 2100    | AMD-V |
| Intel     | Pentium T4300                  | 8378     | 2     | 32K  | 32K  | 1024K |        | 2000    |       |
| Intel     | Atom x5-E8000                  | 8320     | 4     | 96K  | 128K | 2M    |        | 2000    | VT-x  |
| AMD       | Athlon 64 X2 Dual Core 3800+   | 8118     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| Intel     | Celeron E1400                  | 8066     | 2     | 32K  | 32K  | 512K  |        | 2003    |       |
| AMD       | Athlon 64 X2 Dual Core 3800+   | 8040     | 2     | 64K  | 64K  | 512K  |        | 2000    |       |
| AMD       | Athlon 64 X2 Dual Core 3800+   | 8040     | 2     | 64K  | 64K  | 512K  |        | 2000    |       |
| AMD       | Athlon 64 X2 Dual Core 3800+   | 8040     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 3800+   | 8040     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 3600+   | 8038     | 2     |      |      |       |        |         |       |
| AMD       | Turion 64 X2 Mobile Technol... | 8036     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | Turion 64 X2 Mobile Technol... | 8036     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | Sempron Dual Core 2200         | 8036     | 2     | 64K  | 64K  | 256K  |        | 2000    |       |
| AMD       | Athlon64 X2 Dual Core 3800+    | 8036     | 2     | 64K  | 64K  | 512K  |        | 2000    |       |
| Intel     | Core2 Duo T5750                | 8034     | 2     | 32K  | 32K  | 2048K |        | 2000    |       |
| Intel     | Core2 T7200                    | 8026     | 2     | 32K  | 32K  | 4096K |        | 2000    | VT-x  |
| Intel     | Celeron J3355                  | 8016     | 2     | 24K  | 32K  | 1024K |        | 2500    | VT-x  |
| AMD       | Athlon Dual-Core QL-62         | 8002     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | Athlon X2 Dual-Core QL-62      | 8002     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | Turion Dual-Core RM-70         | 8002     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | Turion X2 Dual-Core Mobile ... | 8002     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| Intel     | T2500                          | 8002     | 2     | 32K  | 32K  | 2048K |        | 2000    | VT-x  |
| Intel     | Core2 Duo T7300                | 8002     | 2     | 32K  | 32K  | 4096K |        | 2001    | VT-x  |
| Intel     | Core2 Duo T7300                | 8002     | 2     | 32K  | 32K  | 4096K |        | 2001    | VT-x  |
| Intel     | Pentium Dual T3200             | 8002     | 2     | 32K  | 32K  | 1024K |        | 2000    |       |
| Intel     | Pentium Dual-Core T4200        | 8002     | 2     | 32K  | 32K  | 1024K |        | 2000    |       |
| Intel     | Celeron 3955U                  | 8002     | 2     | 64K  | 64K  | 512K  | 2M     | 2000    | VT-x  |
| AMD       | Turion 64 X2 Mobile Technol... | 8000     | 2     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| AMD       | Turion 64 X2 TL-60             | 8000     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | Dual-Core Opteron 2212 HE      | 8000     | 2     | 256K | 256K | 4M    |        | 2000    | AMD-V |
| AMD       | Dual-Core Opteron 1212         | 8000     | 2     | 64K  | 64K  | 1024K |        | 2000    | AMD-V |
| AMD       | Athlon II Dual-Core M300       | 8000     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | TurionX2 Dual Core Mobile R... | 8000     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| Intel     | Core Duo T2450                 | 8000     | 2     | 32K  | 32K  | 2048K |        | 2000    |       |
| Intel     | Core2 Duo T5800                | 8000     | 2     | 32K  | 32K  | 2048K |        | 2000    |       |
| Intel     | Core2 Duo T7250                | 8000     | 2     | 32K  | 32K  | 2048K |        | 2001    | VT-x  |
| Intel     | Pentium Dual T2410             | 8000     | 2     | 32K  | 32K  | 1024K |        | 2000    |       |
| Intel     | Celeron Dual-Core T3300        | 8000     | 2     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Core2 Duo T6400                | 8000     | 2     | 32K  | 32K  | 2048K |        | 2000    |       |
| Intel     | Core2 Duo P7350                | 8000     | 2     | 32K  | 32K  | 3072K |        | 2000    | VT-x  |
| Intel     | Celeron P4600                  | 8000     | 2     | 32K  | 32K  | 256K  | 2048K  | 1999    | VT-x  |
| Intel     | Celeron N2810                  | 8000     | 2     | 24K  | 32K  | 1024K |        | 1999    | VT-x  |
| Intel     | Atom Z550                      | 7998     | 2     | 24K  | 32K  | 512K  |        | 2000    | VT-x  |
| Intel     | Core2 Duo P7370                | 7996     | 2     | 32K  | 32K  | 3072K |        | 2001    | VT-x  |
| Intel     | Celeron J4005                  | 7990     | 2     | 24K  | 32K  | 4096K |        | 2700    | VT-x  |
| AMD       | A6-9200 RADEON R4, 5 COMPUT... | 7988     | 2     | 32K  | 64K  | 1024K |        | 2000    | AMD-V |
| AMD       | E2-9010 RADEON R2, 4 COMPUT... | 7988     | 2     | 32K  | 64K  | 1024K |        | 2000    | AMD-V |
| AMD       | A6-1450 APU with Radeon HD ... | 7988     | 4     | 32K  | 32K  | 2048K |        | 1000    | AMD-V |
| AMD       | A4 Micro-6400T APU + AMD Ra... | 7988     | 4     | 128K | 128K | 2M    |        | 1000    | AMD-V |
| Intel     | Pentium B940                   | 7988     | 2     | 32K  | 32K  | 256K  | 2048K  | 2000    |       |
| AMD       | A4-3320M APU with Radeon HD... | 7986     | 2     | 64K  | 64K  | 1024K |        | 2000    | AMD-V |
| Intel     | Celeron J4025                  | 7986     | 2     | 24K  | 32K  | 4096K |        | 2900    | VT-x  |
| AMD       | E2-9030 RADEON R2, 4 COMPUT... | 7984     | 2     | 32K  | 64K  | 1024K |        | 2000    | AMD-V |
| AMD       | Quad-Core (up to 1.4GHz)       | 7984     | 4     | 32K  | 32K  | 2048K |        | 1000    | AMD-V |
| AMD       | GX-412TC SOC                   | 7984     | 4     | 128K | 128K | 2M    |        | 1000    | AMD-V |
| Intel     | Celeron 2950M                  | 7984     | 2     | 64K  | 64K  | 512K  | 2M     | 2000    | VT-x  |
| Intel     | 5Y10a                          | 7984     | 4     | 64K  | 64K  | 512K  | 4M     | 2000    | VT-x  |
| Intel     | Core M-5Y10c                   | 7984     | 4     | 32K  | 32K  | 256K  | 4096K  | 2000    | VT-x  |
| Intel     | Core2 Duo T5870                | 7982     | 2     | 32K  | 32K  | 2048K |        | 2001    |       |
| Intel     | Core Duo T2500                 | 7980     | 2     | 32K  | 32K  | 2048K |        | 2000    | VT-x  |
| Intel     | Xeon 5130                      | 7980     | 2     | 32K  | 32K  | 4096K |        |         | VT-x  |
| Intel     | Celeron G530T                  | 7980     | 2     | 32K  | 32K  | 256K  | 2048K  | 2000    | VT-x  |
| Intel     | 5Y10                           | 7980     | 4     | 32K  | 32K  | 256K  | 4096K  | 2000    | VT-x  |
| AMD       | Dual-Core Opteron 1212         | 7978     | 2     | 64K  | 64K  | 1024K |        | 2000    | AMD-V |
| Intel     | Xeon 5130                      | 7978     | 2     | 32K  | 32K  | 4096K |        |         | VT-x  |
| Intel     | Xeon E5503                     | 7978     | 2     | 32K  | 32K  | 256K  | 4096K  |         | VT-x  |
| ARM       | Cortex-A9                      | 7972     | 4     |      |      |       |        | 1300    |       |
| Intel     | Core2 Duo P7350                | 7962     | 2     | 32K  | 32K  | 3072K |        | 1995    | VT-x  |
| Intel     | Pentium P6000                  | 7672     | 2     | 32K  | 32K  | 256K  | 3072K  | 1866    |       |
| AMD       | Athlon 64 X2 Dual Core 3600+   | 7638     | 2     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| AMD       | Athlon X2 Dual Core BE-2300    | 7634     | 2     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| Intel     | Pentium 3805U                  | 7608     | 2     | 32K  | 32K  | 256K  | 2048K  | 1900    | VT-x  |
| AMD       | Athlon Dual-Core QL-60         | 7602     | 2     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| AMD       | Athlon X2 Dual-Core QL-60      | 7602     | 2     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| AMD       | AthlonX2 DualCore QL-60        | 7602     | 2     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| AMD       | Athlon 64 X2 Dual-Core TK-57   | 7600     | 2     | 64K  | 64K  | 256K  |        | 1900    | AMD-V |
| AMD       | Turion 64 X2 Mobile Technol... | 7600     | 2     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| AMD       | Turion 64 X2 TL-58             | 7600     | 2     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| AMD       | Athlon X2 Dual Core BE-2300    | 7600     | 2     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| Intel     | Celeron Dual-Core T3100        | 7600     | 2     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Celeron G465                   | 7600     | 2     | 32K  | 32K  | 256K  | 1.5M   | 1900    | VT-x  |
| Intel     | Celeron 5205U                  | 7598     | 2     | 32K  | 32K  | 256K  | 2048K  | 1900    | VT-x  |
| Intel     | Celeron 5205U                  | 7598     | 2     | 32K  | 32K  | 256K  | 2048K  | 1900    | VT-x  |
| Intel     | Celeron 1005M                  | 7592     | 2     | 32K  | 32K  | 256K  | 2048K  | 1900    | VT-x  |
| Intel     | Pentium 2127U                  | 7590     | 2     | 32K  | 32K  | 256K  | 2048K  | 1900    | VT-x  |
| AMD       | A4-3300M APU with Radeon HD... | 7588     | 2     | 64K  | 64K  | 1024K |        | 1900    | AMD-V |
| AMD       | A4-3305M APU with Radeon HD... | 7588     | 2     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| AMD       | A4-4355M APU with Radeon HD... | 7588     | 2     | 16K  | 64K  | 1024K |        | 1900    | AMD-V |
| Intel     | Celeron B840                   | 7582     | 2     | 32K  | 32K  | 256K  | 2048K  | 1900    | VT-x  |
| Intel     | Core2 6300                     | 7502     | 2     | 32K  | 32K  | 2048K |        | 1870    | VT-x  |
| Intel     | Core2 6320                     | 7478     | 2     | 32K  | 32K  | 4096K |        | 1870    | VT-x  |
| Intel     | Pentium Dual T2390             | 7470     | 2     | 32K  | 32K  | 1024K |        | 1867    |       |
| Intel     | T2130                          | 7468     | 2     | 32K  | 32K  | 1024K |        | 1867    |       |
| Intel     | Celeron N2815                  | 7468     | 2     | 24K  | 32K  | 1024K |        | 2132    | VT-x  |
| Intel     | Core Duo T2350                 | 7466     | 2     | 32K  | 32K  | 2048K |        | 1867    |       |
| Intel     | Core2 Duo L9400                | 7466     | 2     | 32K  | 32K  | 6144K |        | 1868    | VT-x  |
| Intel     | Xeon E5502                     | 7466     | 2     | 32K  | 32K  | 256K  | 4096K  | 1862    | VT-x  |
| Intel     | Atom D2500                     | 7466     | 2     | 24K  | 32K  | 512K  |        |         |       |
| Intel     | Atom Z540                      | 7464     | 2     | 24K  | 32K  | 512K  |        | 1866    | VT-x  |
| Intel     | T1500                          | 7450     | 2     | 32K  | 32K  | 512K  |        |         |       |
| Intel     | Xeon 5120                      | 7450     | 2     | 32K  | 32K  | 4096K |        |         | VT-x  |
| Intel     | Core2 Duo L9400                | 7450     | 2     | 32K  | 32K  | 6144K |        | 1867    | VT-x  |
| Intel     | Xeon 3040                      | 7448     | 2     | 64K  | 64K  | 2M    |        | 1867    | VT-x  |
| Intel     | Celeron P4500                  | 7448     | 2     | 32K  | 32K  | 256K  | 2048K  | 1866    | VT-x  |
| Intel     | Celeron P4500                  | 7446     | 2     | 32K  | 32K  | 256K  | 2048K  | 1866    | VT-x  |
| Intel     | Atom N455                      | 7346     | 2     | 24K  | 32K  | 512K  |        | 1667    |       |
| Intel     | Core2 T5600                    | 7336     | 2     | 32K  | 32K  | 2048K |        | 1833    | VT-x  |
| Intel     | Core2 Duo T5550                | 7334     | 2     | 32K  | 32K  | 2048K |        | 1833    |       |
| Intel     | T2400                          | 7332     | 2     | 32K  | 32K  | 2048K |        | 1833    | VT-x  |
| Intel     | Core2 T5600                    | 7332     | 2     | 32K  | 32K  | 2048K |        | 1833    | VT-x  |
| Intel     | Atom N475                      | 7318     | 2     | 24K  | 32K  | 512K  |        | 1833    |       |
| Intel     | T1700                          | 7316     | 2     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Atom N470                      | 7316     | 2     | 24K  | 32K  | 512K  |        | 1834    |       |
| Intel     | Core Duo T2400                 | 7314     | 2     | 32K  | 32K  | 2048K |        | 1833    | VT-x  |
| AMD       | Athlon 64 X2 Dual-Core TK-55   | 7232     | 2     | 64K  | 64K  | 256K  |        | 1800    | AMD-V |
| AMD       | Turion 64 X2 Mobile Technol... | 7232     | 2     | 64K  | 64K  | 512K  |        | 1800    | AMD-V |
| AMD       | E2-9000 RADEON R2, 4 COMPUT... | 7202     | 2     | 32K  | 64K  | 1024K |        | 1800    | AMD-V |
| Intel     | Celeron 4205U                  | 7202     | 2     | 32K  | 32K  | 256K  | 2048K  | 1800    | VT-x  |
| Intel     | Celeron 4205U                  | 7202     | 2     | 64K  | 64K  | 512K  | 2M     | 1800    | VT-x  |
| Intel     | Celeron 3865U                  | 7202     | 2     | 64K  | 64K  | 512K  | 2M     | 1800    | VT-x  |
| Intel     | Celeron Dual-Core T3000        | 7202     | 2     | 32K  | 32K  | 1024K |        |         |       |
| AMD       | Turion 64 X2 Mobile Technol... | 7200     | 2     | 64K  | 64K  | 512K  |        | 1800    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 3400+   | 7200     | 2     | 64K  | 64K  | 512K  |        |         | AMD-V |
| Intel     | Celeron 3867U                  | 7200     | 2     | 64K  | 64K  | 512K  | 2M     | 1800    | VT-x  |
| Intel     | Pentium Dual E2160             | 7200     | 2     | 64K  | 64K  | 1M    |        | 1800    |       |
| AMD       | Athlon 64 X2 Dual-Core TK-55   | 7198     | 2     | 64K  | 64K  | 256K  |        | 1800    | AMD-V |
| AMD       | Athlon II X2 260u              | 7198     | 2     | 128K | 128K | 2M    |        | 1800    | AMD-V |
| Intel     | Celeron 1037U                  | 7198     | 2     | 32K  | 32K  | 256K  | 2048K  | 1800    | VT-x  |
| Intel     | Celeron B830                   | 7194     | 2     | 32K  | 32K  | 256K  | 2048K  | 1800    | VT-x  |
| Intel     | Celeron 1000M                  | 7194     | 2     | 32K  | 32K  | 256K  | 2048K  | 1800    | VT-x  |
| Intel     | Pentium 2117U                  | 7194     | 2     | 32K  | 32K  | 256K  | 2048K  | 1800    | VT-x  |
| AMD       | A9-9420e RADEON R5, 5 COMPU... | 7190     | 2     | 32K  | 64K  | 1024K |        | 1800    | AMD-V |
| AMD       | E2-3000M APU with Radeon HD... | 7188     | 2     | 64K  | 64K  | 512K  |        | 1800    | AMD-V |
| AMD       | A6-9220C RADEON R5, 5 COMPU... | 7186     | 2     | 32K  | 64K  | 1024K |        | 1800    | AMD-V |
| Intel     | Celeron G460                   | 7186     | 2     | 32K  | 32K  | 256K  | 1536K  | 1800    | VT-x  |
| AMD       | Athlon Neo X2 Dual Core 6850e  | 7184     | 2     | 64K  | 64K  | 512K  |        | 1800    | AMD-V |
| Intel     | Core2 Duo L7700                | 7184     | 2     | 32K  | 32K  | 4096K |        | 1801    | VT-x  |
| Intel     | Core2 Duo T5670                | 7184     | 2     | 32K  | 32K  | 2048K |        | 1801    |       |
| Intel     | Core2 Duo T7100                | 7184     | 2     | 32K  | 32K  | 2048K |        | 1801    | VT-x  |
| Intel     | Core2 Duo P7700                | 7182     | 2     | 32K  | 32K  | 4096K |        | 1800    | VT-x  |
| Intel     | Atom N270                      | 7142     | 2     | 24K  | 32K  | 512K  |        | 1600    |       |
| AMD       | E2-2000 APU with Radeon HD ... | 7000     | 2     | 32K  | 32K  | 512K  |        | 1750    | AMD-V |
| Intel     | Celeron D                      | 6966     | 1     | 16K  |      | 512K  |        |         |       |
| Intel     | Pentium Dual T2370             | 6936     | 2     | 32K  | 32K  | 1024K |        | 1733    |       |
| Intel     | Core Duo T2250                 | 6934     | 2     | 32K  | 32K  | 2048K |        | 1735    |       |
| Intel     | Core2 T5300                    | 6934     | 2     | 32K  | 32K  | 2048K |        | 1733    |       |
| Intel     | U7300                          | 6934     | 2     | 32K  | 32K  | 3072K |        | 1733    | VT-x  |
| Intel     | T2080                          | 6932     | 2     | 32K  | 32K  | 1024K |        | 1735    |       |
| Intel     | T2250                          | 6932     | 2     | 32K  | 32K  | 2048K |        | 1733    |       |
| Intel     | T1400                          | 6932     | 2     | 32K  | 32K  | 512K  |        |         |       |
| Intel     | U4100                          | 6932     | 2     | 32K  | 32K  | 2048K |        | 1733    |       |
| Intel     | Atom N450                      | 6850     | 2     | 24K  | 32K  | 512K  |        | 1670    |       |
| Intel     | Pentium 3556U                  | 6802     | 2     | 32K  | 32K  | 256K  | 2048K  | 1700    | VT-x  |
| AMD       | E2-1800 APU with Radeon HD ... | 6800     | 2     | 32K  | 32K  | 512K  |        | 1700    | AMD-V |
| Intel     | Celeron 3215U                  | 6800     | 2     | 32K  | 32K  | 256K  | 2048K  | 1700    | VT-x  |
| AMD       | E-450 APU with Radeon HD Gr... | 6796     | 2     | 32K  | 32K  | 512K  |        | 1650    | AMD-V |
| Intel     | Celeron B820                   | 6794     | 2     | 32K  | 32K  | 256K  | 2048K  | 1700    | VT-x  |
| Intel     | Celeron 2990U                  | 6786     | 2     | 64K  | 64K  | 512K  | 2M     | 1700    | VT-x  |
| Intel     | Pentium 3558U                  | 6786     | 2     | 32K  | 32K  | 256K  | 2048K  | 1700    | VT-x  |
| AMD       | Sempron 140                    | 6750     | 1     | 64K  | 64K  | 1024K |        | 2700    | AMD-V |
| Intel     | Celeron                        | 6721     | 1     | 16K  |      | 256K  |        | 3067    |       |
| Intel     | Core2 T5500                    | 6690     | 2     | 32K  | 32K  | 2048K |        | 1667    |       |
| Intel     | T2300                          | 6688     | 2     | 32K  | 32K  | 2048K |        | 1667    | VT-x  |
| Intel     | Core2 Duo T5450                | 6670     | 2     | 32K  | 32K  | 2048K |        | 1667    |       |
| Intel     | Atom D410                      | 6668     | 2     | 24K  | 32K  | 512K  |        |         |       |
| Intel     | Atom N280                      | 6668     | 2     | 24K  | 32K  | 512K  |        | 1667    |       |
| Intel     | Core Duo L2400                 | 6666     | 2     | 32K  | 32K  | 2048K |        | 1667    | VT-x  |
| Intel     | T1600                          | 6666     | 2     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Core2 T5500                    | 6666     | 2     | 32K  | 32K  | 2048K |        | 1667    | VT-x  |
| Intel     | Core Duo T2300                 | 6652     | 2     | 32K  | 32K  | 2048K |        | 1667    |       |
| AMD       | G-T56N                         | 6602     | 2     | 32K  | 32K  | 512K  |        | 1650    | AMD-V |
| AMD       | E2-3000 APU with Radeon HD ... | 6590     | 2     | 32K  | 32K  | 1024K |        | 1650    | AMD-V |
| AMD       | GX-217GA SOC with Radeon HD... | 6586     | 2     | 32K  | 32K  | 1024K |        | 1650    | AMD-V |
| Intel     | Celeron E1200                  | 6452     | 2     | 32K  | 32K  | 512K  |        | 1603    |       |
| Intel     | Pentium Dual T2330             | 6444     | 2     | 32K  | 32K  | 1024K |        | 1600    |       |
| Intel     | Celeron 3855U                  | 6434     | 2     | 32K  | 32K  | 256K  | 2048K  | 1600    | VT-x  |
| Intel     | Pentium Dual E2140             | 6432     | 2     | 32K  | 32K  | 1024K |        | 2133    |       |
| Intel     | 2140                           | 6432     | 2     | 32K  | 32K  | 1024K |        | 1603    |       |
| AMD       | Turion 64 X2 Mobile Technol... | 6428     | 2     | 64K  | 64K  | 256K  |        | 1600    | AMD-V |
| AMD       | Turion 64 X2 Mobile Technol... | 6428     | 2     | 64K  | 64K  | 512K  |        | 1600    | AMD-V |
| AMD       | Athlon II X2 250u              | 6428     | 2     | 64K  | 64K  | 1024K |        | 1600    | AMD-V |
| Intel     | Celeron N3050                  | 6424     | 2     | 24K  | 32K  | 1024K |        | 2249    | VT-x  |
| Intel     | Celeron J3060                  | 6422     | 2     | 24K  | 32K  | 1024K |        | 2582    | VT-x  |
| Intel     | Celeron N3060                  | 6422     | 2     | 24K  | 32K  | 1024K |        | 2582    | VT-x  |
| Intel     | Celeron                        | 6406     | 1     | 16K  |      | 256K  |        | 3067    |       |
| AMD       | Turion Neo X2 Dual Core L625   | 6402     | 2     | 64K  | 64K  | 512K  |        | 1600    | AMD-V |
| AMD       | E-350                          | 6402     | 2     | 32K  | 32K  | 512K  |        | 1600    | AMD-V |
| AMD       | E-350D APU with Radeon HD G... | 6402     | 2     | 32K  | 32K  | 512K  |        | 1600    | AMD-V |
| Intel     | Core2 T5200                    | 6402     | 2     | 32K  | 32K  | 2048K |        | 1600    |       |
| Intel     | Atom 230                       | 6402     | 2     | 24K  | 32K  | 512K  |        |         |       |
| Intel     | Atom Z530                      | 6402     | 2     | 24K  | 32K  | 512K  |        | 1600    | VT-x  |
| Intel     | Celeron N2806                  | 6402     | 2     | 24K  | 32K  | 1024K |        | 1999    | VT-x  |
| Intel     | Celeron D                      | 6401     | 1     | 16K  |      | 512K  |        |         |       |
| AMD       | Turion 64 X2 TL-58             | 6400     | 2     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| Intel     | T2060                          | 6400     | 2     | 32K  | 32K  | 1024K |        | 1600    |       |
| Intel     | T2050                          | 6400     | 2     | 32K  | 32K  | 2048K |        | 1600    |       |
| Intel     | Pentium Dual E2140             | 6400     | 2     | 32K  | 32K  | 1024K |        | 1600    |       |
| Intel     | Core2 Duo T5470                | 6400     | 2     | 32K  | 32K  | 2048K |        | 1601    |       |
| Intel     | Core2 Duo L9300                | 6400     | 2     | 32K  | 32K  | 6144K |        | 1601    | VT-x  |
| Intel     | Celeron B815                   | 6394     | 2     | 32K  | 32K  | 256K  | 2048K  | 1600    | VT-x  |
| Intel     | Celeron 1017U                  | 6392     | 2     | 32K  | 32K  | 256K  | 2048K  | 1600    | VT-x  |
| AMD       | A6-9220e RADEON R4, 5 COMPU... | 6390     | 2     | 32K  | 64K  | 1024K |        | 1600    | AMD-V |
| AMD       | A4-9120C RADEON R4, 5 COMPU... | 6388     | 2     | 32K  | 64K  | 1024K |        | 1600    | AMD-V |
| AMD       | Opteron X3216 APU              | 6388     | 2     | 32K  | 96K  | 1024K |        | 1600    | AMD-V |
| AMD       | PRO A6-8500B R5, 6 Compute ... | 6388     | 2     | 32K  | 96K  | 1024K |        | 1600    | AMD-V |
| AMD       | E-350 APU with Radeon HD Gr... | 6386     | 2     | 32K  | 32K  | 512K  |        | 1600    | AMD-V |
| Intel     | Core2 Duo L7500                | 6386     | 2     | 32K  | 32K  | 4096K |        | 1601    | VT-x  |
| Intel     | Core2 Duo U9600                | 6386     | 2     | 32K  | 32K  | 3072K |        | 1601    | VT-x  |
| Intel     | Celeron B810                   | 6386     | 2     | 32K  | 32K  | 256K  | 2048K  | 1600    | VT-x  |
| Intel     | Atom N2100                     | 6386     | 2     | 24K  | 32K  | 512K  |        | 1600    |       |
| AMD       | Turion II Neo K645 Dual-Core   | 6384     | 2     | 128K | 128K | 2M    |        | 1600    | AMD-V |
| Intel     | Core2 Duo L7500                | 6384     | 2     | 32K  | 32K  | 4096K |        | 1601    | VT-x  |
| Intel     | Core2 Duo P7500                | 6384     | 2     | 32K  | 32K  | 4096K |        | 1600    | VT-x  |
| Intel     | Xeon 5110                      | 6384     | 2     | 32K  | 32K  | 4096K |        |         | VT-x  |
| Intel     | Xeon 5110                      | 6384     | 2     | 32K  | 32K  | 4096K |        |         | VT-x  |
| Intel     | Core2 Duo L9300                | 6384     | 2     | 32K  | 32K  | 6144K |        | 1601    | VT-x  |
| Intel     | 230                            | 6384     | 2     | 24K  | 32K  | 512K  |        |         |       |
| Intel     | N270                           | 6384     | 2     | 24K  | 32K  | 512K  |        | 1600    |       |
| Intel     | Pentium 997                    | 6384     | 2     | 32K  | 32K  | 256K  | 2048K  | 1600    |       |
| AMD       | Turion 64 X2 Mobile Technol... | 6376     | 2     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| Intel     | Celeron N2807                  | 6334     | 2     | 24K  | 32K  | 1024K |        | 2165    | VT-x  |
| Intel     | Celeron N2808                  | 6332     | 2     | 24K  | 32K  | 1024K |        | 2249    | VT-x  |
| Intel     | Celeron                        | 6319     | 1     | 16K  |      | 256K  |        | 2266    |       |
| AMD       | Opteron 4334                   | 6200     | 1     | 16K  | 64K  | 2048K | 6144K  |         |       |
| AMD       | Athlon X2 Dual Core 3250e      | 6000     | 2     | 64K  | 64K  | 512K  |        |         | AMD-V |
| Intel     | Core2 Duo T5250                | 6000     | 2     | 32K  | 32K  | 2048K |        | 1500    |       |
| Intel     | Celeron 1007U                  | 6000     | 2     | 32K  | 32K  | 256K  | 2048K  | 1500    | VT-x  |
| Intel     | Celeron 3965Y                  | 5998     | 2     | 64K  | 64K  | 512K  | 2M     | 1500    | VT-x  |
| Intel     | Atom Z670                      | 5998     | 2     | 24K  | 32K  | 512K  |        | 1500    |       |
| Intel     | Celeron B800                   | 5996     | 2     | 32K  | 32K  | 256K  | 2048K  | 1500    | VT-x  |
| Intel     | Pentium 987                    | 5994     | 2     | 32K  | 32K  | 256K  | 2048K  | 1500    |       |
| AMD       | Turion II Neo N40L Dual-Core   | 5990     | 2     | 64K  | 64K  | 1024K |        | 1500    | AMD-V |
| AMD       | A4-9120e RADEON R3, 4 COMPU... | 5990     | 2     | 32K  | 64K  | 1024K |        | 1500    | AMD-V |
| AMD       | E2-9000e RADEON R2, 4 COMPU... | 5990     | 2     | 32K  | 64K  | 1024K |        | 1500    | AMD-V |
| AMD       | E1-7010 APU with AMD Radeon... | 5990     | 2     | 32K  | 32K  | 1024K |        | 1500    | AMD-V |
| AMD       | Embedded G-Series GX-215JJ ... | 5988     | 2     | 64K  | 128K | 2M    |        | 1500    | AMD-V |
| AMD       | E2-7015 APU with AMD Radeon... | 5988     | 2     | 32K  | 32K  | 1024K |        | 1500    | AMD-V |
| Intel     | Celeron 3205U                  | 5988     | 2     | 32K  | 32K  | 256K  | 2048K  | 1500    | VT-x  |
| AMD       | Turion II Neo K625 Dual-Core   | 5986     | 2     | 128K | 128K | 2M    |        | 1500    | AMD-V |
| Intel     | Celeron 887                    | 5986     | 2     | 32K  | 32K  | 256K  | 2048K  | 1500    | VT-x  |
| Intel     | L2300                          | 5984     | 2     | 32K  | 32K  | 2048K |        | 1494    | VT-x  |
| Intel     | Core2 Duo L7400                | 5984     | 2     | 32K  | 32K  | 4096K |        | 1500    | VT-x  |
| AMD       | E1-1500 APU with Radeon HD ... | 5912     | 2     | 32K  | 32K  | 512K  |        | 1480    | AMD-V |
| Intel     | Pentium Dual T2310             | 5868     | 2     | 32K  | 32K  | 1024K |        | 1467    |       |
| Intel     | Celeron N2805                  | 5866     | 2     | 24K  | 32K  | 1024K |        | 1466    | VT-x  |
| Intel     | Atom E3826                     | 5864     | 2     | 24K  | 32K  | 512K  |        | 1466    | VT-x  |
| AMD       | Sempron 2650 APU with Radeo... | 5792     | 2     | 32K  | 32K  | 1024K |        | 1450    | AMD-V |
| Intel     | Celeron U3400                  | 5662     | 2     | 32K  | 32K  | 256K  | 2048K  | 1066    | VT-x  |
| AMD       | Sempron 145                    | 5639     | 1     | 64K  | 64K  | 1024K |        | 2800    | AMD-V |
| AMD       | Athlon LE-1660                 | 5626     | 1     | 64K  | 64K  | 512K  |        | 2800    | AMD-V |
| AMD       | G-T48E                         | 5602     | 2     | 32K  | 32K  | 512K  |        | 1400    | AMD-V |
| AMD       | E1-1200 APU with Radeon HD ... | 5600     | 2     | 32K  | 32K  | 512K  |        | 1400    | AMD-V |
| Intel     | Celeron 2957U                  | 5600     | 2     | 32K  | 32K  | 256K  | 2048K  | 1400    | VT-x  |
| Intel     | Celeron 2955U                  | 5596     | 2     | 32K  | 32K  | 256K  | 2048K  | 1400    | VT-x  |
| AMD       | E1-2500 APU with Radeon HD ... | 5592     | 2     | 32K  | 32K  | 1024K |        | 1400    | AMD-V |
| AMD       | E1-6015 APU with Radeon R2 ... | 5592     | 2     | 32K  | 32K  | 1024K |        | 1400    | AMD-V |
| Intel     | Core2 Duo U9400                | 5590     | 2     | 32K  | 32K  | 3072K |        | 1401    | VT-x  |
| AMD       | E1-6015 APU with Radeon HD ... | 5588     | 2     | 32K  | 32K  | 1024K |        | 1400    | AMD-V |
| Intel     | Core2 Duo L7300                | 5588     | 2     | 32K  | 32K  | 4096K |        | 1401    | VT-x  |
| Intel     | Core2 Duo T5270                | 5588     | 2     | 32K  | 32K  | 2048K |        | 1401    |       |
| Intel     | Core2 Duo U9400                | 5588     | 2     | 32K  | 32K  | 3072K |        | 1401    | VT-x  |
| Intel     | Celeron 877                    | 5588     | 2     | 32K  | 32K  | 256K  | 2048K  | 1400    | VT-x  |
| AMD       | Athlon II Neo K345 Dual-Core   | 5586     | 2     | 64K  | 64K  | 1024K |        | 1400    | AMD-V |
| Intel     | Celeron                        | 5586     | 1     |      |      |       |        |         |       |
| Intel     | Pentium 977                    | 5586     | 2     | 32K  | 32K  | 256K  | 2048K  | 1400    |       |
| AMD       | Opteron 254                    | 5585     | 1     | 64K  | 64K  | 1024K |        |         |       |
| AMD       | Athlon LE-1640                 | 5440     | 1     | 64K  | 64K  | 1024K |        | 2600    | AMD-V |
| AMD       | E1-6010 APU with AMD Radeon... | 5392     | 2     | 32K  | 32K  | 1024K |        | 1350    | AMD-V |
| AMD       | Athlon II Neo K325 Dual-Core   | 5358     | 2     | 64K  | 64K  | 1024K |        | 1300    | AMD-V |
| Intel     | Atom N435                      | 5334     | 2     | 24K  | 32K  | 512K  |        | 1334    |       |
| Intel     | Core2 Duo U7700                | 5332     | 2     | 32K  | 32K  | 2048K |        | 1333    | VT-x  |
| Intel     | Atom Z520                      | 5332     | 2     | 24K  | 32K  | 512K  |        | 1333    | VT-x  |
| Intel     | Atom E3805                     | 5328     | 2     | 24K  | 32K  | 512K  |        | 1333    | VT-x  |
| Intel     | Celeron                        | 5320     | 1     | 16K  |      | 256K  |        |         |       |
| Intel     | Core2 U7700                    | 5320     | 2     | 32K  | 32K  | 2048K |        | 1333    | VT-x  |
| Intel     | Pentium U5600                  | 5318     | 2     | 32K  | 32K  | 256K  | 3072K  | 1333    |       |
| AMD       | Athlon 64 3500+                | 5279     | 1     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | Sempron 130                    | 5223     | 1     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| AMD       | Sempron 130                    | 5210     | 1     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| AMD       | Athlon 64 4000+                | 5199     | 1     | 64K  | 64K  | 512K  |        | 2600    | AMD-V |
| AMD       | E-300 APU with Radeon HD Gr... | 5192     | 2     | 32K  | 32K  | 512K  |        | 1300    | AMD-V |
| AMD       | Athlon II Neo N36L Dual-Core   | 5190     | 2     | 64K  | 64K  | 1024K |        | 1300    | AMD-V |
| Intel     | Pentium 967                    | 5188     | 2     | 32K  | 32K  | 256K  | 2048K  | 1300    |       |
| Intel     | Celeron 867                    | 5184     | 2     | 32K  | 32K  | 256K  | 2048K  | 1300    | VT-x  |
| Intel     | Atom E3930                     | 5144     | 2     | 24K  | 32K  | 1024K |        | 1800    | VT-x  |
| AMD       | Athlon LE-1600                 | 5115     | 1     | 64K  | 64K  | 1024K |        | 2200    | AMD-V |
| Intel     | U2300                          | 5038     | 2     | 32K  | 32K  | 1024K |        |         | VT-x  |
| AMD       | Athlon 64 3000+                | 5000     | 1     | 64K  | 64K  | 512K  |        | 2000    |       |
| AMD       | Athlon 64 3200+                | 5000     | 1     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | Athlon 64 3200+                | 4999     | 1     | 64K  | 64K  | 512K  |        | 2000    |       |
| Intel     | Pentium 4                      | 4997     | 1     |      |      |       |        |         |       |
| Intel     | Mobile Intel Pentium 4 - M     | 4984     | 1     |      |      |       |        | 2500    |       |
| AMD       | Athlon 64 3800+                | 4826     | 1     | 64K  | 64K  | 512K  |        | 2400    |       |
| AMD       | Athlon 64 4000+                | 4824     | 1     | 64K  | 64K  | 1024K |        |         |       |
| AMD       | Athlon 64 3800+                | 4824     | 1     | 64K  | 64K  | 512K  |        | 2400    | AMD-V |
| AMD       | Athlon 64 3400+                | 4823     | 1     | 64K  | 64K  | 512K  |        |         |       |
| AMD       | Athlon 64 3800+                | 4822     | 1     | 64K  | 64K  | 512K  |        | 2400    | AMD-V |
| AMD       | Athlon LE-1620                 | 4822     | 1     | 64K  | 64K  | 1024K |        | 2400    | AMD-V |
| AMD       | Athlon 64 3400+                | 4821     | 1     |      |      |       |        | 2400    |       |
| AMD       | Athlon X2 Dual Core L310       | 4800     | 2     | 64K  | 64K  | 512K  |        |         | AMD-V |
| AMD       | V160                           | 4799     | 1     | 64K  | 64K  | 512K  |        | 2400    | AMD-V |
| AMD       | 3020e with Radeon Graphics     | 4792     | 2     | 64K  | 128K | 1M    | 4M     | 1200    | AMD-V |
| AMD       | GX-212JC SOC with Radeon R2... | 4790     | 2     | 32K  | 32K  | 1024K |        | 1200    | AMD-V |
| Intel     | U2500                          | 4790     | 2     | 32K  | 32K  | 2048K |        | 1200    | VT-x  |
| Intel     | Pentium U5400                  | 4790     | 2     | 32K  | 32K  | 256K  | 3072K  | 1199    |       |
| Intel     | Core Duo U2500                 | 4788     | 2     | 32K  | 32K  | 2048K |        | 1200    | VT-x  |
| Intel     | Core2 Duo L7100                | 4788     | 2     | 32K  | 32K  | 4096K |        | 1201    | VT-x  |
| Intel     | Core2 Duo U7600                | 4788     | 2     | 32K  | 32K  | 2048K |        | 1201    | VT-x  |
| Intel     | Core2 U7600                    | 4788     | 2     | 32K  | 32K  | 2048K |        | 1200    | VT-x  |
| Intel     | Core2 Duo U9300                | 4788     | 2     | 32K  | 32K  | 3072K |        | 1201    | VT-x  |
| Intel     | Celeron U3600                  | 4788     | 2     | 32K  | 32K  | 256K  | 2048K  | 1199    | VT-x  |
| Intel     | Celeron 857                    | 4788     | 2     | 64K  | 64K  | 512K  | 2M     | 1200    | VT-x  |
| AMD       | Opteron 250                    | 4787     | 1     | 64K  | 64K  | 1024K |        |         |       |
| Intel     | Core2 Duo U9300                | 4786     | 2     | 32K  | 32K  | 3072K |        | 1201    | VT-x  |
| AMD       | Sempron 3100+                  | 4680     | 1     | 64K  | 64K  | 256K  |        | 1800    |       |
| AMD       | Sempron LE-1300                | 4623     | 1     | 64K  | 64K  | 512K  |        | 2300    |       |
| AMD       | Sempron 2600+                  | 4607     | 1     | 64K  | 64K  | 128K  |        |         |       |
| AMD       | V140                           | 4601     | 1     | 64K  | 64K  | 512K  |        | 2300    | AMD-V |
| Intel     | Celeron 925                    | 4588     | 1     | 32K  | 32K  | 1024K |        | 15000   |       |
| Intel     | Celeron 570                    | 4533     | 1     | 32K  | 32K  | 1024K |        | 2267    |       |
| AMD       | Athlon XP                      | 4487     | 1     | 64K  | 64K  | 512K  |        |         |       |
| Intel     | Celeron 450                    | 4436     | 1     | 32K  | 32K  | 512K  |        |         |       |
| AMD       | Athlon 64 3700+                | 4432     | 1     | 64K  | 64K  | 1024K |        | 2200    |       |
| AMD       | Athlon 64 3500+                | 4422     | 1     | 64K  | 64K  | 512K  |        | 2200    |       |
| AMD       | Athlon 64 3500+                | 4422     | 1     | 64K  | 64K  | 512K  |        |         |       |
| AMD       | Athlon 64 3500+                | 4422     | 1     | 64K  | 64K  | 512K  |        | 2200    |       |
| AMD       | Athlon 64 3200+                | 4420     | 1     | 64K  | 64K  | 512K  |        | 2200    |       |
| AMD       | Sempron LE-1250                | 4420     | 1     | 64K  | 64K  | 512K  |        | 2200    |       |
| AMD       | Athlon 64 3200+                | 4420     | 1     | 64K  | 64K  | 512K  |        | 2200    |       |
| AMD       | Turion 64 Mobile Technology... | 4420     | 1     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | Athlon 64 3500+                | 4420     | 1     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | Athlon 64 3400+                | 4419     | 1     | 64K  | 64K  | 512K  |        | 2200    |       |
| AMD       | Mobile Athlon 64 3400+         | 4400     | 1     | 64K  | 64K  | 1024K |        | 2200    |       |
| AMD       | Athlon 64 3500+                | 4400     | 1     | 64K  | 64K  | 512K  |        | 2200    |       |
| AMD       | V120                           | 4400     | 1     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| Intel     | Celeron 900                    | 4400     | 1     | 32K  | 32K  | 1024K |        | 2200    |       |
| Intel     | Celeron 847                    | 4398     | 2     | 32K  | 32K  | 256K  | 2048K  | 1100    | VT-x  |
| Intel     | Celeron                        | 4394     | 1     |      |      |       |        |         |       |
| Intel     | Celeron 847E                   | 4394     | 2     | 32K  | 32K  | 256K  | 2048K  | 1100    | VT-x  |
| Intel     | Pentium 2129Y                  | 4390     | 2     | 32K  | 32K  | 256K  | 2048K  | 1100    | VT-x  |
| AMD       | Mobile Athlon 64 3400+         | 4388     | 1     | 64K  | 64K  | 1024K |        | 2200    |       |
| AMD       | Athlon XP 3200+                | 4388     | 1     | 64K  | 64K  | 512K  |        |         |       |
| Intel     | Celeron N3350                  | 4388     | 2     | 24K  | 32K  | 1024K |        | 2400    | VT-x  |
| AMD       | Turion 64 Mobile Technology... | 4387     | 1     | 64K  | 64K  | 1024K |        | 2200    |       |
| Intel     | Mobile Intel Pentium 4 - M     | 4382     | 1     |      |      |       |        |         |       |
| Intel     | Celeron N4000                  | 4378     | 2     | 24K  | 32K  | 4096K |        | 2600    | VT-x  |
| Intel     | Celeron N4020                  | 4378     | 2     | 48K  | 64K  | 4M    |        | 2800    | VT-x  |
| AMD       | Athlon 64 3400+                | 4377     | 1     | 64K  | 64K  | 512K  |        | 2200    |       |
| Intel     | Celeron N4000C                 | 4376     | 2     | 24K  | 32K  | 4096K |        | 2600    | VT-x  |
| Intel     | Celeron N3350                  | 4376     | 2     | 24K  | 32K  | 1024K |        | 2400    | VT-x  |
| AMD       | Athlon 64 3000+                | 4338     | 1     | 64K  | 64K  | 512K  |        | 1800    |       |
| Intel     | 585                            | 4335     | 1     | 32K  | 32K  | 1024K |        | 2167    |       |
| Intel     | Celeron 530                    | 4322     | 1     | 32K  | 32K  | 1024K |        | 1733    |       |
| Intel     | Celeron 430                    | 4320     | 1     | 32K  | 32K  | 512K  |        |         |       |
| AMD       | Athlon XP 3000+                | 4316     | 1     | 64K  | 64K  | 512K  |        |         |       |
| Intel     | Celeron 560                    | 4266     | 1     | 32K  | 32K  | 1024K |        | 2133    |       |
| Intel     | Pentium M                      | 4257     | 1     |      |      |       |        | 2267    |       |
| Intel     | Core Duo U2400                 | 4256     | 2     | 32K  | 32K  | 2048K |        | 1067    | VT-x  |
| Intel     | U2400                          | 4256     | 2     | 32K  | 32K  | 2048K |        | 1067    | VT-x  |
| Intel     | Core2 Duo U7500                | 4256     | 2     | 32K  | 32K  | 2048K |        | 1068    | VT-x  |
| Intel     | Core2 U7500                    | 4256     | 2     | 32K  | 32K  | 2048K |        | 1067    | VT-x  |
| AMD       | Sempron 2800+                  | 4239     | 1     | 64K  | 64K  | 256K  |        |         |       |
| AMD       | Sempron LE-1200                | 4219     | 1     | 64K  | 64K  | 512K  |        | 2100    |       |
| AMD       | Athlon XP 2800+                | 4209     | 1     | 64K  | 64K  | 512K  |        | 2087    |       |
| AMD       | Sempron SI-42                  | 4201     | 1     | 64K  | 64K  | 512K  |        | 2100    |       |
| AMD       | Sempron M120                   | 4188     | 1     |      |      |       |        | 2100    | AMD-V |
| Intel     | Celeron N3000                  | 4160     | 2     | 24K  | 32K  | 1024K |        | 2080    | VT-x  |
| Intel     | Celeron N3010                  | 4160     | 2     | 24K  | 32K  | 1024K |        | 2240    | VT-x  |
| AMD       | Athlon 64 3000+                | 4049     | 1     | 64K  | 64K  | 512K  |        | 1800    | AMD-V |
| AMD       | Sempron 3000+                  | 4026     | 1     | 64K  | 64K  | 512K  |        |         |       |
| AMD       | Athlon 64 3200+                | 4021     | 1     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | Athlon 64 3000+                | 4020     | 1     | 64K  | 64K  | 1024K |        | 2000    |       |
| AMD       | Athlon 64 3000+                | 4020     | 1     | 64K  | 64K  | 512K  |        | 2000    |       |
| AMD       | Sempron 3300+                  | 4020     | 1     | 64K  | 64K  | 128K  |        | 2000    |       |
| AMD       | Athlon 64 3200+                | 4020     | 1     | 64K  | 64K  | 512K  |        | 2000    |       |
| AMD       | Sempron 3600+                  | 4020     | 1     | 64K  | 64K  | 256K  |        | 2000    |       |
| AMD       | Athlon 64 3200+                | 4019     | 1     | 64K  | 64K  | 512K  |        | 2000    |       |
| AMD       | Turion 64 Mobile Technology... | 4019     | 1     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| Intel     | Celeron 440                    | 4019     | 1     | 32K  | 32K  | 512K  |        |         |       |
| AMD       | Sempron LE-1150                | 4018     | 1     | 64K  | 64K  | 256K  |        | 2000    |       |
| AMD       | Sempron 3600+                  | 4018     | 1     | 64K  | 64K  | 256K  |        | 2000    |       |
| AMD       | Athlon II 170u                 | 4018     | 1     | 64K  | 64K  | 1024K |        | 2000    | AMD-V |
| AMD       | Mobile Sempron 3600+           | 4017     | 1     | 64K  | 64K  | 256K  |        | 2000    |       |
| AMD       | Athlon 64 X2 Dual Core 5800+   | 4008     | 2     | 64K  | 64K  | 512K  |        | 3000    | AMD-V |
| Intel     | Celeron 420                    | 4007     | 1     | 32K  | 32K  | 512K  |        |         |       |
| VIA       | Eden X2 U4200                  | 4002     | 2     | 64K  | 64K  | 1024K |        | 1000    | VT-x  |
| AMD       | Mobile Sempron 3600+           | 4001     | 1     | 64K  | 64K  | 256K  |        | 2000    |       |
| AMD       | Athlon 64 3200+                | 4000     | 1     | 64K  | 64K  | 512K  |        | 2000    |       |
| AMD       | Dual-Core Opteron 1220         | 4000     | 2     |      |      |       |        | 2800    | AMD-V |
| AMD       | Sempron SI-40                  | 4000     | 1     | 64K  | 64K  | 512K  |        | 2000    |       |
| AMD       | C-60 APU with Radeon HD Gra... | 4000     | 2     | 32K  | 32K  | 512K  |        | 1000    | AMD-V |
| AMD       | C-70 APU with Radeon HD Gra... | 4000     | 2     | 32K  | 32K  | 512K  |        | 1000    | AMD-V |
| AMD       | G-T40E                         | 4000     | 2     | 64K  | 64K  | 1M    |        | 1000    | AMD-V |
| AMD       | Mobile Sempron 3300+           | 3999     | 1     | 64K  | 64K  | 128K  |        | 2000    |       |
| AMD       | Sempron 3500+                  | 3999     | 1     | 64K  | 64K  | 128K  |        |         |       |
| AMD       | Sempron M100                   | 3999     | 1     | 64K  | 64K  | 512K  |        | 2000    | AMD-V |
| AMD       | Sempron 2800+                  | 3999     | 1     | 64K  | 64K  | 256K  |        | 2004    |       |
| Intel     | Celeron 550                    | 3999     | 1     | 32K  | 32K  | 1024K |        | 2000    |       |
| AMD       | Athlon Dual Core 5200B         | 3998     | 2     | 64K  | 64K  | 512K  |        | 2700    | AMD-V |
| AMD       | Athlon 64 X2 Dual Core 4200+   | 3998     | 2     | 64K  | 64K  | 512K  |        | 2200    |       |
| AMD       | Dual-Core Opteron 1210         | 3998     | 2     | 64K  | 64K  | 1024K |        | 1800    | AMD-V |
| AMD       | G-T40N                         | 3998     | 2     | 32K  | 32K  | 512K  |        | 1000    | AMD-V |
| Intel     | 575                            | 3996     | 1     | 32K  | 32K  | 1024K |        |         |       |
| AMD       | A4-1200 APU with Radeon HD ... | 3994     | 2     | 32K  | 32K  | 1024K |        | 1000    | AMD-V |
| AMD       | E1-2100 APU with Radeon HD ... | 3994     | 2     | 32K  | 32K  | 1024K |        | 1000    | AMD-V |
| AMD       | C-50                           | 3992     | 2     | 32K  | 32K  | 512K  |        | 1000    | AMD-V |
| AMD       | C-60                           | 3992     | 2     | 32K  | 32K  | 512K  |        | 1333    | AMD-V |
| AMD       | Z-60 APU with Radeon HD Gra... | 3992     | 2     | 32K  | 32K  | 512K  |        | 1000    | AMD-V |
| AMD       | A4-1250 APU with Radeon HD ... | 3992     | 2     | 32K  | 32K  | 1024K |        | 1000    | AMD-V |
| AMD       | GX-210JA SOC with Radeon HD... | 3992     | 2     | 32K  | 32K  | 1024K |        | 1000    | AMD-V |
| Intel     | Celeron G470                   | 3992     | 1     | 32K  | 32K  | 256K  | 1.5M   | 2000    | VT-x  |
| Intel     | Celeron M 450                  | 3991     | 1     | 32K  | 32K  | 1024K |        |         |       |
| AMD       | Athlon TF-36                   | 3990     | 1     | 64K  | 64K  | 256K  |        | 2000    | AMD-V |
| AMD       | Z-01                           | 3990     | 2     | 32K  | 32K  | 512K  |        | 1000    | AMD-V |
| Intel     | Celeron 1019Y                  | 3990     | 2     | 32K  | 32K  | 256K  | 2048K  | 1000    | VT-x  |
| AMD       | Athlon 64 3200+                | 3989     | 1     | 64K  | 64K  | 1024K |        | 2000    |       |
| AMD       | Opteron 246                    | 3989     | 1     | 64K  | 64K  | 1024K |        |         |       |
| AMD       | Athlon 64 3200+                | 3988     | 1     | 64K  | 64K  | 512K  |        | 2000    |       |
| AMD       | Turion 64 Mobile Technology... | 3988     | 1     | 64K  | 64K  | 1024K |        | 2000    |       |
| AMD       | Mobile Athlon XP-M 2600+       | 3980     | 1     | 64K  | 64K  | 512K  |        | 1990    |       |
| AMD       | Sempron 3400+                  | 3979     | 1     | 64K  | 64K  | 128K  |        |         |       |
| AMD       | Athlon XP 2600+                | 3849     | 1     | 64K  | 64K  | 512K  |        | 1920    |       |
| AMD       | Sempron LE-1100                | 3817     | 1     | 64K  | 64K  | 256K  |        |         |       |
| AMD       | Athlon XP 2000+                | 3769     | 1     | 64K  | 64K  | 256K  |        |         |       |
| Intel     | Celeron M 440                  | 3735     | 1     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Celeron 540                    | 3735     | 1     | 32K  | 32K  | 1024K |        | 1867    |       |
| Intel     | T1350                          | 3733     | 1     | 32K  | 32K  | 2048K |        | 1867    |       |
| Intel     | Xeon 3040                      | 3724     | 1     | 32K  | 32K  | 2048K |        |         | VT-x  |
| AMD       | Athlon XP 2500+                | 3682     | 1     | 64K  | 64K  | 512K  |        | 1837    |       |
| AMD       | Mobile Athlon XP 2500+         | 3665     | 1     | 64K  | 64K  | 512K  |        |         |       |
| Intel     | T1400                          | 3657     | 1     | 32K  | 32K  | 2048K |        | 1833    |       |
| AMD       | Athlon 64 3000+                | 3619     | 1     | 64K  | 64K  | 512K  |        |         |       |
| AMD       | Athlon 64 2800+                | 3618     | 1     | 64K  | 64K  | 512K  |        | 1800    |       |
| AMD       | Athlon 64 3000+                | 3618     | 1     | 64K  | 64K  | 512K  |        | 1800    |       |
| AMD       | Sempron 3000+                  | 3618     | 1     | 64K  | 64K  | 128K  |        | 1800    |       |
| AMD       | Sempron 3000+                  | 3618     | 1     | 64K  | 64K  | 128K  |        | 1800    |       |
| AMD       | Sempron 3200+                  | 3618     | 1     | 64K  | 64K  | 128K  |        | 1800    |       |
| AMD       | Sempron 3200+                  | 3617     | 1     | 64K  | 64K  | 128K  |        | 1800    |       |
| AMD       | Athlon 64 2800+                | 3616     | 1     | 64K  | 64K  | 512K  |        | 1800    |       |
| AMD       | Mobile Sempron                 | 3616     | 1     | 64K  | 64K  | 512K  |        | 1800    |       |
| AMD       | Mobile Sempron 3400+           | 3616     | 1     | 64K  | 64K  | 256K  |        | 1800    |       |
| AMD       | Mobile Sempron 3500+           | 3616     | 1     | 64K  | 64K  | 512K  |        | 1800    |       |
| AMD       | Athlon 64 3000+                | 3616     | 1     | 64K  | 64K  | 512K  |        | 1800    | AMD-V |
| AMD       | Sempron 3400+                  | 3616     | 1     | 64K  | 64K  | 256K  |        | 1800    |       |
| AMD       | Sempron 3100+                  | 3608     | 1     | 64K  | 64K  | 256K  |        | 1800    |       |
| AMD       | Mobile Sempron 3000+           | 3608     | 1     | 64K  | 64K  | 128K  |        | 1800    |       |
| Intel     | Pentium 4                      | 3608     | 1     |      |      |       |        |         |       |
| Intel     | Celeron                        | 3608     | 1     |      |      |       |        |         |       |
| AMD       | Athlon 2850e                   | 3600     | 1     | 64K  | 64K  | 512K  |        | 1800    | AMD-V |
| AMD       | Sempron 3000+                  | 3600     | 1     | 64K  | 64K  | 128K  |        |         |       |
| AMD       | Turion 64 Mobile Technology... | 3600     | 1     | 64K  | 64K  | 512K  |        | 1800    |       |
| AMD       | Turion 64 Mobile Technology... | 3600     | 1     | 64K  | 64K  | 1024K |        | 1800    |       |
| AMD       | Mobile Sempron 3100+           | 3600     | 1     | 64K  | 64K  | 256K  |        | 1800    |       |
| AMD       | Sempron 3400+                  | 3600     | 1     | 64K  | 64K  | 256K  |        | 1800    |       |
| AMD       | Athlon XP 2200+                | 3600     | 1     | 64K  | 64K  | 256K  |        |         |       |
| Intel     | Pentium M                      | 3599     | 1     |      |      |       |        | 2000    |       |
| AMD       | Athlon II Neo K145             | 3592     | 1     | 64K  | 64K  | 1024K |        | 1800    | AMD-V |
| VIA       | C7-D                           | 3591     | 1     |      |      |       |        | 1800    |       |
| AMD       | Sempron 3000+                  | 3589     | 1     | 64K  | 64K  | 128K  |        | 1800    |       |
| AMD       | Sempron 3200+                  | 3589     | 1     | 64K  | 64K  | 256K  |        | 1800    |       |
| AMD       | Athlon 64 3000+                | 3581     | 1     | 64K  | 64K  | 512K  |        | 1800    |       |
| AMD       | Sempron 3000+                  | 3581     | 1     | 64K  | 64K  | 128K  |        | 1800    |       |
| AMD       | Athlon II Neo K125             | 3503     | 1     | 64K  | 64K  | 1024K |        | 1700    | AMD-V |
| Intel     | Celeron M 430                  | 3468     | 1     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Celeron M 430                  | 3466     | 1     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Celeron M 530                  | 3466     | 1     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Celeron M 530                  | 3459     | 1     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Celeron M 530                  | 3457     | 1     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Celeron M                      | 3425     | 1     |      |      |       |        | 1600    |       |
| AMD       | Athlon XP 2000+                | 3400     | 1     | 64K  | 64K  | 256K  |        |         |       |
| Intel     | Pentium 4                      | 3392     | 1     |      |      |       |        |         |       |
| Intel     | Pentium M                      | 3389     | 1     |      |      |       |        | 1700    |       |
| AMD       | Sempron 2400+                  | 3347     | 1     | 64K  | 64K  | 256K  |        | 1670    |       |
| AMD       | Athlon                         | 3334     | 1     | 64K  | 64K  | 256K  |        | 1150    |       |
| AMD       | Athlon XP 2000+                | 3331     | 1     | 64K  | 64K  | 256K  |        |         |       |
| Intel     | T1300                          | 3326     | 1     | 32K  | 32K  | 2048K |        | 1667    | VT-x  |
| AMD       | Athlon XP 2000+                | 3323     | 1     | 64K  | 64K  | 256K  |        |         |       |
| AMD       | Mobile Athlon XP-M 2200+       | 3316     | 1     | 64K  | 64K  | 512K  |        | 1658    |       |
| AMD       | Sempron 2600+                  | 3215     | 1     | 64K  | 64K  | 128K  |        |         |       |
| AMD       | Sempron 2800+                  | 3214     | 1     | 64K  | 64K  | 256K  |        |         |       |
| AMD       | Turion 64 X2                   | 3214     | 2     | 64K  | 64K  | 512K  |        | 1800    | AMD-V |
| AMD       | Sempron 2800+                  | 3214     | 1     | 64K  | 64K  | 128K  |        |         |       |
| AMD       | Sempron 3000+                  | 3214     | 1     | 64K  | 64K  | 256K  |        |         |       |
| AMD       | Mobile Sempron 3200+           | 3206     | 1     | 64K  | 64K  | 512K  |        | 1600    |       |
| AMD       | Athlon Neo MV-40               | 3201     | 1     | 64K  | 64K  | 512K  |        | 1600    | AMD-V |
| Intel     | Celeron M 520                  | 3201     | 1     | 32K  | 32K  | 1024K |        |         |       |
| AMD       | Turion 64 X2 Mobile Technol... | 3200     | 2     | 64K  | 64K  | 512K  |        | 1900    | AMD-V |
| AMD       | Turion 64 X2 Mobile Technol... | 3200     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| AMD       | Athlon 64 2600+                | 3200     | 1     | 64K  | 64K  | 512K  |        | 1600    | AMD-V |
| AMD       | Mobile Sempron 2800+           | 3200     | 1     | 64K  | 64K  | 256K  |        | 1600    |       |
| AMD       | Turion 64 Mobile Technology... | 3200     | 1     | 64K  | 64K  | 512K  |        | 1600    |       |
| AMD       | Mobile Sempron 2800+           | 3200     | 1     | 64K  | 64K  | 256K  |        | 1600    |       |
| Intel     | Celeron M 420                  | 3200     | 1     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | Celeron M 520                  | 3200     | 1     | 32K  | 32K  | 1024K |        |         |       |
| AMD       | Athlon 2650e                   | 3199     | 1     | 64K  | 64K  | 512K  |        | 1600    | AMD-V |
| AMD       | Turion 64 Mobile Technology... | 3199     | 1     | 64K  | 64K  | 1024K |        | 1600    |       |
| Intel     | Pentium 4 Mobile               | 3197     | 1     |      |      |       |        | 1600    |       |
| Intel     | Celeron G440                   | 3194     | 1     | 32K  | 32K  | 256K  | 1024K  | 1600    | VT-x  |
| VIA       | Nano U2250                     | 3193     | 1     |      |      |       |        | 1600    | VT-x  |
| AMD       | Athlon Neo X2 Dual Core L335   | 3192     | 2     | 64K  | 64K  | 256K  |        | 1600    | AMD-V |
| VIA       | C7-M                           | 3192     | 1     |      |      |       |        | 1600    |       |
| VIA       | Nano U2250                     | 3192     | 1     |      |      |       |        | 1600    | VT-x  |
| AMD       | Athlon XP 3000+                | 3191     | 1     | 64K  | 64K  | 256K  |        | 1600    |       |
| AMD       | Athlon 64 X2 Dual-Core TK-53   | 3190     | 2     | 64K  | 64K  | 256K  |        | 1700    | AMD-V |
| AMD       | Athlon 64 X2 Dual-Core TK-42   | 3190     | 2     | 64K  | 64K  | 512K  |        | 1600    | AMD-V |
| AMD       | Turion 64 X2 Mobile Technol... | 3190     | 2     | 64K  | 64K  | 512K  |        | 1800    | AMD-V |
| AMD       | Turion 64 X2 Mobile Technol... | 3190     | 2     | 64K  | 64K  | 512K  |        | 2200    | AMD-V |
| Intel     | Mobile Intel Celeron           | 3189     | 1     |      |      |       |        |         |       |
| AMD       | Athlon XP 1800+                | 3066     | 1     | 64K  | 64K  | 256K  |        |         |       |
| AMD       | Athlon XP 1800+                | 3014     | 1     |      |      |       |        | 1500    |       |
| Intel     | Celeron D 220                  | 3001     | 1     | 32K  | 32K  | 512K  |        |         |       |
| AMD       | Sempron 210U                   | 3000     | 1     | 64K  | 64K  | 256K  |        |         |       |
| AMD       | E-240                          | 3000     | 1     | 32K  | 32K  | 512K  |        | 1500    | AMD-V |
| Intel     | Celeron 220                    | 3000     | 1     | 32K  | 32K  | 512K  |        |         |       |
| Intel     | T1200                          | 2999     | 1     | 32K  | 32K  | 2048K |        | 1500    | VT-x  |
| AMD       | G-T52R                         | 2993     | 1     | 32K  | 32K  | 512K  |        | 1500    | AMD-V |
| AMD       | Sempron 2200+                  | 2992     | 1     | 64K  | 64K  | 256K  |        |         |       |
| VIA       | Esther                         | 2992     | 1     |      |      |       |        | 1500    |       |
| AMD       | Athlon XP 1700+                | 2939     | 1     |      |      |       |        |         |       |
| Intel     | Celeron M 410                  | 2934     | 1     | 32K  | 32K  | 1024K |        |         |       |
| AMD       | Athlon XP 1700+                | 2932     | 1     | 64K  | 64K  | 256K  |        |         |       |
| Intel     | Atom E3815                     | 2932     | 1     | 24K  | 32K  | 512K  |        | 1466    | VT-x  |
| Intel     | Atom E3815                     | 2932     | 1     | 24K  | 32K  | 512K  |        | 1466    | VT-x  |
| AMD       | Sempron 2500+                  | 2813     | 1     | 64K  | 64K  | 256K  |        |         |       |
| Intel     | Celeron M                      | 2800     | 1     |      |      |       |        |         |       |
| Intel     | Core2 Solo U3500               | 2794     | 1     | 32K  | 32K  | 3072K |        | 1400    | VT-x  |
| Intel     | Celeron 743                    | 2594     | 1     | 32K  | 32K  | 1024K |        |         |       |
| Intel     | U2700                          | 2593     | 1     | 32K  | 32K  | 2048K |        | 1300    |       |
| Intel     | Pentium III family             | 2539     | 1     |      |      |       |        |         |       |
| VIA       | Nano U3300                     | 2400     | 1     |      |      |       |        | 1200    | VT-x  |
| AMD       | C-30                           | 2395     | 1     | 32K  | 32K  | 512K  |        | 1200    | AMD-V |
| AMD       | G-T44R                         | 2395     | 1     | 32K  | 32K  | 512K  |        | 1200    | AMD-V |
| Intel     | Celeron 723                    | 2395     | 1     | 32K  | 32K  | 1024K |        |         |       |
| AMD       | V105                           | 2394     | 1     | 64K  | 64K  | 512K  |        | 1200    | AMD-V |
| Intel     | Core Solo U1400                | 2394     | 1     | 32K  | 32K  | 2048K |        | 1200    | VT-x  |
| AMD       | Athlon L110                    | 2393     | 1     | 64K  | 64K  | 512K  |        |         | AMD-V |
| Intel     | U1400                          | 2393     | 1     | 32K  | 32K  | 2048K |        | 1200    | VT-x  |
| AMD       | Athlon                         | 2310     | 1     | 64K  | 64K  | 512K  |        | 1150    |       |
| Intel     | Mobile Intel Pentium III - M   | 2264     | 1     |      |      |       |        | 1130    |       |
| Intel     | Pentium III Mobile             | 2259     | 1     |      |      |       |        | 1133    |       |
| Intel     | Core2 Solo U2100               | 2127     | 1     | 32K  | 32K  | 1024K |        | 1067    | VT-x  |
| AMD       | Athlon LE-1640                 | 2010     | 1     | 64K  | 64K  | 512K  |        | 2700    | AMD-V |
| AMD       | Athlon 1640B                   | 2008     | 1     | 64K  | 64K  | 512K  |        | 2700    | AMD-V |
| AMD       | Athlon                         | 2000     | 1     | 64K  | 64K  | 256K  |        |         |       |
| Intel     | Celeron (Coppermine)           | 2000     | 1     |      |      |       |        |         |       |
| Intel     | Pentium III (Coppermine)       | 1999     | 1     |      |      |       |        |         |       |
| Intel     | 4000                           | 1996     | 2     | 48K  | 64K  | 1M    |        | 500     | VT-x  |
| VIA       | Eden                           | 1995     | 1     |      |      |       |        |         |       |
| VIA       | Nano U3500                     | 1995     | 1     |      |      |       |        | 1000    | VT-x  |
| AMD       | Athlon 64 3700+                | 1989     | 1     | 64K  | 64K  | 1024K |        | 2200    |       |
| Intel     | Pentium III (Coppermine)       | 1988     | 1     |      |      |       |        |         |       |
| AMD       | Mobile Duron                   | 1600     | 1     | 64K  | 64K  | 64K   |        |         |       |
| AMD       | Athlon 64 3200+                | 1596     | 1     | 64K  | 64K  | 1024K |        | 2000    |       |
| AMD       | Athlon TF-20                   | 1595     | 1     | 64K  | 64K  | 512K  |        | 1600    | AMD-V |
| AMD       | Turion 64 Mobile ML-32         | 1595     | 1     | 64K  | 64K  | 512K  |        | 1800    |       |
| AMD       | Athlon XP 3000+                | 1595     | 1     | 64K  | 64K  | 256K  |        |         |       |
| AMD       | Turion 64 Mobile Technology... | 1591     | 1     | 64K  | 64K  | 1024K |        | 1600    |       |
| AMD       | Turion 64 Mobile Technology... | 1591     | 1     | 64K  | 64K  | 512K  |        | 1800    |       |
| AMD       | Turion 64 Mobile Technology... | 1591     | 1     | 64K  | 64K  | 1024K |        | 1800    |       |
| AMD       | Turion 64 Mobile Technology... | 1591     | 1     | 64K  | 64K  | 1024K |        | 2000    |       |
| Intel     | Pentium III (Coppermine)       | 1474     | 1     |      |      |       |        |         |       |
| Intel     | Pentium III (Coppermine)       | 1471     | 1     |      |      |       |        |         |       |
| Intel     | Celeron (Coppermine)           | 1262     | 1     |      |      |       |        |         |       |
| Intel     | Celeron M                      | 1196     | 1     |      |      |       |        | 1500    |       |
| ARM       | Cortex-A8                      | 1002     | 1     |      |      |       |        | 1008    |       |
| ARM       | Cortex-A57                     | 1000     | 2     |      |      |       |        |         |       |
| ARM       | ARM1176                        | 997      | 1     |      |      |       |        | 1000    |       |
| Intel     | Pentium II (Deschutes)         | 701      | 1     |      |      |       |        |         |       |
| ARM       | Cortex-A17                     | 688      | 4     |      |      |       |        | 1800    |       |
| ARM       | Cortex-A8                      | 592      | 1     |      |      |       |        | 600     |       |
| Intel     | Mobile Pentium MMX             | 463      | 1     |      |      |       |        |         |       |
| ARM       | Cortex-A7                      | 400      | 4     |      |      |       |        | 1392    |       |
| Marvell   | Feroceon 88FR131               | 400      | 1     |      |      |       |        | 1000    |       |
| ARM       | Cortex-A53                     | 356      | 4     | 256K | 256K | 1M    |        | 2600    |       |
| ARM       | Cortex-A57                     | 248      | 4     | 128K | 192K | 2M    |        | 2035    |       |
| ARM       | Cortex-A53                     | 208      | 4     |      |      |       |        | 1600    |       |
| Marvell   | PJ4B-MP                        | 200      | 4     |      |      |       |        | 1333    |       |
| ARM       | Cortex-A55                     | 192      | 4     |      |      |       |        | 2100    |       |
| ARM       | Cortex-A53                     | 152      | 4     |      |      |       |        | 1190    |       |
| ARM       | Cortex-A57                     | 152      | 4     | 128K | 192K | 2M    |        | 2091    |       |
| Qualcomm  | ARMv8 rev 12 (v8l)             | 152      | 4     | 256K | 256K | 1M    | 2M     | 2803    |       |
| Qualcomm  | ARMv8 rev 14 (v8l)             | 152      | 4     |      |      | 1M    | 2M     | 2956    |       |
| Qualcomm  | Kryo V2                        | 152      | 4     | 256K | 256K | 2M    |        | 2457    |       |
| Nvidia    | ARMv8 rev 0 (v8l)              | 124      | 2     | 64K  | 128K | 2048K | 4096K  | 1907    |       |
| Qualcomm  | Krait                          | 114      | 3     |      |      |       |        | 2496    |       |
| ARM       | Cortex-A7                      | 100      | 2     |      |      |       |        | 960     |       |
| Qualcomm  | Krait                          | 80       | 2     |      |      |       |        | 1890    |       |
| Qualcomm  | Krait                          | 76       | 2     |      |      |       |        | 2457    |       |
| Qualcomm  | Kryo                           | 76       | 2     |      |      |       |        | 2150    |       |
| ARM       | Cortex-A9                      | 24       | 4     |      |      |       |        | 996     |       |
| ARM       | Cortex-A5                      | 12       | 4     |      |      |       |        | 1824    |       |
| ARM       | Cortex-A53                     | 0        | 3     |      |      |       |        | 2400    |       |
