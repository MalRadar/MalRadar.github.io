## The MalRadar Dataset

Mobile malware detection has attracted massive research effort in our community. A reliable and up-to-date malware dataset is critical to evaluate the effectiveness of malware detection approaches. Essentially, the malware ground truth should be manually verified by security experts, and their malicious behaviors should be carefully labelled. Although there are several widely-used malware benchmarks in our community (e.g., MalGenome, Drebin, Piggybacking and AMD, etc.), these benchmarks face several limitations including out-of-date, size, coverage, and reliability issues, etc.

We make effort to create MalRadar, a growing and up-to-date Android malware dataset using the most reliable way, i.e., by collecting malware based on the analysis reports of security experts. We have crawled all the mobile security related reports released by ten leading security companies, and used an automated approach to extract and label the useful ones describing new Android malware and containing Indicators of Compromise (IoC) information. We have successfully compiled MalRadar, a dataset that contains 4,534 unique Android malware samples (including both apks and metadata) released from 2014 to April 2021 by the time of this paper, all of which were manually verified by security experts with detailed behavior analysis.


## Access to the dataset

We are happy to share our malware dataset. Our dataset is available on [Zenodo](https://zenodo.org/record/6451769#.Yoir1r1Bxdh). In order to prevent any misuse, we kindly ask you to request access to the dataset via Zenodo stating your identity and research scope. We will then grant you the access.

