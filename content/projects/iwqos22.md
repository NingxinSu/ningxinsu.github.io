+++
title = "How Asynchronous can Federated Learning Be?"
weight = -9
+++

**Ningxin Su**, Baochun Li, University of Toronto,      
*IEEE International Symposium on Quality of Service (IWQoS) 2022*    
[[Paper](/assets/iwqos22.pdf)] [[Slides](/assets/port_slides.pdf)] [[Source Code](https://github.com/TL-System/plato/tree/main/examples/port)]    

As a practical paradigm designed to involve large numbers of edge devices in distributed training of deep learning models, federated learning has witnessed a significant amount of research attention in the recent years. Yet, most existing mechanisms on federated learning assumed either fully synchronous or asynchronous communication strategies between clients and the federated learning server. Existing designs that were partially asynchronous in their communication were simple heuristics, and were evaluated using the number of communication rounds or updates required for convergence, rather than the wall-clock time in practice.

## BibTeX
```
@inproceedings{port_su2022,    
   author = {N. Su and B. Li},      
   journal = {Proc.~Int'l Symposium on Quality of Service (IWQoS)},     
   publisher = {IEEE},                 
   title = {How Asynchronous can Federated Learning Be?},                
   year = {2022},        
}
```