# DLS-Singapore
The present project was developed for the [CyberSecurity Camp & Hackaton @Singapore 2017](http://www.comp.nus.edu.sg/~tsunami/sg-crc17/pdf/NUS-Workshop-Flyer2.pdf)

We provide an OSS implementation of the paper [Deep Neural Network Based Malware Detection Using Two Dimensional Binary Program Features](https://arxiv.org/pdf/1508.03096v2.pdf) and some variations we explored:
- original vector compression by using auto-encoders
- binary code representation based on LSTM auto-encoders
- malware analysis trasposing binary code information to images domain
- multiple architectures we used to evaluate the features generated

We used Keras to generate the encoders and architectures.

REPORT : https://tinyurl.com/yc5eblsg

### Team members:
- Palash Chauhan (Indian Institute of Technology, Kanpur)
- Vivek Verma (Indian Institute of Technology, Kanpur)
- Joze Rozanec (Universidad de Buenos Aires, Argentina)


## Things to read
1. https://www.blackhat.com/docs/us-16/materials/us-16-Berlin-An-AI-Approach-To-Malware-Similarity-Analysis-Mapping-The-Malware-Genome-With-A-Deep-Neural-Network.pdf
2. https://arxiv.org/pdf/1508.03096v2.pdf
3. Any tutorial on Auto-Encoders
 a. https://keras.io/getting-started/sequential-model-guide/
 b. 

## Dataset
1. Malware Files: https://drive.google.com/open?id=0B9fG_FJRJKS_d1BOUjJRZ2pWZEE
2. Reports on Malware Files: https://drive.google.com/file/d/0B9fG_FJRJKS_ZkxxT1BlbWh6MEU/view?usp=sharing
3. Benign Files: https://drive.google.com/open?id=0B9fG_FJRJKS_RnF5Ynhmb0R3WTQ
4. https://zeltser.com/malware-sample-sources/
5. https://www.kaggle.com/c/malware-classification/data


## Useful papers & info
### Malware representation
#### Execution Graph as vector
- Code Graph for Malware Detection: http://ieeexplore.ieee.org/document/4472801/
- Graph embedding as a new approach for unknown malwaredetection: http://www.readcube.com/articles/10.1007/s11416-016-0278-y
- BitBlaze Binary analysis platform: http://bitblaze.cs.berkeley.edu/
- HI-CFG: Construction by Binary Analysis and Application to Attack Polymorphism: https://people.eecs.berkeley.edu/~dawnsong/papers/hicfg.pdf
#### Binary sequence to vector
- we consider binaries of different length as a LSTM case, and turn it into a vector
- http://datascience.stackexchange.com/questions/6866/denoising-autoenoders-with-variable-length-input
- https://keras.io/getting-started/sequential-model-guide/
- https://www.reddit.com/r/MachineLearning/comments/3iidv2/is_it_a_good_idea_generate_sentence_vectors_using/

## Data

- https://drive.google.com/open?id=0B9fG_FJRJKS_UXkwMEgtV2NpRUE
