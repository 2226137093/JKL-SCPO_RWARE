The framework consists of three stages. 
In the first stage, a runtime model SCMG (Safety Con-strained Markov Game) is defined for the multi-robot system at runtime in the intelligent warehouse. 
In the second stage, rPATL (probabilistic alternating-time temporal logic with rewards) is used to express safety properties, and SCMG is cyclically verified and refined through runtime verification (RV) to ensure safety. This stage guarantees the safety of robots’ behaviors before training. 
In the third stage, the verified SCMG guides SCPO (safety constrained policy optimization) to get the optimized safety policy of robots. 
Finally, a multi-robot warehouse (RWARE) scenario of Shanghai Intelligent Warehouse is used for experimental verification. 
