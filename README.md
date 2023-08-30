# Projeto Castração
Sistema desenvolvido em Java, Spring e Hibernate que simula uma clínica pública de castração de animais

<h1>Informações de cadastro</h1>
<h3>Pessoal da saúde:</h3>
- CPF
- nome
- email
- senha
<h3>Veterinário</h3>
- CPF
- CRMV
- nome
- email
- senha
<h3>Dono(a):</h3>
- nome
- CPF (para logar)
- RG
- NIS 
- SUS
- email (opcional)
- senha
<h3>Animal</h3>
- nome
- porte
- raça
- sexo
- data de nascimento (opcional)
- personalidade: MANSO, ARISCO, AGRESSIVO

<h2>Casos de Uso</h2>
<h3> dono do animal (usuário): </h3>
- cadastrar novos animais
- visualizar agenda das castrações
- visualizar a lista de receitas (medicação) de cada castração
- visualizar a lista de castrações (nome veterinario, CRV, data) 
  
  
<h3> Pessoal da saúde (usuário)</h3>
- visualizar agenda
- marcar castração
- cancelar cadastração
- reagendar castração
- listar todas as castrações (filhotes (18 meses), por dono, por raça, por veterinario, etc)
- anexar termo de responsabilidade (envia um email pro dono)

<h3> Veterinario responsavel</h3>
- receitar os medicamentos
 
 <H3>Posteriormente:</H3>
 
 -- splunk
 -- appdynamics 
 -- login (spring security) - posterior
 
 
