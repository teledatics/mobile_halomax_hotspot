## How to Create a Long Range HaloMax™ Mobile Hotspot

Creating a mobile hotspot to provide wide coverage over many miles is straightforward with the right components.

![HaloMax™ Mobile Hotspot](https://github.com/teledatics/mobile_halomax_hotspot/blob/main/images/HaloMaxHotSpot.png)

### Hotspot Components:

- **Raspberry Pi Model 4**
- **HaloMax™ TD-WRLS**
- **TE Conectivity Antenna**
	- [900 MHz 6 dBi Omni](https://www.te.com/en/product-S8964B.html)
- **Battery**
	- [Mobile Power Bank](https://www.amazon.com/gp/product/B0CTHG2JRW)
- **Tripod**
	- [Universal Foldable Tripod](https://www.amazon.com/Pivo-Tripod-Extendable-Universal-Accessory/dp/B08C2BLNH4)
- **Cables and connectors**
	- [USB-A to A Cable](https://www.amazon.com/dp/B0C9J1QQV1)
	- [USB-C Cables](https://www.amazon.com/gp/product/B0B5DRS1LZ)
	- [USB-C Power Injector](https://www.amazon.com/gp/product/B0CYZS4RSW)
	- [u.FL to N-connector Pigtail](https://www.amazon.com/wlaniot-Pigtail-Wireless-Gateway-External/dp/B08ZYK5SL9)
	- [N-connector Antenna Cable](https://www.amazon.com/dp/B07YCS2DVD)
- **3D Printed Components**
	- [HaloMax™ Case & Mounts](https://www.printables.com/model/963148-wi-fi-halow-hotspo-case-and-mounts)

![HaloMax™ Mobile Hotspot](https://github.com/teledatics/mobile_halomax_hotspot/blob/main/images/Portable_HaLow_Tripod.jpg)

### Step-by-Step Setup:

1. **Download the Pi Image**:
   - Download the [pre-configured Raspberry Pi image](https://teledatics.com/image/RPiHalomaxHotspot.zip) from the Teledatics website to ensure compatibility and ease of setup.

2. **Assemble the Components**:
   - Mount the Raspberry Pi and TD-WRLS to the 3D printed enclosure. Ensure the enclosure is securely attached to the tripod.
   - Connect the TEC antenna to the HaloMax™ module using the antenna cable and pigtail.

3. **Power and Connect**:
   - Use USB-C cables and the power injector to connect the Raspberry Pi and HaloMax™ module to the mobile power bank.
   - Ensure all connections are secure and the devices are powered on.

4. **Deploy and Test**:
   - Place the assembled setup in your desired location. The tripod ensures stability in various terrains.
   - Test the network to ensure the hotspot is operational and providing adequate coverage.

### Example Application:
During a large outdoor event, HaloMax™ Mobile Hotspots can be strategically placed to provide robust Wi-Fi communication across wide areas. This setup ensures participants can stay connected, share information, and reach each other via Smartphone Wi-Fi calling.

![Large Scale Event](https://github.com/teledatics/mobile_halomax_hotspot/blob/main/images/large_scale_event.jpg)

**Enhanced Connectivity:**
With the addition of a Starlink terminal, these mobile hotspots ensure continuous internet access, regardless of location, making them ideal for both planned events and emergency situations.

**Open Source Video and Audio Calling:**
Download the [Linphone app](https://www.linphone.org/) to your smartphone and enjoy live video* and audio calls through your HaloMax™ Mobile Hotspot network!

* we recommend qvga resolution