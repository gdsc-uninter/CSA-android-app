# CSA android-app

O app será estruturado usando a arquitetura MVVM e muitas blibiotecas do Android Jetpack. Listo algumas informações úteis de tudo que será usado no projeto:

### [Android App Architecture](https://miro.com/app/board/o9J_l4kQfR4=/)
> Um visão geral de todo a arquitetura do projeto

### [Prototype](https://www.figma.com/proto/oX71OevBT63G53fIfGrGXe/CSA---android-app?node-id=414%3A3543&scaling=scale-down&page-id=4%3A0&starting-point-node-id=414%3A3543)
> Protótipo de todas as funcionalidades e do design do aplicativo

<br/>

## Dependências

#### [Material Design](https://material.io/components?platform=android)
Material é um sistema de design criado pelo Google para ajudar as equipes a criar experiências digitais de alta qualidade para Android, iOS, Flutter e web.

#### [ViewBinding](https://developer.android.com/topic/libraries/view-binding)
ViewBinding é um recurso que facilita a programação de códigos que interagem com visualizações.

#### [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
O LiveData faz parte da biblioteca Lifecycle que foi projetada para ajudá-lo a resolver desafios comuns do Android Lifecycle e tornar seus aplicativos mais fáceis de manter e testáveis. LiveData é um observável ciente do ciclo de vida. O LiveData torna mais fácil manter o que está sendo exibido na tela em sincronia com os dados.

#### [ViewModel](https://developer.android.com/topic/libraries/architecture/lifecycle)
A classe ViewModel foi projetada para armazenar e gerenciar dados relacionados à IU de uma maneira consciente do ciclo de vida. A classe ViewModel permite que os dados sobrevivam às mudanças de configuração, como rotações de tela.

#### [Navigation](https://developer.android.com/guide/navigation)
Navigation refere-se às interações que permitem aos usuários navegar entre, acessar e voltar das diferentes partes do seu aplicativo. O componente de Navigation do Android Jetpack ajuda a implementar a navegação, desde simples cliques em botões até padrões mais complexos, como statusbar de aplicativos e barra de navegação.

#### [Room](https://developer.android.com/topic/libraries/architecture/room)
A biblioteca de persistência da Room oferece uma camada de abstração sobre o SQLite para permitir um acesso mais robusto ao banco de dados, aproveitando todo o poder do SQLite. A biblioteca ajuda a criar um cache dos dados do seu aplicativo em um dispositivo que está executando o seu aplicativo.

#### [WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager)
WorkManager é uma biblioteca Android Jetpack que executa um trabalho em segundo plano adiável e garantido quando as restrições do trabalho são satisfeitas. WorkManager é a prática recomendada atual para muitos tipos de trabalho em segundo plano. 

#### [Retrofit](https://square.github.io/retrofit/)
Retrofit é um cliente REST para Android e Java. Isso torna relativamente fácil recuperar e fazer upload de JSON (ou outros dados estruturados) por meio de um serviço da web baseado em REST. No Retrofit você configura qual conversor será utilizado para a serialização dos dados.

#### [Gson](http://square.github.io/retrofit/)
Gson é uma biblioteca Java que pode ser usada para converter objetos Kotlin em sua representação JSON. Ele também pode ser usado para converter uma string JSON em um objeto Kotlin equivalente. Gson pode trabalhar com objetos Kotlin arbitrários, incluindo objetos pré-existentes dos quais você não possui o código-fonte.

#### [Hilt](https://developer.android.com/training/dependency-injection/hilt-android)
O Hilt é uma biblioteca de injeção de dependência para Android que reduz a injeção manual de código de texto clichê no projeto. O Hilt foi criado com base na conhecida biblioteca de DI Dagger para aproveitar a precisão do tempo de compilação, o desempenho no tempo de execução, a escalonabilidade e o suporte do Android Studio fornecido pelo Dagger.

#### [Espresso](https://developer.android.com/training/testing/espresso/setup)
O Espresso é uma estrutura de teste para Android que torna mais fácil escrever testes de interface de usuário confiáveis. A estrutura também garante que sua atividade seja iniciada antes da execução dos testes.

#### [Mockito](https://site.mockito.org/)
Mockito é um framework mock popular que pode ser usado em conjunto com JUnit. O Mockito permite criar e configurar objetos fictícios. O uso do Mockito simplifica significativamente o desenvolvimento de testes para classes com dependências externas.

#### [Firebase Authentication](https://firebase.google.com/docs/auth/)
O Firebase Authentication fornece serviços de back-end, SDKs fáceis de usar e bibliotecas de IU prontas para autenticar usuários em seu aplicativo. Ele suporta autenticação usando senhas, números de telefone, provedores de identidade populares como Google, Facebook e Twitter e muito mais.
