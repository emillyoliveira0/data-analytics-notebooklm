# 🗄️ SQL para Data Analytics

## 📖 O Papel do SQL em Data Analytics

SQL (Structured Query Language) é uma das principais ferramentas utilizadas por analistas de dados para consultar, filtrar, organizar e analisar informações armazenadas em bancos de dados.

Na área de Data Analytics, o SQL é utilizado para:
- consultar dados
- realizar análises
- gerar relatórios
- identificar padrões
- acompanhar indicadores

O domínio de SQL é considerado uma habilidade essencial para profissionais de dados.

---

# 📊 Principais Comandos SQL

## SELECT

Utilizado para selecionar informações de uma tabela.

```sql
SELECT * FROM vendas;
```

---

## WHERE

Utilizado para filtrar dados.

```sql
SELECT * FROM vendas
WHERE valor > 1000;
```

---

## GROUP BY

Utilizado para agrupar informações.

```sql
SELECT categoria, SUM(valor)
FROM vendas
GROUP BY categoria;
```

---

## ORDER BY

Utilizado para ordenar resultados.

```sql
SELECT * FROM vendas
ORDER BY valor DESC;
```

---

## JOIN

Utilizado para relacionar tabelas.

```sql
SELECT clientes.nome, pedidos.valor
FROM clientes
JOIN pedidos
ON clientes.id = pedidos.cliente_id;
```

---

# 📈 Aplicações do SQL em Data Analytics

SQL pode ser utilizado para:
- análise de vendas
- acompanhamento de KPIs
- análise de comportamento de clientes
- métricas financeiras
- análise operacional

---

# 🚀 Exemplos Práticos

## Análise de faturamento

```sql
SELECT SUM(valor) AS faturamento_total
FROM vendas;
```

---

## Quantidade de clientes

```sql
SELECT COUNT(*) AS total_clientes
FROM clientes;
```

---

## Produtos mais vendidos

```sql
SELECT produto, COUNT(*) AS quantidade
FROM vendas
GROUP BY produto
ORDER BY quantidade DESC;
```

---

# 📌 Principais Aprendizados

Durante os estudos de SQL foi possível compreender:
- importância da organização dos dados
- relação entre consultas e análise de negócio
- uso de filtros para análises mais precisas
- papel do SQL na tomada de decisão baseada em dados

---

# 🧠 Relação com Data Analytics

O SQL possui papel fundamental em Data Analytics porque permite:
- acesso rápido às informações
- análise estruturada de dados
- geração de insights
- construção de relatórios e dashboards

Além disso, muitas ferramentas analíticas utilizam SQL como base para consultas e integração de dados.

---

# 🎯 Conclusão

O SQL é uma das habilidades mais importantes para profissionais da área de dados, sendo amplamente utilizado em:
- Business Intelligence
- análise de dados
- engenharia de dados
- dashboards
- relatórios analíticos

Seu domínio contribui significativamente para análises mais eficientes e estratégicas.
