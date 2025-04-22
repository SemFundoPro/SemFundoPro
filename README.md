# SemFundoPro (versão compatível)

API para remoção de fundos de imagem utilizando FastAPI + rembg + onnxruntime 1.14.1 (compatível com Render Free Tier).

## Como usar no Render

1. Crie um Web Service em https://render.com
2. Conecte este repositório ao serviço
3. Use estas configurações:

- Build Command: pip install -r requirements.txt
- Start Command: uvicorn main:app --host 0.0.0.0 --port $PORT

A API estará acessível em: https://<nomedoseuservico>.onrender.com/remover-fundo/
