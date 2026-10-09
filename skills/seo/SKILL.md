---
name: seo
description: >
  Plano completo de SEO, GEO e Google Ads em 8 passos para qualquer negócio: pesquisa do que
  as pessoas buscam, análise da concorrência, Google Meu Negócio, ajustes no site, plano de
  conteúdo, Google Ads, checklist de acompanhamento e GEO (aparecer em IAs como ChatGPT,
  Gemini e Perplexity). Use quando o usuário pedir "seo", "geo", "palavras-chave",
  "google ads", "aparecer no google", "aparecer no chatgpt", "aparecer nas ias",
  "google meu negócio", "perfil da empresa no google", "analisar concorrência",
  "pesquisa de nicho" ou /seo.
---

# /seo: SEO completo + GEO + Google Ads

Skill gratuita criada por Felipe Almeida (@felipealmeidasid).

## Antes de começar: o contexto do negócio

Tudo nessa skill depende de saber de qual negócio estamos falando.

1. Procurar o arquivo `seo-contexto.md` na pasta aberta.
2. Se existir e estiver preenchido, usar como base e seguir para o Passo 1.
3. Se não existir (ou estiver vazio), fazer uma entrevista curta com o usuário, **uma pergunta por vez**, em linguagem simples:
   - Nome da empresa e o que ela vende ou faz
   - Cidade e região que atende (ou se atende o Brasil todo / online)
   - Quem é o cliente ideal
   - Site atual (link) e se tem perfil no Google Maps
   - 2 ou 3 concorrentes que o usuário conhece (opcional)
   - Diferenciais reais (o que faz melhor que os outros)
   - Tom de voz desejado (mais formal, mais descontraído)
   - Tem verba para anúncios? Quanto por mês, mais ou menos? (opcional)
4. Salvar as respostas em `seo-contexto.md` (modelo no fim deste arquivo) e mostrar ao usuário.

Todos os resultados vão para a pasta `seo/`, criada dentro da pasta aberta.

Linguagem com o usuário: simples, sem jargão. Quando um termo técnico for inevitável (ex.: "schema", "meta description"), explicar em uma frase o que é.

---

## Passo 1: DEMANDA (o que as pessoas buscam)

1. Gerar de 30 a 50 termos iniciais a partir de: produtos/serviços, intenção de busca (pesquisa, comparação, compra), localização e situação de uso do cliente.
2. Pesquisar na web cada grupo de termos: o que aparece (resultados normais, anúncios, mapa), buscas relacionadas, sazonalidade.
3. Classificar cada termo por volume estimado (alto / médio / baixo), intenção, dificuldade (quantos concorrentes fortes) e relevância.

**Arquivo:** `seo/01-pesquisa-demanda.md` com tabela de termos, top 10 prioritários, termos sazonais e descartados (com motivo).

## Passo 2: CONCORRÊNCIA (quem aparece na frente)

1. Para os top 10 termos, ver: top 5 resultados, quem aparece no mapa (nota e número de avaliações), quem anuncia e com qual texto.
2. Abrir o site de 5 a 8 concorrentes e analisar: páginas, títulos, profundidade do conteúdo, dados estruturados, perfil no Google.
3. Apontar: lacunas (o que ninguém faz bem), oportunidades, concorrentes fortes demais para enfrentar de frente e o padrão mínimo a atingir.

**Arquivo:** `seo/02-analise-concorrencia.md` com tabela, mapa de oportunidades e onde atacar primeiro.

## Passo 3: GOOGLE MEU NEGÓCIO (o resultado mais rápido)

Montar tudo o que precisa estar preenchido no Perfil da Empresa no Google:

- Nome, categoria principal e secundárias, endereço, telefone, site, horário, área de atendimento
- Descrição de até 750 caracteres com as palavras certas, no tom do negócio
- Serviços e atributos
- Checklist de fotos (fachada, interior, produtos, equipe)
- 4 posts iniciais e frequência sugerida
- Como pedir avaliações e modelos de resposta (positivas e negativas)
- Diretórios onde cadastrar, sempre com nome, endereço e telefone idênticos

**Arquivo:** `seo/03-google-meu-negocio.md`

## Passo 4: SITE (ajustes página por página)

Se o usuário tiver site, analisar as páginas. Se não tiver, sugerir quais páginas criar.

- Palavra principal de cada página
- Título (50 a 60 caracteres) e descrição (150 a 160 caracteres, com chamada para ação)
- Títulos internos (H1, H2, H3)
- Dados estruturados prontos para copiar (JSON-LD: LocalBusiness, Product, FAQ)
- Checklist técnico: endereços amigáveis, texto alternativo nas imagens, velocidade, celular, sitemap, robots.txt, Open Graph
- Mapa de links entre as páginas

**Arquivo:** `seo/04-otimizacao-site.md` com tabela página → palavra → título → descrição → H1, códigos prontos e checklist.

## Passo 5: CONTEÚDO (virar referência no assunto)

- 5 a 10 ideias de artigos que respondem dúvidas reais do público (título, palavra-alvo, estrutura)
- Uma página principal sobre o tema e páginas de apoio ligadas a ela
- Ordem de publicação, frequência e formato (guia, perguntas frequentes, comparativo)
- Conteúdo local, se fizer sentido

**Arquivo:** `seo/05-estrategia-conteudo.md`

## Passo 6: GOOGLE ADS (campanhas prontas)

- Objetivo (contatos por WhatsApp/ligação, visitas, alcance local)
- Campanha de pesquisa: grupos de anúncios, 10 a 15 palavras por grupo, palavras negativas, 15 títulos e 4 descrições, extensões
- Orçamento diário, lance e região
- Se o site atual serve como página de destino ou se precisa de uma página nova

Nunca inventar custo por clique. Se não houver dado real, dizer que é estimativa e explicar de onde veio.

**Arquivo:** `seo/06-google-ads.md`

## Passo 7: ACOMPANHAMENTO (checklist)

- **Semanal:** posição nos top 10 termos, responder avaliações, 1 post no Perfil da Empresa
- **Mensal:** números dos anúncios, tráfego no Google Search Console, palavras negativas, 1 a 2 conteúdos novos
- **Trimestral:** refazer a análise de concorrência, atualizar fotos, revisar o plano

**Arquivo:** `seo/07-checklist-acompanhamento.md`

## Passo 8: GEO (aparecer nas respostas das IAs)

Cada vez mais gente pergunta ao ChatGPT "qual o melhor X em Y?". Quem aparece ganha cliente sem pagar anúncio.

1. **Diagnóstico:** pesquisar os top termos e ver quais empresas e fontes as IAs citam nesse nicho.
2. **Conteúdo que a IA entende:** resposta direta nas primeiras linhas, dados concretos (números, endereço, certificações), perguntas como subtítulos, nada genérico.
3. **Perguntas frequentes no site** com o código FAQPage (JSON-LD) pronto, 5 a 10 perguntas reais.
4. **Menções externas:** diretórios, sites de avaliação, blogs e mídia do nicho.
5. **Teste mensal:** perguntar os top 5 termos no ChatGPT, Gemini e Perplexity e anotar quem apareceu.

**Arquivo:** `seo/08-geo-aparecer-nas-ias.md`

---

## Como executar

- `/seo` (ou "roda a skill de SEO"): fazer os 8 passos em sequência. Entre um passo e outro, mostrar um resumo curto do que encontrou.
- Um passo só: `/seo passo 3`, `/seo gmb`, `/seo geo`, `/seo ads`.

No final, entregar `seo/00-resumo.md` com:

- As 5 maiores oportunidades
- O que fazer primeiro (em ordem)
- Estimativa de investimento em anúncios (se houver base real)
- Próximos passos

## Regras

- Toda pesquisa deve ser real, feita na web. Nunca inventar volume de busca, concorrente ou custo.
- Quando um número for estimativa, dizer que é estimativa e explicar a lógica.
- Termos em português do Brasil, do jeito que o público busca.
- Textos e anúncios seguem o tom definido em `seo-contexto.md`.
- Foco em termos de quem está perto de comprar.
- Se a ferramenta não tiver acesso à internet, avisar o usuário e pedir que ative a busca na web antes de continuar.

---

## Modelo do `seo-contexto.md`

```markdown
# Contexto do negócio (usado pela skill /seo)

- Empresa:
- O que vende / faz:
- Cidade e região que atende:
- Cliente ideal:
- Site:
- Perfil no Google Maps: (link ou "não tenho")
- Concorrentes que conheço:
- Diferenciais:
- Tom de voz:
- Verba mensal para anúncios: (opcional)
```
