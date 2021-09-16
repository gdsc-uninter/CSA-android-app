# CSA android-app

O app será estruturado usando a Clean Architecture + MVVM e muitas blibiotecas do Android Jetpack. Listo algumas informações úteis de tudo que será usado no projeto:

### [Android App Architecture](https://drive.google.com/file/d/1Ink-r5Z2dRmLfwP6ZAFzVQPj9hz7R_0n/view?usp=sharing)
> Um visão geral de todo a arquitetura do projeto

### [Prototype](https://www.figma.com/proto/oX71OevBT63G53fIfGrGXe/CSA-android-app?node-id=414%3A3543&scaling=scale-down&page-id=4%3A0&starting-point-node-id=414%3A3543&hide-ui=1)
> Protótipo de todas as funcionalidades e do design do aplicativo

## Dependências

#### [Material Design](https://material.io/components?platform=android)
Material é um sistema de design criado pelo Google para ajudar as equipes a criar experiências digitais de alta qualidade para Android, iOS, Flutter e web.

#### [Jetpack Compose](https://developer.android.com/jetpack/compose)
O Jetpack Compose é um kit de ferramentas moderno do Android para criar IUs nativas. Ele simplifica e acelera o desenvolvimento da IU no Android. Dê vida ao seu app rapidamente com menos código, ferramentas eficientes e APIs Kotlin intuitivas.

#### [ViewModel](https://developer.android.com/topic/libraries/architecture/lifecycle)
A classe ViewModel foi projetada para armazenar e gerenciar dados relacionados à IU de uma maneira consciente do ciclo de vida. A classe ViewModel permite que os dados sobrevivam às mudanças de configuração, como rotações de tela.

#### [State, MutableState](https://developer.android.com/jetpack/compose/state)
O estado em um app é qualquer valor que pode mudar ao longo do tempo. Essa é uma definição muito ampla e abrange tudo, de um banco de dados da Room até a variável em uma classe.

#### [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
O LiveData faz parte da biblioteca Lifecycle que foi projetada para ajudá-lo a resolver desafios comuns do Android Lifecycle e tornar seus aplicativos mais fáceis de manter e testáveis. LiveData é um observável ciente do ciclo de vida. O LiveData torna mais fácil manter o que está sendo exibido na tela em sincronia com os dados.

### [Coroutines](https://developer.android.com/kotlin/coroutines)
No Android, as corrotinas ajudam a gerenciar tarefas de longa duração que podem bloquear a linha de execução principal e fazer com que seu app pare de responder. Mais de 50% dos desenvolvedores profissionais que usam corrotinas notaram um aumento na produtividade. Este tópico descreve como você pode usar corrotinas do Kotlin para resolver esses problemas, permitindo criar um código de app mais simples e conciso.

#### [Navigation](https://developer.android.com/jetpack/compose/navigation)
Navigation refere-se às interações que permitem aos usuários navegar entre, acessar e voltar das diferentes partes do seu aplicativo. O componente de Navigation do Android Jetpack ajuda a implementar a navegação, desde simples cliques em botões até padrões mais complexos, como statusbar de aplicativos e barra de navegação.

#### [Firebase Authentication](https://firebase.google.com/docs/auth/)
O Firebase Authentication fornece serviços de back-end, SDKs fáceis de usar e bibliotecas de IU prontas para autenticar usuários em seu aplicativo. Ele suporta autenticação usando senhas, números de telefone, provedores de identidade populares como Google, Facebook e Twitter e muito mais.   

#### [Firebase Realtime database](https://firebase.google.com/docs/database/android/start)
O Firebase Realtime Database é um banco de dados hospedado na nuvem. Os dados são armazenados como JSON e sincronizados em tempo real para cada cliente conectado. Quando você cria aplicativos de multi-plataforma com nossos SDKs para iOS, Android e JavaScript, todos os seus clientes compartilham uma instância do Realtime Database e recebem automaticamente atualizações com os dados mais recentes. 
> [Projeto exemplo](https://github.com/alexmamo/RealtimeDatabase)

#### [WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager)
WorkManager é uma biblioteca Android Jetpack que executa um trabalho em segundo plano adiável e garantido quando as restrições do trabalho são satisfeitas. WorkManager é a prática recomendada atual para muitos tipos de trabalho em segundo plano. 

#### [Hilt](https://developer.android.com/training/dependency-injection/hilt-android)
O Hilt é uma biblioteca de injeção de dependência para Android que reduz a injeção manual de código de texto clichê no projeto. O Hilt foi criado com base na conhecida biblioteca de DI Dagger para aproveitar a precisão do tempo de compilação, o desempenho no tempo de execução, a escalonabilidade e o suporte do Android Studio fornecido pelo Dagger.

#### [Espresso](https://developer.android.com/training/testing/espresso/setup)
O Espresso é uma estrutura de teste para Android que torna mais fácil escrever testes de interface de usuário confiáveis. A estrutura também garante que sua atividade seja iniciada antes da execução dos testes.

#### [Mockito](https://site.mockito.org/)
Mockito é um framework mock popular que pode ser usado em conjunto com JUnit. O Mockito permite criar e configurar objetos fictícios. O uso do Mockito simplifica significativamente o desenvolvimento de testes para classes com dependências externas.

<br/>

```
MIT License

Copyright (c) 2021 Google DSC Uninter

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
