#Drupal Boilerplate#
-

##Informações do Projeto##

- Ambiente de produção: http://site.com.br (Ainda legado)
- Ambiente de desenvolvimento: http://site.dev.mmda.com.br [TODO]
- Ambiente de testes: http://site.test.mmda.com.br [TODO]

- Repositório de código principal: http://bitbucket.org/mmda/[TODO]
- Issue tracker: http://extranet.mmda.com.br/youtrack/issues/[TODO]
- Interação com o cliente: https://mmda.basecamphq.com/projects/[TODO]
- Credenciais: [TODO]

##Envolvidos##
- [Nome do Caboclo](mailto:email@mmda.com.br) - Cargo e papel no projeto
- [Felipe Fidelix](mailto:felipe@mmda.com.br) - Arquiteto e Desenvolvedor

##TODO##
- Ambiente de desenvolvimento e testes
- Repositório de código principal
- Issue tracker
- Interação com o cliente
- Link de credenciais
- Listar o envolvido do cliente
- Colocar informações práticas de desenvolvimento do projeto.

##FOLDERS##
* [docroot](blob/master/docroot)
 * Raiz do Drupal
* [drush](blob/master/drush)
 * Comandos, aliases e configurações do drush específicas do projeto.
* [patches](blob/master/patches)
  * Patches aplicados no projeto.
* [results](blob/master/results)
 * Resultados de testes exportados. Um bom exemplo disto é quando se roda
   drush test-run com a opção --xml. Você pode exportar o xml para este
   diretório para "parse" por ferramentas externas como o jenkins.
* [tests](blob/master/tests)
 * Diretório para testes externos. Ótimo para testes não-específicos do drupal
   como selenium, qunit, casperjs, jasmine.
