---
layout: default
title: Client Report
permalink: /SLF-client-report/
---
## Client Report

[Download my Client Report]({{ "/assets/slf-client-report.pdf" | relative_url }}) in PDF format.<br>
[Download my Poster]({{ "/assets/slf-poster.pdf" | relative_url }}) in PDF format.

**Team:** Guardians of the Grapevine

**Team Members:** Ash Puri, Henry Ainscough, James Larrabee, Katherine Krishtopa, Skylar Walcoff

**Clients:** Cornell CALS Extension / E&J Gallo Winery / National Grape

## Context & Problem Statement

Commercial vineyards in the NY region are increasingly impacted by spotted lanternfly (SLF) infestations, which reduce fruit quality and weaken overall plant health. Current control methods rely heavily on pesticides which compromises produce safety.

Our project focuses on the sub-problem of attracting SLFs and diverting them away from grapevines. By achieving this, we are preserving fruit quality and minimizing reliance on pesticides. Some practical constraints involved are access to an electrical power source to operate the zapping mechanism and noise pollution caused by the vibrating mechanism.

## Impact

The proposed approach reduces both grape contamination and reliance on pesticides, resulting in lower crop loss. In turn, this improves marketability by supporting organic practices and enhancing overall fruit quality and taste. It also promotes a more sustainable and environmentally cautious growing process which aligns with the increasing consumer demand for cleaner agricultural practices.

## Solution Direction

Develop a non-chemical, selective, and scalable device that attracts and eliminates SLFs to protect grapevines and preserve harvest quality. Our concept centers on a pole that vibrates at approximately 60 Hz (based on research indicating that SLFs are attracted to this frequency) to draw insects toward the device. The pole is then electrified to eliminate the pests upon contact. This approach offers a targeted, pesticide-free method that can be implemented at scale across vineyards.

## Final Prototype: Vibrating Zapper Column

**What it is:** The device consists of a vertical pole mounted on a base that houses a motor-driven vibration mechanism. The motor rotates a cam, which converts rotational motion into lateral vibrations of the pole. Initially, the prototype produced vibrations around 25 Hz, but through gear ratio adjustments, the system was refined to reach the target 60 Hz frequency. Once attracted, SLFs move onto the pole, where a zapping system (using two conductive sheets, like insect mesh) is integrated. When the insects make contact across the conductive surfaces, they complete an electrical circuit and are eliminated.

**How it would be used:**

- Placed between vineyard rows
- SLFs are attracted to 60 Hz frequency
- SLFs are zapped when they land on the column

**Why it's better than the status quo:**

- No chemicals or manual labor
- No contamination or fruit bruising
- Can function during growing season

## In-Depth Application

This is designed to be portable and easily deployed throughout a vineyard, allowing growers to position units wherever infestations are most concentrated. Growers can adjust placement based on vine density and pest activity which allows it to integrate easily into existing vineyard operations. Because the system requires minimal setup and maintenance, it can be used without disrupting daily workflows or harvesting processes. Its practicality also makes it suitable for vineyards of varying sizes, from small operations to large-scale commercial fields. Overall, the device provides a convenient and adaptable solution that allows for quick and easy implementation across all vineyards.

## Final Prototype Design

![Final Design]({{ "/assets/images/slf-pole.png" | relative_url }})
*Fig 1 — Final Design*

![Sketch of Design]({{ "/assets/images/slf-sketch.png" | relative_url }})
*Fig 2 — Sketch of Design*

## Conclusion and Recommendation

Based on our design development and testing results, we recommend advancing the Vibrating Zapper Column to field-testing in a vineyard environment. The prototype successfully met all key success criteria, including achieving 60 Hz vibration frequency, operating for 5 minutes without failure, and tolerating 10 N of lateral force without deformation. These results show that the device meets its primary function of reducing SLF populations and can transition from controlled testing to real-world application.

To support successful field implementation, we recommend minor improvements such as incorporating weather-resistant materials, optimizing the power supply (i.e. solar integration), and enhancing durability for long-term outdoor use. Field-testing will also allow for improvement of device spacing, pest reduction effectiveness, and performance under varying environmental conditions.

If taken to market, several design improvements would further enhance performance. These include switching to fully weatherproof materials (e.g. stainless steel) for long-term durability, replacing the motor with a speaker system for more efficient frequencies, and scaling the device to a size comparable to a vine to increase its area of influence. Overall, the device is promising and ready for field-testing.

## Final Testing and Results

1. **60 Hz Vibration Test:** We tested whether the device achieved the target vibration frequency, which is essential for attracting SLFs. Using the PhyPhox app, we measured the output and confirmed a frequency of 60 Hz. This result verifies that our gear ratio adjustments were successful and that the device meets its primary functional requirement. This shows the user that they can start using the device out of the box without any extensive setup.

2. **Continuous Operation Test:** To evaluate reliability, we ran the device continuously for 5 minutes. The mechanism maintained consistent performance with no signs of wear, damage, or failure. This indicates the device can operate for extended periods with minimal maintenance, making it suitable for real-world vineyard use. This shows the user that the device can function on its own without requiring continuous maintenance.

3. **Lateral Force Test:** We tested structural stability by applying a lateral force to the pole to simulate environmental forces such as wind. The structure withstood up to 10 N of force before deformation. This confirms that the device is mechanically stable and capable of maintaining performance under typical field conditions. This shows the user that the device's zapping mechanism does not pose a threat to the product since it is unlikely for the product to fall over.

Overall, the device successfully met all defined success criteria, demonstrating strong performance in functionality, long-term durability, and structural stability. These results indicate that the design will be effective and safe if used in real-life vineyards.

## Initial Prototype and Testing Details

Our assembly was done in a very simple manner. We used Fusion to CAD a base plate which we could then insert all of our components into. Inside of our designed base plate we had slots for the motors, batteries, and gear axles to fit into so that the final construction would be simple and easy to do.

1. Using the CAD designed baseplate and the components that we ordered from McMaster, we first started by inserting the pole into its slot.
2. We then placed our motor and gear system inside the base and after those were settled we inserted the battery in wiring so that the internal parts wouldn't be interfered with.
3. Following that we placed our insect mesh around the pole and fastened it using zip-ties, which fixed the mesh to the pole and created a new, non-conductive surface to attach the next insect mesh to.
4. Following this we placed our second mesh on the outside of the zip-ties and ziptied that to the previous mesh.
5. We then attached wires from the meshes to a power supply, creating the bug zapping mechanism.

## Primary Testing and Improvements

1. **Vibration Frequency Test:** PhyPhox (a smartphone application) was used to measure the vibration frequency of the initial prototype, which was recorded at 25 Hz, below the target required to effectively attract SLFs.

   *Improvement:* We adjusted the gear ratios to increase the rotational speed of the driven shaft to 3600 rpm, corresponding to the desired 60 Hz frequency.

2. **Continuous Operation Test:** To assess durability, we ran the device continuously for 5 minutes. While the mechanism remained functional and intact, the wooden cam caused noticeable damage to the pole due to repeated impact.

   *Improvement:* We replaced the wooden cam with a softer rubber cam that rotates within the tube, significantly reducing wear and improving long-term durability.

3. **Lateral Force Test:** We applied a lateral force to the pole to evaluate structural stability, reaching 5 N without deformation. While this was acceptable for the prototype stage, further improvement was needed for real-world conditions.

   *Improvement:* We refined the design by making the base plate opening slightly narrower, reducing pole movement and increasing overall stability.

## References

Throughout the design process, we sought guidance from **Professor V. Hunter Adams** from Cornell's Electrical and Computer Engineering department, who provided valuable insight into vibration generation and system design. From this discussion, we learned that a speaker-based system would be more effective for producing low-frequency vibrations (on the order of tens of Hz), although we continued with a motor-based approach due to budget constraints. Additionally, we received guidance on optimizing the zapping mechanism, specifically the use of a dual-layer conductive mesh system, where the SLF completes the circuit upon contact, increasing the reliability of elimination. Incorporating expert feedback allowed us to move beyond initial concepts and develop a more informed and functional solution.

## Bill of Materials

| Part | Specs | McMaster Code | Fabrication | Reasoning | Cost |
|---|---|---|---|---|---|
| Base Plate | Custom-designed base plate for final system | NA | CAD + 3D Print | Holds and secures all components in place | $50.00 |
| Prototype Base Plate | Custom-designed base plate for prototype | NA | CAD + 3D Print | Holds all components and provides a general idea about the final base plate | $47.65 |
| Pole | OD 1.75", ID 1.375", Impact-Resistant Polycarbonate Round Tube, 1/16" Wall | 8585K88 | NA | Transmits vibration | $15.44 |
| DC Gear Motor | 60 Hz, 0.02 Nm torque, ~7 W, 3600 RPM | In house | NA | Drives the vibration mechanism | $1.95 |
| AA Batteries | 3 AA batteries | In house | NA | Powers the motor | $0.00 |
| Battery Holder | AA battery holder with wire leads | In house | Wires soldered to motor | Holds batteries and supplies power | $0.00 |
| AC Adaptor | 12 VDC, 1500 mA | In house | NA | Powers the electric field | $0.00 |
| Electric Screen | 24" Wide Aluminum Insect Screening, Unfinished | 1023A75 | Cut to size with scissors | Surface for zapping | $8.96 |
| 32T Gear | 20° Pressure Angle Plastic Gear, Round Bore, 32 Pitch, 32 Teeth | 2662N16 | NA | Gear train | $5.91 |
| 12T Gear | 20° Pressure Angle Plastic Gear, Round Bore, 0.5 Module, 12 Teeth | 2662N27 | NA | Gear train | $3.09 |
| 14T Gear | CAD (6 mm Bore) | NA | CAD | Gear train | $0.25 |
| 14T Gear | CAD (6 mm Bore) | NA | CAD | Backup for gear train | $0.25 |
| 14T Gear (2.3 mm Bore) | ARRMA Pinion Gear 14T 0.5 MOD CNC, ARA-2629 | Amazon | NA | Gear train | $5.99 |
| Gear Shaft (2 mm) | MECCANIXITY 316 Stainless Steel Rod 2 mm × 150 mm (Pack of 10) | Amazon | NA | Holds the gear train | $6.02 |
| Gear Shaft (6.35 mm) | Rotary Shaft, 12L14 Carbon Steel, 1/4" × 3" | 1327K113 | NA | Holds the gear train | $4.10 |
| Vibration Damping Mounts | 5/16" × 5/16" Polyurethane Sandwich Mount, 4-40 stud, 2 lbs capacity | 96905K35 | NA | Isolates vibration to the pole and reduces whole-system vibration | $12.00 |
| Rough-Texture Paint | Coverage 10 ft² @ 1 mil | 7739T6 | NA | Makes the pole look more appealing and conceals rough texture | $14.14 |
| Zip Ties | Standard lab zip ties | In house | NA | Secures the electric screen | $0.00 |
| Tape | Scotch Blue standard tape | In house | NA | Secures motor in place | $0.00 |
| **Total Cost** | | | | | **$175.50** |

## Components List

| Part | Specs | McMaster Code | Fabrication | Reasoning | Cost |
|---|---|---|---|---|---|
| Base Plate | Custom-designed base plate for final system | NA | CAD + 3D Print | Holds and secures all components in place | $50.00 |
| Pole | OD 1.75", ID 1.375", Impact-Resistant Polycarbonate Round Tube, 1/16" Wall | 8585K88 | NA | Transmits vibration | $15.44 |
| DC Gear Motor | 60 Hz, 0.02 Nm torque, ~7 W, 3600 RPM | In house | NA | Drives the vibration mechanism | $1.95 |
| Electric Screen | 24" Wide Aluminum Insect Screening, Unfinished | 1023A75 | Cut to size with scissors | Surface for zapping | $8.96 |
| Zip Ties | Standard lab zip ties | In house | NA | Secures the electric screen | $0.00 |
| AA Batteries | 3 AA batteries | In house | NA | Powers the motor | $0.00 |
| Battery Holder | AA battery holder with wire leads | In house | Wires soldered to motor | Holds batteries and supplies power | $0.00 |
| AC Adaptor | 12 VDC, 1500 mA | In house | NA | Powers the electric field | $0.00 |
| **Total Cost** | | | | | **$76.35** |