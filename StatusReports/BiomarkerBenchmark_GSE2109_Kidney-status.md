<h1><center>BiomarkerBenchmark_GSE2109_Kidney</center></h1>
## Status: Complete
### Testing Directory . . .

#### Results: PASS
---
### Testing file paths:

&#9989;	test_data.tsv exists.

&#9989;	test_metadata.tsv exists.

&#9989;	download.sh exists.

&#9989;	install.sh exists.

&#9989;	parse.sh exists.

&#9989;	cleanup.sh exists.

*Running user code . . .*

&#9989;	data.tsv.gz was created and zipped correctly.

&#9989;	metadata.tsv.gz was created and zipped correctly.

#### Results: PASS
---
### Testing Key Files:

&#9989;	test_data.tsv contains enough unique samples to test

&#9989;	test_data.tsv contains enough test cases (8; min: 8)

&#9989;	test_metadata.tsv contains enough unique samples to test

&#9989;	test_metadata.tsv contains enough test cases (8; min: 8)

#### Results: PASS
---

### First 5 columns and 5 rows of data.tsv.gz:

|	Sample	|	ENSG00000000003	|	ENSG00000000005	|	ENSG00000000419	|	ENSG00000000457	|
|	---	|	---	|	---	|	---	|	---	|
|	GSM46825	|	1.56976304411765	|	-0.04667038875	|	2.10052035	|	0.4140482690625	|
|	GSM46826	|	1.67171784294118	|	-0.01953416375	|	1.89430100444444	|	0.2049952940625	|
|	GSM46847	|	1.672937	|	-0.27605256375	|	1.91097481	|	0.2990809496875	|
|	GSM46858	|	1.15044336235294	|	-0.218941465	|	2.05204581888889	|	0.451392254375	|

**Columns: 20025 Rows: 210**

---
### "data.tsv.gz" Test Cases (from rows in test file). . .

&#9989;	First column of file is titled "Sample"

&#9989;	Row 1: Success

&#9989;	Row 2: Success

&#9989;	Row 3: Success

&#9989;	Row 4: Success

&#9989;	Row 5: Success

&#9989;	Row 6: Success

&#9989;	Row 7: Success

&#9989;	Row 8: Success

#### Results: PASS
---
### First 3 columns and 5 rows of metadata.tsv.gz:

|	Sample	|	Variable	|	Value	|
|	---	|	---	|	---	|
|	GSM46825	|	Alcohol_Consumption	|	No	|
|	GSM46825	|	Clinical_Grade	|	2	|
|	GSM46825	|	Clinical_M	|	0	|
|	GSM46825	|	Clinical_N	|	0	|

**Columns: 3 Rows: 3447**

---
### "metadata.tsv.gz" Test Cases (from rows in test file). . .

&#9989;	First column of file is titled "Sample"

&#9989;	Row 1: Success

&#9989;	Row 2: Success

&#9989;	Row 3: Success

&#9989;	Row 4: Success

&#9989;	Row 5: Success

&#9989;	Row 6: Success

&#9989;	Row 7: Success

&#9989;	Row 8: Success

#### Results: PASS
---
### Comparing samples in both files . . .

#### Results: PASS

---
### Testing Directory after cleanup . . .

#### Results: PASS
---