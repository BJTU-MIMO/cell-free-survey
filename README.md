# cell-free-survey

# Must-Reading Papers on User-Centric Cell-Free Massive MIMO (CF mMIMO) Networks
**Definition:** An ultra-dense network with many more APs than UEs, and where the APs are cooperating to serve the UEs through coherent joint transmission and reception, while making use of the physical layer concepts from the cellular mMIMO area.

**Aims:** Include reproducible codes, good papers and a research library.

Contributed by Jiayi Zhang, BJTU, and Shuaifei Chen, BJTU

<!--Supported by IEEE ComSoc ISAC Emerging Technology Inititive (ETI) &  IEEE SPS ISAC Technical Working Group (TWG)-->

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#1-surveys-and-tutorial">1. Surveys and Tutorials</a></td></tr> 
  <!--<tr>
    <td>&emsp;<a href="#11-basic-concept">1.1 Basic Concept</a></td>
    <td>&ensp;<a href="#12-signal-processing">1.2 Signal Processing</a></td>
</tr> 
  <tr>
    <td>&emsp;<a href="#13-communication-and-networking">1.3 Communication and Networking</a></td>
    <td>&emsp;<a href="#14-mobile-computing">1.4 Mobile Computing</a></td>-->
<tr><td colspan="2"><a href="#2-technical-fundamentals-and-performance-analysis">2. Technical Fundamentals and Performance Analysis</a></td></tr>
<tr><td colspan="2"><a href="#3-resource-allocation-and-signal-processing">3. Resource Allocation and Signal Processing</a></td></tr> 
<tr>
    <td>&emsp;<a href="#31-user-access-and-association">3.1 User Access and Association</a></td>
    <td>&ensp;<a href="#32-channel-estimation">3.2 Channel Estimation</a></td>
</tr> 
  <tr>
    <td>&emsp;<a href="#33-combining-and-precoding">3.3 Combining and Precoding</a></td>
    <td>&emsp;<a href="#34-power-control">3.4 Power Control</a></td>
<tr><td colspan="2"><a href="#4-practical-implementation">4. Practical Implementation</a></td></tr>
  <tr>
    <td>&emsp;<a href="#41-fronthaul-limitation">4.1 Fronthaul Limitation</a></td>
    <td>&ensp;<a href="#42-hardware-impairment">4.2 Hardware Impairment</a></td>
</tr> 
    <tr>
    <td>&emsp;<a href="#43-synchronization">4.3 Synchronization</a></td>
</tr> 
   <tr><td colspan="2"><a href="#5-future-research-directions">5. Future Research Directions</a></td></tr> 
<tr>
    <td>&emsp;<a href="#51-multiple-cpu-cooperation">5.1 Multiple CPU Cooperation</a></td>
    <td>&ensp;<a href="#52-synchronization">5.2 Synchronization</a></td>
</tr> 
<tr>
     <td>&emsp;<a href="#53-mobile-edge-computing">5.3 Mobile Edge Computing</a></td>
    <td>&emsp;<a href="#54-enabling-federated-learning">5.4 Enabling Federated Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#55-multi-antenna-ues">5.5 Multi-Antenna UEs</a></td>
    <td>&emsp;<a href="#56-integrated-sensing-and-computing">5.6 Integrated Sensing and Computing</a></td>
</tr>
  <tr>
     <td>&ensp;<a href="#57-novel-channel-prediction">5.7 Novel Channel Prediction</a></td>
</tr>
</table>




## [1. Surveys and Tutorials](#1-surveys-and-tutorials)

1. **Foundations of User-Centric Cell-Free Massive MIMO.** Foundations and Trends® in Signal Processing, 2021. [Book](http://dx.doi.org/10.1561/2000000109).  [Code](https://github.com/emilbjornson/cell-free-book)

   *Ö. T. Demir, E. Björnson, L. Sanguinetti,* 

1. **Ubiquitous Cell-Free Massive MIMO Communications.** EURASIP J. Wireless Commun. and Netw., 2019. [Journal](https://link.springer.com/article/10.1186/s13638-019-1507-0).

    *G. Interdonato, E. Björnson, H. Q. Ngo, P. Frenger, E. G. Larsson*

1. **Cell-Free Massive MIMO: A New Next-Generation Paradigm.** IEEE Access, 2019. [Journal](https://ieeexplore.ieee.org/abstract/document/8768014/).

    *J. Zhang, S. Chen, Y. Lin, J. Zheng, B. Ai, L. Hanzo*

1. **A Survey on User-Centric Cell-Free Massive MIMO Systems.** ArXiv, 2021. [Journal](https://arxiv.org/abs/2104.13667). 

    *S. Chen, J. Zhang, J. Zhang, E. Björnson, B. Ai*

1. **User-centric Cell-free Massive MIMO Networks: A Survey of Opportunities, Challenges and Solutions.** ArXiv, 2021. [Journal](https://arxiv.org/abs/2104.14589)

    *H. A. Ammar, R. Adve, S. Shahbazpanahi, G. Boudreau, K. V. Srinivas*
    

## [2. Fundamental Theory and Performance Analysis](#2)   

1. **Cell-Free Massive MIMO Versus Small Cells.** IEEE TWC, 2017. [Journal](https://ieeexplore.ieee.org/abstract/document/7827017). [Code](https://github.com/hienquocngo/Cell-Free-Massive-MIMO-Versus-Small-Cells)

    *H. Q. Ngo, A. Ashikhmin, H. Yang, E. G. Larsson, T. L. Marzetta*

2. **Precoding and Power Optimization in Cell-Free Massive MIMO Systems.** IEEE TWC, 2017. [Journal](https://ieeexplore.ieee.org/abstract/document/7917284). 

    *E. Nayebi, A. Ashikhmin, T. L. Marzetta, H. Yang, B. D. Rao*
    
3. **On the Total Energy Efficiency of Cell-Free Massive MIMO.** IEEE TGCN, 2018. [Journal](https://ieeexplore.ieee.org/abstract/document/8097026). 

    *H. Q. Ngo, L.-N. Tran, T. Q. Duong, M. Matthaiou, E. G. Larsson*
    
4. **Channel Hardening and Favorable Propagation in Cell-Free Massive MIMO With Stochastic Geometry.** IEEE TCOM, 2018. [Journal](https://ieeexplore.ieee.org/abstract/document/8379438). 

    *Z. Chen, E. Björnson*

1. **Cell-Free versus Cellular Massive MIMO: What Processing is Needed for Cell-Free to Win?** IEEE SPAWC, 2019. [Conference](https://ieeexplore.ieee.org/document/8815488)

   *E. Björnson, L. Sanguinetti*

1. **User-Centric 5G Cellular Networks: Resource Allocation and Comparison With the Cell-Free Massive MIMO Approach.** IEEE TWC, 2019. [Journal](https://ieeexplore.ieee.org/document/8901451)

   *S. Buzzi, C. D’Andrea, A. Zappone, C. D’Elia*

5. **Scalable Cell-Free Massive MIMO Systems.** IEEE TCOM, 2020. [Journal](https://ieeexplore.ieee.org/abstract/document/9064545).  [Code](https://github.com/emilbjornson/scalable-cell-free)

    *E. Björnson, L. Sanguinetti*

6. **Making Cell-Free Massive MIMO Competitive With MMSE Processing and Centralized Implementation.** IEEE TWC, 2020. [Journal](https://ieeexplore.ieee.org/abstract/document/8845768).  [Code](https://github.com/emilbjornson/competitive-cell-free)

    *E. Björnson, L. Sanguinetti*

7. **Performance of Cell-Free Massive MIMO With Rician Fading and Phase Shifts.** IEEE TWC, 2019. [Journal](https://ieeexplore.ieee.org/abstract/document/8809413).  

    *Ö. Özdogan, E. Björnson, , J. Zhang*
    
7. **Spectral Efficiency Analysis of Cell-Free Massive MIMO Systems With Zero-Forcing Detector.** IEEE TWC, 2020. [Journal](https://ieeexplore.ieee.org/abstract/document/8886730).  

    *P. Liu, K. Luo, D. Chen, T. Jiang*


## [3. Resource Allocation and Signal Processing](#3)  

### [3.1 User Access and Association](#3.1)
1. **Cell-Free Massive MIMO: User-Centric Approach.**  IEEE WCL, 2017. [Letter](https://ieeexplore.ieee.org/abstract/document/8000355)

   *S. Buzzi, C. D’Andrea*
   
1. **Structured Massive Access for Scalable Cell-Free Massive MIMO Systems.**  IEEE JSAC, 2021. [Jounral](https://ieeexplore.ieee.org/abstract/document/9174860)

   *S. Chen, J. Zhang, E. Björnson, J. Zhang, B. Ai*

1. **Performance of Assigning Pilot Sequences in Cell Free Massive MIMO under SINR Constraints.** IEEE ICCE, 2018. [Conference](https://ieeexplore.ieee.org/document/8465748)

   *T. K. Nguyen, T. H. Nguyen*

1. **Pilot Allocation and Sum-Rate Analysis in Cell-Free Massive MIMO Systems.** IEEE ICC, 2018. [Conference](https://ieeexplore.ieee.org/document/8422575)

   *R. Sabbagh, C. Pan, J. Wang*

1. **Graph Coloring Based Pilot Assignment for Cell-Free Massive MIMO Systems.** IEEE TVT, 2021 [Jounral](https://ieeexplore.ieee.org/document/9110802)

   *H. Liu, J. Zhang, S. Jin, B. Ai*

1. **Tabu-Search-Based Pilot Assignment for Cell-Free Massive MIMO Systems.** IEEE TVT, 2019 [Journal](https://ieeexplore.ieee.org/document/8914726)

   *H. Liu, J. Zhang, X. Zhang, A. Kurniawan, T. Juhana, B. Ai*

1. **Pilot Assignment in Cell-Free Massive MIMO Based on the Hungarian Algorithm.** IEEE WCL, 2021 [Journal](https://ieeexplore.ieee.org/document/9178782)

   *S. Buzzi, C. D’Andrea, M. Fresia, Y.-P. Zhang, S. Feng*

1. **Random vs Structured Pilot Assignment in Cell-Free Massive MIMO Wireless Networks.** IEEE ICC Workshops, 2018 [Conference](https://ieeexplore.ieee.org/document/8403508)

   *M. Attarifar, A. Abbasfar, A. Lozano*

1. **An Algorithm for Grant-Free Random Access in Cell-Free Massive MIMO.** IEEE SPAWC, 2020. [Conference](https://ieeexplore.ieee.org/document/9154288)

    *U. K. Ganesan, E. Björnson, E. G. Larsson*

1. **Joint Power Allocation and Load Balancing Optimization for Energy-Efficient Cell-Free Massive MIMO Networks.** IEEE TWC, 2020. [Journal](https://ieeexplore.ieee.org/document/9136914)

    *T. Van Chien, E. Björnson, E. G. Larsson*

1. **Access Point Switch ON/OFF Strategies for Green Cell-Free Massive MIMO Networking.** IEEE Access 8, 2020. [Journal](https://ieeexplore.ieee.org/document/8970501)

    *G. Femenias, N. Lassoued, F. Riera-Palou*



### [3.2 Channel Estimation](#3.2)

1. **Performance of cell-free massive MIMO systems with MMSE and LSFD receiversassive MIMO.** IEEE ACSSC, 2016. [Conference](https://ieeexplore.ieee.org/abstract/document/7869024)

   *E. Nayebi, A. Ashikhmin, T. L. Marzetta, B. D. Rao*

1. **Performance of Cell-Free Massive MIMO With Rician Fading and Phase Shifts.** IEEE TWC, 2019. [Journal](https://ieeexplore.ieee.org/abstract/document/8809413).  

   *Ö. Özdogan, E. Björnson, , J. Zhang*

2. **Low-Complexity Polynomial Channel Estimation in Large-Scale MIMO With Arbitrary Statistics.** IEEE JSTSP, 2014. [Journal](https://ieeexplore.ieee.org/document/6783987). 

   *N. Shariati, E. Björnson, M. Bengtsson, M. Debbah* 

3. **Channel Estimation for Cell-Free mmWave Massive MIMO Through Deep Learning.**  IEEE TVT, 2019. [Journal](https://ieeexplore.ieee.org/document/8815888). 

   *Y. Jin, J. Zhang, S. Jin, B. Ai* 

4. **Estimation of Channel State Information (CSI) in Cell-Free Massive MIMO Based on Time of Arrival (ToA).** Wireless Personal Communications, 2020. [Journal](https://link.springer.com/article/10.1007/s11277-020-07450-8). 

   *A. Almamori, S. Mohan* 

5. **Efficient Enhanced K-Means Clustering for Semi-Blind Channel Estimation of Cell-Free Massive MIMO.**  IEEE ICC, 2020. [Conference](https://ieeexplore.ieee.org/document/9148898). 

   *X. Huang, X. Zhu, Y. Jiang, Y. Liu* 

6. **Angle-Based Multipath Estimation and Beamforming for FDD Cell-free Massive MIMO.**  IEEE SPAWC, 2019. [Conference](https://ieeexplore.ieee.org/document/8815420). 

   *A. Abdallah, M. M. Mansour* 


### [3.3 Combining and Precoding](#3.3)

1. **Making Cell-Free Massive MIMO Competitive With MMSE Processing and Centralized Implementation.** IEEE TWC, 2020. [Journal](https://ieeexplore.ieee.org/abstract/document/8845768).  [Code](https://github.com/emilbjornson/competitive-cell-free)

    *E. Björnson, L. Sanguinetti*

1. **Local Partial Zero-Forcing Precoding for Cell-Free Massive MIMO.** IEEE Trans. Wireless Commun, 2021. [Jourrnal](https://ieeexplore.ieee.org/document/9069486)

    *G. Interdonato, M. Karlsson, E. Björnson, E. G. Larsson*

1. **Modified Conjugate Beamforming for Cell-Free Massive MIMO.** IEEE WCL, 2019. [Letter](https://ieeexplore.ieee.org/document/8599043)

    *M. Attarifar, A. Abbasfar, A. Lozano*

1. **Downlink Spectral Efficiency of Cell-Free Massive MIMO with Full-Pilot Zero-Forcing.** IEEE GlobalSIP, 2018. [Conference](https://ieeexplore.ieee.org/abstract/document/8646666)

    *G. Interdonato, M. Karlsson, E. Björnson, E. G. Larsson*

1. **Downlink Training in Cell-Free Massive MIMO: A Blessing in Disguise.** IEEE TWC, 2019. [Journal](https://ieeexplore.ieee.org/document/8799031)

   *G. Interdonato, H. Q. Ngo, P. Frenger, E. G. Larsson*

1. **User-Centric Cell-Free Massive MIMO with Interference Cancellation and Local ZF Downlink Precoding.** IEEE ISWCS, 2018. [Conference](https://ieeexplore.ieee.org/document/8491054)

   *S. Buzzi, C. D’Andrea, C. D’Elia*

1. **Max-Min Optimal Beamforming for Cell-Free Massive MIMO.** , IEEE CL, 2018. [Letter](https://ieeexplore.ieee.org/document/9108198)

   *A. Zhou, J. Wu, E. G. Larsson, P. Fan*
   
1. **Distributed Precoding Design via Over-the-Air Signaling for Cell-Free Massive MIMO.** IEEE TWC, 2021. [Journal](https://ieeexplore.ieee.org/document/9238440)

   *I. Atzeni, B. Gouda, A. Tölli*


### [3.4 Power Control](#3.4)


1. **Uplink Fractional Power Control and Downlink Power Allocation for Cell-Free Networks.**  IEEE WCL, 2020. [Letter](https://ieeexplore.ieee.org/document/8422577)

    *R. Nikbakht, R. Mosayebi, A. Lozano*

1. **Max-Min Power Optimization in Multigroup Multicast Cell-Free Massive MIMO.** IEEE WCNC, 2019. [Conference](https://ieeexplore.ieee.org/document/8885776)

    *Y. Zhang, H. Cao, L. Yang*

1. **Downlink power control in user-centric and cell-free massive MIMO wireless networks.**  IEEE PIMRC, 2017. [Conference](https://ieeexplore.ieee.org/abstract/document/8292293)

    *S. Buzzi, A. Zappone*

1. **Joint Power Control and LSFD for Wireless-Powered Cell-Free Massive MIMO.**  IEEE TWC, 2021. [Journal](https://ieeexplore.ieee.org/document/9258425)

    *Ö. T. Demir, E. Björnson*
    
1. **Mixed Quality of Service in Cell-Free Massive MIMO.**  IEEE. CL, 2018. [Letter](https://ieeexplore.ieee.org/document/8335309)

    *M. Bashar, K. Cumanan, A. G. Burr, H. Q. Ngo, H. V. Poor*

1. **Max–Min Rate of Cell-Free Massive MIMO Uplink With Optimal Uniform Quantization.**  IEEE TCOM, 2019. [Journal](https://ieeexplore.ieee.org/document/8756286)

    *M. Bashar, K. Cumanan, A. G. Burr, H. Q. Ngo, M. Debbah, P. Xiao*

1. **Power Optimization of Cell Free massive MIMO with Zero-forcing Beamforming Technique**  IEEE CICT, 2018. [Conference](https://ieeexplore.ieee.org/document/8722368)

    *S. C. Tripathi, A. Trivedi, S. Rajoria*

1. **Optimal Power Control and Load Balancing for Uplink Cell-Free Multi-User Massive MIMO**  IEEE Access, 2018. [Journal](https://ieeexplore.ieee.org/document/8281464)

    *T. H. Nguyen, T. K. Nguyen, H. D. Han, V. D. Nguyen*

1. **Energy-Efficient Power Control in Cell-Free and User-Centric Massive MIMO at Millimeter Wave.** IEEE TGCN, 2019. [Journal](https://ieeexplore.ieee.org/document/8676377)

    *M. Alonzo, S. Buzzi, A. Zappone, C. D’Elia*

1. **Energy Efficiency of the Cell-Free Massive MIMO Uplink With Optimal Uniform Quantization.** IEEE TGCN, 2019. [Journal](https://ieeexplore.ieee.org/document/8781848)

    *M. Bashar, K. Cumanan, A. G. Burr, H. Q. Ngo, E. G. Larsson, P. Xiao*

1. **Power Allocation in Cell-Free Massive MIMO: A Deep Learning Method**  IEEE Access, 2020. [Journal](https://ieeexplore.ieee.org/document/9086497)
   
    *Y. Zhao, I. G. Niemegeers, S. H. De Groot*
   
1. **Centralized and Distributed Power Allocation for Max-Min Fairness in Cell-Free Massive MIMO**  IEEE ACSSC, 2019. [Conference](https://ieeexplore.ieee.org/document/9048903)

    *S. Chakraborty, E. Björnson, L. Sanguinetti*

1. **Unsupervised-Learning Power Control for Cell-Free Wireless Systems**  IEEE PIMRC, 2019. [Conference](https://ieeexplore.ieee.org/abstract/document/8904394)

    *R. Nikbakht, A. Jonsson, A. Lozano*

1. **Uplink Power Control in Cell-Free Massive MIMO via Deep Learning.** IEEE CAMSAP, 2019. [Conference](https://ieeexplore.ieee.org/document/9022520)

    *C. D’Andrea, A. Zappone, S. Buzzi, M. Debbah*

1. **Towards Optimal Power Control via Ensembling Deep Neural Networks.** IEEE TCOM, 2020. [Journal](https://ieeexplore.ieee.org/document/8922744)

    *F. Liang, C. Shen, W. Yu, F. Wu*


## [4. Practical Implementation](#4)

### [4.1 Fronthaul Limitation](#4.1)

1. **Exploiting Deep Learning in Limited-Fronthaul Cell-Free Massive MIMO Uplink.** IEEE JSAC, 2021. [Journal](https://ieeexplore.ieee.org/document/9110901)

    *M. Bashar, A. Akbari, K. Cumanan, H.-Q. Ngo, A. G. Burr, P. Xiao, M. Debbah, J. Kittler*

1. **On the Performance of Backhaul Constrained Cell-Free Massive MIMO with Linear Receivers.** IEEE ACSSC, 2018. [Conference](https://ieeexplore.ieee.org/document/8645433)

   *M. Bashar, H. Q. Ngo, A. G. Burr, D. Maryopi, K. Cumanan, E. G. Larsson*

1. **Performance Analysis of Cell-Free Massive MIMO System With Limited Fronthaul Capacity and Hardware Impairments.** IEEE TWC, 2019. [Journal](https://ieeexplore.ieee.org/document/8891922)

   *H. Masoumi, M. J. Emadi*

1. **Deep Learning-Aided Finite-Capacity Fronthaul Cell-Free Massive MIMO with Zero Forcing.** IEEE TWC, 2019. [Journal](https://ieeexplore.ieee.org/document/8891922)

   *H. Masoumi, M. J. Emadi*

1. **Fronthaul-Constrained Cell-Free Massive MIMO With Low Resolution ADCs.** IEEE Access, 2020. [Journal](https://ieeexplore.ieee.org/document/9123382)

   *G. Femenias, F. Riera-Palou*

1. **Cell-Free Massive MIMO with Limited Backhaul.** IEEE ICC, 2018. [Conference](https://ieeexplore.ieee.org/document/8422865)

   *M. Bashar, K. Cumanan, A. G. Burr, H. Q. Ngo, M. Debbah*
   
1. **On the Energy Efficiency of Limited-Backhaul Cell-Free Massive MIMO.** IEEE ICC, 2019. [Conference](https://ieeexplore.ieee.org/document/8761134)

   *M. Bashar, K. Cumanan, A. G. Burr, H. Q. Ngo, E. G. Larsson, P. Xiao*
   
1. **Cell-Free Millimeter-Wave Massive MIMO Systems With Limited Fronthaul Capacity.** IEEE Access, 2019. [Journal](https://ieeexplore.ieee.org/document/8678745)

   *G. Femenias, F. Riera-Palou*
   
1. **Cell Free Massive MIMO with Limited Capacity Fronthaul.** Wireless Personal Communications, 2018. [Journal](https://link.springer.com/article/10.1007/s11277-018-6038-1)

   *M. N. Boroujerdi, A. Abbasfar, M. Ghanbari*
   
1. **Expanded Compute-and-Forward for Backhaul-Limited Cell-Free Massive MIMO.** IEEE ICC Workshops, 2019. [Conference](https://ieeexplore.ieee.org/document/8756704)

   *J. Zhang, J. Zhang, J. Zheng, S. Jin, B. Ai*


### [4.2 Hardware Impairment ](#4.2)

1. **Performance Analysis and Power Control of Cell-Free Massive MIMO Systems With Hardware Impairments.** IEEE Access 6, 2018. [Journal](https://ieeexplore.ieee.org/document/8476516)

    *J. Zhang, Y. Wei, E. Björnson, Y. Han, S. Jin*

1. **Efficient Receiver Design for Uplink Cell-Free Massive MIMO With Hardware Impairments.** IEEE TVT, 2020. [Journal](https://ieeexplore.ieee.org/document/9004558)

   *J. Zheng, J. Zhang, L. Zhang, X. Zhang, B. Ai*

1. **Cell-Free Massive MIMO Systems With Low Resolution ADCs.** IEEE TCOM, 2019. [Journal](https://ieeexplore.ieee.org/document/8756265)

   *X. Hu, C. Zhong, X. Chen, W. Xu, H. Lin, Z. Zhang*

1. **Performance Analysis of Cell-Free Massive MIMO System With Limited Fronthaul Capacity and Hardware Impairments.**  IEEE TWC, 2019. [Journal](https://ieeexplore.ieee.org/document/8891922)

   *H. Masoumi, M. J. Emadi*

1. **Secure Communications Over Cell-Free Massive MIMO Networks With Hardware Impairments.**  IEEE SJ, 2019. [Journal](https://ieeexplore.ieee.org/document/8734757)

   *X. Zhang, D. Guo, K. An, B. Zhang*




## [5. Future Research Directions](#5)

### [5.1 Multiple CPU Cooperation](#5.1)

 1. **Scalability Aspects of Cell-Free Massive MIMO.** IEEE ICC, 2019. [Conference](https://ieeexplore.ieee.org/abstract/document/8761828). 

    *G. Interdonato, P. Frenger, E. G. Larsson*

 1. **MMSE-Optimal Sequential Processing for Cell-Free Massive MIMO With Radio Stripes.** ArXiv, 2020. [Journal](https://arxiv.org/abs/2012.13928). 

    *Z. H. Shaik, E. Björnson, E. G. Larsson*


### [5.2 Synchronization ](#5.2)

1. **Implementation of a Cloud-Based Cell-Free Distributed Massive MIMO System.** IEEE CM, 2020. [Magazine](https://ieeexplore.ieee.org/document/9183752)

   *D. Wang, C. Zhang, Y. Du, J. Zhao, M. Jiang, X. You*

1. **AirSync: Enabling Distributed Multiuser MIMO With Full Spatial Multiplexing.** IEEE/ACM Trans. Netw, 2013. [Journal](https://ieeexplore.ieee.org/document/6403902)

   *H. V. Balan, R. Rogalin, A. Michaloliakos, K. Psounis, G. Caire*

### [5.3 Mobile Edge Computing](#5.3)

1. **Edge Computing-Enabled Cell-Free Massive MIMO Systems.** IEEE TWC, 2020. [Journal](https://ieeexplore.ieee.org/document/8974591)

   *S. Mukherjee, J. Lee*

1. **Massive Access in Cell-Free Massive MIMO-Based Internet of Things: Cloud Computing and Edge Computing Paradigm.** IEEE JSAC, 2021. [Journal](https://ieeexplore.ieee.org/document/9174777)

    *M. Ke, Z. Gao, Y. Wu, X. Gao, K.-K. Wong*


### [5.4 Enabling Federated Learning](#5.4)

1. **Cell-Free Massive MIMO for Wireless Federated Learning.** IEEE TWC, 2021. [Journal](https://ieeexplore.ieee.org/document/9124715)

   *T. T. Vu, D. T. Ngo, N. H. Tran, H. Q. Ngo, M. N. Dao, R. H. Middleton*

1. **User Selection Approaches to Mitigate the Straggler Effect for Federated Learning on Cell-Free Massive MIMO Networks** ArXiv, 2021. [Journal](https://arxiv.org/abs/2009.02031)

   *T. T. Vu, D. T. Ngo, H. Q. Ngo, M. N. Dao, N. H. Tran, R. H. Middleton*

### [5.5 Multi-Antenna UEs](#5.5)

1. **Uplink Performance of Cell-Free Massive MIMO Over Spatially Correlated Rician Fading Channels.** IEEE CL, 2021. [Letter](https://ieeexplore.ieee.org/abstract/document/9276421)

   *Z. Wang; J. Zhang, E. Björnson*
   
2. **Downlink Spectral Efficiency of Cell-Free Massive MIMO Systems With Multi-Antenna Users.** IEEE TCOM, 2021. [Journal](https://ieeexplore.ieee.org/document/9079911)

   *T. C. Mai, H. Q. Ngo, T. Q. Duong*


### [5.6 Integrated Sensing and Computing](#5.6)

1. **MU-MIMO Communications With MIMO Radar: From Co-Existence to Joint Transmission.** IEEE TWC, 2018. [Journal](https://ieeexplore.ieee.org/document/8288677)

   *F. Liu, C. Masouros, A. Li, H. Sun, L. Hanzo*

2. **Joint Radar and Communication Design: Applications, State-of-the-Art, and the Road Ahead.** IEEE TWC, 2020. [Journal](https://ieeexplore.ieee.org/document/8999605)

   *F. Liu, C. Masouros, A. P. Petropulu, H. Griffiths, L. Hanzo*


### [5.7 Novel Channel Prediction](#5.7)

1. **Deep Learning for Fading Channel Prediction.** IEEE OJCS, 2020. [Journal](https://ieeexplore.ieee.org/document/9044427)

   *W. Jiang, H. D. Schotten*

1. **Massive MIMO Channel Prediction: Kalman Filtering Vs. Machine Learning.** IEEE TCOM, 2021. [Journal](https://ieeexplore.ieee.org/document/9210016)

   *H. Kim, S. Kim, H. Lee, C. Jang, Y. Choi, J. Choi*

