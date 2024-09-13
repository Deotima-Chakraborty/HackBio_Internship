
# Stage_1

A Review on the paper titled "***Multi-omic machine learning predictor of breast cancer therapy response***".

**Introduction**

Systemic therapy and targeted therapy are examples of neoadjuvant treatment, which is being utilized more and more in breast cancer management to raise the rate of breast-conserving surgery and enhance survival. Neoadjuvant treatment is not well received by many patients, though. The complexity of tumor ecosystems has not been well captured by the few studies that have used single platform profiling. Better prognostic models should consider tumors as intricate ecosystems with communities of cancerous clones inside a milieu of stromal, vascular, and immune cell types that are impacted by therapy in order to enhance treatment response.

**Solving the Problem**

The microenvironment of the tumor and malignant cells form intricate ecosystems in breast malignancies. Responses to cytotoxic therapy are influenced by the relationships and makeup of these tumor ecosystems. This information has not been taken into account in attempts to develop response predictors. Before surgery, 168 patients receiving chemotherapy with or without HER2 (encoded by ERBB2)-targeted therapy had their breast tumors biopsied. The researchers gathered information on the clinical, digital pathology, genomic, and transcriptome profiles of these samples. These diagnostic biopsies' multi-omic characteristics were subsequently associated with pathology end points (complete remission or residual disease) during surgery. 

**Key Findings of the Study**

Researchers in this paper demonstrate that the pre-treated tumor environment influences the response to treatment, and that machine learning can be used to include the multi-omics landscape of the tumor into prediction models. After treatment, the extent of residual illness is consistently linked to pre-therapy characteristics such as tumor mutational and copy number landscapes, tumor growth, immunological infiltration, and T cell deficiency and exclusion. With an area under the curve of 0.87, a multi-omic machine learning model built using these features predicted a pathological full response in a dataset of 75 patients undergoing external validation. In summary, the baseline properties of the entire tumor ecosystem, as assessed by data integration and machine learning, dictate the response to treatment. It may be possible to create predictors for other malignancies using this method.

**About the Methodology**

The biological characteristics that were taken from a prospective neoadjuvant trial that gathered comprehensive pre-therapy tumour multi-omic data and linked it to the final response were defined here. The aspects of immune activation, evasion, and malignant cells were found to be related to the response to treatment. In order to create prediction models, these features—which were obtained via digital pathology, DNA and RNA sequencing, and clinicopathological variables—were fed into an ensemble machine learning technique. In separate, external cohorts, researchers verified the predictive models' accuracy and showed that the top performers combined genetic and clinicopathological data. It is possible to modify the general strategy to incorporate fewer or more recent features, and it is broadly relevant to other cancer types.

**Diving Deeper into the Results**

The research revealed that the baseline properties of the entire tumor ecosystem have a major role in determining response. As previously reported, tumor proliferation turned out to be a significant factor in determining response. Genomic characteristics such as TP53 mutations, tumor mutation burden, BRCA, HRD, and APOBEC mutational signatures, and chromosomal instability were linked to the response to chemotherapy in HER2− tumors and typically corresponded with proliferation. Surprisingly, response seems to be independent of proliferation in HER2+ tumors treated with chemotherapy and HER2-targeted antibodies. This observation has been documented before and ought to spur the investigation into the underlying mechanism. Remaining disease was linked to subclonal mutations and clonal diversity. This has also been observed in cases of oesophageal carcinoma, indicating that tumors with a variety of clones are more likely to harbor or be able to choose resistant subclones.

The TiME in tumors that have not received treatment is a key factor in determining how well a treatment will work. Previous studies using mouse models have demonstrated that an immune-competent tumor microenvironment is necessary for a successful chemotherapeutic response. Our RNA expression data allowed for the deconvolution of immune subpopulations, and the results indicated that tumors that eventually developed pCR had both innate and adaptive immunity active. In addition to confirming our earlier findings that digital pathology-derived lymphocytic density is an independent predictor of pCR, researchers also demonstrate that it has a substantial correlation with the cytolytic activity score, which serves as a stand-in for CD8 and natural killer cytotoxic cells. Numerous studies have indicated that the infiltration of tumor lymphocytes, as determined by pathologists, can predict the response to chemotherapy and immunotherapy. International norms for scoring are also in place. It has been suggested that chemotherapy-induced immunogenic cell death—a term used to describe the direct involvement of the immune system in the destruction of tumor cells—45. Researchers speculate that such chemotherapy-induced immunogenic cell death is mediated by an activated immune infiltration in the tumor microenvironment in therapy-naive tumors.

**Conclusion**

When it comes to predicting medication response, machine learning models that incorporate data from digital pathology, molecular pathology, and clinical settings perform noticeably better than those that only use clinical factors. The models appear to be robust, as evidenced by the high accuracy in external validation. This could open the door to the use of digital pathology and molecular pathology to guide therapy selection in upcoming clinical trials, especially those involving adjuvant therapy. In a broader sense, the approach emphasizes the significance of integrating data in machine learning models for response prediction, and it has the potential to produce comparable predictors for additional cancer types.

**References**
Sammut, SJ., Crispin-Ortuzar, M., Chin, SF. et al. Multi-omic machine learning predictor of breast cancer therapy response. Nature 601, 623–629 (2022). https://doi.org/10.1038/s41586-021-04278-5

**Contributors**
Name: Sahana Rusum Slack ID: U07KTU83EL9  Email: rusumsahana2001@gmail.com
Name: Zarak Imtiaz Khan Slack ID: U07K6J5SKP0 Email: khanzarak9799@gmail.com 
**Other Links**

