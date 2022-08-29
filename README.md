## UDSM-LLPS-Syn
In this study, we applied the deep sequence model – [UDSMProt](https://github.com/nstrodt/UDSMProt) to two new protein classification tasks.
1. **predict proteins with liquid-liquid phase separation propensity**
2. **predict synaptic proteins**<br />

Our results have shown that, without prior domain knowledge and only based on protein sequences, the fine-tuned language models achieved high classification accuracies and outperformed baseline models using compositional *k*-mer features in both tasks. For details of this work, please refer to our paper [**"Deep sequence representation learning for predicting human proteins with liquid-liquid phase separation propensity and synaptic functions"**](https://dl.acm.org/doi/10.1145/3535508.3545550) (Wei and Wang, 2022)
<p align = "center">
  <img src="figure1.png" width="650"></img>
</p>

## Dependencies
Please refer to the orignal repository of [UDSMProt](https://github.com/nstrodt/UDSMProt) for detailed information.

## Application Documentation
Here, we provide 2 Jupyter Notebooks as examples to show the application of the fine-tuned UDSM-LLPS models in the first learning task. As stated in our paper, we also evaluated the performance of UDSM-LLPS on another well-known database – [DrLLPS](http://llps.biocuckoo.cn/). DrLLPS is currently
the most comprehensive database with the largest collection of LLPS-associated proteins in 164 eukaryotes. In DrLLPS, LLPS-associated proteins can be browsed by three LLPS types, including 
(1) scaffolds, proteins that can drive or undergo LLPS; 
(2) clients, proteins that can be recruited by scaffolds for the formation of biomolecular condensates; 
and (3) regulators, proteins that have not been identified to undergo LLPS but shown to be involved in regulating LLPS behaviors.
