This GitHub repository, titled "OOM-X-IIoT," is dedicated to showcasing our pioneering work on Manifold Adversarial Attacks in the context of Cybersecurity and the Industrial Internet of Things (IIoT). As far as we are aware, this is the first instance of such an approach in these domains.

The repository is structured into three directories, with a refined focus on the ON-X-IIoT Directory:

1. **Original Dataset Directory  (X-IIoTID)**: This contains datasets in both Multiclass and Binary class formats. The data is divided into an 80% training set and a 20% testing set. It includes:
   - *Clean Attack*: Showcasing cybersecurity attack data before the introduction of adversarial inputs.
   - *Test_Clean*: A preprocessing file for test samples, used in conjunction with generated samples in other directories.
  
     ** Creadit: The author of the first two files in the X-IIoTID Dataset is Al-Hawawreh et al., 2021. For more details, refer to DOI 10.21227/mpb6-py55.

2. **ON-X-IIoT Directory**: This directory is uniquely structured to combine on-manifold generated samples and cybersecurity attacks into one unified category. The samples are produced using our SAAE model and focus on two principal classes: Normal operations and combined On-manifold/Cybersecurity attacks for the X-IIoT dataset. This simplification allows for a more streamlined classification and analysis of the manifold adversarial impacts in the IIoT domain.

3. **OFF-ON-X-IIoT Directory**: Includes:
   - *OFF-Manifold Samples (OFF-JSAM)*: With two classes - Normal and Off-manifold attacks (using JSMA) alongside Cybersecurity attacks for the X-IIoT dataset.
   - *Clean_ADV*: Consists of adversarial samples fitting the network traffic’s syntactical and semantic structure, under a single class.
   - *!Clean_adv*: A mix of adversarial attack samples, some aligning with and some deviating from the network traffic structure.
