# 📊 Dashboard de Vendas - Power BI

Projeto desenvolvido para análise de desempenho de e-commerce fictício.

## 🛠️ Recursos Utilizados
- **Transformação de dados**: Power Query
- **Medidas**: DAX (Total de Vendas)
- **Visualizações**: Mapas, KPIs, Gráficos temporais

## ⚙️ Como Executar
1. Baixe o arquivo `.pbix`
2. Abra no Power BI Desktop
3. Atualize a fonte de dados se necessário (em `Home > Transformar dados`)

## 📊 Métricas Principais
```dax
Total Vendas = SUM(Vendas[Quantidade]) * SUM(Vendas[Valor Unitário])
```
