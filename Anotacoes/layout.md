# Layout
- Android Jet-pack: é um conjunto de bibliotecas que encapsula uma série de práticas e bibliotecas recomendadas. Reduz o código.
  - é composto por: Behavior(permissões, compartilhamento, controle), Foundations(pacotes, compatibilidade), Architecture e UI.
  <br>
  <img width="400" src="https://media.geeksforgeeks.org/wp-content/uploads/20201116223336/AndroidJetpackComponents-660x403.png">
 *fonte: https://www.geeksforgeeks.org/introduction-to-android-jetpack/*
<br>

- View Binding: facilita o acesso a componentes definidos no layout XML. Evita a repetição de código buscando o id de componentes através do métdodo *findViewById*.
  - Como utilizar o View Binding?
  <br>
    Em *Gradle Scripts* acesse *build.gradle / app level* na classe Android e adicione o seguinte trecho de código:
    <br>
    Exemplo:
   
    ```
    Android {
      ...
      buildFeatures{
        viewBinding true
      }
    } 
    ```
- O id de um componente em xml: android:id="@+id/**nome**"
- Material design: é um sistema de design criado pelo google que engloba UI e UX para padronizar designs.

## Explorando o xml...
- Constraint layout: flexibiliza as posições do componentes na tela.
- Swipe refresh: quando o usuário rolar para baixo a tela, ele irá carregar novamente, atualizando seu conteúdo.
- RecyclerView: equivalente a um list view. Por exemplo: a cada atualização de uma tela, os antigos dados são mantidos e adicionados novos também.
- Card View: visualização de dados em cards.
- *android:layout_height=”wrap_content”* --> o tamanho do card se adapta ao seu conteúdo.
- *android:text* --> atribui um valor direto a um text view. Não é recomendável usar quando conteúdo do text view irá variar de acordo com uma API, por exemplo.
- *tools:text* --> não atribui diretamente um valor ao componente textview, porém deixa um valor padrão(entrada do dev) para facilitar a visualização. É o mais recomendável a ser utilizado.


**Obs: são anotações da perspectiva de uma iniciante! Algo pode ter sido compreendido eqivocadamente ou não de forma plena.**


 
    
