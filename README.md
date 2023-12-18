This GitHub repository, titled "OOM-X-IIoTID," is dedicated to showcasing our pioneering work on Manifold Adversarial Attacks in the context of Cybersecurity and the Industrial Internet of Things (IIoT). As far as we are aware, this is the first instance of such an approach in these domains.
The name "OOM-X-IIoTID" is derived from the integration of ON and OFF manifold adversarial attacks with the  X-IIoTID dataset.
 ** Creadit: The author of the  X-IIoTID Dataset is Al-Hawawreh et al., 2021. For more details, refer to DOI 10.21227/mpb6-py55.

The repository is structured into three directories, with a refined focus on the ON-X-IIoT Directory:

1. **Original Dataset Directory  (X-IIoTID)**:  The GitHub repository features a structured arrangement of files under the 'Clean Attack' category:

    - Multi-XIIoTD: Multiclass Format File – This file offers a detailed view of the dataset in a multiclass format.

    - Binary-X-IIoTD: Binary Class Format File – It provides a binary class perspective of the dataset.

    -  train: Training Set File – Comprising 90% of the data, this file is intended for training models.

    -  test: Testing Set File – This file contains the remaining 10% of the data, designated for testing models.

    - Clean_Attack_Examples: Normal Attack Samples File – Featuring 319,553 samples of cybersecurity attacks (Normal attack samples), this file represents the dataset before the addition of adversarial inputs.

    - Test_Clean File – A crucial preprocessing tool for test samples, this file is used alongside generated samples in other directories(a preprocessed verion of test file).
    

2. **ON-X-IIoT Directory**: In the ON-X-IIoT directory, we feature On-manifold samples that are generated using our Silency Adversarial Autoencoder (SAAE) model. generates On-manifold adversarial attacks using two optimization algorithms. The first algorithm identifies perturbations in High-Dimensional (H-D) space, while the second finds perturbations in Low-Dimensional (L-D) space, utilizing a generative optimization algorithm. This directory is distinctly organized and includes two types of samples: Normal samples, and a combination of On-manifold and attack samples. For the sake of simplicity, we categorize both the attack samples and the On-manifold samples under a single category labeled 'attack'. This simplification allows for a more streamlined classification and analysis of the manifold adversarial impacts in the IIoT domain.

3. **OFF-ON-X-IIoT Directory**:In this directory, we have generated adversarial attack samples based on attack transferability using the X-IIoTID dataset and a set of adversarial algorithms, namely JSMA, FGSM, BIM, DF, C&W L2, and Linf. The directory contains three main files.
 
   - *OFF-Manifold Samples (OFF-JSAM)*: This file contains samples that comply with the functional behavior of network traffic, encompassing both its syntactical and semantic structure. Generated by JSMA, for simplicity in testing, we have organized it into two classes: Normal, and a combined category labeled 'attack', which includes both Off-manifold attacks and Cybersecurity attacks specific to the X-IIoT dataset
   - *Clean_ADV*: Consists of adversarial samples fitting the network traffic’s syntactical and semantic structure, under a single class.
   - *!Clean_adv*: A mix of adversarial attack samples, some aligning with and some deviating from the network traffic structure.
