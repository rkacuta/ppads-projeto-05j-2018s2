1 -Tipo de Teste: Funcional.
Objetivo: Testar se o usuário consegue logar no sistema.
Motivação: O sistema deve permitir o login de usuários registrados
Descrição: Usuário deve clicar no botão marcar consulta, então informar um login e senha já existente nos campos indicados (ex:user como usuário e senha 123) e clicar no botão login, caso confirme, sistema enviará uma mensagem de bem vindo + "nome do usuário".

2 -Tipo de Teste: Funcional.
Objetivo: Testar se o usuário consegue visualizar listas de consultas.
Motivação: O sistema deve permitir a visualização de consultas.
Descrição: Usuário deve realizar o login e clicar no botão de listar, que exibirá a lista de consultas.

3 -Tipo de Teste: Funcional.
Objetivo: Testar se o adminstrador consegue logar no sistema com sucesso.
Motivação: O sistema deve permitir que o usuário administrador consiga realizar o login.
Descrição: Administrador coloca login admin e senha admin nos campos, clicando no botão logar, caso confirme, será enviado a página de administrador.

4 -Tipo de Teste: Funcional.
Objetivo: Testar se o administrador consegue cancelar consulta.
Motivação: O sistema deve permitir a exclusão de consultas realizadas.
Descrição: Administrador realiza o seu login, na suá pagina, deve preencher o id da consulta que deseja excluir (ex:1),então será mostrado uma mensagem pedindo para confirmar essa exclusão, caso clique em "sim", caso confirme, a consulta será apagada.

5 -Tipo de Teste: Não Funcional.
Objetivo: Testar quando o administrador usa um id inválido para cancelar consulta.
Motivação: O sistema deve permitir cancelar consulta apenas com o campo preenchido corretamente.
Descrição: Administrador realiza login, na sua página, no campo ID deve inserir um número que não exista na lista de consultas (ex:999), então o sistema deve mostrar a mensagem "id não existe".
