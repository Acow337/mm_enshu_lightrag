# LightRAG for MM_enshu



Preparation

```bash
# please install ollama first (https://github.com/ollama/ollama)
ollama pull bge-m3
ollama serve
# make sure that the ollama is running (http://127.0.0.1:11434/)

# create a virtual environment
conda create --name lightrag_env python=3.10
conda activate lightrag_env
```



Quick Start

```bash
# python version >= 3.10
git clone https://github.com/Acow337/mm_enshu_lightrag.git
pip install -e ".[api]"

cd mm_enshu_lightrag
cd lightrag
# copy your .env file to the "lightrag" folder

lightrag-server
```

