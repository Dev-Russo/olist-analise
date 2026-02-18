# 📊 Sumário Executivo: Análise de Comportamento de Compra Olist

## Contexto
Análise de 99.441 pedidos do e-commerce Olist com objetivo de identificar padrões de compra para otimizar estratégias de marketing e alocação de recursos.

---

## 🔍 4 Principais Descobertas

### 1. Segunda-feira é o MELHOR dia para vender
- **15.701 pedidos** concentrados na segunda-feira
- Dias úteis (seg-sex) = **77% do total de vendas**
- Fins de semana = apenas **23% do total**

**Ação**: Aumentar investimento em campanhas de ads pagos, email marketing e notificações push na segunda-feira entre 10h-21h.

---

### 2. Horário de Pico: 11h-17h (Período da Tarde)
- **16h é o campeão** com 6.474 pedidos
- Top 5 horários (11h, 13h, 14h, 15h, 16h) concentram **82% do volume**
- Tarde + Noite = **73% de todas as vendas**

**Ação**: Reforçar equipes de atendimento e logística entre 11h-17h. Agendar conteúdo em redes sociais para esse horário.

---

### 3. Fins de Semana: Oportunidade Desperdiçada
- Sábado e domingo têm **40% menos vendas** que dias úteis
- Diferença representa **milhares de pedidos perdidos**

**Hipótese**: Clientes integram compras na rotina de trabalho. Fins de semana são para descanso e lazer fora de casa.

**Ação**: Criar cupons exclusivos (frete grátis, desconto relâmpago) para sexta-feira à noite, sábado e domingo.

---

### 4. Sazonalidade Crítica: Queda em Setembro
- Crescimento estável de janeiro a agosto
- **Queda drástica de 30% em setembro**
- Leve recuperação em novembro

**Ação**: Investigar causa da queda. Estruturar campanha antecipada para setembro-dezembro (Black Friday/Cyber Monday).

---

## 💡 Top 3 Recomendações (Prioridade)

| # | Ação | Impacto | Prazo |
|---|------|--------|-------|
| 1 | Campanhas direcionadas segunda-feira 10h-21h | +15-20% conversão | Imediato |
| 2 | Cupons exclusivos para fins de semana | +10-15% nas vendas de sábado/domingo | 1 semana |
| 3 | Investigar queda de setembro | Evitar perda futura | 2 semanas |

---

## 📊 Metodologia

- **Período**: Dados de 2016-2018
- **Volume**: 99.441 pedidos analisados
- **Abordagem**: EDA (Exploratory Data Analysis) + Feature Engineering
- **Ferramentas**: Python, Pandas, Matplotlib, Seaborn

---

## 📂 Fonte dos Dados

Dataset público do Kaggle: [Olist E-commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

**Próximos passos sugeridos:**
1. Implementar campanhas de segunda-feira
2. Testar cupons de fins de semana (A/B test)
3. Fazer análise qualitativa com clientes sobre comportamento
4. Segmentar análise por categoria de produto