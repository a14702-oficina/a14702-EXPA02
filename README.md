# **INTRODUÇÃO**

Declaração de funções


 # **CONTEÚDOS**
Para declarar uma função em Python, precisamos conhecer quatro coisas: a palavra-chave def, o nome da função, a lista de parâmetros e o corpo (bloco de comandos).

![image](https://github.com/user-attachments/assets/dede3d39-7477-4b34-90ec-c829241b1aee)


# DECLARAÇÃO SEM PARÂMETROS 

    def exibirMensagem():

     print("Python é fácil")
     
    exibirMensagem()

    exibirMensagem()

    exibirMensagem()


# DECLARAÇÃO COM PARÂMETROS
def exibirMensagemBoasVindas(pessoa, mensagem):
	print(f"{mensagem}, {pessoa}")

exibirMensagemBoasVindas(mensagem = "Bom dia", pessoa = "Ana")
#Saída: Bom dia, Ana




# EXERCÍCIO RESOLVIDO

Desenvolver uma função que leia os valores de uma lista os some e apresente
def somarElementosLista(inteiros):

    	soma = 0
 
   	for valor in inteiros:
 
  	soma = soma + valor
  
	return soma

    print(somarElementosLista([3,4,6,9,10,23,13])) #Resultado 68









