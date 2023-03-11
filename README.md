# Bem vindo à DEVinHouse <img width="180px" alt="Philips" src="ExerciciosM02S06/images/logo-phil.png"/>
## Módulo 02 - Semana 06

Eu desenvolvi uma modelagem conceitual de dados através de diagramas para a elaboração dos 10 exercícios referentes a essa semana. <br>

Para visualizar o meu projeto, <a href="https://github.com/GeorgeEnriqueBravo/DEVinHouse-Modulo02-Semana06/archive/refs/heads/main.zip" target="_blank">
    clique aqui
</a>
para baixa-lo. <br>

Após o download, descompacte o arquivo baixado e abra em seu navegador o site `https://app.diagrams.net/` e escolha a opção de "Abrir diagrama existente". Depois selecione o arquivo "ExerciciosM02S06.drawio" localizado dentro da pasta "ExerciciosM02S06" que foi descompactada no arquivo baixado.
  
---

# Lista de exercícios <img width="75px" alt="Philips" src="ExerciciosM02S06/images/lista.png"/>
### [M2S06] Ex 1 - Gerenciamento Loja

Vamos criar um sistema para o gerenciamento de uma Loja, cada exercício a seguir é parte do desenvolvimento do modelo conceitual desse sistema.

A loja deve ter vários produtos, cada produto tem um código que deve identificar o produto. Todos os produtos devem ter preço. O produto também deve possibilitar a entrada de um nome para o produto.

### [M2S06] Ex 2 - Funcionarios

O sistema também deve ter uma forma de guardar os funcionários, esses devem ter o nome, um identificador, salário base, e o CPF desse funcionário.

Lembrando que o campo salário deve ser numérico com 8 casas de unidade e 2 casas decimais.

### [M2S06] Ex 3 - Clientes Fidelizados

Devemos guardar os clientes fidelizados, esses também devem ter um nome, um identificador, data de nascimento, tempo de fidelização, bônus de fidelidade.

Ele também deve ter o nível de fidelidade:

- Normal
- Gold
- Platinum
- Black
- Infinity

Essa fidelidade deve ser uma entidade separada com um id e o nome da fidelidade.

### [M2S06] Ex 4 - Relacionamentos

Vamos adicionar uma chave estrangeira de vendendor em produto. Nesse relacionamento devemos ter uma classes de Venda, que irá receber o id do produto e do vendedor e a quantidade de produtos vendidos.

### [M2S06] Ex 5 - Endereço Cliente

Vamos adicionar mais detalhes ao cliente fidelizado, adicione as informações de endereço a entidade de Cliente Fidelizado. Devemos ter a informação do logradouro do cliente, numero, estado e cidade.

### [M2S06] Ex 6 - Normalização Cliente

Realizar a normalização na classe de Cliente. - Devemos ter uma entidade Endereço após a normalização.

### [M2S06] Ex 7 - Gerente

Crie agora uma entidade Loja e uma Entidade Gerente

- A Loja deve receber um gerente e agora os funcionários vão ter a FK da Loja.
- O Gerente deve herdar do Funcionário e deve ter um valor de bonus como atributo, esse bonus é por vendas realizadas no mês, por exemplo: 1000.

### [M2S06] Ex 8 - Defina as Formas Normais

Defina as primeiras 3 formas de normalização, com exemplos.

### [[M2S06] Ex 9 - Defina modelo conceitual

Defina modelagem conceitual de dados.

### [M2S06] Ex 10 - Tipos de bancos de dados e SGBDs

Quais são os tipos de bancos de dados e defina quais são os SGBDs.

---

# O que é DEVinHouse?
DEVinhouse é uma jornada de aceleração da carreira com: grade curricular direcionada, professores do mercado, prática constante, interação frequente com as houses parceiras de cada turma, simulação do dia-a-dia DEV e vagas exclusivas que são abertas pelas Houses durante a jornada.

No DEVinHouse você vira um desenvolvedor Fullstack em 9 meses, ao longo de 900 horas de conteúdo, divididas em três módulos de 3 meses cada, com intervalo de uma semana entre cada um. Aproximadamente 25 horas de dedicação por semana entre aulas, atividades e vivências.

__1º módulo:__ Front-End – JavaScript e Angular <br/>
__2º módulo:__ Back-End – Java, Spring e SQL <br/>
__3º módulo:__ Full-Stack – Scrum, DevOps, Clean Code e Design Patterns <br/>
__Ferramentas__ – GitHub, Trello e Slack

---

# Tecnologias Utilizadas <img width="35px" alt="🌐" src="ExerciciosM02S06/images/tag.gif"/>
Nos exercícios dessa semana foram utilizadas as seguintes tecnologias:
<div style="display: inline_block">
    <img align="center" alt="Oracle" src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=black"/>
    <img align="center" alt="Trello" src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white"/>
    <img align="center" alt="GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
</div>
