# Sorelly — Cardápios

Cardápios da Sorelly (Sorocaba): Coquetel, Comida de Boteco, Massa Show, Rodízio de Pizzas,
Feijoada, Churrasco Prata, Churrasco Ouro e Crepe Francês.

Site estático em um único arquivo (`index.html`), pronto para o GitHub Pages.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie estes arquivos para a raiz dele.
2. No repositório, abra **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`, e salve.
4. Em alguns minutos o site fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Editar os cardápios

Cada cardápio é um bloco `<section class="menu-block">` no `index.html`.

- **Valor:** fica em `<div class="price">` dentro do bloco e também no cartão de resumo
  (`<div class="ov-price">`) no topo da página. Altere nos dois lugares.
- **Itens:** são linhas `<li>` dentro de cada grupo (`<div class="group">`).
- **Capa:** o número de cardápios e o menor valor ficam em `data-count`, na capa.
