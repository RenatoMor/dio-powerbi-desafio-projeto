## Desafio de Projeto - Processando e Transformando Dados no Power BI

### Santander Bootcamp 2023 - Ciência de Dados com Python

<h3>Conecte-se!</h3>

<a href="https://web.dio.me/users/renato_moreira?tab=skills" target="_blank"> <img align="center" alt="" height="40" width="110" src="https://hermes.digitalinnovation.one/users/company/3a52d6e3-a58c-4755-89c9-fbc093a8868f.png"></a>
<a href="https://www.instagram.com/piano_tato/" target="_blank"> <img align="center" alt="" height="40" width="40" src="https://img.icons8.com/?size=1x&id=nj0Uj45LGUYh&format=png"></a>
<a href="https://www.facebook.com/renato.moreira.908/" target="_blank"> <img align="center" alt="" height="40" width="40" src="https://img.icons8.com/?size=1x&id=jZ0kw76QEzJU&format=png"></a>
<a href="https://www.linkedin.com/in/renatomoreira-rm//" target="_blank"> <img align="center" alt="" height="40" width="40" src="https://img.icons8.com/?size=1x&id=MR3dZdlA53te&format=png"></a>

"Este projeto teve seu início como parte de um desafio apresentado durante o curso **Santander Bootcamp 2023 - Ciência de Dados com Python**, oferecido na plataforma de ensino DIO. Nesse desafio, fui incumbido de criar uma instância de banco de dados MySQL no ambiente Azure e, posteriormente, integrá-la ao Power BI, além de realizar o tratamento dos dados envolvidos."

## :bookmark_tabs: Descrição do Projeto

1. Mesclagem das tabelas departament e dept_location: 
Realizar uma junção das tabelas departament e dept_location, concatenando as colunas de nome do departamento e localização para criar uma coluna única que representa cada departamento-local.

2. Mesclagem das tabelas employee e departament: 
Junção as tabelas employee e departament, associando o nome dos departamentos aos colaboradores.

3. Junção de colaboradores e gerentes: 
Combinação das tabelas de colaboradores e seus respectivos gerentes, mesclando as colunas de nome e sobrenome de cada colaborador e gerente.

4. Alteração do tipo de dados para valores monetários: 
Conversão da coluna "Salary" (Salário) na tabela employee para o tipo de dados double preciso, garantindo maior precisão nos valores monetários.

5. Separação da coluna complexa "Address" (Endereço): Divisão da coluna complexa "Address" na tabela employee, separando os dados por delimitador em "Number" (Número), "State" (Estado), "City" (Cidade) e "FU" (Federal Unit/Unidade Federativa).

## 	:computer: Tecnologias Utilizadas
```bash	
- Azure - plataforma de nuvem que possibilitou criar um banco de dados MySQL na nuvem
- Power BI - ferramenta de avaliação e visualização de dados da qual utilizamos para fazer a transformação de limpeza dos dados
- MySQL - sistema de gerenciamento de banco de dados usado, que utiliza a linguagem SQL como interface.
```	



## :books: Explicação
**Mesclar consultas em vez de combinar consultas nos cenários mencionados?**

A 'mescla de consultas' é escolhida quando nosso objetivo é unir as colunas de diferentes tabelas, ou seja, quando estamos trabalhando com uma abordagem mais orientada a colunas. Por outro lado, a 'combinação de consultas' é utilizada para unificar apenas as linhas das tabelas, ou seja, quando estamos focando em uma abordagem mais orientada a linhas."


## License
[MIT](https://choosealicense.com/licenses/mit/)