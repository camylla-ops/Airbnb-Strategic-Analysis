#  Airbnb Strategic Analysis: Identifying Opportunities in Europe  
*Análise de dados para otimização de estratégias no Airbnb*  

---


## Objetivo  
Identificar oportunidades e ameaças para o Airbnb em cidades europeias através de uma análise exploratória (EDA) focada em:  
- Relação entre localização, comodidades e preços.  
- Impacto da avaliação de limpeza na satisfação dos hóspedes.  

---

##  Principais Conclusões  
1. **Localização Estratégica**  
   - Propriedades próximas a metrôs e atrações turísticas têm preços **15-25% mais altos**.  
   - Distância de pontos de interesse reduz significativamente a demanda.  

2. **Limpeza é Prioridade**  
   - Avaliações de limpeza acima de **4.5/5** correlacionam-se com maior taxa de reservas recorrentes.  

3. **Oportunidade de Premiumização**  
   - Anfitriões "Superhost" podem cobrar valores mais altos, com **taxa de ocupação 20% superior**.  

---
 
## Análise Exploratória (Python/pandas)  
- **Tratamento de Dados**:  
  - Limpeza de valores nulos e outliers.  
  - Criação de métricas como "distância até atrações".  
- **Visualizações**:  
  - Gráficos de dispersão (preço x localização).  
  - Heatmaps de densidade de propriedades.  

### Infraestrutura  
- **Armazenamento**: Dados brutos e tratados salvos em Google Drive e Google Cloud Storage.  

---

## ⚙️ Tecnologias Utilizadas  
`Python` `pandas` `Jupyter` `Matplotlib` `Google Cloud Platform`  
## 📌 Dados e Referências  
- **Dataset Original**: [Airbnb Price Determinants in Europe](https://www.kaggle.com/datasets/thedevastator/airbnb-price-determinants-in-europe)  
