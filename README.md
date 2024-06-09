# Energy-Efficient Hierarchical Collaborative Learning over LEO Satellite Constellations

The hierarchical collaborative learning within Low Earth Orbit (LEO) satellite constellations, termed LEO-HCL, is increasingly gaining popularity by integrating intra-orbit Inter-Satellite Links and orbital edge computing to alleviate the latency issues caused by intermittent satellite connectivity in traditional training architectures. 
However, LEO-HCL systems are confronted with a triad of challenges: the variable topology induced by satellite mobility, limited onboard computing and communication resources, and stringent energy constraints. 
In response to these challenges, we propose an energy-efficient training algorithm, \ourapp, which adaptively optimizes both aggregation frequency and model compression ratio within the resource-constrained LEO network. We have conducted a theoretical analysis of model convergence and investigated the relationship between convergence, aggregation frequency, and model compression ratio. 
Building on this, we offer an approximation algorithm that dynamically calculates the optimal aggregation frequency and compression ratio during the training process. 
Extensive simulations have demonstrated that \ourapp\ significantly outperforms existing methods, offering enhanced convergence speed and energy efficiency. 
Compared to prior solutions, FedAAC achieves a 60\% reduction in energy consumption, a 70\% decrease in training time, and a 52\% lower communication overhead.
