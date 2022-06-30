# COVID-19 Misinformation Detection: Machine Learned Solutions to the Infodemic

This is the GitHub repository accompanying the paper [COVID-19 Misinformation Detection: Machine Learned Solutions to the Infodemic](https://preprints.jmir.org/preprint/38756) which aims to provide and analyze a collection of machine learning solutions to the COVID-19 misinformation problem.

## Description

This repository contains the following:
- Crowdsourcing Analysis:
    - Crowdsourced data used in the paper (in Crowdsourced_Data.csv file) 
    - Script used to analyze the data. (in analyze_crowdsourced_data.py file)

- ML Models:
    - Script used to train models on 7 dataset combinations and evaluate on external validation datasets. (in .ipynb files)
    - Weights and bias for models can be found here: https://drive.google.com/drive/folders/13GJrnk3D4XFM5N2EPSx4U7N_UYe47cgy?usp=sharing

- Datasets:
    - Datasets used in the paper can be accessed here : https://drive.google.com/drive/folders/12nh1QAD9G5yOGHdNbXO630uhtU7_AzGy?usp=sharing
        - The CoAID dataset is originially from here[1]: https://github.com/cuilimeng/CoAID
        - The FNN dataset is originially from here[2][3][4]: https://github.com/KaiDMML/FakeNewsNet


    - Model Predictions: predictions from models can be accessed here : https://drive.google.com/drive/folders/1k3GwrY4QqB_wwmEWnq4CDHmuFP8LsJBe?usp=sharing



## Authors

Contributors names and contact info

[@Nikhil Kolluri ](nlkolluri@utexas.edu)

[@Yunong Liu](y.liu-306@sms.ed.ac.uk)

[@Dhiraj Murthy](Dhiraj.Murthy@austin.utexas.edu)


## References

[1] @misc{cui2020coaid,
    title={CoAID: COVID-19 Healthcare Misinformation Dataset},
    author={Limeng Cui and Dongwon Lee},
    year={2020},
    eprint={2006.00885},
    archivePrefix={arXiv},
    primaryClass={cs.SI}
}

[2] @article{shu2018fakenewsnet,
  title={FakeNewsNet: A Data Repository with News Content, Social Context and Dynamic Information for Studying Fake News on Social Media},
  author={Shu, Kai and  Mahudeswaran, Deepak and Wang, Suhang and Lee, Dongwon and Liu, Huan},
  journal={arXiv preprint arXiv:1809.01286},
  year={2018}
}

[3] @article{shu2017fake,
  title={Fake News Detection on Social Media: A Data Mining Perspective},
  author={Shu, Kai and Sliva, Amy and Wang, Suhang and Tang, Jiliang and Liu, Huan},
  journal={ACM SIGKDD Explorations Newsletter},
  volume={19},
  number={1},
  pages={22--36},
  year={2017},
  publisher={ACM}
}

[4] @article{shu2017exploiting,
  title={Exploiting Tri-Relationship for Fake News Detection},
  author={Shu, Kai and Wang, Suhang and Liu, Huan},
  journal={arXiv preprint arXiv:1712.07709},
  year={2017}
}
