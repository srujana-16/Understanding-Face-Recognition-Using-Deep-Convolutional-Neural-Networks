# Understanding-Face-Recognition-Using-Deep-Convolutional-Neural-Networks
Our project aims to gain insights into the mechanisms underlying human face recognition by using specialized CNNs. We conducted experiments that included tasks such as target matching, similarity matching, multi-arrangement, and others. By comparing the performances of CNNs and human subjects on these tasks, we aim to understand the mechanisms that drive human face recognition.

## Instructions to run:

1. Access the `Code and Datasets for Experiments` folder, which contains code and stimuli for replicating the paper's results. If the exact stimuli aren't available, we've made every effort to replicate the inferences.

2. Download the necessary stimuli data by following the link provided in the `README.md` file within the `Code and Datasets for Experiments` folder.

3. Run the `Analysis.ipynb` Python script to visualize the results generated by our CNNs.

4. For a complete experience, download the CNN models we trained from the `README.md` file inside the `models` folder.

Training CNNs:

The information and links to the datasets we used to train the CNNs is avaliable on the README.md file inside the folder 'Training CNNs'.

## Methodology
## Data Collection
We procured data from various sources, including datasets provided by the original paper's author and publicly available datasets. This data collection process ensured the accuracy and comprehensiveness of our experiments.

## Experiments and Tasks
We conducted a series of experiments using specialized CNNs, designed to investigate various aspects of human face recognition and representation:

### Task 1: Human-level Accuracy in Face Recognition
- Measurement of human face recognition performance in a target-matching task.
- Testing the accuracy of four CNNs, each trained for specific tasks.
- Utilizing the penultimate layer activations to compute correlation distances between target images and presented images.
  
### Task 2: Representation of Faces in CNNs
- Conducting a multi-arrangement task with human subjects to obtain representational dissimilarity matrices (RDMs).
- Calculating correlation distances between penultimate fully-connected layer activations for pairs of stimuli.
- Comparing RDMs from CNNs to those of humans using Spearman Rank correlation.
  
### Task 3: Exploring Representational Spaces

- Participants perform a similarity-matching task to further understand representational spaces.
  
### Task 4: Classic Signatures of Human Face Processing
- Testing for face inversion and other race effects.
- Observing how human recognition performance is affected by unfamiliar races and upside-down stimuli.
- Demonstrating that CNNs trained on different racial datasets show similar patterns.
  
### Task 5: Inverted Face Inversion Effect

- Training CNNs exclusively on inverted faces and testing with upright datasets to create an "inverted inversion effect."
  
### Task 6: Car Inversion Effect

- Applying the target-matching task to test the effect of presenting the car dataset upside-down to the CNNs.


Note:
All the datasets used to train the CNNs and the stimuli images used to replicate the experiments is linked in the repo. Please refer to our report on the results of our study and summary of the original work.


Replication and Extension of the Research Paper: 'Dobs, Katharina &amp; Yuan, Joanne &amp; Martinez, Julio &amp; Kanwisher, Nancy. (2022). Using deep convolutional neural networks to test why human face recognition works the way it does. 10.1101/2022.11.23.517478. '
