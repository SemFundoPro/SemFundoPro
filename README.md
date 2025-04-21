# SemFundoPro

API para remoção de fundos de imagem utilizando inteligência artificial com FastAPI + rembg.

## 🚀 Como usar no [Render](https://render.com)

1. Faça login no [Render](https://render.com)
2. Crie um novo Web Service
3. Conecte com este repositório
4. Configure:

- **Build Command:** `pip install -r requirements.txt`
- **Start Command:** `uvicorn main:app --host 0.0.0.0 --port 10000`
- **Environment:** Python 3

5. Após o deploy, sua API estará acessível em:

```
https://<nomedoseuservico>.onrender.com/remover-fundo/
```

Você pode usar esse endpoint diretamente no seu agente GPT como ação personalizada.
