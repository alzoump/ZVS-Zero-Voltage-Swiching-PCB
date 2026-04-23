# ZVS-Zero-Voltage-Swiching-PCB
Zero Voltage Switching (ZVS) is a technique where a switch turns on when the voltage across it is zero. This reduces power loss, heat, and electrical noise, improving efficiency and extending component life, especially in high-frequency power converters.


The circuit consists of:

2 × IRF260n MOSFETs
2 × 100 Ω, 5 W resistors
2 × 4.7 kΩ resistors
2 × 12 V Zener diodes
2 × 1N5818 Schottky diodes
2 × UF600J diodes
4 × 1 nF polyester capacitors
1 × 10 µH inductor (or a short across)

this will output in perfect confitions 3Mhz


you can also : 

10nF   500khz    ~10μh
22nf   300 khz   ~13μh
47nf   200khz    ~ 13μh

in our case (250pf total) :

500 kHz   ~405 μh
1 MHz     ~101 μh
2 MHz     ~25 μh
3 MHz     ~11 μh 
5 MHz     ~4 μh


