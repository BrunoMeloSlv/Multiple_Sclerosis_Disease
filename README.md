# Multiple_Sclerosis_Disease
Desafio do kaggle: Multiple Sclerosis Disease

About Dataset
Prospective cohort study was conducted in Mexican mestizo patients newly diagnosed with CIS who presented at the National Institute of Neurology and Neurosurgery (NINN) in Mexico City, Mexico, between 2006 and 2010.

Multiple sclerosis (MS):
"Is the most common demyelinating disease, in which the insulating covers of nerve cells in the brain and spinal cord are damaged. This damage disrupts the ability of parts of the nervous system to transmit signals, resulting in a range of signs and symptoms, including physical, mental, and sometimes psychiatric problems. Specific symptoms can include double vision, visual loss, muscle weakness, and trouble with sensation or coordination. MS takes several forms, with new symptoms either occurring in isolated attacks (relapsing forms) or building up over time (progressive forms). In the relapsing forms of MS, between attacks, symptoms may disappear completely, although some permanent neurological problems often remain, especially as the disease advances.

While the cause is unclear, the underlying mechanism is thought to be either destruction by the immune system or failure of the myelin-producing cells. Proposed causes for this include genetics and environmental factors, such as viral infections. MS is usually diagnosed based on the presenting signs and symptoms and the results of supporting medical tests.
No cure for multiple sclerosis is known. Treatments attempt to improve function after an attack and prevent new attacks.[9] Physical therap and occupational therapy can help with people's ability to function. Many people pursue alternative treatments, despite a lack of evidence of benefit.[18] The long-term outcome is difficult to predict; better outcomes are more often seen in women, those who develop the disease early in life, those with a relapsing course, and those who initially experienced few attacks.

Multiple sclerosis is the most common immune-mediated disorder affecting the central nervous system.[20] Nearly one million people have MS in the United States in 2022, and in 2020, about 2.8 million people were affected globally, with rates varying widely in different regions and among different populations. The disease usually begins between the ages of 20 and 50 and is twice as common in women as in men. MS was first described in 1868 by French neurologist Jean-Martin Charcot. The name "multiple sclerosis" is short for multiple cerebro-spinal sclerosis, which refers to the numerous glial scars (or sclerae – essentially plaques or lesions) that develop on the white matter of the brain and spinal cord." Ref1.

"Multiple sclerosis (MS) begins with an acute clinical attack (clinically isolated syndrome) in approximately 85% of patients. The conversion rate from clinically isolated syndrome to multiple sclerosis has been documented at 30% to 82% in previous studies. When an individual presents for evaluation after a single episode of inflammation of the CNS, several decisions regarding follow-up in subsequent years need to be made, including that of whether or not to start a therapy. There is, therefore, an emerging need to identify the predictive factors that anticipate conversion from CIS to MS." Ref2.

Note: This data was collected in a study conducted in Mexican mestizo patients newly diagnosed with CIS who presented at the National Institute of Neurology and Neurosurgery (NINN) in Mexico City, Mexico, between 2006 and 2010.

Citation:
Pineda, Benjamin; Flores Rivera, Jose De Jesus (2023), “Conversion predictors of Clinically Isolated Syndrome to Multiple Sclerosis in Mexican patients: a prospective study.”, Mendeley Data, V1, doi: 10.17632/8wk5hjx7x2.1

License:
CC BY 4.0

Dataset column descriptions

ID: Patient identifier (int)
Age: Age of the patient (in years)
Schooling: time the patient spent in school (in years)
Gender: 1=male, 2=female
Breastfeeding: 1=yes, 2=no, 3=unknown
Varicella: 1=positive, 2=negative, 3=unknown
Initial_Symptoms: 1=visual, 2=sensory, 3=motor, 4=other, 5= visual and sensory, 6=visual and motor, 7=visual and others, 8=sensory and motor, 9=sensory and other, 10=motor and other, 11=Visual, sensory and motor, 12=visual, sensory and other, 13=Visual, motor and other, 14=Sensory, motor and other, 15=visual,sensory,motor and other
Mono _or_Polysymptomatic: 1=monosymptomatic, 2=polysymptomatic, 3=unknown
Oligoclonal_Bands: 0=negative, 1=positive, 2=unknown
LLSSEP: 0=negative, 1=positive
ULSSEP:0=negative, 1=positive
VEP:0=negative, 1=positive
BAEP: 0=negative, 1=positive
Periventricular_MRI:0=negative, 1=positive
Cortical_MRI: 0=negative, 1=positive
Infratentorial_MRI:0=negative, 1=positive
Spinal_Cord_MRI: 0=negative, 1=positive
initial_EDSS:?
final_EDSS:?
Group: 1=CDMS, 2=non-CDMS
Definition of some of the technical/medical terms [ref. from wikipedia if not stated explicitly].
Varicella : Another name for Chickenpox, or chicken pox, is a highly contagious disease caused by the initial infection with varicella zoster virus (VZV), a member of the herpesvirus family.

BAEP: In human neuroanatomy, brainstem auditory evoked potentials (BAEPs), also called brainstem auditory evoked responses (BAERs), are very small auditory evoked potentials in response to an auditory stimulus, which are recorded by electrodes placed on the scalp.

VEP: Visual evoked potential (VEP) is an evoked potential elicited by presenting light flash or pattern stimulus which can be used to confirm damage to visual pathway including retina, optic nerve, optic chiasm, optic radiations, and occipital cortex.

Oligoclonal bands: Oligoclonal bands (OCBs) are bands of immunoglobulins that are seen when a patient's blood serum, or cerebrospinal fluid (CSF) is analyzed. They are used in the diagnosis of various neurological and blood diseases. Oligoclonal bands are present in the CSF of more than 95% of patients with clinically definite multiple sclerosis.

SSEP : Somatosensory evoked potentials (SSEP) are recorded from the central nervous system following stimulation of peripheral nerves. ULSSEP (upper limb SSEP), LLSSEP (lower limb SSEP)

EDSS: The Expanded Disability Status Scale (EDSS) is a method of quantifying disability in multiple sclerosis and monitoring changes in the level of disability over time. It is widely used in clinical trials and in the assessment of people with MS. 2

Ideas for notebooks:

What symptoms/factors are better predictors of MS?
Classify the two groups based of the other independent features.
