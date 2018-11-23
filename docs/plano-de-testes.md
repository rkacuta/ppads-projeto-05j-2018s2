1 -Tipo de Teste: Funcional.
Objetivo: Testar se o usuário consegue logar no sistema.
Motivação: O sistema deve permitir o login de usuários registrados
Passos:
- Clicar na aba "Marcar consulta".
- Sistema ira para a página "marcar.html"
- Preencher o campo usuário com 123
- Preencher o campo senha com 123.
- Clicar no botão login.
- Será devolvida mensagem "Bem Vindo" + nome do login se os dados estiverem corretos.

2 -Tipo de Teste: Funcional.
Objetivo: Testar se o usuário consegue visualizar listas de consultas.
Motivação: O sistema deve permitir a visualização de consultas.
Passos:
- Clicar no botão "Listar consultas"
- Irá aparecer id, datahora, veterinário, animal, hora, unidade de cada consulta.

3 -Tipo de Teste: Funcional.
Objetivo: Testar se o adminstrador consegue logar no sistema com sucesso.
Motivação: O sistema deve permitir que o usuário administrador consiga realizar o login.
Passos:
- Clicar na aba "Marcar consulta".
- Sistema ira para a página "admLogin.html"
- Preencher o campo usuário com admin.
- Preencher o campo senha com admin.
- Clicar no botão login.
- Caso os dados estiverem corretos, será devolvida mensagem "Logado com sucesso" e o usuário será enviado a página "adm.html".

4 -Tipo de Teste: Funcional.
Objetivo: Testar se o administrador consegue cancelar consulta.
Motivação: O sistema deve permitir a exclusão de consultas realizadas.
Passos:
-Repetir teste 3
-Preencher o campo ID com uma consulta existente (ex: 1)
-Clicar em "cancelar consulta"
-Aparecerá uma caixa de texto perguntando se deseja cancelar consulta.
-Clicar em "Sim".
-Mensagem "Consulta cancelada" será enviada

5 -Tipo de Teste: Não Funcional.
Objetivo: Testar quando o administrador usa um id inválido para cancelar consulta.
Motivação: O sistema deve permitir cancelar consulta apenas com o campo preenchido corretamente.
Passos:
- Repetir teste 3
- Preencher o campo ID com uma consulta não-existente (ex: 999)
- Clicar em "cancelar consulta"
- Aparecerá uma caixa de texto perguntando se deseja cancelar consulta.
- Clicar em "Não".
- Mensagem "Consulta não existe" será enviada
