# 📚 Jupyter Hub — Tutoriais Interativos de Programação

**Três trilhas completas de aprendizado em português, desenvolvidas inteiramente em Jupyter Notebooks.**

---

## 🧭 Visão Geral

Bem-vindo ao **Jupyter Hub**! Este repositório reúne material didático de alta
qualidade para quem quer aprender programação do zero ou aprimorar suas
habilidades. Tudo é feito em **Jupyter Notebooks** — arquivos interativos que
combinam explicações, código executável e visualizações em um só lugar.

O projeto é dividido em três grandes trilhas de aprendizado:

| Trilha | Foco | Nível | Capítulos |
|--------|------|-------|-----------|
| 📓 **Jupyter Notebook** | Aprender a usar a ferramenta Jupyter | Iniciante | 16 |
| 🐍 **Python Completo** | Aprender Python do zero ao avançado | Iniciante ao Avançado | 35 |
| 📊 **Estatística** | Aprender Estatística com Python | Intermediário | 42 |

---

## 📓 Tutorial: Jupyter Notebook

> **A ferramenta primeiro.** Antes de programar, aprenda a usar o ambiente
> onde tudo acontece.

Este tutorial ensina todos os aspectos do Jupyter: instalação, interface,
células de código e Markdown, atalhos de teclado, kernel, widgets interativos,
comandos mágicos, extensões e boas práticas de compartilhamento. São **16
capítulos** que transformam completos iniciantes em usuários confiantes do
Jupyter.

➡️ [`Tutorial_Jupyter/README.md`](Tutorial_Jupyter/README.md)

## 🐍 Curso: Python Completo

> **A linguagem.** Do `print("Olá, mundo!")` até Machine Learning.

Curso intensivo de Python com **35 capítulos** baseado na estrutura do tutorial
da W3Schools, mas expandido e contextualizado para o público brasileiro. Cobre
desde sintaxe básica e tipos de dados até tópicos avançados como Programação
Orientada a Objetos, Manipulação de Arquivos, Bancos de Dados (MySQL, MongoDB),
Visualização com Matplotlib e Machine Learning.

➡️ [`Tutorial_Python/README.md`](Tutorial_Python/README.md)

## 📊 Curso: Estatística

> **A análise dos dados.** Domine os conceitos estatísticos com Python.

Curso completo de Estatística com **42 capítulos** baseado no tutorial da W3Schools
Statistics, adaptado para o público brasileiro. Cobre desde conceitos fundamentais
(introdução, coleta de dados, tipos de estudo) até estatística descritiva (média,
mediana, desvio padrão, histogramas) e inferencial (distribuições, testes de
hipótese, estimação). Todos os exemplos em Python com NumPy, SciPy e Matplotlib.

➡️ [`Tutorial_Estatistica/README.md`](Tutorial_Estatistica/README.md)

---

## 🎯 Público-alvo

- **Estudantes** que querem aprender programação do zero
- **Professores** que precisam de material didático interativo em português
- **Profissionais de dados** que desejam dominar o ecossistema Jupyter + Python
- **Autodidatas** que preferem aprender no próprio ritmo, com exemplos práticos

## ✅ Pré-requisitos

- **Python 3.10** ou superior instalado
- Um navegador moderno (Chrome, Firefox, Edge)
- Vontade de aprender — nenhuma experiência prévia em programação é exigida
  para o curso de Python

## 🚀 Como usar

1. **Clone** ou baixe este repositório
2. Ative o ambiente virtual (`.venv/`) ou instale as dependências com
   `pip install -r requirements.txt`
3. Inicie o Jupyter: `jupyter notebook` ou `jupyter lab`
4. Navegue até a pasta do tutorial desejado e abra o notebook `J00_Index_Jupyter.ipynb`
   (Jupyter), `00_Index.ipynb` (Python) ou `S00_Index_Estatistica.ipynb` (Estatística)

> 💡 **Dica:** Siga a ordem numérica dos arquivos. Cada capítulo assume que
> você já viu o anterior.

---

## 📁 Estrutura do Repositório

```
Jupyter-hub/
│
├── Tutorial_Jupyter/          # 16 notebooks — Tutorial de Jupyter
│   ├── J00_Index_Jupyter.ipynb
│   ├── J01_O_que_e_Jupyter_Instalacao.ipynb
│   ├── ...
│   └── J15_Compartilhar_Boas_Praticas.ipynb
│
├── Tutorial_Python/           # 35 notebooks — Curso de Python
│   ├── 00_Index.ipynb
│   ├── 01_Introducao_e_Ambiente.ipynb
│   ├── ...
│   └── 35_MongoDB.ipynb
│
├── Tutorial_Estatistica/      # 43 notebooks — Curso de Estatística
│   ├── S00_Index_Estatistica.ipynb
│   ├── S01_Introducao_Estatisticas.ipynb
│   ├── ...
│   └── S42_Teste_Media_Bicaudal.ipynb
│
├── jupyterhub_client.py       # Cliente REST API para gerenciar JupyterHub
├── requirements.txt           # Dependências do projeto
├── .env                       # Configuração da API do JupyterHub (não versionar)
├── .env.example               # Template para o arquivo .env
└── W3S_python_Index.md        # Índice de referência do tutorial W3Schools
```

## 🛠️ Ferramentas e Tecnologias

| Ferramenta | Uso no projeto |
|------------|---------------|
| **Jupyter Notebook / JupyterLab** | Ambiente interativo para os tutoriais |
| **Python 3.10+** | Linguagem principal dos cursos |
| **NumPy, Pandas** | Análise e manipulação de dados |
| **Matplotlib, Seaborn, Plotly** | Visualização de dados |
| **scikit-learn** | Machine Learning (classificação, regressão, clustering) |
| **ipywidgets** | Widgets interativos nos notebooks |
| **JupyterHub** | Plataforma de deploy (gerenciada via `jupyterhub_client.py`) |

---

> 🚀 *Navegue até a pasta do tutorial desejado e abra os notebooks no Jupyter
> para começar a estudar!*

---

## 📜 Créditos e Atribuições

Este projeto foi **fortemente baseado nos tutoriais da [W3Schools](https://www.w3schools.com/)**, um dos maiores e mais respeitados sites de aprendizado de programação e tecnologia do mundo.

### 🐍 Curso de Python

O **Curso Completo de Python** (35 capítulos) foi desenvolvido a partir da estrutura e do conteúdo do [W3Schools Python Tutorial](https://www.w3schools.com/python/), expandido e contextualizado para o público brasileiro. Cada capítulo segue a progressão pedagógica proposta pela W3Schools, com acréscimo de explicações detalhadas em português, exemplos extras, exercícios práticos e projetos.

### 📊 Curso de Estatística

O **Curso Completo de Estatística** (42 capítulos) foi desenvolvido a partir do [W3Schools Statistics Tutorial](https://www.w3schools.com/statistics/), seguindo a mesma estrutura de tópicos e a ordem de apresentação dos conceitos. Todo o conteúdo foi adaptado para o português e reescrito com exemplos em Python usando NumPy, SciPy, Matplotlib e Pandas.

### 📓 Tutorial Jupyter

O **Tutorial de Jupyter Notebook** (16 capítulos) é conteúdo original, desenvolvido especificamente para este projeto, e não possui vínculo com a W3Schools.

### ✅ Licenciamento e Boas Práticas

- Todo o material foi **adaptado e reescrito** em português, respeitando a estrutura pedagógica original dos tutoriais da W3Schools.
- Os cursos foram desenvolvidos **para fins educacionais**, como material de apoio para estudantes brasileiros autodidatas.
- Em todas as dúvidas e referências ao longo dos notebooks, o site da [W3Schools](https://www.w3schools.com/) é citado como fonte principal de consulta.
- Recomendamos que os alunos consultem diretamente o site da [W3Schools](https://www.w3schools.com/) como complemento aos estudos, especialmente para exercícios adicionais e referência rápida.
- Este projeto não possui vínculo oficial com a W3Schools nem substitui o conteúdo original disponível no site.
