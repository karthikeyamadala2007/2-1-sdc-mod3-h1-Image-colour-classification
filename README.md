python -m venv .venv
PowerShell -ExecutionPolicy Bypass


.venv\Scripts\activate

python scripts/train_cnn.py                           
python -m scripts.train_hybrid
<!-- python scripts/train_hybrid.py                            -->

.venv\Scripts\python.exe -m streamlit run app.py 