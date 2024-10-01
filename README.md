## 1. Estrutura Geral do Projeto
O programa é dividido em várias funções que têm responsabilidades bem definidas:

- exibeIntroducao(): Exibe uma introdução básica com o nome do usuário e a versão do programa.
- exibeMenu(): Mostra o menu com as opções disponíveis para o usuário.
- leComando(): Lê o comando digitado pelo usuário.
- iniciarMonitoramento(): Realiza o monitoramento dos sites especificados em um arquivo de texto.
- testaSite(): Faz uma requisição HTTP GET para verificar se o site está online e registra o resultado no log.
- leSitesDoArquivo(): Lê a lista de sites a serem monitorados de um arquivo chamado sites.txt.
- registraLog(): Grava o resultado do monitoramento em um arquivo de log logs.txt.
- imprimeLogs(): Exibe o conteúdo do arquivo de logs.
## 2. Requisitos
- Arquivo sites.txt: Um arquivo de texto onde cada linha contém a URL de um site a ser monitorado.
- Arquivo logs.txt: Um arquivo gerado pelo programa, onde são registrados os resultados do monitoramento.
## 3. Funcionalidades
- Monitoramento: O programa testa os sites por um número definido de vezes (motiramentos, fixado como 3) e em intervalos de tempo (delay, fixado em 5 segundos).
- Logs: Os resultados (se o site está online ou offline) são registrados em logs.txt, com a data e hora do monitoramento.
## 4. Como Usar
- No terminal ultilize o comando -> `go run hello.go`
- Este comando vai iniciar o programa.
- Prepare o arquivo sites.txt: Crie um arquivo chamado sites.txt no mesmo diretório do programa e adicione as URLs dos sites a serem monitorados, uma por linha.

- Execute o programa: Ao iniciar, o programa mostrará o menu com opções para iniciar o monitoramento, exibir os logs ou sair do programa.

- Monitorar sites: Escolha a opção 1 no menu para iniciar o monitoramento dos sites listados no arquivo. O programa testará cada site e registrará os resultados.

- Exibir logs: Após o monitoramento, escolha a opção 2 para visualizar os logs gravados no arquivo logs.txt.

- Finalizar: Escolha a opção 0 para sair do programa.
