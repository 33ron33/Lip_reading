# LiveLipNet-Duo: Real-Time Dual-Speaker Lipreading
Abstract
LiveLipNet-Duo: Real-Time Dual-Speaker Lipreading

LiveLipNet-Duo presents a novel approach in assistive technologies for overcoming the com- munication barriers for the individuals with hearing impairments. Our model leverages the synergy between the spatiotemporal convolutions and recurrent neural network architectures to transcribe the real-time interpretation of speech from two speakers simultaneously. For the elim- ination of the manual segmentation, we employ the connectionist temporal classification (CTC) loss which enables direct, end-to-end training from unprocessed video input to textual tran- scription. We are additionally developing an extensive dataset with recordings from a diverse groups of speakers (2 males and 2 females) with varied backgrounds to guarantee robustness and generalization in lipreading training. This project aims not only to improve accessibility for those with hearing impairments, but also extends the use of lipreading into loud environments, where other speech recognition systems that rely solely on audio are ineffective.
# Setting Up the LiveLipNet-Duo Environment

This guide will walk you through setting up the Python environment required to run the projects in the [LiveLipNet-Duo repository](https://github.com/33ron33/LiveLipNet-Duo).

## Prerequisites

Ensure you have Python installed on your system. You can download Python from [python.org](https://www.python.org/downloads/).

## Clone the Repository

First, clone the LiveLipNet-Duo repository to your local machine:

```bash
git clone https://github.com/33ron33/LiveLipNet-Duo.git
cd LiveLipNet-Duo
```

## Create and Activate a Virtual Environment

Create a virtual environment nmaes 'LiveLipNet-env' within the repository directory:

```bash
python -m venv LiveLipNet-env
```

Activate the Virtual Environment 
- On macOS/Linux:
```bash
source LiveLipNet-env/bin/activate
```
- On Windows:
```bash
LiveLipNet-env\Scripts\activate
```
## Insatll and Verify Dependencies 
Install the project dependencies from the 'requirements.txt' file:
```bash
pip install -r requirements.txt
```

Verify Dependencies:
```bash
pip list
```
## Setting Up IPython Kernel

To set up the IPython kernel for the virtual environment, run the following command:

```bash
python -m ipykernel install --name=LiveLipNet-env
```

# Deactivate the Virtual Environment-

```bash
deactivate
```

  



