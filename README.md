# Two Stage Op Amp

#### Aim : 

To design a two stage opamp on Cadence Virtuoso at 90nm technology node for the following specifications- 
- DC gain = 50dB
- GBW = 30MHz
- PM >= 60 deg
- Slew Rate >= 20V/$\mu$S
- $ICMR^+$ = 1.6V
- $ICMR^-$ = 0.8V
- $C_L$ = 2pF
- $V_{dd}$ = 1.8V
- Process = 90nm

#### Schematic :
![op+amp_img](/images/schematic.png)

#### Design Specifications :
- L = 300nm
- $C_C$ = 800fF
- $I_5$ = 20$\mu$A
- $S_1$ and $S_2$ = 5 (where S = W/L)
- $S_3$ and $S_4$ = 3
- $S_5$ = 2
- $S_6$ = 48
- $S_7$ = 16

#### Test Schematic :
![test_img](/images/test.png)
This circuit was used to calculate model paramters for nmos and pmos ($\mu_n$, $\mu_p$, $t_{ox,n}$, $t_{ox,p}$) and device parameters ($V_{t1, min}$, $V_{t1, max}$, $V_{t3, max}$)
