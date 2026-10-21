# openwrt-mikrotik-hap-ac2
Własna kompilacja OpenWrt dla routera MikroTik hAP ac2

- Urządzenie: MikroTik hAP ac² (ipq40xx/mikrotik)
- Bazowa wersja OpenWrt: OpenWrt 25.12.5
- Pamięć masowa: Pendrive USB podłączony pod /mnt/*** (zalecany do przechowywania statystyk RRD i logów).



Custom OpenWrt Firmware for MikroTik hAP ac² (ipq40xx)

Autorski, skompilowany od podstaw obraz systemowy OpenWrt dla routera MikroTik hAP ac², przygotowany z myślą o pełnej stabilności, wydajności oraz zaawansowanym monitorowaniu sprzętowym.

Kluczowe Cechy i Modyfikacje Systemu

- Optymalizacja i Zegary SoC: Pełne wsparcie dla architektury arm_cortex-a7_neon-vfpv4 oraz prawidłowe zarządzanie częstotliwością pracy procesora.
- Obsługa portu USB: Wbudowane sterowniki USB 3.0 / DWC3 oraz obsługa systemów plików (ext4, exFAT, NTFS3, VFAT) wraz z montowaniem pamięci masowej (np. pod /mnt/***), co pozwala na rozbudowę przestrzeni dyskowej.
- Zaawansowana Diagnostyka: Domyślnie zintegrowane narzędzie htop (ze wsparciem dla czujników lm-sensors) do monitorowania zasobów i procesów w czasie rzeczywistym bezpośrednio z terminala.
- Monitorowanie Środowiskowe: Skonfigurowany pakiet collectd wraz z wtyczkami do odczytu statystyk procesora, częstotliwości rdzeni oraz temperatur układów (sensors).
- Zarządzanie Plikami i Siecią: Wbudowane pakiety do obsługi dysków sieciowych (ksmbd-server), zaawansowane reguły zapory sieciowej oraz interfejs LuCI w lekkiej i responsywnej wersji.


  
