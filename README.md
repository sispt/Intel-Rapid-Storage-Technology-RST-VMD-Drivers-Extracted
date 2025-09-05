# Intel® RST VMD Drivers – Extracted

If you’re installing Windows on an Intel system and get:

- **“No device drivers were found”**  
- **“Windows can’t detect your disk”**

…it means the installer needs Intel® RST VMD drivers to see your NVMe SSD.

This repo provides extracted Intel® Rapid Storage Technology (RST) VMD drivers for **8th through 15th Gen Intel platforms**.

---

## Folders

- `IRST_8-9G/` — Intel 8th–9th Gen  
- `IRST_10-11G/` — Intel 10th–11th Gen  
- `IRST_12-13G/` — Intel 12th–13th Gen  
- `IRST_12-15G/` — Intel 12th–15th Gen  
Choose the folder matching your CPU generation.

---

## Usage

1. Copy the right driver folder to a USB stick.  
   - **FAT32** recommended (UEFI safe).  
   - **NTFS** usually works.  
   - **exFAT/ext4** will not work.  

2. Boot the Windows installer.  

3. If you see **“No device drivers were found”** or no disk, click **Load driver**.  

4. Point to the folder on your USB.  

5. The disk should now appear for installation.

---

## Notes

- Drivers belong to **Intel Corporation**.  
- Repo exists to make extracted files accessible for Linux users, dual-boot setups, and anyone hitting disk detection errors.  
- Linux already supports VMD natively.  

---

## Contribution

If you have newer driver versions or extra platform support, feel free to add them in the right folder and open a pull request.  
Clear folder naming and keeping the README updated helps everyone.  

---

**Helps with searches like:**  
- Windows can’t detect disk  
- No device drivers were found  
- Intel VMD NVMe driver  
- RST F6 driver
