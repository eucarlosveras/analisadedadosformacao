# Guia de voz e linguagem de comunicação

Estilo de comunicação dos conteúdos de cada módulo, extraído do Coursera e
adaptado à apostila "Do Zero ao Melhor Analista de Dados". Use este guia ao
escrever ou revisar qualquer seção.

## Os 7 princípios

1. **Fale com o aluno (1ª pessoa do plural + "você").**
   O instrutor conduz junto: "Vamos partir de um exemplo…", "o que **você** vai aprender".

2. **Resultado primeiro (outcome-first).**
   Abra pelo que o aluno será capaz de fazer, não pela definição:
   *"Ao terminar esta aula, você vai saber escrever um `JOIN` e reconhecer quando ele multiplica linhas."*

3. **Diga por que importa.**
   Amarre a técnica a uma aplicação real e à carreira, em uma frase:
   *"Isto importa porque quase toda pergunta de negócio cruza duas tabelas."*

4. **Verbos de ação, convidando a praticar.**
   "Rode", "troque", "experimente", "compare", "defina".

5. **Linguagem simples e concreta.**
   Frases curtas. Exemplo tangível da base de estudo (vendas/colchões). Nenhum jargão sem explicação na primeira vez.

6. **Estrutura escaneável e cronometrada.**
   Objetivo → conteúdo em blocos curtos → recap. O aluno sempre sabe "onde estou e quanto falta" (ex.: "Leitura • X min").

7. **Tom encorajador, de agência.**
   Reforce que o progresso é alcançável e depende do aluno: "assuma o controle da sua jornada".

## Esqueleto de uma seção

```
🎯 Nesta aula: ao terminar, você vai saber <RESULTADO>. Por que importa: <APLICAÇÃO/CARREIRA>.

<conteúdo: o que é → como funciona → exemplo da base → onde falha>

📝 Em resumo: <1 frase com a ideia-chave> + próximo passo.
```

## Padrões de frase (antes → depois)

| Evite | Prefira |
|---|---|
| "Este capítulo trata de amostragem." | "Nesta aula você vai escolher uma amostra que representa a população — e evitar a que distorce o resultado." |
| "A função CALCULATE modifica o contexto de filtro." | "Vamos usar `CALCULATE` para responder 'e se eu ignorar o filtro de categoria?' — o cálculo mais importante do DAX." |
| "Segue a definição de churn." | "Se você trabalha com assinatura, o churn é a métrica que mais tira o sono. Veja como calculá-la." |

## Checklist (aplicar a cada seção)

- [ ] Abre dizendo **o que o aluno vai conseguir fazer**
- [ ] Explica **por que importa** (negócio/carreira) em 1 frase
- [ ] Fala com **"você"/"vamos"**, frases curtas, exemplo concreto da base
- [ ] Tem **um verbo de ação** convidando a praticar
- [ ] Fecha com **recap de 1 linha** + próximo passo
- [ ] Mostra **tempo/esforço** estimado

## Como aparece na apostila

As aberturas e os resumos usam dois blocos próprios no `data.js`:

- `{ "t": "obj", "h": "..." }` → caixa **🎯 Nesta aula** (logo após o título da seção).
- `{ "t": "recap", "h": "..." }` → caixa **📝 Em resumo** (ao fim da seção, antes de "O que estudar em seguida?").

> Extraído de capturas reais do Coursera (visões gerais de módulo, objetivos de
> aprendizagem e aberturas de aula) durante a análise com a ferramenta REA.
