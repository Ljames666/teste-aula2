# MarkDown

# Olá sou o Jamerson <!-- <h1> -->

## Olá sou o Jamerson <!-- <h2> -->

### Olá sou o Jamerson <!-- <h3> -->

#### Olá sou o Jamerson <!-- <h4> -->

##### Olá sou o Jamerson <!-- <h5> -->

###### Olá sou o Jamerson <!-- <h6> -->

<!-- No markdown as imagens não podem ser redimensionadas diretamente e nem com css inline, terá que usar a tag style para estiliza-la conforme seu gosto-->
<style>
  img {
    width:200px;
    }
</style>
<!-- A tag style deve ser usada antes do elemento a ser estilizado -->
<!-- com Markdown -->

![raper](https://i.pinimg.com/originals/9b/03/49/9b034902e0f4527932f5c15625203a3b.jpg)

<!-- em html -->
<img src="https://i.pinimg.com/originals/9b/03/49/9b034902e0f4527932f5c15625203a3b.jpg"/>

<!-- para texto é digitar livremente não de nenhum caracter especial -->
<!-- negrito -->**Negrito**
<!-- italico -->*Negrito*
<!-- negrito italico -->***Negrito***

Em HTML, existem dois caracteres que exigem tratamento especial: e . Os suportes de ângulo esquerdo são usados para iniciar tags; ampersands são usados para denotar entidades HTML. Se você quiser usá-los como caracteres literais, você deve escapar deles como entidades, por exemplo, e .<&&lt;&amp;

<!-- deixe um linha vazias entre os textos para mudar o paragrafo -->

Ampersands, em particular, são desmentidores para escritores web. Se você quer escrever sobre 'AT&T', você precisa escrever ''. Você ainda precisa escapar de ampersands dentro de URLs. Assim, se você quiser vincular a:AT&amp;T

<!-- links -->

[google](https://www.google.com)
[MarkdowGuide](https://www.markdownguide.org)

<!-- tablelas -->

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

<!-- Blocos de codigos -->

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

```html
<body>
  <header>
    <h1>oi mundo</h1>
  </header>
</body>
```

```js
const agoraDeuBom = () => console.log('é nois');
```

<!-- listas de tarefas ou seleçao -->

- [ ] Write the press release
- [ ] Update the website
- [ ] Contact the media

<!-- Emoji pode pesquisar no proprio discord -->

:joy:
:sunglasses:
