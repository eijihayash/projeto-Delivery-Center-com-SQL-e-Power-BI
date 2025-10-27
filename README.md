# Projeto Delivery Center com SQL e Power-BI

## Descrição
Este projeto tem como objetivo explorar, tratar e analisar os dados do **Delivery Center**, incluindo pedidos, entregas, pagamentos, lojas, canais, hubs e motoristas.  
O foco é fornecer insights sobre operações de delivery, pagamentos e performance de entregas, utilizando **SQL** para tratamento e **Power BI** para visualização.

---

## Tecnologias e Ferramentas
- **SQL Server**: consultas, análise exploratória e criação de views.
- **Power BI**: criação de dashboards e visualizações.

---

## Estrutura do Projeto
/projeto-delivery-center

│

├─ views/            # Views criadas no SQL Server para cada tabela relevante

├─ queries/          # Consultas SQL utilizadas na análise exploratória

└─ README.md         # Documentação do projeto

---

## Views Criadas
- **vw_orders**: Informações sobre pedidos (`order_id`, `store_id`, `order_status`, valores, datas, etc.)
- **vw_deliveries**: Informações de entregas, status e motorista registrado.
- **vw_payments**: Detalhes de pagamentos e status.
- **vw_channels**: Informações sobre canais de pedido.
- **vw_stores**: Informações das lojas, incluindo localização e segmentação.
- **vw_drivers**: Informações sobre motoristas.
- **vw_hubs**: Localização dos hubs e informações gerais.

---
## Objetivo dos Dashboards

## Dashboards Criados

### Página 1 – Visão Geral de Receita
![Dashboard Receita](images/dashboard1.png)

### Página 2 – Taxa de Cancelamento
![Dashboard Cancelamento](images/dashboard2.png)


- **Em andamento**

