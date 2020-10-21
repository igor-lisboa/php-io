# [PHP I/O: Trabalhando com arquivos e streams](https://cursos.alura.com.br/course/php-io-arquivos-streams)

## Aula 1
* Como manipular arquivos com PHP
    * Como abrir um arquivo com fopen
    * Como fechar um arquivo com fclose
    * Como ler uma linha com fgets ou fread
    * Como ler todo o conteúdo com file_get_contents ou file

> php leitor-cursos.php

# Aula 2

* Como escrever em um arquivo com fwrite
* [Os vários modos de abertura de um arquivo em PHP](https://www.php.net/manual/pt_BR/function.fopen.php)
* A utilizar a função file_put_contents junto com a flag FILE_APPEND, para escrever no final de um arquivo

# Aula 3
* Que o PHP trabalha com vários protocolos (através de wrappers) de streams
* Como fazer uma requisição HTTP com o PHP, utilizando file_get_contents (mas também poderia ser com fread, por exemplo)
* Como abrir e ler um arquivo ZIP
* Como utilizar filtros com a função stream_filter_append
* Como criar filtros próprios, estendendo a classe php_user_filter
> php -a

# Aula 4
* Como ler dados do teclado ao utilizar o stream STDIN
* Como escrever na tela como se o console fosse um arquivo, utilizando o STDOUT e STDERR
* Como copiar dados diretamente de um stream para outro, com stream_copy_to_stream, poupando memória

# Aula 5
* Que é possível adicionar informações à leitura (ou escrita) de streams através de contextos
* Que a função responsável para criar contextos é a stream_context_create
* Que cada wrapper de stream possui suas possíveis opções de contexto
    * Em http://, vimos como definir o método, cabeçalhos e conteúdo da requisição
    * Em zip://, nós aprendemos a definir a senha para abrir o arquivo

# Aula 6
* Como trabalhar com arquivos no formato CSV, utilizando as funções fputcsv e fgetcsv
* Como ter acesso aos dados de diretórios, através da função dir, que nos retorna uma instância de Directory
* Como tratar streams como objetos, através da classe SplFileObject
    * SPL significa Standard PHP Library, que é uma coleção de classes interfaces criadas com o propósito de resolver problemas comuns
    * [Você pode conferir mais detalhes sobre a SPL aqui](https://www.php.net/manual/en/book.spl.php)

# Aula 7
* O que são conjunto de caracteres (charsets)
* Quais são os principais charsets utilizados
* O que é e porque aderir ao UTF-8
* Como converter charsets utilizando PHP