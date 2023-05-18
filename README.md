<!-- conceito padrão mvc -->

# Padrão MVC
MVC (Model-View-Controller) é um padrão arquitetural amplamente utilizado em desenvolvimento de software para criar aplicativos com uma divisão clara e organizada entre as responsabilidades dos componentes. O padrão MVC foi criado em meados dos anos 70, originalmente para aplicativos de desktop, mas foi adaptado posteriormente para aplicativos web.

## Model
representa a camada de dados, que é responsável pela lógica de negócios e manipulação de dados. Ele não tem conhecimento da camada de apresentação, nem da camada de controle.

## View
representa a camada de apresentação, que é responsável por exibir os dados ao usuário. Ele não tem conhecimento da camada de controle, nem da camada de modelo.

## Controller
representa a camada de controle, que é responsável por gerenciar as interações entre o usuário e o sistema. Ele é o intermediário entre a camada de apresentação e a camada de modelo.

![grafico](https://www.usandopy.com/media/uploads/2023/03/22/pt-cover-website-22.png)           

## Separação clara das responsabilidades
O MVC divide as responsabilidades do aplicativo em camadas distintas, o que facilita o desenvolvimento, teste e manutenção do software. Cada camada tem responsabilidades bem definidas, tornando o código mais organizado e legível.

## Reutilização de código
A separação de responsabilidades também facilita a reutilização de código. O modelo e a camada de controle podem ser usados em diferentes projetos, enquanto a camada de apresentação pode ser facilmente personalizada para diferentes dispositivos.

## Maior escalabilidade
O MVC permite que os desenvolvedores gerenciem o crescimento do aplicativo de forma mais eficaz. A separação das responsabilidades ajuda a minimizar a complexidade do código e facilita a adição de novos recursos.


<!-- conceito framework -->
# Frameworks
Framework nos auxilia no desenvolvimento de aplicações web. Com ele, nós conseguimos ter facilidade e flexibilidade para trabalhar com requisições web.

## Frameworks que usam MVC

### Ruby on Rails
É um framework web escrito em Ruby que usa o padrão MVC para organizar o código.

### Laravel
É um framework web escrito em PHP que segue o padrão MVC.

### Django
É um framework web escrito em Python que usa o padrão MVC.

### Spring
É um framework de aplicação Java que usa o padrão MVC para separar a lógica de negócios da interface do usuário.

### AngularJS
É um framework JavaScript que usa o padrão MVVM (Model-View-ViewModel), que é uma variação do padrão MVC.



<!-- conceito biblioteca -->
# Biblioteca 

Uma biblioteca é uma solução de estruturas e algoritmos, um conjunto de features relacionadas. Sem dúvida ela pode conter helpers. Eventualmente uma biblioteca pode ser composta só de helpers. No contexto do MVC o helper é algo que deve ser usado para organizar a aplicação.

### Biblioteca que usa MVC EM JavaScript 
*React*
É uma biblioteca JavaScript para construção de interfaces de usuário que segue uma arquitetura fluxo unidirecional, mas também é comum a sua utilização com o padrão MVC.



# Links úteis
https://www.youtube.com/watch?v=jyTNhT67ZyY

https://raullesteves.medium.com/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8
