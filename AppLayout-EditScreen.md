# App Layout

### app-layout/edit-screen

Permite customizar os controles da tela de edição.

**URL base**
```css
@import '//glidetools.ml/app-layout/edit-screen'
```

| Propriedade | Valor | Descrição               |
| ----------- | ----- | ----------------------- |
| `cancelLabel` | Texto | Altera o texto do botão Cancelar (canto superior esquerdo) |
| `centerTitle` | N/A | Centraliza o título da tela (em celulares Android)|
| `doneLabel` | Texto | Altera o texto do botão Fechar (canto superior direito) |
| `hideDone` | N/A | Esconde o botão de Fechar (canto superior direito) |
| `hideCancel` | N/A | Esconde o botão de Cancelar (canto superior esquerdo) |
| `title` | Texto | Altera o título da tela de edição |

**Exemplos:**

- Centralizar e alterar o título da tela
```css
@import '//glidetools.ml/app-layout/edit-screen?centerTitle&title=Adicionar Produto'
```

- Ocultar o botão Cancelar e mudar o texto do botão Fechar
```css
@import '//glidetools.ml/app-layout/edit-screen?hideCancel&doneLabel=Salvar'
```

**Preview**

<img src="http://g.recordit.co/LCkhGhsdAY.gif">
