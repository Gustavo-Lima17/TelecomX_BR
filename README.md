# TelecomX_BR
Análise Exploratória de Dados (EDA) focada em retenção de clientes e churn.
# 📊 Análise de Evasão de Clientes (Churn) - TelecomX

![Status](https://img.shields.io/badge/Status-Concluído-green)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Lib](https://img.shields.io/badge/Lib-Pandas%20|%20Seaborn-orange/matplotlib)

## 📝 Descrição do Projeto
Este projeto consiste em uma Análise Exploratória de Dados (EDA) sobre uma base de clientes de uma empresa de telecomunicações. O objetivo principal foi identificar padrões de comportamento e descobrir quais fatores levam os clientes a cancelar o serviço (**Churn**).

A análise foca em responder perguntas de negócio como:
* Qual perfil de cliente tem maior tendência a sair?
* O preço da mensalidade influencia a decisão?
* Serviços adicionais (como suporte técnico) ajudam na fidelização?

## 📂 Estrutura da Análise
O notebook percorre as seguintes etapas:
1.  **Limpeza de Dados:** Tratamento de valores nulos, conversão de tipos (ex: `TotalCharges`) e tradução de colunas.
2.  **Análise Univariada:** Estudo da distribuição de churn, tipos de contrato e métodos de pagamento.
3.  **Análise Bivariada:** Relação entre Evasão e variáveis como Tecnologia (Fibra/DSL) e Preço.
4.  **Matriz de Correlação:** Validação estatística das variáveis que mais impactam o cancelamento.
5.  **Insights e Recomendações:** Plano de ação baseado em dados.

## 💡 Principais Insights (Conclusão)
A partir da análise, identificamos que a taxa de evasão é de **26,5%**, impulsionada por três pilares:

1.  **Fragilidade no Contrato Mensal:** Clientes com contratos de curto prazo (mês a mês) representam a maior fatia de cancelamentos.
2.  **Tecnologia DSL e Fibra:** Há uma obsolescência percebida no DSL (clientes antigos saindo) e uma alta sensibilidade a preço na Fibra Óptica.
3.  **O Papel do Suporte:** A ausência de **Suporte Técnico** dobra a probabilidade de churn. Clientes que contratam serviços de proteção tendem a ser muito mais fiéis.

## 🛠️ Tecnologias Utilizadas
* **Python** (Linguagem principal)
* **Pandas** (Manipulação e limpeza de dados)
* **Matplotlib & Seaborn** (Visualização de dados)
* **Numpy** (Cálculos matemáticos)

## 🚀 Como Executar o Projeto

1. Clone o repositório:
```bash
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
