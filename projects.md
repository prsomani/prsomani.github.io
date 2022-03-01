---
layout: page
title: Projects
---

- **Implemented fault tolerant microservices distributed architecture with Raft for consensus**  
	1. The system consisted of three microservices - front-end, order and catalog server with each server replicated and round robin is employed for load balancing.
    2. The front-end server keeps an in-memory cache which stores recent results from read requests. Push based caching has been used wherein the catalog servers send an
invalidate notification for the item to the cache before updating it in the database.
    3. The application has each server on a docker container than can be easily be downloaded and deployed. For simple state level consensus, primary backup
with fault recovery is used and Raft consensus protocol has been implemented for log level consensus.


- **Implemented HATESPEECH Detection using BERT**  
	1. Employed transfer learning using the  BERT  model  and  fine  tuning  it  for downstream  task  of  hate  speech  detection.
    2. The model achieved 90 % accuracy on Twitter hatespeech test data.
   
- **Implemented DApp for Nim game server on Ethereum Solidity.**

- **Implemented simple blockchain in python that combines the ideas of proof-of-work, transactions, blocks, and blockchains**  
	1. Implemented APIs for different functionalities like validating block and transactions, creating the merkle tree, keeping track of the UTXOs, getting tip of the blochain and so on.
    
- **Wind Turbine Performance monitoring using logistic regression**  
	Prof. Rajesh Wadhvani, NIT Bhopal
	1. Employed monitoring based approach by generating power curves using four parameter and five parameter logistic regression and mahalanobis distance.
    2. Used 24 months training data from Bhopal Energy Center to generate power curve models.
    3. The model gave a 95% accuracy on the test data.
    


- **Implementation of Deep Web Crawler for mining searchable interfaces**  
	Prof. Deepak Tomar, NIT Bhopal
	1. Determined searchable interfaces using complex xpath queries.
    2. Iteratively applied tf-idf  against the content of the parent page and the results rendered from previous search to get  the next set of relevant terms to be searched
    3. Obtained good results on Indian Government research sites like icmr.nic.in and dst.gov.in.
    
<br /> 


