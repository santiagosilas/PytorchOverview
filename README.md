# PytorchOverview
Pytorch Overview

Crie um ambiente virtual. Por exemplo:

```bash
conda create -n Py39PytorchOverview python=3.9
```

Para ativar o ambiente:
```bash
conda activate Py39PytorchOverview
```

Neste ambiente, instale o pytorch neste ambiente:

```bash
conda install pytorch torchvision torchaudio pytorch-cuda=12.4 -c pytorch -c nvidia
```

Instale também
```bash:
conda install -c conda-forge notebook ipykernel
```

Registre o kernel
```bash:
python -m ipykernel install --user --name Py39PytorchOverview --display-name "Pytorch Overview (Python 3.9)"
```

Para desativar o ambiente:
```bash
conda deactivate
```


Bom proveito!


