# Hackintosh-Lenovo-G50_80-Sonoma

EFI Lenovo G50-80 - Intel Core i3-5005U 2GHz - macOS Sonoma 14.1.1 - OpenCore 0.9.6
    
- Processador: Intel Core i3-5005U 2GHz
- Chipset: Intel Wildcat Point-LP, Intel Broadwell
- Video: Intel HD Graphics 5500
- RAM: DDR3 16GB (1600MHz)
- Audio: Conexant CX20751/2 
- SSD: CT500MX500SSD1  (500 GB)
- SSD: TEAM GROUP T-FORCE VULCAN Z (1 TB)
- Wifi/BT: Intel(R) Dual Band Wireless-AC 3160
- Rede: Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter
- WebCam: Lenovo EasyCam 
- SMBIOS: MacBookPro16,3

## Não Funciona:
 - AirDrop
 - Sleep

- Aceleração gráfica ativada com OCLP 1.2.1

## Obs: Security -> SecureBootModel 
Default - Para receber atualizações e conta Apple
Disabled - Para ativar aceleração gráfica com OCPL

Kests Intel Wifi/BT removidas da EFI, caso use Wifi/BT Intel adicinar kexts e dar um OC Clean Snapshot
