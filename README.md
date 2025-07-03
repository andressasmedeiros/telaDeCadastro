# 📝 Tela de Cadastro de Usuário

Este é um exercício prático do curso **Clamed v3 - DEVInHouse**, desenvolvido em grupo, com o objetivo de implementar uma tela de criação de conta utilizando HTML, CSS e JavaScript. A aplicação valida os campos do formulário e armazena os dados do usuário no `localStorage`.

---

## 🚀 Funcionalidades

- **Campos obrigatórios**: Nome, URL da foto, e-mail, senha e confirmação de senha.
- **Validação de dados**:
  - Nome: não pode estar vazio.
  - URL da foto: deve ser uma URL válida.
  - E-mail: deve ser um endereço de e-mail válido.
  - Senha: deve ter entre 8 e 16 caracteres.
  - Confirmação de senha: deve corresponder exatamente à senha digitada.
  - Biografia: não deve exceder 300 caracteres.
- **Armazenamento local**: os dados do usuário são armazenados no `localStorage` no seguinte formato:
  ```json
  {
    "id": 123,
    "nome": "Nome do Usuário",
    "foto": "URL da Foto",
    "email": "email@dominio.com",
    "senha": "senha123",
    "biografia": "Texto da biografia"
  }
  ```
- **Exibição da foto**: ao digitar a URL da foto, ela é exibida automaticamente no campo correspondente.

---

## 📦 Tecnologias Utilizadas

- **HTML5**: Estruturação da página.
- **CSS3**: Estilização da interface.
- **JavaScript**: Lógica de validação e manipulação do DOM.
- **localStorage**: Armazenamento dos dados do usuário no navegador.

---

## 🛠️ Instalação e Execução

1. Clone este repositório:
   ```bash
   git clone https://github.com/andressasmedeiros/telaDeCadastro.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd telaDeCadastro
   ```

3. Abra o arquivo `index.html` em seu navegador preferido.

---

## 📂 Estrutura do Projeto

```
telaDeCadastro/
├── assets/                   # Imagens e recursos estáticos
├── scripts/                  # Scripts JavaScript
├── styles/                   # Arquivos de estilo CSS
├── index.html                # Arquivo principal
└── README.md                 # Este arquivo
```

---

## 📄 Licença

Este projeto está licenciado sob a licença **MIT**. Sinta-se à vontade para usar, modificar e distribuir o código.

---

## 👩‍💻 Exercício proposto no curso DevInHouse

**Andressa S. Medeiros** – Desenvolvedora do projeto

---
