1 -Tipo de Teste: Funcional.
Objetivo: Testar se o usuário consegue logar no sistema.
Motivação: O sistema deve permitir o login de usuários registrados
Descrição: Usuário deve informar um login e senha já existente nos campos indicados (ex:user123 como usuário e senha 123) e clicar no botão confirmar, caso confirme, sisitema avisará que o login foi executado com sucesso.

2 -Tipo de Teste: Funcional.
Objetivo: Testar se o usuário consegue visualizar listas de consultas.
Motivação: O sistema deve permitir a visualização de consultas.
Descrição: Usuário realiza o login e clica no botão de listar, que exibirá a lista de consultas.

3 -Tipo de Teste: Funcional.
Objetivo: Testar se o adminstrador consegue logar no sistema com sucesso.
Motivação: O sistema deve permitir que o usuário administrador consiga realizar o login.
Descrição: Administrador coloca login admin e senha admin nos campos, clicando no botão confirmar, caso confirme, será enviado a página de administrador.

4 -Tipo de Teste: Funcional.
Objetivo: Testar se o administrador consegue cancelar consulta.
Motivação: O sistema deve permitir a exclusão de consultas realizadas.
Descrição: Administrador realiza o seu login, na suá pagina, deve preencher o id da consulta que deseja excluir (ex:1), caso confirme, mensagem de "consulta cancelada" será enviada.

5 -Tipo de Teste: Não Funcional.
Objetivo: Testar quando o administrador usa um id inválido para cancelar consulta.
Motivação: O sistema deve permitir cancelar consulta apenas com o campo preenchido corretamente.
Descrição: Administrador realiza login, na sua página tenta colocar um id que não exista na lista de consultas (ex:999), então a mensagem "não existe essa consulta" deve ser enviada.
