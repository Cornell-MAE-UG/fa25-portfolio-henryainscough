---
layout: project
title: "Heat Exchanger Lab: Parallel, Counterflow, and different speeds"
date: 11/19/2025
tags: [thermodynamics, heat-transfer, lab]
---

## Overview

In this lab I characterized the performance of a small liquid–liquid heat exchanger for different flow
configurations. I measured inlet and outlet temperatures on the hot and cold sides and compared how well
each configuration transferred heat.

The three configurations were:

1. **Parallel flow**
2. **Counterflow**
3. **Different Speeds**

The raw data were recorded by hand, but here is it written up.

---

## Experimental Setup

- **Working fluid:** water on both hot and cold sides  
- **Instrumentation:** thermocouples at each inlet and outlet  
- **Measured quantities:**
  - \(T_{h,in}\) – hot-side inlet temperature  
  - \(T_{c,in}\) – cold-side inlet temperature  
  - \(T_{h,out}\) – hot-side outlet temperature  
  - \(T_{c,out}\) – cold-side outlet temperature  

Flow rates were held approximately constant between runs so that differences in performance are
primarily due to the temperature driving force and flow arrangement.

---

## Results

### Measured Temperatures

| Test | Configuration | \(T_{h,in}\) (°C) | \(T_{c,in}\) (°C) | \(T_{h,out}\) (°C) | \(T_{c,out}\) (°C) |
|------|---------------|-------------------|-------------------|--------------------|--------------------|
| 1    | Parallel      | 43.3              | 9.3               | 33.0               | 9.3                |
| 2    | Counterflow   | 35.4              | 15.6              | 25.6               | 23.8               |
| 3    | Slower Speed  | 35.3              | 13.1              | 26.5               | 21.4               |

From these measurements I can look at how much each stream warmed or cooled:

| Test | \(\Delta T_h = T_{h,in}-T_{h,out}\) (°C) | \(\Delta T_c = T_{c,out}-T_{c,in}\) (°C) |
|------|------------------------------------------|-------------------------------------------|
| 1    | 10.3                                     | 0.0                                       |
| 2    | 9.8                                      | 8.2                                       |
| 3    | 8.8                                      | 8.3                                       |

### Discussion

- **Test 1 – Parallel flow:**  
  The hot stream cooled by about 10 °C, but the cold stream barely warmed. This suggests that the
  temperature driving force is concentrated near the inlets, and a lot of the heat capacity on the cold
  side is unused.

- **Test 2 – Counterflow:**  
  Both streams change temperature significantly (≈ 10 °C on the hot side and ≈ 8 °C on the cold side),
  which indicates that the configuration improves the contact between the streams compared with simple
  parallel flow.

- **Test 3 – Slower Speed:**  
  The hot and cold streams both undergo ~9 °C temperature changes. Counterflow arrangements are known to
  give the largest log-mean temperature difference, so this configuration is expected to be more effective
  at using the available heat transfer area.

*Note:* In a longer report, I would also:

- Calculate the **heat transfer rate** \( \dot Q \) on each side using measured mass flow rates.  
- Use the **log-mean temperature difference (LMTD)** method to estimate an overall heat transfer
  coefficient \( U \).  
- Compare the **effectiveness** \( \varepsilon \) of parallel vs. counterflow using the NTU–effectiveness
  method.

---

## Takeaways

- Flow arrangement has a strong impact on how effectively a heat exchanger can transfer energy between two
  streams.
- Parallel flow may cool the hot fluid but does not necessarily heat the cold fluid efficiently.
- Mixed and counterflow arrangements make better use of the available temperature difference and area,
  which is important in applications where we want to recover as much energy as possible.

