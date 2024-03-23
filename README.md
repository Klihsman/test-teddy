Olá, me chamo Klihsman Freitas e este repositório é produto do teste técnico proposto pela empresa Teddy Open Finance

**TODO LIST (Os itens que tiverem (NOT) não foram feitos || Os itens que tiverem estimativa de tempo são consideradas tasks mães para das demais que vierem a baixo)**

* Criar um projeto Single-SPA com micro front-ends separados por domínios ou contextos de uso. - 1 Dia
* Utilizar Angular na versão 15 em pelo menos um dos micro front-ends.
* Preparar um README.md detalhado para facilitar a configuração do projeto.
* Implementar uma página de login. - 30 minutos
 
* Criar um formulário com opção de digitar usuário e senha.
* Ao clicar em "entrar", redirecionar para a página inicial.
* Funcionalidade de "Manter Conectado":

* Implementar a opção de "manter conectado" na tela de login.
* Salvar o usuário no cookie se a opção estiver marcada, caso contrário, salvar no local storage.
* Ao entrar na página, buscar o nome do usuário no cookie.

* Criar uma página inicial com layout da aplicação, incluindo um menu e os itens especificados. - 4 horas
* Implementar funcionalidade de cadastrar parceiro.
* Implementar funcionalidade de listar todos os parceiros com paginação.
* Incluir ações na última coluna da tabela para editar/deletar registro.

* Criar uma página "Sobre a Aplicação" com informações relevantes sobre o projeto, tecnologias utilizadas, etc.

* Implementar página para cadastrar empresa externa.
* Integrar com a API para persistir o CRUD.
* Página de Listar Empresas Externas:

* Implementar página para listar todas as empresas externas com paginação.
* Incluir ações na última coluna da tabela para editar/deletar registro.
* Compartilhar Dados da Tabela:
* Implementar mecanismo para compartilhar o link da página com paginação.
**

* (NOT) Ao compartilhar o link, redirecionar o usuário para a página específica da tabela.
* (NOT) Criar DockerFile

**Projetos**

**Projetos React (home port - 8081, login - port 8082, navBar - port 8080)**

1 - yarn install

2 - yarn start --port (valor da porta do projeto)

**Projetos Angular (partners, external-Company)**

1 - yarn install

2 - npm run serve:single-spa:{nome-do-projeto}

**Projeto Root (root)**

1 - yarn install

2 - yarn start
