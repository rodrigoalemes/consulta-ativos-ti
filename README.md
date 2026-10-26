<p align="center">
<img src="assets/capa.png" alt="Consulta de Ativos de TI" width="100%">
</p>

<h1 align="center">Consulta de Ativos de TI</h1>
<p align="center"><i>Histórico de equipamentos corporativos por colaborador, em um só lugar</i></p>

<p align="center">
<img src="https://img.shields.io/badge/Gest%C3%A3o%20de%20Ativos-0EA5E9?style=flat-square" alt="Gestão de Ativos">
<img src="https://img.shields.io/badge/Bases%20Lenovo/Dell-334155?style=flat-square" alt="Bases Lenovo/Dell">
<img src="https://img.shields.io/badge/status-conclu%C3%ADdo-2DD4BF?style=flat-square" alt="status: concluído">
</p>

## Sumário

- [Sobre](#sobre)
- [Problema e solução](#problema-e-solução)
- [Funcionalidades](#funcionalidades)
- [Como funciona](#como-funciona)
- [Tecnologias](#tecnologias)
- [Benefícios](#benefícios)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Autor](#autor)

## Sobre

Ferramenta para **consulta rápida ao histórico de equipamentos corporativos**, reunindo as bases **Lenovo** e **Dell**. Agiliza o atendimento e a recuperação de informações de ativos por colaborador, apoiando a **gestão do ciclo de vida dos ativos de TI**.

> [!NOTE]
> Projeto desenvolvido em ambiente corporativo. O código-fonte e os dados não são publicados por conterem informações internas; este repositório documenta o problema, a solução e o funcionamento.

## Problema e solução

| | |
| --- | --- |
| **Problema** | As informações de equipamentos ficavam espalhadas em bases diferentes, e encontrar o histórico de um colaborador tomava tempo do atendimento. |
| **Solução** | Uma consulta centralizada: informa-se o colaborador e a ferramenta retorna os equipamentos associados a ele nas bases Lenovo e Dell. |

## Funcionalidades

- Consulta centralizada por colaborador
- Reúne as bases de equipamentos Lenovo e Dell
- Histórico dos equipamentos associados a cada pessoa
- Apoio ao atendimento e ao ciclo de vida dos ativos

## Como funciona

```mermaid
flowchart LR
    A[Base Lenovo] --> C[Consulta centralizada]
    B[Base Dell] --> C
    U[Busca por colaborador] --> C
    C --> R[Histórico de equipamentos]
    R --> S[Atendimento e gestão do ciclo de vida]
```

Detalhes: [Como funciona](docs/como-funciona.md)

## Tecnologias

| Tecnologia | Uso no projeto |
| --- | --- |
| Bases Lenovo/Dell | Fonte do histórico de equipamentos |
| Consulta centralizada | Busca única por colaborador |

## Benefícios

- Menos tempo de pesquisa no atendimento
- Informação de ativos centralizada
- Apoio à gestão do ciclo de vida dos equipamentos

## Estrutura do repositório

```text
consulta-ativos-ti/
├── assets/
│   └── capa.png
├── docs/
│   └── como-funciona.md
└── README.md
```

## Autor

**Rodrigo Lemes** · Analista de TI · Microsoft 365, AD/Entra ID, Automação, Power BI e IA aplicada

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rodrigo%20Lemes-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rodrigoalemes/)
[![GitHub](https://img.shields.io/badge/GitHub-rodrigoalemes-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/rodrigoalemes)
