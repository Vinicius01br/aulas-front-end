# aulas-front-end
 atividades estudos de html e css

## HTML
- Estruturação
- Semântica
- Padrões Web

## CSS
Linguagem de estilização que "casa" com
elementos HTML.

Em geral, CSS serve para:



1. Estilos de vários tipos (cores, sombra, borda etc)
2. Alinhamentos e espaçamentos
3. Design Responsivo
4. Animações e efeitos especiais de interação

### Formas de implementação
### Inline
O CSS é aplicado diretamente em cada tag HTML
### Interna/Onpage
O CSS é criado usando regras (com Seletores, propriedades, valores) dentro da própria pagina que queremos formatar.
as regras vão valer para todos os elementos/tags desta pagina.
### Como fazer uma regra CSS?
Seletor {propriedade:valor;}
propriedade1: valor;
propriedade2: valor;
propriedadeN: valor;

### Externa
É criado um arquivo de extensão CSS dedicado ás regras de formatação. este arquivo é então "conectado" as pagínas HTML.
## JS
1. primeiro elemento da lista ordenada
2. segundo elemento.

## Tipos de seletor
- Tag: seletor mais abragente/generalista, casa com elementos HTML de acordo
com a tag especificado.
- Descendente: Seletor, mais especifico casa com elementos que são filhos (descendente) de outro elemento que compartilham uma mesma formatação. Usa-se virgula para separar os seletores.

- Agrupado: grupo de seletores que compartilham uma mesma formatação .usa se virgula para separar os seletores.

-Pseudo-Classe: classes "pré-prontas/nativas" da linguagem que pode ser
aplicada em diversas situações. exemplos: passar mouse, reconhecer foco,

selecionar determinado elementos etc. TODAS psudo-classes começa com dois-pontos

- Classe: seletor versátil que permite a aplicação de estilos em diversos
elementos, possibilitando também a combinação de diferentes classes,

- Identificado: seletor bastante restrito (o mesmo id só pode ser usado em um elemento por página),
permitindo criar uma estilização altamente específica. no CSS usa-se #nome-do-id
para criar, e no HTML usa-se o atributo id="nome-do-id" para aplicar
