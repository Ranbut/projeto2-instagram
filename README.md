# [Driven Education](https://www.driven.com.br/) - Projeto 2 - Instagram

[Acesse o site clicando aqui!](https://ranbut.github.io/projeto2-instagram/);

# Descrição

Seu segundo projeto será aplicar o layout responsivo da versão web do Instagram, utilizando HTML e CSS. Tente deixar sua página ao máximo parecida com o [layout fornecido](https://github.com/Ranbut/projeto2-instagram/blob/main/layout/Instagram%20Layout.pdf)!

# Requisitos

Sinta-se à vontade para colocar as fotos de exemplo que quiser no seu Instagram! :)

- Layout
    - [X]  Aplicar layout para desktop, seguindo layout fornecido no figma
    - [X]  Aplicar layout para mobile, seguindo layout fornecido no figma
    - [X]  O layout sem sidebar deve ser ativado quando a largura da tela for menor que 935px
    - [X]  O layout para mobile deve ser ativado quando a largura da tela for inferior a 614px
    - [X]  Não é obrigatório que a sidebar fique fixa conforme o usuário desce na página como ocorre no Instagram (mas é um bônus)
- Ícones
    - [X]  Utilize os ícones da biblioteca Ionicons: [https://ionicons.com/](https://ionicons.com/)
    
- Stories
    - [X]  Na caixa dos stories, deve haver itens o suficiente para ultrapassar a largura, mas os itens a mais não devem ser exibidos, conforme layout
    - [X]  Deve haver, no modo desktop, uma setinha no canto direito dos stories (conforme mostrado no layout do figma)
    - [X]  A setinha não precisa funcionar ao clicar (só será possível quando vermos JavaScript)
    - [X]  Não pode haver um scroll horizontal visível

# Bônus

Bônus não são obrigatórios, mas caso tenha conseguido terminar todo o projeto antes do prazo, sugerimos fazer as seguintes funcionalidades:

- Vídeo
    - [X]  Pelo menos um dos posts deve ser um vídeo
    - [X]  Não é necessário ter o botão de play
    - [X]  O vídeo deve ser inserido tanto no formato .mp4 e .ogg, para que funcione em qualquer navegador
    - [X]  O vídeo deve ser iniciado automaticamente
    
    Nos arquivos úteis já tem um vídeo para facilitar essa parte :)
    
    Para não incomodar o usuário, os navegadores (nem todos) não permitem que um vídeo toque automaticamente a não ser que o som esteja desativado. Então, se colocou o atributo para iniciar o vídeo automaticamente e não funcionou, desative o som dele :)
    
- Sidebar fixa
    
    Se você acessar a página do Instagram do seu computador e descer na página, perceberá que a barra lateral continua visível, fixa na página.
    
    A ideia deste bônus é implementar este comportamento, fazendo que, ao descer na página, a coluna permaneça no mesmo lugar sempre.
    
- Comentários
    
    Pelos propósitos do projeto, não adicionamos os comentários dos posts no layout do Figma. Estes são os requisitos deste bônus:
    
    - [ ]  Ter comentários nos posts, com botão de like no canto direito em cada comentário
    - [ ]  Uma caixa para digitar o comentário, utilizando a tag `input`
    - [ ]  Um botão ao lado desta caixa para **Publicar**, com cor `#B2DFFC` inicialmente e, ao passar o mouse, fique com a cor `#0095F6` com uma transição que dura `300ms`. Procure pela propriedade *transition* para fazer isso :)
