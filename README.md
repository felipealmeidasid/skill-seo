# Skill de SEO grátis para Claude Code e Codex

Um "funcionário de SEO" que mora dentro do seu Claude Code ou Codex.

Você digita **/seo**, responde umas perguntas sobre o seu negócio e ele te entrega um plano completo para:

- aparecer no **Google** (nos resultados e no mapa)
- aparecer quando alguém pergunta ao **ChatGPT, Gemini ou Perplexity**
- montar anúncios no **Google Ads** sem jogar dinheiro fora

Criado por **Felipe Almeida** ([@felipealmeidasid](https://instagram.com/felipealmeidasid)). Grátis, pode usar à vontade.

---

## Sumário

1. [O que é uma "skill"?](#1-o-que-é-uma-skill)
2. [O que essa skill faz (os 8 passos)](#2-o-que-essa-skill-faz-os-8-passos)
3. [Do que você precisa](#3-do-que-você-precisa)
4. [Como instalar no Claude Code](#4-como-instalar-no-claude-code)
5. [Como instalar no Codex](#5-como-instalar-no-codex)
6. [Como usar](#6-como-usar)
7. [O que você recebe no final](#7-o-que-você-recebe-no-final)
8. [Dúvidas comuns](#8-dúvidas-comuns)

---

## 1. O que é uma "skill"?

Pense numa receita de bolo.

O Claude Code e o Codex são assistentes de IA que trabalham no seu computador. Eles são inteligentes, mas não sabem de cor o **seu jeito** de fazer as coisas.

Uma skill é uma receita escrita que você entrega para eles. Quando você chama a skill, a IA segue a receita passo a passo, sempre do mesmo jeito, sem você precisar explicar tudo de novo.

Essa aqui é a receita que eu uso para fazer negócios aparecerem no Google e nas IAs.

---

## 2. O que essa skill faz (os 8 passos)

| Passo | Nome | Em português claro |
|---|---|---|
| 1 | Demanda | Descobre **o que as pessoas digitam** no Google quando procuram o que você vende |
| 2 | Concorrência | Vê **quem aparece na sua frente** e onde eles estão deixando a desejar |
| 3 | Google Meu Negócio | Monta tudo para o seu **perfil no Google Maps** ficar completo (é o que dá resultado mais rápido) |
| 4 | Site | Diz **o que mudar em cada página** do seu site para o Google entender do que ela fala |
| 5 | Conteúdo | Sugere **artigos e páginas** que respondem as dúvidas do seu cliente |
| 6 | Google Ads | Deixa **campanhas de anúncio prontas**, com textos e palavras certas |
| 7 | Acompanhamento | Um **checklist** do que olhar toda semana, todo mês e a cada 3 meses |
| 8 | GEO (IAs) | Mostra como fazer o **ChatGPT e outras IAs indicarem a sua empresa** |

Tudo é pesquisado de verdade na internet. A skill é instruída a **nunca inventar números**. Quando algo é estimativa, ela avisa.

---

## 3. Do que você precisa

- **Claude Code** (do Claude) **ou** **Codex** (do ChatGPT) instalado no computador. Pode ser o aplicativo de desktop ou a versão no terminal.
- Uma assinatura que dê acesso a eles (Claude Pro/Max ou ChatGPT Plus/Pro).
- Acesso à internet ligado na ferramenta (a skill pesquisa no Google).

Não precisa saber programar.

---

## 4. Como instalar no Claude Code

### Jeito mais fácil: pedir para o próprio Claude instalar

Abra o Claude Code, cole a mensagem abaixo e aperte Enter:

```text
Instala a skill de SEO deste repositório como skill global do Claude Code:
https://github.com/felipealmeidasid/skill-seo
Copia a pasta skills/seo para a minha pasta de skills (~/.claude/skills/seo) e me confirma quando terminar.
```

Ele vai pedir permissão para baixar e copiar os arquivos. Aceite. Pronto.

### Jeito manual (se preferir fazer você mesmo)

1. Nesta página, clique no botão verde **Code** e depois em **Download ZIP**.
2. Descompacte o arquivo baixado.
3. Lá dentro, entre em `skills` e copie a pasta **`seo`**.
4. Cole essa pasta em:
   - **Windows:** `C:\Users\SEU-USUARIO\.claude\skills\`
   - **Mac:** `/Users/SEU-USUARIO/.claude/skills/`

   O final tem que ficar assim: `.claude/skills/seo/SKILL.md`

> **Não acha a pasta `.claude`?** Ela é uma pasta "escondida".
> No Windows, no Explorador de Arquivos, clique em **Exibir** e marque **Itens ocultos**.
> No Mac, no Finder, aperte **Cmd + Shift + .** (ponto).
> Se a pasta `skills` não existir, pode criar.

5. Feche e abra o Claude Code de novo.

**Para testar:** digite `/seo` na caixa de mensagem. Se ela aparecer na lista, está instalada.

---

## 5. Como instalar no Codex

### Jeito mais fácil: pedir para o próprio Codex instalar

Abra o Codex e mande:

```text
Instala a skill de SEO deste repositório como skill do Codex:
https://github.com/felipealmeidasid/skill-seo
Copia a pasta skills/seo para ~/.codex/skills/seo e me confirma quando terminar.
```

### Jeito manual

Igual ao do Claude Code, só muda a pasta de destino:

- **Windows:** `C:\Users\SEU-USUARIO\.codex\skills\`
- **Mac:** `/Users/SEU-USUARIO/.codex/skills/`

O final tem que ficar assim: `.codex/skills/seo/SKILL.md`

Feche e abra o Codex de novo.

**Para testar:** no Codex, digite `$seo` ou simplesmente escreva "usa a skill de SEO".

---

## 6. Como usar

1. **Crie uma pasta** para o negócio que você vai analisar (ex.: `Padaria do João`) e abra essa pasta no Claude Code ou no Codex.
2. Digite:
   - no Claude Code: **`/seo`**
   - no Codex: **`$seo`** (ou "roda a skill de SEO")
3. **Responda as perguntas.** Na primeira vez ela pergunta o nome da empresa, cidade, cliente ideal, site e diferenciais. Uma pergunta de cada vez.
4. **Espere ela trabalhar.** Ela pesquisa, analisa e vai te mostrando um resumo a cada passo. Leva alguns minutos.

> **Dica:** quer adiantar? Preencha o arquivo [`seo-contexto.md`](seo-contexto.md) deste repositório com os dados do negócio e coloque dentro da pasta antes de rodar. Aí ela pula as perguntas.

### Quer só uma parte?

| Escreva | Para fazer só |
|---|---|
| `/seo gmb` | o perfil do Google Meu Negócio |
| `/seo geo` | aparecer nas IAs |
| `/seo ads` | as campanhas de Google Ads |
| `/seo passo 2` | a análise de concorrência (vale para qualquer número de 1 a 8) |

No Codex, troque a `/` por `$`.

---

## 7. O que você recebe no final

Uma pasta chamada **`seo`** com um arquivo para cada passo:

```text
seo/
  00-resumo.md                  ← comece por aqui: o que fazer primeiro
  01-pesquisa-demanda.md
  02-analise-concorrencia.md
  03-google-meu-negocio.md
  04-otimizacao-site.md
  05-estrategia-conteudo.md
  06-google-ads.md
  07-checklist-acompanhamento.md
  08-geo-aparecer-nas-ias.md
```

São arquivos de texto. Dá para abrir no próprio Claude/Codex, no Bloco de Notas, ou colar no Google Docs.

---

## 8. Dúvidas comuns

**É de graça mesmo?**
Sim. A skill é grátis. Você só precisa da sua assinatura do Claude ou do ChatGPT.

**Serve para qualquer tipo de negócio?**
Serve para negócio local (padaria, clínica, escritório, loja) e para quem vende online. Funciona melhor para quem tem cidade ou região definida.

**Ela mexe no meu site sozinha?**
Não. Ela só gera o plano e os textos prontos. Quem decide o que aplicar é você.

**Ela cria anúncios e gasta meu dinheiro?**
Não. Ela só deixa as campanhas escritas. Nada é publicado nem cobrado.

**Os números são reais?**
A skill pesquisa na internet e é instruída a não inventar nada. Volume de busca exato só o Google tem, então nesses casos ela mostra uma estimativa e explica de onde tirou.

**Digitei /seo e não apareceu nada.**
Confira se a pasta ficou no lugar certo (`.claude/skills/seo/SKILL.md`, com o arquivo `SKILL.md` direto dentro da pasta `seo`) e reinicie o programa.

**Ela disse que não consegue pesquisar na internet.**
Ative a busca na web nas configurações da ferramenta e rode de novo.

---

Gostou? Me conta o resultado lá no Instagram: [@felipealmeidasid](https://instagram.com/felipealmeidasid)

Licença MIT: pode usar, adaptar e compartilhar, só mantém o crédito.
