# SemFundoPro (GPU compatível)

Versão usando onnxruntime-gpu 1.14.1 — 100% compatível com Python 3.11+ e ambiente do Render.

## Deploy no Render

- Build Command: pip install -r requirements.txt
- Start Command: uvicorn main:app --host 0.0.0.0 --port $PORT
- Porta: dinâmica com variável $PORT

URL da API: https://<nomedoseuservico>.onrender.com/remover-fundo/
