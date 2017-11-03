<h1><center>BiomarkerBenchmark_GSE2109_Colon</center></h1>
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
|	GSM38055	|	2.88366766705882	|	0.55310198125	|	2.28798520777778	|	0.5766371840625	|
|	GSM38061	|	1.57436517764706	|	1.59950003125	|	2.26277430666667	|	0.621868049375	|
|	GSM38074	|	2.58037697294118	|	-0.00589102874999999	|	2.63275796333333	|	0.45848329875	|
|	GSM38075	|	2.13742352764706	|	-0.14214627625	|	2.68426196333333	|	0.477348534375	|

**Columns: 20025 Rows: 248**

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
|	GSM38055	|	Alcohol_Consumption	|	Yes	|
|	GSM38055	|	Days_from_Patient_Diagnosis_to_Excision	|	13	|
|	GSM38055	|	Diagnosis_made_by	|	Colonoscopy	|
|	GSM38055	|	Ethnic_Background	|	Caucasian	|

**Columns: 3 Rows: 4920**

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