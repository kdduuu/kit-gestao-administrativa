
# Gestão de Férias

![Projeto Empresarial](https://img.shields.io/badge/Projeto-Empresarial-242424)
![Status](https://img.shields.io/badge/Status-Concluído-228B22)
![Excel](https://img.shields.io/badge/Excel-2019-217346)
![Power Query](https://img.shields.io/badge/Power_Query-M-555555)

Solução empresarial desenvolvida para acompanhamento de períodos de férias, programações, saldos, prazos e pendências de Recursos Humanos.

## Contexto empresarial

Desenvolvido em ambiente profissional para atender demandas reais de gestão de pessoas de uma empresa do setor de logística.

A solução foi desenvolvida para auxiliar a rotina do RH, centralizando informações relacionadas aos períodos de férias e facilitando o acompanhamento das programações.

## Objetivo

Organizar e acompanhar os períodos de férias dos colaboradores, permitindo a identificação de saldos, prazos e pendências, sem comprometer o histórico das informações anteriores.

## Estrutura da solução

A planilha separa os cadastros, períodos de férias, programações, consultas e estruturas técnicas de apoio.

```mermaid
flowchart LR
    A[Colaboradores] --> B[Períodos de férias]
    B --> C[Programações]
    B --> D[Consulta e alertas]
    C --> D
    E[Histórico de migração] --> B
```

## Funcionalidades

- Cadastro e acompanhamento de colaboradores.
- Controle de períodos de férias.
- Registro e acompanhamento de programações.
- Consulta de saldos disponíveis.
- Monitoramento de prazos e alertas.
- Classificação dos períodos por situação.
- Identificação de pendências para conferência pelo RH.
- Preservação do histórico de dados migrados.
- Separação entre operação e estruturas técnicas.

## Tecnologias utilizadas

- Microsoft Excel 2019
- Power Query (linguagem M)
- Fórmulas e funções do Excel
- Validação de dados

## Resultados e competências

- Centralização das informações de férias.
- Organização do histórico de períodos e programações.
- Apoio ao planejamento das atividades do RH.
- Modelagem de estados e regras temporais.
- Migração e tratamento de dados.
- Separação de responsabilidades e qualidade da informação.

## Demonstração

### Consulta de férias

![Consulta de férias](assets/consulta.png)

### Programações

![Programações de férias](assets/programacoes.png)

A versão demonstrativa está disponível neste diretório:

[Gestão de Férias — Excel](GESTÃO%20DE%20FÉRIAS%20-%20PORTFOLIO.xlsx)

O arquivo permite explorar as funcionalidades da solução utilizando colaboradores, períodos e programações fictícias.

## Confidencialidade

Este repositório apresenta uma versão demonstrativa de uma solução desenvolvida em ambiente empresarial.

Os registros disponibilizados são fictícios. Dados pessoais, informações trabalhistas reais e arquivos corporativos originais não fazem parte deste material.
