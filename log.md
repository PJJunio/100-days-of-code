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


### Day 4:

**Today's Progress**: Hoje não passei muito tempo codando em si, me reuni com o pessoal para resolver bugs que estavam acontecendo no projeto que tomou quase todo meu tempo, mas não achei ruim, porque eu  aprendi
muita coisa resolvendo esses bugs e inclusive teve muita coisa básica que acabei esquecendo, mas vida que segue, vivendo e aprendendo.

**Thoughts:** Não achei o dia de hoje chato, foi interessante, resolver bugs ajudam no aprendizado também querendo ou não kkkk.

### Day 5:

**Today's Progress**: Bom, o dia de hoje aprendi bastante coisa, terminei o módulo de SpringBoot que já era para ter terminado a bastante tempo mas finalmente terminei, apenas finalizei conceitos de PUT e DELETE na API,
logo logo vou aplicar em um desafio da RoadmapSh, sem spoilers por enquanto, depois disso fui resolver um bug em uma api que estava com credenciais expostas, como não fazia ideia de como eu faria, pesquisei sobre .env,
bati cabeça para aprender e resolver alguns bugs, mas finalmente terminei, só esperar para ver se fiz cagada kkkk.

**Thoughts:** O dia de hoje foi bem agradavel, aprendi muita coisa e fiz bastante coisa, logo logo terei novidades sobre algo novo que consegui, sem muitos spoilers kkkkk.

**Link to work:** [VollMed-API](https://github.com/PJJunio/vollmed-api)

### Day 6:

**Today's Progress**: Olá novamente, hoje não fiz muita coisa por conta que tive que vir para a casa dos meus pais e não tenho notebook, mas antes de sair de casa fiz algumas alterações no código do meu projeto, apenas refatorei e adicionei algumas validações, coisa básica, ainda ficaram coisas pendentes mas vou dar meus pulos para conseguir codar.

**Thoughts:** Vou considerar esse feriado como um desafio para fazer eu manter a streak, vai ser difícil mais vou dar meus pulos, nem que eu precise estudar HTMl, PHP ou qualquer coisa novamente kkkkk.

### Day 7:

**Today's Progress**: Olá novamente, 7° dia em, bom, a log de hoje vai ser curta, como dito na anterior não estou em minha casa e por consequência, não tenho nenhum computador para codar, então foquei em fixar conteúdos, fiquei assistindo aulas de GET, PUT, POST e etc para fixar melhor o conteúdo, sinceramente se eu não conseguir nenhum computador até amanhã, vou ter que brincar com PHP novamente, mundo sóbrio que eu não queria voltar.... brincadeiras da parte kkkk.

**Thoughts:** Bom, o dia não teve muita coisa, preferi ficar com minha família e estudar apenas o necessário para o desafio, simples assim.

### Day 8:

**Today's Progress**: Bom, não consegui um PC e nem me rendi ao PHP, mas me lembrei que tinha um curso de AWS para fazer kkkkk, abri o meu e comecei a assistir as aulas para ver como funcionava, vi apenas as interfaces por enquanto, como funcionava as regiões, locais, capacidade, valores, etc, não me aprofundei muito, enfim, o dia foi apenas isso basicamente, preferi focar mais em aproveitar o feriado e descansar um pouco.

**Thoughts:** Por mais que eu esteja mais ocioso nesse feriado, estou conseguindo dar uma destraida na cabeça e descansar, a próxima semana vai ser cheia querendo ou não kkkkk.

### Day 9:

**Today's Progress**: Olá Olá, bom, hoje não como o esperado, n fiz muita coisa, mas pelo menos revisei alguns repositórios meus, alguns exercícios em PHP e Java e principalmente um comparador de planilhas em Python que eu tinha feito, para ser mais específico, teve uma tarefa que foi dada a mim em meu trabalho que consistia em comparar 2 relatórios de empresas diferentes e ver se as contas batiam, nossa empresa oferece serviços e a outra é uma terceirizada que contratamos, basicamente o programa lê as 2 planilhas e compara ambas, se o valor da célula for igual, vai pintar ela de amarelo, todos os resultados são salvos em uma nova planilha.

**Thoughts:** Bom, pretendo ir para casa amanhã mesmo, então vou poder voltar a programar normalmente kkkkk, um dia o descanso tem que acabar né, enfim, dia tranquilo sem muita coisa.

**Link to work:** [Comparador de Planilhas](https://github.com/PJJunio/comparador-de-planilhas)

### Day 10:

**Today's Progress**: Olha e aqui, hoje fiz bastante coisa, iniciei um projetinho pessoal de uma api que gerencia gastos, estudei um pouco mais sobre JWT e dei uma fixada em alguns conteúdos que eu estava achando meio fraco, não foi muita coisa, mas comparado com o feriado, ta mais do que bom.

**Thoughts:** Bom, eu meio que furei um dia, mas foi mais porque eu esqueci de postar mesmo kkkk, eu fui dormir achandoq que eu já tinha postado a log diaria e acabei não postando, mas infelizmente acabei furando 1 dia, entao, vamos adicionar mais um dia ao contador, ao inves de 100 vão ser 101 agora kkkk, enfim, até amanã com outra log.

### Day 11:

**Today's Progress**: Olá, hoje eu fiquei praticando um pouco de .env, ver como funciona e como usar, ainda não entendi muito bem mas ainda estou na luta, amanhã pretendo deixar isso um pouco de lado e me aprofundar em JWT e Spring Security, estou precisando mesmo reforçar essas matérias.

**Thoughts:** Bom, hoje não teve muita coisa,  dia acabou sendo corrido e eu não estava me sentindo muito bem depois de uma viagem para fazer alguns atendimentos, não foi longa mas a estrada tinha muitas curvas e acabei ficando muito enjoado.

### Day 12:

**Today's Progress**: Vou resumir porque já está muito atrasado, hoje eu dei uma estudada sobre retorno de requisições e dei uma alterada em um código para estudos que eu tenho, depois disso comecei a tentar resolver um problema que eu estava tendo com uma .env que o flyway não queria ler as variáveis de ambiente, consegui resolver antes das 00.

**Thoughts:** Escrevi essa log correndo então tá muito resumido, acabei perdendo a noção do tempo resolvendo o problema kkkk

### Day 13:

**Today's Progress**: Olá novamente, hoje eu fiquei em um projeto pessoal de um app de controle financeiro, fiz as variaveis, dtos e repositories para adiantar e amanha ja pretendo fazer os endpoints da api, aprendi sobre migrations do flyway porque eu ainda estava com algumas duvidas e resumidamente foi isso.

**Thoughts:** O dia foi bem interessante, fiz alguns commits, pull requests e etc junto com bastante codigo, estou gostando de como esta ficando a minha api pessoal.

### Day 14:

**Today's Progress**: Hoje tirei algumas duvidas de como relacionar duas tabelas do banco de dados, mas não me aprofundei, codei um pouco na minha API privada para não perder o costume e fui distrair a cabeça.

**Thoughts:** Hoje não fiz muita coisa, tive que fazer atendimentos no meu trabalho das 11 às 20, os locais eram roças então demorava um pouco para chegar, bom, amanha tô com o dia livre.

### Day 15:

**Today's Progress**: Hoje eu dei continuidade a minha API pessoal, aprendi a relacionar uma tabela a outra por meio de uma chave estrangeira, consegui implementar o que eu queria em minha API, ainda estou trabalhando nela mas logo logo acredito que vou finalizar e quando eu terminar vou voltar a estudar sobre segurança.

**Thoughts:** Bom, o dia de hoje foi interessante, consegui aprender bastante coisa e colocar me pratica, mas preciso treinar para fixar esse conhecimento.


### Day 16:

**Today's Progress**: Bom, eu sei que eu não postei nada ontem, mas foi porque caiu um temporal aqui em casa e acabou entrando agua, mas enfim, +1 no contador de dias, enfim, o dia de hoje foi bem legal, não tive quase nada de codigo mas eu finalmente iniciei meu curso de DesenvolvimentoWeb, bom, hoje foi a primeira aula, o professor falou sobre coisas básicas nessa primeira aula, apenas sobre o que é a internet, sua historia e etc, e finalmente consegui um notebook, os organizadores do curso disponibilizaram para fazer as aulas, então, sem mais desculpas para furar quando não estou em casa kkkk.

**Thoughts:** O dia foi legal, conheci um pessoal novo e inturmei com os professores e cordenadores do curso, acredito que dei uma boa primeira impressão para eles, estou ansioso para a proxima aula que vai ser sexta-feira (02/05/25), vamos falar sobre algoritimos.

### Day 17:

**Today's Progress**: Hoje eu estudei sobre SpringSecurity, como funciona, funções e etc, mas acabei me envolvendo um bug quando fui implementar o UUID externo em meu projeto, fiquei em torno de 2 horas resolvendo esse problema, mas consegui absorver muita coisa com isso.

**Thoughts:** A intenção hoje era focar 100% em spring security e JWT, mas acabei me envolvendo em uma coisa totalmente diferente kkkk, mas deu certo, não me arrependo do resultado final.

### Day 18:

**Today's Progress**: Tirei o dia de hoje para para implementar algumas coisas no código, arrumar alguns endpoints, revisar algumas coisas e assistir algumas vídeo aulas, não me aprofundei muito, preferi descansar e ficar tranquilo.

**Thoughts:** Decidi tirar o dia para descansar mesmo, dormir e ficar tranquilo, fazer afazeres de casa e etc, não fiz muita coisa mas amanhã tenho muita coisa para fazer kkkkk.

### Day 19:

**Today's Progress**: Hoje não teve muito código, para falar a verdade nesse exato momento eu estou codando, mas não vem muito ao caso, hoje foi mais um dia do meu curso, como todo inicio foi bem básco, explicaram o que é lógica de programação, algoritimos, linguagens de alto e baixo nivel, etc, coisas bem básicas mesmo, foi interessante rever esses conceitos novamente para fixar um pouco mais o conhecimento.

**Thoughts:** O dia foi bem tranquilo, sem muitas complicações, conteúdos simples e etc, espero que dê uma animada mais para frente kkk.

### Day 19:

**Today's Progress**: Hoje dei uma estudada básica apenas, por conta do curso eu revisei um pouco de algoritimos e web,sem muitas coisas complicadas, preferi descansar e aproveitar o final de semana.

**Thoughts:** Mas no final de tudo, quem disse que vou dormir agora? kkkk vou estudar python para um projeto, bom, vejo vocês amanhã.

### Day 20:

**Today's Progress**: Dia 20 em, finalmente, bom, tive a notícia que vamos mudar o projeto para Python e não estou triste por isso, e sim feliz porque Python e muito mais fácil, por mais que eu ache mais sem graça que o Java, enfim, hoje eu fui ver como o Python funcionava, variáveis, funções, POO, etc. Eu já tinha uma noção de como era o Python porque eu já fiz algumas coisas nessa linguagem, então foi bem tranquilo, bom, acredito que vai dar tudo certo.

**Thoughts:** Olha, quem diria, dia 20 já, enfim, depois de muito tempo usando apenas PC de mesa, vi finalmente a praticidade de usar um notebook, fui para a casa dos meus pais esse final de semana e coloquei ele na mochila para dar uma estudada na casa deles, e como foi? Ótimo, eu fui para uma bancada na área de churrasco da casa deles e fiquei bem tranquilo la codando e assistindo aulas, a experiência foi ótima e com certeza vou repetir mais vezes.

### Day 21:

**Today's Progress**: Hoje foi dia de curso, como sempre fui para a outra cidade participar, na aula de hoje ensinaram lógica de programação com portugol, o básico de sempre, mas o professor já falou para pesquisarmos por fora pois iriamos ficar mais avançados nas proximas aulas, usando linguagens mesmo, bom, por mais que esteja básico agora, o ritimo do curso está bem acelerado então acredito que logo logo vou estar fazendo alguns projetos legais.

**Thoughts:** Hoje foi bem legal, interagi com o pessoal que senta ao meu lado e dei algumas sugestões para as atividades deles, batemos um papo e etc..

### Day 22:

**Today's Progress**: Hoje eu aprofundei mais em FastAPI, vi sobre Union e Opitional, achei essas funcionalidades bem interessantes para projetos futuros, também ví sobre a importância de como mostrar o codigo após a requisição é essencial para uma melhor visualização e organização da API.

**Thoughts:** Hoje estudei bastante, mas acredito que dava para revisar mais conteúos e fixar alguns, amanhã é mais uma aula do curso, de acordo com o prof vamos mexer com github, ensinar o básico da plataforma, pelo rítimo do curso eu acredito que não vá demorar para as coisas esquentarem e ficarem interessantes.
