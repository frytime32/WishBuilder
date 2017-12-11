<h1><center>BiomarkerBenchmark_GSE2109_Uterus</center></h1>
<h2><center> Status: In Progress </center></h2>


### Testing Directory . . .

#### Results: PASS
---
### Testing Configuration File . . .

&#9989;	config.yaml contains all necessary configurations.

&#9989;	Title is less than 100 characters

&#9989;	description.md contains a description.

#### Results: PASS
---
### Running Install . . .

Executing install.sh: Success

#### Results: PASS
---

### Testing file paths:

&#9989;	test_data.tsv exists.

&#9989;	test_metadata.tsv exists.

&#9989;	download.sh exists.

&#9989;	install.sh exists.

&#9989;	parse.sh exists.

&#9989;	cleanup.sh exists.

&#9989;	description.md exists.

&#9989;	config.yaml exists.

*Running user code . . .*

Executing download.sh: 

&#10060;	download.sh returned an error:
~~~bash
--2017-12-11 21:16:13--  https://osf.io/g6thp/download
Resolving osf.io (osf.io)... 35.190.84.173
Connecting to osf.io (osf.io)|35.190.84.173|:443... connected.
HTTP request sent, awaiting response... 302 FOUND
Location: https://files.osf.io/v1/resources/ssk3t/providers/osfstorage/5992193d9ad5a10275e176cf?action=download&version=1&direct [following]
--2017-12-11 21:16:13--  https://files.osf.io/v1/resources/ssk3t/providers/osfstorage/5992193d9ad5a10275e176cf?action=download&version=1&direct
Resolving files.osf.io (files.osf.io)... 104.239.182.178
Connecting to files.osf.io (files.osf.io)|104.239.182.178|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 14349694 (14M) [application/octet-stream]
Saving to: 'tmp/Expression.gz'

     0K .......... .......... .......... .......... ..........  0%  314K 44s
    50K .......... .......... .......... .......... ..........  0%  319K 44s
   100K .......... .......... .......... .......... ..........  1%  638K 36s
   150K .......... .......... .......... .......... ..........  1%  426K 35s
   200K .......... .......... .......... .......... ..........  1% 1.23M 30s
   250K .......... .......... .......... .......... ..........  2%  641K 29s
   300K .......... .......... .......... .......... ..........  2%  639K 28s
   350K .......... .......... .......... .......... ..........  2%  642K 27s
   400K .......... .......... .......... .......... ..........  3%  641K 26s
   450K .......... .......... .......... .......... ..........  3%  139M 23s
   500K .......... .......... .......... .......... ..........  3% 1.25M 22s
   550K .......... .......... .......... .......... ..........  4% 1.24M 21s
   600K .......... .......... .......... .......... ..........  4%  130M 19s
   650K .......... .......... .......... .......... ..........  4%  646K 19s
   700K .......... .......... .......... .......... ..........  5%  111M 18s
   750K .......... .......... .......... .......... ..........  5% 1.26M 17s
   800K .......... .......... .......... .......... ..........  6% 1.26M 17s
   850K .......... .......... .......... .......... ..........  6% 62.7M 16s
   900K .......... .......... .......... .......... ..........  6% 1.26M 16s
   950K .......... .......... .......... .......... ..........  7% 1.26M 15s
  1000K .......... .......... .......... .......... ..........  7% 56.4M 15s
  1050K .......... .......... .......... .......... ..........  7%  110M 14s
  1100K .......... .......... .......... .......... ..........  8% 1.28M 14s
  1150K .......... .......... .......... .......... ..........  8% 1.26M 13s
  1200K .......... .......... .......... .......... ..........  8% 61.0M 13s
  1250K .......... .......... .......... .......... ..........  9%  130M 12s
  1300K .......... .......... .......... .......... ..........  9% 1.27M 12s
  1350K .......... .......... .......... .......... ..........  9%  112M 12s
  1400K .......... .......... .......... .......... .......... 10% 1.25M 12s
  1450K .......... .......... .......... .......... .......... 10% 44.4M 11s
  1500K .......... .......... .......... .......... .......... 11% 1.31M 11s
  1550K .......... .......... .......... .......... .......... 11% 96.2M 11s
  1600K .......... .......... .......... .......... .......... 11%  106M 10s
  1650K .......... .......... .......... .......... .......... 12% 1.25M 10s
  1700K .......... .......... .......... .......... .......... 12%  117M 10s
  1750K .......... .......... .......... .......... .......... 12% 52.6M 10s
  1800K .......... .......... .......... .......... .......... 13%  126M 9s
  1850K .......... .......... .......... .......... .......... 13% 1.33M 9s
  1900K .......... .......... .......... .......... .......... 13% 90.4M 9s
  1950K .......... .......... .......... .......... .......... 14% 1.25M 9s
  2000K .......... .......... .......... .......... .......... 14%  124M 9s
  2050K .......... .......... .......... .......... .......... 14%  125M 8s
  2100K .......... .......... .......... .......... .......... 15% 60.0M 8s
  2150K .......... .......... .......... .......... .......... 15% 1.33M 8s
  2200K .......... .......... .......... .......... .......... 16% 55.2M 8s
  2250K .......... .......... .......... .......... .......... 16%  115M 8s
  2300K .......... .......... .......... .......... .......... 16% 1.28M 8s
  2350K .......... .......... .......... .......... .......... 17% 26.8M 8s
  2400K .......... .......... .......... .......... .......... 17% 97.9M 7s
  2450K .......... .......... .......... .......... .......... 17%  124M 7s
  2500K .......... .......... .......... .......... .......... 18%  114M 7s
  2550K .......... .......... .......... .......... .......... 18% 1.36M 7s
  2600K .......... .......... .......... .......... .......... 18% 73.0M 7s
  2650K .......... .......... .......... .......... .......... 19%  115M 7s
  2700K .......... .......... .......... .......... .......... 19% 1.29M 7s
  2750K .......... .......... .......... .......... .......... 19% 31.1M 7s
  2800K .......... .......... .......... .......... .......... 20% 90.5M 6s
  2850K .......... .......... .......... .......... .......... 20%  102M 6s
  2900K .......... .......... .......... .......... .......... 21%  122M 6s
  2950K .......... .......... .......... .......... .......... 21% 94.8M 6s
  3000K .......... .......... .......... .......... .......... 21% 1.37M 6s
  3050K .......... .......... .......... .......... .......... 22% 72.9M 6s
  3100K .......... .......... .......... .......... .......... 22% 87.5M 6s
  3150K .......... .......... .......... .......... .......... 22%  110M 6s
  3200K .......... .......... .......... .......... .......... 23% 1.26M 6s
  3250K .......... .......... .......... .......... .......... 23% 69.2M 6s
  3300K .......... .......... .......... .......... .......... 23%  104M 5s
  3350K .......... .......... .......... .......... .......... 24%  120M 5s
  3400K .......... .......... .......... .......... .......... 24%  117M 5s
  3450K .......... .......... .......... .......... .......... 24% 91.0M 5s
  3500K .......... .......... .......... .......... .......... 25% 1.40M 5s
  3550K .......... .......... .......... .......... .......... 25% 46.3M 5s
  3600K .......... .......... .......... .......... .......... 26% 89.1M 5s
  3650K .......... .......... .......... .......... .......... 26%  119M 5s
  3700K .......... .......... .......... .......... .......... 26% 1.31M 5s
  3750K .......... .......... .......... .......... .......... 27% 35.5M 5s
  3800K .......... .......... .......... .......... .......... 27% 88.8M 5s
  3850K .......... .......... .......... .......... .......... 27% 59.8M 5s
  3900K .......... .......... .......... .......... .......... 28% 94.3M 5s
  3950K .......... .......... .......... .......... .......... 28%  132M 5s
  4000K .......... .......... .......... .......... .......... 28% 98.0M 4s
  4050K .......... .......... .......... .......... .......... 29% 1.42M 4s
  4100K .......... .......... .......... .......... .......... 29%  101M 4s
  4150K .......... .......... .......... .......... .......... 29% 39.1M 4s
  4200K .......... .......... .......... .......... .......... 30% 78.3M 4s
  4250K .......... .......... .......... .......... .......... 30% 1.31M 4s
  4300K .......... .......... .......... .......... .......... 31% 35.0M 4s
  4350K .......... .......... .......... .......... .......... 31%  128M 4s
  4400K .......... .......... .......... .......... .......... 31% 97.9M 4s
  4450K .......... .......... .......... .......... .......... 32% 57.7M 4s
  4500K .......... .......... .......... .......... .......... 32%  150M 4s
  4550K .......... .......... .......... .......... .......... 32%  121M 4s
  4600K .......... .......... .......... .......... .......... 33%  103M 4s
  4650K .......... .......... .......... .......... .......... 33% 95.2M 4s
  4700K .......... .......... .......... .......... .......... 33% 1.44M 4s
  4750K .......... .......... .......... .......... .......... 34% 53.5M 4s
  4800K .......... .......... .......... .......... .......... 34% 67.0M 4s
  4850K .......... .......... .......... .......... .......... 34%  124M 4s
  4900K .......... .......... .......... .......... .......... 35% 90.5M 4s
  4950K .......... .......... .......... .......... .......... 35% 1.33M 4s
  5000K .......... .......... .......... .......... .......... 36% 28.8M 3s
  5050K .......... .......... .......... .......... .......... 36%  127M 3s
  5100K .......... .......... .......... .......... .......... 36%  122M 3s
  5150K .......... .......... .......... .......... .......... 37% 69.6M 3s
  5200K .......... .......... .......... .......... .......... 37%  113M 3s
  5250K .......... .......... .......... .......... .......... 37% 89.4M 3s
  5300K .......... .......... .......... .......... .......... 38% 62.1M 3s
  5350K .......... .......... .......... .......... .......... 38% 99.3M 3s
  5400K .......... .......... .......... .......... .......... 38% 99.1M 3s
  5450K .......... .......... .......... .......... .......... 39% 1.49M 3s
  5500K .......... .......... .......... .......... .......... 39%  134M 3s
  5550K .......... .......... .......... .......... .......... 39% 50.3M 3s
  5600K .......... .......... .......... .......... .......... 40% 72.7M 3s
  5650K .......... .......... .......... .......... .......... 40% 99.8M 3s
  5700K .......... .......... .......... .......... .......... 41%  122M 3s
  5750K .......... .......... .......... .......... .......... 41%  105M 3s
  5800K .......... .......... .......... .......... .......... 41% 1.34M 3s
  5850K .......... .......... .......... .......... .......... 42% 28.7M 3s
  5900K .......... .......... .......... .......... .......... 42%  117M 3s
  5950K .......... .......... .......... .......... .......... 42%  147M 3s
  6000K .......... .......... .......... .......... .......... 43% 78.5M 3s
  6050K .......... .......... .......... .......... .......... 43%  120M 3s
  6100K .......... .......... .......... .......... .......... 43% 95.3M 3s
  6150K .......... .......... .......... .......... .......... 44%  133M 3s
  6200K .......... .......... .......... .......... .......... 44%  111M 3s
  6250K .......... .......... .......... .......... .......... 44% 98.1M 3s
  6300K .......... .......... .......... .......... .......... 45%  101M 2s
  6350K .......... .......... .......... .......... .......... 45% 1.50M 2s
  6400K .......... .......... .......... .......... .......... 46% 40.5M 2s
  6450K .......... .......... .......... .......... .......... 46%  105M 2s
  6500K .......... .......... .......... .......... .......... 46%  137M 2s
  6550K .......... .......... .......... .......... .......... 47% 79.4M 2s
  6600K .......... .......... .......... .......... .......... 47%  116M 2s
  6650K .......... .......... .......... .......... .......... 47%  121M 2s
  6700K .......... .......... .......... .......... .......... 48% 1.35M 2s
  6750K .......... .......... .......... .......... .......... 48% 25.9M 2s
  6800K .......... .......... .......... .......... .......... 48%  100M 2s
  6850K .......... .......... .......... .......... .......... 49%  113M 2s
  6900K .......... .......... .......... .......... .......... 49%  103M 2s
  6950K .......... .......... .......... .......... .......... 49%  118M 2s
  7000K .......... .......... .......... .......... .......... 50% 99.0M 2s
  7050K .......... .......... .......... .......... .......... 50%  128M 2s
  7100K .......... .......... .......... .......... .......... 51%  100M 2s
  7150K .......... .......... .......... .......... .......... 51%  132M 2s
  7200K .......... .......... .......... .......... .......... 51% 89.8M 2s
  7250K .......... .......... .......... .......... .......... 52%  121M 2s
  7300K .......... .......... .......... .......... .......... 52% 7.13M 2s
  7350K .......... .......... .......... .......... .......... 52% 1.85M 2s
  7400K .......... .......... .......... .......... .......... 53%  117M 2s
  7450K .......... .......... .......... .......... .......... 53%  100M 2s
  7500K .......... .......... .......... .......... .......... 53%  119M 2s
  7550K .......... .......... .......... .......... .......... 54%  112M 2s
  7600K .......... .......... .......... .......... .......... 54% 99.6M 2s
  7650K .......... .......... .......... .......... .......... 54%  111M 2s
  7700K .......... .......... .......... .......... .......... 55% 1.36M 2s
  7750K .......... .......... .......... .......... .......... 55% 24.7M 2s
  7800K .......... .......... .......... .......... .......... 56%  103M 2s
  7850K .......... .......... .......... .......... .......... 56%  124M 2s
  7900K .......... .......... .......... .......... .......... 56%  117M 2s
  7950K .......... .......... .......... .......... .......... 57% 96.9M 2s
  8000K .......... .......... .......... .......... .......... 57%  108M 2s
  8050K .......... .......... .......... .......... .......... 57%  108M 2s
  8100K .......... .......... .......... .......... .......... 58%  119M 2s
  8150K .......... .......... .......... .......... .......... 58%  107M 2s
  8200K .......... .......... .......... .......... .......... 58%  100M 2s
  8250K .......... .......... .......... .......... .......... 59%  138M 2s
  8300K .......... .......... .......... .......... .......... 59%  120M 1s
  8350K .......... .......... .......... .......... .......... 59%  102M 1s
  8400K .......... .......... .......... .......... .......... 60% 7.51M 1s
  8450K .......... .......... .......... .......... .......... 60% 1.86M 1s
  8500K .......... .......... .......... .......... .......... 61%  108M 1s
  8550K .......... .......... .......... .......... .......... 61%  117M 1s
  8600K .......... .......... .......... .......... .......... 61%  108M 1s
  8650K .......... .......... .......... .......... .......... 62%  125M 1s
  8700K .......... .......... .......... .......... .......... 62%  108M 1s
  8750K .......... .......... .......... .......... .......... 62% 87.0M 1s
  8800K .......... .......... .......... .......... .......... 63%  125M 1s
  8850K .......... .......... .......... .......... .......... 63% 1.38M 1s
  8900K .......... .......... .......... .......... .......... 63% 25.3M 1s
  8950K .......... .......... .......... .......... .......... 64%  116M 1s
  9000K .......... .......... .......... .......... .......... 64%  121M 1s
  9050K .......... .......... .......... .......... .......... 64%  109M 1s
  9100K .......... .......... .......... .......... .......... 65%  131M 1s
  9150K .......... .......... .......... .......... .......... 65% 88.8M 1s
  9200K .......... .......... .......... .......... .......... 66%  114M 1s
  9250K .......... .......... .......... .......... .......... 66%  104M 1s
  9300K .......... .......... .......... .......... .......... 66%  120M 1s
  9350K .......... .......... .......... .......... .......... 67%  124M 1s
  9400K .......... .......... .......... .......... .......... 67% 92.4M 1s
  9450K .......... .......... .......... .......... .......... 67%  122M 1s
  9500K .......... .......... .......... .......... .......... 68%  115M 1s
  9550K .......... .......... .......... .......... .......... 68%  111M 1s
  9600K .......... .......... .......... .......... .......... 68% 90.1M 1s
  9650K .......... .......... .......... .......... .......... 69% 9.06M 1s
  9700K .......... .......... .......... .......... .......... 69% 7.87M 1s
  9750K .......... .......... .......... .......... .......... 69% 2.42M 1s
  9800K .......... .......... .......... .......... .......... 70% 92.7M 1s
  9850K .......... .......... .......... .......... .......... 70%  104M 1s
  9900K .......... .......... .......... .......... .......... 71%  118M 1s
  9950K .......... .......... .......... .......... .......... 71% 94.1M 1s
 10000K .......... .......... .......... .......... .......... 71%  111M 1s
 10050K .......... .......... .......... .......... .......... 72%  114M 1s
 10100K .......... .......... .......... .......... .......... 72%  114M 1s
 10150K .......... .......... .......... .......... .......... 72% 1.40M 1s
 10200K .......... .......... .......... .......... .......... 73% 27.0M 1s
 10250K .......... .......... .......... .......... .......... 73%  106M 1s
 10300K .......... .......... .......... .......... .......... 73%  114M 1s
 10350K .......... .......... .......... .......... .......... 74%  111M 1s
 10400K .......... .......... .......... .......... .......... 74% 81.6M 1s
 10450K .......... .......... .......... .......... .......... 74%  143M 1s
 10500K .......... .......... .......... .......... .......... 75%  111M 1s
 10550K .......... .......... .......... .......... .......... 75%  123M 1s
 10600K .......... .......... .......... .......... .......... 75%  113M 1s
 10650K .......... .......... .......... .......... .......... 76%  119M 1s
 10700K .......... .......... .......... .......... .......... 76%  134M 1s
 10750K .......... .......... .......... .......... .......... 77%  118M 1s
 10800K .......... .......... .......... .......... .......... 77% 88.3M 1s
 10850K .......... .......... .......... .......... .......... 77%  108M 1s
 10900K .......... .......... .......... .......... .......... 78%  122M 1s
 10950K .......... .......... .......... .......... .......... 78%  103M 1s
 11000K .......... .......... .......... .......... .......... 78%  112M 1s
 11050K .......... .......... .......... .......... .......... 79% 10.5M 1s
 11100K .......... .......... .......... .......... .......... 79% 7.70M 1s
 11150K .......... .......... .......... .......... .......... 79%  130M 1s
 11200K .......... .......... .......... .......... .......... 80% 2.42M 1s
 11250K .......... .......... .......... .......... .......... 80%  114M 1s
 11300K .......... .......... .......... .......... .......... 80%  103M 1s
 11350K .......... .......... .......... .......... .......... 81%  131M 1s
 11400K .......... .......... .......... .......... .......... 81%  103M 1s
 11450K .......... .......... .......... .......... .......... 82%  114M 1s
 11500K .......... .......... .......... .......... .......... 82%  127M 1s
 11550K .......... .......... .......... .......... .......... 82%  102M 0s
 11600K .......... .......... .......... .......... .......... 83%  103M 0s
 11650K .......... .......... .......... .......... .......... 83%  119M 0s
 11700K .......... .......... .......... .......... .......... 83% 1.43M 0s
 11750K .......... .......... .......... .......... .......... 84% 25.6M 0s
 11800K .......... .......... .......... .......... .......... 84% 98.1M 0s
 11850K .......... .......... .......... .......... .......... 84%  113M 0s
 11900K .......... .......... .......... .......... .......... 85% 98.7M 0s
 11950K .......... .......... .......... .......... .......... 85%  128M 0s
 12000K .......... .......... .......... .......... .......... 85% 98.9M 0s
 12050K .......... .......... .......... .......... .......... 86%  119M 0s
 12100K .......... .......... .......... .......... .......... 86%  120M 0s
 12150K .......... .......... .......... .......... .......... 87%  117M 0s
 12200K .......... .......... .......... .......... .......... 87%  112M 0s
 12250K .......... .......... .......... .......... .......... 87%  108M 0s
 12300K .......... .......... .......... .......... .......... 88%  139M 0s
 12350K .......... .......... .......... .......... .......... 88%  105M 0s
 12400K .......... .......... .......... .......... .......... 88% 92.7M 0s
 12450K .......... .......... .......... .......... .......... 89%  119M 0s
 12500K .......... .......... .......... .......... .......... 89%  111M 0s
 12550K .......... .......... .......... .......... .......... 89% 80.9M 0s
 12600K .......... .......... .......... .......... .......... 90%  111M 0s
 12650K .......... .......... .......... .......... .......... 90% 13.4M 0s
 12700K .......... .......... .......... .......... .......... 90% 7.72M 0s
 12750K .......... .......... .......... .......... .......... 91%  123M 0s
 12800K .......... .......... .......... .......... .......... 91% 8.17M 0s
 12850K .......... .......... .......... .......... .......... 92% 3.41M 0s
 12900K .......... .......... .......... .......... .......... 92% 97.1M 0s
 12950K .......... .......... .......... .......... .......... 92%  119M 0s
 13000K .......... .......... .......... .......... .......... 93%  103M 0s
 13050K .......... .......... .......... .......... .......... 93%  113M 0s
 13100K .......... .......... .......... .......... .......... 93%  118M 0s
 13150K .......... .......... .......... .......... .......... 94%  121M 0s
 13200K .......... .......... .......... .......... .......... 94% 81.1M 0s
 13250K .......... .......... .......... .......... .......... 94%  139M 0s
 13300K .......... .......... .......... .......... .......... 95%  119M 0s
 13350K .......... .......... .......... .......... .......... 95%  118M 0s
 13400K .......... .......... .......... .......... .......... 95% 1.47M 0s
 13450K .......... .......... .......... .......... .......... 96% 23.4M 0s
 13500K .......... .......... .......... .......... .......... 96% 94.5M 0s
 13550K .......... .......... .......... .......... .......... 97% 86.5M 0s
 13600K .......... .......... .......... .......... .......... 97% 82.2M 0s
 13650K .......... .......... .......... .......... .......... 97%  108M 0s
 13700K .......... .......... .......... .......... .......... 98%  121M 0s
 13750K .......... .......... .......... .......... .......... 98%  118M 0s
 13800K .......... .......... .......... .......... .......... 98%  113M 0s
 13850K .......... .......... .......... .......... .......... 99%  119M 0s
 13900K .......... .......... .......... .......... .......... 99%  107M 0s
 13950K .......... .......... .......... .......... .......... 99%  120M 0s
 14000K .......... ...                                        100%  102M=2.5s

2017-12-11 21:16:17 (5.45 MB/s) - 'tmp/Expression.gz' saved [14349694/14349694]

--2017-12-11 21:16:18--  https://osf.io/m6gve/download
Resolving osf.io (osf.io)... 35.190.84.173
Connecting to osf.io (osf.io)|35.190.84.173|:443... connected.
HTTP request sent, awaiting response... 404 NOT FOUND
2017-12-11 21:16:18 ERROR 404: NOT FOUND.
~~~
