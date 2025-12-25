# 🏋️ Academia API

Uma API simples feita com **FastAPI** para estudar backend e criação de APIs REST.

Ela permite cadastrar e listar participantes de uma academia, garantindo regras básicas como **CPF único**.  
Projeto focado em aprendizado e prática 🚀

---

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

## 🔗 Acessos e testes

Depois de rodar o projeto, a API fica disponível localmente.  
Você pode acessar pelo navegador ou usar o Swagger para testar os endpoints.

- 🌐 API (endereço base):  
  [http://127.0.0.1:8000](http://127.0.0.1:8000)

- 📚 Swagger (interface de testes):  
  [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

Links para copiar:
```text
http://127.0.0.1:8000
http://127.0.0.1:8000/docs
