# ⚡ Academia API

Projeto de estudo com **FastAPI** para praticar desenvolvimento de backend.  
A API permite **registrar** e **consultar** participantes da academia, garantindo que cada CPF seja único.  
Um laboratório simples para aprender e testar conceitos de APIs REST 🚀


## 🧠 Como isso funciona?

Essa aplicação é uma **API**, ou seja:
- não tem tela (frontend)
- funciona recebendo requisições (GET, POST, etc.)
- responde com dados em JSON

Para facilitar os testes, o FastAPI gera automaticamente uma interface chamada **Swagger**.

---

## ▶️ Rodando o projeto

Depois de instalar as dependências, use o comando abaixo:

```bash
uvicorn main:app --reload
```

🔗 Acessos e testes

🌐 API (endereço base):
```bash
http://127.0.0.1:8000
```
📚 Swagger (onde você testa a API):
```
http://127.0.0.1:8000/docs
