# EmComm_Guidance
This repository provides a practical and field-tested guide for establishing reliable Emergency Communications (EmComm) using FLDigi and several complementary software tools. The purpose of this documentation is to help amateur radio operators, disaster response teams, volunteer groups, and communication units quickly deploy robust digital communication channels during emergencies when conventional infrastructure fails.

During disasters, internet, cellular networks, and commercial communication systems are often disrupted. In these conditions, HF/VHF radio with digital modes becomes an essential backbone for passing critical information such as situation reports, logistics requests, location updates, and short text messages.

## 📑 Table of Contents
1. **Software Used**
   - FLDigi (Digital Modes)
   - FLRig (Radio Control)
   - FLMsg (Structured Messaging)

2. **Supported Hardware**
   - Icom: IC-9100, IC-7300, IC-7100, IC-705
   - Yaesu: FT-991/991A, FT-857
   - Audio Interfaces: Signalink, DigiRig, USB Soundcard
   - Antennas & Power Backup

3. **Sending Reports & Images**
   - Text message transmission using FLDigi / FLMsg  
   - Image transfer using MFSK Image or supported digital modes  
   - Recommended formats & bandwidth considerations

4. **APRS KISS Mode Support**
   - Enabling KISS mode in FLDigi  
   - Integration with Direwolf / YAAC / APRS clients  
   - Position reporting & message relay for EmComm

## 🧰 Software Used
### **FLDigi**
A multi-mode digital modem software used for transmitting and receiving digital signals such as MFSK, Olivia, PSK, and MT63. Essential for EmComm operations due to its reliability in weak-signal conditions.

### **FLRig**
A lightweight radio control interface that provides CAT control for many HF/VHF radios. Ensures stable communication between software and transceiver, allowing frequency, mode, and PTT control.

### **FLMsg**
A companion application for FLDigi that supports structured message forms (ICS, Radiograms, SITREP, custom forms). Commonly used for message handling and standardized emergency traffic.

### **Get The Software**
<table>
  <thead>
    <tr>
      <th>Software</th>
      <th>Download Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>FLDigi</td>
      <td><a href="https://github.com/YD1RUH/EmComm_Guidance/blob/main/Software/fldigi-4.2.10_setup.exe" target="_blank" rel="noopener">fldigi-4.2.10_setup.exe</a></td>
    </tr>
    <tr>
      <td>FLRig</td>
      <td><a href="https://github.com/YD1RUH/EmComm_Guidance/blob/main/Software/flrig-2.0.09_setup.exe" target="_blank" rel="noopener">flrig-2.0.09_setup.exe</a></td>
    </tr>
    <tr>
      <td>FLMsg</td>
      <td><a href="https://github.com/YD1RUH/EmComm_Guidance/blob/main/Software/flmsg-4.0.24_setup.exe" target="_blank" rel="noopener">flmsg-4.0.24_setup.exe</a></td>
    </tr>
  </tbody>
</table>

## 🛰️ Supported Hardware
### **Icom Radios**
<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>Image</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>IC-9100</td>
      <td><img src="https://github.com/YD1RUH/EmComm_Guidance/blob/main/Asset/9100.jpg" width="200"></td>
    </tr>
    <tr>
      <td>IC-7300</td>
      <td><img src="https://github.com/YD1RUH/EmComm_Guidance/blob/main/Asset/7300.jpg" width="200"></td>
    </tr>
    <tr>
      <td>IC-7100</td>
      <td><img src="https://github.com/YD1RUH/EmComm_Guidance/blob/main/Asset/7100.jpg" width="200"></td>
    </tr>
    <tr>
      <td>IC-705</td>
      <td><img src="https://github.com/YD1RUH/EmComm_Guidance/blob/main/Asset/705.jpg" width="200"></td>
    </tr>
  </tbody>
</table>

### **Yaesu Radios**
<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>Image</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>FT-991</td>
      <td><img src="https://github.com/YD1RUH/EmComm_Guidance/blob/main/Asset/991.jpg" width="200"></td>
    </tr>
    <tr>
      <td>FT-857D</td>
      <td><img src="https://github.com/YD1RUH/EmComm_Guidance/blob/main/Asset/857D.jpg" width="200"></td>
    </tr>
    <tr>
      <td>FT-450D</td>
      <td><img src="https://github.com/YD1RUH/EmComm_Guidance/blob/main/Asset/450D.jpg" width="200"></td>
    </tr>
  </tbody>
</table>

### **Audio Interfaces**
- Signalink USB  
- DigiRig Mobile  
- Generic USB Soundcard (DIY Interface)

### **Antennas**
- Dipole (40m / 20m / 10m)  
- End-fed Half Wave (EFHW)  
- Vertical Antennas  
- Portable Wire Antennas

### **Power Backup**
- 12V Battery  
- LiFePO4 Power Pack  
- Solar Panel + Charge Controller  
- Generator (optional)
