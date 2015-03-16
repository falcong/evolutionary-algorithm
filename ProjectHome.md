The package serves as a foundation class library, supporting the implementation many variants of Evolutionary Algorithms, currently including Genetic Algorithm (GA), Particle Swarm Optimization (PSO), Memetic Algorithm (MA), Evolution Strategy (ES).

Highlighted features

· Support both binary & real-coded string representations of solution

· Operator-based design for flexibility

· EA Operators: Selection, Crossover, Mutation, Move operators in PSO & and the adaptive scheme in EA

· Individual learning: Davidon–Fletcher–Powell (DFP) and Davies, Swann, and Campey with Gram-Schmidt orthogonalization (DSCG) strategies and Random Mutation Hill-climbing (RMHC)

In addition, algorithm pipeline which is specified by XML file is also provided for practitioner to configure & design evolutionary algorithms at ease. User can edit runtime & algorithm parameters in the configuration file (XML) & issue the command to execute
> "java -jar jaea.jar <XML file>"

Note that some standard EA configuration are provided in the executable package: GA (gaconf.xml), MA (maconf.xml) and PSO (psoconf.xml)