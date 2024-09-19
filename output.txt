```
load:0x40080404,len:3904
entry 0x40080640
I (30) boot: ESP-IDF v5.3.1 2nd stage bootloader
I (31) boot: compile time Sep 19 2024 14:44:11
I (31) boot: Multicore bootloader
I (35) boot: chip revision: v1.0
I (39) boot.esp32: SPI Speed      : 40MHz
I (43) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (52) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:
I (61) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (76) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00100000
I (91) boot: End of partition table
I (95) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=1f35ch (127836) map
I (147) esp_image: segment 1: paddr=0002f384 vaddr=3ffb0000 size=00c94h (  3220) load
I (149) esp_image: segment 2: paddr=00030020 vaddr=400d0020 size=82b98h (535448) map
I (337) esp_image: segment 3: paddr=000b2bc0 vaddr=3ffb0c94 size=0323ch ( 12860) load
I (342) esp_image: segment 4: paddr=000b5e04 vaddr=40080000 size=1734ch ( 95052) load
I (391) boot: Loaded app from partition at offset 0x10000
I (391) boot: Disabling RNG early entropy source...
I (403) cpu_start: Multicore app
I (412) cpu_start: Pro cpu start user code
I (412) cpu_start: cpu freq: 160000000 Hz
I (412) app_init: Application information:
I (415) app_init: Project name:     ESP32_ESP-IDF_WiFi-AP
I (421) app_init: App version:      1
I (425) app_init: Compile time:     Sep 19 2024 14:43:48
I (431) app_init: ELF file SHA256:  65cb3ccbb...
I (436) app_init: ESP-IDF:          v5.3.1
I (441) efuse_init: Min chip rev:     v0.0
I (446) efuse_init: Max chip rev:     v3.99 
I (451) efuse_init: Chip rev:         v1.0
I (456) heap_init: Initializing. RAM available for dynamic allocation:
I (463) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (469) heap_init: At 3FFB80F8 len 00027F08 (159 KiB): DRAM
I (475) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (482) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (488) heap_init: At 4009734C len 00008CB4 (35 KiB): IRAM
I (496) spi_flash: detected chip: generic
I (499) spi_flash: flash io: dio
W (503) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (517) main_task: Started on CPU0
I (527) main_task: Calling app_main()
I (547) wifi softAP: ESP_WIFI_MODE_AP
I (557) wifi:wifi driver task: 3ffc0150, prio:23, stack:6656, core=0
I (567) wifi:wifi firmware version: ccaebfa
I (567) wifi:wifi certification version: v7.0
I (567) wifi:config NVS flash: enabled
I (567) wifi:config nano formating: disabled
I (567) wifi:Init data frame dynamic rx buffer num: 32
I (577) wifi:Init static rx mgmt buffer num: 5
I (577) wifi:Init management short buffer num: 32
I (587) wifi:Init dynamic tx buffer num: 32
I (587) wifi:Init static rx buffer size: 1600
I (597) wifi:Init static rx buffer num: 10
I (597) wifi:Init dynamic rx buffer num: 32
I (597) wifi_init: rx ba win: 6
I (607) wifi_init: accept mbox: 6
I (607) wifi_init: tcpip mbox: 32
I (617) wifi_init: udp mbox: 6
I (617) wifi_init: tcp mbox: 6
I (617) wifi_init: tcp tx win: 5760
I (627) wifi_init: tcp rx win: 5760
I (627) wifi_init: tcp mss: 1440
I (627) wifi_init: WiFi IRAM OP enabled
I (637) wifi_init: WiFi RX IRAM OP enabled
I (917) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
I (987) wifi:mode : softAP (58:bf:25:8c:14:65)
I (1097) wifi:Total power save buffer number: 16
I (1097) wifi:Init max length of beacon: 752/752
I (1107) wifi:Init max length of beacon: 752/752
I (1107) wifi softAP: wifi_init_softap finished. SSID:myssid-258 password:12345678 channel:1
I (1107) esp_netif_lwip: DHCP server started on interface WIFI_AP_DEF with IP: 192.168.4.1
I (1117) main_task: Returned from app_main()
I (13847) wifi:new:<1,0>, old:<1,1>, ap:<1,1>, sta:<255,255>, prof:1, snd_ch_cfg:0x0
I (13847) wifi:station: a6:18:f5:c7:92:91 join, AID=1, bgn, 20
I (13877) wifi softAP: station a6:18:f5:c7:92:91 join, AID=1
I (15157) esp_netif_lwip: DHCP server assigned IP to a client, IP is: 192.168.4.2
I (16997) wifi:<ba-add>idx:2 (ifx:1, a6:18:f5:c7:92:91), tid:0, ssn:2, winSize:64
I (22977) wifi:<ba-add>idx:3 (ifx:1, a6:18:f5:c7:92:91), tid:5, ssn:2, winSize:64
I (23317) wifi:<ba-add>idx:4 (ifx:1, a6:18:f5:c7:92:91), tid:1, ssn:0, winSize:64
```
