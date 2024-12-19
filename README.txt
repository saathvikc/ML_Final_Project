1. The file "final_BRCA_pipeline.ipynb" was written to be run directly on jupyter notebook
>> jupyter notebook final_BRCA_pipeline.ipynb
2. The files "Human__[]" were meant to be in the same directory as  "final_BRCA_pipeline.ipynb"

TO DOWNLOAD THE GENE EXPRESSION DATA
Link for data, click on download link based on the following files and their descriptor
https://www.linkedomics.org/data_download/TCGA-BRCA/

Download the following files:
Human__TCGA_BRCA__WUSM__Mutation__GAIIx__01_28_2016__BI__Gene__Firehose_MutSig2CV.cbt: Somatic mutations at gene level SNVs
Human__TCGA_BRCA__UNC__RNAseq__HiSeq_RNA__01_28_2016__BI__Gene__Firehose_RSEM_log2.cct: RNAseq data normalized counts (Illumina HiSeq platform, Gene-level, RPKM)
Human__TCGA_BRCA__MS__Clinical__Clinical__01_28_2016__BI__Clinical__Firehose.tsi: Clinical annotation
Human__TCGA_BRCA__JHU_USC__Methylation__Meth450__01_28_2016__BI__Gene__Firehose_Methylation_Prepocessor.cct: Methylation data of tumor samples at Gene level (Beta values, Illumina HM450K platform)
Human__TCGA_BRCA__BDGSC__miRNASeq__HS_miR__01_28_2016__BI__Gene__Firehose_RPKM_log2.cct: miRNA expression for tumor samples (Illumina HiSeq platform, Normalized, miRgene-level, RPM)

3. The file "brca-clinicalforwiki.xls" is meant to be in the same directory as "final_BRCA_pipeline.ipynb"
4. Image dicom data is meant to be in the directory "TCGA-BRCA"
=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=
5. BEFORE RUNNING
in the second line of the .ipynb --> the jupyter notebook insert dicom directory "wherever the TCGA-BRCA directory path is WITH a slash at the end" (example: directory = "TCGA-BRCA/") in the second line of the .ipynb