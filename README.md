# Auto-Evolution-Hyper-Heuristic-Algorithm

## intorduction

This research uses time series models to forecast electricity generation from renewable energy sources and electricity consumption. Setting the initial parameters for these models typically requires optimization algorithms, but conventional ones often struggle with fixed hyperparameters and limited robustness. To address this, we propose an auto-evolution hyper-heuristic algorithm AE-GAPB. AE-GAPB integrates a genetic algorithm (GA) at the high level and uses particle swarm optimization (PSO) and the bat algorithm (BA) at the low level. The GA continuously finds the best hyperparameters for PSO and BA based on prediction accuracy, improving their optimization. Additionally, the GA's crossover and mutation rates evolve over time and fitness value space, enhancing its adaptability. We validated AE-GAPB using six time series forecasting models and compared it with five other optimization algorithms. AE-GAPB achieved excellent results on renewable energy generation and electricity consumption datasets from Hokkaido, Kyushu, and Tohoku regions in Japan.
