# To do
## General:
- [ ] Add a data accessor function. E.g. my.eset.list <- MetaGxBreast::getExpressionSets(c("DUKE", "TRANSBIG"), rescale=FALSE, probe.gene.mapping=TRUE)

##MetaGxOvarian:
- [ ] Check that MetaGxOvarian has the datasets in the following: http://cancerres.aacrjournals.org/content/early/2015/06/27/0008-5472.CAN-14-3242.short (pg 12-13)
- [ ] Ovarian dataset: GSE53963
- [ ] Add sample number to Crijns dataset (differs from tumor sample #)
- [ ] For the Crijns dataset (GSE13876), include Ovarian tumor sample number, assigned unique patient id, and sample nr

##MetaGxBreast:
- [ ] Include DCIS data: http://cancerres.aacrjournals.org/content/72/17/4574.long
- [ ] Add additional clinical information to MUG

Example, _IDC_A001 has NA values for almost all fields (also in /Users/Natchar/Desktop/MetaGxData/MetaGxBreast/curation/breast/uncurated/MUG.csv), but on GEO we have:

http://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM265557
Alter = 72, Year_of_Diagnosis = 1990, Gender = f, pT = 1C, pN = 1BI, pM = X, Number_of_asported_lymphnodes = NA, Number_of_positive_lyphnodes = NA, Level_Estrogen_receptor_IHC = 3, Level_Progesteron_receptor_IHC = 3, Diagnosis = IDC, Lymphocyte_infiltration = NA, Status = NA, Reason_of_death = NA, DFS_Months = 111, OS_Months = 111, , Epithel_Percentage = NA, Menopausal_status_at_First_Tumor_Diagnosis = NA, Surgical_method = MRM,_axill._Lymphadenektomie, Her2neu_DAKO = NA, Neoadjuvant_PCT_with_Anthracyclin = NA, Neoadjuvant_PCT_without_Anthracyclin = NA, Postoperative_Radiation = yes, Postop_adjuvant_Hormontherapy = NA, Adjuvant_PCT_with_Anthracyclin = NA, Adjuvant_PCT_without_Anthracyclin = NA
- [ ] Add the datasets previously in SUPERTAM_HGU133A, SUPERTAM_HGU133PLUS2
- [ ] Add overall survival to dataset STK (PMID:16280042, GSE1456) 
- [ ] In dataset DUKE (PMID:16273092,GSE3143) add recurrence status (mentioned in the paper)
