<br>

# Especificação CMTAT Solana v1.0.0

<br>

[**Document**](https://github.com/Quantum-Software-Development/solana-atlas-quantum-hub/blob/ff78c94c220f10b6979b8175afe058145359cb57/CMTAT%20Solana%20Specification%20v1.0.0.pdf)

[**Repositório de Referência:**](https://github.com/CMTA/CMTAT-Solana)

<br>

## Visão Geral

A **Especificação CMTAT Solana v1.0.0** define as diretrizes funcionais e técnicas para a implementação de **tokens de segurança compatíveis com CMTAT** na **blockchain Solana**, aproveitando as capacidades avançadas das **extensões SPL Token-2022**.

CMTAT (CMTA Standard Token for Securities) é um **padrão aberto e independente de blockchain**, projetado para a tokenização de instrumentos financeiros como ações, dívidas, produtos estruturados e outros valores mobiliários transferíveis.
Esta especificação explica como os recursos obrigatórios e opcionais do CMTAT podem ser implementados nativamente na Solana.

<br>


## Principais Destaques

* Mapeamento das **funcionalidades principais e opcionais do CMTAT** para a arquitetura de tokens da Solana
* Comparação detalhada com a **implementação em EVM/Solidity** do CMTAT
* Guia prático de **implantação usando SPL Token (Token-2022)**
* Exemplos passo a passo de CLI para criar, gerenciar e administrar tokens compatíveis
* Suporte nativo para **compliance, aplicação de regras e controles administrativos**


<br>


## Tópicos Abrangidos

### [Arquitetura & Padrões]()

* Visão geral do framework CMTAT
* Programa de Token da Solana (Original) vs Token-2022
* Extensões de mint e contas
* Metadados de tokens e dados de compliance on-chain



### [Mapeamento Funcional]()

* Transferências, mint e queima (burn)
* Transferências forçadas e queimas forçadas (Delegado Permanente)
* Congelamento e descongelamento de contas
* Pausa e retomada da atividade do token
* Desativação do token e encerramento do mint



### [Comparação com EVM / Solidity]()

* Diferenças no controle de acesso
* `approve` do ERC-20 vs autoridade delegada na Solana
* Semântica de pausa (comportamento de mint/queima)
* Flexibilidade de metadados
* Mecanismos de aplicação e congelamento



### [Guia de Implantação (Token-2022)]()

* Configuração local da Solana
* Gerenciamento de keypair e autoridades
* Criação de token com extensões obrigatórias
* Inicialização e atualização de metadados
* Minting, transferências, queimas e operações forçadas
* Lista branca via Estado Padrão da Conta
* Desativação do token e encerramento do mint


<br>

## Por que Solana para CMTAT

* Layer 1 de alta performance otimizado para mercados de capitais
* Execução paralela nativa e finalização determinística
* Arquitetura de metadados flexível
* Suporte incorporado para controles avançados de token sem contratos inteligentes personalizados


<br>

## Casos de Uso

* Emissão de tokens de segurança regulamentados
* Tokenização de ações e instrumentos de dívida
* Mercados permissionados ou semi-permissionados
* Infraestruturas de ativos digitais guiadas por compliance



<br>

> *CMTA — Construindo padrões abertos para valores digitais compatíveis.*
