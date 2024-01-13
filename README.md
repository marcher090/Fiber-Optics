# Fiber-Optics
![Diagram for PON Network](https://media.fs.com/images/community/erp/McQXJ_202401091639264BCW8.jpg)
![](https://media.fs.com/images/community/upload/kindEditor/202007/20/_1595239911_UJvUAgYQr0.jpg)
![](https://media.fs.com/images/community/upload/kindEditor/202007/20/_1595239772_WJgBUKb6MC.jpg)
![](https://cdn.bt-pon.com/wp-content/uploads/2021/12/fttx-architecture.png)

## Decible & Decible miliWatt 

**dB (Decibel)** The difference (or ratio) between two signal levels. Used to describe the effect of system devices on signal strength. For example, a cable has 6 dB signal loss or an amplifier has 15 dB of gain. This is useful since signal strengths vary logarithmically, not linearly. Since the dB scale is a logarithmic measure, it produces in simple numbers for large-scale variations in signals. It is very useful because system gains and losses can be calculated by adding and subtracting whole numbers. Every time you double (or halve) the power level, you add (or subtract) 3 dB to the power level. This corresponds to a 50% gain or reduction. 10 dB gain/loss corresponds to a ten-fold increase/decrease in signal level. A 20 dB gain/loss corresponds to a hundred-fold increase/decrease in signal level. In other words, a device (like a cable) that has 20 dB loss through it will lose 99% of its signal by the time it gets to the other side. Thus, big variations in signal levels are easily handled with simple digits.

**dBm (dB milliWatt)** A signal strength or power level. 0 dBm is defined as 1 mW (milliWatt) of power into a terminating load such as an antenna or power meter. Small signals are negative numbers (e.g. -83 dBm). For example, typical 802.11b WLAN cards have +15 dBm (32mW) of output power. They also spec a -83 dBm RX sensitivity (minimum RX signal level required for 11Mbps reception). Another example, 125 mW is 21 dBm and 250 mW is 24 dBm.

## Passive Optical Network 

In contrast to AON, multiple customers are connected to a single transceiver by means of a branching tree of fibers and passive splitter/combiner units, operating entirely in the optical domain and without power in PON.
There are two major current PON standards: Gigabit Passive Optical Network (GPON) and Ethernet Passive Optical Network (EPON).
A Gigabit Ethernet Passive Optical Network (GEPON) system is generally composed of an optical line terminal (OLT) at the service provider’s central office and a number of optical network units (ONUs) or optical network terminals (ONTs) near end users, as well as the optical splitter. In addition, the optical distribution network (ODN) is used during the transmission between OLT and ONU/ONT.

### Optical Line Terminal (OLT)
The main function of OLT is to control the information float across the ODN, going both directions, while being located in a central office. 
Maximum distance supported for transmitting across the ODN is 20 km. 
OLT has two float directions: upstream (getting an distributing different type of data and voice traffic from users) and downstream (getting data, voice and video traffic from metro network or from a long-haul network and send it to all ONT modules on the ODN.
### Optical Network Unit (ONU)
ONU converts optical signals transmitted via fiber to electrical signals. These electrical signals are then sent to individual subscribers. 
In general, there is a distance or other access network between ONU and end user’s premises. Furthermore, ONU can send, aggregate and groom different types of data coming from customer and send it upstream to the OLT. 
Grooming is the process that optimises and reorganises the data stream so it would be delivered more efficient. OLT supports bandwidth allocation that allows to make smooth delivery of data float to the OLT, that usually arrives in bursts from customer. 
ONU could be connected by various methods and cable types, like twisted-pair copper wire, coaxial cable, optical fiber or Wi-Fi.
### Optical Network Terminal (ONT)
Actually, ONT is the same as ONU in essence. ONT is an ITU-T term, whereas ONU is an IEEE term. They both refer to the user side equipment in GEPON system. But in practice, there is a little difference between ONT and ONU according to their location. ONT is generally on customer premises.

## Fiber-Based Access Scenarios (FTTx)
[source](https://www.cisco.com/c/en/us/products/collateral/interfaces-modules/transceiver-modules/datasheet-c78-736392.html)
- Fiber to the home (FTTH)
- Fiber to the building (FTTB)
- Fiber to the curb (FTTC)
- Fiber to the cell (FTTc)
- Fiber to the business (FTTb)
