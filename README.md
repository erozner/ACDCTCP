# ACDCTCP
Source code for AC/DC TCP SIGCOMM 2016 paper.

###### Paper source:
http://ericrozner.com/papers/he2016sigcomm.pdf

###### Installation details:
The source code is set up to work with Open vSwitch v2.3.2 and Linux kernel 3.18.0. Our systems ran Ubuntu. Copy the datapath.c file to the the relevant directory in OVS, change the "BRIDGE_NAME" variable in the code, and compile. Please note this code is a research prototype and we cannot provide extensive support.

###### Bibtex Citation: 
```
@inproceedings{acdc,
 author = {He, Keqiang and Rozner, Eric and Agarwal, Kanak and Gu, Yu (Jason) and Felter, Wes and Carter, John and Akella, Aditya},
 title = {AC/DC TCP: Virtual Congestion Control Enforcement for Datacenter Networks},
 booktitle = {Proceedings of the 2016 ACM SIGCOMM Conference},
 series = {SIGCOMM '16},
 year = {2016},
 isbn = {978-1-4503-4193-6},
 location = {Florianopolis, Brazil},
 pages = {244--257},
 numpages = {14},
 url = {http://doi.acm.org/10.1145/2934872.2934903},
 doi = {10.1145/2934872.2934903},
 acmid = {2934903},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {Congestion Control, Datacenter Networks, Virtualization},
}
```
