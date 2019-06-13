# Feed Book

Estrutura usando ReactJS com Babel, Webpack e Webpack Dev Server, com as ferramentas ESLint, EditorConfig e Prettier durante o desenvolvimento desse projeto.

![Feed](/assets/feed.png)

Esse projeto foi desenvolvido um feed de posts com o estilo similar ao Facebook.

## Descritivo passo-a-passo

O Header e o Post foram criados em componentes separados;
O header do post aonde estão o avatar, nome e tempo do post estão em um componente separado chamado PostHeader;
Os posts são armazenados no estado da aplicação (state) do arquivo principal App.js;
As informação dos posts são passadas como uma única propriedade para o componente de Post quando realizar o map no state de posts: <Post data={post} /> , afim de facilitar o uso.

Anderson V. Bellini
[Linkedin](http://www.linkedin.com/in/abellini)
