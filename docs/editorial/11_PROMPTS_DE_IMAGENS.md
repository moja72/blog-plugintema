# PluginTema — Prompts de Imagens

> Este arquivo transforma o `ESTILO_DE_IMAGENS.md` em instruções operacionais reutilizáveis para criação de imagens editoriais da PluginTema.
>
> Ele deve ser usado em conjunto com:
>
> - `ESTILO_DE_IMAGENS.md`
> - `VOZ_EDITORIAL.md`
> - `POSICIONAMENTO_EDITORIAL.md`
> - `ESTRUTURA_DE_ARTIGOS.md`
> - `CHECKLIST_DE_PUBLICACAO.md`
> - `DIRETRIZES_DE_SEO.md`
> - `TERMINOLOGIA_WORDPRESS.md`
>
> Princípio central:
>
> **o prompt deve descrever uma imagem PluginTema, não apenas uma imagem sobre o assunto.**
>
> O objetivo é permitir variedade de composição sem perder consistência visual.

---

# 1. Como usar este arquivo

Não copiar todos os módulos em todo prompt.

A construção recomendada é:

```text
PROMPT-BASE
+ FORMATO
+ ASSUNTO
+ COMPOSIÇÃO
+ MÓDULO TEMÁTICO
+ ASSETS OFICIAIS
+ TEXTO, se houver
+ RESTRIÇÕES
+ SAÍDA
```

Exemplo:

```text
PROMPT-BASE
+ CAPA HORIZONTAL
+ WORDPRESS
+ ATUALIZAÇÃO DE VERSÃO
+ TEXTO "7.1"
+ SEM LOGO PLUGINTEMA
```

---

# 2. Regra de ouro

Antes de gerar qualquer imagem, responder mentalmente:

1. Qual é o assunto principal?
2. Qual é o ponto focal?
3. Qual informação visual realmente importa?
4. A imagem precisa de texto?
5. Existe logo ou interface oficial que deve ser usado?
6. Qual módulo visual combina com o assunto?
7. A arte continuará reconhecível em tamanho pequeno?

Se essas respostas não estiverem claras, o prompt ainda está vago.

---

# 3. Variáveis padrão

Use estas variáveis quando montar prompts automaticamente.

```text
{TEMA}
{SUBTEMA}
{TIPO_DE_ARTIGO}
{CATEGORIA}
{COR_DOMINANTE}
{COR_SECUNDARIA}
{ELEMENTO_PRINCIPAL}
{ELEMENTOS_SECUNDARIOS}
{LOGO_OFICIAL}
{TEXTO_PRINCIPAL}
{LABELS}
{VERSAO}
{PROPORCAO}
{FUNDO}
{TIPO_DE_SAIDA}
```

Exemplo:

```text
{TEMA} = WordPress 7.1
{TIPO_DE_ARTIGO} = atualização
{ELEMENTO_PRINCIPAL} = número 7.1
{ELEMENTOS_SECUNDARIOS} = blocos de interface e controles responsivos
{TEXTO_PRINCIPAL} = 7.1
{PROPORCAO} = 2,05:1
```

---

# 4. Prompt-base mestre

Usar como fundação para capas e ilustrações editoriais.

```text
Crie uma ilustração editorial para o Blog PluginTema com estética neo-brutalista digital refinada.

A arte deve parecer moderna, jovem, tecnológica, limpa, vetorial, precisa e intencional. Use formas geométricas simples, contornos pretos marcantes e consistentes, sombras sólidas e duras deslocadas em uma única direção, alto contraste, cartões ou objetos com leve volume gráfico e cantos retos ou levemente arredondados.

A composição deve ter hierarquia visual clara: um único elemento principal dominante, de dois a cinco elementos secundários no máximo e espaço negativo suficiente. O assunto principal deve ser compreendido em menos de dois segundos.

Evite aparência de template genérico, stock corporativo, SaaS genérico, estética futurista neon, glassmorphism, 3D plástico, excesso de gradientes, iluminação cinematográfica, circuitos aleatórios, hologramas, elementos flutuando sem lógica, excesso de stickers e qualquer composição com aparência de imagem de IA sem direção de arte.

A profundidade deve vir de sobreposição, escala, contorno e sombra sólida — não de renderização 3D complexa.

Use uma paleta controlada: uma cor dominante, uma cor secundária, preto e branco, com no máximo uma cor adicional de destaque quando realmente necessária.

A imagem deve funcionar bem em desktop, mobile e compartilhamento social. Preserve área segura nas bordas e mantenha os elementos importantes afastados de possíveis recortes.

O resultado final deve parecer parte de um sistema visual editorial consistente da PluginTema mesmo sem exibir o logo da marca.
```

---

# 5. Prompt-base curto

Para situações em que o gerador já conhece o restante do contexto.

```text
Ilustração editorial PluginTema em neo-brutalismo digital refinado: acabamento vetorial limpo, contornos pretos espessos, sombras sólidas deslocadas, formas geométricas simples, alto contraste, poucos elementos, espaço negativo, ponto focal claro e composição moderna. Nada de neon tech genérico, glassmorphism, stock corporativo, 3D plástico, excesso de stickers ou aparência genérica de IA.
```

---

# 6. Formato de capa horizontal

Adicionar ao prompt:

```text
Formato horizontal amplo, aproximadamente 2,05:1, pensado como imagem destacada de artigo. Composição legível mesmo quando reduzida para card de blog ou tela mobile. Manter ponto focal dentro da área central segura e não colocar texto ou logos importantes próximos às extremidades.
```

Resoluções de referência:

- 1640 × 800;
- 1536 × 750;
- 1230 × 600.

---

# 7. Capa sem texto

Preferência padrão.

```text
Não inclua título, frase, slogan ou texto decorativo. A imagem deve comunicar o assunto apenas pela composição visual, objetos, símbolos e assets relevantes.
```

---

# 8. Capa com texto mínimo

Quando houver versão, número ou conceito curto.

```text
Inclua apenas o texto "{TEXTO_PRINCIPAL}", grande, altamente legível e integrado à composição. Não repetir o título completo do artigo. Usar tipografia forte, limpa e moderna, sem efeitos decorativos exagerados.
```

---

# 9. Regra para texto crítico

Quando a grafia precisar ser exata:

```text
Não gere nenhum outro texto além de "{TEXTO_PRINCIPAL}". A ortografia deve ser exata. Se não for possível garantir texto correto, priorize gerar a composição sem texto para que a tipografia seja aplicada posteriormente.
```

---

# 10. Módulo WordPress

```text
Representar WordPress de forma contemporânea, usando referências visuais ao ecossistema, editor, blocos, interface, templates ou estrutura de site. O logo oficial do WordPress pode aparecer quando for necessário identificar claramente a plataforma, mas não deve ser automaticamente o único ou maior elemento da composição.

Evitar usar em toda arte apenas um grande logo azul no centro. Buscar uma representação mais editorial do assunto específico.
```

---

# 11. WordPress — atualização de versão

```text
Criar uma capa editorial sobre uma nova versão do WordPress.

Usar "{VERSAO}" como ponto focal visual, com grande peso gráfico. Ao redor, incluir de dois a quatro elementos que representem as mudanças mais importantes da versão — por exemplo blocos, controles, painéis ou pequenos componentes de interface.

A imagem deve transmitir "nova versão + impacto prático", não apenas "anúncio de software".

Evitar confete, fogos, brilho de lançamento e estética de produto SaaS.
```

---

# 12. WordPress — Editor de Blocos

Usar a nomenclatura editorial correta conforme `TERMINOLOGIA_WORDPRESS.md`. fileciteturn1file1

```text
Representar o Editor de Blocos do WordPress por meio de blocos modulares, controles de interface, estrutura de conteúdo e elementos encaixáveis.

Evitar chamar visualmente o recurso de "Gutenberg" quando o assunto for simplesmente o Editor de Blocos atual.

A estética deve sugerir construção modular e controle visual.
```

---

# 13. WordPress — Editor do Site

```text
Representar o Editor do Site como uma visão estrutural do site inteiro: cabeçalho, conteúdo, navegação, templates e rodapé organizados em blocos.

Mostrar claramente que o assunto envolve edição global do site, e não apenas edição de uma postagem.
```

---

# 14. Módulo plugin

```text
Criar uma ilustração editorial centrada em um plugin WordPress.

Usar o logo oficial do plugin como elemento principal ou secundário quando houver asset real disponível. Ao redor, representar visualmente os recursos que realmente definem o produto.

Não inventar logo, interface, ícones oficiais ou funcionalidades.

Evitar uma simples colagem de logo com três ícones genéricos sem relação concreta com o produto.
```

---

# 15. Plugin — lançamento

```text
Transmitir lançamento ou atualização sem estética promocional exagerada.

Usar o produto como ponto focal e pequenos elementos que indiquem novidade, versão, novos recursos ou mudança de interface.

Pode usar um pequeno badge "NOVO" ou "{VERSAO}" se isso realmente fizer parte do conceito.
```

---

# 16. Plugin — problema ou regressão

```text
Representar visualmente o plugin com um elemento de falha controlada: bloco desalinhado, alerta, componente interrompido ou conexão quebrada.

A imagem deve comunicar problema técnico sem alarmismo.

Não usar caveira, fogo, explosão ou estética de desastre.
```

---

# 17. Módulo de review

As reviews devem manter neutralidade visual compatível com a metodologia editorial de `REVIEWS_E_COMPARATIVOS.md`. fileciteturn1file2

```text
Criar uma capa editorial de review do produto "{TEMA}".

O produto deve ser o ponto focal, acompanhado de elementos que representem seus recursos principais, experiência de uso e contexto real.

A imagem deve comunicar "avaliação", não "propaganda".

Não adicionar nota 10/10, estrelas exageradas, selo de "melhor" ou linguagem de aprovação automática.

O visual pode sugerir análise por meio de cards, checklist, lupa editorial ou componentes organizados, mas sem clichê visual.
```

---

# 18. Review com nota

Somente se o artigo realmente usar nota.

```text
Incluir a nota "{NOTA}/10" como elemento secundário claramente editorial, não como selo promocional. A nota não deve dominar a composição.
```

---

# 19. Módulo comparativo A vs. B

```text
Criar uma capa editorial comparando "{PRODUTO_A}" e "{PRODUTO_B}".

Dividir visualmente a composição em duas áreas equilibradas, com peso semelhante para as duas marcas. Usar logos oficiais e preservar proporção, cores e identidade de cada produto.

No centro, pode existir um pequeno elemento "VS" ou uma linha de comparação.

O objetivo é mostrar comparação justa, não batalha.

Evitar fogo, raios, socos, explosões, ringue, estética esportiva, expressão de vencedor/derrotado ou qualquer recurso que faça um produto parecer superior antes da análise.
```

---

# 20. Comparativo por conceito

Quando logos não forem necessários:

```text
Representar duas abordagens técnicas lado a lado, cada uma com linguagem visual equivalente. Usar símbolos, interfaces ou estruturas diferentes para mostrar contraste, sem sugerir vencedor antecipadamente.
```

---

# 21. Módulo ranking ou “melhores”

```text
Criar uma composição editorial de múltiplas opções sem transformar a imagem em uma fileira de logos.

Usar um elemento central que represente o problema ou categoria e distribuir de três a cinco soluções ao redor em cards ou stickers organizados.

Não atribuir 1º, 2º ou 3º lugar visualmente a menos que o artigo realmente tenha esse ranking.
```

---

# 22. Módulo WooCommerce

```text
Representar WooCommerce com elementos de comércio eletrônico: produto, carrinho, checkout, pedido, painel, pagamento ou loja.

Usar o logo oficial quando necessário, mas não depender exclusivamente dele.

A composição deve deixar claro qual etapa do e-commerce está sendo discutida.
```

---

# 23. WooCommerce — checkout

```text
Usar como foco uma interface simplificada de checkout, carrinho ou fluxo de pagamento, com cartões, produto e confirmação.

Evitar representação genérica de "shopping" sem relação com WordPress/WooCommerce.
```

---

# 24. Módulo construtores

```text
Representar construtores de páginas por componentes de layout, grids, containers, seções, widgets e controles visuais.

A estética deve transmitir montagem de interface.

Não usar martelo, chave de fenda ou ferramentas físicas como metáfora principal, salvo quando houver motivo criativo forte.
```

---

# 25. Elementor

```text
Se o assunto for Elementor, usar o logo oficial apenas quando necessário. Complementar com elementos visuais de editor, widgets, containers e responsividade.

Não criar uma cópia falsa da interface oficial se não houver screenshot real.
```

---

# 26. Bricks

```text
Representar Bricks com linguagem visual técnica, modular e limpa. Se usar logo, usar asset oficial.

Em comparativos com Elementor ou Divi, manter tamanho e peso visual equivalentes entre marcas.
```

---

# 27. Divi

```text
Se o conteúdo diferenciar Divi Theme e Divi Builder, representar o produto correto.

Não usar apenas a marca Divi de forma genérica quando a distinção for importante para o artigo.
```

---

# 28. Módulo performance

```text
Criar uma ilustração editorial sobre performance de WordPress.

Priorizar elementos como métricas, barras, waterfall, cronômetro, página leve, Core Web Vitals, requests, servidor ou fluxo de carregamento.

Evitar usar automaticamente foguete, velocímetro ou raio. Esses elementos podem aparecer apenas quando forem a melhor metáfora para a composição.

A arte deve transmitir medição e eficiência, não apenas "velocidade".
```

---

# 29. Core Web Vitals

```text
Representar LCP, INP e CLS como métricas distintas, usando cards ou indicadores gráficos simples e claros.

Não inventar valores se o artigo não fornece números reais.
```

---

# 30. Benchmark

```text
Criar uma ilustração de benchmark que transmita comparação mensurável: dois ou mais cards, barras ou resultados lado a lado.

Se houver números reais fornecidos, representá-los fielmente. Caso contrário, não gerar valores fictícios.

A estética pode ser técnica, mas precisa continuar editorial e legível.
```

---

# 31. Módulo SEO

As imagens devem complementar, e não substituir, as boas práticas visuais e de acessibilidade definidas em `DIRETRIZES_DE_SEO.md`. fileciteturn1file3

```text
Criar uma ilustração editorial sobre SEO usando elementos como SERP, snippet, headings, estrutura de conteúdo, entidades, indexação, Search Console ou arquitetura de páginas.

Evitar automaticamente lupa, gráfico ascendente e um grande "G" estilizado.

A arte deve representar o aspecto específico de SEO discutido no artigo.
```

---

# 32. SEO — atualização de algoritmo

```text
Representar uma mudança nos resultados ou no sistema de busca através de cards de SERP reorganizados, indicadores de mudança e sinais visuais de atualização.

Evitar dramatizar queda de tráfego como desastre.
```

---

# 33. SEO — Search Console

```text
Usar elementos inspirados em métricas, consultas, gráficos, indexação e páginas, sem falsificar uma screenshot real.

Se houver screenshot oficial fornecido, preferir utilizá-lo diretamente.
```

---

# 34. Módulo segurança

```text
Criar uma ilustração editorial sobre segurança WordPress.

Usar elementos como cadeado, escudo, versão de plugin, aviso, patch, painel, arquivo protegido ou componente vulnerável.

Evitar completamente o clichê de hacker encapuzado, máscara, código verde, caveira, sala escura e laptop cinematográfico.

A imagem deve comunicar risco técnico e ação, não medo.
```

---

# 35. Segurança — vulnerabilidade

```text
Mostrar um componente WordPress ou plugin com uma falha visual pequena e clara, acompanhada de escudo, aviso ou patch.

Se versões afetadas forem parte central do artigo, "{VERSAO_AFETADA}" e "{VERSAO_CORRIGIDA}" podem aparecer como labels curtos.

Não usar texto como "URGENTE" ou "PERIGO" sem necessidade editorial.
```

---

# 36. Segurança — correção

```text
Representar o conceito de correção ou patch com uma estrutura anteriormente aberta agora protegida ou conectada.

A sensação deve ser de resolução técnica.
```

---

# 37. Módulo inteligência artificial

```text
Criar uma ilustração editorial sobre IA aplicada ao ecossistema WordPress.

Preferir prompts, texto, fluxos, nós, automação, integração, agentes, conectores ou blocos inteligentes.

Evitar cérebro neon, robô humanoide genérico, rosto holográfico, circuito azul brilhante e fundo cyberpunk.

A IA deve aparecer como ferramenta dentro de um fluxo real.
```

---

# 38. IA + WordPress

```text
Integrar elementos de WordPress com um fluxo de IA: prompt entrando, processamento em nós ou cartões e resultado sendo aplicado ao site.

A composição deve comunicar integração, não "IA mágica".
```

---

# 39. Módulo PluginTema Labs

O Labs pode ser mais experimental, mas precisa preservar transparência e metodologia conforme o sistema editorial. fileciteturn1file8

```text
Criar uma ilustração editorial para PluginTema Labs com estética neo-brutalista mais experimental e técnica.

Usar elementos de laboratório digital: grids, medições, terminais, benchmarks, setas, caixas de experimento, componentes desmontados, hipóteses, fluxos e gráficos.

A composição pode ser mais densa do que uma capa normal, mas deve continuar clara e intencional.

Adicionar um pequeno badge "LABS" quando fizer sentido.

Transmitir exploração e teste real — não ciência fictícia ou estética de laboratório químico genérico.
```

---

# 40. Labs — experimento

```text
Representar visualmente:

HIPÓTESE → TESTE → RESULTADO

usando três componentes conectados, com setas e linguagem gráfica simples.

O resultado pode ser inesperado ou inconclusivo; não precisa parecer sucesso.
```

---

# 41. Labs — automação

```text
Usar nós conectados, serviços, scripts, WordPress, APIs e saídas de dados em um fluxo técnico claro.

Evitar automação representada apenas por engrenagens.
```

---

# 42. Labs — terminal

```text
Pode incluir um terminal estilizado com poucas linhas abstratas ou comandos reais fornecidos.

Não gerar comandos fictícios que pareçam instruções reais se eles não foram fornecidos.
```

---

# 43. Módulo notícia

```text
Criar uma capa editorial mais simples e imediata.

Usar o evento, produto, marca ou versão como ponto focal e no máximo dois ou três elementos de contexto.

Não dramatizar. A imagem deve comunicar "isso aconteceu" com clareza.
```

---

# 44. Módulo opinião/editorial

```text
Criar uma composição mais conceitual e autoral.

Pode usar metáfora visual, contraste, exagero gráfico controlado e ironia leve.

A imagem deve representar a tese central do artigo, não apenas o assunto nominal.

Evitar transformar opinião forte em caricatura ofensiva ou ataque pessoal.
```

---

# 45. Módulo tutorial

```text
Criar uma imagem que comunique execução prática.

Usar sequência visual curta, interface, cursor, botão, bloco ou pequenos passos.

A capa não precisa mostrar todas as etapas; deve representar claramente a ação que será realizada.
```

---

# 46. Tutorial com screenshot real

```text
Usar o screenshot fornecido como elemento funcional central, sem alterar seu conteúdo factual.

Integrá-lo à identidade PluginTema com moldura de contorno preto, sombra sólida e pequenas anotações visuais quando necessário.

Não redesenhar a interface.
```

---

# 47. Screenshot estilizado

Este módulo serve para enquadrar uma captura real, não para fabricá-la.

```text
Preservar integralmente o conteúdo factual do screenshot fornecido.

Recortar apenas áreas irrelevantes, manter legibilidade, ocultar dados sensíveis quando necessário e inserir a captura em um card neo-brutalista com borda preta espessa e sombra sólida deslocada.

Pode adicionar no máximo duas ou três anotações: seta, caixa, círculo ou label curto.

Não alterar textos, valores, botões, menus ou estados da interface.
```

---

# 48. Mockup de interface

```text
Criar uma interface estilizada e claramente ilustrativa, sem imitar exatamente um produto real.

A composição deve ser identificável como conceito/mockup, não como screenshot.

Evitar logos oficiais ou nomes reais se isso puder levar o leitor a acreditar que a interface existe.
```

---

# 49. Módulo diagrama

```text
Criar um diagrama editorial neo-brutalista claro.

Usar caixas geométricas, contorno preto, sombra sólida discreta, ícones simples e setas consistentes.

Manter o fluxo linear sempre que possível.

Não adicionar componentes apenas para parecer tecnicamente complexo.
```

---

# 50. Diagrama de arquitetura

```text
Organizar a arquitetura em camadas ou fluxo.

Cada bloco deve representar uma função real.

Usar labels curtos e setas sem cruzamentos desnecessários.

A clareza técnica tem prioridade sobre decoração.
```

---

# 51. Módulo gráfico

```text
Criar um gráfico editorial limpo e compatível com a identidade PluginTema.

Manter eixo, escala, labels, unidades e valores corretos.

Aplicar identidade por meio de bordas, tipografia, cards e layout — nunca distorcendo os dados.

Não gerar dados que não tenham sido fornecidos.
```

---

# 52. Módulo antes/depois

```text
Criar composição dividida em "antes" e "depois" mantendo a mesma escala, enquadramento e condição visual.

A diferença deve refletir somente a mudança real.

Não exagerar contraste ou manipular elementos para amplificar artificialmente o resultado.
```

---

# 53. Módulo ícone de categoria

```text
Criar um ícone vetorial simples para a categoria "{CATEGORIA}".

Estética neo-brutalista refinada, traço preto marcante, geometria simples, leitura imediata em tamanho pequeno e no máximo duas cores além de preto/branco.

O ícone deve funcionar isoladamente, sem texto e sem depender de detalhes pequenos.

Evitar ícones 3D, emoji, gradientes, glassmorphism e excesso de detalhes.
```

---

# 54. Ícone Performance

```text
Usar conceito de medição, eficiência, barras, métrica ou velocidade controlada.

Evitar depender sempre de foguete ou raio.
```

---

# 55. Ícone SEO

```text
Usar busca, estrutura, página, snippet, indexação ou conexões semânticas.

Evitar lupa genérica como única solução.
```

---

# 56. Ícone Segurança

```text
Usar escudo, cadeado ou camada de proteção com geometria simples.

Nada de hacker ou caveira.
```

---

# 57. Ícone Construtores

```text
Usar grid, layout, blocos, container ou componentes encaixáveis.
```

---

# 58. Ícone PluginTema Labs

```text
Usar experimento digital, frasco abstrato combinado com código, nó técnico, medição ou laboratório visual minimalista.

Evitar estética escolar de laboratório químico.
```

---

# 59. Módulo sticker

```text
Criar um sticker vetorial neo-brutalista isolado de "{ELEMENTO_PRINCIPAL}".

Usar contorno preto espesso, forma compacta, sombra sólida curta quando fizer sentido, poucos detalhes e leitura imediata.

O sticker deve funcionar como elemento de composição em outras artes.

Sem fundo.
```

---

# 60. Sticker de logo

Quando houver logo oficial:

```text
Usar o logo oficial fornecido sem redesenhá-lo ou distorcê-lo.

Criar ao redor apenas a linguagem de sticker: contorno externo, pequena borda e sombra sólida, preservando integralmente o logo.
```

---

# 61. Módulo fundo transparente

```text
Entregar o elemento completamente isolado sobre transparência real.

Não criar fundo branco.
Não criar fundo quadriculado.
Não simular transparência.
Não criar halo branco, borda residual ou sombra cortada.

Preservar canal alpha real ao redor de todo o objeto.
```

---

# 62. Transparência para sticker

```text
O contorno e a sombra fazem parte do objeto e devem permanecer visíveis. Apenas a área externa ao sticker deve ser transparente.
```

---

# 63. Asset isolado sem sombra

```text
Elemento vetorial isolado, sem fundo e sem sombra externa, preparado para composição posterior.
```

---

# 64. Módulo fotografia real

```text
Usar fotografia real apenas quando o assunto exigir pessoa, evento, espaço ou produto físico real.

Preservar autenticidade documental.

A integração à identidade PluginTema pode usar recorte, moldura, contorno, sombra sólida, labels ou stickers.

Não alterar fatos visuais da fotografia.
```

---

# 65. Pessoa real

```text
Preservar identidade, traços, proporções e características reconhecíveis da pessoa.

Não transformar a pessoa em alguém diferente.

Qualquer estilização deve ser claramente artística e não documental.
```

---

# 66. Módulo humor

```text
Adicionar humor visual leve e inteligente relacionado ao cotidiano WordPress.

Preferir ironia visual, excesso controlado de plugins, bloco rebelde, loading, update ou comportamento reconhecível pela comunidade.

Não transformar a composição em meme genérico.
```

---

# 67. Humor com plugins

```text
Representar uma situação de "plugins demais" usando cartões ou ícones acumulados de maneira deliberadamente exagerada, mas visualmente organizada.

Evitar logos reais aleatórios se eles não forem relevantes ao artigo.
```

---

# 68. Módulo cores

```text
Usar "{COR_DOMINANTE}" como cor principal e "{COR_SECUNDARIA}" como apoio, além de preto e branco.

A cor da categoria é apenas acento: não alterar os pilares de contorno, sombra, tipografia e composição da identidade PluginTema.
```

---

# 69. Fundo claro

```text
Fundo predominantemente claro, limpo e sólido, com alto contraste dos elementos. Usar espaço negativo generoso.
```

---

# 70. Fundo escuro

```text
Fundo preto ou quase preto, mantendo contornos, cartões e tipografia perfeitamente legíveis.

A arte deve continuar neo-brutalista; não converter para estética neon/cyberpunk.
```

---

# 71. Fundo colorido

```text
Fundo sólido em "{COR_DOMINANTE}", com elementos em branco, preto e "{COR_SECUNDARIA}".

Evitar gradientes se não forem necessários.
```

---

# 72. Fundo geométrico

```text
Usar poucas formas geométricas amplas como suporte de composição, sem competir com o elemento principal.
```

---

# 73. Regras de logo

Adicionar quando houver marca real:

```text
Usar apenas logos oficiais fornecidos ou claramente disponíveis como asset.

Não reconstruir logos por aproximação.
Não alterar proporção.
Não trocar tipografia.
Não modificar símbolo.
Não inventar versão alternativa.
Não adicionar texto falso ao logo.
```

---

# 74. Regra de logos em comparação

```text
Os logos de "{PRODUTO_A}" e "{PRODUTO_B}" devem ter peso visual equivalente. Não aumentar um deles para sugerir favoritismo.
```

---

# 75. Regra de marca PluginTema

```text
O logo PluginTema é opcional. Se aparecer, deve funcionar como assinatura discreta e não competir com o assunto.

A identidade deve continuar reconhecível mesmo sem o logo.
```

---

# 76. Negative prompt — universal

Quando o gerador aceitar instruções negativas, usar:

```text
Evitar: stock corporativo, SaaS genérico, glassmorphism, futurismo neon, cyberpunk, cérebro de IA, robô humanoide genérico, circuito azul, 3D plástico, iluminação cinematográfica, glow, sombras suaves corporativas, blur excessivo, gradientes genéricos, blobs, excesso de stickers, arco-íris, bordas finas, tipografia ornamental, texto longo, logos deformados, interface inventada apresentada como real, números fictícios, gráficos fictícios, elementos sem função, composição lotada, thumbnail de YouTube, setas vermelhas gigantes, fogo, explosões, sensacionalismo.
```

---

# 77. Negative prompt — segurança

```text
Sem hacker encapuzado, máscara, caveira, código verde, laptop em sala escura, mãos digitando em teclado com neon, cadeado holográfico.
```

---

# 78. Negative prompt — IA

```text
Sem cérebro neon, robô humanoide, cabeça holográfica, circuitos brilhantes, rosto artificial futurista, cidade cyberpunk.
```

---

# 79. Negative prompt — performance

```text
Sem foguete automático, velocímetro clichê, raio gigante ou fogo saindo de computador, a menos que solicitado explicitamente.
```

---

# 80. Negative prompt — comparativo

```text
Sem luta, ringue, socos, fogo, raios, explosões, vencedor e perdedor visual, logo maior para um dos lados ou estética de torcida.
```

---

# 81. Prompt pronto — capa WordPress

```text
Crie uma capa editorial horizontal, proporção aproximada 2,05:1, para um artigo do Blog PluginTema sobre "{TEMA}".

Use estética neo-brutalista digital refinada: acabamento vetorial limpo, contornos pretos espessos, sombras sólidas deslocadas para a direita e para baixo, formas geométricas simples, alto contraste e espaço negativo.

O elemento principal deve ser "{ELEMENTO_PRINCIPAL}". Inclua no máximo quatro elementos secundários relacionados a "{SUBTEMA}".

Representar WordPress por meio de blocos, interface e componentes do ecossistema, sem depender apenas de um grande logo central.

Paleta: "{COR_DOMINANTE}", "{COR_SECUNDARIA}", preto e branco.

Não inserir título completo. {INSTRUCAO_DE_TEXTO}

A imagem deve ser entendida em menos de dois segundos e permanecer clara em mobile.

Evitar SaaS genérico, neon tech, 3D plástico, glassmorphism, logos deformados, excesso de elementos e aparência genérica de IA.
```

---

# 82. Prompt pronto — review

```text
Crie uma capa editorial horizontal 2,05:1 para um review da PluginTema sobre "{PRODUTO}".

Use o produto como ponto focal e represente visualmente os recursos "{RECURSOS_PRINCIPAIS}" com poucos elementos secundários.

A estética deve ser neo-brutalista digital refinada: vetor limpo, contorno preto espesso, sombra sólida deslocada, alto contraste, formas geométricas simples e composição editorial.

A imagem deve comunicar análise e avaliação, não propaganda.

Usar logo oficial apenas se fornecido. Não inventar interface ou recurso.

Não usar estrelas exageradas, 10/10, selo "melhor", troféu ou mensagem promocional.

Paleta: "{COR_DOMINANTE}", preto, branco e uma cor secundária controlada.

Manter área segura e legibilidade em mobile.
```

---

# 83. Prompt pronto — comparativo

```text
Crie uma capa editorial horizontal 2,05:1 comparando "{PRODUTO_A}" e "{PRODUTO_B}" para o Blog PluginTema.

Divida a composição em duas áreas equilibradas. Use os logos oficiais fornecidos com peso visual equivalente.

Representar "{DIFERENCIAL_A}" no lado A e "{DIFERENCIAL_B}" no lado B com elementos visuais simples.

No centro, usar apenas um pequeno "VS" ou divisor gráfico.

Estética neo-brutalista digital refinada: acabamento vetorial, contornos pretos espessos, sombras sólidas, alto contraste, fundo limpo, poucos elementos e boa área negativa.

Não sugerir vencedor antecipadamente.

Sem fogo, raios, luta, explosões, setas agressivas ou thumbnail de YouTube.
```

---

# 84. Prompt pronto — segurança

```text
Crie uma capa editorial horizontal 2,05:1 para um artigo PluginTema sobre "{TEMA_DE_SEGURANCA}".

O ponto focal deve ser "{ELEMENTO_AFETADO}", representado com uma falha técnica visual controlada e um elemento de proteção/correção.

Usar estética neo-brutalista refinada, vetor limpo, contorno preto espesso, sombra sólida e paleta controlada.

Se necessário, mostrar "{VERSAO_AFETADA}" e "{VERSAO_CORRIGIDA}" como labels curtos.

A imagem deve comunicar risco técnico e ação recomendada sem alarmismo.

Sem hacker encapuzado, caveira, código verde, máscara, laptop cinematográfico ou estética cyberpunk.
```

---

# 85. Prompt pronto — performance

```text
Crie uma capa editorial horizontal 2,05:1 para um artigo PluginTema sobre "{TEMA_DE_PERFORMANCE}".

Usar "{METRICA_OU_ELEMENTO}" como ponto focal. Representar medição, eficiência e comportamento real por meio de barras, waterfall, cronômetro, requests, página, servidor ou Core Web Vitals.

Estética neo-brutalista digital refinada, acabamento vetorial, contorno preto espesso, sombras sólidas e composição limpa.

Não inventar valores.

Evitar foguete, velocímetro e raio como solução automática.
```

---

# 86. Prompt pronto — SEO

```text
Crie uma capa editorial horizontal 2,05:1 para um artigo PluginTema sobre "{TEMA_DE_SEO}".

Representar o conceito por meio de "{ELEMENTOS_SEO}", usando SERP, snippets, headings, páginas, entidades, Search Console ou indexação conforme o assunto.

Estética neo-brutalista digital refinada com vetor limpo, contornos pretos, sombras sólidas, alto contraste e poucos elementos.

Evitar lupa genérica, grande logo do Google, gráfico subindo sem contexto e estética de agência de marketing genérica.
```

---

# 87. Prompt pronto — PluginTema Labs

```text
Crie uma capa editorial horizontal 2,05:1 para PluginTema Labs sobre o experimento "{EXPERIMENTO}".

Use uma linguagem neo-brutalista mais técnica e experimental: grids, medição, terminal, componentes, cards de teste, setas e resultados.

Organize visualmente a lógica "{HIPOTESE} → {TESTE} → {RESULTADO}".

Adicionar um pequeno badge "LABS".

A imagem pode ter maior densidade de informação que uma capa comum, mas deve permanecer clara.

Não fingir ciência. Não inventar números ou resultados.
```

---

# 88. Prompt pronto — tutorial

```text
Crie uma capa editorial horizontal 2,05:1 para um tutorial PluginTema sobre "{ACAO}".

Representar visualmente a ação com um fluxo simples de dois ou três elementos: origem, ação principal e resultado.

Usar interface real somente se fornecida.

Estética neo-brutalista digital refinada, vetor limpo, contorno preto, sombra sólida, alto contraste e composição clara.

A imagem deve comunicar "como fazer" sem precisar escrever o passo a passo completo.
```

---

# 89. Prompt pronto — sticker transparente

```text
Crie um sticker vetorial isolado de "{ELEMENTO}".

Estética PluginTema: neo-brutalismo refinado, contorno preto espesso, poucas formas, alto contraste e leve sombra sólida integrada ao sticker.

O elemento deve ter leitura imediata em tamanho pequeno.

Entregar com fundo totalmente transparente e canal alpha real.

Não desenhar fundo quadriculado. Não usar falso alpha. Não deixar halo branco ou área residual ao redor.
```

---

# 90. Prompt pronto — ícone

```text
Crie um ícone vetorial de "{CONCEITO}" para o Blog PluginTema.

Neo-brutalismo refinado, geometria simples, contorno preto marcante, até duas cores além de preto/branco, leitura imediata em 24–48 px e sem texto.

O ícone deve funcionar em navegação, categoria e card.

Sem 3D, gradiente, emoji, glassmorphism ou detalhes minúsculos.
```

---

# 91. Prompt pronto — screenshot com anotação

```text
Edite o screenshot fornecido preservando integralmente seu conteúdo factual.

Recorte apenas o necessário, oculte qualquer dado sensível e integre a captura ao estilo PluginTema com uma moldura de contorno preto e sombra sólida.

Adicionar somente as anotações necessárias: "{ANOTACOES}".

Não alterar textos, botões, valores, menus, estados ou layout real da interface.
```

---

# 92. Prompt pronto — diagrama técnico

```text
Crie um diagrama técnico editorial PluginTema mostrando o fluxo:

{FLUXO}

Usar caixas geométricas, contorno preto espesso, sombra sólida discreta, ícones simples, setas consistentes e alto contraste.

Organizar da esquerda para a direita ou de cima para baixo, sem cruzamentos desnecessários.

Cada elemento deve representar uma função real.

Não adicionar componentes decorativos apenas para aumentar complexidade.
```

---

# 93. Prompt pronto — fundo transparente de objeto

```text
Crie "{OBJETO}" como asset vetorial isolado, limpo e reutilizável.

Usar estética neo-brutalista PluginTema, contorno preto consistente e detalhes reduzidos.

Sem texto.
Sem cenário.
Sem fundo.
Sem superfície.
Sem moldura.

Fundo totalmente transparente com canal alpha real e bordas limpas.
```

---

# 94. Prompt pronto — imagem conceitual de opinião

```text
Crie uma capa editorial conceitual para a tese:

"{TESE}"

Transforme a tese em uma metáfora visual simples, moderna e inteligente relacionada ao ecossistema WordPress.

Use neo-brutalismo refinado, composição forte, poucos elementos, contorno preto espesso, sombra sólida e alto contraste.

A imagem pode ter ironia leve, mas não deve atacar pessoas, distorcer marcas ou recorrer a meme genérico.
```

---

# 95. Prompt pronto — atualização problemática

```text
Crie uma capa editorial mostrando uma atualização de "{PRODUTO}" que exige cautela.

Representar a nova versão como elemento principal e usar um pequeno sinal visual de atenção, compatibilidade ou regressão.

A sensação deve ser "teste antes de atualizar", não "catástrofe".

Sem sirene, fogo, caveira ou mensagem alarmista.
```

---

# 96. Prompt pronto — recurso nativo vs. plugin

```text
Crie uma capa editorial comparando um recurso nativo do WordPress com a necessidade de usar um plugin externo.

À esquerda, representar o recurso nativo por componentes integrados ao WordPress. À direita, representar o plugin como dependência adicional.

Manter os dois lados visualmente justos.

A imagem deve comunicar a pergunta "ainda precisamos do plugin?" sem declarar visualmente a resposta.
```

---

# 97. Prompt pronto — muitos plugins

```text
Crie uma ilustração editorial com humor leve sobre excesso de plugins em WordPress.

Mostrar um painel ou site visualmente sobrecarregado por vários cartões de plugin empilhados, todos organizados dentro da estética neo-brutalista.

O humor deve vir da quantidade e da situação, não de texto ou meme.

Não usar logos reais aleatórios.
```

---

# 98. Prompt pronto — notícia rápida

```text
Crie uma capa editorial simples para a notícia "{NOTICIA}".

Use um único elemento principal e no máximo dois elementos secundários.

Neo-brutalismo refinado, alto contraste, contorno preto e sombra sólida.

Não dramatizar e não adicionar texto além de "{LABEL_CURTO}" se ele for realmente necessário.
```

---

# 99. Prompt de revisão da arte

Depois de gerar uma imagem, usar este prompt para refinamento:

```text
Revise esta imagem para aproximá-la da identidade editorial PluginTema.

Preserve o conceito principal, mas:
- reduza elementos sem função;
- deixe o ponto focal mais claro;
- torne os contornos pretos mais consistentes;
- substitua sombras suaves por sombras sólidas deslocadas;
- reduza efeitos 3D e iluminação realista;
- aumente o espaço negativo;
- remova aparência genérica de IA;
- simplifique a paleta;
- mantenha acabamento vetorial e editorial;
- preserve logos oficiais sem alteração;
- garanta leitura em tamanho pequeno.

Não adicione novos elementos apenas para preencher espaço.
```

---

# 100. Prompt de simplificação

```text
Simplifique a composição em aproximadamente 20%.

Preserve o assunto, o ponto focal e os elementos indispensáveis.

Remova objetos redundantes, pequenos detalhes, texturas, efeitos, stickers e elementos decorativos que não ajudam a explicar o conceito.

A versão final deve parecer mais editorial, mais limpa e mais intencional.
```

---

# 101. Prompt de correção neo-brutalista

```text
Refaça o acabamento para neo-brutalismo digital refinado.

Use:
- contorno preto espesso e uniforme;
- sombra sólida curta e deslocada;
- cores sólidas;
- geometria simples;
- cantos retos ou levemente arredondados;
- alto contraste;
- acabamento vetorial.

Remover:
- sombras suaves;
- glow;
- blur;
- 3D plástico;
- gradientes genéricos;
- glassmorphism;
- iluminação cinematográfica.
```

---

# 102. Prompt de correção de IA genérica

```text
A imagem está com aparência genérica de arte gerada por IA.

Refaça mantendo o conceito, mas:
- reduza detalhes aleatórios;
- elimine objetos flutuando sem função;
- remova futurismo neon;
- elimine luz cinematográfica;
- simplifique a perspectiva;
- use geometria vetorial;
- aplique contorno preto e sombra sólida;
- use menos elementos e mais espaço negativo.

O resultado deve parecer uma ilustração editorial desenhada por um diretor de arte, não uma renderização automática.
```

---

# 103. Prompt de correção de logo

```text
Preserve exatamente o logo oficial fornecido.

Não redesenhe.
Não altere proporção.
Não modifique tipografia.
Não troque cores.
Não acrescente texto.
Não simplifique o símbolo.

Apenas integre o logo à composição ao redor.
```

---

# 104. Prompt de remoção de texto

```text
Remova todo texto gerado da imagem sem alterar a composição principal.

Reconstrua o fundo e os elementos que estavam atrás do texto de forma natural.

A arte final deve funcionar sem tipografia.
```

---

# 105. Prompt de fundo transparente real

```text
Remova completamente o fundo e entregue somente o objeto principal com transparência real.

Não desenhe padrão quadriculado.
Não substitua o fundo por branco.
Não mantenha retângulo transparente falso.
Não deixe halo ao redor.

Preservar contorno, detalhes internos e sombra pertencente ao objeto.
```

---

# 106. Prompt de versão escura

```text
Crie uma versão dark da mesma composição.

Preserve posição, escala, elementos e hierarquia.

Troque o fundo para preto ou quase preto e adapte cores, contornos e tipografia apenas o necessário para manter contraste.

Não transformar em estética neon.
```

---

# 107. Prompt de versão clara

```text
Crie uma versão light da mesma composição.

Preserve posição, escala, elementos e hierarquia.

Use fundo branco ou muito claro, mantendo contornos pretos, sombras sólidas e cores de destaque.

A imagem deve continuar forte e neo-brutalista.
```

---

# 108. Prompt de adaptação para mobile

```text
Adapte esta composição para formato vertical/mobile.

Preserve o mesmo conceito, ponto focal, paleta e identidade.

Reorganize os elementos; não simplesmente recorte ou estique a arte horizontal.

Garanta que logo, texto e elemento principal permaneçam totalmente visíveis.
```

---

# 109. Prompt para Open Graph

```text
Adapte a composição para compartilhamento social, mantendo área segura generosa nas laterais e no topo.

O ponto focal deve permanecer claro mesmo em previews pequenos.

Evitar texto pequeno e elementos importantes nas extremidades.
```

---

# 110. Prompt para card pequeno

```text
Simplifique esta capa para funcionar em card de blog pequeno.

Manter apenas o ponto focal e até dois elementos secundários.

A leitura precisa funcionar com aproximadamente 320 px de largura.
```

---

# 111. Módulo de factualidade

Adicionar quando a imagem envolver produto real:

```text
Não inventar fatos visuais.

Não inventar:
- versão;
- preço;
- recurso;
- interface;
- botão;
- logo;
- resultado;
- gráfico;
- número;
- selo.

Se um elemento factual não foi fornecido, representá-lo de forma abstrata ou omiti-lo.
```

---

# 112. Módulo de neutralidade visual

Adicionar em reviews e comparativos:

```text
A composição não deve antecipar a conclusão editorial.

Nenhum produto deve receber automaticamente:
- tamanho maior;
- posição superior;
- iluminação melhor;
- cor mais atraente;
- selo;
- troféu;
- check verde;
- expressão de vencedor.

A imagem deve permitir que o texto faça a avaliação.
```

---

# 113. Módulo de acessibilidade visual

```text
Manter contraste forte, formas identificáveis e tipografia legível.

Não depender apenas de cor para diferenciar estados importantes.

Evitar labels minúsculos ou elementos indispensáveis que desapareçam quando a imagem for reduzida.
```

---

# 114. Módulo de reutilização

Para assets de biblioteca:

```text
Criar o elemento de forma modular e reutilizável, sem fundo editorial específico e sem texto contextual.

A silhueta deve continuar reconhecível em outras composições.
```

---

# 115. Ordem recomendada para gerar uma capa

Fluxo:

```text
1. Definir conceito.
2. Escolher ponto focal.
3. Escolher módulo temático.
4. Decidir se precisa de asset oficial.
5. Decidir se precisa de texto.
6. Gerar composição.
7. Aplicar teste de redução.
8. Aplicar teste de factualidade.
9. Aplicar revisão visual.
10. Gerar variantes apenas se necessário.
```

---

# 116. Brief mínimo para capa

Antes de gerar, preencher:

```text
Artigo:
Categoria:
Tipo de conteúdo:
Ideia central:
Ponto focal:
Elementos secundários:
Asset oficial necessário:
Texto na imagem:
Cor dominante:
Cor secundária:
Formato:
```

---

# 117. Exemplo preenchido — WordPress 7.1

```text
Artigo: WordPress 7.1: o que mudou e o que revisar antes de atualizar
Categoria: WordPress
Tipo de conteúdo: atualização/análise
Ideia central: atualização importante, mas nem tudo tem o mesmo impacto
Ponto focal: 7.1
Elementos secundários: controles responsivos, blocos, painel
Asset oficial necessário: logo WordPress opcional
Texto na imagem: 7.1
Cor dominante: cor da categoria WordPress
Cor secundária: cor de apoio da marca
Formato: 2,05:1
```

Prompt resultante:

```text
Crie uma capa editorial horizontal 2,05:1 para um artigo PluginTema sobre o WordPress 7.1.

Use o número "7.1" como ponto focal grande e forte. Ao redor, inclua três pequenos componentes visuais que representem controles responsivos, blocos e interface do WordPress.

A estética deve ser neo-brutalista digital refinada: vetor limpo, contornos pretos espessos, sombras sólidas deslocadas para a direita e para baixo, formas geométricas simples, alto contraste e bastante espaço negativo.

Use referências ao ecossistema WordPress sem depender exclusivamente de um grande logo no centro.

Não incluir o título completo. O único texto permitido é "7.1".

A arte deve transmitir atualização + impacto prático, não celebração de lançamento.

Sem neon, glassmorphism, 3D plástico, confete, foguetes ou aparência genérica de IA.
```

---

# 118. Exemplo preenchido — comparativo

```text
Artigo: Elementor ou Bricks: qual faz mais sentido para o seu projeto?
Categoria: Construtores
Tipo: comparativo
Ponto focal: Elementor vs Bricks
Elementos: componentes de layout, performance, ecossistema
Assets: logos oficiais
Texto: VS
Formato: 2,05:1
```

Prompt:

```text
Crie uma capa editorial horizontal 2,05:1 comparando Elementor e Bricks para o Blog PluginTema.

Divida a composição em dois lados de peso visual equivalente.

No lado Elementor, representar ecossistema e construção visual por widgets e componentes de layout. No lado Bricks, representar controle técnico, estrutura e performance por containers e componentes modulares.

Usar os logos oficiais fornecidos com o mesmo peso visual. Inserir apenas um pequeno "VS" no centro.

Estética neo-brutalista digital refinada, com contornos pretos espessos, sombras sólidas, formas geométricas, alto contraste e composição limpa.

Não sugerir vencedor.

Sem fogo, raios, socos, explosões, troféus ou estética de batalha.
```

---

# 119. Exemplo preenchido — segurança

```text
Artigo: vulnerabilidade em plugin
Categoria: Segurança
Ponto focal: plugin + versão afetada
Elementos: alerta, patch, escudo
Texto: versão
```

Prompt:

```text
Crie uma capa editorial horizontal 2,05:1 para um artigo PluginTema sobre uma vulnerabilidade em um plugin WordPress.

Usar o plugin como elemento principal e mostrar uma pequena falha gráfica em um de seus componentes. Próximo a ela, inserir um escudo e um pequeno elemento de patch/correção.

Usar a versão afetada como label curta apenas se fornecida.

Neo-brutalismo refinado, vetor limpo, contorno preto espesso, sombra sólida, alto contraste e poucos elementos.

A imagem deve transmitir "há um problema e existe uma ação técnica" sem alarmismo.

Sem hacker encapuzado, caveira, máscara, código verde, laptop escuro ou neon.
```

---

# 120. Exemplo preenchido — Labs

```text
Artigo: benchmark de cache
Categoria: PluginTema Labs
Ponto focal: dois resultados
Elementos: gráfico, servidor, terminal
Texto: LABS
```

Prompt:

```text
Crie uma capa editorial horizontal 2,05:1 para PluginTema Labs sobre um benchmark de cache WordPress.

Usar dois cards de resultado como ponto focal, acompanhados de um pequeno gráfico, um servidor e um terminal estilizado.

Organizar visualmente a lógica "ambiente → teste → resultado".

Adicionar um pequeno badge "LABS".

Usar neo-brutalismo digital refinado com abordagem mais técnica: grid discreto, contornos pretos, sombras sólidas, cards geométricos e alto contraste.

Não inventar números. Os cards podem permanecer abstratos se nenhum resultado real foi fornecido.
```

---

# 121. Teste de reconhecimento da imagem

Após gerar, perguntar:

- [ ] Sem logo PluginTema, a arte ainda parece nossa?
- [ ] Existe contorno preto consistente?
- [ ] As sombras são sólidas?
- [ ] Há espaço negativo?
- [ ] O acabamento é vetorial?
- [ ] A paleta está controlada?
- [ ] Existe um ponto focal claro?

Se várias respostas forem “não”, aplicar o prompt de revisão.

---

# 122. Teste de assunto

Perguntar:

> Sem ler o título, consigo entender aproximadamente o tema?

Se não:

- tornar elemento principal mais específico;
- reduzir decoração;
- melhorar contexto visual.

---

# 123. Teste de redução

Visualizar a arte pequena.

Confirmar:

- [ ] ponto focal continua visível;
- [ ] texto continua legível;
- [ ] logos não desaparecem;
- [ ] contorno não fica fino demais;
- [ ] elementos secundários não viram ruído.

---

# 124. Teste de excesso

Perguntar:

> Posso remover 20% e melhorar?

Se sim:

usar o prompt de simplificação.

---

# 125. Teste de factualidade

Para imagens sobre produtos reais:

- [ ] logo correto;
- [ ] versão correta;
- [ ] interface real quando apresentada como screenshot;
- [ ] recursos reais;
- [ ] números reais;
- [ ] nenhuma marca inventada.

As imagens editoriais não estão isentas das regras de precisão e transparência definidas na política editorial. fileciteturn1file4

---

# 126. Teste anti-marketing

Em review:

> A imagem poderia ser usada sem alterações na landing page do fabricante?

Se sim, provavelmente está promocional demais.

---

# 127. Teste anti-sensacionalismo

Perguntar:

> A imagem aumenta artificialmente a gravidade ou importância do assunto?

Se sim:

reduzir.

---

# 128. Teste anti-template

Perguntar:

> Esta arte é apenas a capa anterior com logo e cor trocados?

Se sim:

buscar outra composição.

O sistema visual deve ser consistente sem virar template rígido.

---

# 129. Teste anti-IA genérica

Verificar:

- [ ] não há neon por padrão;
- [ ] não há 3D plástico;
- [ ] não há objetos flutuando sem lógica;
- [ ] não há circuitos aleatórios;
- [ ] não há detalhes absurdos;
- [ ] não há texto corrompido;
- [ ] não há perspectiva incoerente;
- [ ] não há excesso de brilho.

---

# 130. Teste de transparência

Para asset transparente:

- [ ] fundo é alpha real;
- [ ] não há padrão quadriculado desenhado;
- [ ] não há halo branco;
- [ ] sombra não foi cortada;
- [ ] bordas estão limpas.

---

# 131. Regras para geração automatizada

Se um sistema automatizado montar prompts:

deve receber no mínimo:

```text
tipo de imagem
assunto
categoria
tipo de artigo
ponto focal
assets oficiais disponíveis
texto permitido
formato
```

Não gerar a partir apenas do título do artigo se houver contexto editorial disponível.

---

# 132. Ordem de precedência

Se houver conflito entre instruções:

1. factualidade;
2. autenticidade de assets;
3. segurança e privacidade;
4. legibilidade;
5. assunto;
6. identidade PluginTema;
7. estética;
8. decoração.

Uma imagem correta e clara é mais importante que uma imagem visualmente impressionante.

---

# 133. Regra para assets oficiais

Sempre que a imagem depender de:

- logo;
- screenshot;
- produto;
- interface;
- pessoa real;

usar o asset fornecido ou oficial quando disponível.

Não pedir ao modelo para reconstruí-lo de memória.

---

# 134. Regra para texto

Sempre que texto dentro da imagem puder ser aplicado posteriormente com maior precisão:

preferir:

> gerar sem texto → aplicar tipografia na etapa de design.

Isso é especialmente importante para:

- títulos;
- versões longas;
- labels técnicos;
- nomes de plugins;
- números;
- comparativos.

---

# 135. Regra para dados

Modelos de imagem não devem decidir:

- valor de benchmark;
- preço;
- versão;
- porcentagem;
- nota;
- métrica.

Esses dados precisam ser fornecidos pelo conteúdo editorial.

---

# 136. Regra para imagem de destaque

A capa deve complementar o título.

Não repetir tudo.

Perguntar:

> O que a imagem consegue comunicar que o título não comunica sozinho?

Essa resposta deve orientar o conceito.

---

# 137. Regra para imagens internas

Imagem interna deve servir a uma função específica:

- demonstrar;
- explicar;
- comparar;
- provar;
- orientar.

Não gerar ilustração para cada H2 apenas por padrão.

---

# 138. Regra para humor

Humor visual deve respeitar a voz editorial: jovem, moderna, humana e técnica, sem virar caricatura ou piada constante. fileciteturn1file9

---

# 139. Checklist de prompt antes de gerar

- [ ] O tipo de imagem está definido?
- [ ] O assunto está claro?
- [ ] O ponto focal está definido?
- [ ] A categoria foi considerada?
- [ ] A composição foi especificada?
- [ ] Há asset oficial necessário?
- [ ] Está claro se pode ou não ter texto?
- [ ] A paleta está controlada?
- [ ] O formato está definido?
- [ ] As principais restrições foram informadas?
- [ ] Não estamos pedindo fatos que o gerador teria de inventar?

---

# 140. Checklist após gerar

- [ ] A imagem parece PluginTema?
- [ ] O assunto está claro?
- [ ] O ponto focal funciona?
- [ ] O visual está limpo?
- [ ] O contorno é consistente?
- [ ] As sombras seguem a mesma direção?
- [ ] A paleta está controlada?
- [ ] Logos estão corretos?
- [ ] Textos estão corretos?
- [ ] Não há fatos inventados?
- [ ] Funciona pequena?
- [ ] Não parece SaaS genérico?
- [ ] Não parece thumbnail de YouTube?
- [ ] Não parece arte genérica de IA?
- [ ] Está pronta para publicação ou precisa de refinamento?

---

# 141. Frase-guia para criação

> **Primeiro defina a ideia. Depois componha. Só então estilize.**

Não começar o prompt com:

> “faça algo bonito sobre WordPress”.

Começar com:

> “represente esta ideia específica desta forma”.

---

# 142. Frase-guia para consistência

> **Mesmo sistema, composição diferente.**

O objetivo não é gerar cem capas iguais.

É gerar cem capas que claramente pertencem à mesma publicação.

---

# 143. Frase-guia para IA

> **A IA executa a direção de arte. Ela não define a direção de arte.**

O prompt precisa informar:

- intenção;
- hierarquia;
- limites;
- linguagem visual;
- fatos disponíveis.

---

# 144. Regra final

> **Uma boa imagem PluginTema não é apenas bonita. Ela resume visualmente uma ideia editorial.**

Quando o prompt estiver correto, a imagem deve:

- parecer parte da PluginTema;
- comunicar o assunto rapidamente;
- respeitar fatos;
- evitar clichês;
- funcionar pequena;
- complementar o artigo;
- permanecer visualmente consistente sem repetir sempre a mesma composição.
