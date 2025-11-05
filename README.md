# Challenge_Data_Science

# 🏪 Análise de Performance das Lojas - Challenge Data Science

Bem-vindo! Este projeto é um **desafio de Data Science** para alunos iniciantes aprenderem análise de dados com Python e Pandas.

---

## 📋 O que é este projeto?

Você tem um conjunto de dados com informações de **4 lojas** (vendas, avaliações de clientes, custos de frete, categorias de produtos, etc.) e precisa analisar qual loja deveria ser vendida para otimizar os negócios.

**Objetivo:** Usar Python para analisar dados e tomar uma decisão baseada em indicadores de performance.

---

## 📊 O que você vai aprender

- ✅ Importar dados com Pandas
- ✅ Calcular métricas importantes (somas, médias, percentuais)
- ✅ Comparar dados entre grupos
- ✅ Visualizar resultados
- ✅ Tomar decisões baseadas em dados

---

## 📁 Estrutura dos Dados

O projeto contém dados de 4 lojas em arquivos CSV:

```
base-de-dados-challenge-1/
├── loja_1.csv  → Dados da Loja 1
├── loja_2.csv  → Dados da Loja 2
├── loja_3.csv  → Dados da Loja 3
└── loja_4.csv  → Dados da Loja 4
```

---

## 🚀 Como começar

### 1️⃣ Pré-requisitos

Certifique-se que você tem instalado:
```bash
pip install pandas
```

---

## 💡 Dicas para Iniciantes

**Função úteis do Pandas:**
```python
df.sum()           # Soma os valores de uma coluna
df.mean()          # Calcula a média
df.min() / df.max() # Valor mínimo/máximo
df.describe()      # Resumo estatístico
df.groupby()       # Agrupa dados por categoria
```

**Salvando seu resultado:**
```python
# Criar um DataFrame e salvar como CSV
resultado = pd.DataFrame({'Loja': [1,2,3,4], 'Faturamento': [...]})
resultado.to_csv('resultado.csv', index=False)
```

---

## 📌 Recomendação Final

Com base na análise dos dados:

| Métrica | Loja 1 | Loja 2 | Loja 3 | Loja 4 |
|---------|--------|--------|--------|--------|
| **Faturamento** | R$ 1.534.509 | R$ 1.488.459 | R$ 1.464.025 | R$ 1.384.498 |
| **Avaliação** | 3.98 ⭐ | 4.04 ⭐ | 4.05 ⭐ | 4.00 ⭐ |
| **Frete Médio** | R$ 34.69 | R$ 33.62 | R$ 33.07 | R$ 31.28 |

**Decisão:** Vender a **Loja 4** (menor faturamento) para investir em lojas mais lucrativas.

---

## 📚 Recursos para Aprender Mais

- [Documentação Pandas](https://pandas.pydata.org/docs/)
- [Python para Data Science - Curso Alura](https://www.alura.com.br)
- [Real Python - Pandas Tutorial](https://realpython.com/learning-paths/pandas-data-science/)

---

## 📝 Licença

Este projeto é de código aberto. Use livremente para aprender!

---
