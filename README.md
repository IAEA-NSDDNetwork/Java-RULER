# Java-RULER Test Phase
The program recommended by USNDP and NSDD to calculate gamma-ray transition strengths in ENSDF file with proper propagations of large/asymmetric uncertainties including the Monte-Carlo approach for ENSDF evaluation. Java-RULER uses the slave version (BrIccS) of BrIcc (2008KI07)(https://bricc.anu.edu.au/) for calculations of conversion coefficients on the fly when needed. 

Java-RULER is part of the [ENSDF Analysis and Utility Programs](https://nds.iaea.org/public/ensdf_pgm/).

Please address any feedback to Jun Chen chenj@frib.msu.edu

## Change History

#### 2025-04
update BrIccS exectutables with new versions from T. Kibedi at ANU.

#### 2025-02
Bug fixes and improvements

#### 2024-09
Bug fixes and improvements

#### 2024-02
Bug fixes and improvements

#### 2023-05
Bug fixes and improvements, e.g., improved extracting of B(XL) values in level comments for calculating T1/2 and MR using the T1/2 and MR calculator. To get this calculator, right click on a blank area in the main window. To use this calculator, copy and paste a complete data section (including gamma data) of the level to be calculated into the top text area in the calculator window, as well as the level record line (only) of the final level of the transition to be calculated. 

#### 2023-04
Add calculations for B(E6) and B(M6)

#### 2023-02
-	Bug fix

#### 2022-08
-	Minor improvements

#### 2022-04
-	Following the discussions in the 2022 NSDD Sprint meeting, a result using the median value as the final value is also listed in the report file under the Monte-Carlo approach.  
-	A document-record line for Java-RULER version will be automatically inserted after the history record lines in the output file.

#### 2021-04
Minor fix 

#### 2019-04 
- Monte Carlo method for error propagation
- GUI window for plotting PDF of B(XL) from Monte-Carlo method
- GUI window for plotting comparisons of three approaches

#### 2018-12
Java version of Ruler code which has an improved treatment of uncertainties with respect to the old Ruler code. 
Comments and feedback should be sent to the code developer Jun Chen

## Disclaimer

Neither the author nor anybody else makes any warranty, express or implied, or assumes any legal liability or responsibility for the accuracy, completeness or usefulness of any information disclosed, or represents that its use would not infringe privately owned rights.
