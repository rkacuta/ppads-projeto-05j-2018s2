# Casos de uso

## CDU001: Marcar consulta
### Fluxo principal
- Cliente acessa página web
- Cliente realiza login
- Cliente acessa aba marcar consulta
- Sistema mostra lista de consulta disponiveis (nome do veterinário, tipo de animal, data e hora)
- Cliente escolhe a consulta que deseja marcar
- Cliente confirma escolha

## CDU002: Visualizar consulta
### Fluxo principal
- Cliente acessa página web
- Cliente realiza login
- Cliente acessa aba visualizar consulta
- Sistema mostra lista de consultas marcadas

## CDU003: Cancelar consulta
### Fluxo principal
- Cliente acessa página web
- Cliente realiza login
- Cliente acessa aba visualizar consulta
- Sistema mostra lista de consultas marcadas
- Cliente escolhe a consulta que deseja cancelar
- Cliente confirma escolha

## CDU004: Verificar veterinário
### Fluxo principal
- Cliente acessa página web
- Cliente realiza login
- Cliente acessa aba verficar veterinário
- Sistema mostra lista de veterinários com os animais que cuidam

## CDU005: Verificar datas disponiveis
### Fluxo principal
- Cliente acessa página web
- Cliente realiza login
- Cliente acessa aba verificar datas disponiveis
- Sistema mostra as datas livres

## CDU006: Deletar veterninário
### Fluxo principal
- Usuário admin acessa página web
- Usuário admin realiza login
- Usuário admin acessa aba lista de veterinários
- Sistema mostra a lista de veterinários com seus respectivos IDs
- Usuário admin digita o ID do veterinário que será excluido
- Usuário admin confirma escolha

## SPRINT 1
### Marcar consulta - Fluxo alternativo:
- Cliente acessa aba marcar consulta
- Sistema mostra lista de consulta disponiveis (nome do veterinário, tipo de animal, data e hora)
- Cliente escolhe a consulta que deseja marcar
- Cliente confirma escolha
- O cliente digitou N ao invés de S
- Sistema exibe mensagem de "Consulta cancelada"
- Sistema mostra lista de consulta disponiveis (nome do veterinário, tipo de animal, data e hora)

### Cancelar consulta - Fluxo alternativo:
- Sistema mostra lista de consultas marcadas
- Cliente escolhe a consulta que deseja cancelar
- Cliente confirma escolha 
- O cliente digitou N ao invés de S
- Sistema mostra lista de consultas marcadas
