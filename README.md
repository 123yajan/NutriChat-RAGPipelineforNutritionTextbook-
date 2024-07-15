# NutriChat-RAG Pipeline for Nutrition Textbook

## Setup

Note: Tested in Python 3.11, running on Windows 11 with a NVIDIA RTX 4090 with CUDA 12.1.

### Clone repo

```
git clone https://github.com/mrdbourke/simple-local-rag.git
```

```
cd simple-local-rag
```


### Create environment

```
python -m venv venv
```

### Activate environment

Linux/macOS:
```
source venv/bin/activate
```

Windows: 
```
.\venv\Scripts\activate
```

### Install requirements

```
pip install -r requirements.txt
```


On Windows I used:

```
pip3 install -U torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```

### Launch notebook

VS Code:

```
code .
```

Jupyter Notebook

```
jupyter notebook
```


