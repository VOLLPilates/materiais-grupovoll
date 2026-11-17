# materiais-grupovoll

Página geral do Grupo VOLL e base para as landing pages da marca.

## Estrutura das páginas

Mantenha a página geral na raiz e crie cada nova LP em uma pasta própria, com o index.html dentro dela. O nome da pasta vira o caminho da página.

    materiais-grupovoll/
    ├── index.html                 # página geral
    ├── README.md
    ├── assets/                     # identidade visual e arquivos compartilhados
    │   ├── logo-voll-pilates.webp
    │   ├── manrope-variable.ttf
    │   └── OFL-Manrope.txt
    ├── nova-pagina/
    │   └── index.html              # /nova-pagina/
    └── teste/
        └── index.html              # /teste/

Exemplos:

- /nova-pagina/index.html fica disponível em /nova-pagina/.
- /teste/index.html fica disponível em /teste/.

Use pastas com nomes simples em minúsculas e hífens, sem espaços ou acentos, como curso-de-pilates. Guarde arquivos compartilhados em assets/ e use caminhos relativos a partir da página: ../assets/logo-voll-pilates.webp em uma LP dentro de uma subpasta. Mantenha cada landing page e seus arquivos específicos juntos na pasta dela.

## Identidade visual

A página usa o logotipo institucional da VOLL e a tipografia Manrope. O arquivo da fonte e sua licença Open Font License ficam em assets/.
