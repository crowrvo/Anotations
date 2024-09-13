Usuário que é identificado pelo Documento

Evento que é identificado pelo Nome

Participação que não tem identificação direta, mas serve para informar se um usuário esta participando de um determinado evento

Funções

- Cadastro de Usuário
	- Condições
		- Um mínimo de 3 atributos
		 Obrigatoriamente precisa de uma identificação (atualmente escolhida como documento)
		- Obrigatoriamente ele precisa de um endereço (afinal precisamos comparar ele com o do evento)
		- o Atributo Documento deve ser único pois serve como identificação.
		 
- Cadastro de Evento
	-	Condições
		-	Atributos Obrigatórios: Nome, Endereço, Categoria, horário e descrição.
		-	 Delimitar as categorias ao seguinte grupo (Festas, eventos, shows, etc...)
		-	 O Atributo horário precisa informar inicio e fim do evento caso o evento receba data e hora, caso receba apenas data, só precisa do inicio
		- chamar a função de Escrever eventos no arquivo
		- o atributo NOME deve ser único, pois serve como identificação

- Notificação de Evento **PRINCIPAL OBJETIVO** 
	- Execuções
		- Fica a critério do desenvolvedor
		- Destacar eventos ocorrendo na mesma cidade
	- Condições
		- O Usuário precisa confirma a participação no evento
		- O Usuário deve residir na mesma cidade do evento

- Consultar Eventos
	- Condições
		-	Exibir os eventos com a data mais próxima primeiro e informar eventos ocorrendo no momento

- Confirmar participação
	- Condições
		- O usuário não pode já esta cadastrado em um evento para o mesmo horário
		- O Usuário não pode já esta cadastrado nesse mesmo evento


- Cancelar Participação
	- Condições
		- O evento não deve ter passado ainda
		- O Usuário precisa ter confirmado a participação

- Escrever eventos no arquivo

- Ler eventos do arquivo
	- Execuções
		- Quando a aplicação iniciar