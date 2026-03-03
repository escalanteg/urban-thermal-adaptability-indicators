## MRT Validation with ground data – Córdoba, Argentina

In this section, ground data is used to validate results of MRT estimating in Córdoba, Argentina 

This section describes the in-situ measurements used to validate the estimated Mean Radiant Temperature (MRT) in Córdoba, Argentina.

---

### Instruments used

Field measurements were carried out using two black globe thermometers and two anemometers, allowing parallel measurements at different locations within the city.

#### Black Globe Thermometers
- **Thermometer 1:** Sper Scientific 800036 (40 mm globe)
- **Thermometer 2:** TM-188D TENMARS (50 mm globe)

#### Anemometers
- **Anemometer 1:** HP-878 cup anemometer
- **Anemometer 2:** TL-300 mini handheld anemometer

---

### Instrument Intercomparison

Since the instruments differ in brand and technical specifications, an intercomparison analysis was conducted before collecting validation data. Parallel measurements under identical environmental conditions were performed to quantify systematic differences.

 - in notebook `3.4.4.2.differences-t1-t2` the differences in Globe Temperature (TG) variable of the thermometers is analyzed
 - in notebook `3.4.4.4.wind-a1-a2` the difference in the wind speed variable of the anemometers is analyzed

Based on these analyses, correction criteria were defined to ensure comparable measurements.

---

### Shadow vs. Sun Exposure Test

To evaluate the effect of solar exposure on Globe Temperature (TG), both thermometers were placed at the same location (identical environmental context), with:
- One instrument under direct solar radiation
- The other instrument under shade

A total of 38 TG measurements were recorded over a 30-minute period.

- `3.4.4.3.shadow-sun`

---

### MRT Validation

The final validation of predicted MRT values for Córdoba is performed in:

- `3.4.4.1.validation-2026`

This notebook integrates corrected ground measurements and compares them against modeled MRT.



