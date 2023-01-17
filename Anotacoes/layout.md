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
    Em *Gradle Scripts* acesse *build.gradle / app level* na classe Android e adicione o seguinte trecho de        código:
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
    
