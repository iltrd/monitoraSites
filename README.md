# Monitor de Sites

A aplicação inicia mostrando a introdução, dando boas vindas e informando a versão da aplicação que está sendo utilizada, logo após, é exibido o menu de opções, onde podemos escolher entre 3 opções: 1 - iniciar monitoramento, 2 - exibir logs, 3 - sair do programa. Ao selecionar a opção desejada é informado o comando escolhido e inicia a função. 

Caso tenha escolhido o comando 1
É iniciado o monitoramento. Ele testa site por site,  informando o site específico que carregou corretamente ou se identificou algum erro. 

OBS: Temos um arquivo já com sites que podemos testar e fazer o monitoramento. 

Caso tenha escolhido o camando 2
É iniciado o comando de exibir os logs. Caso seja a primeira execução do comando, ele automaticamente cria um arquivo “log.txt” e grava e exibe os logs que foram rodados acima, informando a data, hora, site que foi monitorado e o status dizendo se o site está online ou não. 


A aplicação tem a função de monitorar e exibir logs. Os sites por enquanto são informados por um arquivo .txt. Utilizando pacotes como: net/http que tem a funcionalidade de acessar a internet, de fazer requisições através da linguagem. io/ioutil utilizado para gravar conteúdo no arquivo, utilizando o método ioutil.ReadFile() para retornar os dados do arquivo ou um erro que é o nosso caso. strconv e strings utilizado para formatar dados que será exibido e gravado no logs com data, hora e para fazer a conversão de booleano para string. 
