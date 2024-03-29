# Test dataset

The folder **`test_dataset_abemus`** contains a ready to use dataset to explore ABEMUS workflow as described in the [Usage](https://github.com/cibiobcg/abemus/wiki/Usage) page of the [Wiki](https://github.com/cibiobcg/abemus/wiki).
Download the **test_dataset_abemus.tar.gz** file, extract with `tar xvzf test_dataset_abemus.tar.gz` and follow steps as reported in the [test_example](https://github.com/cibiobcg/abemus/blob/master/test_example.R).

# Platform-specific Error Models

You can find platform-specific Error Models computed by ABEMUS as described and investigated in the original manuscript (Casiraghi et al. 2019, submitted) at https://bcglab.cibio.unitn.it/abemus_models

|                  ﻿Target                 |  Folder Name | Target Size |      Sequencing     | Institution | n. Controls | Seq. Protocol |           PMID           |
|:---------------------------------------:|:------------:|:-----------:|:-------------------:|:-----------:|:-----------:|:-------------:|:------------------------:|
| Targeted Custom Amplicon Panel AmpliSeq |   AmpliSeq   |    40 kbp   |    IonTorrent PGM   |     ICR     |     113     |       SE      |    25232177, 26537258    |
|    Illumina True Seq Custom Amplicon    |     TSCA     |   106 kbp   |    Illumina MiSeq   |    UNITN    |      3      |       PE      |            --            |
|     Roche NimbleGen SeqCap Exome v3     | Nimble_Exome |    64 Mbp   | Illumina HiSeq 2000 |     WCM     |      40     |       SE      | Beltran et al, submitted |
|   Roche NimbleGen N250 targeted panel   |  Nimble_N250 |   3.2 Mbp   | Illumina HiSeq 2000 |     WCM     |      20     |       PE      |            --            |
|          Agilent HaloPlex Exome         |   Haloplex   |    36 Mbp   | Illumina HiSeq 2000 |     WCM     |      50     |       PE      |         26855148         |
