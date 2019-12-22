# P.808 Toolkit
The P.808 Toolkit is a software package that enables users to run speech quality assessment test
in Amazon Mechanical Turk (AMT) crowdsourcing platform, according to the ITU-T Recommendation P.808.

For more information about the ITU-T Rec. P.808 please read:

[ITU-T Recommandation P.808, _Subjective evaluation of speech quality with a crowdsourcing approach._](https://www.itu.int/rec/T-REC-P.808/en) 
Geneva: International Telecommunication Union, 2018.

## Getting Started
* [Preparation](docs/preparation.md)
* [Running the Evaluation on Amazon Mechanical Turk](docs/running_test_mturk.md)
* [Analyzing Data](docs/results.md)


## Troubleshooting
For bug reports and issues with this code, please see the 
[_github issues page_](https://github.com/babaknaderi/hitapp_p808/issues). Please review this page before contacting the authors.


## Contact

Contact Babak Naderi <bnaderi9[at]gmail.com) with any questions.


## Code License
MIT License

Copyright 2019 (c) Microsoft Corporation.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Audio clips License
The datasets are provided under the original terms that Microsoft received such datasets. See below for more information about each dataset.

The datasets used in this project are licensed as follows:

* Following clips are created under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode) license:
    *  `src/P808Template/assets/clips/math/*`
    *  `src/P808Template/assets/clips/sample_hearing_test/*`
    *  `src/trapping/messages/*`
* Following clips are taken from [PTDB-TUG: Pitch Tracking Database from Graz University of Technology](https://www.spsc.tugraz.at/databases-and-tools/ptdb-tug-pitch-tracking-database-from-graz-university-of-technology.html); License: http://opendatacommons.org/licenses/odbl/1.0/ 
    * `src//environment test/script/clips/*`
    * `src/P808Template/assets/clips/signal_level.wav`
* Following clips are created by adding noise to above-mentioned clips; License [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode) ?
    * `src/environment test/script/clips_snr/*`
    * `src/environment test/assets/jnd_noise/*`
    * `src/P808Template/assets/clips/sample_jnd/*`
    * `src/P808Template/assets/clips/sample_speech/*`
    * `src/trapping/source/*`
    * `src/P808Template/assets/clips/sample_tp.wav`
