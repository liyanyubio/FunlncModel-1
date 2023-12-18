# FunlncModel
A machine learning computational framework for the identification of functional long noncoding RNAs by integrating multi-omics network
Accumulating evidence indicates that long non-coding RNAs (lncRNAs) play important roles in molecular and cellular biology. Although many algorithms have been developed to reveal their associations with complex diseases by using downstream targets, the upstream (epi)genetic regulatory information has not been sufficiently leveraged to predict the function of lncRNAs in various biological processes. Therefore, we present FunlncModel, a machine learning-based interpretable computational framework, which aims to screen out functional lncRNAs by integrating a large number of (epi)genetic features and functional genomic features from their upstream/downstream multi-omic regulatory networks. We adopted the random forest method to mine nearly 60 features in three categories from over 2,000 datasets across 11 data types, including transcription factors (TFs), histone modifications, typical enhancers (TEs), super-enhancers (SEs), methylation sites, mRNAs, etc. FunlncModel outperformed alternative methods for classification performance in human embryonic stem cell (hESC) (0.95 AUROC and 0.97 AUPRC). It could not only infer the most known lncRNAs that influence the states of stem cells, but also discover novel high-confidence functional lncRNAs (HCFun_lncs). We extensively validated FunlncModel's efficacy by up to 27 cancer-related functional prediction tasks, which involved multiple cancer cell growth processes and cancer hallmarks. Meanwhile, we have also found that (epi)genetic regulatory features, such as TFs and histone modifications, serve as strong predictors for revealing the function of lncRNAs. Overall, FunlncModel is a strong and stable prediction model for identifying functional lncRNAs in specific cellular contexts.
![1702906200(1)](https://github.com/chunquanlipathway/FunlncModel/assets/59090102/83ca385a-e601-46b9-b798-452508fdf42b)
