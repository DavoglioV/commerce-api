# Dev Log

## Sessão 002 - 07/07/2026
### Objetivo
Construção da estrutura de pastas do projeto. Analise do domínio.
- **Quais atributos um produto deve possuir?**
ID, nome, descrição, preço, categoria, quantidade em estoque, Desconto aplicado
- **Quais atributos uma categoria deve possuir?**
ID, nome, descrição, status

### Desafio de hoje
**Pergunta 1: Explique a diferença entre @entity e @table**
R: Ambos são anotations usadas no spring boot para mapeamento do banco de dados. 
Entity é usado para que o sistema entenda determinada classe como uma entidade. 
Já table, identifica uma tabela logica existente de faot no banco de dados.\
**Pergunta 2: Por que o id normalmente é um Long e não um Integer?**
R: Alem de Integer ser um objeto, Long cabe um número bem maior de itens. \
**Pergunta 3: Qual a diferença entre GenerationType.IDENTITY, GenerationType.SEQUENCE e GenerationType.AUTO?**
R: ID vai grar um numero randomico, Sequence gera uma sequencia numerica logica e auto, o proprio spring boot vai definir quando usar o que. 

### O que aprendi
- Diferença entre Entity e Table. 
- Conceitos de DDD e arquitetura hexagonal.



## Sessão 001 - 06/07/2026
### Objetivo
Construção do projeto spring boot. Criação do repositório no GitHub e configuração do ambiente de desenvolvimento.

### Conceitos estudados
- Spring Initializr
- Group
- Artifact
- Gerenciamento de features com GitHub Projects

### O que aprendi
- Construção e gerenciamento de demandas usando o GitHub Projects
- Revisitei conceitos de Group, Artifact e Packaging do Spring Boot
- Aprendi o conceito por tras da estrutura de pastas no formato br.com.nomedaempresa

### Dificuldades
- Demorei para definir o nome do projeto e do pacote, pois me dediquei a entender o motivo pelo qual é usado a estrutura padrão comum

### Como resolvi
- Neste caso, preferi entender os conceitos usando Google e ChatGPT

### Tempo estudado 
- 2 horas 18 min 