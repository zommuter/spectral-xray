---
title: Ermittlung Atomarer Zusammensetzung durch multispektrales Röntgen
author: Tobias Kienzler
date: 21.09.2018
...

# Motivation
- Unterstützung der Röntgendiagnostik:  
Atomare Zusammensetzung
- Gängige Detektoren: Komplettes Spektrum absorbiert  
(Ausnahme: DXA)
- Untersuchung möglicher Adaption existierender Aufbauten

# Grundlagen: Absorption I
- Absorption elektromagnetischer Strahlung **exponentiell** in Dicke $d$, Lambert-Beersches Gesetz:  
$$I = I_0\cdot\exp{\left(-\mu\cdot d\right)}$$
- Zusammengesetztes Material: Integration (vgl. Hounsfield-Skala im CT)  
$$I = I_0\cdot\exp{\left(\int \mu(x)\, dx\right)}$$
- Massenschwächungskoeffizient $\mu/\rho$ abhängig von Photonenenergie

# Grundlagen: Absorption II
- Tabelliert, z.B. <https://www.nist.gov/pml/x-ray-mass-attenuation-coefficients>  
![](murho_tissue.png){ height=50% }

# Grundlagen: Röhrenspektrum & Detektor
- Emittiertes Spektrum kontinuierlich, abhängig von Anodenmaterial, Filter und Beschleunigungsspannung  
[![](xray-alter3.png){ height=40% }](https://www.radiologycafe.com/radiology-trainees/frcr-physics-notes/production-of-x-rays)
- Detektor registriert alle Photonen, kein monochromatisches Abfahren einzelner Wellenlängen möglich

# Dual-Röntgen-Absorptiometrie (DXA)
- Subtraktion zweier Aufnahmen bei unterschiedlicher Energie  
[![](index_clip_image002_0010.jpg){ height=50%}  
\tiny [http://www.upstate.edu/radiology/education/rsna/radiography/dual.php]](http://www.upstate.edu/radiology/education/rsna/radiography/dual.php)
- Anwendung z.B. Knochendichtemessung

# Triple-Röntgen-Absorptiometrie
- Analog mit dritter Energie  
![](triple.png){ height=75%}

# Multispektrale Röntgen-Absorptiometrie
- Mehrere Radiographien bei unterschiedlichen Energien
- Numerischer Fit mit den wahrscheinlichsten Atomen oder Substanzen (z.B. Knochen, Wasser, Nierensteine)
- Pixelweise Analyse der geschichteten Zusammensetzung
- Keine 3D-Information!

# Abschätzung Patientendosis
- Für optimale Ergebnisse Ausnutzung des vollen Generatorspektrums
- z.B. 40-125 kV
- Dosis bei niedriger Spannung relativ hoch
- Alternative zu Energievariation: verschiedene Filter
- Abschätzung: ca. 100 Aufnahmen für 100 verschiedene Atomzahlen
- CXR je 0.1 mSv $\Rightarrow$ 10 mSv, ähnlich CT
- Reduktion der Dosis durch Reduktion auf wahrscheinlichste Substanzen

# Ausblick
- Kombination CT oder Parallaxenverschiebung