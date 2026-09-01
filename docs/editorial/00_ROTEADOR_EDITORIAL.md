# PluginTema — Roteador Editorial

> Arquivo de entrada do sistema editorial do Blog PluginTema.
> Antes de escrever, pesquisar, revisar, atualizar ou criar imagens, use este documento para decidir quais arquivos consultar.
> Este arquivo não substitui os demais: ele apenas roteia a tarefa.

---

# 1. Regra central

Todo conteúdo da PluginTema deve procurar responder, quando aplicável:

1. O que aconteceu?
2. O que isso muda na prática?
3. Para quem isso importa?
4. Qual é a interpretação da PluginTema?
5. O que vale fazer a partir disso?

Fato primeiro. Interpretação depois. Recomendação apenas quando houver base.

---

# 2. Ordem de precedência

Em caso de conflito entre regras, priorizar:

1. segurança;
2. correção factual;
3. transparência;
4. `POLITICA_EDITORIAL.md`;
5. `REGRAS_DE_PESQUISA.md`;
6. `POSICIONAMENTO_EDITORIAL.md`;
7. `VOZ_EDITORIAL.md`;
8. regra específica do tipo de conteúdo;
9. `ESTRUTURA_DE_ARTIGOS.md`;
10. `TERMINOLOGIA_WORDPRESS.md`;
11. `DIRETRIZES_DE_SEO.md`;
12. estética;
13. conversão.

SEO, estética e conversão nunca vencem verdade, segurança ou transparência.

---

# 3. Arquivos do sistema

```text
00_ROTEADOR_EDITORIAL.md

01_VOZ_EDITORIAL.md
02_POSICIONAMENTO_EDITORIAL.md
03_ESTRUTURA_DE_ARTIGOS.md
04_CHECKLIST_DE_PUBLICACAO.md
05_REGRAS_DE_PESQUISA.md
06_POLITICA_EDITORIAL.md
07_DIRETRIZES_DE_SEO.md
08_REVIEWS_E_COMPARATIVOS.md
09_TERMINOLOGIA_WORDPRESS.md
10_ESTILO_DE_IMAGENS.md
11_PROMPTS_DE_IMAGENS.md
```

Se os arquivos estiverem sem numeração, localizar pelo nome correspondente.

Se existir `Teste Final antes de Publicar.md`, usá-lo como microcheck final depois de `CHECKLIST_DE_PUBLICACAO.md`.

---

# 4. Arquivos obrigatórios para qualquer artigo

Antes de redigir um artigo novo, consultar:

- `VOZ_EDITORIAL.md`
- `POSICIONAMENTO_EDITORIAL.md`
- `ESTRUTURA_DE_ARTIGOS.md`
- `TERMINOLOGIA_WORDPRESS.md`

Se houver fatos externos, atuais ou técnicos, consultar também:

- `REGRAS_DE_PESQUISA.md`
- `POLITICA_EDITORIAL.md`

Antes de entregar ou publicar:

- `DIRETRIZES_DE_SEO.md`
- `CHECKLIST_DE_PUBLICACAO.md`

---

# 5. Roteamento por tarefa

## Artigo padrão / análise

Consultar:

`VOZ_EDITORIAL` → `POSICIONAMENTO_EDITORIAL` → `ESTRUTURA_DE_ARTIGOS` → `TERMINOLOGIA_WORDPRESS` → `REGRAS_DE_PESQUISA` → `DIRETRIZES_DE_SEO` → `CHECKLIST_DE_PUBLICACAO`

## Notícia

Consultar:

`REGRAS_DE_PESQUISA` → `POLITICA_EDITORIAL` → `VOZ_EDITORIAL` → `POSICIONAMENTO_EDITORIAL` → `ESTRUTURA_DE_ARTIGOS` → `TERMINOLOGIA_WORDPRESS` → `DIRETRIZES_DE_SEO` → `CHECKLIST_DE_PUBLICACAO`

Regra: fonte original → confirmação → contexto → impacto → recomendação.

Não reescrever release como artigo.

## Atualização de WordPress, plugin ou plataforma

Consultar principalmente:

`REGRAS_DE_PESQUISA`, `POSICIONAMENTO_EDITORIAL`, `ESTRUTURA_DE_ARTIGOS`, `TERMINOLOGIA_WORDPRESS`, `CHECKLIST_DE_PUBLICACAO`.

Verificar versão, data, changelog, documentação/Dev Notes, compatibilidade, problemas conhecidos e se vale atualizar agora.

## Tutorial

Consultar:

`VOZ_EDITORIAL` → `ESTRUTURA_DE_ARTIGOS` → `TERMINOLOGIA_WORDPRESS` → `REGRAS_DE_PESQUISA` → `POLITICA_EDITORIAL` quando houver risco → `DIRETRIZES_DE_SEO` → `CHECKLIST_DE_PUBLICACAO`

O tutorial deve ser reproduzível e, quando aplicável, informar pré-requisitos, versão, passos, resultado esperado, como confirmar que funcionou, riscos, backup e rollback.

## Review

Consultar obrigatoriamente:

`REVIEWS_E_COMPARATIVOS` → `POLITICA_EDITORIAL` → `REGRAS_DE_PESQUISA` → `VOZ_EDITORIAL` → `POSICIONAMENTO_EDITORIAL` → `ESTRUTURA_DE_ARTIGOS` → `TERMINOLOGIA_WORDPRESS` → `DIRETRIZES_DE_SEO` → `CHECKLIST_DE_PUBLICACAO`

Nunca produzir review completo apenas pela página comercial.

Nunca escrever “testamos” sem teste real.

## Comparativo / ranking

Consultar obrigatoriamente:

`REVIEWS_E_COMPARATIVOS` → `POLITICA_EDITORIAL` → `REGRAS_DE_PESQUISA` → `POSICIONAMENTO_EDITORIAL` → `VOZ_EDITORIAL` → `ESTRUTURA_DE_ARTIGOS` → `DIRETRIZES_DE_SEO` → `CHECKLIST_DE_PUBLICACAO`

Aplicar critérios equivalentes às opções.

“Melhor” sempre precisa significar “melhor para quê e para quem”.

Não terminar apenas com “depende”: explicar do que depende.

## Opinião

Consultar:

`VOZ_EDITORIAL`, `POSICIONAMENTO_EDITORIAL`, `REGRAS_DE_PESQUISA`, `POLITICA_EDITORIAL`, `ESTRUTURA_DE_ARTIGOS`.

Opinião pode ser forte, mas precisa de tese, argumentos, evidências e contrapontos.

## PluginTema Labs

Consultar:

`POSICIONAMENTO_EDITORIAL` → `ESTRUTURA_DE_ARTIGOS` → `REGRAS_DE_PESQUISA` → `POLITICA_EDITORIAL` → `VOZ_EDITORIAL` → `CHECKLIST_DE_PUBLICACAO`

Registrar hipótese, ambiente, metodologia, teste, resultado, limitações e interpretação.

Não fingir rigor científico que o teste não possui.

## Segurança

Consultar obrigatoriamente:

`REGRAS_DE_PESQUISA` → `POLITICA_EDITORIAL` → `ESTRUTURA_DE_ARTIGOS` → `TERMINOLOGIA_WORDPRESS` → `CHECKLIST_DE_PUBLICACAO`

Confirmar versões afetadas/corrigidas, severidade, condição de exploração, correção e ação recomendada.

Sem alarmismo.

## SEO

Ao escrever sobre SEO:

`REGRAS_DE_PESQUISA` → `DIRETRIZES_DE_SEO` → `POLITICA_EDITORIAL` → `VOZ_EDITORIAL`

Priorizar documentação atual e não transformar correlação ou rumor em regra de ranking.

---

# 6. Roteamento visual

Para qualquer imagem editorial:

consultar obrigatoriamente:

- `ESTILO_DE_IMAGENS.md`
- `PROMPTS_DE_IMAGENS.md`

Antes de gerar, definir:

```text
TIPO DE IMAGEM:
ARTIGO:
CATEGORIA:
IDEIA CENTRAL:
PONTO FOCAL:
ELEMENTOS SECUNDÁRIOS:
ASSETS OFICIAIS:
TEXTO PERMITIDO:
COR DOMINANTE:
FORMATO:
```

A imagem deve complementar o título, não repeti-lo inteiro.

Usar assets reais para logos, screenshots e interfaces quando disponíveis.

Não inventar interface, versão, preço, gráfico ou benchmark.

---

# 7. Primeira pessoa

Consultar `VOZ_EDITORIAL.md`.

Regra rápida:

**“eu”** → experiência real, teste real ou julgamento pessoal assumido.

**“nós”** → posição institucional ou trabalho realizado pela PluginTema.

Não usar primeira pessoa para criar falsa autoridade.

---

# 8. Fato, observação e opinião

Separar sempre:

**Fato** — verificável.

**Observação** — resultado percebido em experiência/teste real.

**Opinião** — interpretação editorial.

Nunca misturar as três como se tivessem o mesmo nível de certeza.

---

# 9. Pesquisa

Pesquisar sempre que a informação puder ter mudado.

Especialmente:

- versões;
- preços;
- compatibilidade;
- vulnerabilidades;
- funcionalidades;
- políticas;
- SEO;
- IA;
- roadmaps;
- SaaS.

Hierarquia rápida:

```text
1. fonte primária
2. evidência técnica independente
3. fonte especializada
4. comunidade
5. conteúdo comercial
```

Reddit é termômetro de percepção, não autoridade automática.

Quando a comunidade revelar um problema:

relato → investigação → confirmação quando possível.

---

# 10. Produtos relacionados comercialmente à PluginTema

Se a PluginTema vende, distribui ou possui interesse comercial no produto:

consultar obrigatoriamente:

- `POLITICA_EDITORIAL.md`
- `REVIEWS_E_COMPARATIVOS.md`

A análise deve ficar mais rigorosa, não menos.

É permitido concluir que um concorrente é melhor para determinado cenário.

---

# 11. Processo padrão de criação

## 1 — Definir a pauta

Responder:

- qual pergunta será resolvida?
- para quem?
- qual tipo de artigo?
- por que esse conteúdo merece existir?

## 2 — Pesquisar

Separar:

- fatos;
- claims;
- relatos;
- dúvidas;
- pontos não confirmados;
- testes necessários.

## 3 — Definir a tese

Responder:

> O que a PluginTema conclui a partir das evidências?

## 4 — Estruturar

Definir H2/H3 e fluxo antes de escrever artigos longos.

## 5 — Redigir

Aplicar voz, posicionamento e terminologia.

## 6 — Otimizar

Aplicar SEO depois de resolver a lógica editorial.

## 7 — Criar imagens

Aplicar o sistema visual e os prompts oficiais.

## 8 — Revisar

Aplicar o checklist completo e o microcheck final, se houver.

---

# 12. Briefing mínimo

Antes de escrever conteúdo importante, montar internamente:

```text
PAUTA:
TIPO:
CATEGORIA:
PERGUNTA PRINCIPAL:
PÚBLICO:
INTENÇÃO DE BUSCA:
TESE / CONCLUSÃO PROVISÓRIA:
FONTES PRINCIPAIS:
O QUE PRECISA SER TESTADO:
O QUE A COMUNIDADE ESTÁ DIZENDO:
PONTOS DE INCERTEZA:
ESTRUTURA:
CTA:
CONCEITO DA IMAGEM:
```

---

# 13. Regras rápidas de qualidade

Nunca inventar:

- fonte;
- citação;
- dado;
- preço;
- versão;
- teste;
- experiência;
- consenso;
- benchmark;
- screenshot;
- interface;
- funcionalidade.

Quando não for possível confirmar, dizer isso.

Depois de cada fato importante, perguntar:

> E daí?

Toda recomendação importante deve responder:

> Para quem isso é verdade?

Antes de recomendar uma ferramenta, considerar custos ocultos como performance, manutenção, renovação, aprendizado, dependência, migração, suporte e privacidade.

---

# 14. Anti-documentação

Perguntar:

> O artigo acrescenta algo além do que a documentação já diz?

Se não, adicionar contexto, impacto, experiência, contraponto ou recomendação.

---

# 15. Anti-hype

Não usar automaticamente:

- revolucionário;
- muda tudo;
- obrigatório;
- perfeito;
- fim de X;
- melhor de todos.

Afirmação forte exige evidência proporcional.

---

# 16. Anti-SEO artificial

Perguntar:

> Esta frase existe porque ajuda o leitor ou porque alguém acha que “o Google gosta”?

Se existir apenas pela segunda razão, remover ou reescrever.

---

# 17. Atualização de artigos antigos

Não apenas trocar o ano.

Revisar fatos, versões, preços, screenshots, recursos, links, concorrentes, conclusão e SEO.

---

# 18. Comando recomendado para iniciar um artigo

```text
Use o 00_ROTEADOR_EDITORIAL.md para identificar as regras aplicáveis.

Antes de redigir:
1. classifique o tipo de conteúdo;
2. consulte os arquivos indicados;
3. pesquise informações atuais quando necessário;
4. defina tese e estrutura;
5. escreva seguindo a voz PluginTema;
6. aplique SEO sem deformar o texto;
7. revise pelo checklist antes de entregar.
```

---

# 19. Comando recomendado para revisão

```text
Revise este artigo de acordo com o 00_ROTEADOR_EDITORIAL.md e os arquivos especializados indicados por ele.

Verifique precisão, pesquisa, voz, posicionamento, estrutura, primeira pessoa, terminologia, SEO, repetição, opinião, recomendação, transparência e checklist de publicação.

Preserve boas decisões autorais; não reescreva mecanicamente.
```

---

# 20. Regra final

> **O roteador decide quais documentos consultar. Os documentos especializados determinam como executar.**

Não usar este arquivo como substituto simplificado dos demais.

A qualidade editorial da PluginTema depende do conjunto.
