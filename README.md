# SemFundoPro (sem onnx - fallback definitivo)

API para remoção de fundo com rembg (sem onnxruntime), compatível com Render Free Tier (Python 3.11+).

### Deploy no Render:
- Build: pip install -r requirements.txt
- Start: uvicorn main:app --host 0.0.0.0 --port $PORT
- Endpoint: /remover-fundo/
