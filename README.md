# Within- and between-host efficacy of neuraminidase inhibitors against influenza infection

This repository is provided as a companion to the paper [title], which can be obtained from [bioRxiv](biorxiv), and which we also provide here for completeness.

We explore the effects of therapy with NAIs using the within-host model of influenza by [Lukens *et al.* (2014)](https://bmcpublichealth.biomedcentral.com/articles/10.1186/1471-2458-14-1019), which includes symptoms, and which we expand with a simple description of the antiviral drug. The system is given by

<p align="center"><img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/998088932b9f94fb40bfbdd6c6fb9706.svg?invert_in_darkmode" align=middle width=81.88917pt height=18.330015pt/></p>

<p align="center"><img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/67eabbd2d66fa577a89265e1a40229b2.svg?invert_in_darkmode" align=middle width=107.77371pt height=18.330015pt/></p>

<p align="center"><img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/fc91c6a0a8f3a98c88f69ddcd3c53b88.svg?invert_in_darkmode" align=middle width=86.7405pt height=16.50363pt/></p>

<p align="center"><img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/4fe0b125350f9f28bc0b9437f077469f.svg?invert_in_darkmode" align=middle width=227.2446pt height=39.45249pt/></p>

<p align="center"><img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/b1baa4de64863a8543547b341bfefb37.svg?invert_in_darkmode" align=middle width=92.95836pt height=16.50363pt/></p>

<p align="center"><img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/c5f0ebb2cdd8e62ea5f58ccc670f76ea.svg?invert_in_darkmode" align=middle width=59.47392pt height=18.330015pt/></p>

where <img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/2f118ee06d05f3c2d98361d9c30e38ce.svg?invert_in_darkmode" align=middle width=11.889405pt height=22.46574pt/> are susceptible target cells, <img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/8eb543f68dac24748e65e2e4c5fc968c.svg?invert_in_darkmode" align=middle width=10.696455pt height=22.46574pt/> infected cells, <img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/21fd4e8eecd6bdf1a4d3d6bd1fb8d733.svg?invert_in_darkmode" align=middle width=8.51598pt height=22.46574pt/> productively infected cells, <img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/a9a3a4a202d80326bda413b5562d5cd1.svg?invert_in_darkmode" align=middle width=13.242075pt height=22.46574pt/> the viral load, <img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/535b15667b86f1b118010d4c218fecb9.svg?invert_in_darkmode" align=middle width=12.78552pt height=22.46574pt/> the symptoms intensity and <img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/78ec2b7008296ce0561cf83393cb746d.svg?invert_in_darkmode" align=middle width=14.06625pt height=22.46574pt/> the drug concentration.

This simplified by considering a *best-case scenario*, in which the drug stays at a constant concentration given by the peak <img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/1ee3252ffc26342ad92c9009179dbca7.svg?invert_in_darkmode" align=middle width=21.381855pt height=22.46574pt/> at which it quickly converges, resulting in a constant efficacy <img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/214137ef71f6ae5ef408da351260bf63.svg?invert_in_darkmode" align=middle width=14.400705pt height=22.63866pt/>, as shown below (<img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/02ab12d0013b89c8edc7f0f2662fa7a9.svg?invert_in_darkmode" align=middle width=10.58706pt height=20.22207pt/> corresponds to the time of the <img src="https://rawgit.com/cparrarojas/neuraminidase-inhibitors/master/eqs/5cd92f0b94ff48a41ce46f35769fb579.svg?invert_in_darkmode" align=middle width=46.759185pt height=24.6576pt/>-th drug intake).

<p align="center"><img src="./figures/D_eps.png" alt="constant efficacy" style="width: 500px;"/></p>

Using this constant-efficacy within-host model, we explore the impact of treatment as a function of the efficacy and time of initiation post-infection.

Focusing on the prophylactic scenario, we further assess the effectiveness of NAIs in containing an epidemic in a given population, considering the drug coverage and availability/cost.

Our results suggest that the use of NAIs is unwarranted in practical treatment settings, while its large cost-effectiveness ratio cast doubts on their prophylactic use.

The following directories are part of this repository:
- `docs` contains a copy of the paper.
- `code` contains the source code necessary to reproduce our results, along with further details on its implementation.
- `data` contains the data employed for the epidemic simulation.
- `figures` contains all images appearing in the paper, plus additional outputs from the code.
- `eqs` simply contains renderings of the LaTeX equations shown in this page.
