# CFIBRO.PTML
IFPTML Personalized Medicine Metagenomic Analysis of Microbiome Cystic Fibrosis Patients

#Authors
Carmen Velásquez 1, Estefania Asencio-Medina2,3,6, 
Amaia González-Magaña1, Maria. D Pastor-Viveros1 
Sonia Arrasate3,4, Humberto González-Díaz1,4,5, David Albesa-Jové,1,5

#Affiliations
1 BIOFISIKA: Basque Center for Biophysics CSIC, (UPV/EHU), Barrio Sarriena s/n, Leioa, Bizkaia 48940
2 Department of Computer Science and Information Technologies, Faculty of Computer Science, CITIC-Research Center of Information and Communication Technologies, University of A Coruña, Campus Elviña s/n, 15071, A Coruña, Spain.
3 IKERDATA S.L., ZITEK, University of Basque Country UPVEHU, Rectorate Building, 48940 Leioa, Spain.
4Department of Organic and Inorganic Chemistry, Faculty of Science and Technology, University of The Basque Country (UPV/EHU), P.O. Box 644, 48080, Bilbao, Spain.
5IKERBASQUE, Basque Foundation for Science, 48011, Bilbao, Spain.
6Departamento de Bioquímica y Biología Molecular, Universidad del País Vasco UPV/EHU, 48080 Bilbao, España.

# Abstract
Cystic fibrosis (CF) is an autosomal recessive monogenic disease caused by mutations in a gene on the long arm of chromosome 7 that codes for the CFTR (Cystic Fibrosis Transmembrane conductance Regulator) protein (Kerem et al.,1989) These mutations cause dysfunctional transport of chloride and other ions such as sodium and bicarbonate (Fonseca et al., 2020) which leads to the generation of thick and viscous mucus secretions from the lungs, as a consequence the airways are obstructed with an ideal environment for microbial colonization (Chen et al., 2021) During childhood infections produced by Staphylococcus aureus, Haemophilus influenzae and Streptococcus are common, while in adults Pseudomonas aeruginosa, Stenotrophomonas maltophilia and Burkholderia spp predominate (O’Toole, 2018) However 80% of patients suffer from chronic P. aeruginosa infection and generally, their presence is associated with more rapid disease progression, along with an increased risk of morbidity and mortality (Zemanick et al., 2017)  The main treatment in this disease and specifically in exacerbations (phenomenon where there is a rapid deterioration of lung function) is antibiotic therapy  (Girirajan et al., 2011). The choice administered to each patient depends on the antibiotic resistance profile obtained from a routine practice where sputum is analyzed during an exacerbation (Döring et al., 2012) In addition, antibiotic resistances present in each microorganism could be identified, which would help to understand the relationships between the microbiome, resistances and disease. This information would be useful to find more effective therapeutic approaches that do not accelerate antibiotic resistance and delay disease progression (Stanford et al., 2021a). However with this method significant clinical improvements are not always observed based on these results(O’Toole, 2018) In this moment are developing methods independent of culture, which allow the detection and quantification of all microorganisms present in a clinical sample, obtaining more information about the pulmonary microbiome and facilitating the development of powerful diagnostic, prognostic and treatment tools, for example Next-generation sequencing (NGS) (Sheka et al., 2021Kai et al., 2019).Such as targeted metagenomics for the identification of bacterial species from a clinical sample, specifically, the 16S rRNA gene is usually chosen as the diagnostic gene for sequencing. This choice is due to the fact that rRNA genes are universal in all organisms, so their sequencing allows taxonomic identification (at the genus level and even being able to differentiate between species) of the bacterial diversity of a complex biological mixture (Marimón, 2018) With the use of NGS platforms it is possible to obtain the complete composition of the microbiome, however studying bacterial communities as a complex network, instead of each element separately taking into account variables such as (exacerbations, treatment, age, CFTR protein mutation, other pathologies, metagenomics), is the opportunity to obtain information from patients in a personalized way (Wani et al., 2022)  However, the analysis of the large number of data could be extensive and time consumin (Badillo et al., 2020) The use Artificial inteligence /Machine learning (AI/ML) could be a solution, using the data generated in CF research to create customized Personalized Medicine (PM) treatments for specific patients. We used the model IFPTML with includes (Information Fusion +Perturbation Theory + Machine Learning) using the Non-linear ML methods (LDA) (Bediaga et al., 2022).The IFPTML has been used in multiple studies for example nano medicinal (Diéguez-Santana & González-Díaz, 2023) leishmaniasis (Santiago et et al., 2021) antifungal drugs (Jansen et al.,2021) etc. Additionally, we are going to train alternative IFPTML models with other models from ML, such as artificial neuronal networks (ANN) (Diéguez-Santana et al., 2022) In our case, based on a study of the pulmonary microbiome, by metagenomic sequencing, in patients with FQ and with other clinical data of the patient. We build a predictive model that will improve the patient's prognosis and help to design more personalized and effective treatments for this disease. 


#Data Protection
All data management and analysis were in compliance with the General Data Protection Regulation (GDPR). GDPR defines pseudonymization in Article 4 (5) as: 'the processing of personal data in such a way that they can no longer be attributed to a data subject without the use of additional information, provided that such additional information is kept separately and is subject to technical and organizational measures intended to ensure that the personal data are not attributed to an identified or identifiable natural person'. In general terms, pseudonymization aims at protecting personal data by hiding the identity of individuals (data subjects) in a data set, for example by replacing one or more personal data identifiers with so-called pseudonyms and by adequately protecting the link between the pseudonyms and the initial identifiers. Consequently, all patient data was pseudonymized by the team of the First Affiliated Hospital of Soochow University by using an internal code to identify the patients. These codes and the identities of patients were never shared with the other researchers in this paper. In addition, the pseudonymized data was processed in a single computer and was never copied, transferred, or accessed from/to other devices in the UPV/EHU.

#Supporting Information
Supporting information files contain the following information:

Supporting Information file SI00.doc
Under construction

Supporting Information file SI01.xlsx
Under construction

Additionally, the data is also released for free in data repository Figshare and indexed with doi number: https://doi.org/10.6084/m9.figshare.21206174.v1.

#ANN code
Supporting information file IFPTML-ANN-CFIBRO.c contain the code in c language of the ANN models trained and validated in this paper. The code of the software used to generate the models is part of the STATISTICA package an is not propietary of the authors for release. The code may be used to implement the model in other software ever following the licence specifications by Statsoft inc. specified inside these files. Please in case you want to obtain similar ANN models use this package or other ANN algorithms package implemented in Phyton, WEKA, or other algorithms. In any case, we would like to point out that the linear models presented in the paper are simpler and have similar to better statistical performance than the ANN models released here. If your objective is using our models to predict new fuel blends we recommend the linear models instead of the ANN models released here. This linear models can be run in Excel or in any other script using the linear equations presented in the paper. You can reproduce the models using the data released at follows in the Supporting information files.

# Funding
Under construction

#References
Under construction


