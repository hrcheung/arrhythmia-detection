<a name="readme-top"></a>
<div align="center">
<h1 align="center">Arrhythmia Detection</h1>
</div>

![visitor badge](https://visitor-badge.glitch.me/badge?page_id=hrcheung.arrhythmia-detection&left_color=green&right_color=red)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

###### Author: Chenjie Wu, Haoran Zhang, Qishu Dong 

###### The [paper](./final%20write-up.pdf)

## Everything About This Project

This project focused on the development of a machine learning model capable of distinguishing cardiac arrhythmias from normal electrocardiogram (ECG) signals. The primary aim was to build a reliable tool that could assist healthcare professionals in the diagnosis of arrhythmias, potentially leading to improved patient outcomes.

This project has successfully trained, compared two models and creatively identified popular deep learning model, Bidirectional Encoder Representations from Transformers (BERT), as a powerful tool. Models were trained and tested using the widely-used MIT-BIH Arrhythmia Database, which contains ECG recordings from a diverse range of patients with various cardiac conditions. A model was optimized using a random forest algorithm, which resulted in a high accuracy rate of 98.45\% in identifying arrhythmias. And the other model was optimized using BERT model, with 87\% accuracy rate. 


### Tech Requirements

- `Python` is required to run the model. 
- `Internet` is required to load the data. 
- `Colab` is an optional environment setup.

#### How to Reproduce the Result

1. Upload the `Detection.ipynb` to Colab.
2. Connect to runtime
3. Change runtime type to GPU hardware accelerator
4. Click Run button for each section to replicate feature engineering, BERT Model, and Random Forest Model
	- except for "2.3.2 Train" in "2.3 Trained with Pre-Trained BERT". This part might take more than 2 hours on GTX-3090.

### Other Resources
- [Presentation slides](https://docs.google.com/presentation/d/1DMAFFwFVI51kP_uvz7dtNAUy-8maEmEhzy5W9C0D0yg/edit#slide=id.p)


## Thanks

Thanks to prof. [Karl Ni](https://github.com/kni-neu) and all the references mentioned in the paper. <br>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
