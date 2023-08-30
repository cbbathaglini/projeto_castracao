# Projeto Castração
Sistema desenvolvido em Java, Spring e Hibernate que simula uma clínica pública de castração de animais

1) Desenvolver o diagrama de classes
2) Desenvolver o diagrama de casos de uso
3) Desenvolver o diagrama de entidade relacionamento

:bangbang: Importante :bangbang:
- Lembre de desenvolver com Clean Code
- utilize ao menos um desing pattern
- lembre do SOLID
- Utilize herança

<h1>Informações de cadastro</h1>
<h3>Pessoal da saúde:</h3>
- CPF <br>
- nome<br>
- email<br>
- senha<br>
<h3>Veterinário</h3>
- CPF<br>
- CRMV<br>
- nome<br>
- email<br>
- senha<br>
<h3>Dono(a):</h3>
- nome<br>
- CPF (para logar)
- RG<br>
- NIS <br>
- SUS<br>
- email (opcional)<br>
- senha<br>
<h3>Animal</h3>
- nome<br>
- porte<br>
- raça<br>
- sexo<br>
- data de nascimento (opcional)<br>
- personalidade: MANSO, ARISCO, AGRESSIVO<br>
<br>
<h2>Casos de Uso</h2>
<h3> dono do animal (usuário): </h3>
- cadastrar novos animais<br>
- visualizar agenda das castrações<br>
- visualizar a lista de receitas (medicação) de cada castração<br>
- visualizar a lista de castrações (nome veterinario, CRV, data) <br>
  <br>
  
<h3> Pessoal da saúde (usuário)</h3>
- visualizar agenda<br>
- marcar castração<br>
- cancelar cadastração<br>
- reagendar castração<br>
- listar todas as castrações (filhotes (18 meses), por dono, por raça, por veterinario, etc)<br>
- anexar termo de responsabilidade (envia um email pro dono)<br>

<h3> Veterinario responsavel</h3>
- receitar os medicamentos <br>


 
 <H3>Posteriormente:</H3>
 
 -- splunk
 -- appdynamics 
 -- login (spring security) - posterior
 
 
