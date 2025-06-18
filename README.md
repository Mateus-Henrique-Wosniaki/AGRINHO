# A Conexão Campo Cidade

## A Importância dessa conexão para a Sociedade


## Descrição
Este projeto consiste em uma aplicação *web* desenvolvida para o Projeto Agrinho. [Saiba Mais.](https://www.sistemafaep.org.br/agrinho/)


Trata-se de uma página expositiva para destacar a importância dessa conexão, visando os benefícios e aprendizados.

A página é composta apenas por elementos visuais, como textos, ícones e imagens. Com foco em um único ator: o Leitor.


## Execução
Para executar o projeto execute os seguintes passos:  

~~~html
1 - Clonar o repositório do projeto.
~~~
~~~html
2 - Abra o terminal e digite: 
git clone https://github.com/Mateus-Henrique-Wosniaki/Projeto-Agrinho.git
~~~
~~~html
3 - Executar o arquivo: index.html.
~~~


Ou, clique [Aqui](https://agrinho-liard-zeta.vercel.app/) para visualizar a página em seu navegador.


## Autor
Mateus Henrique Wosniaki  
mateus.wosniaki@escola.pr.gov.br  


## Educação
Orientadora: Profª Maria Aparecida Bilinowski Mazur
Colégio Estadual Professora Edithe  
Campo Largo - PR


## Linguagens e Bibliotecas
- Html 5
- Css 3
- V-Libras


## Status do Projeto
Finalizado


# Funcionalidades

Conforme mencionado anteriormente, esse projeto contém apenas elementos visuais. Para evidenciar todas as funcionalidades disponiveís é necessário entender a organização na página. E para isso, serve a seguinte descrição:

### Barra de Navegação

Com a barra de Naveção é possível acessar todas as seções da página, basta clicar sobre um item que nela contém, para ser redirecionado a seção correspondente. Ela é composta pelos seguintes itens:

- Início
- Resumo
- Eventos
- Sobre
- Contato

### Seções

As seções são responsáveis por separar os conteúdos da página. Conforme apresentado acima, neste projeto existem 5 seções, e cada uma delas contém conteúdos expecíficos, sendo:

> [**INICIO**]
   >> Introduz ao leitor o objetivo do projeto, atrevés de conceitos iniciais.

> [**RESUMO**]
>> Abrange os seguintes temas: Benefício, Importância, Dependência. Apresentando mais detalhes sobre a conexão Campo-Cidade.

> [**EVENTOS**]
>> Apresenta dois principais eventos do Estado do Paraná, que festejam esta conexão. Destaca características e atrações de cada evento.

> [**SOBRE**]
>> Descreve o objetivo do projeto e suas informações de criação.

> [**CONTATO**]
>> Apresenta o email @escola do estudante para contato.


### Rodapé

O Rodapé do site serve para fornecer informações adicionais ao conteúdo da página. Nele estão presentes o ano e autor do conteúdo e a parte legal sobre os direitos autorais. Com isso, conclui-se a página, como uma área de fechamento.

### V-Libras

"O VLibras Widget é um recurso de acessibilidade desenvolvido para tornar páginas web acessíveis para pessoas surdas. Com a tradução automática de Português Brasileiro para a Língua Brasileira de Sinais (LIBRAS), essa ferramenta permite que usuários surdos sejam capazes de consumir conteúdos de texto em qualquer website." [V-LIBRAS(2025)](https://vlibras.gov.br/doc/widget/introduction/presentation.html).


Neste projeto a biblioteca V-LIBRAS está sendo utilizada para promover a acessibilidade e a inclusão.

A parte no qual é feita a integração encontra-se nas primeira linhas depois da tag < body >:

~~~html
<div vw class="enabled">
    <div vw-access-button class="active"></div>
    <div vw-plugin-wrapper>
      <div class="vw-plugin-top-wrapper"></div>
    </div>
  </div>
  <script src="https://vlibras.gov.br/app/vlibras-plugin.js"></script>
  <script>
    new window.VLibras.Widget('https://vlibras.gov.br/app');
  </script>
~~~

