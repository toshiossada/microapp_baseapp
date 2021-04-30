# FLUTTER - BASE APP

#### Versão 1.0
Para rodar o projeto execute o **flutter pub get** para baixar as dependências e depois **flutter run**

# I - Introdução

O base app é o ponto de entrada da aplicação, ele irá conversar somente com o **CORE** que irá acessar os modulos.
É o único que conhece todo o micro app
Ele irá ter a chamado do runApp()

    void main() => runApp(
      ModularApp(
        module: AppModule(),
        child: AppWidget(
          initialRoute: '/splash',
        ),
      ),
    );

# II - Dependências 
  commons:
    git:
      url: https://github.com/toshiossada/microapp_commons.git
      ref: v1.0.0
  core:
    path: '../core'
    
# III - Telas

![App](https://media3.giphy.com/media/j0NLsIT8GqF1RQnQMe/giphy.gif)
