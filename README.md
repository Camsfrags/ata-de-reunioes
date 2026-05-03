# ata-de-reunioes

Agent de reunioes para Claude — estrutura pautas, facilita decisoes e gera atas corporativas completas no formato padrao.

## Skill Disponivel

### reunioes

Skill que guia o Claude a atuar como parceiro estrategico no ciclo completo de reunioes:

- **Preparacao**: objetivo, pauta estruturada, checklist de participantes
- **Facilitacao**: tecnicas por tipo de reuniao, DACI para decisoes
- **Pos-Reuniao**: ata no formato padrao, follow-up, rastreamento de acoes

Link direto: [reunioes/SKILL.md](.agents/skills/reunioes/SKILL.md)

## Estrutura da Ata (formato padrao)

```
# ATA DE REUNIAO
[Titulo descritivo]
[Data] | [HH:MM - HH:MM] | [Plataforma]

Participantes / Citados ausentes / Duracao / Transcricao

1. Contexto da Reuniao
2. Decisoes e Alinhamentos (Outcomes)
   2.1 [Tema 1]
   2.2 [Tema 2] ...
3. Insights Estrategicos
4. Riscos Identificados
5. Proximos Passos e Responsaveis
6. Pontos em Aberto
```

## Como usar no Claude

1. Acesse o link da skill acima
2. Copie o conteudo completo do arquivo
3. No Claude, crie um **Project** e cole o conteudo em **Custom Instructions** ou **Project Knowledge**
4. Pronto! O Claude vai gerar atas no formato padrao automaticamente

Para gerar uma ata a partir de uma transcricao (Tactiq, Fireflies, Otter), basta colar a transcricao bruta no chat — o Claude estrutura tudo no formato correto sem precisar de instrucoes adicionais.

## Etapas cobertas

| Etapa | O que o agent faz |
|-------|-------------------|
| Preparacao | Cria pauta, define objetivo, checklist de participantes |
| Facilitacao | Sugere tecnicas por tipo de reuniao, template DACI |
| Pos-Reuniao | Gera ata completa com decisoes, insights, riscos e acoes |
