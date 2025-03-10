# Bibliotecas Boost C++ 

O projeto Boost fornece bibliotecas de código fonte C++ portáteis revisadas por pares gratuitas.

Enfatizamos bibliotecas que funcionam bem com a Biblioteca Padrão C++. As bibliotecas Boost
destinam-se a ser amplamente úteis e utilizáveis ​​em um amplo espectro
de aplicações. A licença Boost incentiva o uso comercial e não comercial
e não requer atribuição para uso binário.

O site do projeto é www.boost.org, onde você pode obter mais informações e
[baixar](https://www.boost.org/users/download/) a versão atual.

## Construindo a biblioteca usando o MSVC (Microsoft Visual Studio) 2022 (Visual c++ 14.3)

### Criando a Infraestrutura de compilação para MSVC (Microsoft Visual Studio) 2022 (Visual c++ 14.3)

```cmd
bootstrap vc143
```

### Compilando as biblotecas e gerando os arquivos cabeçalhos

```cmd
.\b2 && .\b2 headers
```

### Adicionando o caminho dos aqruivos cabeçalho na variável de ambiente INCLUDE
```cmd

SET INCLUDE=%INCLUDE%;[caminho onde você baixou o código fonte da biblioteca boost]

```

### Adicionando o caminho dos binários das bibliotecas na variável de ambiente LIB
```cmd

SET LIB=%LIB%;[caminho onde você baixou o código fonte da biblioteca boost]\stage\lib

```


