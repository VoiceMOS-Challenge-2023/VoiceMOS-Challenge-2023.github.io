## Announcing the VoiceMOS Challenge 2023!

In 2022 we ran [the first edition of the VoiceMOS Challenge](https://voicemos-challenge-2022.github.io), a shared task for Mean Opinion Score prediction of synthesized speech.  22 teams from academia and industry participated, and we had a special session about the challenge at Interspeech.  The main task was MOS prediction for a large-scale, diverse dataset of synthesized speech from text-to-speech and voice conversion systems, and an out-of-domain track focused on MOS prediction for a separate listening test using only a small amount of labeled data.

The 2023 challenge emphasized **real-world and challenging zero-shot out-of-domain MOS prediction** with three tracks for three different voice evaluation scenarios.  In collaboration with this year's [Blizzard Challenge](https://www.synsig.org/index.php/Blizzard_Challenge_2023) and [Singing Voice Conversion Challenge](http://www.vc-challenge.org), we had a **French speech synthesis track** and a **singing voice conversion track.**  Samples from BC and SVCC teams were provided while those challenges' listening tests are still ongoing, and the task was to predict MOS ahead of the true ratings becoming known.  We also had a third **noisy and enhanced speech track** with a leaderboard on CodaLab.  **Unlike in 2022, no MOS-labelled audio data from the target domains was provided.**  This was to reflect a real-world MOS prediction scenario.  Participants were encouraged to develop MOS predictors that are flexible and generalizeable to a wide variety of audio evaluation tasks.  As in 2022, the primary evaluation metrics for MOS prediction focused on **correct ranking** of synthesis systems in each track.  Teams were allowed to participate in any subset of the three tracks.

### The VoiceMOS Challenge 2023 has ended!

Thanks so much to everyone who participated!  The VoiceMOS Challenge 2023 was accepted as a special session at ASRU 2023.

The Track 3 TMHINT-QI(S) test phase data is described here: [A Study on Incorporating Whisper for Robust Speech Assessment](https://arxiv.org/pdf/2309.12766.pdf) by Ryandhimas E. Zezario, Yu-Wen Chen, Szu-Wei Fu, Yu Tsao, Hsin-Min Wang, and Chiou-Shann Fuh.

<!-- More challenge-related publications to be added shortly! -->

### VoiceMOS 2023 Publications

Challenge summary paper: [The VoiceMOS Challenge 2023: Zero-Shot Subjective Speech Quality Prediction for Multiple Domains](https://doi.org/10.1109/ASRU57964.2023.10389763)

[LE-SSL-MOS: Self-Supervised Learning MOS Prediction with Listener Enhancement](https://doi.org/10.1109/ASRU57964.2023.10389788)

[SQAT-LD: SPeech Quality Assessment Transformer Utilizing Listener Dependent Modeling for Zero-Shot Out-of-Domain MOS Prediction](https://doi.org/10.1109/ASRU57964.2023.10389681)



<!-- ### Participate

If you are interested in participating in the challenge, please fill out [this Google form](https://forms.gle/kcLc69Wa4Q97rSNq7).  Same as last year's challenge, there is no fee to participate.  **Please note that this year, we require an institutional email address (e.g., university or company) for team registration.** -->

### Tentative schedule

The tentative schedule for the VoiceMOS challenge is as follows:

* Friday April 28: CodaLab page and noisy/enhanced speech track go live.
* Wednesday May 24: BC and VCC samples released to VoiceMOS participants.
* Wednesday June 14: Predictions for BC and SVCC tracks due.
* Friday June 16: BC and SVCC release their listening test results.
* Friday June 23: VoiceMOS Challenge results for French and Singing tracks announced.
* Friday June 30: System descriptions due.

### Rules

* Registration must be done with an institutional email address (e.g., university or company), not a personal one.
* Participants are required submit a system description after the challenge ends.
* Any **public** dataset may be used to develop your prediction system, and datasets used must be reported in the system description.  Use of proprietary datasets, including collecting your own MOS ratings, is not permitted.
* If you are already participating in BC or SVCC, you are absolutely welcome to participate in the VoiceMOS Challenge as well.  However, it is not permitted to use your own BC or VCC synthesis systems to generate additional audio samples to use for developing your MOS predictor.

### Suggested public datasets

* [Blizzard Challenge 2023 training data and resources](https://zenodo.org/record/7560290#.ZCoqES8Rr0p)
* [Recommended datasets for SVCC](http://vc-challenge.org/rules.html)  (see the section "Special rules on additional datasets")
* [The BVCC Dataset](https://zenodo.org/record/6572573#.ZCorDy8Rr0o)
* [The SOMOS Dataset](https://zenodo.org/record/7119400#.ZCorKy8Rr0o)
* [Data from past Blizzard Challenges](https://www.cstr.ed.ac.uk/projects/blizzard/data.html)  (audio samples overlap with BVCC, but labels are from separate listening tests)
* [Data for the DNS Challenge](https://github.com/microsoft/DNS-Challenge/)

### Open-source MOS predictors:

These were the baseline systems in last year's challenge:
* [SSL-MOS](https://github.com/nii-yamagishilab/mos-finetune-ssl)
* [LDNet](https://github.com/unilight/LDNet)
* [MOSA-Net](https://github.com/dhimasryan/MOSA-Net-Cross-Domain)

<!-- ### Publication opportunities

We are happy to announce that this year's challenge has been accepted as a Challenge Special Session at ASRU 2023!
-->

<!-- Test -->

## Organizers

* Wen-Chin Huang (Nagoya University, Japan)
* Erica Cooper (National Institute of Informatics, Japan)
* Yu Tsao (Academia Sinica, Taiwan)
* Hsin-Min Wang (Academia Sinica, Taiwan)
* Tomoki Toda (Nagoya University, Japan)
* Junichi Yamagishi (National Institute of Informatics, Japan)

