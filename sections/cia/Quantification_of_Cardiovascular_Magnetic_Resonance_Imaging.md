# Quantification of Cardiovascular Magnetic Resonance Imaging (CMR)

- Rob J. van der Geest, PhD
- Patrick de Koning, MSc

### Background
In this project, methods are developed for quantification of left ventricular function from magnetic resonance imaging (MRI) of the heart. A software package (MASS) has been developed providing automated contour detection and manual contour tracing facilities as well as dedicated global and regional LV function quantification tools. A short-axis MRI study of the heart consists of multiple slices covering the whole heart and multiple phases within the cardiac cycle. Left ventricular volumes can be measured from these images without using any geometrical assumptions from contours describing the endocardial (inner) and epicardial (outer) boundaries of the myocardium. Regional function analysis is also possible by measuring the left ventricular wall motion or wall thickening.

### Goals
Development of automated contour detection techniques to be able to reduce the total analysis time and to reduce the inter- and intraobserver variabilities associated with manual contour tracing.

### Approach
The contour detection that has been developed follows a number of steps. In the first step the center of the left ventricular cavity is detected using the Hough transform. By using this method for all slices through the left ventricle the long-axis of the LV is detected, which results in center points for the individual slice locations. Using this center point, epicardial contours are found in the first phase and subsequently in the remaining phases using a frame-to-frame contour detection procedure. This frame-to-frame epicardial contour detection procedure is based on matching of line profiles which are positioned perpendicularly to the model contour (derived from the first phase) and then automatically positioned at the corresponding tissue transitions in other phases within the same slice level. By this approach the algorithm is able to deal with the fact that the epicardial boundary of the myocardium is adjacent to regions having different gray value characteristics. A first estimate of the endocardial contour is found using an optimal thresholding technique within the region described by the epicardial contour. The final endocardial contour is found by using a model-based edge-detection technique using dynamic programming.

### Status
The developed contour detection algorithms are integrated into the software package QMass-MR ®, which is commercially available through MEDIS medical imaging systems.

### Contact
Rob J. van der Geest, PhD
Division of Image Processing
Department of Radiology, 1-C2S
Leiden University Medical Center
P.O. Box 9600
2300 RC Leiden
The Netherlands
Tel. +31 (0)71 526 2138
Fax. +31 (0)71 526 6801
e-mail: R.J.van_der_Geest@lumc.nl

## Publications
### 1995
Helbing WA, Bosch JG, Maliepaard C, Rebergen SA, van der Geest RJ, Hansen B, Ottenkamp J, Reiber JHC, de Roos A. Comparison of echocardiographic methods with magnetic resonance imaging for assessment of right ventricular function in children. Am J Cardiol 1995; 76:589-594.
- Hoogendoorn LI, Pattynama PMT, Buis B, van der Geest RJ, van der Wall EE, de Roos A. Noninvasive evaluation evaluation of aortocoronary bypass grafts with magnetic resonance flow mapping. Am J Cardiol 1995; 75:845-848.
- Lamb HJ, Singleton RR, van der Geest RJ, Pohost GM, de Roos A. MR imaging of regional cardiac function: Low-pass filtering of wall thickness curves. Magnetic Resonance in Medicine 1995; 34:498-502.
- Pattynama PMT, Lamb HJ, van der Velde EA, van der Geest RJ, van der Wall EE, de Roos A. Reproducibility of MRI-derived measurements of right ventricular volumes and mass. Magnetic Resonance Imaging 1995; 13:53-63.
- Holman ER, Vliegen HW, van der Geest RJ, Reiber JHC, van Dijkman PRM, van der Laarse A, de Roos A, van der Wall EE. Quantitative analysis of regional left ventricular function after myocardial infarction in the pig assessed with cine magnetic resonance imaging. Magn Reson Med 1995; 34:161-169.
- Dendale PAC, Franken PR, Waldman GJ, Baur LHB, Vandamme S, van der Geest RJ, de Roos A. Regional diastolic wall motion dynamics in anterior infarction: analysis and quantification with magnetic resonance imaging. Coronary Artery Disease 1995; 6:723-729.
### 1996
- Matheijssen NAA, Baur LHB, Reiber JHC, van der Velde EA, van Dijkman PRM, van der Geest RJ, de Roos A. Assessment of left ventricular volume and mass by cine-magnetic resonance imaging in patients with anterior myocardial infarction intra-observer and inter-observer variability on contour detection. Int J Cardiac Imag 1996; 12:11-19.
- Niezen RA, Helbing WA, van der Geest RJ, Rebergen SA, de Roos A. Biventricular systolic function and mass studied with MR imaging in children with pulmonary regurgitation after repair for Tetralogy of Fallot. Radiology 1996; 201:135-140.
- Helbing WA, Niezen RA, le Cessie S, van der Geest RJ, Ottenkamp J, de Roos A. Right ventricular diastolic function in children with pulmonary regurgitation after repair of Tetralogy of Fallot: Volumetric evaluation by magnetic resonance velocity mapping. J Am Coll Cardiol 1996; 28:1827-1835.
- Baur LHB, Schipperheyn JJ, van der Velde EA, van der Wall EE, Reiber JHC, van der Geest RJ, van Dijkman PRM, Gerritsen JG, van Eck-Smit BLF, Voogd PJ, Bruschke AVG. Reproducibility of left ventricular size, shape and mass with echocardiography, magnetic resonance imaging and radionuclide angiography with anterior wall infarction. A plea for core laboratories. Int J Card Imag 1996; 12:233-240.
### 1997
- van der Geest RJ, Buller VGM, Jansen E, Lamb HJ, Baur LHB, van der Wall EE, de Roos A, Reiber JHC. Comparison between manual and automated analysis of left ventricular volume parameters from short axis MR images. J Comput Assist Tomogr 1997; 21:756-765.
- van der Geest RJ, de Roos A, van der Wall EE, Reiber JHC. Quantitative analysis of cardiovascular MR images. Int J Card Im 1997; 13:247-258.
- Holman ER, Buller VGM, de Roos A, van der Geest RJ, Baur LHB, van der Laarse A, Bruschke AVG, Reiber JHC, van der Wall EE. Detection and quantification of dysfunctional myocardium by magnetic resonance imaging: A new three-dimensional method for quantitative wall-thickening analysis. Circulation 1997; 95:924-931.
- Johnson DB, Foster RE, Barilla F, Blackwell GG, Roney M, Stanley AWH, Kirk K, Orr RA, van der Geest RJ, Reiber JHC, Dell’Italia LJ. Angiotensin-converting enzyme Inhibitor therapy affects left ventricular mass in patients with ejection fraction >40% after acute myocardial infarction. J Am Coll Cardiol 1997; 29:49-54.
- Kayser HWM, Stoel BC, van der Wall EE, van der Geest RJ, de Roos A. MR velocity mapping of tricuspid flow: Correction for through-plane motion. J Magn Reson Im 1997; 7:669-673.
- Buller VGM, van der Geest RJ, Kool MD, van der Wall EE, de Roos A, Reiber JHC. Assessment of regional left ventricular wall parameters from short-axis MR imaging using a 3D extension to the improved centerline method. Invest Radiol 1997; 32:529-539.
- Dendale P, Franken PR, Meusel M, van der Geest RJ, de Roos A. Distinction between open and occluded infarct-related arteries using contrast-enhanced magnetic resonance imaging. Am J Cardiol 1997; 80:334-335.
### 1998
- van der Geest RJ, Niezen RA, van der Wall EE, de Roos A, Reiber JHC. Automated measurement of volume flow in the ascending aorta using MR velocity maps: evaluation of inter- and interobserver variability in healthy volunteers. J Comp Assist Tomogr 1998; 22:904-911.
- Kroft LJM, Doornbos J, van der Geest RJ, van der Laarse A, van der Meulen H, de Roos A. Ultrasmall superparamagnetic particles of iron oxide (USPIO) MR imaging of infarcted myocardium in pigs. MRI 1998; 16:755-763.
- Marcus JT, Götte MJW, de Waal LK, Stam MR, van der Geest RJ, Heethaar RM, van Rossum AC. The influence of through-plane motion on left ventricular volumes measured by magnetic resonance imaging: implications for image acquisition and analysis. J Cardiovasc Magnetic Resonance 1998; 1:1-6.
### 1999
- van der Geest RJ, Reiber JHC. Quantification in cardiac MRI. J Magn Reson Imag 1999; 10:602-608.
- Lelieveldt BPF, van der Geest RJ, Ramze Rezaee M, Bosch JG, Reiber JHC. Anatomical model matching with fuzzy implicit surfaces for segmentation of thoracic volume scans. IEEE Transactions on Medical Imaging 1999; 18:218-230.
- Kroft LJM, Doornbos J, van der Geest RJ. Blood pool contrast agent CMD-A2-Gd-DOTA-Enhanced MR imaging of infarcted myocardium in pigs. J Magn Reson Imaging 1999; 10:170-177.
- Kroft LJM, Doornbos J, van der Geest RJ, Benderbous S, de Roos A. Infarcted myocardium in pigs: MR imaging enhanced with slow-interstitial-diffusion gadolinium compound P760. Radiology 1999; 212:467-473.
- Marcus JT, de Waal LK, Götte MJW, van der Geest RJ, Heethaar RM, van Rossum AC. MRI-derived left ventricular function parameters and mass in healthy young adults: Relation with gender and age. Int J Cardiac Imag 1999; 15:411-419.
- Marcus JT, Smeenk HG, Kuijer JP, van der Geest RJ, Heethaar RM, van Rossum AC. Flow profiles in the left anterior descending and the right coronary artery assessed by MR velocity quantification: effects of through-plane and in-plane motion of the heart. J Comput Assist Tomogr 1999; 23:567-576.
### 2000
- van der Geest RJ, Lelieveldt BPF, Reiber JHC Quantification of global and regional ventricular function in cardiac magnetic resonance imaging. Topics in Magn Reson Imag 2000; 11:348-358.
- Kayser HW, van der Geest RJ, van der Wall EE, Duchateau C, de Roos A. Right ventricular function in patients after acute myocardial infarction assessed with phase contrast MR velocity mapping encoded in three directions. J Magn Reson Imag 2000; 11:471-475.
- Ramze Rezaee M, van der Zwet PMJ, B.P.F.Lelieveldt, van der Geest RJ, Reiber JHC. A multi-resolution segmentation technique based on pyramidal segmentation and fuzzy clustering. IEEE Transactions on Image Processing 2000; 9:1238-1248.
### 2001
- Mitchell SC, Lelieveldt BPF, van der Geest RJ, Bosch JG, Reiber JHC, Sonka M. Multistage hybrid active appearance model matching: Segmentation of left and right ventricles in cardiac MR images. IEEE Trans Med Imag 2001; 20:415-423.
- Lelieveldt BPF, van der Geest RJ, Lamb HJ, Kayser HWM, Reiber JHC. Automated observer-independent acquisition of cardiac short-axis MR images: A pilot study. Radiology 2001; 221:537-542.
### 2002
- Dirksen MS, Bax JJ, de Roos A, Jukema JW, van der Geest RJ, Geleijns K, Boersma E, van der Wall EE, Lamb HJ. Usefulness of dynamic Multislice Computed Tomography of left ventricular function in unstable angina pectoris and comparison with Echocardiography. Am J Cardiol 2002; 90:1157-1160.
- Mitchell SC, Bosch JG, Lelieveldt BPF, van der Geest RJ, Reiber JHC, Sonka M. 3-D Active appearance models: Segmentation of cardiac MR and ultrasound images. IEEE Med Imag 2002; 21:1167-1178.
### 2003
- Dirksen MS, Lamb HJ, van der Geest RJ, de Roos A. Toward comparability of coronary magnetic resonance angiography: proposal for a standardized quantitative assessment. Eur Radiology 2003; 13:2353-2357.
- Box FMA, Spilt A, Van Buchem MA, van der Geest RJ, Reiber JHC. Automatic model-based contour detection and blood flow quantification in small vessels with velocity encoded magnetic resonance imaging Invest Radiol. 2003; 38:567-577.
- de Koning PJH, Schaap JA, Janssen JP, Westenberg JJM, van der Geest RJ, Reiber JHC. Automated segmentation and analysis of vascular structures in magnetic resonance angiographic images. Magn Reson Med 2003; 50:1189-1198.
### 2004
- van der Geest RJ, Lelieveldt BPF, Angelié E, Danilouchkine M, Swingen C, Sonka M, Reiber JHC. Evaluation of a new method for automated detection of left ventricular boundaries in time series of magnetic resonance images using an Active Appearance Motion Model. J Cardiovasc Magn Reson 2004; 6:609-617.
- Schuijf JD, Kaandorp TA, Lamb HJ, van der Geest RJ, Viergever EP, van der Wall EE, de Roos A, Bax JJ. Quantification of myocardial infarct size and transmurality by contrast-enhanced magnetic resonance imaging in men. Am J Cardiol. 2004; 94:284-288.
- Westenberg JJM, Danilouchkine MG, Doornbos J, Bax JJ, van der Geest RJ, Labadie G, Lamb HJ, Versteegh MIM, de Roos A, Reiber JHC. Accurate and reproducible mitral valvular blood flow measurement with three-directional velocity-encoded magnetic resonance imaging. J Cardiovasc Magn Reson 2004; 6 :767-776.
- Dirksen MS, Bax JJ, de Roos A, Jukema JW, van der Geest RJ, Geleijns J, van der Wall EE, Lamb HJ. Dynamic multislice computed tomography of left ventricular function. Circulation 2004; 109:E25-E26.
### 2005
- Angelié E, De Koning PJH, Danilouchkine MG, Van Assen HA, Koning G, van der Geest RJ, Reiber JHC. Optimizing the automatic segmentation of the left ventricle in magnetic resonance images. Med Physics 2005; 32:369-375
- Westenberg JJM, Doornbos J, Versteegh MIM, Bax JJ, van der Geest RJ, de Roos A, Dion RAE, Reiber JHC. Accurate quantitation of regurgitant volume with MRI in patients selected for mitral valve repair European Journal of Cardio-thoracic Surgery 2005; 27:462–467.
- Üzümcü, M, van der Geest RJ, Sonka M, Lamb HJ, Reiber JHC, Lelieveldt BPF. Multiview active appearance models for simultaneous segmentation of cardiac 2- and 4-chamber long-Axis magnetic resonance images. Invest Radiol 2005; 40:195-203
- Paelinck BP, de Roos A, Bax JJ, Bosmans JM, van der Geest RJ, Dhondt D, Parizel PM, Vrints CJ, Lamb HJ. Feasibility of tissue magnetic resonance imaging: a pilot study in comparison with tissue Doppler imaging and invasive measurement. J Am Coll Cardiol. 2005; 45:1109-1116
- Westenberg JJM, van der Geest RJ, Lamb HJ, Versteegh MIM, Braun J, Doornbos J, de Roos A, van der Wall EE, Dion RAE, Reiber JHC, Bax JJ. MRI to evaluate left atrial and ventricular reverse remodeling after restrictive mitral annuloplasty in dilated cardiomyopathy. Circulation 2005; 112 [suppl I]:437-442.
- Danilouchkine MG, van der Geest RJ, Westenberg JJ, Lelieveldt BPF, Reiber JHC. Influence of positional and angular variation of automatically planned short-axis stacks on quantification of left ventricular dimensions and function with cardiovascular magnetic resonance. J Magn Reson Imaging 2005; 22:754-764.
### 2006
- Üzümcü M, van der Geest RJ, Swingen C, Reiber JH, Lelieveldt BP. Time continuous tracking and segmentation of cardiovascular magnetic resonance images using multidimensional dynamic programming. Invest Radiol. 2006; 41:52-62.
- Westenberg JJ, Lamb HJ, van der Geest RJ, Bleeker GB, Holman ER, Schalij MJ, de Roos A, van der Wall EE, Reiber JH, Bax JJ. Assessment of left ventricular dyssynchrony in patients with conduction delay and idiopathic dilated cardiomyopathy: head-to-head comparison between tissue doppler imaging and velocity-encoded magnetic resonance imaging. J Am Coll Cardiol. 2006; 47:2042-2048.
- Doðan H, Kroft LJ, Bax JJ, Schuijf JD, van der Geest RJ, Doornbos J, de Roos A. MDCT assessment of right ventricular systolic function. Am J Roentgenol. 2006; 186:S366-S370.
### 2007
- Doðan H, MD, Kroft LJM, Huisman MV, van der Geest RJ, de Roos A. Right Ventricular Function in Patients with Acute Pulmonary Embolism: Analysis with Electrocardiography-synchronized Multi–Detector Row CT. Radiology 2007; 242:78-84
- Milles J, van der Geest RJ, Jerosch-Herold M, Reiber JHC, Lelieveldt BPF. Fully automated registration of first-pass myocardial perfusion MRI using independent component analysis. Inf Process Med Imaging 2007; 20:544-555.
- Winter EM, Grauss RW, Hogers B, van Tuyn J, van der Geest RJ, Lie-Venema H, Vicente Steijn R, Maas S, de Ruiter MC, de Vries AAF, Steendijk P, Doevendans PA, van der Laarse A, Poelmann RE, Schalij MJ, Atsma DE, Gittenberger-de Groot AC. Preservation of left ventricular function and attenuation of remodeling after transplantation of human epicardium-derived cells into the Infarcted mouse heart. Circulation 2007; 116:917-927.
- Grauss RW, Winter EM, van Tuyn J, Pijnappels DA, Steijn RV, Hogers B, van der Geest RJ, de Vries AA, Steendijk P, van der Laarse A, Gittenberger-de Groot AC, Schalij MJ, Atsma DE. Mesenchymal stem cells from ischemic heart disease patients improve left ventricular function after acute myocardial infarction. Am J Physiol Heart Circ Physiol 2007; 293:H2438-H2447.
- Angelié E, Oost ER, Hendriksen D, Lelieveldt BP, Van der Geest RJ, Reiber JH. Automated contour detection in cardiac MRI using active appearance models: the effect of the composition of the training set. Invest Radiol. 2007; 42:697-703.
### 2008
- Henneman MM, Schuijf JD, Dibbets-Schneider P, Stokkel MP, van der Geest RJ, van der Wall EE, Bax JJ. Comparison of multislice computed tomography to gated single-photon emission computed tomography for imaging of healed myocardial infarcts. Am J Cardiol. 2008; 101:144-148.
- Winter EM, Grauss RW, Atsma DE, Hogers B, Poelmann RE, van der Geest RJ, Tschöpe C, Schalij MJ, Gittenberger-de Groot AC, Steendijk P. Left ventricular function in the post-infarct failing mouse heart by magnetic resonance imaging and conductance catheter: a comparative analysis. Acta Physiol (Oxf). 2008; 194:111-122.
- Grauss RW, van Tuyn J, Steendijk P, Winter EM, Pijnappels DA, Hogers B, Gittenberger-De Groot AC, van der Geest RJ, van der Laarse A, de Vries AA, Schalij MJ, Atsma DE. Forced myocardin expression enhances the therapeutic effect of human mesenchymal stem cells after transplantation in ischemic mouse hearts. Stem Cells. 2008; 26:1083-1093.
- Westenberg JJ, Braun J, Van de Veire NR, Klautz RJ, Versteegh MI, Roes SD, van der Geest RJ, de Roos A, van der Wall EE, Reiber JH, Bax JJ, Dion RA. Magnetic resonance imaging assessment of reverse left ventricular remodeling late after restrictive mitral annuloplasty in early stages of dilated cardiomyopathy. J Thorac Cardiovasc Surg. 2008; 135:1247-1252.
- Westenberg JJ, Roes SD, Ajmone Marsan N, Binnendijk NM, Doornbos J, Bax JJ, Reiber JH, de Roos A, van der Geest RJ. Mitral Valve and Tricuspid Valve Blood Flow: Accurate Quantification with 3D Velocity-encoded MR Imaging with Retrospective Valve Tracking. Radiology. 2008; 249:792-800.
- Milles J, van der Geest RJ, Jerosch-Herold M, Reiber JH, Lelieveldt BPF. Fully automated motion correction in first-pass myocardial perfusion MR image sequences. IEEE Trans Med Imaging. 2008; 27:1611-1621.
### 2009
- Roes SD, Westenberg JJ, Doornbos J, van der Geest RJ, Angelié E, de Roos A, Stuber M. Aortic vessel wall magnetic resonance imaging at 3.0 tesla: A reproducibility study of respiratory navigator gated free-breathing 3D black blood magnetic resonance imaging. Magn Reson Med 2009; 61:35-44.
- Roes SD, Borleffs CJW, van der Geest RJ, Westenberg JJM, Ajmone Marsan N,. Kaandorp TAM, Reiber JHC, Zeppenfeld K, Lamb HJ, de Roos A, Schalij MJ, Bax JJ. Infarct Tissue Heterogeneity Assessed with Contrast-Enhanced Magnetic Resonance Imaging Predicts Spontaneous Ventricular Arrhythmia in Patients with Ischemic Cardiomyopathy and Implantable Cardioverter-Defibrillator. Circ Cardiovasc Imaging 2009;2(3):183-190.
- Marsan NA, Westenberg JJ, Ypenburg C, van Bommel RJ, Roes S, Delgado V, Tops LF, van der Geest RJ, Boersma E, de Roos A, Schalij MJ, Bax JJ. Magnetic resonance imaging and response to cardiac resynchronization therapy: relative merits of left ventricular dyssynchrony and scar tissue. Eur Heart J 2009;30(19):2360-2367.
- Grotenhuis HB, Westenberg JJ, Steendijk P, van der Geest RJ, Ottenkamp J, Bax JJ, Jukema JW, de Roos A. Validation and reproducibility of aortic pulse wave velocity as assessed with velocity-encoded MRI. J Magn Reson Imaging 2009;30(3):521-526.
- Roes SD, Hammer S, van der Geest RJ, Ajmone Marsan N, Bax JJ, Lamb HJ, Reiber JHC, de Roos A, Westenberg JJM. Flow assessment through four heart valves simultaneously using 3-dimensional 3-directional velocity-encoded magnetic resonance imaging with retrospective valve tracking in healthy volunteers and patients with valvular regurgitation. Invest Radiol 2009;44:669-675
- Marsan NA, Westenberg JJ, Ypenburg C, Delgado V, van Bommel RJ, Roes SD, Nucifora G, van der Geest RJ, de Roos A, Reiber JC, Schalij MJ, Bax JJ. Quantification of functional mitral regurgitation by real-time 3D echocardiography: comparison with 3D velocity-encoded cardiac magnetic resonance. JACC Cardiovasc Imaging. 2009;2(11):1245-1252.
### 2010
- Attili AK, Schuster A, Nagel E, Reiber JHC, van der Geest RJ. Quantification in cardiac MRI: advances in image acquisition and processing. Int J Cardiovasc Imaging 2010.
- Germans T, Russel IK, Gotte MJW, Spreeuwenberg MD, Doevendans PA, Pinto YM, van der Geest RJ, van der Velden J, de Wilde AAM, van Rossum AC. How do hypertrophic cardiomyopathy mutations affect myocardial function in carriers with normal wall thickness? Assessment with cardiovascular magnetic resonance. J Cardiovasc Magn Reson 2010;12:13, doi:10.1186/1532-429X-12-13.
- Tao Q, Milles J, Zeppenfeld K, Lamb HJ, Bax JJ, Reiber JH, van der Geest RJ. Automated segmentation of myocardial scar in late enhancement MRI using combined intensity and spatial information. Magn Reson Med. 2010;64(2):586-594.
- Doðan H, Kroft LJ, Huisman MV, van der Geest RJ, Li O Y, Lamb HJ, de Roos A. Assessment of right ventricular function in acute pulmonary embolism using ECG-synchronized MDCT. AJR Am J Roentgenol 2010;195(4):909-915.
- Gupta V, Hendriks EA, Milles J, van der Geest RJ, Jerosch-Herold M, Reiber JH, Lelieveldt BPF. Fully Automatic Registration and Segmentation of First-Pass Myocardial Perfusion MR Image Sequences. Acad Radiol. 2010;17(11):1375-1385.
- Wijnmalen AP, van der Geest RJ, van Huls van Taxis CF, Siebelink HM, Kroft LJ, Bax JJ, Reiber JHC, Schalij MJ, Zeppenfeld K. Head-to-head comparison of contrast-enhanced magnetic resonance imaging and electroanatomical voltage mapping to assess post-infarct scar characteristics in patients with ventricular tachycardias: Real-time image integration and reversed registration. Eur Heart J 2010;32(1):104-114.
- Westenberg JJ, de Roos A, Grotenhuis HB, Steendijk P, Hendriksen D, van den Boogaard PJ, van der Geest RJ, Bax JJ, Jukema JW, Reiber JHC. Improved aortic pulse wave velocity assessment from multislice two-directional in-plane velocity-encoded magnetic resonance imaging. J Magn Reson Imaging. 2010;32(5):1086-1094.
- Gai N, Turkbey EB, Nazarian S, van der Geest RJ, Liu CY, Lima JA, Bluemke DA. T-1 mapping of the gadolinium-enhanced myocardium: Adjustment for factors affecting interpatient comparison. Magn Reson Med. 2011;65(5):1407-1415.
- Kiriþli HA, Schaap M, Klein S, Papadopoulou SL, Bonardi M, Chen CH, Weustink AC, Mollet NR, Vonken EJ, van der Geest RJ, van Walsum T, Niessen WJ. Evaluation of a multi-atlas based method for segmentation of cardiac CTA data: a large-scale, multicenter, and multivendor study. Med Phys. 2010 ;37(12):6279-6291.
### 2011
- Marsan NA, Westenberg JJ, Roes SD, van Bommel RJ, Delgado V, van der Geest RJ, de Roos A, Klautz RJ, Reiber JC, Bax JJ. Three-dimensional echocardiography for the preoperative assessment of patients with left ventricular aneurysm. Ann Thorac Surg. 2011;91(1):113-121.
- Brandts A, Bertini M, van Dijk EJ, Delgado V, Marsan NA, van der Geest RJ, Siebelink HM, de Roos A, Bax JJ, Westenberg JJ. Left ventricular diastolic function assessment from three-dimensional three-directional velocity-encoded MRI with retrospective valve tracking. J Magn Reson Imaging. 2011;33(2):312-319.
- Zeppenfeld K, van der Geest RJ. The infarct characteristics on magnetic resonance imaging and ventricular tachycardia: do we see what we need to see? Europace. 2011;13(6):770-772.
- Asghar MS, Hansen AE, Amin FM, van der Geest RJ, Koning PV, Larsson HB, Olesen J, Ashina M. Evidence for a vascular factor in migraine. Ann Neurol. 2011;69(4):653-645.
- Boogers MJ, van Werkhoven JM, Schuijf JD, Delgado V, El-Naggar HM, Boersma E, Nucifora G, van der Geest RJ, Paelinck BP, Kroft LJ, Reiber JH, de Roos A, Bax JJ, Lamb HJ. Feasibility of diastolic function assessment with cardiac CT Feasibility study in comparison with tissue doppler imaging. JACC Cardiovasc Imaging. 2011;4(3):246-256.
- Westenberg JJ, Scholte AJ, Vaskova Z, van der Geest RJ, Groenink M, Labadie G, van den Boogaard PJ, Radonic T, Hilhorst-Hofstee Y, Mulder BJ, Kroft LJ, Reiber JH, de Roos A. Age-related and regional changes of aortic stiffness in the marfan syndrome: Assessment with velocity-encoded MRI. J Magn Reson Imaging. 2011 Jul 14. doi: 10.1002/jmri.22646. [Epub ahead of print].
- Boyé P, Abdel-Aty H, Zacharzowsky U, Bohl S, Schwenke C, van der Geest RJ, Dietz R, Schirdewan A, Schulz-Menger J. Prediction of life-threatening arrhythmic events in patients with chronic myocardial infarction by contrasteEnhanced CMR. JACC Cardiovasc Imaging. 2011;4(8):871-879.
- Tao Q, Milles J, van Huls van Taxis C, Lamb HJ, Reiber JH, Zeppenfeld K, van der Geest RJ. Toward Magnetic Resonance-Guided Electroanatomical Voltage Mapping for Catheter Ablation of Scar-Related Ventricular Tachycardia: A Comparison of Registration Methods. J Cardiovasc Electrophysiol. 2011 Sep 13. doi: 10.1111/j.1540-8167.2011.02167.x. [Epub ahead of print] .
- Turkbey EB, Backlund JY, Genuth S, Jain A, Miao C, Cleary PA, Lachin JM, Nathan DM, van der Geest RJ, Soliman EZ, Liu CY, Lima JA, Bluemke DA and the DCCT/EDIC Research Group. Myocardial Structure, Function, and Scar in Patients With Type 1 Diabetes Mellitus. Circulation. 2011 Oct 18;124(16):1737-1746. Epub 2011 Sep 26.
- Nacif MS, Turkbey EB, Gai N, Nazarian S, van der Geest RJ, Noureldin RA, Sibley CT, Ugander M, Liu S, Arai AE, Lima JA, Bluemke DA. Myocardial T1 mapping with MRI: Comparison of look-locker and MOLLI sequences. J Magn Reson Imaging. 2011 Sep 23. doi: 10.1002/jmri.22753. [Epub ahead of print]
- DCCT/EDIC Research Group, de Boer IH, Sun W, Cleary PA, Lachin JM, Molitch ME, Steffes MW, Zinman B. Intensive diabetes therapy and glomerular filtration rate in type 1 diabetes. N Engl J Med. 2011 Dec 22;365(25):2366-76. Epub 2011 Nov 12.
- Ng ACT, Auger S, Delgado V, Elderen SGV, Bertini M, Siebelink HM, van der Geest RJ, Bonetti C, van der Velde ET, de Roos A, Smit JWA, Leung DY, Bax JJ, Lamb HJ. Association between diffuse myocardial fibrosis by cardiac magnetic resonance contrast-enhanced T1 mapping and subclinical myocardial dysfunction in diabetic patients: A pilot study. Circ Cardiac Imaging 2011. DOI: 10.1161/CIRCIMAGING.111.965608.