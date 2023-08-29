# Linguagem: Python

## Explicação

Pasta para códigos e exemplos da linguagem de programação Python. Dentro dela, você encontrará subpastas chamadas: *codigos*, a qual deve ser manualmente criada, na qual você deverá armazenar seus códigos; *exemplos*, onde estão disponíveis diversos exemplos de como funciona a linguagem, os quais também podem ser utilizado para testar se os métodos de criação de arquivos executáveis está funcionando; *.vscode*, na qual está armazenado os arquivos que o programa Visual Studio Code utiliza para configurar o projeto corretamente.

## Instalação

1. Verifique se o Python está instalado em sua máquina com o comando `python --version` no terminal. Caso esteja, já está tudo pronto! Caso contrario, prossiga para o proximo passo;
2. Baixe-o em [https://www.python.org/downloads/](https://www.python.org/downloads/) ou instale-o via gerenciador de pacotes da sua distribuição Linux;
3. Adicione o Python ao PATH do seu sistema operacional, para que o terminal possa reconhecer o comando `python` e `pip`;
4. Instale as extensões recomendadas para Python no Visual Studio Code, caso esteja utilizando-o;
5. Pronto! Agora você pode utilizar o Python em seu terminal e no Visual Studio Code.

## Como usar

Caso esteja utilizando a IDE chamada Visual Studio Code, simplesmente abra esta pasta chamada ***Python*** no programa e comece a programar! Quando necessitar compilar e testar seu programa, na parte esquerda, vá na aba de *Run and Debug* (acessível também pela combinação Ctrl+Shift+D) e selecione o tipo de tarefa que quer executar¹ e clique no botão verde. Nas vezes subsequentes, basta estar com o arquivo aberto e apertar *F5* que a tarefa deve executar automaticamente.

¹ O grupo PET Computação já deixou uma pré-pronta que deve funcionar na maioria dos casos.

## Cadeiras Aplicáveis

* Classificação e Pesquisa de Dados - INF01124
* Inteligência Artificial - INF01048

## Como Modificar

Para modificar a maneira na qual o programa VSCode realiza o processo de compilação e debug do seu código é necessário modificar os conteúdos da pasta .vscode. Lá dentro, estão 4  arquivos que modificam as propriedades da area de trabalho atual.

* *extensions.json:* armazena as extensões recomendadas;
* *settings.json:* armazena configurações especificas para esta pasta;
* *launch.json:* armazena o os processos que devem ser executados na aba de *Run and Debug*, para executar o processo de depuração com argumentos de linha de comando, basta adiciona-los ao item `"args"` do arquivo;

## Links de referencia

* [https://docs.python.org/3/tutorial/index.html](https://docs.python.org/3/tutorial/index.html) - Tutorial da Linguagem Python [EN/PT]
* [https://docs.python.org/3/index.html](https://docs.python.org/3/index.html) - Guia de referencia da Linguagem Python [EN/PT]
* [https://www.w3schools.com/python/](https://www.w3schools.com/python/) - Guia da W3Schools de Python [EN]
* [Intro à Programação em Python](https://www.youtube.com/watch?v=5x_IveLQ-UE&list=PLtwdb83BFgnIeG9aPlfMhNUYIFSZ_GBYz) - Playlist produzida pelo Prof. Dennis Giovani do INF UFRGS [PT]
