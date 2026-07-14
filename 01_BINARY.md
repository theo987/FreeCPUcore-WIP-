# Physikalische Grundlagen & Halbleitertechnologie

Hier sind die digitalisierten Aufschriebe zu den physikalischen und technologischen Grundlagen des Prozessor-Core-Designs.

---

## 1. Elektronische Kennwerte von Halbleitern

Die Leitfähigkeit eines Halbleitermaterials hängt stark von der Ladungsträgerkonzentration ab. Die intrinsische Ladungsträgerkonzentration $n_i$ in Abhängigkeit von der Temperatur $T$ und der Bandlücke $E_g$ berechnet sich wie folgt:

$$
n_i(T) = \sqrt{N_C \cdot N_V} \cdot \exp\left(-\frac{E_g}{2 \cdot k_B \cdot T}\right)
$$

Hierbei sind:
* $N_C, N_V$ — Effektive Zustandsdichten im Leitungs- und Valenzband
* $E_g$ — Bandabstandsenergie (Band Gap) in Elektronenvolt ($\text{eV}$)
* $k_B$ — Boltzmann-Konstante ($1{,}38 \times 10^{-23} \, \text{J/K}$)
* $T$ — Absolute Temperatur in Kelvin ($\text{K}$)

---

## 2. Dotierung und Ladungsträgerdichte

Durch gezieltes Einbringen von Fremdatomen (Donatoren $N_D$ für n-Leitung, Akzeptoren $N_A$ für p-Leitung) wird das Massenwirkungsgesetz im thermodynamischen Gleichgewicht bestimmt:

$$
n_0 \cdot p_0 = n_i^2
$$

Für ein rein n-dotiertes Halbleitermaterial ($N_D \gg n_i$) gilt näherungsweise für die Elektronenkonzentration $n_0$ und die Löcherkonzentration $p_0$:

* **Elektronen:** $n_0 \approx N_D$
* **Löcher:** $p_0 \approx \frac{n_i^2}{N_D}$

---

## 3. Skalierung und Gatter-Laufzeiten (Mikroelektronik)

Für die digitale Schaltungstechnik in CMOS-Strukturen ist die Verzögerungszeit $\tau$ (Propagation Delay) eines Logikgatters entscheidend. Diese wird maßgeblich durch die Lastkapazität $C_L$ und den Sättigungsstrom $I_{DS,sat}$ der Transistoren bestimmt:

$$
\tau \approx \frac{C_L \cdot V_{DD}}{I_{DS,sat}}
$$

Wobei der Strom im Sättigungsbereich wie folgt definiert ist:

$$
I_{DS,sat} = \frac{W}{2 \cdot L} \cdot \mu \cdot C_{ox} \cdot (V_{GS} - V_{th})^2
$$

* $W / L$ — Weiten- zu Längenverhältnis des Transistorkanals
* $\mu$ — Ladungsträgermobilität
* $C_{ox}$ — Oxidkapazität pro Flächeneinheit
* $V_{th}$ — Schwellenspannung (Threshold Voltage)

---

## Originalaufschrieb (Referenz)
Falls du das Originalblatt im Repository einsehen möchtest:
![Original Notizen](./images/IMG_2789.jpeg)
