# 📊 Projeto 1: Análise de Comportamento de Compra - Olist E-commerce

## 🎯 Problema de Negócio

Analisar **quando e como os clientes compram** no e-commerce Olist para gerar insights acionáveis que otimizem estratégias de marketing, alocação de recursos e campanhas promocionais.

---

## 📈 Principais Descobertas

### 1️⃣ Segunda-feira é o MELHOR dia da semana
- **15.701 pedidos** concentrados na segunda-feira
- Dias úteis (segunda a sexta) representam **~77% de todas as vendas**
- Fins de semana caem drasticamente (**-40% vs dias úteis**)

**Por quê?** Clientes priorizam compras durante horário comercial, integrando atividades de compra na rotina de trabalho. Fins de semana são destinados a descanso e atividades fora de casa.

---

### 2️⃣ Horário de Pico é entre 11h e 17h (Tarde)
- **16h é o horário campeão** com 6.474 pedidos
- Top 5 horários (11h, 13h, 14h, 15h, 16h)
- Período da tarde + noite = **~73% de todas as vendas**

**Curiosidade:** O volume é muito uniforme entre 11h-16h, demonstrando que clientes navegam e compram de forma consistente durante o expediente.

---

### 3️⃣ Sazonalidade Crítica: Queda em Setembro
- Crescimento estável entre janeiro e agosto
- **Queda brusca de 30% em setembro**
- Leve recuperação em novembro

**Oportunidade:** Investigar o que causou essa queda para evitar que se repita. Pode ser relacionado ao calendário, economia ou fatores externos.

---

### 4️⃣ Fins de Semana são Oportunidade Desperdiçada
- Sábado e domingo representam apenas **~23% do total**
- Se equilibrados, teriam ~30% (15% por dia)
- Diferença representa **milhares de pedidos perdidos**

**Recomendação:** Criar estratégia específica para fins de semana (cupons relâmpago, frete grátis) para equilibrar a demanda.

---

## 💡 Recomendações Estratégicas

### ✅ Curto Prazo (Imediato)
1. **Campanhas de Segunda-feira**: Aumentar investimento em ads pagos, email marketing e notificações push na segunda-feira entre 10h-21h
2. **Reforço Operacional**: Ampliar equipes de atendimento e logística entre 11h-17h para não perder vendas por atraso
3. **Cupons para Fins de Semana**: Oferecer descontos ou frete grátis para sexta-feira à noite, sábado e domingo

### 📊 Médio Prazo (1-2 meses)
1. **Investigar Setembro**: Fazer análise qualitativa sobre o que causou a queda de vendas
2. **Venda Cruzada**: Implementar recomendações de produtos em dias de alto fluxo (segunda-feira)
3. **Segmentação por Período**: Entender se produtos diferentes vendem melhor em horários diferentes

### 🎯 Longo Prazo (3+ meses)
1. **Planejamento de Campanhas**: Estruturar calendário de Black Friday e Cyber Monday para setembro-dezembro
2. **Análise Qualitativa de Clientes**: Pesquisar por que fins de semana têm menos vendas
3. **Teste A/B**: Validar se as recomendações realmente aumentam conversão


---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Manipulação e análise de dados
- **Matplotlib & Seaborn** - Visualização de dados
- **Jupyter Notebook** - Ambiente de análise

---

## 📊 Resumo das Análises

| Semana | Objetivo | Resultado |
|--------|----------|-----------|
| **Dia 1** | Setup, Limpeza e EDA | ✅ Dados auditados e limpos |
| **Dia 2** | Features Temporais | ✅ Padrões identificados |
| **Dia 3** | Visualizações | ✅ Insights documentados |
| **Dia 4** | Documentação e GitHub | ✅ Em progresso |

---

## 🚀 Como Rodar o Projeto

### Pré-requisitos
- Python 3.7+
- Pip ou Conda
- Git

### Passo a Passo

1. **Clone o repositório**
   git clone https://github.com/[seu-usuario]/projeto-olist.git
   cd projeto-olist

2. **Crie um ambiente virtual**
    python -m venv venv
    Linux e Mac: source venv/bin/activate 
    No Windows: venv\Scripts\activate

3. **Instale as dependências**
    pip install -r requirements.txt

4. **Abra o Jupyter Notebook**
    jupyter notebook

5. **Execute os notebooks em ordem**
    Primeiro: 01_eda_initial.ipynb
    Depois: 02_temp_feature.ipynb
    Por último: 03_visual_storytelling.ipynb

## 📥 Fonte dos Dados

O dataset foi obtido do **Kaggle** no link: [Olist E-commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Este é um dataset público contendo informações reais de transações de um marketplace brasileiro de 2016 a 2018.

### Tabelas do Dataset:
- **olist_orders_dataset.csv** - Informações dos pedidos
- **olist_order_items_dataset.csv** - Itens de cada pedido
- **olist_order_payments_dataset.csv** - Pagamentos dos pedidos
- **olist_customers_dataset.csv** - Dados dos clientes (não utilizado neste projeto)
- **olist_products_dataset.csv** - Catálogo de produtos (não utilizado)
- **olist_sellers_dataset.csv** - Dados dos vendedores (não utilizado)

---

## 📬 Contato

- **GitHub**: [@Dev-Russo](https://github.com/Dev-Russo)
- **LinkedIn**: [Murilo Russo](https://www.linkedin.com/feed/)
- **Email**: murilo.russo@outlook.com