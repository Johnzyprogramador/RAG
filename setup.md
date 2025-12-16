# Setup

pip -m venv .venv

source .venv/bin/activate

pip install -r requirements.txt

# Register the kernel
pip install ipykernel
python -m ipykernel install --user --name=rag-venv --display-name "Python (RAG)"
