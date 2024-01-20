# PyTorchU Toolkit

## Environment Setup

We recommend using [Anaconda](https://www.anaconda.com/) along with [conda environments](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#) for a consistent development environment. You can replicate the required environment by following the steps below:

### Installation from YML File

Run the following command to create the environment from the provided YAML file:

```bash
C:\...> conda env create -f pytorch.yml
```

### Manual Installation

In case the YAML file installation fails, you can manually set up the environment using the following commands:

```bash
C:\...> conda create -n pytorch python=3.10
C:\...> conda activate pytorch
(pytorch) C:\...> conda install pytorch torchvision torchaudio cpuonly -c pytorch
(pytorch) C:\...> conda install ipykernel
(pytorch) C:\...> conda install -c anaconda seaborn
(pytorch) C:\...> conda install scikit-learn
(pytorch) C:\...> conda install -c conda-forge detecto
```

These instructions ensure a clean and comprehensive setup for the PyTorchU Toolkit.