# GoBarber

![img/gobarber.png](img/gobarber.png)

## Sobre

Consiste em uma plataforma para gerenciamento de atendimento em uma barbearia. Onde clientes e barbeiros podem fazer cadastro e agendar serviços.

## Tecnologias utilizadas

- Node.js para back-end
- React.js para front-end
- React-Native para mobile
- Banco de dados PostgreSQL


## Requisitos para execução dos módulos

Para executar backend, frontend e mobile é necessário ter os seguintes requisitos instalados no sistema:

- Node 12.x ou superior
- Yarn 1.21 ou superior
- PostgreSQL 11.x ou superior
- Docker 19.x ou superior (opcional)


## Executando o projeto

### Clonando o projeto

```bash
$ git clone https://github.com/felipedmsantos95/go-barber
$ cd go-barber
```

### Iniciando Backend

1. Para rodar a API pela primeira vez acessar o diretório ./backend/ e executar o comando abaixo para instalar as dependências:

```bash
$ cd backend
$ yarn
```

2. Uma vez instaladas as dependências,  se certificando que o postgreSQL esteja sendo executado, pelo comando abaixo é possível executar o backend da aplicação, por padrão ele estará disponível para requisições através da porta 3333 no endereço http://localhost:3333/:

```bash
$ yarn dev:server
```

### Iniciando Frontend

Com o backend sendo executado, pode-se executar os passos abaixo para rodar o frontend da aplicação localmente.

1. Acessar o diretório ./frontend/ e executar o comando abaixo para instalar as dependências:

```bash
$ cd frontend
$ yarn
```

2. Uma vez instaladas as dependências, pelo comando abaixo é possível executar o frontend da aplicação:

```bash
$ yarn start
```

3. Feito isso, através de um navegador de internet (preferencialmente o Chrome ou o Firefox), através do endereço abaixo, será possível interagir com a aplicação desenvolvida.

```bash
$ http://localhost:3000/
```

### Iniciando Aplicativo Mobile

Em breve.
