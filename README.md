# Modelo Relacional de um BSS para uma Telefonia Móvel

## Visão Geral
Este projeto apresenta um **modelo de dados para um Business Support System (BSS) de uma telefonia móvel**, projetado para simular as operações centrais de uma operadora móvel. O modelo cobre assinantes, planos, pacotes, serviços, faturamento, recargas e registro de uso, fornecendo uma base para compreender as operações de telecomunicações a nível de banco de dados.

## Objetivo
O principal objetivo deste projeto é explorar a **arquitetura e funcionamento dos sistemas de telecomunicações**, incluindo como os dados dos assinantes, pacotes de serviços, saldos e detalhes de uso interagem em um ambiente de rede móvel. Além disso, demonstra a aplicação prática de **modelagem relacional em MySQL**, com relações e integridade referencial.

## Principais Funcionalidades
- Gestão de **assinantes**, incluindo IMSI, MSISDN e status da conta.  
- Representação de **planos**, **pacotes** e **serviços** (voz, SMS, dados).  
- Acompanhamento de **assinaturas**, **carteiras digitais (wallets)**, **recargas** e **transações de pacotes**.  
- Registro de **CDRs (Call Detail Records)** e uso de serviços, incluindo histórico detalhado de transações.  
- Implementação de **tarifas, rating e lógica de faturamento**, refletindo operações reais de telecom.  
- Suporte a **modelos pré-pagos e pós-pagos**, incluindo atualização de saldos e expiração de pacotes.  
- Estrutura modular que permite **extensão e análise de processos de telecom**.

## Tecnologias
- **Banco de Dados:** MySQL (com engine InnoDB)  
- **Ferramenta de Modelagem:** MySQL Workbench 

## Estrutura do Banco de Dados
- **Assinantes e Contas:** Armazena informações de identidade do assinante e status da conta.  
- **Planos e Pacotes:** Define planos pré e pós-pagos, categorias de pacotes e serviços associados.  
- **Serviços e Uso:** Controla o consumo de voz, SMS e dados através de registros detalhados.  
- **Carteiras e Transações:** Gerencia créditos, recargas, transferências e histórico financeiro.  
- **Faturamento e Tarifas:** Calcula custos de uso com base em tarifas e regras de negócio.