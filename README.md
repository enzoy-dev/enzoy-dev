# Olá, eu sou o Enzo! 👋

**Desenvolvimento Backend • Python • Inteligência Artificial**

Desenvolvo projetos com Python e SQL, com foco em APIs, bancos de dados, testes automatizados e aplicações de inteligência artificial.

Gosto de transformar ideias em sistemas que possam ser executados, testados e compreendidos — não apenas demonstrados.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/enzo-santos-b2b6aa299)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:enzosouzasantos08@gmail.com)

## Sobre mim

- 🇧🇷 Desenvolvedor em formação, baseado no Brasil.
- 🎓 Estudante de Desenvolvimento de Sistemas.
- 🧠 Interesses principais: backend, engenharia de software e aplicações de IA.
- 🛠️ Trabalho com modelagem de dados, regras de negócio, APIs REST, testes e análise de dados.
- 📈 Busco evoluir construindo projetos reproduzíveis, com documentação clara e decisões técnicas justificadas.

## Tecnologias e ferramentas

### Linguagens e dados

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### Backend, IA e qualidade

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Sentence Transformers](https://img.shields.io/badge/Sentence_Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

Também exploro embeddings, busca vetorial, FAISS, RAG e integração com modelos de linguagem.

## Projetos em destaque

### 🧠 AI Document Search — busca inteligente em PDFs

API de pesquisa semântica e perguntas sobre documentos PDF, desenvolvida com FastAPI, Sentence Transformers, FAISS e Google Gemini.

- Extração de texto com referência às páginas e divisão em trechos.
- Geração de embeddings e recuperação de conteúdo semanticamente relacionado.
- Respostas com identificação das fontes recuperadas.
- Autenticação por chave de API, armazenamento transacional em SQLite e cache vetorial FAISS.
- Testes automatizados, integração contínua e avaliação de recuperação com perguntas em português e inglês.

**Destaque técnico:** o projeto compara modelos de embeddings usando métricas de recuperação. Os resultados são de um conjunto pequeno de avaliação, não uma medida geral de precisão da IA.

[Ver código, documentação e resultados →](https://github.com/enzoy-dev/Ai-document-search)

### 🛒 Sistema de Loja — API e PostgreSQL

Sistema de gestão comercial com PostgreSQL e FastAPI, estruturado em torno de integridade de dados e regras de negócio.

- Cadastro de clientes, categorias e produtos.
- Pedidos com múltiplos itens, descontos e frete.
- Controle de estoque, cancelamento e devolução de unidades.
- Transações atômicas e tratamento de concorrência nas vendas.
- Relatórios SQL, testes de integração com PostgreSQL real e CI com GitHub Actions.

**Destaque técnico:** a lógica evita vendas parciais e testa disputas simultâneas por estoque. A API foi projetada para uso local e ainda não possui autenticação para exposição pública.

[Ver arquitetura e instruções de execução →](https://github.com/enzoy-dev/sistema-loja)

### 📊 Ecommerce Sales — análise de rentabilidade

Análise exploratória de uma amostra histórica de e-commerce usando Python, pandas, Jupyter e Matplotlib.

- 9.994 linhas de vendas analisadas, com faturamento registrado de aproximadamente US$ 2,30 milhões.
- Investigação de margens por categoria, região, produto e desconto.
- Identificação de baixa rentabilidade em móveis e prejuízos concentrados em determinados produtos.
- Notebook reproduzível, verificações de consistência e execução automatizada no GitHub Actions.

**Destaque analítico:** as recomendações distinguem correlações observadas de efeitos causais que os dados não permitem demonstrar.

[Explorar análises, gráficos e conclusões →](https://github.com/enzoy-dev/Ecommerce-sales)

### 🎮 TheMansion — jogo de terror em Python

Jogo narrativo de sobrevivência no terminal, criado para praticar programação orientada a objetos, gerenciamento de estado e lógica de sistemas.

- Exploração, inventário, armas, combate e decisões com consequências.
- Duas rotas de fuga e gerenciamento de recursos.
- Salvamento e carregamento em JSON, com validação de dados.
- Testes de regras, persistência e percursos completos.

**Destaque técnico:** o jogo permite reproduzir eventos aleatórios e preserva o estado do combate ao salvar.

[Conhecer o jogo →](https://github.com/enzoy-dev/TheMansion)

## Como desenvolvo

Procuro aplicar práticas de engenharia que tornam os projetos mais confiáveis:

- **Reprodutibilidade:** instruções de instalação e execução.
- **Testabilidade:** testes automatizados para regras e cenários de falha.
- **Integridade:** validação de entradas, transações e persistência consistente.
- **Documentação:** decisões, limitações e próximos passos descritos com clareza.
- **Evolução contínua:** melhoria gradual da arquitetura e da qualidade do código.

## Contato

- **LinkedIn:** [linkedin.com/in/enzo-santos-b2b6aa299](https://www.linkedin.com/in/enzo-santos-b2b6aa299)
- **E-mail:** [enzosouzasantos08@gmail.com](mailto:enzosouzasantos08@gmail.com)
- **GitHub:** [github.com/enzoy-dev](https://github.com/enzoy-dev)

---

*Construindo, testando e aprendendo — um projeto de cada vez.*

