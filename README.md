# 🤖 Automação de Relatório de Vendas com Python

Este projeto foi desenvolvido durante meus estudos no curso **#Treinamentos**, com o objetivo de aplicar na prática conceitos de automação utilizando Python.

A aplicação realiza uma automação completa para coletar, processar e enviar um relatório de vendas automaticamente.

---

## 🚀 Funcionalidades

* Acessa um sistema automaticamente (Google Drive)
* Faz download de uma base de dados em Excel
* Lê e processa os dados com Python
* Calcula indicadores importantes:

  * 💰 Faturamento total
  * 📦 Quantidade de produtos vendidos
* Envia um e-mail automático com o relatório

---

## 🧠 Conceitos aplicados

* Automação de tarefas com Python
* Manipulação de dados com Pandas
* Leitura e processamento de arquivos Excel
* Automação de interface com PyAutoGUI

---

## 🛠️ Tecnologias utilizadas

* Python
* PyAutoGUI
* Pandas
* OpenPyXL
* Pyperclip

---

## 📊 Exemplo de relatório enviado

Prezados,

Segue o relatório de vendas de hoje.

Faturamento: R$ 1.500,00
Quantidade de produtos vendidos: 150

Qualquer dúvida estou à disposição.

Att,
Eric Domingues

---

## 📸 Demonstração

![Automação rodando](img/demo.gif)

---

## ⚙️ Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/eric-domingues1/automacao-relatorio-vendas-python.git
```

---

### 2. Instalar as dependências

```bash
pip install pandas pyautogui openpyxl pyperclip
```

---

### 3. Executar o projeto

Abra o arquivo abaixo no VS Code ou Jupyter Notebook:

```
automacao_relatorio.ipynb
```

Execute as células passo a passo para rodar a automação.

---

## ⚠️ Observações importantes

* As coordenadas do mouse podem variar conforme a resolução da tela
* Pode ser necessário ajustar os tempos (`time.sleep`) dependendo da velocidade da internet
* O caminho do arquivo Excel pode precisar de ajuste no seu computador

---

## 💡 Melhorias futuras

* Tornar a automação independente da resolução da tela
* Integrar com APIs (evitar automação baseada em cliques)
* Converter o projeto para `.py` (padrão de mercado)
* Criar interface gráfica
* Agendar execução automática (Task Scheduler / Cron)

---

## 📁 Estrutura do projeto

```
📂 automacao-relatorio-vendas-python
 ┣ 📂 img
 ┃ ┗ 📸 demo.gif
 ┣ 📄 automacao_relatorio.ipynb
 ┣ 📄 README.md

```

---

## 📌 Autor

Desenvolvido por **Eric Domingues** 🚀
