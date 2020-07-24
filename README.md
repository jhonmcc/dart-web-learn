# dart-web-learn
* Este é um resumo sobre a utilização da linguagem de programação Dart em conjunto com html e css na construção de páginas web inclusive um SPA (Single Page Application)
* Caso tenha cometido algum erro ou equivoco e/ou queira contribuir com o resumo manda a sua pull request :) ou faz um fork o importante é espalhar a palavra.

- Instalação <br>
Há algumas formas para instalar o dart você poderá conferi-las no link abaixo<br>
https://dart.dev/get-dart#install

- Para este resumo foi realizado a instalação seguindo os passos a seguir:

* Dart SDK archive 
    - acesse o link abaixo e siga as instruções esta instalação foi realizada em uma maquina Windows 10<br>
    https://dart.dev/tools/sdk/archive
    - na tabela selecione 32 bits ou 64 bits e click no link Dart SDK para baixar o zip
    - atente-se as versões recomenda-se baixar uma versão estable na página também esta disponível as versões beta das releases do dart.

    - crie uma pasta src no seu disco local C:\ recomenda-se este diretorio para não ter problemas de permissão de usuário.<br>
    esperado >>> C:\src
    - copie ou recorte o arquivo zip baixado descompacte ele dentro do diretorio C:\src<br>
    esperado >>> C:\src\dart-sdk

    - próximo passo abra as configurações das variaveis de ambiente e selecione a opção path do usuario 
    - insira um novo registro conforme o exemplo abaixo<br>
    C:\src\dart-sdk\bin
    - salve as modificações agora é hora de testar a instalação
    - abra algum terminal da sua prefencia cmd, powershell
    - insira o comando a seguir dart --version<br>
    esperado >>> informações da versão do SDK instalado 

* Hello world! - Dart
    - abra o seu editor de texto pode ser o vscode ou algum da sua preferença crie um diretorio para armazenar seus arquivos e dentro do diretorio crie o arquivo hello.dart<br>
    Caso venha a utilizar o vscode é possível utilizar extensões que irão nos ajudar durante o desenvolvimento,<br> inclusive para gerenciar os nossos arquivos via terminal pois ele já tem o mesmo embutido.
    - após criar o arquivo hello.dart veja o código de referencia do arquivo 1-hello.dart neste mesmo diretório.<br>1-hello.dart
    - para rodar o arquivo abra o terminal e entre no diretorio do arquivo <br>
    execute o comando dart 1-hello.dart <br>
    esperado >>> mensagem no console ex: hello world!!!

* Compilando o arquivo dart para javascript
    - por padrão o browser não aceita dart então teremos que fazer a conversão dele para javascript
    - utilizando o arquivo 1-hello.dart como exemplo faremos a conversão dele para o js utilizando o comando abaixo<br>
    - dart2js -o nomeArquivoConvertido.js nomeArquivoDart.dart
    - é possíve utilizar -o > gera saida js -m > gera uma saida minificada -h Apresentar uma msg mensagem

* Dart linha de comando
    - ...

* Identificadores dart
    - Identificadores validos: firstName, first_name, num1, $result
    - Identificadores invalidos: Var, first name, first-name, 1num

* Palavras chave - Keywords
    - anexar imagem

* Dart sintaxe
    - variaveis e operadores
    - classes
    - functions
    - expressoes e contrutores
    - condições e loop's 
    - comentarios 
    - libs e pacotes
    - typedefs 
    - estrutura de dados representando coleções / genericas

* Dart é Case-Sensitive
    - ...

* Dart Comentarios 
    - utilize // para linhas simples 
    - utilize /* ... */ para mutliplas linhas

* Dart é Orientado a Objeto 
    - é isso mesmo orientado a objeto rs

* Dart variaveis - tipos de dados
    - ver o arquivo 2-type-vars.dart




    
