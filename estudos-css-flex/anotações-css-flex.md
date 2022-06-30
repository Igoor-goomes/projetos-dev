# Posicionando elementos com Flexbox em CSS

## Fundamentos do Flexbox

- `display-flex` | seu padrão de orientação sempre será na horizontal
- `flex-direction` | usado para definir a direção que os flex-itens serão colocados
- `flex-wrap` | usado para definir quais itens devem ou não quebrar linha, lembrando que por padrão os flex não quebram linha e pode ocorrer o vazamendo do item dentro do container
- `flex-flow` | atalho para as propriedades ``flex-direction`` e `flex-wrap`
- `justify-content` | usada para linhamento do itens dentro do container de acordo com a direção pretendida e tratar da distribuição do espaçamento entre eles
- `align-items` | trata o alinhamento dos flex itens de acordo com eixo do container
- `align-content` | trata o alinhamento das linhas do container em relação ao exio vertical do container, precisamos que o container utilizar quebra de linhas e a altura do container seja maior que a soma das linhas dos itens
- `flex-grow` | define a proporcionalidade de crescimento dos itens, respeitando o tamanho de seus contéudos internos, caso o `justify-content` estiver adicionado ao nosso flex container, o `flex-grow` não irá funcionar
- `flex-basic` | estabelece o tamanho inicial do item antes das distribuições de espaço restante dentro dele, usando como base o conteúdo interno disposto
- `flex-shrink` | estabelece a capacidade de redução ou compressão do tamanho de um item
- `flex` | atalho ou abreviação de escrita para as propriedades:grow, shrink e basis
- `order` | 
- `align-self` | estavele o alinhamento de modo individual sobre um determinado item
