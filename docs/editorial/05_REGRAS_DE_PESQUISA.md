# PluginTema — Regras de Pesquisa

> Este arquivo define como a PluginTema deve pesquisar, verificar, comparar e validar informações antes de escrever ou atualizar conteúdos editoriais.
>
> Ele deve ser usado em conjunto com:
>
> - `VOZ_EDITORIAL.md`
> - `POSICIONAMENTO_EDITORIAL.md`
> - `ESTRUTURA_DE_ARTIGOS.md`
> - `CHECKLIST_DE_PUBLICACAO.md`
> - `POLITICA_EDITORIAL.md`
> - `DIRETRIZES_DE_SEO.md`
> - `REVIEWS_E_COMPARATIVOS.md`
>
> O objetivo é simples:
>
> **publicar menos suposição e mais informação verificável, atual, contextualizada e útil.**

---

# 1. Princípio central

A pesquisa da PluginTema deve seguir esta ordem:

**descobrir → localizar a fonte primária → verificar → cruzar → contextualizar → interpretar → publicar**

Nunca:

**ver uma manchete → presumir que está correta → reescrever → publicar**

---

# 2. Pesquisa não é coleta de links

Ter muitas fontes não significa ter uma boa pesquisa.

Uma boa pesquisa precisa responder:

- qual é o fato?
- quem é a fonte original?
- quando isso aconteceu?
- essa informação ainda está atual?
- existe conflito entre fontes?
- a afirmação foi testada?
- existe interesse comercial envolvido?
- o dado se aplica ao cenário do artigo?
- qual parte é fato e qual parte é interpretação?

Quantidade de fontes não substitui qualidade.

---

# 3. Hierarquia geral de fontes

Como regra padrão, priorizar nesta ordem:

## Nível 1 — Fonte primária

Preferência máxima.

Exemplos:

- documentação oficial;
- WordPress.org;
- Make WordPress;
- Dev Notes;
- repositório oficial;
- GitHub oficial;
- changelog oficial;
- release oficial;
- documentação de API;
- página oficial de preços;
- documentação técnica do produto;
- advisories de segurança do responsável pelo projeto;
- banco de dados oficial;
- comunicado oficial da empresa.

Usar para confirmar:

- versões;
- datas;
- requisitos;
- recursos;
- mudanças;
- compatibilidade declarada;
- preços;
- planos;
- APIs;
- correções;
- comportamento documentado.

---

## Nível 2 — Evidência técnica independente

Muito forte.

Exemplos:

- testes reproduzíveis;
- benchmarks com metodologia;
- análises técnicas independentes;
- pesquisadores de segurança reconhecidos;
- laboratórios;
- publicações técnicas especializadas;
- código-fonte;
- commits;
- issues confirmadas;
- pull requests;
- testes próprios da PluginTema.

Usar para:

- validar claims;
- testar performance;
- verificar bugs;
- avaliar impacto real;
- analisar comportamento não documentado;
- comparar produtos.

---

## Nível 3 — Fontes jornalísticas e especializadas

Boas para contexto.

Exemplos:

- veículos especializados em WordPress;
- publicações reconhecidas de tecnologia;
- entrevistas;
- análises editoriais;
- cobertura de lançamentos.

Usar para:

- contexto;
- histórico;
- reação de mercado;
- entrevistas;
- síntese de acontecimentos.

Sempre que possível, voltar à fonte original.

---

## Nível 4 — Comunidade

Fonte importante de sinais, não de verdade automática.

Exemplos:

- Reddit;
- fóruns do WordPress;
- fóruns de suporte;
- GitHub Discussions;
- issues;
- comunidades;
- grupos;
- comentários;
- avaliações de usuários.

Usar para descobrir:

- bugs;
- frustrações;
- padrões;
- problemas de suporte;
- incompatibilidades;
- comportamento real;
- percepção da comunidade.

---

## Nível 5 — Conteúdo comercial ou afiliado

Usar com cautela.

Exemplos:

- blogs de empresas;
- landing pages;
- comparativos de afiliados;
- conteúdos patrocinados;
- páginas de venda;
- materiais de marketing;
- “estudos” publicados pelo próprio produto avaliado.

Podem informar fatos sobre o próprio produto.

Não devem ser tratados automaticamente como evidência independente.

---

# 4. Fonte primária não significa fonte neutra

Uma empresa é a melhor fonte para informar:

- preço;
- versão;
- recursos anunciados;
- requisitos;
- roadmap oficial.

Mas não necessariamente para provar:

- que é a mais rápida;
- que é a melhor;
- que é superior a concorrentes;
- que melhora conversão;
- que tem “zero impacto”;
- que economiza determinada porcentagem de tempo.

Regra:

> **fonte primária é autoridade sobre o que ela fez ou anunciou, não sobre a qualidade universal do que ela fez.**

---

# 5. Regra da fonte original

Quando uma matéria diz:

> “Segundo a Automattic...”

procurar a publicação original da Automattic.

Quando um blog diz:

> “Segundo o changelog...”

abrir o changelog.

Quando uma notícia cita:

> “Segundo pesquisadores...”

procurar o advisory ou relatório original.

Sempre que a fonte original estiver acessível, preferi-la.

---

# 6. Quando uma única fonte é suficiente

Uma única fonte primária pode ser suficiente para fatos simples e objetivos.

Exemplos:

- data de lançamento;
- número da versão;
- requisito mínimo;
- recurso anunciado;
- preço oficial atual;
- nome de plano;
- existência de uma função;
- item de changelog.

Mesmo assim, verificar se a página está atualizada.

---

# 7. Quando exigir duas ou mais fontes

Buscar confirmação cruzada quando a afirmação envolver:

- segurança;
- vulnerabilidade;
- impacto relevante em performance;
- números de mercado;
- estatísticas;
- controvérsia;
- mudança com grande impacto;
- alegação de superioridade;
- quebra de compatibilidade;
- problema generalizado;
- política ou regra importante;
- risco de perda de dados;
- rumor;
- informação contestada.

Preferência:

**fonte primária + fonte independente**

ou:

**duas fontes independentes confiáveis**

---

# 8. Quando três fontes fazem sentido

Usar três ou mais fontes relevantes quando:

- houver conflito entre relatos;
- a conclusão for forte;
- o assunto for controverso;
- a informação puder causar ação de alto impacto;
- houver suspeita de viés comercial;
- for difícil determinar a causa de um problema;
- a comunidade estiver dividida.

Mais fontes não significam automaticamente maior verdade.

As fontes precisam ser independentes entre si.

---

# 9. Independência de fontes

Três sites repetindo o mesmo release não são três confirmações.

Perguntar:

- todos estão citando a mesma origem?
- existe investigação independente?
- há teste próprio?
- os dados vieram do mesmo estudo?
- existe relação comercial?

Uma cadeia de republicações conta essencialmente como uma única origem.

---

# 10. Datas importam

Toda pesquisa deve considerar:

1. data de publicação;
2. data do evento;
3. data da última atualização da página;
4. versão do produto naquele momento;
5. se a informação ainda é válida.

Uma página recente pode citar informação antiga.

Uma página antiga pode continuar sendo a documentação oficial válida.

A data sozinha não determina a qualidade.

---

# 11. Informação que envelhece rápido

Exigir verificação recente para:

- versões de WordPress;
- versões de plugins;
- preços;
- planos;
- requisitos;
- compatibilidade;
- vulnerabilidades;
- status de correções;
- APIs;
- políticas;
- funcionalidades;
- roadmap;
- SEO;
- algoritmos de busca;
- navegadores;
- PHP;
- WooCommerce;
- Elementor;
- serviços SaaS.

Não confiar apenas em memória.

---

# 12. Datas relativas

Evitar escrever:

- hoje;
- ontem;
- recentemente;
- há pouco;
- atualmente;

quando a frase pode envelhecer mal.

Preferir datas ou versões concretas quando importante.

Exemplo:

> Em agosto de 2026...

ou:

> A partir da versão 7.1...

---

# 13. Versões

Sempre confirmar:

- versão estável atual;
- versão analisada;
- versão em que o recurso apareceu;
- versões afetadas por bug;
- versões corrigidas;
- beta, RC ou stable.

Não confundir:

- anúncio;
- beta;
- release candidate;
- lançamento final.

---

# 14. Changelogs

Changelog é fonte importante, mas limitada.

Serve muito bem para:

- saber que algo mudou;
- identificar versão;
- localizar correção;
- encontrar recurso.

Não prova sozinho:

- impacto real;
- qualidade;
- performance;
- estabilidade;
- compatibilidade universal.

Sempre perguntar:

> O que o changelog diz que mudou e o que realmente aconteceu na prática?

---

# 15. Dev Notes e documentação técnica

Para mudanças no WordPress Core, priorizar quando disponíveis:

- Dev Notes;
- Make WordPress;
- Field Guide;
- documentação de desenvolvedor;
- tickets do Core;
- Trac;
- GitHub oficial.

Dev Notes costumam oferecer contexto técnico melhor do que posts de anúncio.

---

# 16. GitHub como fonte

GitHub pode ser uma das fontes mais valiosas.

Usar:

- releases;
- tags;
- commits;
- pull requests;
- issues;
- discussions;
- código-fonte.

Mas entender o estado de cada item.

## Issue aberta

Pode indicar problema.

Não prova que o problema foi confirmado.

## Issue fechada

Verificar por quê foi fechada.

Pode ter sido:

- corrigida;
- duplicada;
- rejeitada;
- sem reprodução;
- inválida.

## Pull request

Pode mostrar intenção de mudança.

Não significa que chegou à versão estável.

## Commit

Prova alteração no código daquele branch ou repositório.

Não significa automaticamente que usuários já receberam a mudança.

---

# 17. GitHub e datas

Verificar:

- branch;
- tag;
- versão;
- data do commit;
- data do merge;
- release em que entrou.

Não escrever:

> “O recurso já está disponível”

apenas porque existe um commit.

---

# 18. Issues e bugs

Antes de afirmar que existe um bug:

- procurar reprodução;
- verificar versão;
- observar número de relatos;
- procurar resposta do desenvolvedor;
- verificar se existe correção;
- testar quando possível.

Diferenciar:

> “Há relatos de...”

de:

> “O bug foi confirmado...”

---

# 19. Reddit

Reddit é permitido e valorizado como fonte de percepção da comunidade.

Pode revelar:

- opiniões fortes;
- reclamações;
- bugs;
- comparações reais;
- problemas recorrentes;
- experiências de migração;
- suporte ruim;
- dificuldades de uso;
- recursos apreciados.

Mas Reddit não é autoridade técnica automática.

---

# 20. Como usar Reddit corretamente

Preferir:

- threads com discussão real;
- vários participantes;
- comentários com contexto;
- relatos detalhados;
- usuários que explicam ambiente ou cenário;
- convergência entre múltiplos relatos.

Evitar basear conclusão em:

- um comentário;
- post sem contexto;
- conta suspeita;
- afirmação sem evidência;
- opinião claramente tribal;
- thread antiga sobre versão diferente.

---

# 21. Reddit como termômetro

A melhor função do Reddit é responder:

> **O que usuários reais estão percebendo?**

Não necessariamente:

> **Qual é a verdade técnica definitiva?**

Exemplo correto:

> Há uma frustração recorrente entre usuários sobre X.

Depois:

- buscar issues;
- testar;
- consultar documentação;
- verificar se existe correção.

---

# 22. Opiniões fortes da comunidade

Podem ser usadas para dar vida ao artigo.

Mas contextualizar.

Exemplo:

> Em discussões no Reddit, parte dos usuários descreveu a mudança como um passo tardio, principalmente porque ferramentas concorrentes já oferecem algo semelhante há anos.

Isso é diferente de:

> Usuários dizem que o recurso é ruim.

---

# 23. Fóruns

Fóruns oficiais são especialmente úteis para:

- problemas recorrentes;
- compatibilidade;
- respostas de suporte;
- workarounds;
- regressões;
- versões afetadas.

Avaliar:

- data;
- versão;
- resposta oficial;
- número de pessoas afetadas;
- resolução.

---

# 24. Avaliações de usuários

Reviews em marketplaces ou diretórios podem ajudar a detectar:

- suporte ruim;
- mudanças de preço;
- problemas após atualização;
- bugs recorrentes;
- satisfação.

Mas sofrem com:

- viés de seleção;
- reviews falsas;
- usuários avaliando problemas fora do controle do produto;
- versões antigas.

Usar como sinal.

Não como prova isolada.

---

# 25. Claims de empresas

Toda afirmação comercial forte deve entrar na pesquisa com etiqueta mental:

> **claim do fabricante — ainda não verificado**

Exemplos:

- “50% mais rápido”
- “o plugin mais usado”
- “a solução nº 1”
- “reduz o tempo em 70%”
- “não adiciona peso ao site”
- “melhora Core Web Vitals”

---

# 26. Como validar um claim

Perguntar:

1. Qual é a métrica?
2. Qual era a baseline?
3. Em qual ambiente?
4. Quantas execuções?
5. Qual versão?
6. Contra qual concorrente?
7. Quem conduziu o teste?
8. Existe metodologia pública?
9. O teste é reproduzível?
10. Existe confirmação independente?

Se não houver resposta suficiente, escrever como claim:

> Segundo a empresa...

---

# 27. Benchmarks de terceiros

Antes de citar:

- verificar ambiente;
- hardware;
- localização;
- versão;
- cache;
- tema;
- plugins;
- tamanho do banco;
- método;
- número de execuções.

Benchmark sem metodologia tem valor limitado.

---

# 28. Testes próprios da PluginTema

Testes próprios têm alto valor editorial quando bem documentados.

Sempre registrar:

- objetivo;
- ambiente;
- versões;
- configurações;
- ferramenta;
- método;
- número de execuções;
- resultado;
- limitações.

Nunca escrever:

> X é 30% mais rápido.

quando o correto seria:

> No nosso ambiente de teste, X foi aproximadamente 30% mais rápido neste cenário.

---

# 29. Reprodutibilidade

Sempre que possível, a pesquisa técnica deve permitir que outra pessoa repita o teste.

Isso aumenta:

- credibilidade;
- utilidade;
- transparência.

Especialmente importante em PluginTema Labs.

---

# 30. Rumores

Rumor deve ser tratado como rumor.

Nunca transformar:

- leak;
- comentário;
- roadmap informal;
- issue;
- post em rede social;
- screenshot;

em anúncio confirmado.

Usar expressões como:

- há indícios;
- ainda não está confirmado;
- segundo relatos;
- a empresa ainda não anunciou oficialmente;
- pode;
- está sendo discutido;
- aparece em desenvolvimento.

---

# 31. Roadmaps

Roadmap não é compromisso absoluto.

Diferenciar:

- planejado;
- em desenvolvimento;
- em teste;
- confirmado;
- lançado.

Se não há data:

> ainda não há data oficial.

Não inventar previsão.

---

# 32. Notícias

Para notícia, pesquisar:

1. fonte original;
2. data do evento;
3. confirmação atual;
4. contexto anterior;
5. impacto;
6. reação técnica ou comunitária quando relevante.

Não reescrever apenas o comunicado.

---

# 33. Segurança

Conteúdo de segurança exige rigor maior.

Priorizar:

- advisory do desenvolvedor;
- WordPress.org;
- CVE/NVD quando aplicável;
- pesquisadores de segurança reconhecidos;
- Patchstack;
- Wordfence Intelligence;
- WPScan;
- repositórios oficiais.

Confirmar:

- versões afetadas;
- versões corrigidas;
- severidade;
- vetor;
- autenticação necessária;
- exploração ativa quando houver evidência;
- patch disponível.

---

# 34. Segurança: duas fontes por padrão

Para vulnerabilidades relevantes, buscar sempre que possível:

**fonte do fornecedor + fonte independente de segurança**

Se houver divergência, não esconder.

Explicar.

---

# 35. Não exagerar vulnerabilidades

Diferenciar:

- vulnerabilidade teórica;
- vulnerabilidade explorável;
- PoC disponível;
- exploração observada;
- exploração em massa.

Não usar “ataque ativo” sem evidência.

---

# 36. SEO

Conteúdo de SEO deve priorizar:

- Google Search Central;
- documentação oficial;
- Search Status Dashboard;
- comunicação de representantes oficiais;
- documentação de schema;
- estudos independentes bem desenhados.

Comunidade pode ajudar a detectar padrões.

Mas:

> correlação observada não é prova de fator de ranking.

---

# 37. Atualizações de algoritmo

Ao analisar updates de busca:

- confirmar se update foi anunciado;
- verificar início e fim quando disponíveis;
- separar volatilidade de confirmação oficial;
- evitar atribuir queda ou alta a update sem evidência suficiente.

---

# 38. Preços

Para preços, sempre usar a fonte oficial mais recente.

Confirmar:

- moeda;
- mensal/anual;
- imposto quando aplicável;
- número de sites;
- renovação;
- preço promocional;
- preço após promoção;
- plano necessário para o recurso citado.

Evitar usar snippet de busca como fonte final de preço.

---

# 39. Licenças

Ao falar de licenciamento, verificar:

- GPL;
- licença comercial;
- número de instalações;
- restrições;
- renovação;
- atualizações;
- suporte.

Não presumir condições com base em produtos semelhantes.

---

# 40. Compatibilidade

“Compatível com WordPress” é amplo demais.

Quando relevante, verificar:

- versão do WordPress;
- PHP;
- WooCommerce;
- multisite;
- Gutenberg;
- page builder;
- tema;
- cache;
- hospedagem;
- navegador.

Diferenciar:

- compatibilidade declarada;
- compatibilidade testada;
- relatos da comunidade.

---

# 41. Estatísticas

Para estatísticas:

- localizar fonte original;
- verificar metodologia;
- verificar universo;
- data;
- definição da métrica.

Exemplo:

> “43% da web usa WordPress”

precisa de fonte, data e definição adequada.

---

# 42. Números de mercado

Não misturar:

- market share entre todos os sites;
- market share entre sites com CMS conhecido;
- instalações ativas;
- downloads;
- usuários;
- sites detectados.

São métricas diferentes.

---

# 43. Estudos

Antes de citar estudo:

- quem financiou?
- quem executou?
- tamanho da amostra?
- método?
- período?
- limitações?
- conclusão do estudo é igual à conclusão do artigo?

Evitar extrapolação.

---

# 44. Inteligência artificial

Conteúdo sobre IA exige verificar:

- modelo;
- versão;
- data;
- plano;
- limites;
- preços;
- créditos;
- privacidade;
- retenção de dados;
- integração real;
- disponibilidade regional.

Recursos mudam rapidamente.

---

# 45. Documentação desatualizada

Nem toda documentação oficial está atualizada.

Se houver conflito:

1. verificar changelog;
2. verificar release atual;
3. testar;
4. procurar issue;
5. procurar anúncio mais recente.

Se a documentação aparentar estar defasada, mencionar.

---

# 46. Conflito entre fontes

Quando duas fontes confiáveis divergem:

não escolher silenciosamente a que combina com nossa tese.

Procedimento:

1. comparar datas;
2. comparar versões;
3. identificar escopo;
4. procurar fonte primária;
5. testar quando possível;
6. procurar terceira fonte;
7. explicar a divergência se continuar relevante.

---

# 47. Informação não confirmada

Se não for possível confirmar:

não preencher a lacuna com suposição.

Usar:

- não encontramos confirmação oficial;
- os relatos divergem;
- ainda não é possível afirmar;
- a documentação não esclarece;
- não conseguimos reproduzir.

Isso é melhor do que fingir certeza.

---

# 48. Ausência de evidência

Não confundir:

> “não encontramos relatos”

com:

> “não existe problema”.

Da mesma forma:

> “não encontramos evidência de ganho”

não significa:

> “não existe ganho”.

Usar linguagem proporcional.

---

# 49. Pesquisa para reviews

Antes de review:

- documentação oficial;
- preço;
- requisitos;
- changelog;
- histórico recente;
- suporte;
- testes próprios;
- Reddit;
- fóruns;
- concorrentes;
- problemas conhecidos.

Nunca produzir review completo apenas a partir da página de vendas.

---

# 50. Pesquisa para comparativos

Aplicar os mesmos critérios a todos os produtos.

Pesquisar, para cada opção:

- versão;
- preço;
- recursos;
- requisitos;
- performance;
- suporte;
- manutenção;
- lock-in;
- comunidade;
- problemas conhecidos;
- experiência prática.

Não pesquisar profundamente o favorito e superficialmente o concorrente.

---

# 51. Pesquisa de concorrentes

Concorrentes devem ser tratados com a mesma justiça que ferramentas vendidas pela PluginTema.

Não procurar apenas:

> “problemas do concorrente”

Pesquisar também:

> “vantagens do concorrente”

e vice-versa.

---

# 52. Conflito comercial

Quando a PluginTema vende ou possui relação comercial com algo citado:

a pesquisa deve ficar **mais rigorosa, não menos**.

Buscar:

- críticas;
- limitações;
- alternativas;
- desvantagens;
- concorrentes.

O objetivo é evitar viés inconsciente.

---

# 53. Pesquisa de opinião

Para artigos de opinião:

primeiro definir a tese.

Depois pesquisar:

- evidências que sustentam;
- evidências que contradizem;
- casos em que a tese falha;
- argumentos do outro lado.

Não pesquisar apenas para confirmar o que já pensamos.

---

# 54. Regra anti-viés de confirmação

Para análises importantes, fazer ao menos uma busca mental ou explícita por:

> “O que provaria que minha conclusão está errada?”

Se existir boa evidência contrária, incorporar.

---

# 55. Pesquisa por cenário

Uma ferramenta pode ser boa em um cenário e ruim em outro.

Pesquisar sempre:

- usuário iniciante;
- desenvolvedor;
- agência;
- loja WooCommerce;
- site simples;
- site de alto tráfego;
- múltiplos sites;

quando esses perfis forem relevantes.

---

# 56. Contexto brasileiro

Quando o conteúdo tiver implicações para usuários no Brasil, considerar:

- preço em real;
- impostos;
- meios de pagamento;
- suporte em português;
- latência;
- disponibilidade regional;
- LGPD;
- hospedagem;
- integração com serviços locais.

Não forçar contexto brasileiro onde ele não muda nada.

---

# 57. Traduções

Ao traduzir termos técnicos:

- manter o nome original quando isso ajuda a localizar a função;
- evitar tradução que altere o significado;
- observar como o WordPress traduz oficialmente o termo em PT-BR.

Exemplo:

> Full Site Editing (Edição completa do site)

quando a dupla nomenclatura for útil.

---

# 58. Capturas de tela como evidência

Screenshot pode provar que algo apareceu em determinado ambiente.

Mas não prova:

- comportamento universal;
- causa;
- existência em todas as versões;
- permanência futura.

Sempre registrar contexto.

---

# 59. Vídeos

Vídeos podem ser usados para:

- demonstração;
- entrevistas;
- anúncios;
- reprodução visual.

Mas fatos importantes devem ser confirmados em fonte textual quando possível, especialmente para facilitar revisão e atualização.

---

# 60. Conteúdo gerado por IA

Texto produzido por IA não é fonte.

IA pode ajudar a:

- organizar;
- resumir;
- sugerir caminhos de pesquisa;
- comparar documentos;
- localizar perguntas.

Mas informação factual deve voltar à fonte verificável.

Nunca citar “a IA disse”.

---

# 61. Snippets de busca

Snippets ajudam a localizar informação.

Não devem ser tratados como fonte final quando a página original está disponível.

Abrir a fonte.

---

# 62. Resultados patrocinados

Anúncio não ganha autoridade por aparecer primeiro.

Não confundir posicionamento pago com relevância editorial.

---

# 63. Domínios copiados e agregadores

Evitar:

- sites que copiam documentação;
- agregadores sem fonte;
- páginas geradas automaticamente;
- sites que não informam autoria;
- scrapers;
- conteúdo claramente reescrito de terceiros.

Voltar à origem.

---

# 64. Arquivo e histórico

Quando uma página foi alterada, histórico pode ser necessário para responder:

- quando mudou;
- como era antes;
- qual preço existia;
- qual promessa foi feita;
- quando recurso foi removido.

Deixar claro quando a informação é histórica.

---

# 65. Atualização de artigos antigos

Antes de atualizar um artigo existente:

1. identificar o que mudou;
2. verificar links;
3. verificar preços;
4. verificar versões;
5. verificar screenshots;
6. verificar recomendações;
7. verificar concorrentes;
8. verificar SEO;
9. remover informação obsoleta;
10. registrar mudança relevante quando necessário.

Não apenas mudar o ano do título.

---

# 66. Pesquisa mínima por tipo de conteúdo

## Notícia rápida

Mínimo:

- fonte original;
- confirmação de data;
- contexto essencial.

## Atualização de produto

Mínimo:

- release;
- changelog;
- documentação;
- problemas conhecidos quando relevantes.

## Tutorial

Mínimo:

- documentação;
- execução prática;
- versão utilizada.

## Review

Mínimo:

- documentação;
- preço;
- teste;
- changelog;
- comunidade;
- alternativas.

## Comparativo

Mínimo:

- fontes equivalentes para todos;
- preço;
- teste ou evidência independente;
- cenários de uso.

## Segurança

Mínimo:

- advisory;
- fonte independente;
- versão corrigida.

## PluginTema Labs

Mínimo:

- hipótese;
- metodologia;
- resultados;
- limitações.

---

# 67. Registro de pesquisa

Para artigos importantes, manter um bloco interno de pesquisa com:

- fontes;
- data de acesso;
- versão;
- fatos principais;
- dúvidas;
- pontos não confirmados;
- citações relevantes;
- hipóteses;
- testes realizados.

Esse bloco não precisa necessariamente aparecer publicado.

Serve para auditoria editorial.

---

# 68. Separar nota interna de conteúdo publicável

Durante pesquisa, podem existir notas como:

- `VERIFICAR`
- `FONTE`
- `HIPÓTESE`
- `TESTAR`
- `DÚVIDA`
- `CONFLITO`

Antes da publicação, nenhuma dessas marcações internas pode permanecer no artigo.

---

# 69. Matriz de confiança

Quando útil, classificar internamente uma afirmação:

## Alta confiança

- fonte primária clara;
- informação atual;
- confirmação independente quando necessária.

## Média confiança

- boa fonte;
- contexto parcial;
- falta algum detalhe.

## Baixa confiança

- relato;
- rumor;
- evidência limitada;
- informação antiga;
- conflito não resolvido.

A força da linguagem deve acompanhar a confiança.

---

# 70. Linguagem proporcional à confiança

## Alta confiança

> O WordPress 7.1 adicionou...

## Média confiança

> Os testes disponíveis indicam...

## Baixa confiança

> Há relatos de...

> Ainda não está claro se...

> Não encontramos confirmação oficial...

---

# 71. Quando testar

Testar quando a resposta depender de comportamento que pode ser observado diretamente.

Exemplos:

- recurso funciona?
- interface mudou?
- plugin adiciona script?
- configuração resolve?
- bug pode ser reproduzido?
- performance muda?
- incompatibilidade existe?

Pesquisa documental e teste se complementam.

---

# 72. Quando não testar

Não criar teste artificial quando:

- fonte oficial já resolve um fato simples;
- não há ambiente adequado;
- o teste seria enganoso;
- o resultado depende de escala que não conseguimos reproduzir.

Nesse caso, dizer que não testamos.

---

# 73. Não fingir acesso

Nunca escrever:

> “testamos”

se apenas lemos documentação.

Nunca escrever:

> “confirmamos no código”

se apenas lemos um artigo de terceiros.

Precisão sobre o método faz parte da credibilidade.

---

# 74. Perguntas obrigatórias antes de encerrar a pesquisa

Antes de começar a redação, responder:

1. Qual é a fonte original do principal fato?
2. A informação ainda está atual?
3. Qual versão estou analisando?
4. Há alguma fonte em conflito?
5. Existe interesse comercial?
6. O que a comunidade está relatando?
7. Preciso testar?
8. Há algum claim que ainda não foi validado?
9. O que é fato?
10. O que é observação?
11. O que é opinião?
12. O que ainda não sabemos?

---

# 75. Teste da fonte

Para cada fonte importante, perguntar:

- Quem publicou?
- Por quê?
- Quando?
- Com base em quê?
- É fonte original?
- Existe metodologia?
- Pode existir viés?
- A informação se aplica à versão atual?
- Outra fonte independente confirma?

---

# 76. Teste de atualidade

Antes de publicar conteúdo sujeito a mudança:

- [ ] pesquisar pela versão atual;
- [ ] verificar changelog recente;
- [ ] verificar documentação recente;
- [ ] verificar anúncios recentes;
- [ ] verificar issues recentes;
- [ ] confirmar preço;
- [ ] confirmar status do recurso.

---

# 77. Teste de confirmação cruzada

Para afirmações de maior impacto:

- [ ] existe fonte primária?
- [ ] existe fonte independente?
- [ ] ambas falam da mesma versão?
- [ ] ambas falam do mesmo cenário?
- [ ] existe conflito?
- [ ] a conclusão respeita o nível de evidência?

---

# 78. Teste anti-marketing

Antes de repetir um claim, perguntar:

> Se eu removesse o nome da empresa dessa frase, eu ainda acreditaria nela com as evidências disponíveis?

Se não:

tratar como claim, não como fato.

---

# 79. Teste anti-Reddit

Antes de usar uma opinião da comunidade:

> Isso é um padrão ou apenas uma história interessante?

Se for uma história isolada, apresentar como tal.

---

# 80. Teste anti-rumor

Perguntar:

- existe anúncio?
- existe código?
- existe release?
- existe documentação?
- existe apenas conversa?

A resposta define o vocabulário.

---

# 81. Teste anti-desatualização

Perguntar:

> Se alguém abrir este artigo daqui a seis meses, qual parte terá maior chance de estar errada?

Marcar essas partes para revisão futura quando possível.

---

# 82. O que fazer quando não encontramos resposta

Não inventar.

Podemos:

- dizer que não está documentado;
- relatar que não conseguimos confirmar;
- explicar o que sabemos;
- mostrar hipóteses como hipóteses;
- indicar como o leitor pode verificar no próprio ambiente.

---

# 83. Pesquisa e velocidade

Ser rápido não significa cortar verificação essencial.

Conteúdo simples pode exigir pouca pesquisa.

Conteúdo sensível ou técnico pode exigir muito mais.

A profundidade da pesquisa deve acompanhar o risco da afirmação.

---

# 84. Regra de proporcionalidade

Quanto maior a consequência de uma informação errada, maior deve ser o rigor.

Exemplos de alto rigor:

- vulnerabilidades;
- perda de dados;
- migração;
- compatibilidade;
- desempenho;
- decisões de compra caras;
- políticas;
- afirmações legais;
- mudanças de SEO;
- quebra de sites.

---

# 85. Regra final

> **A PluginTema não pesquisa para encontrar uma frase que confirme o que queremos escrever. Pesquisa para descobrir o que é verdade, o que ainda é incerto e o que realmente importa para o leitor.**

A pesquisa termina quando temos contexto suficiente para escrever com segurança — não quando encontramos a primeira fonte que concorda conosco.
