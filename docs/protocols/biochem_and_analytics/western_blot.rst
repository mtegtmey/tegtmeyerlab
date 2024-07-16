============
Western Blot
============

Lysis
=====

Materials:
----------
* 10X Cell Lysis Buffer from CST
* 200mM PMSF (200X concentrated)
* Cell Scraper
* Blunt 21 gauge needles
* Lock-joint syringe
* Cells to lyse

.. note::
   * If 10X cell lysis buffer will be continually used, it is recommended that the 10x buffer be kept at 4°C for 1-2 weeks.
     For longer periods of time, buffer should be stored at -20°C. Aliquoting of 10x buffer is recommended if many small experiments are to be performed.
   * PMSF is unstable in water and should be added to lysis buffers or other aqueous solutions just prior to use.
     Typically, a final concentration of 1 mM provides sufficient protease protection. Store lyophilized at RT for 24 months protected from direct light.
     Once in solution, PMSF can be stored at -20ºC for up to 3 months, protected from light.

Protocol:
---------

.. important:: All reagents and lysates must be kept cold. In addition, **keep plates on ice** during lysis step.

.. note:: We usually use the 10X cell lysis buffer

1. Cool microcentrifuge to 4°C.
2. Dilute 10X Cell Lysis Buffer to a 1X solution using Elga water.

   - Can use either 10X lysis buffer or RIPA in -20°C "Western Reagents" box.

3. Chill 1X buffer on ice and add PMSF just prior to use.
4. Wash plate with ice-cold PBS to remove residual media.
5. Add 400 uL of 1X lysis buffer to the 10cm dish of cells.

    ===================================   ==========================   ==================================
    **Solution**                          **Vol for 1x10cm**           **Vol for 3x10cm**
    ===================================   ==========================   ==================================
    ELGA water                             358 µL                         1,170 µL
    10X cell lysis buffer                   40 µL                           130 µL
    200 mM PMSF                              2 µL                             6.5 µL
    ===================================   ==========================   ==================================

.. note:: 
   BAL has also used 6-well plates to make cell lysate instead of 10cm dishes. Volume of 1x lysis buffer is scaled by surface area, so 68uL of lysis buffer is required per 6-well.

6. Tilt to coat bottom of dish, then incubate on ice for 5 minutes.
7. Scrape cells with a cell scraper and transfer lysed solution to a small centrifuge tube.
8. Use 21 gauge needles to shear the cells 5-6 times (change out needle so 1 needle/sample).
9. Spin extract 10-12 minutes at 14,000 x g (~11,500 rpm) in the 4°C microcentrifuge.
10. Remove supernatant for use and aliquot.

   - You should have ~500-600 µL per 10cm dish (or about 70-80 uL per 6-well).
   - ~50-60 µL/aliquot is good because you can load 25 µL/well (12.5 µL lysate + 12.5 µL 2X Laemmli)
      so 50 µL will give enough for 4 wells (i.e. 4 antibodies).
   - BAL uses 20-25 uL/aliquot for lysates from a 6-well since 12.5 uL/well (6.25 uL lysate + 6.25 uL 2X Laemmli) has be sufficient for detecting proteins.

.. note::
   * Use prepared lysates as quickly as possible, and store for as short a time as possible.
   * Store lysates at -80°C for as long as possible. For lysates that will need to be kept around long term,
     transfer freshly prepared tubes to an available -80°C freezer to prevent degradation.
   * Lysates have a shorter shelf life when stored at -20℃; long-term storage at this temperature is not recommended.
     CST recommends that lysates are stored at -20℃ for no longer than 3 months.
   * Minimize your freeze/thaw cycles as much as possible. Instead, aliquot into smaller volumes.


Bradford Assay
==============

Introduction
------------

The Bradford Assay is used for protein concentration quantification.
It utilizes Coomassie Brilliant Blue G-250 dye which binds to proteins and shifts the maximum absorption from 470nm to 595nm.
This absorption at 595nm can be measured using the NanoDrop.
The protein concentration can be estimated by creating a standard curve and using Beer's law.

Materials
---------

* Bradford Assay Reagent
* BSA Standard (2 mg/mL)
* Lysis Buffer
* Lysate Samples

.. important::
   Ensure that the Bradford assay kit is compatible with the lysis buffer.

   For example, the Bradford assay should be compatible with RIPA lysis buffer but is not compatible with the CST Cell Lysis Buffer due to high amounts of Triton.

   See `Bradford Assay Documentation <https://geneseesci.com/shop-online/product-doc/18-442?doc_id=1>`_ for the full list of compatible reagents.

Protocol
--------

1. Remove Bradford Protein Assay Reagent from the refrigerator and gently mix by inverting the bottle several times.
2. Aliquot the required volume of the dye reagent and allow it to equilibrate to room temperature before use.
3. Prepare diluted BSA protein standards. Be sure to dilute the supplied BSA standard (2000 ug/mL) in the same buffer as the test samples (e.g. 1x lysis buffer).
   Use the tables below as a guide for preparing a set of protein standards.

For a working range of 100 to 1500 ug/mL:

====== ======================== ================================ ===================
Tube # Buffer/Diluent Vol. (uL) BSA Standard (2 mg/mL) Vol. (uL) Final Protein Conc.
====== ======================== ================================ ===================
Blank   80                          0                               0
1       0                           80                              2000 ug/mL
2       20                          60                              1500 ug/mL
3       40                          40                              1000 ug/mL
4       50                          30                              750 ug/mL
5       60                          20                              500 ug/mL
6       70                          10                              250 ug/mL
7       75                          5                               125 ug/mL
8       79                          1                               25 ug/mL
====== ======================== ================================ ===================

For a working range of 1 to 25 ug/mL:

====== ======================== ================================ ===================
Tube # Buffer/Diluent Vol. (uL) BSA Standard (2 mg/mL) Vol. (uL) Final Protein Conc.
====== ======================== ================================ ===================
Blank   800                          0                                 0
1       790                          10                                25 ug/mL
2       792                          8                                 20 ug/mL
3       794                          6                                 15 ug/mL
4       796                          4                                 10 ug/mL
5       798                          2                                 5 ug/mL
6       799                          1                                 2.5 ug/mL
7       799.5                        0.5                               1.25 ug/mL
====== ======================== ================================ ===================

1. Combine each standard and unknown sample with the Bradford Reagent.

   * For a working range of 100-1500 ug/mL, pipette 1 uL of each standard or unknown sample into a labeled tube and add 20 uL of the Bradford Protein Assay Reagent and mix well.
   * For a working range of 1-25 ug/mL, pipette 10 uL of each standard or unknown sample into a labeled tube and add 10 uL of the Bradford Protein Assay Reagent and mix well.

2. Incubate at room temperature for 10 minutes.
3. On the NanoDrop, select the Proteins tab and then Bradford Assay.
4. Enter the concentrations of each BSA standard and select the number of replicates.
5. Measure the absorbance of of each BSA standard as directed by the NanoDrop to construct the standard curve.
6. Measure the absorbance of each sample. The NanoDrop will automatically calculate the protein concentration for you based on the standard curve.





Protein Gel Casting
===================

Modified for a Western Blot from `this protocol <https://gallowaylabmit.github.io/protocols/en/latest/protocols/protein_production/bis_tris_protein_gels.html>`_.

Required stock solutions
------------------------

* **40% Acrylamide stock solution**: Solution of monomers for gel polymerization.

  We find it cheaper to buy premixed 40% stock solution, with a acrylamide:bis-acrylamide
  ratio of 29:1 (3.3%). Stocks with a 37.5:1 ratio also work, and are typically used
  for resolving larger proteins.


* **3x bis-Tris gel buffer**: Ion buffer used in gel casting.

  =========== =================== ==========================
  Component     Concentration     g/L to final concentration
  =========== =================== ==========================
  bis-Tris      1 M                 209.242
  HCl          Add to pH 6.5-6.8
  =========== =================== ==========================

* **10% APS**: One of the polymerization initiators. Only a small quantity
  needs to be prepared; each gel only requires 35 uL. Make fresh each time by dissolving in water.

  ======================== =================== ===========================================
  Component                 Concentration      g/L to final concentration
  ======================== =================== ===========================================
  Ammonium persulfate       10%                 100 (For example: 10mg/100uL or 100mg/1mL)
  ======================== =================== ===========================================

Casting protocol
----------------

.. warning::

    The acrylamide monomers used here are toxic. Read the
    `SDS <https://www.fishersci.com/store/msds?partNumber=BP14081&productDescription=ACRYLAMIDE%3ABISACRYLAMIDE+29%3A1&vendorId=VN00033897&countryCode=US&language=en>`_.

    Perform polymerization steps with a lab coat in a fume hood, and collect rinse waste in
    a waste container.
..

1. Prepare 1X resolving and stacking buffers. These buffers can be stored
   in the refrigerator for several weeks. Recipes given here for enough for 2 0.75mm gels.

   **Resolving buffer:** ~3 mL per gel (6.5 mL total). Final acrylamide concentration depends on desired protein size:

   ============  ==============  ===========================  ===============  =============================
   Protein Size  Gel %           Vol 40% Acrylamide Stock     Vol DI Water     Vol 3x bis-Tris gel buffer
   ============  ==============  ===========================  ===============  =============================
     4-40 kDa     20%               3.25 mL                       1.05 mL        2.2 mL
     12-45 kDa    15%               2.44 mL                       1.86 mL        2.2 mL
     10-70 kDa    12.5%             2.03 mL                       2.27 mL        2.2 mL
     15-100 kDa   10%               1.63 mL                       2.67 mL        2.2 mL
     25-100 kDa   8%                1.30 mL                       3.00 mL        2.2 mL
   ============  ==============  ===========================  ===============  =============================

   **Stacking buffer:**  ~1.2 mL per gel (2.5 mL total):

   =======================    ===========  ===========================================================
   Component                   Volume       Final concentration
   =======================    ===========  ===========================================================
   3x bis-Tris gel buffer       0.83 mL      1x
   40% Acrylamide stock         0.32 mL      5%
   DI water                     1.36 mL
   Bromophenol blue                         50 uL (enough to give color which helps when loading)
   =======================    ===========  ===========================================================


Gel casting setup
-----------------
In-lab, we have the ability to cast two gels simultaneous; this is recommended even if you only
need one, so that you have a backup in case of pouring mishaps. Our gel runner also requires two
poured gels to properly seal.

1. Locate two 0.75mm spacer plates and two short glass plates.
2. Use ethanol and a Kimwipe to clean both glass surfaces.
3. Assemble them in the green alignment device.
4. Lock the two gels into the transparent gel pouring device.

Resolving gel
~~~~~~~~~~~~~

.. tip::

    The resolving gel can polymerize within a just minute or two, especially at higher percentages of acrylamide.
    Therefore, pour the gel quickly using a P1000 pipette.

    It is best to pour the gel from the edges of the gel mold to avoid bubbles.

    Get ~10 mL isopropyl alcohol (IPA) ready before pouring the resolving gel to help keep the gel interface straight and level.
..

1.   Prepare fresh 10% APS. 1 gel requires ~35 uL so if making 2 gels, prepare ~100 µL (10 mg).
2.   Measure 6.5 mL of **1X resolving buffer** per gel to pour.
3.   Add 50 uL of **10% APS** per gel, mix well.
4.   Add 20 uL **TEMED**, mixing quickly (don't pipette mix, just flip it x3 manually to mix).
5.   Pour both gels to the resolving gel height (3 mL per gel, 1,000 µL at a time).
6.   Ideally there shouldn't be bubbles, but if so, lightly tap and tilt the gel to remove
7.   Once done pouring, quickly but carefully fill the remaining height with IPA, making sure the gel-water
     interface stays undisturbed. This is to ensure the resolving-stacking interface is straight and level.
8.   Wait for the polymerization reaction to finish (noticeable by a change in refractive index).
9.   Drain the IPA by tilting the gel past 90 degrees, and wicking away with a Kimwipe.


Stacking gel
~~~~~~~~~~~~

1.  Measure 2.5 mL of **1X stacking buffer** to pour.
2.  Add 20 uL of **10% APS**, mix well.
3.  Add 10 uL **TEMED**, mixing quickly (don't pipette mix, just flip it x3 manually to mix).
4.  Add 1,000 µL of stacking gel into each gel.
5.  Insert the comb into the top very carefully, one edge at a time to avoid bubbles. The stacking gel will overflow.
6.  If any bubbles, pop comb slightly up near problem area and use remaining buffer to fill before closing again.
7.  Wait for the stacking gel to polymerize.
8.  Rinse with water or IPA (evaporates faster) to remove unpolymerized acrylamide.
9.  If removing the combs prior to storage, slowly remove the comb, ensuring that wells are not broken.


Loading and Running the Gel
===========================

Modified for a Western Blot from `this <https://gallowaylabmit.github.io/protocols/en/latest/protocols/protein_production/denaturing_protein_gel.html>`_ protocol.

Solutions required
------------------
* **20x MES-SDS running buffer stock solution**: Suitable for separating proteins with a molecular weight less than 75 kDa.

  It is also generally cheaper to order this as a pre-mixed 20x stock solution. If you need to make it yourself, the recipe is:

  =========   ===================  ==========================
  Component   Final concentration  g/L to final concentration
  =========   ===================  ==========================
  MES           1 M                  195.2 g
  Tris          1 M                  121.13 g
  EDTA          20 mM                5.845 g
  SDS           2%                   N/A
  =========   ===================  ==========================

* **200x running buffer reductant**: Ensures that the gel remains under reducing conditions when run. Add directly to
  1x running buffer before filling the gel tank. Dissolve sodium bisulfite in DI water.

  .. note::
   Dilute sodium bisulfite solution loses effectiveness in ~2 days so spike in fresh each time.

   This helps because although β-mercaptoethanol in the Laemmli buffer is a strong reductant that prevents crosslinking via reduction
   of disulfide bonds, over time it can degrade.

  =================   ===================  ==========================
  Component           Final concentration  g/L to final concentration
  =================   ===================  ==========================
  Sodium bisulfite      1 M                 104.061 g
  =================   ===================  ==========================


* **200 mM Tris-HCl stock**: Dissolve components in DI water.

  =========== =================== ==========================
  Component     Concentration     g/L to final concentration
  =========== =================== ==========================
  Tris-HCl      200 mM                 31.52 g
  NaOH          Add to pH 6.8
  =========== =================== ==========================

* **20% SDS stock**: At low temperatures, the SDS may fall out of solution. Therefore, warm in a water bath to dissolve. Mix well before transferring.

  ======================= =================== ================================
  Component                Concentration      To make final concentration
  ======================= =================== ================================
  Sodium dodecyl sulphate          20%          2g / 10 mL DI water
  ======================= =================== ================================

* **0.1% bromophenol blue**: 1 mg / mL
* **2x Loading Buffer (Laemmli Buffer)**: Used to denature and solubilize protein samples. Can be stored at 4°C.

  ===========================  ======================  ================
  Component                     Final concentration     Volume
  ===========================  ======================  ================
  200 mM Tris-HCl stock         100 mM                  5 mL
  Glycerol                      20%                     2 mL
  20% SDS stock                 4%                      2 mL
  0.1% bromophenol blue stock   0.01%                   1 mL
  2-mercaptoethanol             10%                     1.1 mL
  ===========================  ======================  ================

.. warning::

    2-mercaptoethanol smells awful; always add it inside a fume hood.

    2-mercaptoethanol is hazardous waste and should be disposed of in the proper waste container.

Running procedure
-----------------
1. Add **2x Laemmli Buffer** to an equal volume of lysate in PCR tubes. 50-60 µL is good for ~4 lane (need 12.5 µL lysate/lane)
   This is recommended unless the online antibody datasheet indicates that non-reducing and non-denaturing conditions should be used.
2. Use a PCR machine to reduce and denature the lysate samples at 95℃ for 5 minutes (use 4℃ hold at end to keep cold).
3. Dilute enough **20x MES-SDS running buffer** to fill the gel tank,
   adding fresh **200x running buffer reductant** if a gel has not been recently run.
4. Place a prepared bis-Tris protein gel in the gel-runner. Fill both chambers with the prepared 1% MES-SDS running buffer.
   Fill the inner chamber to the top of the stacking gel, and the outside chamber to the top of the resolving gel.
   You will need about 1 liter of the 1% MES-SDS running buffer.
5. Carefully load equal amounts of protein samples, including 5 µL of a protein ladder, into the wells of the gel. Each well can be loaded with a maximum of 25 uL.
   20-30 ug of total protein from cell lysate is generally used unless further optimization is needed for the desired protein(s).

        - The protein ladder is in the -20℃ fridge in the restriction enzyme ice box

   .. note::
      BAL has found loading 12 uL of denatured lysate in Laemmli buffer per well is sufficient to detect most proteins.

      BAL tried freezing Laemmli buffer-denatured lysate at -20℃ and it worked for Western

   .. tip:: Choose an asymmetric loading pattern so if the gel is flipped over, you will still know the order of your samples.

   .. warning:: The glass gel holders have directionality! If your gel isn't reaching 30 mA check that the open side is facing inwards.

6. Run the gels at constant current, about 30 mA (~43V) per mini-gel for approximately 125 minutes. The dye band runs around 3-5 kDa, so
   it is typically ok to run the dye band to the bottom of the gel unless very small proteins are
   of interest.

        - Rinse gel holder and runner with water to help reduce smell

   .. note:: BAL has run the gel for up to 140 minutes and found this helps separate out some of the larger proteins such as pERK which has bands at both 42 and 44 kDa.

7. Pour DI water into a plastic tray (tip box lid), about half a centimeter deep.
8. Very carefully separate the gel plates without breaking the gel. The gel will stick to one side or the other.
9. With a razor blade, cut off the stacking portion of the gel while still on glass.
10. Invert the plate/gel over the water and "convince" the gel to fall into the dish. It can help to put the gel and plate into the water and let the solution help the gel release.
    Using a green gel scraper can also help with this process.
11. Place the gel on a rocker for 2-5 minutes to remove excess free proteins.


Coomassie Staining
==================

Solutions required
------------------

* **Coomassie staining dye**:
  When preparing this dye, pour the 10% methanol first, using it to dissolve the R-250.
  Then, add water. Add the glacial acetic acid last to prevent aggregation.

  ================  ===================  ==================
  Component         Final concentration  Amount per 1 liter
  ================  ===================  ==================
  Coomassie R-250    0.2% (2g/L)          2g
  Methanol           10%                  100 mL
  Water              80%                  800 mL
  Acetic acid        10%                  100 mL
  ================  ===================  ==================

* **10% Acetic Acid**: Used as a destain solution.

  .. Warning:: Do not microwave pure acetic acid.


Procedure
---------

1. Drain the water from the dish without dropping your gel in the sink, and cover with ~0.5 cm of Coomassie staining dye.
2. Place the gel in stain in the microwave and microwave on high until the solution just begins to boil (this step greatly accelerates the procedure and allows you to see you bands in a minute or so).
   This only takes 20-30 seconds in the microwave.
3. Remove from the microwave and place on a rocker for a few minutes. Once you see the gel filled with Coomassie, it's done.
4. Drain the Coomassie and cover the gel with water, rock for about 5 minutes, drain.
5. Cover with **10%** acetic acid, place a couple folded Kim-wipes over the gel, and microwave again until the solution begins to boil (20-30 seconds).
6.  Remove from microwave and rock to remove Coomassie not bound to protein.
    If there is excess stain, replace the 10% acetic acid and Kim-wipes and continue to rock until the gel is clear with dark purple protein bands.



Transferring the protein from the gel to the membrane
=====================================================

.. tip::
  Proteins in the gel can be transferred to a membrane using the iBlot2. It is recommended to watch
  `this iBlot2 tutorial video <https://www.youtube.com/watch?v=g7DT5xGheCE>`_ to learn how to use this device.
  The `iBlot2 manual <https://tools.thermofisher.com/content/sfs/manuals/iblot2_device_man.pdf>`_
  is another helpful resource for learning to use the iBlot2 and contains more detailed instructions.


1. Open the lid of the iBlot2 device using the latch. Ensure the blotting surface is clean. Wipe down electrical contacts.
2. Unseal the iBlot™ 2 Transfer Stack.
3. Separate the Top Stack and set it to one side of the bench with the transfer gel layer facing up.
     Keep the Bottom Stack in the transparent plastic tray. Top and bottom stacks are divided by a separator. Ensure the membrane is not stuck to the
     separator and is with the bottom stack.
4. Place the Bottom Stack with the plastic tray directly on the blotting surface.
5. Ensure there are no bubbles between the membrane and the transfer stack. Remove any trapped air bubbles using a roller such as a plastic conical.
6. Carefully separate the glass plates surrounding the gel so the gel is left on one of glass plates. Using a razor blade,
   cut off the stacking region of the gel. Then carefully remove the gel from the glass into a dish filled with 1 cm of DI water.
7. Place the pre-run gels on the transfer membrane of the Bottom stack. Note: two gels can fit onto a single membrane.
8. Use a roller to remove any air bubbles between the gel and the membrane.
9. Soak the iBlot Filter Paper from the transfer stack in a clean container of deionized water.
10. Place the presoaked iBlot Filter Paper on the pre-run gel. Use a roller to remove any air bubbles between the filter paper and gel.
11. Remove and discard the white plastic separator from the Top stack.
12. Take the Top Stack from the bench and place it on top of the presoaked filter paper with the copper electrode facing up
    (and transfer gel layer facing down). Remove any air-bubbles using a roller.
13. Place the iBlot™ 2 Absorbent Pad on top of the iBlot™ 2 Transfer Stack such that the electrical contacts are aligned with the corresponding
    electrical contacts on the blotting surface of the iBlot™ 2 Gel Transfer Device.
14. Use the Blotting Roller to flatten any protrusions in the transfer stack.
15. After assembling the iBlot™ 2 Gel Transfer Stack, perform blotting within 10-15 minutes of assembling the stacks with the gel.
16. Gently close the iBlot™ 2 Gel Transfer Device lid by pressing down with two hands on the sides of the lid. Make sure the latch is secure.
    Do not forcibly push the lid when closing, because it can cause the transfer stack or metal contacts to shift out of position.

    .. note::
      If the iBlot2 device says the transfer stack is not detected, try opening and closing the lid until you are able to start the program.
      Cleaning the electrical contacts before and after each use may help with this issue.

17. Ensure that the correct Method is selected.


  ======  ================  ================  ==============
  Method  Voltage           Default Run Time  Run Time Limit
  ======  ================  ================  ==============
  P0      | 20 V for 1 min  7 min             13 min
          | 23 V for 4 min
          | 25 V for 2 min
  P1      25 V              6 min             10 min
  P2      23 V              6 min             11 min
  P3      20 V              7 min             13 min
  P4      15 V              7 min             16 min
  P5      10 V              7 min             25 min
  ======  ================  ================  ==============

  .. note::
    See page 17 of the `iBlot2 manual <https://tools.thermofisher.com/content/sfs/manuals/iblot2_device_man.pdf>`_
    for more detailed information about running parameters.

    Transfer protocol P0 with default run time has worked previously when blotting for Beta-actin, WT-p53, and RAS.

    For proteins from 30 to 150 kDa method P0 for a 7 minute run time is recommended. For proteins >150 kDa methods P0 or P3 with
    a run time of 8-10 min is recommended.


18.	Touch the Start icon on the screen to begin the transfer.
19.	At the end of the transfer, the current automatically shuts off and the iBlot™ 2 Gel Transfer Device signals the end of transfer with repeated beeping sounds, and a message on the digital display.
20.	Touch the Done icon to stop the beeping.
21.	To obtain good transfer and detection results, open the device and disassemble the stack within 30 minutes of ending the blotting procedure.
22.	Open the lid of the iBlot™ 2 Gel Transfer Device.
23.	Discard the iBlot™ 2 Absorbent Pad and Top Stack.
24.	Carefully remove and discard the gel and filter paper. Remove the transfer membrane from the stack.
25.	If needed, cut the membrane with a razor blade or scissors to separate the regions corresponding to each gel.


Antibody Staining
=================

Solutions required
------------------
* **10X Tris-Buffered Saline (TBS)**:
  Add ~450 mL of DI water to dissolve the Tris and NaCl. Adjust to a pH of 7.6. Then add the remaining DI water to reach a final volume of 500 mL.

    .. note:: Took ~8-9 mL 12N HCl to get to pH ~ 7.6

  =========   ===================  =============
  Component   Final concentration  Amount Needed
  =========   ===================  =============
  Tris-base      200 mM             12 g
  NaCl           1500 mM            44 g
  DI Water                          To 500 mL
  =========   ===================  =============

* **10% Tween20**:

  =========   ===================  =============
  Component   Final concentration  Amount Needed
  =========   ===================  =============
  Tween20       10%                1 mL
  DI Water                         9 mL
  =========   ===================  =============

  .. note:: Larger volumes of Tween20 are easier to measure because it is very viscous.

* **1x Tris-Buffered Saline / Tween (TBST)**:

  ===========   =======================  =====================  =============================
  Component     Final concentration      Amount Needed (50 mL)   Amount Needed (1 L)
  ===========   =======================  =====================  =============================
  10X TBS       1X                       5 mL                     100 mL
  10% Tween20   0.1%                     0.5 mL                   10 mL  (or 1 mL Tween-20)
  DI Water                               To 50 mL                 890 mL (or 900 mL)
  ===========   =======================  =====================  =============================

* **Blocking Buffer**:

  ===========   =======================  ===================
  Component     Final concentration      Amount Needed
  ===========   =======================  ===================
  Milk Powder   5%                       2.5 g
  10% Tween20   0.1%                     0.5 mL
  10x TBS       1X                       5 mL
  DI Water                               To 50 mL
  ===========   =======================  ===================

* **10% Blocking Buffer**: For diluting primary and secondary antibodies.

  =============================     =======================  ===================
  Component                           Final concentration      Amount Needed
  =============================     =======================  ===================
  Blocking Buffer                      10%                      5 mL
  1x TBST (TBS/0.1% Tween-20)                                   45 mL
  =============================     =======================  ===================


Staining Procedure
------------------

   .. note:: A 10 cm dish works well for the wash steps.

1. Wash the membrane with DI water for 5 minutes using agitation.
2. Block the membrane with blocking solution for 30-60 minutes at room temperature with agitation. Alternatively, block overnight at 2-8°C. (NW does 60 min at RT).
3. Incubate the membrane with 4 mL/10 cm of primary antibody diluted (at manufacturer’s recommended dilution) in 10% blocking solution overnight at 2-8°C.
4. Wash the membrane 3 times for 10 minutes each in TBST using agitation to remove any unbound primary antibody.
5. Incubate blot with 4 mL/10 cm of secondary antibody HRP-conjugate at a 1:10,000 dilution (or at the manufacturer’s recommended dilution) for 30 minutes to 1 hour at room temperature using agitation. (NW does 1 hr at RT)

    - Can even go down to 1:50,000 for 2nd ab HRP-conjugate

6. Wash the membrane 6 times for 5 minutes each in TBST to remove any unbound secondary antibody conjugate. It is crucial to thoroughly wash the membrane after incubation with the HRP enzyme conjugate.
7. Prepare the `SuperSignal West Femto Substrate <https://www.thermofisher.com/order/catalog/product/34094>`_ working solution by mixing equal parts of the Substrate and Stable Peroxide components
   (e.g. 5 mL substrate with 5 mL stable peroxide). Use a sufficient volume (~3 mL/10 cm) to ensure the blot is completely wetted with the substrate and does not become dry.

   .. note:: The working solution is stable for up to 6-8 hours at room temperature.

8. Incubate the membrane with the substrate working solution for 5 minutes.
9.  Remove the blot from the working solution and place it in a labeled, clear plastic bag, and remove excess liquid with an absorbent tissue.
10. Image the blot using chemiluminescence. The membrane does not need to be removed from the clear plastic bag for imaging. The Niles Lab in BE has a ChemiDoc Imaging System that they let us use, and images can be transferred using a USB flash drive.
11. Blot quantification can be done using the `Gel Analyzer tool <https://alfresco.uclouvain.be/alfresco/service/guest/streamDownload/workspace/SpacesStore/62eef827-f095-4bfd-b607-e0688df2317c/ImageJ%20-%20western%20blot%20quantification.pdf?a=true&guest=true>`_ in ImageJ.

   .. note:: Use colorimetric for a black/white photo that you can merge with the chemiluminescence photo

    .. note:: NW uses optimal auto-rapid as default

   .. note::
      BAL has used a fluorescent secondary antibody instead of chemiluminescence since the ChemiDoc Imaging System can detect various fluorescent channels.
      This method seems to be slightly less sensitive and requires a high concentration of antibody for protein detection.
      Anti-rabbit secondary antibodies seem to bind to the protein ladder.
      Keep blots protected from light after adding the secondary antibody during staining.
      Online protocols suggest that it is important to make sure the membrane is dry before imaging.

      BAL has been able to re-probe a fluorescent blot for chemiluminescence.
      You can rewet the membrane by first using 70% ethanol and then washing with TBST because the PVDF membrane does not absorb aqueous solutions uniformly unless pre-wet.
      Once rewet, you can proceed to re-probe the membrane.