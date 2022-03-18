# Hello World no JCL utilizando o IEBGENER #

  O [utilitário IEBGENER](https://www.ibm.com/docs/en/zos-basic-skills?topic=utilities-iebgener-utility-generate-copy-sequential-data-set) do JCL é utilizado para copiar datasets ou outros conjuntos de dados de uma entrada `SYSUT1` para uma saída `SYSUT2`. 
  
  No arquivo aqui presente, o objetivo é o de realizar o famoso "Hello, World!" utilizando a linguagem JCL e o seu utilitário `IEBGENER`.
  
  Após realizar o `SUBMIT` no JOB, o print do 'Hello, World' pode ser visualizado por meio do comando `TSO SDSF`, ele redirecionará para um painel com várias ferramentas, para acessar o SDSF basta digitar `ST`, esse, por sua vez, é uma ferramenta que oferece os logs com erros e mensagens/dados que a aplicação retorna.
  
  Caso não realize a alteração do nome do JOB presente aqui nesse repositório, basta procurar por `PRE HELLO` no SDSF. Lá você pode visualizar o log e a mensagem "Hello, World" da aplicação na última linha do arquivo de log.
  
   <img width="800" alt="Hello-World" src="https://user-images.githubusercontent.com/82983123/159076705-46da1cf0-c903-46b7-8386-e66c13168fe7.png">
