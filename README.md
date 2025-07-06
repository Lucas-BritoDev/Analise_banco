# Dashboard de Análise de Dados Bancários

Este projeto implementa um dashboard interativo para análise de dados bancários utilizando Streamlit.

## 🚀 Tecnologias Utilizadas

- **Python** - Linguagem principal
- **Streamlit** - Framework para criação de dashboards web
- **Pandas** - Manipulação e análise de dados
- **NumPy** - Computação numérica
- **Plotly** - Visualizações interativas
- **Statsmodels** - Análise estatística

## 📋 Pré-requisitos

- Python 3.8 ou superior
- Poetry (gerenciador de dependências)

## 🛠️ Instalação

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd analise-banco
```

2. Instale as dependências com Poetry:
```bash
poetry install
```

3. Ative o ambiente virtual:
```bash
poetry shell
```

## 🚀 Executando o Projeto

Para executar o dashboard:

```bash
poetry run streamlit run app.py
```

Ou usando o script configurado:

```bash
poetry run start
```

O dashboard estará disponível em: http://localhost:8501

## 📊 Funcionalidades

- **Geração de dados simulados** - Criação de dados bancários realistas
- **Análise exploratória** - Visualizações e estatísticas descritivas
- **Segmentação de clientes** - Análise por segmentos (Varejo, Premium, Alta Renda, Private)
- **Análise de rentabilidade** - Cálculo de receita, custos e lucro
- **Dashboard interativo** - Interface web responsiva

## 📁 Estrutura do Projeto

```
analise-banco/
├── app.py              # Aplicação principal Streamlit
├── pyproject.toml      # Configuração do Poetry
├── README.md          # Documentação
└── .gitignore         # Arquivos ignorados pelo Git
```

## 🤝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes. 