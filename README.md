This is the official implementation of the materilas required to reproduce the results, presented in: 

**An analysis of vibrations and currents for broken rotor bar detection in three-phase induction motors**

Reproduction of the results provided in the paper, can be done through the following steps:

0. Downloading the original dataset and providing the path to ```.mat``` files to ```data_mining/upsampling_data_mining.ipynb``` notebook, as a ```string``` under the variable ```base_dir```
1. Running the ```data_mining/upsampling_data_mining.ipynb```
2. Running the ```data_mining/freq_domain_mining_hdf.ipynb```
3. Going through the **Conventional Classification** experiments, by running ```conventional_classification/coventional_current_based_classifier.ipynb``` and ```conventional_classification/coventional_vibration_based_classifier.ipynb```
4. Going through the **Hybrid Classification** experiments, by running ```hybrid_classification/current_based_hybrid_classifier.ipynb``` and ```hybrid_classification/vibrations_based_hybrid_classifier.ipynb```

Please cite our paper using the following citation entry:
```
@inproceedings{taghiyarrenani2022analysis,
  title={An analysis of vibrations and currents for broken rotor bar detection in three-phase induction motors},
  author={Taghiyarrenani, Zahra and Berenji, Amirhossein},
  booktitle={PHM Society European Conference},
  volume={7},
  number={1},
  pages={43--48},
  year={2022}
}
```