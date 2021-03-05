### Alinhamentos
    justify-content
    align-content
    justify-items
    align-items
    justify-self
    align-self

### Content

Sabendo que o grid é bidimensional, nós temos o eixo x e o y
`Justify-content` e `align-content` nos permite alinhar o próprio grid, relativo ao espaço fora do grid.

Podemos usar **7 valores**:
start
end
center
stretch <!-- preenche todo o campo permitido -->
space-between
space-around
space-evenly <!-- se divide com espaços iguais -->

### Items

`justify-items` e `align-items` vai permitir alinhas os itens do nosso grid, em qualquer espaço disponível, na célula (cada grid, quadrado é uma célula) que ele habitar

Podemos usar **4valores**:
start
end
center
stretch

### Self

`justify-self` e `align-self` vai nos permitir alinhar o item em sim.

Faz a mesma coisa que o `justify-items` e `align-items`, porém, aplicado diretamente no item de um grid

Podemos usar **4valores**:
start
end
center
stretch