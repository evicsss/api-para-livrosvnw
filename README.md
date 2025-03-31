# API de Gerenciamento de Livros - Vai Ler na Web  

Uma API desenvolvida com **Flask** e **SQLite**, permitindo o cadastro e a listagem de livros doados. Criada para fins de estudo na **Escola Vai na Web**.

---

## Tecnologias utilizadas  

- **Python 3**  
- **Flask**  
- **SQLite**   

---

## Pré-requisitos  

Antes de começar, certifique-se de ter:  

- **Python** instalado na versão 3+  
- **Git** para clonar o repositório  
- Um terminal configurado para rodar os comandos  

---

## Instalação e Execução  

Siga os passos abaixo para rodar a API no seu ambiente local:  

### 1️⃣ Clone este repositório  

```bash
git clone https://github.com/SeuUsuario/nome-do-repositorio.git
cd nome-do-repositorio
```

### 2️⃣ Crie e ative um ambiente virtual  

```bash
python -m venv venv
source venv/Scripts/activate  # Windows
source venv/bin/activate      # Linux/Mac
```

### 3️⃣ Instale as dependências  

```bash
pip install -r requirements.txt
```

### 4️⃣ Execute o servidor  

```bash
python app.py
```

A API estará rodando em **http://127.0.0.1:5000/**  

---

## 🌍 Endpoints  

### 📌 `POST /doar` - Cadastrar um livro  

**Requisição (JSON):**  

```json
{
  "titulo": "Descolonizando Afetos",
  "categoria": "Psicologia",
  "autor": "Geni Núñez",
  "imagem_url": "https://exemplo.com/livro.jpg"
}
```

**Resposta (201 - Criado):**  

```json
{
  "mensagem": "Livro cadastrado com sucesso!"
}
```

---

### 📌 `GET /livros` - Listar todos os livros cadastrados  

**Resposta (200 - OK):**  

```json
[
  {
    "id": 1,
    "titulo": "Descolonizando Afetos",
    "categoria": "Psicologia",
    "autor": "Geni Núñez",
    "imagem_url": "https://exemplo.com/livro.jpg"
  }
]
```

---

   ```

3. **Realize as alterações** e faça commit delas:  

   ```bash
   git commit -m "Adiciona nova funcionalidade X"
   ```

4. **Envie para o repositório remoto**:  

   ```bash
   git push origin minha-nova-feature
   ```

5. **Abra um Pull Request** e aguarde a revisão!  

---

##  Licença  

Este projeto está sob a **Licença MIT**. Sinta-se à vontade para usá-lo e modificá-lo.  

---
 *Projeto desenvolvido para fins educacionais na Escola Vai na Web.* 
