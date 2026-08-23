# Planejamento de Obra | Engenharia e Produtividade

Aplicação web desenvolvida para apoiar o **planejamento, dimensionamento de equipes e estimativa de duração de atividades em obras**, utilizando coeficientes de produtividade como referência para análises de engenharia e gestão operacional.

O projeto foi desenvolvido com foco em **produtividade, planejamento, padronização de informações e tomada de decisão orientada a dados**, permitindo estruturar atividades da obra e estimar o esforço necessário para sua execução.

## Aplicação

A aplicação está disponível em:

**[Planejamento de Obra | Engenharia e Produtividade](https://silvaniosg.github.io/Planejamento-de-Obra-Engenharia-e-Produtividade/)**

## Objetivo

O objetivo do projeto é disponibilizar uma ferramenta simples e prática para apoiar o planejamento de obras por meio da relação entre:

* Atividades executadas;
* Quantidades previstas;
* Índices de produtividade;
* Composição de equipes;
* Jornada diária de trabalho;
* Horas necessárias para execução;
* Duração estimada da obra.

A proposta é transformar informações técnicas de produtividade em uma visão mais objetiva para **planejamento, acompanhamento e tomada de decisão operacional**.

## Principais funcionalidades

### Cadastro e seleção de atividades

A aplicação permite trabalhar com diferentes atividades da obra, informando:

* Atividade;
* Unidade de medida;
* Quantidade;
* Índice de produtividade em horas por unidade;
* Coeficiente de equipe.

Também é possível inserir novas atividades com seus respectivos coeficientes.

### Coeficientes de produtividade

O sistema utiliza coeficientes de produtividade calibrados tendo como referência **SINAPI e TCPO 2025**, permitindo relacionar a quantidade de serviço ao esforço necessário para sua execução.

Como exemplo, a aplicação apresenta o coeficiente de referência para reboco calibrado:

> 0,24 h/m² — massa fina

Os coeficientes devem ser entendidos como referências para planejamento e podem ser ajustados de acordo com as características específicas de cada obra, equipe, método executivo e condições de produção.

### Formação de equipe

A ferramenta considera a composição da equipe para estimar a capacidade produtiva e apoiar o dimensionamento necessário para execução das atividades.

### Jornada de trabalho

O usuário pode informar a quantidade de horas trabalhadas por dia para realizar a estimativa da duração das atividades.

### Cálculo sequencial do planejamento

Após selecionar as atividades e informar os parâmetros necessários, o sistema calcula uma estimativa da duração da obra considerando a execução sequencial das atividades pela mesma equipe.

## Metodologia

A lógica geral do planejamento considera a relação entre quantidade de serviço, índice de produtividade, composição da equipe e jornada diária.

De forma simplificada:

```text
Horas necessárias = Quantidade × Índice de produtividade

Produção diária = Capacidade da equipe × Jornada diária

Duração estimada = Horas necessárias ÷ Capacidade diária
```

O resultado deve ser utilizado como **estimativa de planejamento**, e não como garantia do prazo real de execução.

Fatores como disponibilidade de materiais, logística, interferências, condições climáticas, restrições de acesso, retrabalho, qualidade da mão de obra, método construtivo e condições específicas do canteiro podem alterar significativamente a produtividade observada.

## Referências

Os coeficientes utilizados no projeto têm como referências principais:

* **SINAPI — Sistema Nacional de Pesquisa de Custos e Índices da Construção Civil**
* **TCPO — Tabelas de Composições de Preços para Orçamentos**

As referências são utilizadas como base para estruturação dos parâmetros de produtividade e devem ser analisadas de acordo com o contexto específico de cada empreendimento.

## Aplicações práticas

A ferramenta pode apoiar atividades relacionadas a:

* Planejamento de obras;
* Engenharia de produção;
* Gestão de operações;
* Dimensionamento de equipes;
* Estimativa de duração;
* Análise de produtividade;
* Planejamento de recursos;
* Gestão de mão de obra;
* Acompanhamento de desempenho;
* Tomada de decisão orientada a dados.

## Tecnologias

O projeto é disponibilizado como uma aplicação web estática, executada diretamente no navegador.

Estrutura atual:

```text
Planejamento-de-Obra-Engenharia-e-Produtividade/
│
├── index.html
├── Gestão_SG.png
└── README.md
```

## Demonstração

A versão publicada pode ser acessada diretamente pelo GitHub Pages:

https://silvaniosg.github.io/Planejamento-de-Obra-Engenharia-e-Produtividade/

## Autor

**Silvanio Gois**
Gestor de Operações e Negócios Orientado a Dados

Profissional com atuação voltada à gestão, operações, produtividade, análise de indicadores e utilização de dados como suporte à tomada de decisão.

### Contato e perfis

**Website**
https://www.silvaniogois.com.br/

**LinkedIn**
https://www.linkedin.com/in/silvanio-gois-6667b918b

**GitHub**
https://github.com/SilvanioSG

## Licença

Este projeto é disponibilizado para fins de estudo, análise, planejamento e aplicação profissional.

Os parâmetros de produtividade e resultados apresentados devem ser avaliados de acordo com as condições específicas de cada empreendimento e não substituem memoriais de cálculo, projetos, especificações técnicas, composições oficiais ou avaliação de profissional habilitado.

---

**Silvanio Gois — Gestão de Operações e Negócios Orientada a Dados**
