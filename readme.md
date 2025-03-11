# Desafio DIO: Dataset GameShop

## Descrição do Projeto

Este projeto faz parte do desafio DIO intitulado "dataset-gamesshop". O objetivo é analisar os dados de vendas dos consoles Meganium, fabricados pela nossa empresa. Vale ressaltar que a empresa foca exclusivamente na fabricação de consoles, deixando a distribuição e a venda para terceiros. Os produtos são vendidos globalmente.

## Dados Utilizados

Os dados utilizados para a análise são fornecidos pela empresa e incluem informações como:
- SKU (identificador único do produto)
- Produto vendido
- Data da venda
- Quantidade vendida
- Preço unitário
- Preço total
- Moeda da transação
- Site de venda
- Valor do cupom de desconto
- Data de nascimento do comprador
- Nome do comprador
- País de entrega
- ID da fatura

## Análises Realizadas

### Número Total de Vendas por Produto

| Produto                | Número Total de Vendas |
|------------------------|-------------------------|
| NEW MEGANIUM RG35XX    | 8                       |
| NEW MEGANIUM RG28XX    | 11                      |
| NEW MEGANIUM RG CubeXX | 10                      |
| NEW MEGANIUM RG 40XXV  | 11                      |
| MEGANIUM RG353M        | 9                       |

### Produto Mais Vendido e Menos Vendido por País

| País       | Produto Mais Vendido       | Quantidade | Produto Menos Vendido     | Quantidade |
|------------|----------------------------|------------|---------------------------|------------|
| Austrália  | NEW MEGANIUM RG CubeXX     | 8          | NEW MEGANIUM RG28XX       | 1          |
| Canadá     | NEW MEGANIUM RG 40XXV      | 5          | NEW MEGANIUM RG28XX       | 1          |
| Alemanha   | NEW MEGANIUM RG28XX        | 4          | NEW MEGANIUM RG 40XXV     | 1          |
| França     | NEW MEGANIUM RG35XX        | 7          | NEW MEGANIUM RG28XX       | 1          |
| Japão      | NEW MEGANIUM RG 40XXV      | 6          | MEGANIUM RG353M           | 1          |
| Reino Unido| NEW MEGANIUM RG35XX        | 4          | MEGANIUM RG353M           | 2          |
| EUA        | MEGANIUM RG353M            | 3          | NEW MEGANIUM RG28XX       | 1          |

### Média das Vendas por Produto

| Produto                | Média de Vendas |
|------------------------|------------------|
| NEW MEGANIUM RG35XX    | 3                |
| NEW MEGANIUM RG28XX    | 2.5              |
| NEW MEGANIUM RG CubeXX | 2.2              |
| NEW MEGANIUM RG 40XXV  | 2.9              |
| MEGANIUM RG353M        | 2.7              |

## Ferramentas Utilizadas

- Python para análise de dados
- Bibliotecas como Pandas e Matplotlib para manipulação e visualização de dados
- COPILOT - prompts

## Conclusão

A análise dos dados de vendas dos consoles Meganium revelou insights valiosos sobre os produtos mais e menos vendidos por país, além da média das vendas por produto. Esse tipo de análise é crucial para a empresa tomar decisões informadas sobre a fabricação e o fornecimento de seus consoles.

---

**Observação**: Este README foi criado para o desafio DIO e pode ser ajustado conforme necessário para incluir mais detalhes ou análises futuras.
