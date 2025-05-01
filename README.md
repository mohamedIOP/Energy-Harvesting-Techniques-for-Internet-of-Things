# 📡 Energy Harvesting Technologies for IoT Edge Devices

## 📖 Abstract

Traditional IoT devices rely on limited power sources, making them unsuitable for long-term deployment. This section introduces energy harvesting (EH) as a sustainable method to power IoT systems by converting ambient energy—such as solar, thermal, and vibrational—into electrical energy. The aim is to reduce dependency on conventional batteries and achieve autonomous operation using duty cycling strategies.

[1] [Fatih Ünlü, Lukas Wawrla, Adriana Díaz (2018). *Energy Harvesting Technologies for IoT Edge Devices*.](https://www.iea-4e.org/wp-content/uploads/publications/2018/07/Energy_Harvesting_Final_Report.pdf)

[2] [Teodora Sanislav, George Dan Mois, Sherali Zeadally, Silviu Corneliu Folea (2021). *Energy Harvesting Technologies for IoT Edge Devices*.](https://ieeexplore.ieee.org/document/9370135)

---

## ❗ Problem Definition

While EH offers advantages, it suffers from challenges like low efficiency, poor scalability, and integration difficulties. This section outlines the environmental and safety concerns of batteries and emphasizes the need for better energy management systems in IoT.

[3] [Fitbit Fined Over Ionic Smartwatch Burns](https://www.theverge.com/2025/1/23/24350413/fitbit-fine-ionic-smartwatch-burns)

[4] [Battery Incidents Affecting Businesses - Aviva](https://gcs.aviva.com/en-gb/news/Lithium-ion-battery-incidents-affect-more-than-half-of-businesses/)

[5] [E-Scooter and Vape Injuries Overwhelm Herston Burns Unit](https://wilstongrangenews.com.au/herston-burns-unit-overwhelmed-by-e-scooter-and-vape-injuries/)

---

## 📚 Literature Review

Energy harvesting (EH) has emerged as a sustainable power alternative for IoT devices, aiming to replace or complement traditional batteries. Studies show that ambient energy sources such as solar, RF, thermal, vibrational, and triboelectric can be used to generate sufficient power for low-energy applications. However, literature highlights challenges like low conversion efficiency, intermittent energy availability, and integration issues. RF-based energy harvesting, in particular, has been explored using circuits like the Powercast P2110B, which converts RF signals into usable DC power. Several works propose optimizing antenna matching, rectification stages, and energy management circuits to improve harvesting efficiency. Recent advances also explore hybrid systems and wearable sensors powered solely by ambient sources, enabling real-time, battery-free monitoring solutions.

### Online Sources:
[6] Optimizing IoT Energy Efficiency with Deep Learning: A Case for Solar-Powered Systems [2025] Authors: Steve Smith, Nisar Ahmad.

[7] [RF Energy Harvester Applications – ResearchGate (2023)](https://www.researchgate.net/publication/378082885_RF%20Energy_Harvester_and_Its_Applications_in_IoT_A_Review)

[8] [Investigation of Energy Harvesting Techniques – IJMICSE](https://international.aritekin.or.id/index.php/IJMICSE/article/view/71)

[9] [Smart Grid Management and IoT Integration](https://internationalpubls.com/index.php/pmj/article/view/1866)

[10] [IoT-Based Hybrid Renewable Energy System](https://www.researchgate.net/publication/353611601_IoT%20Based_Hybrid_Renewable_Energy_System_for_Smart_Campus)

---

## 📐 Mathematical Modeling and Methodology

Here, the RF energy harvesting system is modeled using a series of electrical and differential equations:

- Antenna System: Modeled with a first-order ODE to describe its electromagnetic response.

- Matching Network: A second-order ODE model to maximize power transfer.

- Rectifier: Modeled to convert RF AC to DC using a multi-stage approach.

- Load Consumption: Captures the transient behavior and power delivery using capacitors.

[11] A. Kaur, H. Nagaraja, "RF-energy harvester and its applications in IoT", ICI 2023. DOI: [10.1109/ICI60088.2023.10421418](https://doi.org/10.1109/ICI60088.2023.10421418)

[12] L.-G. Tran, H.-K. Cha, W.-T. Park, "RF power harvesting", Micro and Nano Systems Letters, 2017. DOI: [10.1186/s40486-017-0051-0](https://doi.org/10.1186/s40486-017-0051-0)

[13] [Antenna as RLC Circuit – EE Diary](https://www.ee-diary.com/2023/06/how-antenna-as-rlc-circuit-works.html)

[14] J. Singh, "RF Energy Harvesting Circuit Analysis", 2015. DOI: [10.13140/RG.2.1.4838.4488](https://doi.org/10.13140/RG.2.1.4838.4488)

[15] H. Rahmani, "Wireless Power for Biomedical Implants", 2017. DOI: [10.13140/RG.2.2.32007.04000](https://doi.org/10.13140/RG.2.2.32007.04000)

[16] [Hayt, Kemmerly, Durbin, *Engineering Circuit Analysis*, 9th ed., McGraw-Hill, 2019.](https://elcom-team.com/Subjects/%D8%AF%D9%88%D8%A7%D8%A6%D8%B1%20%D9%83%D9%87%D8%B1%D8%A7%D8%A6%D9%8A%D8%A9%201/%D8%A7%D9%84%D9%83%D8%AA%D8%AA%D8%A8%20%D9%88%D8%A7%D9%84%D8%AD%D9%84%D9%88%D9%84/cct1-book(9ed).pdf)

---

## 🧪 Simulation and Results

The project utilizes a Powercast P2110B chip for RF energy harvesting. LabVIEW and USRP were used to transmit modulated RF signals, and energy harvesting performance was measured. Among the tested modulations, BPSK provided the best efficiency. The section also discusses the use of triboelectric generators for self-powered sensors.

[17] C. R. Reddy, K. S. Reddy, S. R. Reddy, "Low Power RF Energy Harvesting System", ICRAECC 2019, India. DOI: [10.1109/ICRAECC43874.2019.8995099](https://doi.org/10.1109/ICRAECC43874.2019.8995099)

[18] [RF-Energy Harvester and Its Applications in IoT: A Review.](https://www.researchgate.net/publication/378082885_RF-Energy_Harvester_and_Its_Applications_in_IoT_A_Review)

[19] [Flexible and wearable healthcare sensors for visual reality health-monitoring.](https://www.sciencedirect.com/science/article/pii/S2096579619300543?via%3Dihub)

[20] [A MXene-Based Wearable Biosensor System for High-Performance In Vitro Perspiration Analysis.](https://onlinelibrary.wiley.com/doi/10.1002/smll.201901190)

[21] [Harnessing Energy for Wearables: A Review of Radio Frequency Energy Harvesting Technologies.](https://www.mdpi.com/1996-1073/16/15/5711)

[22] [Wireless battery-free wearable sweat sensor powered by human motion.](https://www.science.org/doi/10.1126/sciadv.aay9842)

[23] [Piezoelectric energy harvesting for self-powered wearable upper limb applications.](https://onlinelibrary.wiley.com/doi/10.1002/nano.202000242)

[24] [Body-Integrated Self-Powered System for Wearable and Implantable Applications.](https://pubs.acs.org/doi/10.1021/acsnano.9b02233)

---
# 📊 Poster

[![Poster Preview](poster/preview.png)](poster/poster.pdf)

📄 [Download PDF](poster.pdf)

---

<h2>
  <span style="display: inline-block; width: 150px; text-align: right;">
    <img src="Logo.png" alt="Logo" width="150">
  </span>
</h2>

## 🛠️ Contributers

- Omar Sherif El-Sayed Abdelkhaleq
  
- Hesham Abd El-Rahman Mahmoud
  
- Mohamed Hossam El-Sawy Omran
  
- Mina Wael Tanagho Fahmy Sedrak
  
- Hesham Elsayed Ahmed Eltaiary
  
- Youssef Ibrahim Shaban Abdelsalam
  
- Youssef Mohamed Ibrahim Sayed
  
- Youssef Talaat Farouk Ahmed
