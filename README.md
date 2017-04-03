# DPVNE
Distributed and Parallel Virtual Network Embedding


Author: Michael Till Beck <michael.beck@ifi.lmu.de>

http://www.michaeltillbeck.de



## Implementation of the DPVNE algorithm

Title: **Distributed and Scalable Embedding of virtual Networks**

Published in: Journal of Network and Computer Applications, Elsevier

URL: http://www.sciencedirect.com/science/article/pii/S1084804515001393

Authors: Michael Till Beck, Andreas Fischer, Juan-Felipe Botero, Claudia Linnhoff-Popien, Hermann de Meer

Abstract:
> "Abstract Network virtualization is widely regarded as a key technology for the Future Internet, enabling the deployment of new network protocols without changing dissimilar hardware devices. This leads to the problem of mapping virtual demands to physical resources, known as Virtual Network Embedding (VNE). Current \{VNE\} algorithms do not scale with respect to the substrate network size. Therefore, these algorithms are not applicable in large-scale scenarios where virtual networks have to be embedded in a timely manner. This paper discusses DPVNE, a Distributed and Generic \{VNE\} framework: It runs cost-oriented centralized embedding algorithms in a distributed way, spreading workload across the substrate network instead of concentrating it on one single node (as centralized algorithms do). Several state-of-the-art algorithms were evaluated running inside the DPVNE framework. Results show that DPVNE leads to runtime improvements in large-scale scenarios and embedding results are kept comparable."


# Requirements

DPVNE is now part of the ALEVIN simulation framework:

Alevin 2.2 (http://alevin.sf.net/)


# If you like this code, please read and cite

    @article{DPVNEJournal,
        title = {Distributed and scalable embedding of virtual networks},
        journal = {Journal of Network and Computer Applications},
        year = {2015},
        volume={56},
        publisher={Elsevier},
        pages={124--136},
        issn = {1084-8045},
        doi = {http://dx.doi.org/10.1016/j.jnca.2015.06.012},
        url = {http://www.sciencedirect.com/science/article/pii/S1084804515001393},
        author = {Michael Till Beck and Andreas Fischer and Juan-Felipe Botero and Claudia Linnhoff-Popien and Hermann {de Meer}}
    }

    @inproceedings {DPVNE,
        title = {A Distributed, Parallel, and Generic Virtual Network Embedding Framework},
        year = {2013},
        tags = {All4Green, EINS_NoE, ISL_Institute},
        url = {http://www.net.fim.uni-passau.de/pdf/Beck2013a.pdf},
        web_url = {http://www.ieee-icc.org/},
        publisher = {IEEE},
        pages={3471--3475},
        booktitle = {23th IEEE International Conference on Communications (ICC)},
        author = {Michael Till Beck and Juan-Felipe Botero and Andreas Fischer and Hermann {de Meer} and Xavier Hesselbach}
    }
