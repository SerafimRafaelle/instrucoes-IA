# Gerenciamento de Agenda

Sistema de gerenciamento e organização da agenda de estudos orientado à aprendizagem, consistência e desenvolvimento de longo prazo.

## Objetivo

O projeto tem como objetivo gerenciar a agenda de forma precisa, sustentável e orientada ao desenvolvimento de longo prazo, conciliando diferentes dimensões:

* Vestibulares;
* Desenvolvimento técnico na área administrativa e técnológica;
* Preparação profissional comportamental;
* Compromissos pessoais e externos;
* Descanso, recuperação e sustentabilidade.

O gerenciamento prioriza **aprendizagem e consistência**, e não a quantidade artificial de tarefas concluídas.

## Princípios

O funcionamento do gerenciamento é orientado pelos seguintes princípios:

* Integridade e veracidade dos dados;
* Respeito aos compromissos e restrições temporais reais;
* Preservação do sistema de revisões;
* Priorização acadêmica;
* Respeito às dependências pedagógicas;
* Consideração da carga cognitiva e da energia disponível;
* Sustentabilidade da rotina;
* Preservação adequada de pausas, descanso e recuperação.

Quando houver conflito entre objetivos, **qualidade, consistência e sustentabilidade prevalecem sobre quantidade artificial de tarefas**.

## Eixos de desenvolvimento

O gerenciamento organiza a rotina principalmente em três eixos acadêmicos e profissionais:

### Vestibular

O vestibular constitui o eixo de maior prioridade quando existe competição real por tempo ou energia.

A meta atual é estudar e revisar **dois tópicos de vestibular por dia**, entendendo essa quantidade como uma meta flexível. A distribuição deve considerar lacunas, equilíbrio entre áreas, progressão, importância estratégica, carga cognitiva e preparação adequada.

### Desenvolvimento técnico

O desenvolvimento técnico possui como meta atual **um conteúdo técnico novo por dia**, quando houver tempo e energia adequados.

O aprendizado deve priorizar aplicação prática. Em programação e áreas semelhantes, a prática deve prevalecer sobre o consumo ativo/prático de conteúdo.

O ciclo de aprendizagem recomendado é:

**conceito → exemplo → tentativa → erro → correção → nova tentativa → aplicação**

### Preparação profissional

A preparação profissional constitui um eixo independente.

O foco está no desenvolvimento de competências técnicas e comportamentais, comunicação profissional, organização, autonomia, rotinas administrativas, processos empresariais, indicadores, acompanhamento e relacionamento profissional.

No dia-a-dia empresarial, a preparação deve ser adaptada às demandas, ferramentas, processos, dificuldades e lacunas observadas.

A frequência-base definida é de dois blocos por semana, com duração usual de 60–90 minutos.

## Sistema de revisões

O sistema possui dois tipos principais de revisão:

* **Revisão de Vestibular** — conteúdos relacionados à preparação para vestibulares;
* **Revisão Técnica** — conteúdos relacionados ao desenvolvimento técnico.

Quando um conteúdo é efetivamente estudado e o processo de revisão é solicitado, é criado um ciclo composto por:

**D+1 → D+7 → D+21**

São espaçados em três períodos para melhor fixação do conteúdo.

Por padrão, as datas são calculadas utilizando dias corridos a partir da data-base do estudo.

As revisões devem priorizar:

* Recuperação ativa;
* Exercícios;
* Aplicação;
* Resolução de problemas;
* Identificação de lacunas;
* Correção de erros.

Revisões técnicas devem envolver prática sempre que apropriado.

## Organização temporal

O gerenciamento considera a data e o horário atuais no momento de cada solicitação e utiliza o horário e fusohorário local de Brasília (UTC−3).

Compromissos com horário não podem apresentar sobreposição.

Compromissos externos e restrições temporais reais possuem precedência sobre estudos.

Tarefas sem horário permanecem flexíveis e não recebem horário automaticamente.

Quando sessões cognitivas forem consecutivas, utiliza-se **15 minutos de pausa** como padrão.

## Priorização

Quando houver competição real por tempo ou energia, a ordem de prioridade é:

1. Vestibular;
2. Desenvolvimento técnico;
3. Preparação profissional.

Essa prioridade não autoriza sacrificar sono, recuperação ou qualidade da aprendizagem.

## Integridade dos dados

O sistema não deve presumir informações que não foram confirmadas.

Não devem ser inventados ou assumidos:

* Compromissos;
* Estudos realizados;
* Horários;
* Disponibilidade;
* Conclusão de tarefas;
* Eventos duplicados.

Também deve ser distinguido o que foi:

* Efetivamente estudado;
* Parcialmente estudado;
* Apenas iniciado;
* Apenas instalado ou configurado;
* Conhecido superficialmente;
* Apenas sugerido.

**Instalar ou configurar uma ferramenta não equivale automaticamente a estudar seu conteúdo.**

## Reorganização da agenda

Alterações na agenda devem passar por auditoria antes e depois da execução.

A auditoria considera:

* Agenda existente;
* Compromissos;
* Tarefas concluídas e pendentes;
* Revisões;
* Conflitos;
* Duração;
* Energia e sono;
* Carga cognitiva;
* Prioridades;
* Dependências pedagógicas;
* Espaço temporal disponível.

Quando uma reorganização ainda não tiver sido autorizada, a proposta deve apresentar o que será alterado, a justificativa, os horários relevantes, os conflitos encontrados e os critérios utilizados.

Após aprovação explícita, somente a configuração autorizada deve ser executada.

## Sustentabilidade

A agenda deve considerar o estado real da usuária.

Cansaço, sono insuficiente, recuperação de sono, excesso de atividades e baixa energia cognitiva podem justificar redução ou redistribuição da carga.

A agenda deve permanecer sustentável mesmo quando a rotina real não seguir o planejamento original.

## Status do projeto

**Em desenvolvimento.**

As regras operacionais atuais estão documentadas em [`instrucoes/gerenciamento-agenda.md`](instrucoes/gerenciamento-agenda.md).

## Documentação

| Documento                                                                  | Descrição                                    |
| -------------------------------------------------------------------------- | -------------------------------------------- |
| [`instrucoes/gerenciamento-agenda.md`](instrucoes/gerenciamento-agenda.md) | Instruções operacionais do gerenciamento     |
| [`docs/regras.md`](docs/regras.md)                                         | Regras de negócio do sistema                 |
| [`docs/arquitetura.md`](docs/arquitetura.md)                               | Arquitetura técnica do projeto               |
| [`docs/historico.md`](docs/historico.md)                                   | Histórico das decisões e evolução do projeto |
| [`CHANGELOG.md`](CHANGELOG.md)                                             | Registro das alterações do projeto           |

## Fonte operacional

O arquivo `instrucoes/gerenciamento-agenda.md` constitui a **fonte operacional do gerenciamento da agenda**.

Novas regras devem ser analisadas quanto à sua relação com as regras existentes, identificando se adicionam, substituem ou contradizem uma regra anterior.

Regras contraditórias não devem ser aplicadas simultaneamente.
