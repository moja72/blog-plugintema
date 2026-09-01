# PluginTema — Mapa de Conteúdo

> Este arquivo organiza o crescimento editorial do Blog PluginTema em hubs, clusters, artigos-pilar, conteúdos satélite, prioridades e relações internas.
>
> Diferente dos demais documentos editoriais, este arquivo é **vivo**:
>
> - deve ser atualizado conforme novos artigos forem publicados;
> - deve registrar lacunas;
> - deve orientar links internos;
> - deve ajudar a decidir o que escrever depois;
> - deve evitar conteúdo isolado e canibalização.
>
> Usar em conjunto com:
>
> - `00_ROTEADOR_EDITORIAL.md`
> - `13_PERFIS_DE_LEITOR.md`
> - `14_CATEGORIAS_DO_BLOG.md`
> - `15_ESTRATEGIA_DE_CONTEUDO.md`
> - `07_DIRETRIZES_DE_SEO.md`
>
> Princípio central:
>
> **cada novo artigo deve fortalecer alguma parte do acervo — não apenas adicionar mais uma URL ao blog.**

---

# 1. Objetivo do mapa

O mapa responde a cinco perguntas:

1. Quais temas queremos dominar?
2. Quais artigos-pilar precisamos ter?
3. Quais conteúdos menores sustentam esses pilares?
4. O que já existe?
5. O que devemos produzir depois?

---

# 2. Diferença entre categoria, hub, cluster e artigo

## Categoria

É a taxonomia pública principal.

Exemplo:

> Performance

## Hub

É um grande assunto editorial.

Exemplo:

> Performance WordPress

## Cluster

É um conjunto de conteúdos conectados dentro do hub.

Exemplo:

> Cache

## Artigo

É uma URL específica.

Exemplo:

> Cache de página vs. cache de objetos: qual a diferença?

---

# 3. Estrutura geral

```text
BLOG PLUGINTEMA

├── WordPress
│   ├── Versões e atualizações
│   ├── Editor de Blocos
│   ├── Editor do Site
│   ├── WordPress Core
│   ├── Multisite
│   └── Recursos nativos
│
├── Performance
│   ├── Core Web Vitals
│   ├── Cache
│   ├── Banco de dados
│   ├── Imagens
│   ├── JavaScript/CSS
│   ├── Servidor
│   └── Benchmarks
│
├── SEO
│   ├── SEO técnico
│   ├── Indexação
│   ├── Search Console
│   ├── Dados estruturados
│   ├── Links internos
│   ├── Plugins SEO
│   └── Google Search
│
├── Plugins
│   ├── Escolha de plugins
│   ├── Reviews
│   ├── Comparativos
│   ├── Backup
│   ├── Formulários
│   ├── Migração
│   └── Produtividade
│
├── Temas
│   ├── Escolha de temas
│   ├── Block themes
│   ├── Temas clássicos
│   ├── Child themes
│   ├── Reviews
│   └── Comparativos
│
├── WooCommerce
│   ├── Checkout
│   ├── Performance
│   ├── Pagamentos
│   ├── Extensões
│   ├── Assinaturas
│   ├── Atualizações
│   └── Integrações
│
├── Construtores
│   ├── Elementor
│   ├── Bricks
│   ├── Divi
│   ├── Comparativos
│   ├── Performance
│   ├── Lock-in
│   └── Workflow
│
├── Segurança
│   ├── Vulnerabilidades
│   ├── Hardening
│   ├── Autenticação
│   ├── Backups
│   ├── WAF
│   └── Recuperação
│
└── PluginTema Labs
    ├── Benchmarks
    ├── Automações
    ├── Infraestrutura
    ├── Experimentos WordPress
    ├── Testes de plugins
    └── Ferramentas próprias
```

---

# 4. Estados do conteúdo

Todo item no mapa pode usar um destes status:

```text
⚪ IDEIA
🟡 AVALIAR
🔵 APROVADO
🟣 EM PRODUÇÃO
🟠 REVISAR
🟢 PUBLICADO
🔴 ATUALIZAR
⚫ DESCARTADO
```

---

# 5. Níveis de prioridade

```text
P0 — urgente / oportunidade imediata
P1 — prioridade alta
P2 — importante
P3 — expansão futura
```

---

# 6. Tipos de conteúdo

Usar códigos curtos:

```text
[PILAR] artigo central de cluster
[GUIA] guia evergreen
[TUT] tutorial
[NEWS] notícia/análise de atualidade
[REVIEW] review
[COMP] comparativo
[DEC] conteúdo de decisão
[LABS] experimento próprio
[SEG] segurança
[UPDATE] atualização de produto/plataforma
```

---

# 7. Fase inicial recomendada

No início, concentrar esforço em cinco frentes:

1. WordPress
2. Plugins
3. Performance
4. Construtores
5. WooCommerce

SEO, Segurança, Temas e Labs continuam presentes, mas crescem gradualmente.

---

# 8. HUB 1 — WordPress

## Objetivo

Ser referência prática para mudanças do WordPress, traduzindo novidades do Core em impacto real.

---

## Cluster 1.1 — Versões e atualizações

### Artigo-pilar

🟡 P1 `[PILAR]`

> Como atualizar o WordPress com segurança: o que revisar antes e depois

### Conteúdos satélite

🟢 `[UPDATE]`

> WordPress 7.1: o que mudou e o que revisar antes de atualizar

🟡 P1 `[UPDATE]`

> WordPress 7.1: problemas conhecidos e compatibilidade

⚪ P2 `[GUIA]`

> Vale atualizar o WordPress no primeiro dia?

⚪ P2 `[TUT]`

> Como testar uma atualização do WordPress em staging

⚪ P3 `[GUIA]`

> Beta, RC e versão estável: o que significam no WordPress?

### Links internos desejados

```text
WordPress 7.1
→ Como atualizar com segurança
→ Staging
→ Compatibilidade
→ Backup
```

---

# 9. Cluster 1.2 — Editor de Blocos

### Artigo-pilar

⚪ P1 `[PILAR]`

> Editor de Blocos do WordPress: guia prático para entender o que realmente mudou

### Satélites

⚪ P1 `[GUIA]`

> Editor de Blocos vs. page builder: onde cada um faz mais sentido

⚪ P2 `[GUIA]`

> Padrões sincronizados: quando realmente usar

⚪ P2 `[TUT]`

> Como criar layouts responsivos no Editor de Blocos

⚪ P2 `[GUIA]`

> O WordPress ainda precisa de page builders?

⚪ P3 `[GUIA]`

> Gutenberg, Editor de Blocos e Editor do Site: qual é a diferença?

---

# 10. Cluster 1.3 — Editor do Site

### Artigo-pilar

⚪ P2 `[PILAR]`

> Editor do Site do WordPress: como funciona e para quem já faz sentido

### Satélites

⚪ P2

> Temas de blocos estão prontos para projetos comerciais?

⚪ P3

> Como editar templates no Editor do Site

⚪ P3

> Editor do Site vs. Theme Builder

---

# 11. Cluster 1.4 — WordPress Multisite

### Artigo-pilar

⚪ P2 `[PILAR]`

> WordPress Multisite: quando faz sentido e quando evitar

### Satélites

⚪ P2

> Multisite ou múltiplas instalações independentes?

⚪ P3

> Como plugins funcionam em uma rede Multisite

⚪ P3

> Principais armadilhas do WordPress Multisite

---

# 12. HUB 2 — Performance

## Objetivo

Construir um dos clusters técnicos mais fortes do blog com conteúdo mensurável e sem receitas genéricas.

---

# 13. Cluster 2.1 — Guia geral de performance

### Artigo-pilar

🔵 P1 `[PILAR]`

> Performance WordPress: o que realmente deixa um site lento

### Satélites

⚪ P1

> Como diagnosticar lentidão no WordPress antes de instalar outro plugin

⚪ P1

> O que medir antes de otimizar um site WordPress

⚪ P2

> PageSpeed 100 vale a pena?

⚪ P2

> Site rápido no teste, lento para o usuário: por que isso acontece?

---

# 14. Cluster 2.2 — Core Web Vitals

### Artigo-pilar

⚪ P1

> Core Web Vitals no WordPress: LCP, INP e CLS sem complicação

### Satélites

⚪ P1

> Como reduzir LCP no WordPress

⚪ P2

> Como corrigir CLS sem quebrar o layout

⚪ P2

> INP ruim no WordPress: onde procurar o problema

⚪ P2

> Core Web Vitals ainda importam para SEO?

Link cruzado:

> SEO

---

# 15. Cluster 2.3 — Cache

### Artigo-pilar

🔵 P1

> Cache no WordPress: página, objetos, navegador e servidor

### Satélites

⚪ P1

> Cache de página vs. cache de objetos

⚪ P1

> Redis no WordPress: quando faz diferença

⚪ P2

> LiteSpeed Cache: o que realmente vale ativar

⚪ P2

> WP Rocket vs. LiteSpeed Cache

⚪ P2

> Quando um plugin de cache é desnecessário

⚪ P3

> Como limpar cache sem limpar “tudo”

---

# 16. Cluster 2.4 — Banco de dados

### Artigo-pilar

⚪ P2

> Banco de dados WordPress: o que cresce e o que realmente precisa de limpeza

### Satélites

⚪ P2

> Autoload no WordPress: quando vira problema

⚪ P2

> Limpar revisões melhora performance?

⚪ P3

> WooCommerce e banco de dados: onde surgem gargalos

---

# 17. Cluster 2.5 — Imagens

### Artigo-pilar

⚪ P2

> Otimização de imagens no WordPress: formato, tamanho e carregamento

### Satélites

⚪ P2

> WebP ou AVIF?

⚪ P2

> Lazy loading ainda precisa de plugin?

⚪ P3

> Imagem grande realmente derruba o PageSpeed?

---

# 18. Cluster 2.6 — JavaScript e CSS

### Artigo-pilar

⚪ P2

> JavaScript e CSS no WordPress: onde o excesso começa

### Satélites

⚪ P2

> Defer, delay e async: qual a diferença?

⚪ P2

> Remover CSS não utilizado vale a pena?

⚪ P3

> Como descobrir qual plugin carrega determinado script

---

# 19. Cluster 2.7 — Servidor

### Artigo-pilar

⚪ P2

> Hospedagem e performance WordPress: o que realmente importa no servidor

### Satélites

⚪ P2

> OpenLiteSpeed vs. LiteSpeed Enterprise para WordPress

⚪ P3

> PHP: quanto a versão impacta performance?

⚪ P3

> Quanto RAM um site WordPress realmente precisa?

---

# 20. HUB 3 — Plugins

## Objetivo

Ajudar o leitor a decidir o que instalar — e principalmente o que não instalar.

---

# 21. Cluster 3.1 — Escolha de plugins

### Artigo-pilar

🔵 P1

> Como escolher um plugin WordPress para o seu projeto

### Satélites

⚪ P1

> Quantos plugins são plugins demais?

⚪ P1

> Como saber se um plugin WordPress é confiável

⚪ P2

> Quando não vale instalar um plugin

⚪ P2

> Plugin abandonado: como identificar antes de instalar

⚪ P2

> Gratuito ou premium: quando vale pagar?

---

# 22. Cluster 3.2 — Backups

### Artigo-pilar

⚪ P2

> Backup WordPress: o que precisa ser salvo de verdade

### Satélites

⚪ P2

> Melhores plugins de backup

⚪ P2

> Backup da hospedagem substitui plugin?

⚪ P3

> Como testar se um backup realmente funciona

---

# 23. Cluster 3.3 — Formulários

### Artigo-pilar

⚪ P2

> Plugins de formulário WordPress: como escolher

### Satélites

⚪ P2

> Fluent Forms vs. WPForms

⚪ P3

> Contact Form 7 ainda vale a pena?

---

# 24. Cluster 3.4 — Migração

### Artigo-pilar

⚪ P2

> Como migrar um site WordPress sem transformar isso em pesadelo

### Satélites

⚪ P2

> Melhores plugins de migração

⚪ P3

> Migração manual vs. plugin

---

# 25. HUB 4 — Construtores

## Objetivo

Criar autoridade comparativa forte em page builders e construção visual.

---

# 26. Cluster 4.1 — Elementor

### Artigo-pilar

🔵 P1

> Elementor: guia completo para entender quando ele faz sentido

### Satélites

⚪ P1 `[REVIEW]`

> Elementor Pro vale a pena?

⚪ P1

> Elementor está pesado ou o problema é o site?

⚪ P2

> Elementor Free vs. Elementor Pro

⚪ P2

> Containers no Elementor: o que mudou

⚪ P2

> Como melhorar performance de um site Elementor

⚪ P3

> Vale abandonar Elementor?

---

# 27. Cluster 4.2 — Bricks

### Artigo-pilar

⚪ P1

> Bricks Builder: para quem faz sentido

### Satélites

⚪ P1 `[REVIEW]`

> Bricks vale a pena?

⚪ P2

> Bricks é realmente mais rápido que Elementor?

⚪ P2

> Limitações do Bricks que você deve conhecer

---

# 28. Cluster 4.3 — Comparativos

### Artigos prioritários

🔵 P1 `[COMP]`

> Elementor vs. Bricks: qual faz mais sentido para o seu projeto?

⚪ P2 `[COMP]`

> Elementor vs. Gutenberg

⚪ P2 `[COMP]`

> Bricks vs. Gutenberg

⚪ P3 `[COMP]`

> Divi vs. Elementor

---

# 29. Cluster 4.4 — Lock-in e migração

### Artigo-pilar

⚪ P2

> Page builder lock-in: o que acontece quando você decide trocar?

### Satélites

⚪ P2

> Vale migrar Elementor para Bricks?

⚪ P3

> O que quebra quando você desativa um page builder?

---

# 30. HUB 5 — WooCommerce

## Objetivo

Cobrir WooCommerce com foco operacional, técnico e comercial.

---

# 31. Cluster 5.1 — Performance WooCommerce

### Artigo-pilar

🔵 P1

> Performance WooCommerce: onde uma loja começa a ficar lenta

### Satélites

⚪ P1

> Redis melhora WooCommerce?

⚪ P2

> Cache em WooCommerce: o que pode e o que não pode ser cacheado

⚪ P2

> Como reduzir lentidão no checkout

⚪ P3

> Banco de dados WooCommerce: principais gargalos

---

# 32. Cluster 5.2 — Checkout

### Artigo-pilar

⚪ P1

> Checkout WooCommerce: performance, UX e compatibilidade

### Satélites

⚪ P1

> Como reduzir abandono de checkout sem encher a loja de plugins

⚪ P2

> Checkout em uma página vale a pena?

⚪ P2

> Plugins de checkout: quais recursos realmente importam

---

# 33. Cluster 5.3 — Atualizações

### Artigo-pilar

⚪ P2

> Como atualizar WooCommerce com segurança

### Satélites

⚪ P2

> Vale atualizar WooCommerce no primeiro dia?

⚪ P2

> Como testar checkout depois de uma atualização

---

# 34. Cluster 5.4 — Extensões

### Artigo-pilar

⚪ P2

> Como escolher extensões WooCommerce sem transformar sua loja em um Frankenstein

### Satélites

⚪ P2

> Plugins de assinatura para WooCommerce

⚪ P2

> Plugins de pagamento: o que avaliar

---

# 35. HUB 6 — SEO

## Objetivo

Construir autoridade em SEO técnico aplicado a WordPress sem reproduzir mitos.

---

# 36. Cluster 6.1 — SEO técnico

### Artigo-pilar

⚪ P2

> SEO técnico no WordPress: o que realmente precisa ser configurado

### Satélites

⚪ P2

> Canonical no WordPress

⚪ P2

> Sitemap XML: quando mexer?

⚪ P2

> Robots.txt no WordPress

⚪ P3

> Noindex, canonical e redirect: quando usar cada um

---

# 37. Cluster 6.2 — Plugins SEO

### Artigo-pilar

⚪ P1

> Plugin de SEO no WordPress: o que ele realmente precisa fazer

### Satélites

⚪ P1 `[COMP]`

> Rank Math vs. Yoast SEO

⚪ P2 `[REVIEW]`

> Rank Math PRO vale a pena?

⚪ P3

> Você realmente precisa de plugin de SEO?

---

# 38. Cluster 6.3 — Search Console

### Artigo-pilar

⚪ P2

> Google Search Console para WordPress: o que acompanhar

### Satélites

⚪ P2

> Impressões subindo e cliques caindo: o que investigar

⚪ P3

> Como encontrar conteúdos que precisam de atualização

---

# 39. Cluster 6.4 — Dados estruturados

### Artigo-pilar

⚪ P2

> Dados estruturados no WordPress: o que realmente vale implementar

### Satélites

⚪ P3

> Article schema no WordPress

⚪ P3

> Breadcrumb schema: quando usar

---

# 40. HUB 7 — Segurança

## Objetivo

Dar respostas rápidas, precisas e não alarmistas.

---

# 41. Cluster 7.1 — Fundamentos

### Artigo-pilar

⚪ P2

> Segurança WordPress: o que realmente reduz risco

### Satélites

⚪ P2

> 2FA no WordPress

⚪ P2

> Vale esconder o wp-admin?

⚪ P2

> Preciso de plugin de segurança?

⚪ P3

> Permissões de arquivos no WordPress

---

# 42. Cluster 7.2 — Vulnerabilidades

### Modelo recorrente

`[SEG]`

> Vulnerabilidade em {produto}: versões afetadas e o que fazer

Cada artigo deve ligar para:

- guia geral de segurança;
- página do produto, quando relevante;
- atualização/correção.

---

# 43. Cluster 7.3 — Recuperação

### Artigo-pilar

⚪ P2

> Site WordPress hackeado: o que fazer primeiro

### Satélites

⚪ P3

> Como restaurar um site após comprometimento

⚪ P3

> Backup é estratégia de segurança?

---

# 44. HUB 8 — Temas

## Objetivo

Ajudar na escolha e manutenção de temas sem tratar “tema leve” como argumento vazio.

---

# 45. Cluster 8.1 — Escolha de temas

### Artigo-pilar

⚪ P2

> Como escolher um tema WordPress

### Satélites

⚪ P2

> Tema leve: o que isso realmente significa?

⚪ P2

> Tema gratuito vs. premium

⚪ P3

> Astra vs. GeneratePress

---

# 46. Cluster 8.2 — Arquitetura de temas

### Artigo-pilar

⚪ P2

> Temas clássicos vs. temas de blocos

### Satélites

⚪ P2

> Ainda faz sentido usar child theme?

⚪ P3

> Quando criar um tema personalizado

---

# 47. HUB 9 — PluginTema Labs

## Objetivo

Criar conteúdo proprietário, reproduzível e citável.

---

# 48. Cluster 9.1 — Benchmarks de plugins

### Ideias

⚪ P1 `[LABS]`

> O que acontece com o wp-admin quando ativamos 10, 30 e 50 plugins?

⚪ P1 `[LABS]`

> Elementor vs. Bricks em uma instalação equivalente

⚪ P2 `[LABS]`

> 5 plugins de cache no mesmo servidor

⚪ P2 `[LABS]`

> Redis em WooCommerce: benchmark real

---

# 49. Cluster 9.2 — Automações

### Ideias

⚪ P2 `[LABS]`

> Criamos um monitor de atualizações de plugins

⚪ P2 `[LABS]`

> Como automatizamos o monitoramento de performance

⚪ P2 `[LABS]`

> IA pode ajudar a revisar changelogs de WordPress?

---

# 50. Cluster 9.3 — Infraestrutura

### Ideias

⚪ P2 `[LABS]`

> OpenLiteSpeed vs. LiteSpeed Enterprise em ambiente controlado

⚪ P3 `[LABS]`

> Quanto RAM realmente muda um WordPress?

⚪ P3 `[LABS]`

> PHP 8.x: diferença prática entre versões

---

# 51. Cluster 9.4 — Experimentos editoriais

### Ideias

⚪ P3

> Quanto conteúdo desnecessário existe em um changelog típico?

⚪ P3

> O que a comunidade reclama vs. o que conseguimos reproduzir

---

# 52. Artigos prioritários — Fase 1

Primeira leva recomendada:

```text
P1  WordPress 7.1: o que mudou e o que revisar antes de atualizar
P1  Como escolher um plugin WordPress para o seu projeto
P1  Performance WordPress: o que realmente deixa um site lento
P1  Cache no WordPress: página, objetos, navegador e servidor
P1  Elementor Pro vale a pena?
P1  Elementor vs. Bricks
P1  Bricks Builder: para quem faz sentido
P1  Performance WooCommerce: onde uma loja começa a ficar lenta
P1  Rank Math vs. Yoast SEO
P1  Segurança WordPress: o que realmente reduz risco
P1  PluginTema Labs: impacto de 10, 30 e 50 plugins
```

---

# 53. Fase 2

Depois de estabelecer os primeiros pilares:

```text
Core Web Vitals
Redis
WooCommerce checkout
Editor de Blocos
Editor do Site
Temas de blocos
Backups
SEO técnico
Search Console
Lock-in de page builders
```

---

# 54. Fase 3

Expansão:

```text
Multisite
banco de dados
servidor
temas
migração
formulários
dados estruturados
automações
infraestrutura Labs
```

---

# 55. Regra de publicação em cluster

Evitar publicar 10 artigos isolados.

Preferir ciclos.

Exemplo:

```text
SEMANA / CICLO PERFORMANCE

1. Performance WordPress — pilar
2. Cache — satélite
3. LCP — satélite
4. Redis — satélite
5. Benchmark Labs — diferencial
```

Isso acelera formação de autoridade temática.

---

# 56. Regra 1 pilar + 3 satélites

Antes de abrir um novo grande tema, tentar ter:

```text
1 artigo-pilar
+
3 conteúdos satélite
```

Isso cria massa mínima de cluster.

Não é regra absoluta.

---

# 57. Links internos — regra base

Todo artigo novo deve tentar ter:

- pelo menos 1 link para um conteúdo mais amplo;
- pelo menos 1 link para conteúdo complementar;
- links para conteúdos mais específicos quando existirem.

Não inserir link artificialmente.

---

# 58. Link ascendente

Satélite → Pilar.

Exemplo:

> Redis no WordPress

linka para:

> Cache no WordPress

---

# 59. Link descendente

Pilar → Satélite.

Exemplo:

> Performance WordPress

linka para:

- Cache;
- Core Web Vitals;
- Banco;
- Imagens.

---

# 60. Link lateral

Satélite → Satélite relacionado.

Exemplo:

> Redis

→ cache de objetos

---

# 61. Link cruzado entre hubs

Quando o assunto realmente conectar duas áreas.

Exemplo:

> Core Web Vitals

Performance → SEO

Não criar links cruzados apenas por SEO.

---

# 62. Artigos órfãos

Nenhum artigo estratégico deve permanecer órfão.

Ao publicar:

identificar:

- de onde receberá link;
- para onde apontará.

---

# 63. Canibalização

Antes de aprovar nova pauta:

pesquisar no mapa:

> já existe conteúdo respondendo a mesma intenção?

Se sim:

- atualizar;
- ampliar;
- consolidar;

antes de criar URL nova.

---

# 64. Exemplo de canibalização

Possível conflito:

> Como deixar WordPress rápido

e:

> Como melhorar performance WordPress

Provavelmente mesma intenção.

Melhor:

um artigo-pilar forte.

---

# 65. Conteúdos de versão

Versões relevantes podem ter URL própria.

Exemplo:

```text
WordPress 7.1
WordPress 7.2
WordPress 7.3
```

Porque possuem contexto histórico próprio.

---

# 66. Conteúdos “melhores X”

Preferir uma URL atualizável.

Exemplo:

```text
/melhores-plugins-de-cache/
```

Não criar:

```text
/melhores-plugins-de-cache-2026/
/melhores-plugins-de-cache-2027/
```

salvo decisão editorial específica.

---

# 67. Reviews

Uma review deve se conectar a:

```text
produto
→ categoria
→ comparativo
→ alternativa
→ tutorial
```

Exemplo:

```text
Elementor Pro review
→ Construtores
→ Elementor vs Bricks
→ Performance Elementor
→ Guia Elementor
```

---

# 68. Comparativos

Comparativo deve linkar para reviews individuais quando existirem.

```text
Elementor vs Bricks
├── Elementor review
└── Bricks review
```

---

# 69. Labs como fonte de autoridade

Quando um artigo editorial fizer afirmação suportada por teste próprio:

linkar para o Labs.

Exemplo:

> Em nossos testes...

→ artigo do experimento.

Isso transforma experiência em evidência rastreável.

---

# 70. Conteúdo comercial

Se um artigo mencionar produto vendido pela PluginTema:

link comercial apenas quando relevante.

O mapa editorial não deve ser desenhado exclusivamente para empurrar produtos.

---

# 71. Página comercial x artigo

Não criar artigo que duplique a função da página de produto.

Exemplo:

Página comercial:

> Elementor Pro

Artigo:

> Elementor Pro vale a pena?

As intenções são diferentes.

---

# 72. Conteúdo que falta

O mapa deve possuir uma seção contínua de lacunas.

Formato:

```text
LACUNA:
MOTIVO:
CLUSTER:
PRIORIDADE:
```

---

# 73. Lacunas iniciais importantes

```text
LACUNA: guia central de Performance
PRIORIDADE: P1

LACUNA: guia central de Plugins
PRIORIDADE: P1

LACUNA: pilar Elementor
PRIORIDADE: P1

LACUNA: pilar WooCommerce Performance
PRIORIDADE: P1

LACUNA: pilar SEO técnico
PRIORIDADE: P2

LACUNA: pilar Segurança
PRIORIDADE: P2
```

---

# 74. Conteúdo publicado — registro

Manter uma tabela atualizada.

| Artigo | Categoria | Cluster | Tipo | Status | Última revisão |
|---|---|---|---|---|---|
| WordPress 7.1: o que mudou e o que revisar antes de atualizar | WordPress | Versões | UPDATE | 🟢 | preencher |
| Como escolher um plugin WordPress para o seu projeto | Plugins | Escolha | GUIA | verificar | preencher |

Atualizar conforme o blog real.

---

# 75. Não presumir publicação

Somente marcar:

> 🟢 PUBLICADO

quando a URL estiver realmente no ar.

Se houver dúvida:

> 🟠 REVISAR

ou:

> 🔵 APROVADO.

---

# 76. Campo URL

Depois da publicação, registrar:

```text
URL:
```

Isso ajuda:

- links internos;
- auditoria;
- atualização;
- canibalização.

---

# 77. Campo de data

Registrar:

```text
PUBLICADO:
ÚLTIMA ATUALIZAÇÃO:
PRÓXIMA REVISÃO:
```

Especialmente em:

- reviews;
- comparativos;
- preços;
- versões;
- SEO;
- segurança.

---

# 78. Modelo de registro de artigo

```text
TÍTULO:
URL:
STATUS:
PRIORIDADE:
CATEGORIA:
CLUSTER:
TIPO:
PERFIL PRIMÁRIO:
INTENÇÃO:
PILAR RELACIONADO:
SATÉLITES:
LINKS INTERNOS DE ENTRADA:
LINKS INTERNOS DE SAÍDA:
PUBLICADO:
ÚLTIMA ATUALIZAÇÃO:
PRÓXIMA REVISÃO:
OBSERVAÇÕES:
```

---

# 79. Backlog prioritário

O backlog deve ser derivado deste mapa.

Não manter duas listas completamente independentes.

Mapa:

> define arquitetura.

Backlog:

> define execução.

---

# 80. Atualização do mapa

Atualizar quando:

- artigo publicado;
- pauta aprovada;
- cluster criado;
- conteúdo consolidado;
- URL removida;
- nova categoria estratégica;
- nova oportunidade relevante.

---

# 81. Revisão mensal

Uma vez por mês, verificar:

1. quais clusters cresceram;
2. quais ficaram abandonados;
3. quais artigos viraram órfãos;
4. quais páginas competem entre si;
5. quais pilares precisam de atualização;
6. quais oportunidades surgiram.

---

# 82. Revisão trimestral

A cada trimestre:

- reavaliar prioridades;
- comparar Search Console;
- avaliar conversão;
- identificar clusters fortes;
- consolidar conteúdo;
- expandir hubs vencedores.

---

# 83. Search Console no mapa

Adicionar sinal quando uma pauta surgir de dados reais.

Exemplo:

```text
ORIGEM:
Search Console — consulta em crescimento
```

Isso ajuda a distinguir:

- ideia;
- oportunidade comprovada.

---

# 84. Reddit/comunidade no mapa

Quando uma pauta nascer da comunidade:

```text
ORIGEM:
Reddit / fórum / suporte

SINAL:
problema recorrente
```

Depois pesquisar normalmente.

---

# 85. Loja no mapa

Quando uma pauta nascer de dúvida comercial:

```text
ORIGEM:
pré-venda / suporte / produto

DÚVIDA:
...
```

Sem expor dados pessoais de clientes.

---

# 86. Score de prioridade

Opcionalmente, adicionar:

```text
RELEVÂNCIA: 0–3
DEMANDA: 0–3
DIFERENCIAÇÃO: 0–3
ATUALIDADE: 0–3
CLUSTER: 0–3
VALOR COMERCIAL: 0–3
CAPACIDADE PRÓPRIA: 0–3
TOTAL:
```

Usar como apoio.

Não como decisão automática.

---

# 87. Conteúdo experimental

Labs pode gerar novas pautas editoriais.

Exemplo:

```text
LABS:
Redis não mudou TTFB em determinado cenário

↓

ARTIGO:
Quando Redis não faz diferença no WordPress
```

---

# 88. Conteúdo editorial pode gerar Labs

Fluxo inverso:

```text
Pergunta recorrente:
Elementor é pesado?

↓

LABS:
benchmark controlado

↓

Review / comparativo atualizado
```

Esse ciclo é especialmente valioso.

---

# 89. Conteúdos de ligação

Alguns artigos conectam hubs.

Exemplo:

> Elementor vs Gutenberg

Conecta:

- WordPress;
- Construtores.

Esses artigos são estratégicos para navegação interna.

---

# 90. Artigos de ponte sugeridos

```text
Editor de Blocos vs Elementor
Performance vs SEO: onde Core Web Vitals realmente entram
Plugin de cache ou cache de servidor?
Tema leve ou builder otimizado?
WooCommerce: performance ou conversão?
```

---

# 91. Não expandir tudo ao mesmo tempo

O mapa mostra possibilidades.

Não significa produzir tudo.

Prioridade:

> profundidade antes de largura.

---

# 92. Sinal de cluster maduro

Um cluster começa a ficar forte quando possui:

- pilar;
- vários satélites;
- links internos;
- atualização;
- tráfego;
- autoridade;
- perguntas complementares.

---

# 93. Sinal de cluster fraco

- um artigo isolado;
- pouca conexão;
- nenhuma busca;
- nenhum link interno;
- assunto distante do público.

Nesse caso:

- expandir;
- consolidar;
- abandonar.

---

# 94. Mapa e calendário

Calendário editorial deve escolher itens do mapa.

Não inventar pautas desconectadas apenas para preencher calendário.

---

# 95. Mapa e categorias

A estrutura deste arquivo não cria novas categorias.

Clusters são organização editorial interna.

Exemplo:

```text
Categoria: Performance
Cluster: Cache
```

Não é necessário criar categoria “Cache”.

---

# 96. Mapa e tags

Tags podem ajudar a navegar entidades recorrentes.

Exemplo:

```text
Categoria: Construtores
Cluster: Elementor
Tag: Elementor
```

Mas seguir as regras de `14_CATEGORIAS_DO_BLOG.md`.

---

# 97. Mapa e SEO

O mapa deve ajudar:

- arquitetura;
- intenção;
- links internos;
- cobertura temática;
- atualização.

Não criar cluster artificial apenas porque ferramenta SEO recomenda.

---

# 98. Mapa e autoridade editorial

Os clusters mais fortes devem refletir onde a PluginTema possui:

- experiência;
- produtos;
- conhecimento;
- capacidade de testar;
- relevância de público.

---

# 99. Diferenciais que devem aparecer no mapa

Ao longo do tempo, aumentar conteúdos com:

```text
[TESTE PRÓPRIO]
[DADO PRÓPRIO]
[EXPERIÊNCIA REAL]
[COMPARAÇÃO]
[METODOLOGIA]
[FERRAMENTA PRÓPRIA]
```

Esses conteúdos são difíceis de commoditizar.

---

# 100. Meta de maturidade inicial

Primeira meta estrutural:

> **5 clusters fortes com ao menos 1 pilar + 3 satélites cada.**

Sugestão:

1. WordPress — Atualizações
2. Performance — Cache
3. Plugins — Escolha
4. Construtores — Elementor/Bricks
5. WooCommerce — Performance

Isso cria uma base de aproximadamente:

> 20 conteúdos conectados.

---

# 101. Meta seguinte

Depois:

> **9 categorias com pelo menos um cluster útil e não vazio.**

Sem forçar quantidade igual.

---

# 102. Meta de Labs

Primeira meta:

> 3 experimentos de alta qualidade.

Melhor 3 bons Labs do que 20 testes superficiais.

---

# 103. Meta de atualização

Nenhum conteúdo estratégico deve ficar abandonado.

Reviews, comparativos e conteúdos temporais devem possuir:

> próxima revisão prevista.

---

# 104. Regra de decisão

Antes de escrever qualquer pauta nova:

1. localizar categoria;
2. localizar cluster;
3. verificar se já existe URL;
4. identificar pilar;
5. definir links;
6. definir prioridade;
7. só então produzir.

---

# 105. Checklist de entrada no mapa

- [ ] categoria definida;
- [ ] cluster definido;
- [ ] intenção definida;
- [ ] perfil definido;
- [ ] não existe canibalização;
- [ ] diferencial identificado;
- [ ] artigo-pilar relacionado;
- [ ] links internos possíveis;
- [ ] prioridade definida.

---

# 106. Checklist após publicação

- [ ] status atualizado para publicado;
- [ ] URL registrada;
- [ ] data registrada;
- [ ] links internos inseridos;
- [ ] artigos antigos passaram a apontar para o novo;
- [ ] próxima revisão definida quando necessário;
- [ ] sitemap/indexação verificados quando aplicável.

---

# 107. Regra de manutenção

Este arquivo não deve virar uma lista infinita de ideias.

Remover ou arquivar:

- pautas descartadas;
- duplicadas;
- irrelevantes.

Manter visível:

> o que ajuda a decidir o próximo movimento editorial.

---

# 108. Visão resumida da prioridade inicial

```text
P1
├── WordPress
│   └── Atualizações
├── Performance
│   ├── Guia geral
│   └── Cache
├── Plugins
│   └── Escolha
├── Construtores
│   ├── Elementor
│   ├── Bricks
│   └── Comparativos
└── WooCommerce
    └── Performance

P2
├── SEO técnico
├── Segurança
├── Temas
├── Banco de dados
└── Checkout WooCommerce

P3
├── Multisite
├── Infraestrutura avançada
├── Dados estruturados
└── expansão de Labs
```

---

# 109. Visão de longo prazo

O objetivo não é ter:

> centenas de artigos.

É ter:

> **um acervo em que cada tema importante tenha uma resposta central, respostas específicas, testes próprios e caminhos claros de navegação.**

---

# 110. Regra final

> **O mapa de conteúdo é a arquitetura do conhecimento da PluginTema.**

Categorias dizem onde o artigo pertence.

Estratégia diz por que vale produzi-lo.

Perfis dizem para quem escrever.

O mapa diz:

> **o que existe, o que falta e qual conteúdo deve vir depois.**

Quanto mais o blog crescer, mais importante este arquivo se torna.
