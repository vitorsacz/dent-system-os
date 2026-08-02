---
name: roteiro-conteudo
description: >
  Gera pauta semanal de ideias pra Instagram (posts + stories) com roteiro de vídeo pronto pra
  cada uma — gancho, o que falar, CTA. Pensada pra quem já sabe gravar mas trava na ideia e na
  estrutura da fala. Use quando o usuário disser "ideias pro instagram", "não sei o que postar",
  "pauta de conteúdo", "roteiro pra stories", "roteiro de vídeo", "o que gravar essa semana",
  ou "/roteiro-conteudo".
---

# /roteiro-conteudo — Pauta semanal + roteiro de vídeo

Resolve o "tenho câmera e estrutura mas não tenho ideia nem sei o que falar". Entrega ideias
já prontas pra gravar, não só temas soltos.

## Dependências

- **Negócio e gargalo:** `_memoria/empresa.md`, `_memoria/estrategia.md` (o que a produção de
  conteúdo deve atacar primeiro — hoje, captação de pacientes)
- **Tom de voz:** `_memoria/preferencias.md` — calibrar toda ideia e roteiro por aqui, incluindo
  o que evitar (nada apelativo)

---

## Workflow

### Passo 1 — Tema da semana

Perguntar:
> "Tem alguma dúvida de paciente, procedimento ou situação específica que você quer abordar essa
> semana? Ou prefere que eu gere as ideias do zero com base no que você atende?"

Se o usuário passar um tema/dúvida → usar como âncora de pelo menos 1-2 das ideias.
Se não passar nada → gerar do zero com base em `_memoria/empresa.md` (procedimentos, perfil de
paciente) e no gargalo de `_memoria/estrategia.md`.

### Passo 2 — Gerar 5 ideias

Variar o tipo pra não ficar repetitivo — misturar entre:
- **Educativo** — tira dúvida ou desmistifica medo comum (o exemplo de tom em
  `_memoria/preferencias.md` é esse formato: parte de um pensamento do paciente, responde com
  informação real)
- **Antes/depois ou caso real** — sem prometer resultado, mostrando processo
- **Bastidor** — rotina da clínica, o dia a dia, humaniza
- **Prova social** — o que pacientes costumam dizer depois de tratar
- **CTA direto** — convite objetivo pra agendar avaliação (sem apelação, sem urgência forçada)

Cada ideia numa linha curta, tipo manchete.

### Passo 3 — Roteiro de vídeo pra cada ideia

Pra cada uma das 5 ideias, escrever um roteiro pronto de fala, estruturado em:

```
### [nome da ideia]

**Gancho (primeiros 3s):** [frase que trava o dedo do paciente na tela — pergunta ou afirmação
que gera identificação, no tom de preferencias.md]

**Corpo:** [o que falar, em ordem, frases curtas e naturais — como se estivesse explicando pro
paciente na cadeira, não lendo um roteiro]

**Fechamento/CTA:** [como encerrar — direto quando fizer sentido pro gargalo de captação, sem
soar apelativo]

**Duração estimada:** [15-30s / 30-60s]
```

Roteiro é pra ser falado, não lido — frases curtas, sem jargão técnico sem explicar.

### Passo 4 — Salvar

Salvar em `marketing/conteudo/roteiro-<YYYY-MM-DD>.md` com as 5 ideias + roteiros.

### Passo 5 — Resumo

Mostrar as 5 manchetes numa lista curta e perguntar se quer ajustar alguma antes de fechar (trocar
ideia, mudar tom, aprofundar roteiro específico).

---

## Regras

- Nunca usar linguagem apelativa (regra de `_memoria/preferencias.md`)
- Não inventar depoimento, número ou resultado de paciente — se for prova social, deixar
  genérico ou pedir pra ela confirmar um caso real
- Roteiro precisa soar falado, não escrito — testar lendo em voz alta mentalmente antes de
  entregar
- Se o gargalo em `_memoria/estrategia.md` mudar, recalibrar a mistura de tipos de ideia
  (hoje pesa mais pro CTA de captação)
