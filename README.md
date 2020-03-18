# Autism Diagnosis

Autism spectrum disorder is a condition related to brain development that impacts how a person perceives and socializes with others, 
causing problems in social interaction and communication. The disorder also includes limited and repetitive patterns of behavior. 
The term "spectrum" in autism spectrum disorder refers to the wide range of symptoms and severity.

**ASD** includes conditions that were previously considered separate — autism, **Asperger's syndrome**, childhood 
disintegrative disorder and an unspecified form of pervasive developmental disorder. Some people still use the term "Asperger's syndrome,"
which is generally thought to be at the mild end of autism spectrum disorder. The dataset also predicts another category of **PDD**. 
Pervasive Developmental Disorder – Not Otherwise Specified (PDD-NOS) refers to a group of disorders characterised by impairment in the 
development of social interaction, verbal and non-verbal communication, imaginative activity and a limited number of interests and 
activities that tend to be repetitive.

In this project, thirteen personal characteristics are extracted from 785 subjects in the Autism Brain Imaging Data Exchange (ABIDE) 
database. ABIDE is an international collaborative project that collected data from a large number of ASD patients and typical non-ASD 
controls from 17 research and clinical institutes. 

The thirteen features are: 'SEX',  'HANDEDNESS_CATEGORY',  'AGE_AT_SCAN',  'FIQ',  'VIQ',  'PIQ',  'ADOS_TOTAL',  'ADI_R_SOCIAL_TOTAL_A', 
'ADI_R_VERBAL_TOTAL_BV',  'ADI_RRB_TOTAL_C',  'ADI_R_ONSET_TOTAL_D',  'SUB_IN_SMP',  'CURRENT_MED_STATUS'. For more detailed information about 
these phenotypes and their coding specifications, refer the ABIDE data legend in the above repository. 

'DSM_IV_TR' contains the four resultant classes. For deeper information of the machine learning models evaluated in this projectory, checkout
the python notebook autism_classification.ipynb in the above repository. Six different models along with their accuracy metrics are displayed
in the result. 

The ABIDE, Autism Brain Imaging Data Exchange, can be accessed at http://preprocessed-connectomes-project.org/abide/download.html.

Citation: Cameron Craddock, Yassine Benhajali, Carlton Chu, Francois Chouinard, Alan Evans, András Jakab, Budhachandra Singh Khundrakpam,
John David Lewis, Qingyang Li, Michael Milham, Chaogan Yan, Pierre Bellec (2013). The Neuro Bureau Preprocessing Initiative: open 
sharing of preprocessed neuroimaging data and derivatives. In Neuroinformatics 2013, Stockholm, Sweden.
