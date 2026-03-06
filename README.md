# Monitor de Mercado - OBInvest

Aplicativo em **Streamlit** para visualização de indicadores macroeconômicos brasileiros, projeções do mercado e simulação de rentabilidade de investimentos.

O app foi desenvolvido com foco educacional para apoiar a compreensão de variáveis econômicas centrais, como **Selic, IPCA, IGP-M, dólar e PIB**, além de oferecer uma calculadora simples de projeção financeira.

---

## Funcionalidades

### 1. Dados Macroeconômicos
Painel com os principais indicadores da economia brasileira:

- **Taxa Selic**
- **IPCA**
- **Juro Real**
- **Dólar PTAX**
- **IGP-M**
- **PIB projetado pelo Focus**

O painel permite:

- visualizar cards com valores atualizados;
- acessar gráficos históricos por indicador;
- filtrar o período de análise;
- consultar uma tabela resumida com dados recentes.

### 2. Calculadora de Rentabilidade
Simulador de investimento com três modalidades:

- **Pós-fixado (CDI)**
- **IPCA +**
- **Pré-fixado**

O usuário pode informar:

- aporte inicial;
- aporte mensal;
- prazo em anos;
- tipo de indexador.

O app calcula:

- total investido;
- saldo bruto projetado;
- rendimento acumulado;
- evolução do patrimônio ao longo do tempo.

### 3. Glossário
Seção educativa com definições simples de conceitos importantes do mercado financeiro, como:

- Selic
- IPCA
- PIB
- CDI
- IGP-M
- Dólar PTAX
- Pós-fixado
- Pré-fixado
- Híbrido (IPCA+)

---

## Fontes de dados

O aplicativo utiliza dados públicos das seguintes fontes:

- **Banco Central do Brasil (SGS)**  
  Séries históricas de indicadores econômicos.

- **Banco Central do Brasil (Focus)**  
  Expectativas de mercado para inflação e PIB.

Bibliotecas utilizadas:
- `python-bcb`
- `pandas`
- `plotly`
- `streamlit`

---

## Estrutura do projeto

```bash
.
├── appy2.py
├── requirements.txt
└── README.md
