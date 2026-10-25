# [Modulation Technology] Break the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]

Personal Blog: https://www.cnblogs.com/EWFrontier  
More importantly, the core technologies supporting current wireless communication—QAM (Quadrature Amplitude Modulation) and PSK (Phase Shift Keying), are products of the 1960s to 1970s. They have been able to survive today not because they are "optimal" but because at that time, due to limited computational capabilities, designers prioritized "easily analyzeable" over "performance optimal."  
As 5G evolves towards 6G, with increasingly stringent requirements for energy consumption, speed, and environmental protection, can these "old-fashioned" designs still hold up? The research team at KTH Royal Institute of Technology has provided an answer: asymmetric constellation design is rewriting the rules of wireless communication.  
A "ultimate competition" across 14 designs in search of superior modulation schemes, the research team conducted large-scale comparison experiments—testing 14 hexadecimal constellation designs all at once, covering four major categories:  
✧  
Traditional benchmarks: familiar 16-QAM (square grid) and 16-PSK (circular arrangement);  
✧  
Asymmetric geometries: six innovative shapes including hexagonal, star-shaped, elliptical, and non-circular;  
✧  
Intelligent optimization: two optimized designs based on particle swarm optimization (PSO) and genetic algorithm (GA);  
✧  
Formation technology: four cutting-edge solutions including bio-inspired "golden angle modulation."  
The entire experiment was like a "marathon" in the communications world: under both AWGN (ideal channel) and Rayleigh (actual multipath fading channel) scenarios, it tested transmission of 780 million symbols (1 million symbols per SNR point, covering a range from -5 to 50dB, across 56 intervals). Using the most rigorous Monte Carlo simulations to ensure statistical reliability of results.  
Simply put, this is the most comprehensive and rigorous "test" of constellation design to date.  
Key Findings: Performance and Energy Consumption "Win-Win Formula" After massive simulations and data analysis, several groundbreaking conclusions emerged:
1. The lattice-based design has reached the pinnacle, but QAM still "stands its ground" among all designs. In terms of technical performance, the lattice-based constellation shows the best results with an overall score of 0.898 (maximum score of 1). Its minimum Euclidean distance (the distance between signal points, the larger the better for reducing error) reaches 0.667, which is 5.5% higher than that of 16-QAM at 0.632. Under a 10dB signal-to-noise ratio, the symbol error rate (SER) is only 0.217, the lowest among all schemes.
However, surprisingly, the 16-QAM, which has been used for half a century, still ranks second with an overall score of 0.877. This indicates that after decades of standardization and optimization, the balance between "distance-energy consumption" in QAM indeed approaches optimality, making it difficult to be replaced easily.
2. Asymmetrical design breaks the "energy consumption curse" One major challenge of traditional QAM is the high peak-to-average power ratio (PAPR) (2.55dB), leading to low amplifier efficiency and severe energy consumption. However, experiments have shown that geometrically asymmetrical design can reduce PAPR by 1-2dB—with the elliptical design being particularly outstanding, achieving a PAPR of only 1.62dB, reducing by 36% compared to QAM.
3. Environmental value far exceeds expectations The carbon footprint of the communication industry cannot be underestimated, and the optimization of constellation design can directly lead to significant environmental benefits. Based on the 1.6dB reduction in PAPR calculated for the elliptical design:
✧
Globally, about 50 million 5G base stations could save 7.9 terawatt-hours of electricity annually;
✧
Annual reduction of 3.9 million tons of carbon dioxide emissions, equivalent to the halting of 850,000 vehicles;
✧
Under the "dual carbon" goals, this path of "technological optimization = environmental emission reduction" undoubtedly holds great practical significance.
4. Bioinspired "golden angle modulation": Potential dark horse in 6G This experiment features the most imaginative design as "Golden Angle Modulation (GAM)". It draws inspiration from the arrangement principle of sunflower seeds—using a 137.5° golden angle to distribute signal points in a spiral pattern, ensuring uniform spacing while also possessing strong scalability.
Two GAM schemes each have their highlights:
The Disk-shaped GAM: Distributed radially uniformly, with a PAPR of only 2.75dB, offering performance comparable to QAM and unaffected by rotation and scaling;
✧
The Clock-shaped GAM: Gaussian distributed, although with a higher PAPR, close to the Shannon limit without any asymptotic capacity loss.
More importantly, regardless of the modulation order from 16 to 1024, this helical structure maintains uniform distribution, avoiding signal point clustering or gaps, perfectly adapting to the high spectral efficiency demands of 6G.
Practical Guide: How to choose in different scenarios? There is no one-size-fits-all design; the research team provides clear selection recommendations, balancing performance, energy consumption, and practicality:
✧
Power-limited scenarios (IoT, satellite communications): Prioritize elliptical or non-symmetric designs, with a 1.6dB PAPR advantage significantly extending device battery life;
✧
Throughput-priority scenarios (5G core network, data centers): 16-QAM remains the optimal solution, stable and highly compatible;
✧
Frontier exploration scenarios (6G prototypes, special channels): Grid-based design or golden angle modulation can balance performance and scalability;
✧
Future of 6G: What can the constellation design evolve? This study is just a starting point; there are three promising directions for future constellation design:
1.
Combine with error correction codes: Optimize the constellation design in conjunction with modern error correction codes like LDPC/Polar, further reducing error rates;
2.
Hardware validation: Test actual amplifiers and channel performance through software defined radio (USRP) testing;
3.
Smart adaptation: Use machine learning to dynamically select the optimal constellation shape based on real-time channel conditions, combined with reconfigurable intelligent surfaces (RIS) for ultimate optimization.
From QAM in the 1960s to asymmetric and bio-inspired designs today, the "alphabet" of wireless communication is being rewritten. This transformation not only allows 5G to be more power-efficient but also contributes to global carbon reduction - technological progress always requires both speed and distance.
What do you think will be the modulation innovations in 6G? Feel free to leave a comment and discuss!

## Images

![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](01.jpg)
![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](02.jpg)
![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](03.jpg)
![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](04.jpg)
![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](05.jpg)
![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](06.jpg)
![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](07.jpg)
![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](08.jpg)
![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](09.jpg)
![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](10.jpg)
![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](11.jpg)
![(Modulation Technology)Breaking the 50-year monopoly! Asymmetrical constellation design makes 5G/6G more energy-efficient and faster, reducing carbon emissions by 3.9 million tons per year [with Python code attached]](12.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
