# AGENTS.md — Diretrizes para Agentes

## Visão do Projeto

Jupyter Hub é um repositório de ensino com dois cursos completos em português, construídos em Jupyter Notebooks:

1. **Tutorial Jupyter** (16 capítulos) — Ensina a usar a ferramenta Jupyter Notebook
2. **Curso Python** (35 capítulos) — Do básico ao avançado (ML, DSA, Bancos de Dados)

O público-alvo é estudantes brasileiros que querem aprender programação do zero, de forma autodidata.

## Estrutura

```
Jupyter-hub/
├── Tutorial_Jupyter/          # 16 notebooks — Tutorial de Jupyter
│   ├── J00_Index_Jupyter.ipynb
│   ├── J01_...J15_*.ipynb
│   └── README.md
├── Tutorial_Python/           # 35 notebooks — Curso de Python
│   ├── 00_Index.ipynb
│   ├── 01_...35_*.ipynb
│   └── README.md
├── jupyterhub_client.py       # Cliente REST API para JupyterHub
├── requirements.txt
├── .env / .env.example
├── ANALISE_TRILHAS.md         # Análise pedagógica das trilhas
└── W3S_python_Index.md        # Índice de referência W3Schools
```

## Convenções dos Notebooks

- Cada notebook começa com título bilingual (PT + EN)
- Navegação: `[◀ Anterior | 📖 Índice | Próximo ▶]`
- Seções: `🎯 Objetivos` → `📝 Introdução` → `📚 Explicação Detalhada` → `💻 Exemplos` → `📝 Exercícios`
- Código comentado em português
- Terminologia técnica em inglês com tradução entre parênteses

## Regras para Edição

1. **Manter a consistência**: seguir o padrão de seções acima ao adicionar conteúdo
2. **Não quebrar navegação**: ao renomear arquivos, atualizar links em todos os notebooks vizinhos
3. **Preservar o formato JSON**: notebooks são JSON — editsdevem manter a estrutura `cells`, `metadata`, `nbformat`
4. **Python versions**: Tutorial_Jupyter usa 3.10.20, Tutorial_Python usa 3.12.13 (manter consistente por pasta)
5. **Idioma**: explicações em português, código e termos técnicos em inglês

## Pendências Conhecidas

Ver `ANALISE_TRILHAS.md` para detalhes. Prioridades:

- **Alto**: Adicionar projetos integradores (cap 10, 20, 35)
- **Alto**: Incluir exercícios resolvidos em todos os notebooks
- **Alto**: Reescrever capítulos 27-30 (ML) com projeto real
- **Médio**: Adicionar capítulos de Comprehensions e Testing
- **Médio**: Trocar MySQL por SQLite (cap 34-35)
- **Médio**: Limpar artefatos de build na pasta Tutorial_Python/

## Comandos Úteis

```bash
# Instalar dependências
pip install -r requirements.txt

# Iniciar Jupyter
jupyter lab
# ou
jupyter notebook

# Verificar versão do Python
python --version
```
