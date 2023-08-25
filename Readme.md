# How to generate Spectral files (FTIR / Raman) using Gaussian16

## Input file (general structure coming soon)

<pre>
```bash
%nprocshared=4
%mem=4GB
%chk=C:\Users\jared\Desktop\spectras\4-ONE_5-IMINE-PYRENE\ethanol_solvent\ETHANOL-4-ONE_5-IMINE-PYRENE.chk
# freq=raman b3lyp/6-311++g(d,p) scrf=(cpcm,solvent=ethanol)
geom=connectivity

Title Card Required

0 1 
 C                 -3.53067833   -0.50651839    0.00001203
 C                 -2.80438817   -1.68367941    0.00001003
 C                 -1.39320107   -1.67404227   -0.00000298
 C                 -0.70925313   -0.42801112   -0.00001598
 C                 -1.47254130    0.76875990   -0.00002498
```
</pre>

The structure that I generated in gaussview (tutorial coming soon):
![SVG Image](4-ONE_5-IMINE-PYRENE.svg)

## Raman and IR Spectra of molecule
![IR Spectra](4-ONE_5-IMINE-PYRENE_EtOH_IR.svg)
![RAMAN Spectra](4-ONE_5-IMINE-PYRENE_EtOH_RAMAN.svg)

[Click here to see the vibrations corresponding to the frequency -- in the form of a youtube video](https://youtu.be/OEnIv5xCmJs )

### Section 1

Some content in the first section.

### Section 2

More content in the second section.

#### Subsection 2.1

Content for subsection 2.1.

#### Subsection 2.2

Content for subsection 2.2.
