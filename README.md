# Frontend Mentor - Fylo data storage component

![Design preview for the Fylo data storage component coding challenge](./design/desktop-preview.jpg)

## Bem vindo! 👋


Estes é  um desafio proposto no [Frontend Mentor](https://www.frontendmentor.io) Lá tem desafios que ajudam você a melhorar as suas *coding skills by building realistic projects*. [PÁGINA](https://odisseu93.github.io/fylo-data-storage-component-master/)  


## The challenge

O desafio é construir esse componente de armazenamento de dados e fazê-lo parecer o mais próximo possível do <a href="https://www.imagemhost.com.br/album/rV8hV" target="_blank">design<a>.


- Visualizar o layout ideal para o site, dependendo do tamanho da tela do dispositivo


 ### Construído com:

- HTML5
- [SASS](https://sass-lang.com/documentation)
- CSS 
- Flexbox
- Mobile-first workflow

### O que eu aprendi

usar a stylesheet language SASS e algumas das suas funcionalidades

veja alguns exemplos, abaixo:

#### Variáveis 

```sass
 /* variáveis no arquivo _varibles.sass*/           
$background-Dark-Blue-color: hsl(228, 56%, 26%)
$background-very-Dark-Blue-color:hsl(229, 57%, 11%)
$font-pale-blue-color: hsl(243, 100%, 93%)  
$font2-grayish-blue-color: hsl(229, 7%, 55%)  
```

```sass
/* importação de arquivo*/            
@use 'variables'
```

```sass
/* utilização das variváveis */
*
  font-family: 'Raleway', sans-serif
  font-size: 14px
  font-weight: 400
  color: variables.$font-pale-blue-color
  padding: 0
  margin: 0
  box-sizing: border-box
```            
       
#### mixins    


```sass
/* criando um mixin com o nome 'flex-column-center'*/
@mixin flex-column-center
  display: flex
  flex-direction: column
  align-items: center
  justify-content: center            
            
```

```sass
/* utilização */
  .main
    @include mixins.flex-column-center
    width: 100vw
    height: 95vh
```
            
### o que foi feito 
- Estilização da tela mobile (telas de 320 a 425px)  ✅
- Deploy no Git-pages ✅ [CLIQUE AQUI PARA ACESSAR A PÁGINA! ](https://odisseu93.github.io/fylo-data-storage-component-master/)       

### o que falta fazer
- Estilização para outras telas 👷
- refatoração do código 👷            
