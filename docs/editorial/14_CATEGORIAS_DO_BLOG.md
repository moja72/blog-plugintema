# PluginTema — Categorias do Blog

> Este arquivo define a taxonomia editorial principal do Blog PluginTema.
>
> Ele deve ser usado em conjunto com:
>
> - `00_ROTEADOR_EDITORIAL.md`
> - `01_VOZ_EDITORIAL.md`
> - `02_POSICIONAMENTO_EDITORIAL.md`
> - `03_ESTRUTURA_DE_ARTIGOS.md`
> - `07_DIRETRIZES_DE_SEO.md`
> - `09_TERMINOLOGIA_WORDPRESS.md`
> - `10_ESTILO_DE_IMAGENS.md`
> - `13_PERFIS_DE_LEITOR.md`
>
> Princípio central:
>
> **categoria deve explicar ao leitor qual é o tema editorial dominante do artigo.**
>
> A categoria não existe para repetir palavras-chave nem para criar uma pasta para cada assunto.

---

# 1. Categorias principais

O Blog PluginTema trabalha com estas categorias editoriais principais:

1. WordPress
2. Performance
3. SEO
4. Plugins
5. Temas
6. WooCommerce
7. Construtores
8. Segurança
9. PluginTema Labs

Essas categorias formam a taxonomia principal do blog.

Não criar novas categorias por impulso.

---

# 2. Regra da categoria dominante

Um artigo pode tocar em vários assuntos.

Mas deve ter uma categoria principal que represente:

> **o motivo central pelo qual alguém leria aquele conteúdo.**

Exemplo:

> Elementor 4 ficou 20% mais rápido

Pode envolver:

- Elementor;
- performance;
- construtores.

Pergunta:

> Qual é a pauta principal?

Se o artigo analisa a nova versão do Elementor e a performance é uma das mudanças:

> **Construtores**

Se o artigo é um benchmark aprofundado sobre impacto de Elementor na velocidade:

> **Performance**

---

# 3. Categoria não é tag

Categoria responde:

> **qual pilar editorial este artigo pertence?**

Tag responde:

> **quais entidades, produtos ou subtemas aparecem aqui?**

Exemplo:

```text
Categoria: Performance

Tags:
Elementor
Core Web Vitals
LCP
JavaScript
```

Não criar uma categoria “Elementor” apenas porque muitos artigos citam Elementor.

---

# 4. Preferir uma categoria principal

Como regra padrão:

> **1 artigo = 1 categoria principal.**

Isso melhora:

- arquitetura;
- navegação;
- SEO;
- clareza editorial;
- organização dos clusters.

Se o WordPress permitir múltiplas categorias, evitar usar essa possibilidade como padrão.

---

# 5. Quando aceitar mais de uma categoria

Somente quando houver razão editorial muito forte e a implementação do site realmente depender disso.

Exemplo raro:

> vulnerabilidade crítica no WooCommerce Core

Pode ser útil em:

- WooCommerce;
- Segurança.

Mesmo assim, a preferência editorial é escolher a dominante e usar tags/links internos para o restante.

---

# 6. Ordem para decidir categoria

Quando houver dúvida, perguntar nesta ordem:

1. Qual é a pergunta principal do artigo?
2. Qual é a decisão que o leitor precisa tomar?
3. Qual é o objeto principal da análise?
4. Qual categoria reuniria naturalmente outros artigos semelhantes?
5. Onde o leitor esperaria encontrar este conteúdo?

A primeira resposta normalmente define a categoria.

---

# 7. Categoria: WordPress

## Definição

Categoria central para conteúdos sobre o WordPress como plataforma, projeto, Core e ecossistema nativo.

## Entra aqui

- novas versões do WordPress;
- WordPress Core;
- Editor de Blocos;
- Editor do Site;
- temas de blocos quando o foco for recurso nativo;
- padrões;
- APIs nativas;
- mudanças de interface do WordPress;
- roadmap do Core;
- Gutenberg como projeto;
- WP-CLI quando o foco for WordPress;
- Multisite;
- recursos nativos;
- decisões do projeto WordPress;
- notícias relevantes do ecossistema central.

## Exemplos

> WordPress 7.1: o que mudou e o que revisar antes de atualizar

> WordPress 7.2: principais mudanças previstas

> O novo Editor do Site finalmente substitui este fluxo?

> WordPress Multisite: quando faz sentido usar

> O WordPress ainda precisa de tantos plugins?

## Não entra aqui quando

O WordPress é apenas a plataforma de fundo.

Exemplo:

> Como melhorar o LCP no WordPress

Categoria:

> Performance

---

# 8. WordPress como categoria guarda-chuva

WordPress não deve virar categoria para tudo.

Quase todos os conteúdos do blog terão relação com WordPress.

Isso não significa que todos pertencem a WordPress.

Regra:

> Se outra categoria descreve melhor a intenção do artigo, usar a outra.

---

# 9. Categoria: Performance

## Definição

Conteúdos cujo objetivo principal é melhorar ou medir desempenho, eficiência e experiência de carregamento.

## Entra aqui

- Core Web Vitals;
- LCP;
- INP;
- CLS;
- TTFB;
- cache;
- Redis;
- object cache;
- CDN;
- imagens;
- scripts;
- CSS;
- banco de dados;
- otimização de servidor;
- PageSpeed;
- Lighthouse;
- benchmarks;
- comparação de desempenho;
- hospedagem quando o foco for performance;
- impacto de plugins no carregamento;
- otimização do wp-admin.

## Exemplos

> Redis realmente melhora WooCommerce? Nosso teste

> Como reduzir o LCP no WordPress sem destruir o layout

> Elementor vs Bricks: qual pesa menos no front-end?

> LiteSpeed Cache: quais recursos realmente fazem diferença

## Não entra aqui

Se performance for apenas um critério secundário em review geral.

Exemplo:

> Review do Elementor Pro

Categoria:

> Construtores

---

# 10. Performance não é “site rápido”

Não usar Performance para qualquer artigo que mencione velocidade.

Pergunta:

> medir ou melhorar desempenho é a tese principal?

Se não:

escolher outra categoria.

---

# 11. Categoria: SEO

## Definição

Conteúdos sobre descoberta, indexação, busca orgânica, arquitetura de conteúdo e ferramentas ligadas diretamente a SEO.

## Entra aqui

- Google Search;
- Search Console;
- indexação;
- crawling;
- canonical;
- sitemap;
- robots;
- schema/dados estruturados;
- snippets;
- títulos SEO;
- links internos;
- canibalização;
- SEO técnico;
- Core Web Vitals quando tratados sob impacto em busca;
- atualizações de algoritmo;
- Rank Math;
- Yoast SEO;
- plugins SEO quando a intenção principal é SEO;
- AI Overviews quando discutidos pela ótica de busca;
- estratégia de conteúdo orgânico.

## Exemplos

> Rank Math ou Yoast: qual faz mais sentido em 2026?

> Canonical no WordPress: quando você realmente precisa mexer nisso

> O que o Google mudou na documentação de dados estruturados

> AI Overviews: o que muda para sites WordPress?

## Não entra aqui

Se o artigo é review genérico de plugin sem foco em SEO.

---

# 12. SEO e Performance

Há sobreposição natural.

Regra:

## Performance

Quando a pergunta é:

> como medir ou melhorar velocidade?

## SEO

Quando a pergunta é:

> como isso afeta rastreamento, indexação, visibilidade ou busca?

Exemplo:

> Como melhorar o LCP

→ Performance

> Core Web Vitals ainda afetam SEO?

→ SEO

---

# 13. Categoria: Plugins

## Definição

Conteúdos sobre plugins WordPress que não pertencem de forma mais natural a uma categoria especializada.

## Entra aqui

- reviews de plugins gerais;
- plugins de formulário;
- plugins de backup;
- plugins de migração;
- plugins administrativos;
- plugins de produtividade;
- automações;
- membership;
- social;
- utilidades;
- comparativos entre plugins de função geral;
- lançamentos de plugins;
- mudanças comerciais importantes;
- ecossistemas de plugins.

## Exemplos

> Fluent Forms vale a pena?

> Os melhores plugins de backup para WordPress

> Esse plugin substitui três ferramentas que você provavelmente já usa

> Vale instalar um plugin só para redirecionamentos?

## Não entra aqui

Se existe categoria especializada melhor.

Exemplo:

> Review do Rank Math

→ SEO

> Review do WP Rocket

→ Performance

> Review do Elementor Pro

→ Construtores

> Review de plugin de checkout WooCommerce

→ WooCommerce

> Vulnerabilidade grave em plugin

→ Segurança, se a vulnerabilidade for o assunto central.

---

# 14. Plugins funciona como categoria residual

“Plugins” recebe ferramentas que não cabem melhor em:

- Performance;
- SEO;
- WooCommerce;
- Construtores;
- Segurança.

Isso evita criar dezenas de categorias pequenas.

---

# 15. Categoria: Temas

## Definição

Conteúdos em que o tema WordPress é o objeto principal de avaliação, escolha ou implementação.

## Entra aqui

- reviews de temas;
- comparativos de temas;
- block themes;
- temas clássicos;
- performance de temas quando a análise é centrada no tema;
- arquitetura de tema;
- child themes;
- atualização de tema;
- tendências de temas;
- escolha de tema para projetos;
- Divi Theme quando o foco for o tema.

## Exemplos

> GeneratePress ou Astra: qual escolher?

> Ainda faz sentido usar child theme?

> Temas de blocos finalmente estão prontos para projetos comerciais?

> Divi Theme vale a pena em um projeto novo?

## Não entra aqui

Se o assunto é principalmente:

- Elementor;
- Bricks;
- Divi Builder;
- Editor do Site como recurso do WordPress.

Esses casos podem pertencer a:

- Construtores;
- WordPress.

---

# 16. Tema x Construtor

Pergunta:

> O artigo está avaliando o sistema visual do tema ou a ferramenta de construção?

## Tema

→ Temas

## Builder/editor

→ Construtores

Exemplo:

> Divi Theme: review completo

→ Temas

> Divi Builder vs Elementor

→ Construtores

---

# 17. Categoria: WooCommerce

## Definição

Conteúdos cujo contexto principal é comércio eletrônico dentro do ecossistema WooCommerce.

## Entra aqui

- WooCommerce Core;
- versões;
- checkout;
- carrinho;
- produtos;
- pedidos;
- pagamentos;
- assinaturas;
- extensões;
- integrações;
- estoque;
- frete;
- impostos quando ligados ao WooCommerce;
- performance específica de loja;
- segurança específica de loja;
- automação de e-commerce;
- plugins WooCommerce;
- CRO técnico relacionado diretamente à implementação.

## Exemplos

> WooCommerce 10.x: vale atualizar agora?

> Como reduzir abandono no checkout sem adicionar cinco plugins

> Redis em WooCommerce: vale a pena?

> Melhor plugin de assinatura para WooCommerce

## Regra especial

WooCommerce tem maior sensibilidade operacional.

Quando uma mudança pode afetar:

- checkout;
- pagamentos;
- pedidos;
- receita;

a análise deve ser mais conservadora.

---

# 18. WooCommerce x Performance

Exemplo:

> Redis realmente melhora lojas WooCommerce?

Se o artigo é benchmark:

→ Performance

Se o artigo é guia operacional de otimização para lojas:

pode ser:

→ WooCommerce

Pergunta:

> Qual cluster editorial seria mais útil para o leitor?

---

# 19. WooCommerce x Plugins

Plugin criado especificamente para WooCommerce:

normalmente:

> WooCommerce

Plugin genérico usado também em WooCommerce:

normalmente:

> Plugins

ou categoria especializada pela função.

---

# 20. Categoria: Construtores

## Definição

Conteúdos sobre ferramentas de construção visual de páginas, sites, templates e layouts.

## Entra aqui

- Elementor;
- Elementor Pro;
- Bricks;
- Divi Builder;
- Beaver Builder;
- Oxygen;
- Breakdance;
- outros builders;
- comparativos;
- widgets;
- containers;
- theme builders;
- recursos de construção visual;
- performance de builders quando tratada dentro da decisão de escolha;
- migração entre builders;
- lock-in;
- workflow de criação.

## Exemplos

> Elementor ou Bricks: qual faz mais sentido?

> Elementor Pro ainda vale a pena?

> Containers do Elementor: o que realmente mudou

> Vale migrar um site pronto de Elementor para Bricks?

## Não entra aqui

Editor de Blocos e Editor do Site pertencem normalmente a:

> WordPress

a menos que o artigo seja um comparativo explícito de construtores.

---

# 21. Gutenberg x Construtores

Exemplo:

> Gutenberg vs Elementor

Pode entrar em:

> Construtores

porque a intenção principal é escolher uma abordagem de construção.

Exemplo:

> Novidades do Editor de Blocos no WordPress 7.1

→ WordPress

---

# 22. Categoria: Segurança

## Definição

Conteúdos cujo objetivo principal é informar, prevenir, detectar ou corrigir riscos de segurança.

## Entra aqui

- vulnerabilidades;
- CVEs;
- patches;
- exploits;
- malware;
- hardening;
- autenticação;
- 2FA;
- permissões;
- WAF;
- backups sob perspectiva de segurança;
- atualizações críticas;
- ataques;
- segurança de plugins e temas;
- práticas de proteção;
- incidentes relevantes.

## Exemplos

> Falha no plugin X: quem é afetado e o que fazer

> Vale esconder a URL do wp-admin?

> 2FA no WordPress: quais opções realmente fazem sentido

> O que fazer quando um site WordPress é comprometido

## Regra

Segurança prevalece sobre a categoria do produto quando:

> o risco de segurança é a razão principal do artigo.

---

# 23. Segurança x Produto

Exemplo:

> Elementor corrige vulnerabilidade na versão X

Se o foco é:

- falha;
- versões afetadas;
- correção;

→ Segurança

Se o foco é:

- nova versão do Elementor;
- vários recursos, incluindo correção;

→ Construtores

---

# 24. Categoria: PluginTema Labs

## Definição

PluginTema Labs é o espaço experimental e metodológico do blog.

A categoria existe para conteúdos em que a **experimentação própria** é parte central do valor.

## Entra aqui

- testes próprios;
- experimentos;
- benchmarks originais;
- automações;
- protótipos;
- investigações técnicas;
- “o que acontece se...”;
- provas de conceito;
- ferramentas próprias;
- análises de infraestrutura baseadas em experimento;
- testes que não cabem em artigo editorial convencional.

## Exemplos

> Testamos 30 plugins ativos para ver o que acontece com o wp-admin

> Quanto Redis muda um WooCommerce real? Nosso benchmark

> Criamos uma automação para monitorar atualizações de plugins

> O que acontece se carregarmos o WordPress sem jQuery?

## Regra fundamental

PluginTema Labs não é apenas:

> conteúdo técnico.

Precisa existir:

- hipótese;
- teste;
- metodologia;
- observação própria.

---

# 25. Labs x Performance

Um benchmark próprio pode caber nos dois.

Regra:

## PluginTema Labs

Quando o experimento/metodologia é o protagonista.

## Performance

Quando o objetivo principal é responder uma dúvida recorrente de performance e o teste é apenas o método.

Exemplo:

> Benchmark de 10 plugins de cache no mesmo servidor

Pode ser Labs se a identidade experimental for central.

Pode ser Performance se fizer parte de um cluster comercial/editorial amplo de cache.

A decisão deve considerar o mapa de conteúdo.

---

# 26. Labs não deve virar depósito de conteúdo técnico

Não colocar em Labs apenas porque:

- tem código;
- tem terminal;
- é avançado;
- envolve servidor.

Labs exige experimento ou construção original.

---

# 27. Categorias e intenção de busca

Categoria não deve ser escolhida apenas por keyword.

Exemplo:

Busca:

> plugin Elementor lento

Pode resultar em artigo de:

> Performance

mesmo contendo “plugin Elementor”.

A intenção editorial prevalece.

---

# 28. Categorias e URL

Se a arquitetura do site usar categoria na URL:

não alterar categoria de artigo publicado sem avaliar impacto de URL, canonical e redirects.

Idealmente:

> categoria não deve precisar fazer parte do slug do artigo.

Isso reduz dependência da taxonomia.

---

# 29. Categorias e SEO

Cada categoria deve possuir identidade temática suficiente para funcionar como hub.

Uma boa página de categoria deve reunir conteúdos que realmente compartilham intenção.

Evitar:

- categorias com 1 artigo;
- categorias duplicadas;
- categorias quase idênticas;
- taxonomia criada apenas por keyword.

---

# 30. Página de categoria

Cada página de categoria pode ter:

- nome;
- descrição editorial curta;
- ícone;
- cor de acento;
- artigos em destaque;
- artigos recentes;
- clusters relevantes.

Não preencher com 500 palavras genéricas apenas para SEO.

---

# 31. Descrição das categorias

## WordPress

> Atualizações, recursos, Core e decisões do ecossistema WordPress explicados com foco no impacto real.

## Performance

> Testes, métricas e otimizações para tornar WordPress mais rápido e eficiente sem seguir receita pronta.

## SEO

> SEO técnico, Google Search e estratégias de descoberta aplicadas ao WordPress com menos mito e mais evidência.

## Plugins

> Análises, novidades e escolhas de plugins que resolvem problemas reais — ou que talvez você nem precise instalar.

## Temas

> Reviews, comparativos e decisões sobre temas WordPress, arquitetura visual e manutenção.

## WooCommerce

> Tecnologia, plugins, performance e operação para lojas WooCommerce.

## Construtores

> Elementor, Bricks, Divi e outras ferramentas de construção visual analisadas na prática.

## Segurança

> Vulnerabilidades, correções e práticas de segurança WordPress sem alarmismo.

## PluginTema Labs

> Experimentos, benchmarks, automações e testes próprios do laboratório editorial da PluginTema.

---

# 32. Cor e identidade visual por categoria

As categorias podem possuir:

- cor de acento;
- ícone;
- pequenos elementos visuais.

Mas devem manter as regras de:

`10_ESTILO_DE_IMAGENS.md`

A categoria modifica:

> acento.

Não modifica:

> identidade PluginTema.

---

# 33. Ícones de categoria

Sugestões conceituais:

## WordPress

- blocos;
- estrutura WordPress;
- símbolo relacionado ao ecossistema.

## Performance

- métrica;
- barras;
- velocidade mensurável.

## SEO

- resultado de busca;
- estrutura;
- indexação.

## Plugins

- peça modular;
- encaixe;
- extensão.

## Temas

- layout;
- janela;
- composição visual.

## WooCommerce

- produto;
- carrinho;
- checkout.

## Construtores

- grid;
- containers;
- blocos encaixáveis.

## Segurança

- escudo;
- cadeado.

## PluginTema Labs

- experimento;
- terminal;
- laboratório digital.

Seguir `10_ESTILO_DE_IMAGENS.md`.

---

# 34. Tags recomendadas

Tags podem representar:

## Produtos

- Elementor
- Bricks
- Rank Math
- Yoast
- WP Rocket
- LiteSpeed Cache

## Tecnologias

- PHP
- Redis
- Cloudflare
- CSS
- JavaScript

## Recursos

- Core Web Vitals
- Multisite
- Editor de Blocos
- Editor do Site

## Tipos de conteúdo

Evitar tags como:

- tutorial;
- review;
- notícia;

se o sistema do site já possui outra forma de identificar formato.

---

# 35. Regra de criação de tag

Criar tag apenas se houver potencial de:

> **agrupar múltiplos conteúdos úteis.**

Não criar tag por qualquer termo citado.

Uma tag com um único artigo normalmente não agrega valor.

---

# 36. Tags não devem duplicar categoria

Evitar:

```text
Categoria: SEO
Tag: SEO
```

Isso cria páginas concorrentes e confusas.

---

# 37. Tags de versão

Evitar criar tags como:

- WordPress 7.1;
- WordPress 7.2;

a menos que exista estratégia específica.

A versão já pode aparecer:

- no título;
- no conteúdo;
- em links internos.

---

# 38. Categorias que não devemos criar

Evitar como categorias principais:

- Tutoriais;
- Notícias;
- Reviews;
- Guias;
- Dicas;
- Novidades;
- Tecnologia;
- Web;
- Desenvolvimento;

quando essas palavras descrevem formato, não tema.

---

# 39. Formato não é categoria

“Tutorial” deve ser atributo editorial.

Não pilar temático.

Um tutorial pode ser:

- Performance;
- SEO;
- WooCommerce;
- Segurança;
- Construtores.

---

# 40. Notícias também não são categoria principal

Notícia é formato.

Exemplo:

> WordPress lança versão 7.2

Categoria:

> WordPress

> Vulnerabilidade é descoberta em plugin

Categoria:

> Segurança

---

# 41. Reviews também não são categoria

Review é formato.

Exemplo:

> Review do Elementor Pro

→ Construtores

> Review do WP Rocket

→ Performance

> Review do Fluent Forms

→ Plugins

---

# 42. Hierarquia temática

Visualmente:

```text
BLOG PLUGINTEMA

├── WordPress
├── Performance
├── SEO
├── Plugins
├── Temas
├── WooCommerce
├── Construtores
├── Segurança
└── PluginTema Labs
```

Por enquanto, evitar subcategorias públicas.

Clusters podem ser construídos via:

- tags;
- links internos;
- hubs editoriais;
- páginas especiais.

---

# 43. Por que evitar subcategorias agora

O blog ainda precisa acumular volume editorial.

Subcategorias precoces criam:

- páginas vazias;
- navegação complexa;
- fragmentação;
- manutenção desnecessária.

Criar subcategoria somente quando o volume justificar.

---

# 44. Critério futuro para subcategoria

Considerar uma subcategoria quando:

- existe volume consistente;
- existe intenção própria;
- existem pelo menos vários artigos relevantes;
- melhora navegação;
- não compete com outra taxonomia.

Exemplo futuro possível:

```text
Performance
└── Core Web Vitals
```

Mas somente quando houver conteúdo suficiente.

---

# 45. Regra de desempate — objeto x intenção

Quando objeto e intenção apontarem para categorias diferentes:

priorizar:

> **intenção editorial.**

Exemplo:

Objeto:

> Elementor

Intenção:

> medir impacto no LCP.

Categoria:

> Performance

Tags:

> Elementor, LCP, Core Web Vitals

---

# 46. Regra de desempate — segurança

Se o leitor abre o artigo principalmente para saber:

> estou vulnerável e o que devo fazer?

categoria:

> Segurança

independentemente de plugin, tema ou WooCommerce.

---

# 47. Regra de desempate — WooCommerce

Se a decisão só existe porque o cenário é uma loja:

> WooCommerce

tende a prevalecer.

Exemplo:

> Melhor gateway para checkout WooCommerce

→ WooCommerce

---

# 48. Regra de desempate — Labs

Labs prevalece quando:

> o experimento original é o produto editorial.

Se o experimento apenas sustenta outro guia:

usar a categoria temática.

---

# 49. Regra de desempate — WordPress

WordPress prevalece quando:

> o assunto é Core, recurso nativo, roadmap ou mudança da plataforma.

Não quando WordPress é apenas o ambiente.

---

# 50. Exemplos de classificação

| Artigo | Categoria | Tags possíveis |
|---|---|---|
| WordPress 7.1: o que mudou | WordPress | WordPress 7.1, Editor de Blocos |
| Elementor Pro vale a pena? | Construtores | Elementor, Elementor Pro |
| Elementor vs Bricks | Construtores | Elementor, Bricks |
| Elementor piora o LCP? | Performance | Elementor, LCP |
| WP Rocket vs LiteSpeed Cache | Performance | WP Rocket, LiteSpeed Cache |
| Rank Math vs Yoast | SEO | Rank Math, Yoast SEO |
| Falha crítica no Rank Math | Segurança | Rank Math, vulnerabilidade |
| Melhor plugin de formulários | Plugins | formulários |
| Astra vs GeneratePress | Temas | Astra, GeneratePress |
| WooCommerce 10.x: vale atualizar? | WooCommerce | WooCommerce |
| Melhor plugin de checkout | WooCommerce | checkout |
| Como configurar Redis | Performance | Redis |
| Redis em WooCommerce: benchmark experimental | PluginTema Labs ou Performance | Redis, WooCommerce |
| Gutenberg vs Elementor | Construtores | Editor de Blocos, Elementor |
| Novidades do Editor do Site | WordPress | Editor do Site |
| Como configurar 2FA | Segurança | 2FA |
| Criamos um monitor automático de plugins | PluginTema Labs | automação, plugins |

---

# 51. Categoria do primeiro artigo do Blog

Para:

> WordPress 7.1: o que mudou e o que revisar antes de atualizar

categoria recomendada:

> **WordPress**

Motivo:

- assunto central é uma versão do WordPress;
- as mudanças pertencem ao Core/ecossistema nativo;
- performance, Gutenberg/editor e compatibilidade são subtemas.

---

# 52. “PluginTema Labs” como categoria editorial diferenciada

Labs pode possuir:

- badge próprio;
- identidade visual secundária;
- destaque na navegação;
- filtros próprios.

Mas o leitor deve entender imediatamente que:

> é conteúdo experimental da própria PluginTema.

---

# 53. Menu do blog

As categorias podem aparecer no menu editorial.

A presença no menu não obriga que todas tenham o mesmo volume de conteúdo desde o primeiro dia.

Mas evitar manter categoria permanentemente vazia.

---

# 54. Ordem no menu

A ordem pode acompanhar prioridade editorial e navegação.

Exemplo:

```text
Performance
SEO
Plugins
Temas
WooCommerce
Construtores
Segurança
```

WordPress e PluginTema Labs podem receber posições visuais específicas conforme o design do header.

A ordem de menu não altera a hierarquia editorial.

---

# 55. “Loja” não é categoria editorial

“Loja” no menu aponta para a operação comercial da PluginTema.

Não confundir:

> Loja

com:

> WooCommerce

WooCommerce é uma categoria de conteúdo.

Loja é navegação comercial.

---

# 56. Página de busca

Busca deve atravessar todas as categorias.

Não criar categoria “Resultados de busca”.

---

# 57. Conteúdo institucional

Páginas como:

- Sobre;
- Contato;
- Política Editorial;
- Termos;

não pertencem a categorias de artigos.

---

# 58. Categorias e conteúdo comercial

Página de produto não deve ser publicada dentro de categoria editorial apenas para captar SEO.

Artigo e página comercial possuem funções distintas conforme `07_DIRETRIZES_DE_SEO.md`.

---

# 59. Auditoria periódica

A cada período de crescimento do blog, revisar:

- número de artigos por categoria;
- sobreposição;
- categorias vazias;
- tags inúteis;
- canibalização;
- clusters faltantes;
- distribuição editorial.

---

# 60. Sinal de categoria mal definida

Revisar se:

- ninguém sabe onde publicar;
- todo artigo cabe em três categorias;
- uma categoria recebe quase tudo;
- existem categorias com 1–2 artigos por muito tempo;
- categoria e tag são iguais;
- artigos semelhantes ficam espalhados sem lógica.

---

# 61. Sinal de categoria boa

Uma categoria funciona bem quando o leitor entra nela e pensa:

> “Se gostei deste artigo, provavelmente vou gostar dos outros daqui.”

Essa é uma regra importante.

---

# 62. Campo obrigatório no briefing

Todo novo artigo deve registrar:

```text
CATEGORIA PRINCIPAL:
TAGS:
JUSTIFICATIVA DA CATEGORIA:
```

Para pautas ambíguas:

```text
CATEGORIA ALTERNATIVA CONSIDERADA:
POR QUE NÃO FOI ESCOLHIDA:
```

---

# 63. Checklist de categorização

- [ ] Existe uma categoria dominante?
- [ ] A categoria descreve a intenção principal?
- [ ] Outra categoria seria mais específica?
- [ ] O artigo está sendo jogado em WordPress apenas porque usa WordPress?
- [ ] O artigo está sendo jogado em Plugins apenas porque cita um plugin?
- [ ] O formato está sendo confundido com tema?
- [ ] Tags complementam sem duplicar categoria?
- [ ] O leitor encontraria esse artigo onde espera?
- [ ] A classificação ajuda a formar um cluster futuro?

---

# 64. Teste de categorização

Perguntar:

> **Se eu removesse o nome do produto do título, qual assunto continuaria sendo central?**

Exemplo:

> Elementor piora o LCP?

Removendo Elementor:

> ferramenta piora o LCP?

Tema central:

> performance.

---

# 65. Teste do próximo artigo

Perguntar:

> Que outros cinco artigos naturalmente apareceriam nesta categoria ao lado deste?

Se não conseguimos imaginar:

a categoria pode estar específica demais.

---

# 66. Teste da página de categoria

Perguntar:

> A página formada por esses artigos teria utilidade editorial real?

Se não:

rever taxonomia.

---

# 67. Regra de estabilidade

Categorias devem mudar raramente.

Tags e clusters podem evoluir com mais liberdade.

Por isso:

> criar categoria é decisão estrutural.

Não decisão de pauta.

---

# 68. Regra final

> **Categorias organizam o conhecimento do blog. Tags organizam detalhes. Formatos organizam a forma de contar.**

A PluginTema deve manter poucos pilares editoriais fortes, suficientemente amplos para crescer e suficientemente específicos para que o leitor saiba o que encontrará dentro de cada um.

Taxonomia boa não é a que descreve cada artigo perfeitamente.

É a que organiza centenas de artigos sem virar bagunça.
