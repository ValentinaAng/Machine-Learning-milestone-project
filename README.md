# Machine-Learning-milestone-project

Problem description
The AIDS Clinical Trials Group Study 175 Dataset contains healthcare statistics and categorical information about patients who have been diagnosed with AIDS. This dataset was initially published in 1996. The prediction task is to predict whether or not each patient died within a certain window of time or not.

Column description:
* time - time to failure or censoring
* trt - treatment indicator, medication used for treatment (0 = ZDV only; 1 = ZDV + ddI, 2 = ZDV + Zal, 3 = ddI only). Where ZDV stands for Zidovudine, ddi stands for Drug-drug interactions and Zal stands for Zalcitabine.
* wtkg - weight in kg
* hemo - hemophilia (0=no, 1=yes)
* homo - homosexual activity (0=no, 1=yes)
* drugs - history of Intervanous drug use (0=no, 1=yes)
* karnof - Karnofsky score (on a scale of 0-100) where 0 means dead, 100 means no evidence of disease
* oprior - Non-ZDV antiretroviral therapy pre-175 (AIDS Clinical Trials Group Study 175) -> (0=no, 1=yes)
* z30 - ZDV in the 30 days prior to 175 (0=no, 1=yes)
* zprior - ZDV prior to 175 (0=no, 1=yes)
* preanti - days pre-175 anti-retroviral therapy
* race - race (0=White, 1=non-white)
* gender - gender (0=F, 1=M)
* str2 - antiretroviral history (0=naive, 1=experienced)
* strat - antiretroviral history stratification (1='Antiretroviral Naive',2='> 1 but <= 52 weeks of prior antiretroviral therapy',3='> 52 weeks)
* symptom - symptomatic indicator (0=asymp, 1=symp)
* trat - treatment indicator (0=ZDV only, 1=others)
* offtrt - 	indicator of off-trt before 96+/-5 weeks (0=no,1=yes)
* cd40 - CD4 (Clusters of differentiation 4 are glycoproteins present on the immune cells' surface such as monocytes) at baseline
* cd80 - CD8 (cells called cytotoxic T-lymphocytes) at baseline
* cd420 - CD4 at 20+/-5 weeks
* cd820 - CD8 at 20+/-5 weeks
* pidnum - Patient ID
* cid - censoring indicator (1 = failure, 0 = censoring), Death or Censored (did not die within the time of observation)
