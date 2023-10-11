## Kraken 2 / Bracken Refseq indexes

| Collection | Contains |	Date | Archive size (GB) | Index size (GB) | HTTPS URL	| Bracken | Kraken2 |
|:-----------|:--------:|:----:|:-----------------:|:---------------:|:----------:| :--------------:|:--------------:| 
| Viral	     |Refeq viral	| 6/5/2023 |	0.5	| 0.6	| [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_viral_20230605.tar.gz) | Y (6/7/2022	prebuilt only) | Y |
| MinusB	   |Refeq archaea, viral, plasmid, human1, UniVec_Core |6/5/2023	|6.5	|9.4	| [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_minusb_20230605.tar.gz) | Y  (6/7/2022	& 5/17/2021 prebuilt only)  | Y |
| Standard	 |Refeq archaea, bacteria, viral, plasmid, human1, UniVec_Core	| 6/5/2023 | 51 |	67	| [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_standard_20230605.tar.gz)	| Y  (6/7/2022 & 5/17/2021 prebuilt only)  | Y|
| Standard-8 |Standard with DB capped at 8 GB	 | 6/5/2023	 | 5.5 |	7.5	| [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_standard_08gb_20230605.tar.gz)	| N | Y |
| Standard-16|Standard with DB capped at 16 GB |	6/5/2023 | 11	 |  15	| [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_standard_16gb_20230605.tar.gz)	| N | Y |
| PlusPF	   |Standard plus Refeq protozoa & fungi |	6/5/2023	| 55	| 71	| [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_pluspf_20230605.tar.gz)	|Y| Y|
| PlusPF-8	 |PlusPF with DB capped at 8 GB	|6/5/2023	| 5.5	| 7.5	| [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_pluspf_08gb_20230605.tar.gz)	|N|Y|
| PlusPF-16	 |PlusPF with DB capped at 16 GB |	6/5/2023	| 11	| 15 | [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_pluspf_16gb_20230605.tar.gz)	|Y|Y|
| PlusPFP	   |Standard plus Refeq protozoa, fungi & plant	| 6/5/2023	| 108	| 148 |	[tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_pluspfp_20230605.tar.gz)	|N|Y|
| PlusPFP-8	 |PlusPFP with DB capped at 8 GB	| 6/5/2023	| 5.1 |	7.5	| [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_pluspfp_08gb_20230605.tar.gz)	|N|Y|
| PlusPFP-16 |PlusPFP with DB capped at 16 GB	| 6/5/2023	| 10	| 15	| [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_nt_20230502.tar.gz)	|N|Y|
| nt Database|Very large collection, inclusive of GenBank, RefSeq, TPA and PDB	| 5/2/2023 |	360	| 480 |[tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_nt_20230502.tar.gz)	|N|Y|
| EuPathDB462|Eukaryotic pathogen genomes with contaminants removed	| 4/18/2023 |	8.4	| 11	| [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/k2_eupathdb48_20230407.tar.gz)	|N|Y|

## Kraken 2 / Bracken 16s RNA indexes

| Collection      |  latest version | Size (MB)     | HTTPS URL     | Bracken  | Kracken2 |
|:----------------|:-------------:|:-------------:|:---------------:|:----------------:|:----------------:|
| Greengenes      |   13.5        | 73.2          | [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/16S_Greengenes13.5_20200326.tgz)   | N | Y |
| RDP             |   11.5        | 168           | [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/16S_RDP11.5_20200326.tgz)          | N | Y |
| Silva           |   132         | 117           | [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/16S_Silva132_20200326.tgz)         | N | Y |
| Silva           |   138         | 112	          | [tar.gz](https://genome-idx.s3.amazonaws.com/kraken/16S_Silva138_20200326.tgz)         | Y | Y |

Reference URL: https://benlangmead.github.io/aws-indexes/k2

Bracken DBs are formatted as databaseXmers.kmer_distrib: https://github.com/jenniferlu717/Bracken
