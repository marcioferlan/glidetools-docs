# GlideTools <small>// Extend your Glide apps!</small>

## Apresentação

O projeto GlideTools tem por objetivo estender as funcionalidades do Glide oferecendo recursos não disponíveis ainda na versão atual.

## Serviços

Os serviços podem ser adicionados ao app por meio de um componente Rich Text, selecionando a opção Custom e seguem uma mesma estrutura básica:

```html
<span style="display:none"/>
<style>
  @import '//glidetools.ml/nome-do-servico/nome-do-recurso?propriedade1=valor1&propriedade2=valor2';
</style>
```

## Serviços disponíveis

| Serviço | Descrição |
| - | - |
| [app-layout/nav-bars](AppLayout-NavBars.md) | Permite ocultar o menu lateral e a barra de abas na parte inferior do app. |
| [app-layout/add-screen](AppLayout-AddScreen.md) | Permite ocultar ou renomear botões, centralizar e mudar o título da tela, etc. |
| [app-layout/edit-screen](AppLayout-EditScreen.md) | Permite ocultar ou renomear botões, centralizar e mudar o título da tela, etc. |
| [app-layout/delete-button](AppLayout-DeleteButton.md) | Permite alterar o texto do botão, bem como o título mensagem e botões da mensagem de confirmação, etc. |
