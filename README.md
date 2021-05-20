# POO

Esse Repositorio tem o Objetivo de Qualificar as Habilidades restritas à POO. Isso
se dá pela resolução do seguinte Problema

# The Problem

Imagine que voce tem que construir o codigo base para um Banco com os Seguintes requisitos:

- Um Banco possui um Nome, Endereço, Numero total de clientes, total de depositos ( montante do saldo acumulado de todos os clientes do banco), agencia e um numero limitado de contas correntes (10)
- Um Cliente possui (Nome, Endereço, Idade, Data de Nascimento) - Alem disso um cliente possui uma conta corrente com saldo e agencia  
- Endereço  composto por: Logradouro, Numero, Cep e Bairro

O Sitema Proposto deve obrigatoriamente realizar as seguinte operações:
 - Cadastrar Novos Clientes ( não mais que 10 )
 - Clientes podem acessar sua conta ( inserindo agencia, conta e senha )
 - um Cliente pode consultar saldo e realizar tranferencias (se houver saldo disponivel)
 - O Sistema deve mostrar sempre o total de clientes e o montante do saldo acumulado de todos os clientes do banco
