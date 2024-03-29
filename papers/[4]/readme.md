## Title
Improving the Utility of Locally Differentially Private Protocols for Longitudinal and Multidimensional Frequency Estimates

## Abstract
This paper investigates the problem of collecting multidimensional data throughout time (i.e., longitudinal studies) for the fundamental task of frequency estimation under Local Differential Privacy (LDP) guarantees. Contrary to frequency estimation of a single attribute, the multidimensional aspect demands particular attention to the privacy budget. Besides, when collecting user statistics longitudinally, privacy progressively degrades. Indeed, the “multiple” settings in combination (i.e., many attributes and several collections throughout time) impose several challenges, for which this paper proposes the first solution for frequency estimates under LDP. To tackle these issues, we extend the analysis of three state-of-the-art LDP protocols (Generalized Randomized Response – GRR, Optimized Unary Encoding – OUE, and Symmetric Unary Encoding – SUE) for both longitudinal and multidimensional data collections. While the known literature uses OUE and SUE for two rounds of sanitization (a.k.a. memoization), i.e., L-OUE and L-SUE, respectively, we analytically and experimentally show that starting with OUE and then with SUE provides higher data utility (i.e., L-OSUE). Also, for attributes with small domain sizes, we propose Longitudinal GRR (L-GRR), which provides higher utility than the other protocols based on unary encoding. Last, we also propose a new solution named Adaptive LDP for LOngitudinal and Multidimensional FREquency Estimates (ALLOMFREE), which randomly samples a single attribute to be sent with the whole privacy budget and adaptively selects the optimal protocol, i.e., either L-GRR or L-OSUE. As shown in the results, ALLOMFREE consistently and considerably outperforms the state-of-the-art L-SUE and L-OUE protocols in the quality of the frequency estimates.

## Experiments
* Please refer to [1_ALLOMFREE_Analysis.ipynb](https://github.com/hharcolezi/ldp-protocols-mobility-cdrs/blob/main/papers/%5B4%5D/1_ALLOMFREE_Analysis.ipynb) for the theoretical analysis.
* Please refer to [2_ALLOMFREE_LDP_VHs.ipynb](https://github.com/hharcolezi/ldp-protocols-mobility-cdrs/blob/main/papers/%5B4%5D/2_ALLOMFREE_LDP_VHs.ipynb) for the experimental evaluation with a real-world and open dataset.

## Recommended citation

If you consider using our findings and dataset in your research, we would appreciate a reference to:

```
Arcolezi, H. H., Couchot, J.F., Al Bouna, B., & Xiao, X. Improving the utility of locally differentially private protocols for longitudinal and multidimensional frequency estimates. Digital Communications and Networks (2022). https://doi.org/10.1016/j.dcan.2022.07.003
```

## Bibtex
```
@article{Arcolezi2021_allomfree,
  doi = {10.1016/j.dcan.2022.07.003},
  year = {2022},
  month = jul,
  publisher = {Elsevier {BV}},
  author = {H{\'{e}}ber H. Arcolezi and Jean-Fran{\c{c}}ois Couchot and Bechara Al Bouna and Xiaokui Xiao},
  title = {Improving the utility of locally differentially private protocols for longitudinal and multidimensional frequency estimates},
  journal = {Digital Communications and Networks}
}
```
