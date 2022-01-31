# [Re] Process Aware Stealthy Attack Detection on Industrial Control Systems. #17

This is a python implementation of the original work in the paper

Wissam Aoudi, Mikel Iturbe, and Magnus Almgren. 2018. Truth Will Out:
Departure-Based Process-Level Detection of Stealthy Attacks on Control
Systems. In 2018 ACM SIGSAC Conference on Computer and Communications
Security (CCS ’18), October 15–19, 2018, Toronto, ON, Canada. ACM, New
York, NY, USA, 15 pages. https://doi.org/10.1145/3243734.3243781

## Abstract

Although the traditional IT security layer provided to Industrial Control Systems offers a great deal of protection, security managers often overlook the possibility of a potential stealthy attacks at the process level. In the paper, "Truth Will Out: Departure‐Based Process‐Level Detection of Stealthy Attacks on Control Systems" the authors bring out a novel approach to detecting stealthy attacks on the control system through a process‐aware methodology which they call ‐ PASAD. It enables early detection in the subtle variation of process behavior, thus averting strategic adversaries from maliciously manipulating the industrial process within the noise level. The original implementation for the PASAD algorithm was in Matlab. In this replication, I use Python, and popular visualization library, Matplotlib, to obtain the results claimed.

This submission includes a full replication of the first 5 scenarios in the original paper (DA1, DA2, SA1, SA2 and SA3), and does not contain the code for experiments 4 and 5 that end the original paper. The data for this work is, however, included in the code repository, for the reader interested to implement this work themselves.


## Usage

The main code is in the folder "./data + Solutions". The code is released under an MIT License.

Code for each scenario is implemented in Jupyter notebooks, in separate folders containing a notebook alongside the data used to generate the figures discussed in the manuscript.

A requirements.txt file contains the minimum set of packages that were used in the reviewing of this code.
