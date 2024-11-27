# Path-Loss-measumerent

This proyect outlines the methodology, results, analysis, and key conclusions of the path loss measurement project conducted for a telecommunications antenna situated in the central area of Santiago, Chile. The project focuses on evaluating the signal degradation, or path loss, experienced by radio waves as they propagate from the antenna across the urban environment. This study provides insights into the performance of the antenna, considering various environmental factors and urban challenges. We will delve into the techniques used for measurement, the data collected, and the implications of these findings for improving communication network efficiency in the city.

The primary objective of this project is to analyze and quantify the path loss of a telecommunications antenna located in the central area of Santiago, Chile. This includes understanding how signal strength deteriorates over distance and identifying the factors contributing to this degradation, particularly in dense urban environments. The results aim to enhance the efficiency and reliability of urban communication networks.

Secondary objectives include:

Evaluating the impact of urban infrastructure, such as buildings and street layouts, on signal propagation.
Assessing the effectiveness of empirical path loss models, such as Okumura-Hata and Friis, by comparing their predictions with measured data.
Developing tools and methodologies for systematic data collection, analysis, and visualization of path loss metrics.
Providing actionable insights for optimizing antenna placement and network design in similar urban settings.

# Theoretical Framework

## Key parameters in antenna radiation efficiency:

Antenna radiation efficiency is a fundamental metric that determines how effectively an antenna converts input power into radiated electromagnetic energy. Several key parameters influence this efficiency, including Antenna Gain, Directivity, Polarization, Impedance, and Material Efficiency. These parameters collectively define the performance and suitability of an antenna for specific applications in wireless communication.:

1. Antenna Gain
Antenna gain measures the ability of an antenna to focus radiated energy in a particular direction, relative to an isotropic radiator. It is expressed in decibels (dBi) and combines the effects of both directivity and radiation efficiency. High-gain antennas are preferred in applications where focused energy is required, such as long-distance communication, while low-gain antennas are better suited for omnidirectional coverage.

2. Directivity
Directivity quantifies how concentrated an antenna's radiation pattern is in a specific direction compared to an isotropic source. It is a critical parameter for determining the angular distribution of radiated power. Antennas with high directivity are ideal for point-to-point communication systems, as they minimize energy loss in undesired directions and enhance signal strength in the intended direction.

3. Polarization
Polarization refers to the orientation of the electric field vector in the radiated electromagnetic wave. It can be linear, circular, or elliptical, depending on the antenna design and application requirements. The polarization of the transmitting and receiving antennas must match to maximize signal reception. Polarization mismatches lead to losses and reduced radiation efficiency, making polarization a vital factor in antenna design.

4. Impedance
The impedance of an antenna, typically expressed in ohms, characterizes its opposition to current flow. For optimal performance, the impedance of the antenna must match that of the transmission line or feeding network. Impedance mismatches result in reflections and standing waves, which reduce radiation efficiency. Impedance matching techniques, such as the use of matching networks, are often employed to mitigate these losses.

5. Material Efficiency
Material efficiency describes the impact of the materials used in the construction of the antenna on its performance. Conductors with high conductivity and low resistance, such as copper or aluminum, are commonly used to minimize resistive losses. Additionally, dielectric materials used in antenna substrates must exhibit low loss tangents to ensure minimal energy dissipation. The choice of materials directly affects the overall efficiency and durability of the antenna.

By understanding and optimizing these parameters, antenna designers can enhance radiation efficiency, ensuring that antennas meet the performance demands of modern communication systems. These considerations are especially critical in applications requiring high power efficiency, minimal losses, and reliable signal transmission over varying distances and environments.

## Impact of Urban Environments on Communication Systems:

The performance and reliability of the telecommunications systems are significantly influenced by various propagation phenomena, including Building Attenuation, Reflection, Diffraction, Scattering, and Shadowing. Understanding these effects is crucial for designing robust communication networks in urban areas.

1. Building Attenuation
Building attenuation refers to the reduction in signal strength as electromagnetic waves penetrate through structures such as walls, windows, and roofs. The degree of attenuation depends on the material properties, thickness, and frequency of the transmitted signal. For instance, concrete and metal structures exhibit higher attenuation compared to glass or wood.

2. Reflection
Reflection occurs when electromagnetic waves encounter smooth surfaces, such as glass façades or metallic structures, and are redirected without significant penetration. While reflection can create multiple paths for the signal to reach the receiver, it may also result in phase shifts and interference, known as multipath fading.

4. Diffraction
Diffraction describes the bending of electromagnetic waves around obstacles, enabling signal propagation even when the direct line of sight (LOS) is blocked. In urban settings, diffraction commonly occurs around the edges of buildings and other large objects.

5. Scattering
Scattering results from the interaction of electromagnetic waves with small, irregular objects such as street signs, foliage, or vehicles. It causes the signal to disperse in multiple directions, which can either enhance coverage by creating additional paths or degrade performance due to increased noise and interference.

6. Shadowing
Shadowing occurs when obstacles completely block the direct path of the signal, creating zones of reduced signal strength or complete loss of connectivity. The extent of shadowing depends on the size and material properties of the obstructing object, as well as the frequency of the signal. Shadowing can create dead zones in urban networks, requiring strategic placement of base stations or repeaters to ensure continuous coverage.

In summary, urban environments introduce a range of propagation challenges that significantly impact signal quality, reliability, and network performance. Effective communication system design must account for these phenomena, employing advanced modeling techniques and technologies such as adaptive beamforming, multiple-input multiple-output (MIMO), and small cell deployments to overcome the limitations posed by urban infrastructure.

## Phenomenon of Power Loss (Path Loss)

Path loss, or power loss, is a fundamental phenomenon in wireless communication systems that describes the attenuation of a signal as it propagates from the transmitter to the receiver. This attenuation increases with the distance between the two points, posing a significant challenge for maintaining reliable connectivity, especially in large-scale networks or adverse environments. 

1. Distance
Distance is the most intuitive factor affecting path loss. As the separation between the transmitter and receiver increases, the signal's power diminishes due to the spreading of the wavefront in space, a phenomenon quantified by the inverse square law. Free-space path loss (FSPL) models provide a mathematical representation of this relationship, showing that signal strength decreases proportionally to the square of the distance in an ideal, obstruction-free environment.

2. Operating Frequency
The frequency of operation plays a critical role in determining the extent of path loss. Higher-frequency signals, such as those used in millimeter-wave communication, are more susceptible to attenuation due to atmospheric absorption, rain, and other environmental factors.

3. Environment
The surrounding environment introduces significant variability in path loss. Open areas, such as rural landscapes, typically exhibit lower path loss compared to dense urban environments, where obstacles like buildings, trees, and vehicles cause additional attenuation through phenomena such as reflection, diffraction, and scattering. Similarly, indoor environments often involve complex multipath propagation due to walls and furniture, leading to unpredictable variations in signal strength. 

# Methodology

## Field Measurements: Data collection in an urban environment

To capture real world signal behavior, field measurements were conducted along a designated urban street, the antenna is located at the intersection of Domyeko and Republica streets in a central area of ​​Santiago de Chile. Measurement points were systematically spaced at intervals of 10 meters with Google Street, covering a range of distances from the transmitter. At each point, 100 individual measurements were recorded to ensure statistical robustness.

The measured parameters included Reference Signal Received Power (RSRP), Signal-to-Noise and Interference Ratio (SINR), RSRQ,	CE,	BER,	Tempeture and	humidity. These data were collected using calibrated measurement equipment to ensure accuracy and consistency.

## Methodological Challenges: Errors and Uncertainties

1. While field measurements provide valuable empirical data, various factors contribute to potential errors and uncertainties:

2. Street Traffic: Vehicular movement introduce dynamic obstructions and scattering effects, causing variations in signal strength.

3. Weather Conditions: Fluctuations in atmospheric conditions, such as humidity and temperature, may affect signal propagation during measurements.

Environmental Changes: Temporary obstacles, such as parked vehicles or construction activities, can alter the propagation path and lead to deviations from theoretical predictions.


## Comparative Analysis

The study involves generating two distinct path loss curves:

1. Theoretical Path Loss: Derived from the models implemented in Radio Mobile and traditional formulas, representing the ideal propagation scenario.

2. Measured Path Loss: Based on empirical data collected during fieldwork, reflecting real-world signal attenuation in an urban street environment.

Both curves are analyzed and compared to identify discrepancies and validate the accuracy of the theoretical models.

## Teorical models

### Friss

$$
P_r \, \text{(dBm)} = P_t \, \text{(dBm)} - \left[20 \log_{10}(d) + 20 \log_{10}(f) + 20 \log_{10}\left(\frac{4\pi}{c}\right)\right]
$$

**Where:**
- $P_r$: Received power in dBm.  
- $\P_t\$: Transmitted power in dBm.  
- $\d\$: Distance between transmitter and receiver (m).  
- $\f\$: Operating frequency (Hz).  
- $\c\$: Speed of light (\(3 \times 10^8 \, \text{m/s}\)).  

### Okomura-Hata

$$
P_r \, \text{(dBm)} = P_t \, \text{(dBm)} - \left[69.55 + 26.16 \log_{10}(f) - 13.82 \log_{10}(h_b) - a(h_r) + \left(44.9 - 6.55 \log_{10}(h_b)\right)\log_{10}(d)\right]
$$


**Where:**
- $\P_r\$: Received power in dBm.  
- $\P_t\$: Transmitted power in dBm.  
- $\f\$: Frequency (MHz).  
- $\h_b\$: Height of the transmitter antenna (m).  
- $\h_r\$: Height of the receiver antenna (m).  
- $\a(h_r)\$: Correction factor for receiver antenna height:
  $$
  a(h_r) = \begin{cases} 
  3.2 (\log_{10}(11.75 h_r))^2 - 4.97, & \text{if } f > 400 \, \text{MHz} \\ 
  8.29 (\log_{10}(1.54 h_r))^2 - 1.1, & \text{if } f \leq 400 \, \text{MHz}
  \end{cases}
  $$
- $\d\$: Distance between transmitter and receiver (km). 


## Simulation Integration

The simulated results obtained from Radio Mobile serve as an intermediary between the theoretical and measured curves. By incorporating terrain data and environmental parameters, the software provides a nuanced representation of signal propagation that accounts for some real world factors.

The final analysis juxtaposes the theoretical, simulated, and measured path loss curves to evaluate their alignment and identify the conditions under which each model performs optimally. This comparison is essential for refining propagation models and improving the predictability of wireless network performance in urban environments.

 


# Analysis



# Conclusion
