**Overview**

+ Extract DNA from Helicoverpa tissue for pooling using known, working protocol.

+ Concentrate DNA samples together.

+ Run BsaXI digest tests changing concentration of enzyme. 

*DNA extractions* 

1. Autoclave micropestle tubes, potassium acetate and lysis buffer.

2. Slice tissue into sections and place in cold 250uL Lysis buffer.

3. Mash with micropestle until homogenized.

4. Incubate for 30 minutes at 70C.

5. Add 35uL Potassium Acetate (pH 9), inversion mix and incubate on ice for 30 minutes. 

4. Spin for 5 minutes at 13,000 RPM, RT.

**Mix of mix1-8 reactions from /180730_DNA_Extraction_Pooling/README.md added into this step**

5. Take the acqueous layer and mix with 300μL Phenol:Chloroform in a new, numbered tube. Vortex for 3 seconds then spin for 5 minutes at 13,000 RPM, RT.

6. Remove the acqueous layer and place into another new, numbered tube. Repeat step 5, placing the acqueous layer into another tube.

7. Mix this supernatant with 150μL Isopropanol, and spin for 5 minutes at 13,000RPM. Theoretically a DNA pellet should be visible. 

8. Wash this pellet with 70% ethanol, and spin down for 5 minutes at 13,000RPM. Repeat this step to ensure clean DNA is collected. 

9. Air dry on the bench for 5-10 minutes until pellet is visibly dry. Resuspend in 30μL nuclease-free H2O. 

10. Incubate at 55 degrees, with 2uL RNase for 15 minutes. Store on ice and read results. 

*results*

|ID|ng/μL|260/280|260/230|
|:-----:|:-----:|:-----:|:-----:|
|mix9|2283.1|1.96|2.07|
|mix10|1542.5|2.04|2.21|
|mix11|1024.6|2.06|2.20|
|mix12|2050.4|1.87|1.95|
|mix13|436.0|1.97|1.9|
|mix14|1710.8|2.01|2.21|
|mix15|1598.0|2.04|2.20|
|mix16|1010.3|2.05|2.31|
|mix1-8.1|236.1|1.76|1.21|
|mix1-8.2|253.1|1.73|1.08|

Cleanup of mix1-8 samples worked well. Once gel is complete samples will be mix and vacuum concentrated. 

gel: [](/placeholder.jpg)

## Concentration of mixes 2/08/18 ##

1. Pool DNA samples together into two separate tubes (Mix1-8, & Mix9-16).

2. Place in rotorgene for 45 minutes, 55 degree heat. 

3. Take mix 1-8 tube out, spin another 45 minutes for mix9-16.

4. Elute in 30uL water each, measure with Qubit BR kit.

Results:

|ID|ng/μL|Total_ng|
|:-----:|:-----:|:-----:|
|mix1-8|54.6|1638|
|mix9-16|173|5190|

## BsaXI assay tests 2/08/18 ##

1.One unit BsaXI defines as the amount required to digest 1ug in 1 hour. Tube says 2U/uL. I reduced reaction to 500ng to have enough DNA to use for later reactions.

2. Set up master mixes - 10 reactions.

Heli MM

|Item|uL_per_rxn|uL_total|
|:-----:|:-----:|:-----:|
|Cutsmart buffer|5|25|
|DNA|2.89|14.45|
|Water|up_to_50ul|210.55|

Lambda MM

|Item|uL_per_rxn|uL_total|
|:-----:|:-----:|:-----:|
|Cutsmart buffer|5|25|
|DNA|0.87|4.37|
|Water|up_to_50ul|220.63|

3. Place MM reactions into each tube with the following volumes, and add the appropriate amount of enzyme on ice:

|Sample|MM_Volume|Enyzme_volume|
|:-----:|:-----:|:-----:|
|LN|50|0|
|L0.5|49.5|0.5|
|L1|49|1|
|L2|48|2|
|L5|45|5|
|HN|50|0|
|H0.5|49.5|0.5|
|H1|49|1|
|H2|48|2|
|H5|45|5|

4. Incubate 1hr, 37 degrees. After one hour take 25uL aliquot and leave rest in for 3 more hours, 37 degrees.

## Results ##

1 hour gel

[](/bsa_heli_vs_lambda.jpg)

Lanes 3-7 = Lambda 0.5, 1, 2, 5, Negative Control

Lanes 12-16 = Heli 0.5, 1, 2, 5, Negative control

Band becomes visibly smaller as more enzyme introduced, 5uL destroys HMW band in both samples.