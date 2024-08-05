<h1 align="center">Gasto de Viagem</h1>

<p align="center">
  <a href="https://opensource.org/licenses/Apache-2.0"><img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"/></a>
  <a href="https://android-arsenal.com/api?level=27"><img src="https://img.shields.io/badge/API-27%2B-brightgreen.svg?style=flat" border="0" alt="API"></a>

  <br>
  <a href="https://wa.me/+5519989091331"><img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/vinicius-buzzo-casaca/"><img alt="Linkedin" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:vinicasaca@hotmail.com"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">  

⭐ Esse é um projeto para demonstrar meu conhecimento técnico no desenvolvimento Android nativo com Kotlin. Mais informações técnicas abaixo.

Visão Geral

O aplicativo "Gasto Viagem" foi desenvolvido para ajudar os usuários a calcular o custo total de uma viagem com base em variáveis como distância, preço do combustível e autonomia do veículo. A interface amigável e as funcionalidades bem definidas proporcionam uma experiência intuitiva para o usuário.

Conhecimentos Técnicos Utilizados:

- Arquitetura de Aplicação:

Activity: A MainActivity é a principal atividade que gerencia a interface do usuário. Ela implementa a interface View.OnClickListener para lidar com eventos de clique.

Data Binding: Utilizado para ligar os componentes da interface do usuário às variáveis do layout. A classe ActivityMainBinding facilita o acesso e a manipulação dos componentes de interface.

- Validação de Dados:

isValid: Método utilizado para garantir que todos os campos de entrada estejam preenchidos e que a autonomia não seja zero. Isso evita cálculos incorretos e possíveis falhas no aplicativo.

- Compatibilidade e Estilo:

Compatibilidade com Diferentes Versões do Android: Utiliza componentes da biblioteca de suporte (androidx) para garantir compatibilidade com várias versões do Android.
Estilo e Temas: Personalização do estilo dos componentes da interface do usuário para uma aparência coesa e agradável, utilizando recursos como bg_rounded_corner e primaryColor.
</p>

</br>

<p float="left" align="center">
<img alt="screenshot" width="30%" src="app/screenshots/print app gasto.png"/>
</p>

## Download

Faça o download da <a href="app/apk/app-debug.apk?raw=true">APK diretamente</a>. Você pode ver <a href="https://www.google.com/search?q=como+instalar+um+apk+no+android">aqui</a> como instalar uma APK no seu aparelho android.

## Tecnologias usadas e bibliotecas de código aberto

- Minimum SDK level 27
- [Linguagem Kotlin](https://kotlinlang.org/) 

- Jetpack
  
  ViewBinding: Utilizado para ligar os componentes da interface do usuário (definidos em XML) às propriedades no código Kotlin, garantindo segurança de tipo e facilidade de acesso aos elementos da UI.

- Arquitetura
- MVC (Model-View-Controller):

View: XML layout para a interface do usuário.

Controller: MainActivity gerencia a interação do usuário e os eventos de clique.

Model: Os dados são gerenciados dentro da atividade, sem uma separação explícita entre as camadas.

## Arquitetura
Gasto Viagem utiliza a arquitetura MVVM (Model-View-ViewModel) e o padrão de Repositories, que segue as recomendações oficiais do Google.
</br></br>
## Features

### Feature App
<img src="app/screenshots/feature.gif" width="25%"/>

Utilização do aplicativo de maneira simples e intuitiva!

# Licença
 

```xml
Copyright [2024] [Vinicius Buzzo]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

```
