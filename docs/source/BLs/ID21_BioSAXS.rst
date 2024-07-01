``ID21`` BioPharma-BioSAXS (BioSAXS)
=================================

1. Introduction
---------------

The BioPharma-BioSAXS beamline performs overall structural
characterization and structural transition studies of biological
molecules in solution based on small angle X-ray scattering (SAXS)
technique.[1, 2] SAXS measurement of samples in solution can obtain
information with a resolution as low as 1-2 nm. It can be applied to a
unique physiological solution environment where the physiological
phenomena of biological molecules can be activated. It is possible to
analyze the structural characteristics of crystalline/non-crystalline
biological molecules under physiological conditions and conduct
structural stability and structural transition studies under various
experimental environmental conditions (temperature, pressure, pH,
UV/Visible, ionic strength, ligand, electric field, magnetic field,
etc.). Due to these advantages, the usability of the solution SAXS
technique has greatly increased along with high-resolution structural
analysis methods of biological molecules such as X-ray crystallography,
nuclear magnetic resonance spectroscopy, and cryo-electron
microscopy.[3] As a result, solution SAXS technique is being used as a
standard analysis technique for structural characterization from
biological molecules to nanostructure systems such as organic/inorganic
nanoparticles, polymers, liquid crystals, colloids, and metals. Over the
past 10 years, a dedicated BioSAXS beamline has been built at a
world-class synchrotron radiation facility, contributing widely to the
development of basic and applied science fields such as nanoresearch,
structural biology, medicine, and new drug development. Recently, the
biopharmaceutical field has begun to include the BioSAXS analysis
technique in the workflow for analyzing the characteristics of
biopharmaceutical for the purpose of identifying the structure,
function, and operating principle of bio/protein therapeutics and
providing evidence to prove the biological equivalence of biosimilars
compared to original biopharmaceuticals. The BioPharma-BioSAXS beamline
is classified and constructed as an industry priority support beamline
to respond to the demands of industries in the bio and pharmaceutical
fields and to promote manpower in related fields. The main strategy of
the beamline is to process a large number of samples at high speed
(high-throughput) in order to efficiently utilize high brilliance and
low divergence X-rays based on 4\ :sup:`th` generation synchrotron
radiation.[4]

2. Scientific Objects
--------------------

The BioPharma-BioSAXS beamline provides a solution SXAS technique,
contributing to the analysis of biopharmaceutical properties by studying
the three-dimensional structure and structural transition of
solution-phase biological molecules and their complexes. Examples of
applications using the solution SAXS technique are as follows: (1)
Quantitatively characterize the structure of multi-domain proteins
linked by flexible linkers and intrinsically disordered proteins.[5-8]
(2) Reveal the structural behavior and stability of proteins and protein
drugs through understanding the structure of the native and denatured
states of proteins.[9-11] (3) Recently, mRNA vaccines and treatments
have been in the spotlight, and lipid nanoparticles (LNPs) are being
used as an effective mRNA delivery system, and the structural stability
of mRNA-LNPs in solution is being studied.[12, 13] (4) Real-time
SEC-SAXS technique is used to study the change in solution phase
structure of monodisperse biopolymer materials through
separation/purification.[14] To facilitate such research, a collimated
beam with high beam flux must be irradiated onto the sample. Varying the
SDD is essential due to the diversity of samples to be measured and the
need for a wide q range. A variable q range vacuum chamber will be built
for fast and precise SDD change (0.5 - 6 m). By introducing an automatic
sample changer at a fixed sample environment location, large number of
samples can be processed at high speed to collect data at high
throughput.

3. Beamline Requirements for the Insertion Device
-------------------------------------------------

The BioPharma-BioSAXS beamline will require the highest brilliance in
the energy range of 5-20 keV without energy discontinuity. The source
will be in-vacuum undulator with period length of 24 mm and total length
of 3 m. A detailed description of the BioPharma-BioSAXS Insertion Device
can be found in the [].

Table 1. Source Parameter for BioPharma-BioSAXS beamline

+---------+-----------+----------+-----------------------+-----------+
| Un      | Period    | Length   | Location              | Max Power |
| dulator | [mm]      | [m]      |                       |           |
+=========+===========+==========+=======================+===========+
| IVU24   | 24        | 3.0      | Center of Straight    | 0.96 kW   |
|         |           |          | section               |           |
+---------+-----------+----------+-----------------------+-----------+

Maximum power refers to the maximum beam power passing through a mask
with an aperture of 2 x 2 mm² @ 23 m using the IVU24.

4. Beamline Requirements for Front End
--------------------------------------

The front end of BioPharma-BioSAXS beamline will require to handle a
maximum power of 17.9 kW. The output of the beam from IVU24 is
appropriately attenuated using three masks in the front end to prevent
damage to the optical devices in the PTL section and enable stable
operation of the beam line. The BioPharma-BioSAXS beamline will utilize
the standard KOREA-4GSR IVU24 front end design. Two fixed type masks and
one movable type mask will control a total of 17.5 kW of heat at the
front end. The beamsize drawn from the front end will be 1.3 x 1.3 mm²
at front end exit port. A detailed description of the BioPharma-BioSAXS
Front End can be found in the [].

5. Beamline Layouts
--------------------

The BioPharma-BioSAXS beamline is a SAXS-dedicated beamline at the
KOREA-4GSR construction. The beamline layout is shown in Figure 1, where
the beamline will consist of a front end, an optical hutch, a photon
transfer line, and an experimental hutch.

|image1|

Figure 1. Layout of BioPharma-BioSAXS beamline

Table 2 shows major beamline components, their location along the
beamline, and description.

Table 2. List of BioPharma-BioSAXS beamline component

+------------+---------------+------------------+---------------------+
| Distance   | Component     | Description      | Comments            |
| from       |               |                  |                     |
| source (m) |               |                  |                     |
+============+===============+==================+=====================+
| 27.7       | Attenuator    | Water cooled,    | Removing low energy |
|            |               | CVD diamond,     | X-ray beam          |
|            |               | B\ :sub:`4`\ C,  |                     |
|            |               | Si               |                     |
+------------+---------------+------------------+---------------------+
| 28.3       | Slit          | Water cooled,    | Eliminating heat    |
|            |               | 4-way slit, UHV  | load                |
|            |               |                  |                     |
|            |               |                  | Mirror incident     |
|            |               |                  | X-ray conditioning  |
+------------+---------------+------------------+---------------------+
| 28.8       | Diagnostic    | W-blade BPM      | Beam position &     |
|            |               |                  | profile defining    |
+------------+---------------+------------------+---------------------+
| 30.0       | HHLM          | Flat mirror      | Eliminating heat    |
|            |               |                  | load from X-ray     |
|            | (High heat    | 2-stripe coating |                     |
|            | load mirror)  | (Pt, Rh)         |                     |
+------------+---------------+------------------+---------------------+
| 32.2       | Slit          | 4-way slit, UHV  | Beam conditioning   |
+------------+---------------+------------------+---------------------+
| 33.1       | Diagnostic    | W-blade BPM      | Beam position &     |
|            |               |                  | profile defining    |
+------------+---------------+------------------+---------------------+
| 34.0       | DCM           | Si (111), fixed  | Monochromatizating  |
|            |               | exit,            | X-ray beam          |
|            | (Double       | NL\ :sub:`2`     |                     |
|            | crystal       | cooled           |                     |
|            | m             |                  |                     |
|            | onochromator) |                  |                     |
+------------+---------------+------------------+---------------------+
| 35.9       | Slit          | 4-way slit, UHV  | Beam conditioning   |
+------------+---------------+------------------+---------------------+
| 36.3       | Diagnostic    | YAG + CCD        | Beam position &     |
|            |               |                  | profile defining    |
+------------+---------------+------------------+---------------------+
| 37.4       | VFM           | Ellipsoid        | Focusing the beam   |
|            |               |                  | in vertical         |
|            | (Vertical     | Rh, PT coating   | direction           |
|            | Focusing      |                  |                     |
|            | Mirror)       |                  |                     |
+------------+---------------+------------------+---------------------+
| 39.1       | HFM           | Ellipsoid        | Focusing the beam   |
|            |               |                  | in horizontal       |
|            | (Horizontal   | Rh, PT coating   | direction           |
|            | Focusing      |                  |                     |
|            | Mirror)       |                  |                     |
+------------+---------------+------------------+---------------------+
| 50.0       | Slit          | 4-way slit, HV   | Monochromatic beam  |
|            |               |                  | conditioning        |
+------------+---------------+------------------+---------------------+
| 50.9       | Diagnostic    | YAG + CCD        | Beam position &     |
|            |               |                  | profile defining    |
+------------+---------------+------------------+---------------------+
| 57.0       | Diagnostic    | OFHC + YAG       | Beam position &     |
|            |               |                  | profile defining    |
+------------+---------------+------------------+---------------------+
| 61.8       | Slit          | 4-way slit, HV   | Monochromatic beam  |
|            |               |                  | collimation         |
+------------+---------------+------------------+---------------------+
| 62.5       | Diagnostic    | YAG + CCD        | Beam position &     |
|            |               |                  | profile defining    |
+------------+---------------+------------------+---------------------+
| 67.1       | Shutter       | W                | Blocking the beam   |
+------------+---------------+------------------+---------------------+
| 68.0       | Slit          | 4-way slit, HV   | Parasitic beam      |
|            |               |                  | rejection           |
+------------+---------------+------------------+---------------------+
| 69.0       | Sample        | ARINAX robot     | Automatic sample    |
|            | environment   |                  | exchanging system   |
+------------+---------------+------------------+---------------------+
| 69.3~75.8  | Variable      | 7 m long         | Detector position   |
|            | *q*-range     |                  | in vacuum tube      |
|            | vacuum        |                  |                     |
|            | chamber       |                  | SDD adjustment      |
+------------+---------------+------------------+---------------------+
| 69.5~75    | 2D detector   | Eiger2 X 4M      | Scattering pattern  |
|            |               |                  | detection           |
+------------+---------------+------------------+---------------------+

Reference
----------

[1] FEBS Letters, 589, 2570-2577 (2015)

[2] Chemical Reviews 116, 11128-11180 (2016)

[3] Nature Methods 6, 606 (2009)

[4] Current Opinion in Structural Biology 58, 197-213 (2019)

[5] Structure 22, 1862–1874 (2014)

[6] Scientific Reports 11, 5655 (2021)

[7] Journal of American Chemical Society 142, 15697−15710 (2020)

[8] Journal of American Chemical Society 143, 20109−20121 (2021)

[9] Physical Chemistry Chemical Physics 19, 17143—17155 (2017)

[10] Polymers 11, 2104 (2019)

[11] Molecular Pharmaceutics 17, 2809–2820 (2020)

[12] PNAS 115, E3351-E3360 (2018)

[13] ACS Nano 15, 6709−6722 (2021)

[14] Bioinformatics 34, 1944-1946 (2017)

.. |image1| image::ID21_BioSAXS/media/image1.png
   :width: 6.26806in
   :height: 2.53819in
