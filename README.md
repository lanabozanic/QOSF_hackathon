# Quantum Futures Hackathon 2019

This repository is dedicated to the work my team and I had done during the Quantum Futures Hackathon, co-organized by CERN and the Quantum Open Source Foundation (QOSF). This hackathon was such an amazing opportunity. Big thanks to Mark Fingerhuth and Tomas Babej for hosting this incredible event!

With access to Rigetti's quantum simulators, my team recreated a quantum clustering model, and visualizer. The goal of this project was to compare the cluserting algorithms on a quantum computer vs. on a classical one. To do this, we used the Iris dataset, to compare between two different types of Irises (the Setosa and the Versicolor).

### Classical Algorithm

Using the k-means clustering algorithm , we were able to achieve 100% accuracy in clustering 8 data samples in a time of 35.7 ms on a local CPU.

### Quantum Algorithm
By using the max-cut problem, we were able to recreate a quantum clusering algorithm. Using Rigetti's quantum aproximation optimization algorithm (QAOA), we were successfully able to build our clustering model. Although sucessful and achieved 100% accuracy, the model was very inefficent. Compared to the classical approach, the quantum model to *92,000 ms* to cluster the same amout of data.

This shows how far quantum computing has come, but also how much it has yet to go. This emerging technology is just at its beginning, and I hope to do more work with it in the future. 
