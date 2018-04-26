# HITECS : A UML Profile and Analysis Framework for Hardware-in-the-Loop Testing of Cyber Physical Systems

_**Seung Yeob Shin, Karim Chaouch, Shiva Nejati, Mehrdad Sabetzadeh, Lionel C. Briand, and Frank Zimmer**_

## Abstract

Hardware-in-the-loop (HiL) testing is an important step in the development of cyber physical systems (CPS). This paper proposes a framework to help engineers systematically specify CPS HiL test cases and analyze HiL testing risks. Leveraging the UML pro le mechanism, we develop an executable domain-speci c language, HITECS, for HiL test case specification. HITECS builds on the UML Testing Pro le (UTP) and the UML action language (Alf). Using HITECS, we provide analysis methods to ensure that HiL test cases are well-behaved, and to estimate the execution time of these test cases before the actual HiL testing phase. We apply HITECS to an industrial case study from the satellite domain. Our results show that HITECS helps engineers de ne more complete and e ective well-behavedness assertions for HiL test cases, compared to when these assertions are de ned without systematic guidance; HITECS veri es in practical time that HiL test cases are well-behaved; and HITECS accurately estimates HiL test case execution times.

## Project artifacts

### HITECS specifications
* ./HITECS
  Anonymized HITECS test specifications

### Experiment results
* ./experiments
  The results of the RQ1 and RQ2 experiments

## License

_MIT License_

_Copyright (c) 2018 Seung Yeob Shin, Karim Chaouch, Shiva Nejati, Mehrdad Sabetzadeh, Lionel C. Briand, and Frank Zimmer_

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

