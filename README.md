# +A Educação - Desenvolvedor Front-End

## Objetivo do Desafio

O objetivo deste desafio é avaliar as competências técnicas dos candidatos a desenvolvedor Front-End na Maior Plataforma de Educação do Brasil.

Será solicitado o desenvolvimento de uma página web responsiva baseada no layout fornecido no Figma. Regras e requisitos técnicos estão detalhadas abaixo.

## Especificações Técnicas

- **HTML/CSS**: O uso de HTML semântico e CSS modularizado é esperado. 
- **JavaScript**: Utilize JavaScript para adicionar interatividade ao site, como animações, transições e validações de formulários.
- **Responsividade**: A página deve ser totalmente responsiva, adaptando-se a diferentes tamanhos de tela (desktop e mobile) conforme o layout fornecido.
- **Acessibilidade**: Seguir as melhores práticas de acessibilidade web, garantindo que a página seja navegável por todos os usuários.
- **Envio de Formulário**: O formulário de contato deve estar funcional e enviar os dados para um e-mail preestabelecido, contanto que as validações sejam atendidas.
- **Validações de Formulário**:
  - **Campo de Nome**: Deve ter mais de 3 caracteres, não pode conter números ou caracteres especiais.
  - **Campo de E-mail**: Deve ser um endereço de e-mail válido.
- **Idioma de escrita do código**: Inglês

## Requisitos

### Contextualização

Considere que uma Instituição de Ensino Superior deseja criar uma landing page promocional para uma de suas campanhas educacionais. A página deve ser atrativa, acessível e completamente responsiva.

O desafio consiste em criar a página de acordo com o layout fornecido e os critérios de aceitação abaixo.

### Mockups de Interface

Os mockups da interface foram fornecidos e servem como guia para a criação do front-end. Utilize sua criatividade e habilidades técnicas para implementá-los.

- [Link para o layout no Figma](https://www.figma.com/design/tVVM84kkTzHuo7ZpWz9Zxl/LP-DEVS?node-id=3-1042&node-type=FRAME&t=zBOTwbyY5Ew6AHbR-0)

## Histórias do Usuário

- **Sendo um usuário da internet**
  - Quero visualizar uma landing page promocional
  - Para que eu possa entender os serviços oferecidos e entrar em contato

- **Sendo um visitante da página**
  - Quero preencher o formulário de contato
  - Para que eu possa enviar minhas informações diretamente para a instituição via e-mail

## Critérios de Aceitação

### Cenário: Exibir Landing Page em Diferentes Dispositivos

- **Dado** que estou acessando a página em um dispositivo desktop
- **Quando** abro a página
- **Então** a visualização deve corresponder ao layout fornecido para desktop

- **Dado** que estou acessando a página em um dispositivo móvel
- **Quando** abro a página
- **Então** a visualização deve corresponder ao layout fornecido para mobile

### Cenário: Interações e Acessibilidade

- **Dado** que estou visualizando a página
- **Quando** clico nos botões e links interativos
- **Então** eles devem responder de forma visual e funcional
- **E** a navegação pela página deve ser fluida e intuitiva

### Cenário: Formulário de Contato Funcional com Validações

- **Dado** que estou visualizando a página
- **Quando** preencho o formulário de contato
- **E** o campo de nome tem mais de 3 caracteres e não contém números ou caracteres especiais
- **E** o campo de e-mail contém um endereço de e-mail válido
- **Então** os dados devem ser enviados para um e-mail preestabelecido
- **E** uma mensagem de confirmação deve ser exibida ao usuário

## Critérios de Avaliação

- **Qualidade de escrita do código**
- **Organização do projeto**
- **Qualidade do CSS e JavaScript utilizados**
- **Aderência ao layout fornecido**
- **Acessibilidade e responsividade**
- **Funcionalidade do formulário**
- **Validações de formulário**
- **Tratamento de erros**

## Diferenciais

- **SEO básico implementado**
- **Segurança do código JavaScript (evitar XSS, por exemplo)**

## Instruções de Entrega

- Faça o push do código desenvolvido no seu GitHub
- Inclua um arquivo chamado `COMMENTS.md` explicando:
  - Lista de bibliotecas de terceiros utilizadas
  - O que você melhoraria se tivesse mais tempo
  - Quais requisitos obrigatórios que não foram entregues
