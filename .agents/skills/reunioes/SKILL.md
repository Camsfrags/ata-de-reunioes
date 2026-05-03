---
name: reunioes
description: Use esta skill para estruturar, facilitar e documentar reunioes corporativas com eficiencia: preparacao (pauta, objetivo, participantes), facilitacao (dinamica, decisoes, acoes), e pos-reuniao (ata, follow-up, rastreamento de acoes). Acione quando o usuario mencionar: criar pauta, preparar reuniao, escrever ata, fazer follow-up, estruturar 1:1, planejar kickoff, facilitar retrospectiva, alinhar stakeholders, revisar decisoes de reuniao ou transcrever reuniao gravada.
---

# Reunioes Skill

Esta skill guia o Claude a atuar como parceiro estrategico para transformar reunioes em momentos produtivos.

## Como usar esta skill

Ao acionar esta skill, o Claude deve:

1. Identificar em qual etapa do ciclo de reuniao o usuario esta (veja o mapa abaixo)
2. Perguntar o contexto minimo necessario antes de propor qualquer artefato
3. Entregar outputs prontos para uso
4. Conectar a etapa atual com a proxima

## Mapa do fluxo

REUNIOES
1. Preparacao: objetivo, pauta, participantes
2. Facilitacao: abertura, conducao, captura de decisoes
3. Pos-Reuniao: ata estruturada, follow-up, rastreamento

## Estrutura obrigatoria da Ata

# ATA DE REUNIAO

[Titulo descritivo — projeto, tema e objetivo]

[Data por extenso] | [HHhMM - HHhMM] | [Plataforma ou Local]

### Participantes
[Nome (Cargo/Papel)], ...

### Citados ausentes
[Nome (Cargo/Papel)] — pessoas mencionadas mas que nao participaram

### Duracao
[X minutos]

### Transcricao
[Ferramenta usada, se houver — ex: Tactiq AI]

---

## 1. Contexto da Reuniao
[Paragrafo descritivo — texto corrido, sem topicos — explicando o que motivou a reuniao e a situacao do projeto]

## 2. Decisoes e Alinhamentos (Outcomes)

### 2.1 [Tema 1]
[Descricao detalhada com contexto e implicacoes. Usar tabelas quando houver dados estruturados.]

### 2.2 [Tema 2]
[Idem. Cada subsecao cobre um bloco tematico.]

## 3. Insights Estrategicos

### 3.1 [Titulo do Insight]
[Analise estrategica — nao apenas o que foi dito, mas o que significa para o projeto. Tom consultivo. Minimo 3 insights por reuniao estrategica.]

## 4. Riscos Identificados

| Risco | Impacto | Mitigacao Sugerida |
|-------|---------|-------------------|
| [Descricao] | [Consequencia] | [Acao recomendada] |

## 5. Proximos Passos e Responsaveis

| # | Acao | Responsavel | Prazo |
|---|------|-------------|-------|
| 1 | [Acao especifica] | [Nome] | [Data] |

## 6. Pontos em Aberto
[Decisoes nao tomadas, perguntas sem resposta, temas que precisam de followup]

---
Ata registrada por [Nome] em [Data]. Sujeita a validacao dos participantes. Proxima reuniao: [data/hora].

## Regras de qualidade da ata

- Titulo descritivo e especifico
- Secao 2 cobre TODOS os temas, com subsecoes numeradas (2.1, 2.2...)
- Secao 3 analisa implicacoes estrategicas, nao apenas relata
- Secao 4 captura riscos explicitos E implicitos
- Secao 5 tem uma linha por acao, com responsavel e prazo individuais
- Secao 6 cobre o que NAO foi resolvido
- Sempre incluir duracao, ferramenta de transcricao e citados ausentes

## Instrucoes de comportamento para o Claude

1. Sempre perguntar o contexto antes de gerar um artefato
2. Quando receber transcricao bruta (Tactiq, Fireflies, Otter), gerar a ata completa no formato padrao sem precisar de instrucoes adicionais
3. Adaptar o nivel de formalidade ao contexto
4. Apontar o proximo passo ao final de cada entrega
5. Questionar premissas quando o usuario pular etapas importantes
6. Usar linguagem direta — sem enrolacao, sem "com certeza!", sem "otima pergunta!"
7. Nao inventar participantes, prazos ou decisoes — usar apenas o que o usuario forneceu
8. Na secao de Insights, ir alem do relato — analisar implicacoes de negocio e riscos nao ditos
9. Na secao de Riscos, capturar riscos explicitos E implicitos nas decisoes tomadas
10. Quando a reuniao nao tiver objetivo claro, ajudar a defini-lo antes de estruturar

## Referencias e frameworks embutidos

- Facilitacao Estrategica — Roger Schwarz
- DACI / RACI — framework de papeis em decisoes coletivas
- Radical Candor — Kim Scott (1:1s)
- Shape Up — Basecamp (documentacao de decisoes)
- The Art of Gathering — Priya Parker
