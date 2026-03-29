# 🤖 Automação de Relatório de Vendas com Python - Projeto #Treinamentos

Este projeto realiza uma automação completa utilizando Python para coletar, processar e enviar um relatório de vendas automaticamente.

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
git clone https://github.com/seu-usuario/automacao-relatorio-vendas-python.git
```

---

### 2. Instalar as dependências

```bash
pip install pandas pyautogui openpyxl pyperclip
```

---

### 3. Executar o script

```bash
python automacao_relatorio.py
```

---

## ⚠️ Observações importantes

* As coordenadas do mouse podem variar conforme a resolução da tela
* Pode ser necessário ajustar os tempos (`time.sleep`) dependendo da sua internet
* O caminho do arquivo Excel pode precisar de ajuste no seu computador

---

## 💡 Melhorias futuras

* Tornar a automação independente da resolução da tela
* Integrar com API (evitar uso de automação de mouse)
* Criar interface gráfica
* Agendar execução automática (Task Scheduler / Cron)

---

## 📁 Estrutura do projeto

```
📂 automacao-relatorio-vendas-python
 ┣ 📂 img
 ┃ ┗ 📸 print.png
 ┣ 📄 automacao_relatorio.ipynb
 ┣ 📄 README.md
 
```

---

## 📌 Autor

Desenvolvido por **Eric Domingues** 🚀

