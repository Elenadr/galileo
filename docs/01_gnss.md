
## GNSS
Global Navigation Satellite System, refers to any satellte constellation that provides global positioning, navigation and timing services.

There are several GNSS:
* Galileo --> European GNSS
* GPS (Global Positioning System) --> USA GNSS
* GLONASS --> Russia's GNSS constellation
* BeiDou --> China's GNSS constellation
* QZSS (Quasi-Zenith Satellite System) --> Japan's GNSS

## Hystory and need
* 1957 - the Soviet Union launched **Sputnik 1**, the first artificial satellite. It emitted radio signals that led to the discovery of the **Doppler effect**, which allowed for tracking satellite positions from the ground.
  
![](https://github.com/Elenadr/galileo/blob/main/img/sputnik.jpg?raw=true)
Sputnik 1
  
* 1960 - U.S. Navy launched Transit, also known as NAVSAT or NNSS (for Navy Navigation Satellite System), the first satellite navigation system. First successful tests of the system were made also in this year.
![](https://github.com/Elenadr/galileo/blob/main/img/transit1b.jpg?raw=true)

Transit 1B


* 1964 - the system entered Naval service in.
* 1968 - A fully operational constellation of 36 satellites was in place.
* 1973 - GPS Project is started by the US Department of Defense, to create a satellite-based navigation system tha overcome the previous limitations.
* 1976 - **URSS** The Soviet Union signs the official decree to begin the development of GLONASS.
* 1978 - **EEUU** First GPS satellite experimental is launched (Block-I)
* 1982 - **URSS** First GLONASS satellite, Kosmos 1413 is launched.
* 1983 - **EEUU** After the KAL 007 flight tragedy , Ronald Reagan announces GPS will be available for civil use
* 1993 - **EEUU** GPS is declared IOC, Initial Operational Capabilities.
* 1993 — **Europe** The European Commission and ESA officially propose Galileo to ensure European technological independence.
* 1995 - **EEUU** GPS is declared FOC, Fully Operational Capabilities
* 1995 — **Russia** GLONASS reaches its full constellation of 24 satellites for the first time.
* 2000 — **USA** "Selective Availability" (SA) is turned off. This instantly improved civilian GPS accuracy from 100m to roughly 20m.
* 2000 — **China** Launch of the first BeiDou-1 experimental satellite (a regional, active-based system).
* 2003 — **Europe** Official signing of the framework and funding for the Galileo project.
* 2005 — **Europe** Launch of GIOVE-A, the first Galileo test satellite, to secure radio frequencies.
* 2011 — **Russia** After a period of decline following the fall of the USSR, GLONASS restores its full global constellation (24 satellites).
* 2012 — **China** BeiDou-2 begins providing regional services to the Asia-Pacific area.
* 2016 — ** Europe** Galileo launches its "Initial Services," allowing compatible smartphones to use its signals for the first time.
* 2018 — **China** Accelerated launches complete the BeiDou-3 global constellation.
* 2020 — **China** BeiDou is officially declared complete and fully operational worldwide, featuring more satellites than GPS.
* 2023 — **Europe** Galileo launches its High Accuracy Service (HAS), offering decimeter-level precision (approx. 20cm) for free.

## GNSS kEY Differences
Understanding the distinctions between the world's primary GNSS constellations—GPS, Galileo, GLONASS, and BeiDou—is crucial for appreciating their unique contributions and the benefits of modern multi-constellation receivers.

---

## 1. Comparative Analysis Table

| Feature | **GPS (USA)** | **Galileo (EU)** | **GLONASS (Russia)** | **BeiDou (China)** |
| :--- | :--- | :--- | :--- | :--- |
| **Control Entity** | Military (DoD) | **Civilian (ESA/EC)** | Military (Roscosmos) | Military (CNSA) |
| **Primary Goal** | Dual-use (Mil/Civ) | **Purely Civilian** | Dual-use (Mil/Civ) | Dual-use (Mil/Civ) |
| **Satellites** | ~31 | ~28 | ~24 | ~35 |
| **Orbital Planes** | 6 | 3 | 3 | Hybrid (MEO, IGSO, GEO) |
| **Inclination** | 55° | 56° | **64.8° (Polar)** | 55° (Global MEO) |
| **Accuracy (Civ)** | ~3.5m | **< 1m** | ~5-10m | ~2-5m |
| **Special Feature** | Industry Standard | **High Accuracy (HAS)** | High Latitude Coverage | Short Message Service |

---

![](https://github.com/Elenadr/galileo/blob/main/img/GNSS.jpg?raw=true)
GNSS Differences


## 2. Key Differentiating Factors

### 2.1. Governance and Sovereignty
* **Military-Controlled:** GPS, GLONASS, and BeiDou were born as defense projects. The controlling nations can implement "denial of service" or signal degradation in specific geographic zones during geopolitical conflicts.
* **Civilian-Controlled:** **Galileo** is unique as the only system worldwide designed and managed by civilian authorities. It ensures that essential services (transport, banking, emergency) remain independent of foreign military policy.

### 2.2. Orbital Geometry and Latitudes
The way satellites are positioned affects where they work best:
* **High Latitudes:** **GLONASS** is the most effective system for polar regions (Northern Canada, Russia, Scandinavia) because its satellites fly at a higher inclination (64.8°), putting them "higher" in the sky when viewed from the poles.
* **Regional Augmentation:** **BeiDou** uses a "Hybrid" constellation. While others only use MEO satellites, BeiDou includes **GEO (Geosynchronous)** satellites that stay fixed over China, providing extra precision and a unique two-way messaging service in the Asia-Pacific region.

### 2.3. Signal Precision and Technology
* **Modern Modulation:** Galileo uses **MBOC (Multiplexed Binary Offset Carrier)** modulation. This technical design reduces "multipath errors"—the interference caused by satellite signals bouncing off glass buildings in "urban canyons."
* **High Accuracy Service (HAS):** As of 2023, Galileo provides the **HAS** (High Accuracy Service), delivering decimeter-level precision (~20cm) globally and for free. Standard GPS requires paid subscriptions or internet-based corrections (DGPS/RTK) to achieve similar results.

---

## 3. The Power of "Multi-GNSS"
Modern receivers (smartphones, drones, tractors) do not choose just one system. They use **Interoperability**, combining signals from all four constellations simultaneously.

**Benefits include:**
1. **Reduced Time-To-First-Fix (TTFF):** Faster location locking.
2. **Redundancy:** If one system is degraded, others compensate.
3. **Better Geometry:** With 4 constellations, there are almost always 10-15+ satellites visible, even in deep valleys or city centers.

   
### Bibliografy

* [Euspa](https://www.euspa.europa.eu/eu-space-programme/galileo/what-gnss)
* [Cambridge University](https://www.cambridge.org/core/journals/journal-of-navigation/article/abs/brief-history-of-global-navigation-satellite-systems/F3B51AED21EAD7459CA7A09E4C37E765)
* https://www.duncan-parnell.com/blog/282/past-present-future-of-gnss-technology?srsltid=AfmBOooj23G-g5WC3GYytCj-gJ_1gLof0-7MplXLeMo5TvlIpB7nzkQK



