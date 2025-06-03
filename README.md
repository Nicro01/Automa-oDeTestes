[![Testes Robot Framework](https://github.com/Nicro01/Automa-oDeTestes/actions/workflows/robot-tests.yml/badge.svg)](https://github.com/Nicro01/Automa-oDeTestes/actions/workflows/robot-tests.yml)

Aplicação simples de página de login com HTML, CSS e JavaScript. Este projeto inclui testes automatizados com **Robot Framework** e **SeleniumLibrary** para validar o comportamento da interface de login.

---

## 🚀 Como executar localmente

### 1. Clonar o repositório

```bash
git clone https://github.com/Nicro01/Automa-oDeTestes
cd loginpage
```

### 2. Iniciar um servidor local

Execute o comando abaixo para iniciar o servidor HTTP:

```bash
python -m http.server 8000
```

Acesse no navegador:

```
http://localhost:8000/index.html
```

---

## 🤖 Executando os testes automatizados

### 1. Instalar dependências

Você precisa do **Python 3** instalado. Em seguida:

```bash
pip install -r requirements.txt
```

### 2. Executar os testes

```bash
robot tests/teste_login.robot
```

Após a execução, serão gerados os seguintes arquivos na pasta `tests/`:

- `log.html`: Log detalhado dos testes
- `report.html`: Relatório resumido
- `output.xml`: Arquivo de saída padrão

---

## 🛠️ Ferramentas e Bibliotecas

- HTML/CSS/JavaScript
- [Robot Framework](https://robotframework.org/)
- [SeleniumLibrary](https://robotframework.org/SeleniumLibrary/)
- Google Chrome + ChromeDriver

---

## ✅ Status dos testes automatizados

Todos os testes são executados automaticamente no GitHub Actions a cada `push` ou `pull request` na branch `main`. O badge no topo deste README indica o status atual da última execução.

---

## 📁 Estrutura do Projeto

```
loginpage/
├── index.html
├── dashboard.html
├── script.js
├── style.css
├── tests/
│   └── teste_login.robot
│   └── log.html / report.html
├── requirements.txt
└── .github/
    └── workflows/
        └── robot-tests.yml
```
