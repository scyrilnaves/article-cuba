# Repository for CUBA Consensus Protocol

We propose a consortium-based distributed ledger (Blockchain) consensus algorithm overcoming the classical problems of Byzantine Fault Tolerant (BFT) consensus algorithms. The identified issues with respect to Byzantine algorithms are scalability, performance, and attack resilience. These factors inspire us to conceive our novel consensus algorithm CUBA. CUBA expands to Contesting Utilitarian Byzantine Agreement which evaluates and valorizes each consensus action as a Utilitarian metric of the gamified participants in the network. The obtained utilitarian metrics are used as feedback to reorganize the network either for faster performance of the network consensus or for being resilient to the malicious activity noticed. This consensus protocol is designed to sustain or increase the Utilitarian happiness in a Byzantine environment of identified participants for the network's Liveness, Safety, Performance, and Scalability. Evaluation results show an improved throughput, scalability, and malicious resilience in comparison to Proof of Authority protocols like PBFT, IBFT, and QBFT as well as comparable to Clique for consortium Distributed Ledger networks.

# Folder Organization:
## Cuba Result Visualizer
1. Implementation of  Result Statistics Dashboard for CUBA Simulation
## Cuba Simulator
2. Implementation of Blockchain simulator containing networking, tranasaction, consensus, cryptography as well as Contesting Utilitarian Byzantine Agreemnt Protocol.
## Cuba Cloud Deploy
3. Contains the cloud Kubernetes scripts for deploying the CUBA container as well as visualizer.
