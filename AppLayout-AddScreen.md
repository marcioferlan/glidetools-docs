# App Layout

### app-layout/add-screen

Permite customizar os controles da tela de inclusão.

**URL base**
```css
@import '//glidetools.ml/app-layout/add-screen'
```

| Propriedade | Valor | Descrição               |
| ----------- | ----- | ----------------------- |
| `addLabel` | Texto | Altera o texto do botão Adicionar (canto superior direito) |
| `cancelLabel` | Texto | Altera o texto do botão Cancelar (canto superior esquerdo) |
| `centerTitle` | N/A | Centraliza o título da tela (em celulares Android)|
| `hideAdd` | N/A | Esconde o botão de Adicionar (canto superior direito) |
| `hideCancel` | N/A | Esconde o botão de Cancelar (canto superior esquerdo) |
| `title` | Texto | Altera o título da tela de inclusão |

**Exemplos:**

- Centralizar e alterar o título da tela
```css
@import '//glidetools.ml/app-layout/add-screen?centerTitle&title=Adicionar Produto'
```

- Ocultar o botão Cancelar e mudar o texto do botão Adicionar
```css
@import '//glidetools.ml/app-layout/addScreen?hideCancel&addLabel=Salvar'
```

**Preview**

<img src="http://g.recordit.co/LCkhGhsdAY.gif">
