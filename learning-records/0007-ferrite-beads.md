# 铁氧体磁珠 — 精密信号链的电源噪声滤波

Completed Lesson 0008 on ferrite beads. Covered: material science basis (NiZn vs MnZn ferrite), impedance-frequency characteristic (R(ω) resistive loss mechanism vs X_L inductive reactance, cross frequency f1, resonance frequency f2), critical distinction between ferrite bead and inductor (loss vs storage, absorption vs reflection), key datasheet parameters (Z@100MHz, DCR, rated current, f_res), π-type filter design (bead + capacitor pair) for TIA power rail and ADC V_REF decoupling, digital-analog power isolation strategy, saturation risk and derating rule (≤70% rated current), temperature drift, and four common design mistakes with their corrections. Includes selection guide table for TIA/ADC/MCU/VOA power scenarios.

**Status**: active
**Evidence**: Completed Lesson 0008 with three quiz questions on impedance-frequency curve interpretation, ferrite bead selection for TIA application, and bead-vs-inductor scenario judgment.

**Implications**: The user now understands ferrite bead as a core component for power integrity in precision analog circuits. Combined with Lessons 0004 (PCB layout) and 0005 (ADC), this completes the power supply design knowledge for the photodetection signal chain. Ready for deeper topics: detailed π-filter design optimization, bead selection using vendor simulation tools, or system-level power integrity analysis.
