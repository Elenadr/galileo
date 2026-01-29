# Galileo GNSS: Signals, Services, and Frequencies

Galileo is the European Global Navigation Satellite System. Unlike other systems, it was designed from the ground up for civilian use, offering highly stable signals and innovative services that were not available in legacy systems like GPS.

![](https://github.com/Elenadr/galileo/blob/main/img/satellite.jpg?raw=true)
Galileo Satellite

---

## 1. Galileo Services
Galileo does not just provide a single "position." It offers different levels of service depending on the user's needs:
![](https://github.com/Elenadr/galileo/blob/main/img/Galileo%services.png?raw=true)
Galileo Services
* **Open Service (OS):** The free-to-access service used by smartphones and car navigation. It provides positioning and timing.
* **High Accuracy Service (HAS):** A unique, free service that provides decimeter-level accuracy (approx. 20cm) globally. It is transmitted directly via the E6 signal.
* **Public Regulated Service (PRS):** An encrypted, robust service restricted to government-authorized users (police, military, emergency services). It is designed to be highly resistant to jamming.
* **Search and Rescue (SAR):** Galileo is part of the Cospas-Sarsat system. It can pick up distress signals from beacons and, uniquely, send a "Return Link" message back to the user to confirm help is on the way.

---

## 2. Frequency Plan
Galileo operates in three main frequency bands. Using multiple frequencies allows receivers to cancel out "ionospheric error" (distortions from the atmosphere).



| Band | Frequency | Primary Use |
| :--- | :--- | :--- |
| **E1** | 1575.42 MHz | The "Common" band. Shared with GPS (L1). Used by all smartphones. |
| **E5 (E5a / E5b)** | 1176 - 1207 MHz | The "Advanced" band. High-precision and very resistant to signal reflections (multipath). |
| **E6** | 1278.75 MHz | The "Professional" band. Used for High Accuracy (HAS) and encrypted PRS services. |

---

## 3. Signal Characteristics (High Level)
Why are Galileo signals considered superior for modern use?

### A. Multiplexed Binary Offset Carrier (MBOC)
This is the "shape" of the signal. Galileo E1 uses a specific modulation that makes it easier for a receiver to distinguish the "true" signal from "echoes" (signals bouncing off buildings). This is why Galileo is much more accurate in big cities (urban canyons).

### B. Message Authentication (OSNMA)
Galileo is the first GNSS to introduce **Open Service Navigation Message Authentication**. This adds a digital signature to the signal, making it much harder for hackers to "spoof" (fake) the signal to lead a ship or car off course.

### C. The "Triple Frequency" Advantage
By providing signals across E1, E5, and E6 simultaneously, Galileo allows professional devices to calculate their position with extreme stability, even during solar storms or atmospheric disturbances.

# Bibliography and References

## 1. Official GNSS Providers & Documentation

* **European Union Agency for the Space Programme (EUSPA).** *Galileo Services Overview.* Available at: [https://www.euspa.europa.eu/european-space/galileo/services](https://www.euspa.europa.eu/european-space/galileo/services)
* **European Space Agency (ESA).** *Galileo Navigation - Technical Manuals.* Available at: [https://www.esa.int/Applications/Navigation/Galileo](https://www.esa.int/Applications/Navigation/Galileo)
* **U.S. Coast Guard Navigation Center.** *GPS Global Positioning System Standard Positioning Service Performance Standard.* Available at: [https://www.gps.gov/technical/ps/](https://www.gps.gov/technical/ps/)
* **Russian Federal Space Agency (Roscosmos).** *GLONASS Interface Control Document.* Available at: [https://www.glonass-iac.ru/en/](https://www.glonass-iac.ru/en/)
* **China Satellite Navigation Office (CSNO).** *BeiDou Navigation Satellite System Signal In Space Interface Control Document.* Available at: [http://en.beidou.gov.cn/SYSTEMS/ICD/](http://en.beidou.gov.cn/SYSTEMS/ICD/)

## 2. Technical Standards and White Papers

* **European Union (2023).** *Galileo High Accuracy Service (HAS) Info Note.* [Online Resource].
* **Hofmann-Wellenhof, B., Lichtenegger, H., & Wasle, E.** *GNSS – Global Navigation Satellite Systems: GPS, GLONASS, Galileo, and more.* Springer-Verlag Wien.
* **Teunissen, P. J., & Montenbruck, O.** *Springer Handbook of Global Navigation Satellite Systems.* Springer Nature.

## 3. Educational Resources

* **ESA Navipedia.** *The Reference Wiki for Global Navigation Satellite Systems.* Available at: [https://gssc.esa.int/navipedia/](https://gssc.esa.int/navipedia/)
* **GSA (now EUSPA).** *GNSS User Technology Report.* Issued periodically to track the evolution of receivers and constellations.

