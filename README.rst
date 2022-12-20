#########################
LINCS L1000 Pilot PHASE I
#########################

`<https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE92742>`_

**`Series GSE92742 </geo/q uery/acc.cgi?acc=GSE92742>`__**: `Query DataSets for
GSE92742 </gds/?ter m=GSE92742%5BAccession%5D>`__

**Status:** Public on Mar 03, 2017

**Title:** L1000 Connectivity Map perturbational profiles from Broad Institute
LINCS Center for Transcriptomics LINCS Pilot PHASE I (n=1,319,138; updated
March 03, 2017)

**Project:** `Connectivity Map <https://clue.io/>`__

**Sample organism:** `Homo sapiens
</Taxonomy/Browser/wwwtax.cgi?mode=Info&id=9606>`__

**Experiment type:** Expression profiling by array

**Web link:** `<https://clue.io/>`_

**Submission date:** Dec 22, 2016

**Last update date:** Sep 08, 2021

**Contact name:** Aravind Subramanian

**Organization name:** The Broad Institute

**Lab:** Connectivity Map

**Street address:** 415 Main Street

**City:** Cambridge

**State/province:** MA

**ZIP/Postal code:** 02142

**Country:** USA

*******
Summary
*******

The Library of Integrated Cellular Signatures (LINCS) is an NIH program which
funds the generation of perturbational profiles across multiple cell and
perturbation types, as well as read-outs, at a massive scale.  The LINCS Center
for Transcriptomics at the Broad Institute uses the L1000 high-throughput
gene-expression assay to build a Connectivity Map which seeks to enable the
discovery of functional connections between drugs, genes and diseases through
analysis of patterns induced by common gene-expression changes. These files
represent L1000 data generated during the LINCS Pilot Phase (2012-2015), as
well as profiles generated for more specific purposes, such as assay
development and validation projects or testing custom compounds or non-standard
cell lines (not part of the core LINCS cell lines). Note: Related GEO projects
include (a) Additional L1000 and RNA-Seq data used to validate the assay and
improve the inference model, available at GSE92743 (b) The LINCS “production
phase” (also termed Phase II, 2015-2020) which is generating an additional
cohort of L1000 data, available at GSE70138.  The Platform is GPL20573: Broad
Institute Human L1000 epsilon
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GPL20573 For questions or
assistance with this dataset, please email the CMap support team at:
clue@broadinstitute.org
 
**************
Overall design
**************

LINCS aims to enable a functional understanding of biology by cataloging
changes in gene expression and other cellular processes that occur when cells
are exposed to a variety of perturbing agents. The Broad Institute LINCS Center
for Transcriptomics contributes to this collaborative effort by application of
the Connectivity Map concept. In brief, the study design involves the
generation of a compendium of transcriptional expression data from cultured
human cells treated with small-molecule and genetic loss/gain of function
perturbagens. These measurements are made using the L1000 high-throughput
gene-expression assay that enables data generation at an unprecedented scale.
The data are processed through a computational system, that converts raw
fluorescence intensities into differential gene expression signatures. The data
at each stage of the pre-processing are available: Level 1 (LXB) - raw,
unprocessed flow cytometry data from Luminex scanners. One LXB file is
generated for each well of a 384-well plate, and each file contains a
fluorescence intensity value for every observed analyte in the well.  Level 2
(GEX) - gene expression values per 1,000 genes after deconvolution from Luminex
beads. Level 3 (Q2NORM) - gene expression profiles of both directly measured
landmark transcripts plus inferred genes. Normalized using invariant set
scaling followed by quantile normalization. Level 4 (Z-SCORES) - signatures
with differentially expressed genes computed by robust z-scores for each
profile relative to control (PC relative to plate population as control; VC
relative to vehicle control). Level 5 (SIG) consists of the replicates, usually
3 per treatment, aggregated into a single differential expression vector
derived from the weighted averages of the individual replicates.  Please note
that a description of the latest file, and a table listing the contents of the
'Broad_LINCS_auxiliary_datasets.tar.gz' file are updated in the following
document; ` <https://docs.google.com/document/d/1q2gciWRhVCA%3Ctr%20valign=>`__

***********
Citation(s)
***********

Subramanian A, Narayan R, Corsello SM, Peck DD et al. A Next Generation
Connectivity Map: L1000 Platform and the First 1,000,000 Profiles. Cell 2017
Nov 30;171(6):1437-1452.e17. PMID: `29195078
<https://www.ncbi.nlm.nih.gov/pubmed/29195078>`_

Seçilmiş D, Hillerton T, Morgan D, Tjärnberg A et al. Uncovering cancer gene
regulation by accurate regulatory network inference from uninformative data.
NPJ Syst Biol Appl 2020 Nov 9;6(1):37. PMID: `33168813
<https://www.ncbi.nlm.nih.gov/pubmed/33168813>`_

+------------------------------------------------------------------------+------------+
| **Download family**                                                    | **Format** |
+------------------------------------------------------------------------+------------+
| `SOFT formatted family file(s)                                         | SOFT       |
| <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE90nnn/GSE90063/soft/>`__   |            |
+------------------------------------------------------------------------+------------+
| `MINiML formatted family file(s)                                       | MINiML     |
| <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE90nnn/GSE90063/miniml/>`__ |            |
+------------------------------------------------------------------------+------------+
| `Series Matrix File(s)                                                 | TXT        |
| <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE90nnn/GSE90063/matrix/>`__ |            |
+------------------------------------------------------------------------+------------+

+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| **Supplementary  | **Size** | **Download**                                                                                                                                                    | **File           |
| file**           |          |                                                                                                                                                                 | type/resource**  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92742_Broad_  | 1.2 Tb   | `(ftp)                                                                                                                                                          | TAR              |
| LINCS_Level1_LXB |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5FLevel1%5FLXB%5Fn1403502%2Etar%2Egz>`__                              |                  |
| _n1403502.tar.gz |          | `(http)                                                                                                                                                         |                  |
|                  |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5FLevel1%5FLXB%5Fn1403502%2Etar%2Egz>`__                     |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92742         | 98.9 Mb  | `(ftp)                                                                                                                                                          | GCTX             |
| _Broad_LINCS_Lev |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5FLevel2%5FGEX%5Fdelta%5Fn49216x978%2Egctx%2Egz>`__                   |                  |
| el2_GEX_delta_n4 |          | `(http)                                                                                                                                                         |                  |
| 9216x978.gctx.gz |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5FLevel2%5FGEX%5Fdelta%5Fn49216x978%2Egctx%2Egz>`__          |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92742_Bro     | 2.3 Gb   | `(ftp)                                                                                                                                                          | GCTX             |
| ad_LINCS_Level2_ |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5FLevel2%5FGEX%5Fepsilon%5Fn1269922x978%2Egctx%2Egz>`__               |                  |
| GEX_epsilon_n126 |          | `(http)                                                                                                                                                         |                  |
| 9922x978.gctx.gz |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5FLevel2%5FGEX%5Fepsilon%5Fn1269922x978%2Egctx%2Egz>`__      |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92742_Broa    | 48.8 Gb  | `(ftp)                                                                                                                                                          | GCTX             |
| d_LINCS_Level3_I |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5FLevel3%5FINF%5Fmlr12k%5Fn1319138x12328%2Egctx%2Egz>`__              |                  |
| NF_mlr12k_n13191 |          | `(http)                                                                                                                                                         |                  |
| 38x12328.gctx.gz |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5FLevel3%5FINF%5Fmlr12k%5Fn1319138x12328%2Egctx%2Egz>`__     |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| G                | 49.6 Gb  | `(ftp)                                                                                                                                                          | GCTX             |
| SE92742_Broad_LI |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5FLevel4%5FZSPCINF%5Fmlr12k%5Fn1319138x12328%2Egctx%2Egz>`__          |                  |
| NCS_Level4_ZSPCI |          | `(http)                                                                                                                                                         |                  |
| NF_mlr12k_n13191 |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5FLevel4%5FZSPCINF%5Fmlr12k%5Fn1319138x12328%2Egctx%2Egz>`__ |                  |
| 38x12328.gctx.gz |          |                                                                                                                                                                 |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92742_Bro     | 19.9 Gb  | `(ftp)                                                                                                                                                          | GCTX             |
| ad_LINCS_Level5_ |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5FLevel5%5FCOMPZ%2EMODZ%5Fn473647x12328%2Egctx%2Egz>`__               |                  |
| COMPZ.MODZ_n4736 |          | `(http)                                                                                                                                                         |                  |
| 47x12328.gctx.gz |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5FLevel5%5FCOMPZ%2EMODZ%5Fn473647x12328%2Egctx%2Egz>`__      |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92742_Broad_  | 25.8 Kb  | `(ftp)                                                                                                                                                          | PDF              |
| LINCS_README.pdf |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5FREADME%2Epdf>`__                                                    |                  |
|                  |          | `(http)                                                                                                                                                         |                  |
|                  |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5FREADME%2Epdf>`__                                           |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92742_Broad   | 1.6 Gb   | `(ftp)                                                                                                                                                          | TAR              |
| _LINCS_auxiliary |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5Fauxiliary%5Fdatasets%2Etar%2Egz>`__                                 |                  |
| _datasets.tar.gz |          | `(http)                                                                                                                                                         |                  |
|                  |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5Fauxiliary%5Fdatasets%2Etar%2Egz>`__                        |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92            | 2.5 Kb   | `(ftp)                                                                                                                                                          | TXT              |
| 742_Broad_LINCS_ |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5Fcell%5Finfo%2Etxt%2Egz>`__                                          |                  |
| cell_info.txt.gz |          | `(http)                                                                                                                                                         |                  |
|                  |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5Fcell%5Finfo%2Etxt%2Egz>`__                                 |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92            | 211.6 Kb | `(ftp)                                                                                                                                                          | TXT              |
| 742_Broad_LINCS_ |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5Fgene%5Finfo%2Etxt%2Egz>`__                                          |                  |
| gene_info.txt.gz |          | `(http)                                                                                                                                                         |                  |
|                  |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5Fgene%5Finfo%2Etxt%2Egz>`__                                 |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE9             | 18.3 Kb  | `(ftp)                                                                                                                                                          | TXT              |
| 2742_Broad_LINCS |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5Fgene%5Finfo%5Fdelta%5Flandmark%2Etxt%2Egz>`__                       |                  |
| _gene_info_delta |          | `(http)                                                                                                                                                         |                  |
| _landmark.txt.gz |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5Fgene%5Finfo%5Fdelta%5Flandmark%2Etxt%2Egz>`__              |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92            | 11.5 Mb  | `(ftp)                                                                                                                                                          | TXT              |
| 742_Broad_LINCS_ |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5Finst%5Finfo%2Etxt%2Egz>`__                                          |                  |
| inst_info.txt.gz |          | `(http)                                                                                                                                                         |                  |
|                  |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5Finst%5Finfo%2Etxt%2Egz>`__                                 |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92            | 1.1 Mb   | `(ftp)                                                                                                                                                          | TXT              |
| 742_Broad_LINCS_ |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5Fpert%5Finfo%2Etxt%2Egz>`__                                          |                  |
| pert_info.txt.gz |          | `(http)                                                                                                                                                         |                  |
|                  |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5Fpert%5Finfo%2Etxt%2Egz>`__                                 |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92742         | 908.9 Kb | `(ftp)                                                                                                                                                          | TXT              |
| _Broad_LINCS_per |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5Fpert%5Fmetrics%2Etxt%2Egz>`__                                       |                  |
| t_metrics.txt.gz |          | `(http)                                                                                                                                                         |                  |
|                  |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5Fpert%5Fmetrics%2Etxt%2Egz>`__                              |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE9             | 10.6 Mb  | `(ftp)                                                                                                                                                          | TXT              |
| 2742_Broad_LINCS |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5Fsig%5Finfo%2Etxt%2Egz>`__                                           |                  |
| _sig_info.txt.gz |          | `(http)                                                                                                                                                         |                  |
|                  |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5Fsig%5Finfo%2Etxt%2Egz>`__                                  |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE9274          | 11.9 Mb  | `(ftp)                                                                                                                                                          | TXT              |
| 2_Broad_LINCS_si |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FBroad%5FLINCS%5Fsig%5Fmetrics%2Etxt%2Egz>`__                                        |                  |
| g_metrics.txt.gz |          | `(http)                                                                                                                                                         |                  |
|                  |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FBroad%5FLINCS%5Fsig%5Fmetrics%2Etxt%2Egz>`__                               |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+
| GSE92742_S       | 1.4 Kb   | `(ftp)                                                                                                                                                          | TXT              |
| HA512SUMS.txt.gz |          | <https://ftp.ncbi.nlm.nih.gov/geo/series/GSE92nnn/GSE92742/suppl/GSE92742%5FSHA512SUMS%2Etxt%2Egz>`__                                                           |                  |
|                  |          | `(http)                                                                                                                                                         |                  |
|                  |          | <https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE92742&format=file&file=GSE92742%5FSHA512SUMS%2Etxt%2Egz>`__                                                  |                  |
+------------------+----------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------+

Raw data are available on Series record

Processed data are available on Series record
