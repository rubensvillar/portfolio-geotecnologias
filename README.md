# Portfólio de Geotecnologias — Rubens

Site estático em HTML, CSS e JavaScript, com galeria de mapas temáticos dos 33 municípios selecionados de Goiás.

## Conteúdo inicial

- Página inicial corporativa em azul-marinho e branco.
- Galeria com 13 mapas reais: território, demografia, IDHM e economia.
- Filtros por tema e visualização ampliada.
- Layout responsivo, sem dependências externas.

## Como visualizar no computador

Como a galeria lê `maps.json`, abra a pasta em um servidor HTTP local (não apenas com duplo clique em `index.html`). Com Python instalado, abra o terminal **dentro da pasta** e execute:

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000` no navegador. No Anaconda Prompt, o comando também funciona.

## Como publicar no GitHub Pages

1. Crie um repositório público `SEU-USUARIO.github.io` no GitHub (substitua pelo seu usuário real). O repositório com esse nome publica o site no endereço principal do GitHub Pages. Alternativamente, um repositório `portfolio-geotecnologias` publicará no endereço `https://SEU-USUARIO.github.io/portfolio-geotecnologias/`.
2. No GitHub Desktop, clone o repositório vazio para o computador.
3. Copie **o conteúdo desta pasta** (index.html, style.css, app.js, maps.json, assets/, README.md) para a raiz do repositório clonado.
4. Faça `Commit to main` e depois `Push origin`.
5. No GitHub, abra **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
6. Aguarde a publicação e acesse a URL do GitHub Pages exibida em Settings → Pages.

## Personalização antes da publicação

- Substitua o nome `Rubens`, se desejar, no arquivo `index.html`.
- Inclua seus links profissionais (LinkedIn e e-mail público) na seção Contato, somente se quiser divulgá-los.
- Confira se todos os mapas podem ser compartilhados publicamente e se você tem autorização para divulgar materiais associados a projetos institucionais ou apresentações de terceiros.
- Leia o texto de cada mapa e revise créditos, fontes e anos antes de publicar.

## Inserir ou remover mapas

Copie a imagem para `assets/maps`, uma miniatura para `assets/thumbs` e acrescente um objeto no arquivo `maps.json`, seguindo o padrão dos existentes.

**Observação:** o conjunto disponível nesta versão não inclui o Slide 12 (PIB municipal absoluto), porque não havia uma exportação final daquele slide entre os arquivos acessíveis. Ele pode ser acrescentado posteriormente.

## Licença e dados

Os mapas são produtos de demonstração técnica. As fontes originais estão descritas em cada peça; não é atribuída uma licença de reutilização aos dados ou produtos cartográficos de terceiros por este repositório. Antes da publicação pública, confirme os direitos de uso e a autorização de divulgação dos projetos.
