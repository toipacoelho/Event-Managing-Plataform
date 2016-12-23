Esta ativo o SSL pelo que quando se executa o teste é necessário adicionar uma exceção de segurança no browser pois não existe certificado associado.

Utilizadores:
* admin@edc.com
* Pa$$word1
* user@edc.com
* Pa$$word1

Funcionalidades:
* Lista utilziadores e roles
--* painel de administração na navbar
* Criar eventos
--* logado através da navbar
* Listar eventos
--* através da navbar
* Web service [listagem de eventos]
--* através do home screen debaixo do jumbotron

Foi tentanto implementar um mapa e texbox com autocomplete na pagina para criar eventos. Código referente ao mapa encontra-se comentado.
Esta tarefa foi tentada com recurso à API da Google e do Bing Maps. A dificuldade em concluir a mesma resulta do facto destas APIs funcionarem sobre javascript clientside, existindo alguma dificultade em extrair as informações no codebehind, uma vez que este executa do lado do servidor.

Existe também suporte para Oauth, esta funcionalidade esta ativa com chaves do Facebook e do Google.

A base de dados XML foi iniciada com o schema do xml que define os eventos e respetiva tabela, existiu alguma dificuldade em conseguir atualizar a respetiva tabela.