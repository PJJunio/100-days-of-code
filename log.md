# 100 Days Of Code - Log - started on the 10-04-25

### Day 0:


**Today's Progress**: 

* *19:50:* Hoje dei continuidade a minhas aulas no curso da Alura e desenvolvi o básico e uma API de controle de consultório médico, fiz apenas a parte de cadastro de paciente e médico
utilizando DTOs, DAOs, e interfaces em meu projeto, atualmente estou utilizando SpringBoot e MySQL, com frameworks como Lombok e Flyway para criar os getter, setters, constructors, etc e as
migrations do projeto.

**Thoughts:** De primeira achei meio complexo, mas a medida que eu ia fazendo e tirando dúvidas na aula comecei a ficar mais tranquilo e achar mais fácil, tinha muitas dúvidas de como separar os Controllers,
DTOs, Repository, etc, mas tirei bastante dúvidas até o momento.

**Link to work:** [VollMed-API](https://github.com/PJJunio/vollmed-api)

### Day 1:

**Today's Progress**: 

* *23:30:* Bom, atrasei hoje mais estamos aqui, hoje eu aprendi a usar o Bean Validation para validar alguns dados como campos obrigatórios e email, fiz tambem meu primeiro método GET que lista todos os médicos
do banco de dados, hoje foi bem curto mas pelo menos codei o suficiente e aprendi bastante.

**Thoughts:** Bom, eu fiquei meio com medo de como eu ia validar os dados mas depois que usei o Bean Validation eu achei a coisa mais facil do mundo, essa ferramenta ajuda muito hoje em dia, sobre as listas eu
já tinha ideia de como seria, por exemplo criar o DTO para mostrar apenas os dados que eu quero mas eu não fazia ideia que o Jpa tinha um método só para isso.

**Link to work:** [VollMed-API](https://github.com/PJJunio/vollmed-api)

### Day 2:

**Today's Progress**: Bom hoje não teve muito código, estou na casa do meu amigo usando um notebook emprestado para fazer a aula de hoje. Não teve muito código, apenas fiz alguns testes com a função pageble do JPA, adicionando o pageble a classe que faz as listagens e declarando ela com um nome escolhido, podemos mudar também o método list para page, já que queremos que receba do front uma requisição para mostrar dados de uma página especifica. Com algumas módificações no return do método, para que o findall para mostar os dados do método paginação (nome definido por mim para o método pageble) e removendo o strem pois o find all já retorna o page e o método page já tem o método map diretamente nele e nem o tolist pois já converte automaticamente.
No caso do Backend, se especificarmos no método GET em frente a url ?size=1&page=2, ele vai mostar 1 registro da página 2 do banco de dados. 

**Thoughts:** Bom, foi bem no limite mas estamos aqui, amanhã vou tentar codar um pouco mais para compensar, ou se duvidar entro na madrugada para brincar um pouco em alguns projetos kkkkk.

**Link to work:** [VollMed-API](https://github.com/PJJunio/vollmed-api)

### Day 3:

**Today's Progress**: Hoje no momento que cheguei em casa fui terminar o módulo de GET do curso de Spring, aprendemos como podemos mostrar dados de páginas especificas fazendo uma optimização do código e mostrando
apenas dados importantes e relevantes para a atual situação, foi utilizado a classe Pageable para essa atividade, apenas chamando essa classe na urlcom "http://localhost8080/medicos?sort=crm,desc&size=2&page=1"
ele vai filtrar pelo CRM do médico, mostrar apenas 10 tabelas da página 1, mas claro que podemos personalizar que para caso for chamado sem nenhuma especificação, mostrar dados específicos, utilizando a tag
@PageableDefault(size = 10, sort = {"nome"} dentro da classe criada, como mostrado no exemplo, podemos personalizar esses dados.

**Thoughts:** Bom, hoje encerrei o modulo de GET, amanhã vou adiantar o sobre DELETE e PUT que eu já deveria ter terminado, até o momento SpringBoot está sendo bem facil e estou conseguindo me adaptar bem,
logo logo vou aplicar em projetos meus.

**Link to work:** [VollMed-API](https://github.com/PJJunio/vollmed-api)
