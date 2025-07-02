##  Case Study Summary: RIS-Aided Two-Cell Network

###  Objective
Evaluate how a Reconfigurable Intelligent Surface (RIS) placed between two neighboring cells can:
- Enhance desired signal strength
- Control inter-cell interference
- Trade-off performance when optimized for one user

---

###  Simulation Setup
- 2 Base Stations (BS1, BS2)
- 2 Users (U1 served by BS1, U2 by BS2)
- 1 RIS with N = 16 elements placed at cell boundary
- Simulated 3 scenarios:
  -  No RIS
  -  Random RIS
  -  RIS optimized for U1

---

###  Results (SNR in log scale)

| Scenario        | U1 SNR (Target) | U2 SNR (Neighbor) |
|-----------------|-----------------|-------------------|
| No RIS          | Lower (Direct only) | Decent (Direct only) |
| Random RIS      | Slight boost     | Neutral or slight boost |
| Optimized for U1| **Significant boost**  | Slight degradation  |

---

###  Key Takeaways

- RIS phase control provides **major gains** for the intended user
- Random phase settings offer mild/unpredictable improvements
- Optimizing RIS for one user can **negatively impact others**
- Highlights need for **multi-user phase optimization** in practical systems

---

###  Future Directions

- Optimize RIS jointly for U1 and U2
- Introduce user mobility
- Add D2D links and study resource sharing
- Compare passive vs hybrid RIS performance

---

**Author**: Sharmila Rapeti  
**Intern | RIS-D2D for 6G+ Project | SERB Funded**

