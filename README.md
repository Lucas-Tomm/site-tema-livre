# Lendas do Octógono

Tema: Os 3 melhores lutadores de UFC do mundo
Nome: Lucas Corrêa Tomm
Turma: DSM3 2025
Unidade curricular: Programação de Aplicativos
Ano: 2026

## Sobre o projeto

O Lendas do Octógono é um site informativo sobre Jon Jones, Georges St-Pierre e Anderson Silva. Ele traz a história de cada lutador, dados de lutas marcantes e formulários de cadastro e de contato. O site foi feito só com HTML, sem CSS e sem JavaScript.

## Como abrir o projeto

Não precisa instalar nada. Basta baixar ou clonar o repositório e abrir o arquivo `index.html` no navegador (duplo clique). Depois é só navegar pelo menu.

Para clonar:

```
git clone https://github.com/Lucas-Tomm/site-tema-livre.git
```

## Páginas do site

- `index.html`: início, apresenta o tema e os três lutadores.
- `sobre.html`: sumário, artigos sobre cada lutador, curiosidade e glossário.
- `dados.html`: tabela com seis lutas marcantes.
- `cadastro.html`: formulário de cadastro de torcedor.
- `contato.html`: endereço fictício, horários e formulário de mensagem.

## Tecnologias utilizadas

- HTML5
- Git
- GitHub

## Recursos de acessibilidade aplicados

- Idioma da página definido como pt-BR.
- Link "Pular para o conteúdo" no início de todas as páginas.
- `aria-current="page"` no link da página atual do menu.
- Estrutura com `header`, `nav`, `main` e `footer`.
- Hierarquia de títulos sem pular nível.
- Texto alternativo nas imagens e `alt` vazio na imagem decorativa.
- `figure` com `figcaption` nas fotos.
- Tabela com `caption`, `scope` nos cabeçalhos e `time` nas datas.
- Formulários com `label` ligado ao campo por `for` e `id`.
- `fieldset` com `legend` para agrupar os campos.
- Validação nativa do HTML nos formulários.

## Validação e testes

- Validador: as cinco páginas foram testadas no Nu Html Checker da W3C e não apresentaram nenhum erro.
- Teste de teclado (só com a tecla Tab):
  - [ X ] Início
  - [ X ] Sobre
  - [ X ] Dados
  - [ X ] Cadastro
  - [ X ] Contato

  Resultado: todas as páginas funcionaram bem. Consegui chegar em todos os links, botões e campos usando só o Tab, e o link "Pular para o conteúdo" apareceu no primeiro Tab.
- Lighthouse de acessibilidade: não foi possível gerar o relatório do Lighthouse, porque os computadores da escola bloqueiam as ferramentas de desenvolvedor e a instalação de programas (falta de permissão de administrador), e não tenho computador disponível em casa. No lugar, foi feita uma estimativa a partir da revisão do código, com base nos critérios de acessibilidade que o Lighthouse verifica: idioma, título, texto alternativo, labels, ordem dos títulos, nome dos links, landmarks, cabeçalhos de tabela, ids únicos e contraste. A nota estimada é 100 nas cinco páginas, mas isso é uma estimativa e **não** uma medição do Lighthouse. O relatório real pode ser gerado depois, em um computador com permissão.

## Dificuldades

Ao pesquisar as lutas da tabela, vi que o round de Anderson Silva x Rich Franklin (UFC 64) que eu tinha anotado estava diferente das fontes, que indicam nocaute técnico no 1º round. Corrigi na tabela depois de conferir.

Também tive que evitar o `<br>` para quebrar as linhas do endereço, porque a regra do desafio não permite. Troquei por um `<p>` por linha dentro do `<address>`.

Instalar o GitHub CLI não funcionou no computador da escola (erro 1603 do instalador). Por isso criei o repositório pelo site do GitHub e liguei como origin.

O Lighthouse também não pôde ser usado, pelo mesmo motivo de permissão.

## Fontes consultadas

- [Site oficial do UFC](https://www.ufc.com/)
- [UFC na Wikipédia](https://pt.wikipedia.org/wiki/Ultimate_Fighting_Championship)
- [Fight Matrix](https://www.fightmatrix.com/): ranking histórico, citado no site como debatível.
- Dados das lutas:
  - [UFC 165, Jones x Gustafsson](https://www.ufc.com/event/ufc-165)
  - [UFC 285, Jones x Gane](https://www.cbssports.com/mma/news/ufc-285-results-highlights-jon-jones-earns-heavyweight-title-with-first-round-submission-of-ciryl-gane/live)
  - [UFC 94, St-Pierre x Penn](https://www.sherdog.com/news/articles/St-Pierre-Stops-Penn-After-Fourth-16014)
  - [UFC 217, St-Pierre x Bisping](https://www.ufc.com/news/ufc-217-bisping-vs-st-pierre-final-results)
  - [UFC 64, Silva x Franklin](https://www.boxingscene.com/articles/full-ufc-64-results-new-champ-silva)
  - [UFC 126, Silva x Belfort](https://www.sherdog.com/news/news/Silva-Front-Kick-KOs-Belfort-at-UFC-126-29956)
  - [Maiores reinados de campeões do UFC](https://www.ufc.com/news/longest-ufc-title-reigns-legends-octagon) (defesas de título de Anderson Silva)

## Fontes e licenças das imagens

- `jon-jones.jpg`: https://s2-ge.glbimg.com/chsdAghW_4i2K_c9GeDdqzaqZpw=/0x0:8606x5737/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_bc8228b6673f488aa253bbcb03c80ec5/internal_photos/bs/2024/p/G/vtwGj8RXCW2TLufaYCmA/gettyimages-2185190862.jpg
- `georges-st-pierre.jpg`: https://s2.glbimg.com/FTaaC62B0tXf6z2ONUXOotA0Z1I=/0x0:4368x2908/924x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_bc8228b6673f488aa253bbcb03c80ec5/internal_photos/bs/2017/r/2/Yvw0aLT5OhtBBG1TBgWA/gettyimages-871061334.jpg
- `anderson-silva.jpg`: https://ufc.com/images/styles/background_image_sm/s3/2020-05/Anderson%20Silva%20Win%20Hero%20Belfort%20126.jpg?itok=b4wWu9Z8

Licença: são imagens de terceiros. As duas primeiras vêm do portal ge.globo.com, com créditos da Getty Images, e a terceira vem do site do UFC. Foram usadas apenas para fins educacionais neste trabalho escolar, e os direitos são reservados aos autores.

## Autor

Nome: Lucas Corrêa Tomm
Turma: DSM3 2025
Ano: 2026
