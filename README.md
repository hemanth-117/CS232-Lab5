# Best-Offset Prefetching
This project is an implementation of the "Best-Offset Prefetching" algorithm described in the paper "Improving Data Cache Performance by Prefetching Based on Best Offset" by Q. Wu, W. Huang, W. Gao, and X. Zhang.
### STEPS EXECUTE THE CODE

- Download [ChampSim repository]( https://github.com/casperIITB/ChampSim)
- Place `bofp.l2c_pref` files inside `champsim/ChampSim/prefetcher` folder 
- Download traces for execution
- Navigate to the `/champsim/ChampSim` folder, and run:

./build_champsim.sh bimodal no no bofp no lru 1

- Now, we need to run the `run_champsim.sh` file for the BINARY created in above step and for each TRACE and observe the results:

./run_champsim.sh [BINARY] 30 30 [TRACE]
### Contribution
-Hemanth,Chanikya,Lohith
