# The Cable Bible
A comprehensive guide to cables and connectors potentially used for audiovisual/media preservation. Cable types and connectors are organized by the primary purpose of the signal being transferred - video, audio-only, data (i.e. computer cables) and power. Examples of physical connectors, pinouts and contextual uses for each kind of cable are nested within descriptions of signal types, wiring, interfaces and protocols!

## Table of Contents ##

1. [Video] (README.md#video) :tv:
  1. [Analog] (README.md#analog)
    1. [Composite] (README.md#composite)
    2. [Component YPbPr] (README.md#component-ypbpr)
    3. [S-Video] (README.md#s-video)
    4. [RGBS] (README.md#rgbs)
    5. [RGBVH] (README.md#rgbvh)
  2. [Digital] (README.md#digital)
    1. [SDI] (README.md#sdi)
    2. [FireWire (IEEE 1394)] (README.md#firewire)
    3. [DVI] (README.md#dvi)
    4. [DisplayPort] (README.md#displayport)
    5. [HDMI] (README.md#hdmi)
  3. [Integrated] (README.md#integrated)
    1. [DVI-I] (README.md#dvi-i)
2. [Audio] (README.md#audio) :sound:
  1. [Analog] (README.md#analog-1)
    1. [Balanced] (README.md#balanced)
    2. [Unbalanced] (README.md#unbalanced)
  2. [Digital] (README.md#digital-1)
    1. [AES-3 (AES/EBU)] (README.md#aes-3)
      1. [Balanced] (README.md#balanced-1)
      2. [Unbalanced] (README.md#unbalanced-1)
    2. [S/PDIF] (README.md#spdif)
      1. [Optical] (README.md#optical)
      2. [Unbalanced] (README.md#unbalanced-2)
    3. [MIDI] (README.md#midi)
      1. [Balanced] (README.md#balanced-2)
    4. [TDIF] (README.md#tdif)
      1. [Unbalanced] (README.md#unbalanced-3)
    5. [ADAT] (README.md#adat)
      1. [Optical] (README.md#optical-1)
3. [Data] (README.md#data) :computer: :floppy_disk:
  1. [Parallel] (README.md#parallel)
    1. [PATA] (README.md#pata)
    2. [Parallel SCSI] (README.md#parallel-scsi)
    3. [IEEE 1284 ("Parallel Port", "printer port", "Centronics port")] (README.md#ieee-1284)
  2. [Serial] (README.md#serial)
    1. [RS-232 ("the serial port")] (README.md#rs-232)
    2. [RS-422] (README.md#rs-422)
    3. [SAS (Serial SCSI)] (README.md#serial-scsi)
    4. [SATA] (README.md#sata)
    5. [Apple Desktop Bus] (README.md#apple-desktop-bus)
    6. [PS/2] (README.md#ps2)
    7. [USB] (README.md#usb)
      1. [USB 2.0] (README.md#usb-20)
      2. [USB 3.0] (README.md#usb-30)
      3. [USB 3.1] (README.md#usb-31)
    8. [FireWire] (README.md#firewire-1)
      1. [FireWire 400] (README.md#firewire-400)
      2. [FireWire 800] (README.md#firewire-800)
    9. [ThunderBolt] (README.md#thunderbolt)
      1. [ThunderBolt 1 and 2] (README.md#thunderbolt-1-and-2)
      2. [ThunderBolt 3] (README.md#thunderbolt-3)
    10. [HDBaseT (network)] (README.md#hdbaset)
4. [Power] (README.md#power)


## Video ##
### Analog ###
#### Composite ####
  In composite cables, all video information (including both luminance and chrominance) is encoded on to a single channel/wire.
  
  **Introduced:** 1956  
  **Max resolution:** Standard Definition (typically 480i or 576i)  
  **Connectors and ports:**  
  ![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/Composite-video-cable.jpg/320px-Composite-video-cable.jpg)  
  _RCA_  
  Used primarily with consumer equipment (e.g. Betamax, VHS, DVD)  
  Audio: no
  
  
  ![](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/BNC_connector_%28male%29.jpg/320px-BNC_connector_%28male%29.jpg)  
  _BNC_  
  Used in professional broadcast and some consumer equipment  
  Audio: no
  
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/UHF-Connector.png" height="289" width="322">  
  _UHF_  
  A WWII-era connector design originally intended for video connections in radar applications. Used with late-period 1/2" open reel decks (e.g. Sony AV decks) and some early 3/4" U-matic players.  
  
  ![](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/F_Connector_Side.jpg/320px-F_Connector_Side.jpg)  
  _F-type_  
  Found in North American television antenna, cable and satellite television installations; some older VCRs  
  Audio: no
  
  _Video patch (MUSA)_  
  Originally developed for manually switching signals in radar installations; now commonly used for patch bays in production and preservation workflows.  
  Audio: no
  
  _8-pin EIAJ_  
  Monitor cables designed specifically to carry both input and output signal between a video deck and monitor over the same cable. Seen on 1/2" open reel decks (the only available output on Sony CVs), 3/4" U-matic, and contemporary monitors.  
  Audio: yes, stereo, unbalanced
  
  ![](https://upload.wikimedia.org/wikipedia/en/e/e0/Fake-scart-brkn.jpg)  
  _SCART_  
  European 21-pin connector designed to be capable of carrying both input and output of multiple signal standards, including composite video (see also: [S-Video] (README.md#s-video), [RGBS] (README.md#rgbs), [YPbPr] (README.md#component-ypbpr)).  
  Audio: yes, stereo, unbalanced  
  
#### Component YPbPr ####
YPbPr signal is often referred to, imprecisely, simply as "component" video, although there are actually several standards of component video (any signal standard that splits video information into multiple channels is component, including S-Video and the multiple RGB standards). In YPbPr, the video signal is split into three channels: Y (containing luminance and sync), Pb (the difference between blue and luma), and Pr (the difference between red and luma). The remaining (green) chrominance information is derived from the relationship between these three signals. YPbPr cables are sometimes referred to as "yipper" cables and are connectors are usually color-coded (Y=green, Pb=blue, Pr=red); however YPbPr cables are fundamentally wired the same as composite cables and can be used interchangeably as long as the corresponding ports are properly connected.

**Introduced:**  
**Max resolution:** High Definition (up to 1080p)  
**Connectors and ports:**  
![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Component-cables.jpg/309px-Component-cables.jpg)  
_RCA_  
Used primarily with consumer equipment  
Audio: no

_BNC_  
Seen with professional broadcast and production equipment, some consumer electronics  
Audio: no  

![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/SCART_20050724_002.jpg/320px-SCART_20050724_002.jpg)  
_SCART_  
European 21-pin connector designed to be capable of carrying both input and output of multiple signal standards; a YPbPr pinout is possible with a SCART connector but extremely rare as European monitors generally did not support YPbPr input.  
Audio: yes, stereo, unbalanced  

#### S-Video ####
S-Video (sometimes known as "separate video") cables carry video over two synchronized signal channels: Y (luma) and C (chroma, including saturation and hue). It can achieve better image quality than composite but lower color resolution than component RGB or YPbPr video. Most often associated with S-VHS but found with many other consumer deck formats as well.  

**Introduced:**  
**Max resolution:** Standard Definition (generally 480i or 576i)  
**Connectors and ports:**  
![](https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/S-video-connection.jpg/320px-S-video-connection.jpg)  
_Mini-DIN 4-pin_  
The most common type of S-Video connector. The exact same mini-DIN connector is used for the [Apple Desktop Bus] (README.md#apple-desktop-bus) data protocol and these cables are interchangeable.  
Audio: no  

_BNC_  
Generally for use in some S-Video patch panels.  
Audio: no

![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/SCART_20050724_002.jpg/320px-SCART_20050724_002.jpg)  
_SCART_  
European 21-pin connector designed to be capable of carrying both input and output of multiple signal standards; an S-Video pinout is possible with a SCART connector but rare, as European monitors generally did not support S-Video input.  
Audio: yes, stereo, unbalanced  

#### RGBS ####
A component video standard in which luminance and chrominance information is encoded into three channels (red, green and blue) and a fourth is used for composite sync (vertical and horizontal sync encoded together on the same wire). RGBS utilizes no compression and has no particular limit on color depth or resolution, but requires a high bandwidth as the three channels carry much redundant information (i.e. the same black-and-white luma information repeated three times). Extremely common in European equipment (especially monitors), rare elsewhere.  

**Introduced:**  
**Max resolution:** Generally up to 1080p (HD), but can go beyond  
**Connectors and ports:**  
![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/SCART_20050724_002.jpg/320px-SCART_20050724_002.jpg)  
_SCART_  
European 21-pin connector designed to be capable of carrying both input and output of multiple signal standards. RGBS cables most frequently have SCART connectors and vice versa.  
Audio: yes, stereo, unbalanced  

#### RGBVH ####
A component video standard essentially the same as [RGBS] (README.md#rgbs), except the sync signal is split into vertical and horizontal sync on separate wires. Most frequently employed in the context of the Video Graphics Array (VGA) display standard.  

**Introduced:**  
**Max resolution:** Generally up to 1080p (HD), but can go beyond  
**Connectors and ports:**  
![](https://upload.wikimedia.org/wikipedia/commons/thumb/8/81/Vga-cable.jpg/320px-Vga-cable.jpg)  
_VGA (DE-15)_  
A 15-pin D-sub connector commonly offered on modern computers for display connections.  
Audio: no  

_Mini-VGA_  
Used to adapt VGA/RGBVH signals input and output for laptop computers.  
Audio: no  

_BNC_  
Found with some high-end monitors and video cards. Wires are usually color-coded, though the colors used for the two sync signals sometimes varies: e.g. yellow (H) and white (V), yellow (H) and black (V), gray (H) and black (V).  
Audio: no  

_DVI-A_  
Much more frequently found in its [DVI-D] (README.md#dvi) and [DVI-I] (README.md#DVI-I) flavors, Digital Video Interface (DVI) is designed to transmit uncompressed digital video information, but can be compatible with analog RGBVH video through the VGA interface. DVI-A (analog) cables and connectors are essentially the same electrically as VGA cables and connectors.  
Audio: no  

_Mini-DVI_  
Used on certain Apple computers, especially laptops, to accept a DVI-A/VGA connection.  
Audio: no  

### Digital ###
#### SDI ####
#### FireWire ####
#### DVI ####
#### DisplayPort ####
#### HDMI ####
### Integrated ###
#### DVI-I ####


## Audio ##
### Analog ###
#### Balanced ####
#### Unbalanced ####
### Digital ###
#### AES-3 ####
##### Balanced #####
##### Unbalanced #####
#### SPDIF ####
##### Optical #####
##### Unbalanced #####
#### MIDI ####
##### Balanced ######
#### TDIF ####
##### Unbalanced ######
#### ADAT ####
##### Optical #####


## Data ##
### Parallel ###
#### PATA ####
#### Parallel SCSI ####
#### IEEE 1284 ####
### Serial ###
#### RS-232 ####
#### RS-422 ####
#### Serial SCSI ####
#### SATA ####
#### Apple Desktop Bus ####
#### PS2 ####
#### USB ####
##### USB 2.0 #####
##### USB 3.0 #####
##### USB 3.1 #####
#### FireWire ####
##### FireWire 400 #####
##### FireWire 800 #####
#### ThunderBolt ####
##### ThunderBolt 1 and 2 #####
##### ThunderBolt 3 #####
#### HDBaseT ####


## Power ##
