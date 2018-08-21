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

## CDU003

### Fluxo principal

cliente -> marcar  consulta
	-> visualizar consulta
	-> cancelar consulta
	-> verificar datas disponiveis
	-> verificar veterinarios disponiveis 
	
veterinario -> visualizar consultas
	   
usuario adm -> marcar  consulta
            -> visualizar consulta
            -> cancelar consulta
            -> verificar datas disponiveis
	    -> verificar veterinarios disponiveis 
	-> cadastra veterinarios
	-> deleta veterinario
