# Multimodal RAG 
Multimoda RAG having Ability to process and generate multiple types of data, such as text, images, audio and more.
[knowledge](https://tulip-midnight-661.notion.site/Multimodal-RAG-150081da862380c1a020f850dec08350)

# Installation 
1. Clone the repository
```sh
git clone https://github.com/kaniagalih/multimodal_RAG.git
```

2. Run this code for installing requirements using conda 

```sh
conda env create --prefix ./multimodal_venv --file requirements.yaml
```

3. Activate the environment 
```sh
conda activate ./multimodal_venv
```

4. Verify Installation
```sh
conda list
```

5. Deactive environment
```sh
conda deactivate
```

6. Set Environment Variable 
```sh
export PROTOCOL_BUFFERS_PYTHON_IMPLEMENTATION=python  # For Linux/Mac
set PROTOCOL_BUFFERS_PYTHON_IMPLEMENTATION=python    # For Windows
```

7. Installing Poppler and tesseract
``sh
sudo apt-get install poppler-utils
sudo apt install tesseract-ocr
sudo apt install libtesseract-dev
```